# Incident Handling Exercise

[Lab pdf Scenario](https://github.com/bhklimk/CS482/blob/master/labs/Incident_Handling/L.pdf)

#### Question1: What tools will you use to analyze the network trafﬁc and log ﬁles for this network event? List the tools (VMs and software) that you will use during your investigation and what each will be used for. You will likely update this list as you go through the lab.
- Wireshark, Kali, VmWare, leafpad
#### Question2: What is the IP address of the host in the 172.16.2.0/24 subnet that accessed our DNS server?
- 172.16.2.58
#### Question3: What are the ﬁrst three requests made from that host to our DNS server?

#### Question5: What is unusual about this interaction between an (external) Internet host and our DNS server?
the external host attempted and achieved a zone transfer
#### Question6: Which hosts were scanned?
#### Question7: The attacker scanned the same group of ports on each server. Which ports did the attacker include in his/her scan of these hosts?
#### Question8: Which ports did the attacker ﬁnd open (which ports accepted connection attempts)? Hint: look for evidence of a complete TCP 3-way handshake.
#### Question9: What is wrong with our ﬁrewall rules that allowed these scans to get to our DMZ network? Hint: The ﬁrewall rules are provided in ﬁrewall rules.txt.
#### Question10: What did the attacker do during his/her anonymous login? What information was the attacker able to get from the FTP server during the anonymous login? Hint: look at both the ftp and ftp-data trafﬁc (tcp ports 20 and 21).
#### Question11: What approach did the attacker take with the internal web server (what was he/she doing that could be considered malicious)? Give examples of the malicious behavior. Hint: Don’t forget the log ﬁles!
#### Question12: What information was the attacker able to gain from the internal web server that he/she could use in his/her continued attempts to compromise your network?
#### Question13: Which account does the attacker use to log in to the FTP server?
#### Question14: What password does the attacker use to log on to the FTP server? 
#### Question15: Where did the attacker get that password?
#### Question16: What ﬁles did the attacker attempt to GET from the FTP server? Question17: Which ﬁles did they successfully GET?  
#### Question18: The attacker placed some ﬁles on the FTP server. What are the names of the ﬁles the attacker tried to upload to the server?
#### Question19: Which ﬁles did he/she successfully upload? Question20: Should any rules be immediately applied to prevent further malicious activity from the suspected attacker? If so, what should the new rule(s) be?
#### Question21: Are there any other actions that you would recommend to system administrators to contain the current event? (Your answer should be speciﬁc to the incident you are investigating.)
#### Question22: Is there evidence that the attacker put something on your system that will allow him or her to easily regain access? Hint: What ﬁles did the attacker UPLOAD to your network and what might he/she be able to do with them?
#### Question23: What server would you check immediately to determine whether any unusual ports are open? Why?
#### Question24: Assuming that you ﬁnd evidence that one of your systems remains compromised after the attack, what actions do you recommend that system administrators take to remedy the compromise?
#### Question25: What conﬁguration changes must be made on our current DNS server to limit outsiders’ access to detailed information about our network?
#### Question26: The company is currently using a single DNS server to service both internal and external DNS requests. Assuming the company has sufﬁcient resources to deploy a second DNS server, in what conﬁguration should we deploy those servers to improve security? How is security improved by your recommendation?
#### Question27: What ﬁrewall rule changes do you recommend to provide better security to our DMZ? (You need not provide a speciﬁc set of rules, but you should recommend a better approach for our ﬁrewall conﬁguration and provide enough guidance so your recommendations can be implemented).
#### Question28: The only security-speciﬁc device in our network is a ﬁrewall. Are there any additional network devices that we could have placed in our network to alert systems administrators of potentially malicious activity on our network? How would such devices improve security?
#### Question29: Are there any services on the network that should be turned off to better protect data in transit? What can those potentially insecure services be replaced with to provide better security?
#### Question30: There seems to be a problem with the password policy on the network since you should have seen at least some passwords in the network trafﬁc. What is wrong with the current password and what recommendations would you make with regard to password policy to ﬁx this issue?

Application of Security Primitives - 5 points, 5 points each

NOTE: The above sections are a group effort. This section is completed by each individual. 

NOTE2: You only need to do one paragraph for this lab 

Take anyONEfound and discussed issue (vulnerability) from in this lab and explain this vulnerability in a short paragraph using at least two of the terms from the three basic security primitives discussed in lesson 2 (CIA+ Triad, 4 Elements of Defensible Systems, and the 13 Security Design Principles). Make sure you address how you would ﬁx this issue.


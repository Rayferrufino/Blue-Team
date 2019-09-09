# Title (incident HackTheBox OneTwoSeven)
#### Date : 02 Sep 2019
#### Authors: Rita Law, Hailey Hirsch, Ray Ferrufino
#### Status: Closed
#### Summary: 
A set credentials on the website 10.10.10.133 were left on the open. 
Attackers are able to accesss the sfpt server by using the credentials that were on the signup.php page. Attacker added the 10.10.10.133 ip address 
to the their/etc/host file to be able to access the directory  ```http://onetwoseven.htb/~ots-wOWM5YWM``` 
then attacker was able to navigate throught the webserver after enumarating, he was able to list and access the following directories: 
```/var/www/html-admin```  ```/var/www```
then a  .php.swp file was inside the ```/var/html``` from there the attacker was able to obtain the hardcode creds and with an hash-decoder the attacker was able to botain the username and pass and fully compromised the machine

#### Impact: Web server was compromised
#### Root Causes: 
#### Trigger:.php.swp
#### Resolution
#### Detection
# Action Items
# Lessons Learned
Never present passwords in plaintext, even if it is just being shown to the user who created the account. Disable users from accessing /etc/passwd file or any other sensitive files that only administrators should have privileges for.

#### What went well
Admin button on Homepage was disabled which disallowed login as admin. Attacker could not use SSH using SFTP credentials. Attacker did not have access to the test.php file and was prevented from uploading a remote file. Access to .php files was restricted. Uploading plugins is disabled.

#### What went wrong:
Password is displayed in plaintext when you sign up for an account. Attacker was able to read /etc/passwd file and access other sensitive files on web server. Application running on port 60080 that had a login page and credentials are hardcoded allowing password crack. Attacker was able to find and manipulate PHP code to find credentials for SFTP. Running sudo -l after gaining root access allows you to view all privileges you have access to as root.

#### Where we got lucky

# Timeline
# Supporting information

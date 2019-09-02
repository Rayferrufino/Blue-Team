# Blue-Team Notes
![Blue-Team](https://8truhw.dm.files.1drv.com/y4mSaAg5PYru4dzKg07xrxe5p7hYOk6ihHC0hsTDMh8768QoCuRPRV_X7haputhoJ7FOoAvyoQOJC73yssv23YTubOVTS8cFFplYw85ZqcaOyJBr60zEeA31W88PdGBeW2f85LBBxbjJVDBozRlI9UlD2TSGZ92zLXREFzUpG-tobvU31rbE_fvbqGB0r17G17NUHsQg1CFwVC-jGnNTFqPjg?width=650&height=269&cropmode=none)
## CIA
**Confidentialy:** ensures that unauthorized indiv are not able to gain access to sensitive info

**Integrity:** ensures that there are not unathorized modifications to info or systems 

**Availbility:** ensures that info and systems are ready to meet the needs of legitimate users

**Vulnerability:** is a weakness in a device, system , app or proccess that might allow an attack to take place

**Threat:** Outside force that may exploit a vulnerability 

**Risk:** is the combination of a threat  and a corresponding vuln. both of this factors must be present before a situation pose a risk!

***Risk= Threat X Vuln***

## NIST SP 800-30 RISK ASSESSTMENT:
1. Identify threat sources and events
2. Identify Vuln and predisposing conditions
3. Determinate likelihood of Occurence
4. Determinate Magnitude of Impact
5. Determinate Risk
  
**Identify Threats:**
  - APT
  - Accidental Threats
  - Structural Thteats
  - Environmental Threats

**Determinate Likelihood, Impact and Risk:**
  - Low, medium, high
  - Risk acceptance, risk transference, risk avoidence
  - Network Acces Control (NAC) uses 802.1x protocol
  - Supplicant= request and authenticator= on network switch or AP, use RADIUS
  
**NAC**
  - NAC criterias: Role, Location, Time of Day, System Health
  
**FIREWALLS**
  - Firewall: triple-homed means ONE firewall connects 3 networks
  
  - Type of Firewals:
    - Packet filtering: check each packet againts firewall rules 
    - Statuful Inspection: Check packets and retain info about each state of passing connections
    - NGFWs: packet check + state info + contextual imformation
    - WAFs: Protec againts SQLinjection  and CXSS scripting

**DNS SINKHOLES:** feed false info to malicious software that had compromised the network.

## NIST PENTEST
  - Planing: timing, scope, Authorization, 
  - Discovery: Port scans, checking public material, web app testers
  - Attack: Gaining access, Escalating Priv, System Brownsing, Install additional tools
  - Reporting 


**Reverse Engineering:** Decomposition

**Isolation and Sanboxing:** 
Sanboxing systems/solutions search systems and network for unknown code or strange behavior flagged as code detonation and sandbox it

**Fingerprint Software:** use of hash prevent code tampering

**Active Recon:** 
Uses host scanning tools to gather info about systems, services ,and vuln. Mapping network and discovering topology 
**NMAP:**
- Service and Version: banner grabbing (nmap -sV).
- OS Fingerprinting: nmap -O
- Nmap TCP SYN: most popular type of scan method. quick and unobtrusive


**Passive Recon:**
- Network-Logs
- Netflow: is a cisco protocol that collects IP traffic infonetowkr monitoring. 
- Netstat: gather local host network info.
- DHCP-logs and DHCP Server Configuration: quick way to identify the number of host in the network.
- Firewall-logs: for ACL
- System-logs: linux var/log

**Windows log types:** 
- Aplication logs........event logs ofr programs
- Security logs..........login events, resources and right usage 
- Setup logs.............capture setup apps
- System logs............loged events by windows components
- ForwardEvent logs......events for remote pc's

**Harvesting Data from WHOIS**

**IP to human readable** NSLOOKUP 

**Traceroute:** usuful for mapping the external network of a company

**Domain names** are managed by REGISTRARS....TDL:Top level domain.....ccTLD...country top level domain

**DIG:** useful for querying a DNS server

**ZONE TRANSFERS:** used for replicating DNS databases between DNS servers.Ex host -t axfr domain.name dns-server.

**Exif data:** tag data from photos
**Metadata scrubbing:** sensitive metadata like geolocation,timestamp creator of file

**SOCIAL ENGINEERING**
**creepy:** geolocation tool that uses social media and file metadata 
**Social Enginerring toolkit**
**Metasploit**

## DETECTING, PREVENTING AND RESPONDING TO RECON:

**NETWORK TRAFFIC ANALYSIS:**
Using IDS, HIDSs and NIDSs you can perform:
- Packet analysis
- Protocol Analysis
- Traffic and Flow analysis
- Device and System logs
- SIEM
- Security Device Log

## DATA ANALYSIS METHODS

**Anomaly Analysis:** Look for differences on common patterns or expected behaviors. System Admin set what is normal to build the threat model that IDS will use

**Trend Analysis:** Focus on predicting behaviors base on current data.

**Signature Analysis:** uses a fingerprint or signature to detec threats based on other events. the signature has to exist first before it can be detected

**Heuristic/Behavior Analysis:** detects threats based on their behavior. heuristic detection can detect unknown threats

**Manual Analysis:** human expertise and instinc can be useful when analyzing data.

## Preventing Passive Info Gathering:

- Blacklisting systems or networks that abuse service
- Using CAPTCHAs to prevent bots
- Implementing rate limit to fight lookups at high speed
- Hide zone transfer info.

# Regulatory Environments
## HIPPA
Regulates the way that healthcare providers, insurance companies and their bussiness handle protected health info.

## GLBA 
Regulates how financial institutions may handle customer financial records.

## Payment Card Industry Data Security Standard (PCI DSS)
### Regulates how companies handle credit card transactions and security controls.
- Company must run internal and external vuln scans.
- Scans must be run at least on a quaterly basis and after any **significant**  change in the network.
- Internal scans must be run by qualified personnel. 
- External scans must be run by  an Approved Scanning Vendor (ASV)

## FISMA
Requires goverment agencies and goverment contractors to comply with  a series of security standards.
### FIPS 199 Standard
![FIPS-199](https://thecybersecuritymancom.files.wordpress.com/2018/03/fips-199.png)                                        

# NIST 800-53 Security and Privacy Controls for Federal Information Systems and Organizations
|NIST 800-53 Security and Privacy Controls for Federal Information Systems and Organizations|
|-------------------------------------------------------------|
|A. Scans for vuln in the info system  and hosted applications|
|B. Employs vuln scanning tools  and techniques that facilitate interoperability among tools and automate parts of the vuln management proccess|
|C. Analyze vuln scan reports and results from security control assessments| 
|D. Remediates legitimate  vuln in accordance with an organizational assessment of risk|
|E. Shares information obtained from the vuln scanning proccess and security control assesssments to hel eliminate similar vuln in other systems |


# Scan Frequency

### Risk Appetite:
Willingness to tolerate risk within the environment.

### Regulatory requirements:
PCI DSS or FISMA may indicate a minimun frequency for vuln scans

### Technical Constraints:
may limit the frequency of scanning.Ex scannings can only be done for a certain amount per day.

### Business Constraints :
may limit the organization from conducting resource intense scans during periods of high business activity to avoid disruption of critical proccess|

### License limitations:
may curtail bandwidth consumed by the scanner.

# Scoping Vulnerability Scans

### What systems and networks will be included  in the scan ?
### Waht technical measures will be used to test wether systems are present on the network?
### What test will be performed againts systems discovered by a vulnerability scan?


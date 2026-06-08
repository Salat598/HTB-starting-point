# HTB Starting Point - Meow 
## Objective 
Just do a little bit of enumeration and get on a Linux machine.
## Tools Used 
* Nmap 
* Telnet 
* Kali Linux 

## Enumeration
 Nmap Scan
 nmap -sV 10.129.64.111
Results: 
* 23/tcp open
* Service: telnet
 ## Exploitation
Once the Telnet service was identified, a connection was made to the target machine. 
telnet 10.129.64.111
The service allowed access and gave a shell.
## Key Takeaways
 Importance of first counting
List services that are listening
Understand the security risks of Telnet
Finding files and basic Linux navigation
 ##Demonstrated Skills
Network scan
Service enumeration
Remote Access Assessment
 Linux command line use 
 
 ##What I learned
Telnet transmits data in clear text and should not be exposed to untrusted networks. Modern environments should be using SSH instead.

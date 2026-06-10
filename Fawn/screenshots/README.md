#HTB starting point- Fawn

##objective

learn the basics of file transfer protocol and anonyous login

##Enumeration

##Nmap scan

nmap -sV 10.129.71.173

##Results

Port 21/tcp open
Service: FTP

#Exploitation

Connected to FTP using anonymous login

##Lessons Learned

FTP allows file transfer between systems.
Anonymous login can be misconfigured and expose sensitive files.
Basic enumeration is essential before exploitation.

##Skills Practiced

Nmap scanning
FTP enumeration
Anonymous FTP access
File retrieval

click the link to download complete VAPT report: https://raw.githubusercontent.com/chyanil358/Metasploitable2_VAPT_report/main/metasploitable2_VAPT_report.pdf
# Metasploitable2_VAPT_report
#Internal network VAPT on metasploitable2 vulnerable machine.

## Overview
The Vulnerability Assessment and Penetration Testing (VAPT) engagement was conducted on the metasploitable2 vulnerable machine to evaluate the security posture of the internal network. This project demonstrate hands-on practice in identifying, exploiting, remedating,CVSS Scoring and reporting the security Vulnerabilities using the industry standard tools.

## Target Machine
Metasploitable2 vulnerable machine is a intensionally vulnerable operating system (server) designed to help security beginer and students practice internal network penetration testing techniques and understand common network vulnerabilities.

## Scope
The assessment focuses on identifying common network vulnerabilites including those listed in the OWASP Top 10 and ptes. Testing was performed in controlled lab environment.

## Methodology
The testing process followed a standart web application penetration testing and penetration Execution testing standard methodology.

   1. Information Gathering and service Enumeration
   2. Vulnerability Identification
   3. Exploitation
   4. Risk Assesment (cvss)
   5. Documentation and Reporting

## Vulnerabilities Identified
- Anonymous ftp login enabled
- Weak authentication in ssh service
- Clear text authentication in telnet 
- Smtp User Enumeration Enabled
- Web Server default page exposure
- RPC service Exposure
- smb/netbios service exposure inforamtion disclosure and netbios-ssn
- Smb service misconfiguration information disclosure
- Insecure Remote Command Execution 
- Clear text remote login service
- Insecure Remote shell service
- Remote code execution via java
- Unauthenticated Bind Shell Access(Backdoor Service)
- Distcc Remote Code Execution
- Weak authentication in mysql service
- Backdoor Remote Code Execution in irc
- AJP file Inclusion (Ghostcat)
- Proftpd Backdoor Command Execution ftp

## Tools used
- nmap
- Metasploit
- vncviewer
- psql
- mysql
- telnet
- rsh
- rpcinfo
- smtp-user-info
- ssh
- mount

## Report
The complete VAPT report is contaion in metasploitable2_VAPT_report.pdf.

## Screenshots
Proof of Concept screenshots are kept in screenshots folder.

## Disclaimer
The Vulnerability Assessment and Penetration Testing was conducted on the controlled lab environment.The techniques demonstrated are intended strictly for educational and ethical security research purposes.

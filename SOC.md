Security Operations Center (SOC) analysts  
Cyber Incident Response Team (CIRT)  
Computer Security Incident Response Team (CSIRT)  
... are the first responders or first line of defense responding to cybersecurity incidents. 

According to NIST  
Incident: "a violation or imminent threat of violation of computer security policies, acceptable use policies, or standard security practices."

The NIST Incident Response Process is:
1) Preparation
2) Detection and Analysis
3) Containment, Eradication and Recovery
4) Post-Incident Activity  
[NIST Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf)

According to SANS  
Incident: "an adverse event in an information system, and/or network, or the threat of the occurrence of such an event. Incident implies harm, or the intent to do harm."

The SANS Incident Response Process is:
1) Preparation: making the system resilient to attacks before an attack happens. Prepare by hardening systems, writing policies and procedures, conducting risk assessments, securing connection points, malware prevention, user awareness and training.
3) Identification: monitor log data, alerts, reports to determine if an incident has taken place and how severe it may be.
4) Containment: limit the scope and magnitude of the incident. Contain by shutting down a system, disconnecting affected system from the network, disabling certain functions.
5) Eradication: remove the cause of the incident and restore the affected system to a secure state.
6) Recovery: restoration of data from backup, rebuilding systems, installing patches, security testing.
7) Lessons Learned: what happened and how could we do better? Analysis of the incident and responses to identify whether procedures or systems could be improved.  
[SANS Incident Management White Paper](https://sansorg.egnyte.com/dl/xA2zHfNRL2)

Domain Name System (DNS): like a phonebook for the internet. DNS translates fully qualified domain names to IP addresses so browsers can load internet resources. DNS works over port 53. 
  Example is hostname www.github.com and its IP address 192.30.252.0. An IP address is given to each device on the internet. 
HTTP


<u>Protocols</u>
TCP/IP = Internet Protocol Suite
Collection of networking protocols that work to transfer data packets from one computer to another across networks.  
TCP/IP uses the client-server model of communication which is a user/computer (client) requesting a service from another computer (server) in the network.  
The suite of protocols is stateless  
4 layers of the TCP/IP Model:  
1) Application Layer: HTTP, FTP, POP3, SMTP, SNMP
2) Transport Layer: TCP and UDP
3) Network Layer: IP and ICMP
4) Physical Layer: Ethernet and ARP  
TCP uses three-way handshake to establish a connection. Client sends syn packet to server, server sends syn/ack packet to client and then client sends ack packet back to server. 

[OWASP Top 10](https://owasp.org/www-project-top-ten/)
- Broken Access Control
- Cryptographic Failures
- Injection
- Insecure Design
- Security Misconfiguration
- Vulnerable and Outdated Components
- Identification and Authentication Failures
- Software and Data Integrity Failures
- Security Logging and Monitoring Failures
- Server-Side Request Forgery

<u>Skills needed in SOC analyst role:</u>
- Excellent verbal and written communication skills
- Passion and ability to learn new tools and technologies
- Problem-solving
- Excellent collaboration and team-working skills
- Attention to detail

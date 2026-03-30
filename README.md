Project Name: Network Traffic Analysis using Wireshark

Introduction:
This project focuses on capturing and analyzing network traffic using Wireshark. The aim is to understand how data packets travel across a network and identify basic protocols like DNS, HTTP, and TCP.

Objective:
- To capture live network traffic
- To analyze different types of packets
- To understand protocol behavior

Tools Used:
- Wireshark

Methodology:
1. Installed Wireshark
2. Started packet capture on Wi-Fi interface
3. Generated traffic by browsing websites
4. Applied filters such as:
   - dns
   - http
   - tcp
5. Observed packet details
   
   Protocols Observed:
- DNS → Used for domain name resolution
- HTTP → Used for web communication

Analysis:

DNS Analysis:
- Observed DNS queries when accessing websites
- DNS converts domain names into IP addresses

HTTP Analysis:
- Observed HTTP requests and responses
- Data is visible because HTTP is not encrypted

TCP Analysis:
- Observed connection establishment (SYN, ACK)
- TCP ensures reliable communication

  Observation:
DNS request was sent to resolve google.com.
This shows how domain names are converted into IP addresses.

 Security Insight:
 - DNS traffic can be used to detect suspicious domains in cyber attacks.

Key Findings:
- Every website request starts with DNS query
- HTTP traffic is readable (not secure)
- TCP ensures packet delivery
  
Future Improvement:
- Analyze HTTPS traffic
- Detect malicious packets
- Use advanced filters
  
Conclusion:
This project helped in understanding how network communication happens and how Wireshark can be used to analyze traffic. It is useful for detecting suspicious activity in cybersecurity.



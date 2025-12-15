Task 4: Setup and Use a Firewall on Windows

Objective
To configure and test basic firewall rules to allow or block network traffic and verify the results using Nmap.

Tools Used
- Windows Defender Firewall
- Nmap 

#Steps Performed

1. Opened firewall configuration tool.
2. Listed existing firewall rules.
3. Added a firewall rule to block inbound traffic on port 23 (Telnet).
4. Scanned the target system using Nmap to verify port status.
5. Observed that port 23 was open before blocking.
6. Applied firewall rule to block port 23.
7. Re-scanned to confirm the port was filtered.
8. Documented commands and screenshots.

Nmap Command Used:
Result
- Port 23 (Telnet) was initially open.
- Firewall rule successfully blocked the port.
- Re-scan confirmed the port was filtered.

Outcome
Gained practical experience in firewall configuration, network traffic filtering, and port security.

Key Concepts
- Firewall rules
- Inbound and outbound traffic
- Port blocking
- Telnet security risks
- Network scanning using Nmap

Screenshots
Screenshots are provided in the screenshots folder as proof of configuration and testing.

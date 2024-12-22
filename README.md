# Web Server Attack Analysis Lab

## Objective

This project focused on identifying and mitigating a suspected Denial of Service (DoS) attack targeting a travel agency's web server. Using a packet sniffer, the investigation uncovered a flood of TCP SYN requests from an unfamiliar IP address, overwhelming the server and causing connection timeouts. Key tasks included taking the server offline for recovery, blocking the malicious IP address via the firewall, and preparing recommendations to prevent future attacks. This project provided hands-on experience in network traffic analysis, incident response, and implementing immediate defensive measures.

### Skills Learned

- Proficiency in using packet-sniffing tools like Wireshark to analyze network traffic and identify suspicious activity.
- Ability to detect and mitigate Denial of Service (DoS) attacks by recognizing abnormal traffic patterns.
- Experience in configuring firewalls to block malicious IP addresses and reduce attack impact.
- Knowledge of TCP/IP protocols, including identifying SYN flood attacks and their effects on web servers.
- Enhanced skills in incident response, including server recovery and communication with stakeholders.
- Practical understanding of implementing short-term and long-term solutions to strengthen network security.



### Tools Used

- Wireshark for capturing and analyzing network traffic.
- Firewall configuration tools to block malicious IP addresses.
- Packet-sniffing utilities to monitor and troubleshoot server connectivity issues.
- Documentation tools for reporting and communicating findings during incident response.


## Steps
![Screen Shot 2024-12-21 at 9 42 16 PM](https://github.com/user-attachments/assets/0127ff9c-cbd8-4de5-ad2b-8a76888e621d)

Ref 1. This screenshot shows the analysis of a suspected Denial of Service (DoS) attack on the travel agency’s web server. Using Wireshark, a high volume of TCP SYN requests from an unfamiliar IP address was detected, overwhelming the server and causing connection timeouts. Immediate actions included taking the server offline, blocking the malicious IP with the firewall, and planning further steps to prevent future attacks.

![Screen Shot 2024-12-21 at 9 43 53 PM](https://github.com/user-attachments/assets/d9d9fa04-9089-4a77-a5de-89847dd16422)

Ref 2. This screenshot displays Wireshark logs capturing a SYN flood attack, where an unusually high number of TCP SYN requests from an unfamiliar IP address overwhelm the server, leading to connection timeouts and server unresponsiveness.


![Screen Shot 2024-12-21 at 9 45 17 PM](https://github.com/user-attachments/assets/fd9d8b4f-dd27-4b7d-8820-3f6e4e4e3782)

Ref 3. The analysis concluded that the web server was targeted by a SYN flood attack, overwhelming its capacity to handle incoming traffic. Immediate action was taken to block the malicious IP and temporarily take the server offline, with further measures recommended to prevent future attacks.

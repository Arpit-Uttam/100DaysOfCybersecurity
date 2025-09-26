# Day 09 - Firewalls
## Topics
- Firewalls
- Types of Firewalls
- Need of Firewalls

## FIREWALLS
A firewall is a security device or software that monitors and controls incoming and outgoing network traffic based on predetermined security rules to protect networks and devices from unauthorized access and cyber threats.

## TYPES OF FIREWALLS
## BASED ON FUNCTION AND PLACEMENT
### PACKET FILTERING FIREWALL
The most basic type, it inspects packet headers (IP address, port number, protocol) and allows or blocks traffic based on predefined rules, without inspecting packet contents.

### STATEFUL INSPECTION FIREWALL
Monitors active connections and makes filtering decisions based on the context of traffic, not just individual packets.

### PROXY FIREWALL
Acts as an intermediary, fetching data on behalf of users while filtering out harmful content at the application layer.

### CIRCUIT-LEVEL FIREWALL
Validates whether a connection is established (e.g., TCP handshake) without examining the actual packet content.

### WEB APPLICATION FIREWALL (WAF)
Specifically protects web applications by filtering malicious web traffic like SQL injection or cross-site scripting.

### NEXT GENERATION FIREWALL (NGFW)
Combines traditional firewall features with advanced security functions such as intrusion prevention, application control, malware detection, and inspection of encrypted traffic.

## BASED ON SYSTEM PROTECTED
### NETWORK FIREWALL
Protects an entire network, usually placed at the network perimeter.

### HOST-BASED FIREWALL
Installed on individual devices (computers, servers, mobile phones) to protect only that device.

## BASED ON DATA FILTERING METHOD
### PERIMETER FIREWALL
Sits at the edge of a network, filtering inbound and outbound internet traffic.

### INTERNAL FIREWALL
Deployed inside a network to segment traffic and protect sensitive internal zones.

### DISTRIUTED FIREWALL
Security policies applied across multiple endpoints in a network, providing decentralized protection.

## NEED OF FIREWALLS 
- Firewalls block unauthorized access to network resources, preventing hacking and data theft.
- They monitor and filter network traffic, stopping malicious content and cyberattacks from entering the system.
- Firewalls protect sensitive data and maintain user privacy by creating barriers against external threats.
- They help organizations meet compliance standards and maintain secure operations.

## 💡KEY TAKEAWAYS
- Firewalls block unauthorized access and cyberattacks, serving as the frontline defense for networks and devices.
- They monitor and filter network traffic, stopping viruses, malware, and suspicious activities from reaching internal systems.
- Firewalls safeguard sensitive data and privacy, ensuring compliance with security standards and protecting business and personal information.

# Day 21 - VPN & Tunnelling Protocols
## Topics
- What is vpn
- Benefits of vpn
- Types of VPN
- Different Tunnelling & vpn Protocols
- Common Tunneling & vpn attacks

## WHAT IS VPN
A virtual private network, or VPN, is a security tool that protects your online privacy, encrypts sensitive information, and ensures secure internet access. A VPN stops hackers, ISPs, and other third parties from tracking or monitoring your online activities by establishing an encrypted tunnel between your device and the internet.

By masking your IP address and rerouting your traffic through distant servers, a VPN makes it difficult to track down your location or identity. In addition to improving data security, this enables you to access restricted content, bypass geo-restrictions, and remain anonymous online.

## BENEFITS OF VPN
1. PRIVACY PROTECTION: A VPN hides your IP address, ensuring that your browsing habits and activities remain private.
2. SECURITY ON PUBLIC NETWORKS: Public Wi-Fi networks are often insecure, but a VPN encrypts your connection, making it safer to browse the internet on networks like those in cafes or airports.
3. BYPASS GEO-RESTRICTIONS: A VPN allows you to access content that may be blocked in certain regions (such as streaming platforms, social media sites, etc.).
4. PREVENT DATA THROTTLING: Some ISPs throttle your connection speed when you stream or play games. A VPN can bypass this, allowing for faster internet speeds.
5. ACCESSING REMOTE WORK RESOURCES: A VPN enables secure access to private networks, making it ideal for businesses and remote workers.
## TYPES OF VPNs
### Remote Access VPN  
Allows individual users to securely connect to a private network from anywhere using encrypted tunnels.  
Commonly used by remote employees to access office files, emails, and internal applications.  
Uses protocols like OpenVPN, L2TP/IPsec, and IKEv2/IPsec for secure communication.  

### Site-to-Site VPN  
Connects two or more private networks, such as branch offices, over the internet.  
Routers or gateways on each side create a permanent, encrypted link.  
Ideal for organisations needing continuous inter-office communication.  

### Mobile VPN  
Designed for devices that switch between different networks like Wi-Fi and mobile data.  
Keeps the VPN session active even during connectivity changes.  
Popular among field workers and mobile staff for uninterrupted, secure access.  

### MPLS VPN  
Provider-managed VPN offering efficient data routing across a private backbone.  
Allows traffic prioritisation for critical applications.  
Preferred by large enterprises for scalability and performance.  

### PPTP VPN  
One of the oldest VPN protocols, known for simplicity and speed.  
Uses outdated encryption, making it insecure by modern standards.  
Still present in some legacy systems and hardware.  

### L2TP/IPsec VPN  
Combines Layer 2 Tunnelling Protocol for tunnelling and IPsec for encryption/authentication.  
Offers more security than PPTP but can be slower due to double encapsulation.  
Supported by most operating systems and devices.  

### OpenVPN  
Open-source, highly secure VPN protocol using SSL/TLS encryption.  
Works on any port and supports both TCP and UDP for flexibility.  
Widely used in custom VPN solutions and by commercial providers.  

### IKEv2/IPsec VPN  
Modern and secure protocol with excellent stability and speed.  
Automatically reconnects when changing networks or facing interruptions.  
Favoured for mobile devices and high-mobility environments.

## DIFFERENT TUNNELING & VPN PROTOCOLS
1. PPTP (Point-to-Point Tunnelling Protocol)
Developed by Microsoft, PPTP is an old VPN protocol that creates a simple tunnel using GRE and TCP port 1723. It allows fast connections and is widely compatible, but uses weak encryption (MPPE with RC4), making it insecure against modern attacks. It's mostly deprecated today but may still be found in legacy systems.​

2. L2TP/IPsec (Layer 2 Tunnelling Protocol with IPsec)
L2TP itself doesn’t encrypt data but creates a tunnel for encapsulating packets. Paired with IPsec, which provides strong encryption and authentication, L2TP/IPsec offers secure VPN connections. Because it double-encapsulates data, it tends to be slower but is broadly supported across platforms and good for site-to-site VPNs.​

3. OpenVPN
An open-source, highly secure protocol that leverages SSL/TLS for encryption and authentication. It supports both TCP and UDP, making it versatile and firewall-friendly. OpenVPN is robust and flexible, often preferred for remote access VPNs and custom setups, though it requires client software for configuration.​

4. IKEv2/IPsec (Internet Key Exchange version 2 with IPsec)
IKEv2 establishes a secure tunnel with the help of IPsec for encryption. It is very fast, supports automatic reconnection after network interruptions, and is stable on mobile devices. Its strong security and performance make it a popular choice for both business and personal VPNs, especially on smartphones.​

5. WireGuard
A relatively new VPN protocol designed for simplicity, speed, and security. WireGuard uses state-of-the-art cryptography and is lightweight, leading to high performance and easy auditing. It is rapidly gaining adoption for both commercial and open-source VPNs due to its efficiency.​

6. SSTP (Secure Socket Tunnelling Protocol)
Developed by Microsoft, SSTP tunnels VPN traffic inside SSL/TLS connections on TCP port 443, which helps it bypass most firewalls and network restrictions. It provides strong AES-256 encryption and is well integrated into Windows, but has limited support on other platforms.​

7. SoftEther
An open-source multi-protocol VPN solution that supports multiple protocols, including its own SSL-VPN, OpenVPN, L2TP/IPsec, and SSTP. It uses SSL to tunnel traffic, bypasses firewalls effectively, and offers strong encryption and compatibility across platforms, making it a versatile enterprise and personal VPN choice.​

8. IPSec (Internet Protocol Security)
A comprehensive suite of protocols that encrypts and authenticates IP packets. IPSec is often paired with other tunnelling protocols like L2TP or IKEv2 to secure VPN connections. It secures data at the IP layer and is heavily used for site-to-site VPNs in enterprise networks.​

9. GRE (Generic Routing Encapsulation)
A tunnelling protocol used to encapsulate many types of network layer protocols inside virtual point-to-point links. GRE itself does not provide encryption, so it's often combined with protocols like IPSec to secure data in site-to-site VPNs.​

10. TLS/SSL (Transport Layer Security / Secure Sockets Layer)
Protocols used to encrypt and secure communication over the internet. Many VPNs like OpenVPN and SSTP use TLS/SSL as the basis for creating encrypted tunnels, benefiting from widespread client support and strong cryptographic standards

## COMMON TUNNELING AND VPN ATTACKS
1. VPN Endpoint Vulnerabilities
Attackers exploit software flaws in VPN servers or appliances to gain unauthorized access or execute malicious code.​

2. Session Hijacking
Stealing or hijacking active VPN sessions due to weak session management, allowing attackers access without credentials.​

3. Credential Harvesting & Phishing
Phishing campaigns and weak credential policies lead to stolen VPN login details, enabling unauthorized network access.​

4. Man-in-the-Middle (MitM) Attacks
Intercepting VPN traffic during connection setup by exploiting improper certificate validation or weak encryption.​

5. Denial of Service (DoS) Attacks
Flooding VPN servers with traffic or exploiting protocol vulnerabilities to disrupt or crash VPN services.​

## 💡KEY TAKEAWAYS
- We need vpn day to day life because threats are increasing day by day












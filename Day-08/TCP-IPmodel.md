# Day 08 - TCP/IP Model
## Topics
- TCP/IP Model
- Importance/Relevance of TCP/IP Model

## TCP/IP MODEL
The TCP/IP model is a layered framework used for network communication, consisting of four layers: Application, Transport, Internet (Network), and Network Access (Link) layers. Each layer has its protocols and responsibilities that help in the reliable transmission of data across networks.

### APPLICATION LAYER
- Top layer of the TCP/IP model, closest to the user.
- Acts as a bridge between software applications (like web browsers, email clients, file sharing tools) and the network.
- Supports protocols such as:
  - HTTP (websites)
  - FTP (file transfers)
  - SMTP (emails)
  - DNS (domain name resolution)
- Manages data formatting to ensure both sender and receiver understand the data.
- Handles encryption for data security.
- Manages sessions to keep track of ongoing connections.

### TRANSPORT LAYER
- Ensures reliable and ordered delivery of data between devices.
- Responsible for error checking, re-sending missing data, and flow control.
- Uses two main protocols:
   - TCP (Transmission Control Protocol): Reliable, connection-oriented protocol for complete and correct data delivery (e.g., web page loading, file downloads).
   - UDP (User Datagram Protocol): Faster, connectionless protocol without guaranteed delivery (e.g., live videos, online gaming).

### NETWORK/INTERNET LAYER
- Finds the best path for data to travel across multiple networks.
- Functions like a traffic controller for data packets, moving them across networks to the correct destination.
- Key responsibilities:
    - Routing
    - Packet forwarding
    - Fragmentation (breaking large data into smaller packets)
    - Addressing with unique IP addresses (IPv4 or IPv6)
- Principal protocol: Internet Protocol (IP)

### NETWORK ACCESS LAYER
- Bottom layer of the TCP/IP model.
- Manages the physical connection and communication between devices on the same local network.
- Deals with hardware such as cables, switches, and wireless signals.
- Uses MAC addresses for device identification.
- Creates frames, the formatted units of transmission over the physical link.
- Checks for basic transmission errors.

## IMPORTANCE & RELEVANCE
1. Foundation of Internet Communication: TCP/IP is the core protocol suite that enables reliable data exchange and communication across the entire internet and other networks worldwide.

2. Interoperability Across Systems: It allows diverse hardware, operating systems, and networks to communicate seamlessly, ensuring universal compatibility.

3. Reliable and Efficient Data Transmission: TCP/IP breaks data into packets, routes them efficiently, ensures error-free delivery, and reassembles data correctly at the destination.

4. Highly Scalable and Flexible: Suitable for networks of all sizes from small LANs to massive global WANs, supporting a wide variety of protocols and communication types.
   
5. Open Standard with Continuous Evolution: TCP/IP is an open, vendor-neutral standard maintained by the Internet community, continuously evolving to include new technologies like IPv6 and enhanced security

## 💡KEY TAKEAWAYS
- It is the backbone of computer networking
- Define how data travels from one device to another

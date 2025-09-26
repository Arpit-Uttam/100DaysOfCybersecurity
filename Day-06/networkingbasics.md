# Day 06 - Computer Network Basics
## Topics
- What is Networking
- IP addresses
- DNS (Domain Name System)
- Ports

## WHAT IS NETWORKING
Computer networking is the practice of connecting two or more computing devices—such as computers, servers, printers, or smartphones—so they can communicate and share information, resources, and services.

## IP ADDRESSES
An IP address serves as a device's "home address" within a network, enabling the accurate delivery of data packets by identifying both the origin and destination of information. It consists of either numerical values (IPv4) or alphanumeric characters (IPv6), and each IP address is globally or locally unique within its network scope.

## TYPES OF IP ADDRESSES
### IPv4 VS IPv6
The two main address formats—IPv4 uses a 32-bit structure (e.g., 192.168.1.1), while IPv6 uses a 128-bit structure (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334

### STATIC VS DYNAMIC
- STATIC IP ADDRESS: Fixed and manually assigned; does not change over time
- DYNAMIC IP ADDRESS: Automatically assigned by network services like DHCP; may change over time with each connection


### PRIVATE VS PUBLIC 
- PUBLIC IP ADDRESS: Used for communication on the global internet; assigned by an ISP and can be accessed from anywhere in the world.
- PRIVATE IP ADDRESS: Used within local networks (e.g., homes, offices); not routable on the internet and helps conserve IP address space

## DNS (DOMAIN NAME SYSTEM)
DNS (Domain Name System) is a hierarchical and distributed system that translates human-friendly domain names (like google.com) into numerical IP addresses that computers use to identify each other across the network. Without DNS, users would need to remember complex strings of numbers for every website they visit. When a domain is entered in a browser, the DNS finds the appropriate IP address through a multi-step query involving local caches, DNS resolvers, root servers, TLD servers, and authoritative servers—all usually within milliseconds.

## PORTS 
Ports, in networking, are logical endpoints for managing multiple types of network traffic on a single IP address. Every IP-based network service (like HTTP, FTP, or SSH) runs on a specific port number, allowing the operating system to route incoming and outgoing data accurately. Numbers identify ports: well-known ports like 80 (HTTP), 443 (HTTPS), and 22 (SSH) are standardised for common services, while others can be dynamically assigned.

## 💡KEY TAKEAWAYS
- IP addresses are the digital addresses where ports are the entry points of any service
- All these make the flow of communication efficient

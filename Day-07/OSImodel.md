# Day 07 - The OSI Model
## Topics
- The OSI Model
- Working of the OSI Model
  
## OSI MODEL
The OSI (Open Systems Interconnection) model is a conceptual framework that standardises how communication between different computer systems over a network occurs. It divides the complex process of networking into seven distinct layers, each with specific functions, enabling interoperability and easier troubleshooting. Data moves down through these layers at the sender’s side and up through the layers at the receiver’s side. Each layer adds or removes information to ensure accurate and reliable data transmission

### APPLICATION LAYER
- Closest to the end user; enables network services for applications.
- Supports protocols used by software like HTTP, FTP, and SMTP.
- Provides resource sharing, remote file access, and user interface protocols

###  PRESENTATION LAYER
- Translates data formats between applications and the network.
- Handles encryption, decryption, compression, and data translation.
- Ensures data is in a readable format for the application layer.

###  SESSION LAYER
- Manages sessions or connections between applications.
- Establishes, maintains, and terminates communication sessions.
- Handles dialogue control and synchronisation (checkpoints, timeouts).

###  TRANSPORT LAYER
- Provides reliable data transport with segmentation, error checking, and flow control.
- Ensures complete data transfer with acknowledgements and retransmissions.
- Protocols like TCP operate here.

###  NETWORK LAYER
- Manages logical addressing and routing of packets across multiple networks.
- Breaks data into packets and determines best paths to the destination.
- Handles traffic control and packet forwarding.

###  DATA LINK LAYER
- Responsible for node-to-node data transfer and error detection/correction.
- Frames data packets and adds MAC addresses for device identification on the local network.
- Controls access to the transmission medium to avoid collision.

###  PHYSICAL LAYER
- Deals with the physical connection between devices.
- Transmits raw bits as electrical, optical, or radio signals over cables, fibre optics, or wireless.
- Manages bit synchronisation, bit rate control, physical topology, and transmission mode.
- Devices: Hubs, Repeaters, Modems, and cables.

## WORKING OF OSI MODEL
When a user sends data (e.g., an email), it starts at the Application layer, then travels down each layer, where different processing happens:
- The application prepares data.
- Presentation encrypts and formats the data.
- Session establishes a connection.
- Transport breaks data into segments and ensures reliability.
- Network routes packets.
- Data Link frames packets for local transmission.
- Physical transmits bits over the medium.
At the receiver’s end, the data moves up the layers, reversing these processes until the application receives the complete, readable information.

## KEY TAKEAWAYS
- The OSI model divides network communication into seven standardised layers, each handling a specific function.
- Data flows down from the application to the physical layer at the sender and reverses at the receiver for accurate transmission.
- The model promotes device interoperability, simplifies troubleshooting, and ensures reliable data exchange across networks

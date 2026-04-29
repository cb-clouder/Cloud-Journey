For this lesson I was asked to create an acount on DynomiteLab to view packet information such as pcap files which are usefull in monitoring network traffic. I downloaded some files from Dynamitelabs and reviewed some packet information including source and destinations, ports, and packet transport process information. 

- DynamiteLab: A web-based packet capture analysis tool.
- Packet Capture (pcap): A file that stores network traffic data collected during packet sniffing. These files can be opened with analysis tools to inspect individual packets and communication patterns.
- Packet Sniffing: The process of capturing and analyzing data packets as they travel across a network, often used for troubleshooting or monitoring traffic.

## TCP

- Transmission Control Protocol
- Part of the TRANSPORT LAYER in the TCP/IP Model
- Purpose: Making sure data is delivered accurately, in the correct order, and without duplication. 
- Supports many everyday activities, such as loading webpages, sending emails, or downloading files.
- Connection oriented. It creates a stable, two-way link between devices before any data is exchanged. This initial setup, known as the TCP handshake, is the first sign of a reliable connection.
- Uses port numbers to direct traffic to the right application on a device.
      - Port 80 is used for insecure web traffic (HTTP).
      - Port 443 is used for secure web traffic (HTTPS).
      - Port 22 is the default port for Secure Shell remote access (SSH).

## UDP 

- Faster than TCP
- Less reliable than TCP

## Successful Packet Transport Process

    (Upper Case = Client  Lowe Case = Server)

- S = SYN from client
- h = SYN-ACK from server
- A = ACK from client (completes the handshake)
- F = FIN from client (initiates termination)
- a = ACK from server (acknowledges the FIN)
- f = FIN from server (completes termination)

## Terms to Know:

- Flow Control: A method used by TCP to prevent the sender from overwhelming the receiver by adjusting how much data can be sent at a time.
- Congestion: A network condition where too much data is transmitted at once, causing delays or dropped packets because devices or links are overloaded.
- TCP Handshake: The initial setup process (SYN, SYN-ACK, and ACK) that creates a reliable, two-way connection between devices before data is exchanged.
- Synchronize (SYN): A TCP segment sent by a client to request a connection and share its starting sequence number.
- Synchronize-Acknowledge (SYN-ACK): A TCP segment sent by a server that acknowledges the client’s SYN and provides its own sequence number.
- Acknowledge (ACK): A TCP segment used to confirm the receipt of a SYN or other data, completing the handshake and supporting reliable communication.
- Port Number: A numerical identifier that directs traffic to the correct application on a device, such as port 80 for HTTP or port 443 for HTTPS.
- Source Port: A port number chosen by the client to identify its side of a TCP connection.
- Destination Port: A port number used by the server’s service to receive traffic and match it to the correct application.
- Successful Finish (SF): A state in packet capture analysis that shows a TCP handshake completed successfully and the session ended normally.
- Rejected Connection (REJ): A state in packet capture analysis that shows a TCP handshake attempt was refused, usually because no service was listening on the destination port.


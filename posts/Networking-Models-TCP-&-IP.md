## Networking Models- TCP/IP 

Whenever you send a message, stream a video, or load a webpage, your device follows an organized process that determines how information moves from one place to another. These processes are described by networking models. Conceptual frameworks that explain how digital communication happens behind the scenes.
- The TCP/IP model, created alongside early U.S. Department of Defense networking research, organizes communication into four layers. It is the model used in real-world networks. A four-layer networking model that defines how data is transmitted across the Internet.
- The OSI model is a seven-layer conceptual framework used for teaching and troubleshooting. A seven-layer teaching model used to describe communication processes in greater detail.
- Network Stack: The collection of protocols on a device that work together to support network communication.

## TCP/ICP Model (4 layers)
- Link Layer: manages local delivery within the same network
- Internet Layer: handles addressing and long-distance routing
- Transport Layer: ensures successful delivery of information
- Application Layer: provides the services that apps rely on

## Layer #1 - Link
Think of it as your local post office, the place where your letter begins its journey. Just as your neighborhood post office decides when mail can be accepted, organizes it, and prepares it for regional transport, the Link Layer manages communication within a single local network.

- MAC addresses: A hardware identifier used for communication within a local network. Similar to unique house numbers in your neighborhood.
- Network Interface Cards (NICs): A hardware component that enables a device to connect to a network and send or receive data. Like the mailboxes where letters are dropped off and collected.
- Frames: A structured unit of data used for local network communication. Act like envelopes that carry information between nearby devices.
- Ethernet: A protocol used for wired local communication.
- Wi-Fi: A protocol used for wireless local communication.

## Layer #2 - Internet
- Usees the Internet Protocol (IP)
- IP Address: A unique number that identifies each device on a network.
- Internet Protocol (IP): Rules for addressing and routing information between networks.

## Layer #3 - Transport
- TCP: A protocol that ensures accurate, complete, and ordered delivery of information. Every piece is checked. Missing pieces are resent. Delivery is confirmed. Ideal for tasks like loading web pages or sending files.
- UDP: A fast, lightweight protocol that does not guarantee delivery or order. Ideal for video calls, streaming, and gaming

## Layer #4 - Application
This layer provides the tools that applications use to request or deliver information across a network. Some of the most common services include:
- Simple Mail Transfer Protocol (SMTP): A protocol for sending outgoing email.
- Internet Message Access Protocol (IMAP): A protocol that lets users access and manage email stored on a server.
- Post Office Protocol version 3 (POP3): A protocol that downloads email to a local device.
- HyperText Transfer Protocol (HTTP): A protocol used by web browsers to request and display web pages.
- HTTP Secure (HTTPS): A secure version of HTTP that encrypts communication.
- Domain Name System (DNS): A service that translates website names into IP addresses.
- File Transfer Protocol (FTP): A protocol used to upload or download files.

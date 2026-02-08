# The-Internet-Protocols
This repository contains screenshots and basic analysis of network traffic captured using Wireshark. It demonstrates filtering and examining HTTP, TCP, and UDP packets, including HTTP requests and responses, TCP connection and data transfer, and UDP packet details. This work was completed as part of a networking lab assignment.
## 📸 Screenshots and Descriptions

### Pic 1 – HTTP Packet Filtering
[![Pic 1](Screenshot 2026-02-08 165100.png)](Screenshot 2026-02-08 165100.png)  
Shows Wireshark with the `http` display filter applied, displaying only HTTP packets captured during web browsing activity.

### Pic 2 – HTTP Stream Analysis
[![Pic 2](pic2.png)](pic2.png)  
Shows the result of using **Follow → HTTP Stream**, displaying the complete HTTP communication between the client and server, including request and response messages.

### Pic 3 – HTTP Protocol Details
[![Pic 3](pic3.png)](pic3.png)  
Displays the **Hypertext Transfer Protocol** section expanded, showing HTTP request and response details such as method, host, and status code.

### Pic 4 – TCP Packet Filtering
[![Pic 4](pic4.png)](pic4.png)  
Shows Wireshark with the `tcp` display filter applied, isolating TCP packets for connection analysis.

### Pic 5 – TCP Protocol Details
[![Pic 5](pic5.png)](pic5.png)  
Displays the **Transmission Control Protocol** section expanded, showing TCP header fields including sequence and acknowledgment numbers.

### Pic 6 – TCP Data Transfer Packets
[![Pic 6](pic6.png)](pic6.png)  
Shows TCP packets filtered using `tcp.len > 0`, indicating packets that carry actual data during the TCP connection.

### Pic 7 – UDP Packet Filtering
[![Pic 7](pic7.png)](pic7.png)  
Shows Wireshark with the `udp` display filter applied, displaying only UDP packets generated during the capture.

### Pic 8 – UDP Protocol Details
[![Pic 8](pic8.png)](pic8.png)  
Displays the **User Datagram Protocol** section expanded, showing source port, destination port, packet length, checksum, and payload information.

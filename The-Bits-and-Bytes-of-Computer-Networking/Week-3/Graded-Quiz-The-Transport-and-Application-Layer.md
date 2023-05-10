``` 
  # Do not copy if you are taking the test.
``` 
--- 
 
# The Transport and Application Layer    
##### Graded Quiz. • 1h 10m. • 10 total points 
----- 


### 01.  Nodes on a network have the ability to direct traffic toward many different receiving services. What provides this ability in the transport layer?
    
- [ ]  File Transfer    
- [ ]  Multiplexing    
- [ ]  Socket address    
- [ ]  Demultiplexing    


### 02.  Which field in a Transmission Control Protocol (TCP) header is chosen from ephemeral ports?
    
- [ ]  Sequence number    
- [ ]  Destination port    
- [ ]  Acknowledgement number    
- [x]  Source port   


### 03.  The sequence of SYN, SYN/ACK, and ACK packets is known as the _________.
    
- [ ]  two-way handshake    
- [ ]  four-way handshake    
- [ ]  high five    
- [x]  three-way handshake   


### 04.  If a TCP socket is ready and listening for incoming connections, it's in the ______ state.
    
- [ ]  CLOSE_WAIT    
- [ ]  SYN_SENT    
- [ ]  ESTABLISHED    
- [x]  LISTEN    


### 05.  Connection-oriented protocols protect against dropped data by forming connections and using a constant stream of what?   
    
- [ ]  Recognition    
- [x]  Acknowledgements    
- [ ]  Verifiers    
- [ ]  Approvals   


### 06.  In the OSI network model, the ________ is responsible for making sure that the unencapsulated application layer data is actually able to be understood by the application in question.
    
- [ ]  application layer    
- [ ]  session layer    
- [ ]  presentation layer    
- [ ]  data layer   


### 07.  You are sending a very small amount of information that you need the listening program to respond to immediately. Which Transmission Control Protocol (TCP) flag will be used?
    
- [ ]  ACK    
- [ ]  URG    
- [ ]  RST    
- [ ]  PSH    


### 08.  Application layer data lives in the _____ section of the transport layer protocol.
    
- [ ]  footer    
- [ ]  header    
- [ ]  flags    
- [x]  payload    


### 09.  A user requests an unencrypted webpage from a web server running on a computer, listening on the Internet Protocol address 10.1.1.150. What will be the socket address?
    
- [ ]  10.1.1.150.80    
- [ ]  10.1.1.150:21    
- [ ]  10.1.1.150.21    
- [x]  10.1.1.150:80    


### 10.  A 32-bit number that's used to keep track of where you are in a sequence of TCP segments is known as a(n) ______ number.
    
- [ ]  address    
- [x]  sequence    
- [ ]  TCP    
- [ ]  acknowledgement    


-----------------------
## (Alternative Questions) 

### 01.  The transport layer handles multiplexing and demultiplexing through what type of device?
    
- [ ]  Routers    
- [ ]  Switches    
- [x]  Ports    
- [ ]  Hubs   


### 03.  A Transmission Control Protocol (TCP) connection is established and two devices ensure that they're speaking the same protocol. What has occurred?
    
- [ ]  Handwaving    
- [ ]  Two-way handshake    
- [ ]  Four-way handshake    
- [x]  Three-way handshake   


### 04.  A Transmission Control Protocol (TCP) connection is in working order and both sides can send each other data. What is the TCP socket state?
    
- [x]  ESTABLISHED    
- [ ]  SYN_RECEIVED    
- [ ]  LISTEN    
- [ ]  SYN_SENT    


### 05.  If the checksum doesn't compute for a packet sent at the Internet Protocol (IP) level, what will happen to the data?
   
- [x]  The data will be discarded   
- [ ]  It will be sent, but may be out of order.   
- [ ]  The data will be sent back to the sending node with an error.   
- [ ]  The data will be resent   


### 06.  The OSI network model has _____ layers.
    
- [ ]  five    
- [x]  seven    
- [ ]  six    
- [ ]  eight   


### 07.  Which Transmission Control Protocol (TCP) flag is used to make sure the receiving end knows to examine the sequence number field?   
    
- [x]  SYN    
- [ ]  PSH    
- [ ]  RST    
- [ ]  FIN    


### 08.  HTTP is an example of a(n) ______ layer protocol.
    
- [ ]  data-link    
- [x]  application    
- [ ]  transport    
- [ ]  network     


### 09.  Ports that are generally used to establish outbound connections are known as ______ ports.   
    
- [ ]  reserved    
- [ ]  system    
- [x]  ephemeral     
- [ ]  registered    


### 10.  A communication between two devices is over the maximum limit of an ethernet frame size. The Transmission Control Protocol (TCP) splits up the data into segments. Which field in the header helps keep track of the many segments?    
     
- [ ]  Urgent pointer     
- [ ]  Acknowledgement number     
- [x]  Sequence number     
- [ ]  Checksum   



-----------------
## (More Alternative Questions)  


### 01.  The concept of taking traffic that’s all aimed at the same node and delivering it to the proper receiving service is known as _________.
     
- [x]  demultiplexing     
- [ ]  encapsulation     
- [ ]  routing     
- [ ]  multiplexing    


### 02.  Which field in a Transmission Control Protocol (TCP) header provides the next expected segment?
     
- [ ]  Data offset     
- [ ]  Sequence number     
- [x]  Acknowledgement number     
- [ ]  Checksum     


### 03.  The sequence of SYN, SYN/ACK, and ACK packets is known as the _________.
     
- [ ]  four-way handshake     
- [ ]  high five     
- [x]  three-way handshake     
- [ ]  two-way handshake     


### 04.  A Transmission Control Protocol (TCP) connection is in working order and both sides can send each other data. What is the TCP socket state?
    
- [ ]  SYN_SENT    
- [ ]  SYN_RECEIVED    
- [ ]  LISTEN    
- [x]  ESTABLISHED    


### 05.  A communication sent through Transmission Control Protocol (TCP) arrives out of order. What allows the data to be put back together in the correct order?   
    
- [x]  Sequence numbers    
- [ ]  Acknowledgement number    
- [ ]  Checksum    
- [ ]  Preamble    


### 07.  One side in a Transmission Control Protocol (TCP) connection has not been able to properly recover from a series of malformed segments. Which Transmission Control Protocol (TCP) flag will be used?
   
- [ ]  FIN   
- [ ]  PSH   
- [x]  RST   
- [ ]  SYN


### 09.  What port does the File Transfer Protocol (FTP) typically listen on?   
   
- [ ]  443   
- [ ]  80   
- [ ]  25    
- [x]  21   





--- 
> [The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking/) {Week-2} 

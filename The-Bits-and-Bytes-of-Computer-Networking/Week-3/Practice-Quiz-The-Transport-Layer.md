```
  # Do not copy if you are taking the test.
```
--- 

# The Transport Layer   
##### Practice Quiz • 8 min • 5 total points 
----- 


### 01.  What ordering of TCP flags make up the Three-Way Handshake?
    
- [ ]  SYN, ACK, SYN, ACK    
- [ ]  SYN, ACK, FIN    
- [ ]  FIN, FIN/ACK, ACK    
- [x]  SYN, SYN/ACK, ACK  

> The computer that wants to establish a connection sends a packet with the SYN flag set. Then, the server responds with a packet with both the SYN and ACK flags set. Finally, the original computer sends a packet with just the ACK flag set.


### 02.  Transport layer protocols, like TCP and UDP, introduce the concept of a port. How many bits are in a port field?
    
- [ ]  4    
- [x]  16    
- [ ]  32    
- [ ]  8   

> A TCP port and a UDP port are both 16-bit numbers, meaning there are theoretically 65,535 possible values it can have.


### 03.  A device that blocks traffic that meets certain criteria is known as a ________.
    
- [x]  Firewall    
- [ ]  Switch    
- [ ]  Hub    
- [ ]  Router   

> A firewall is used to block certain defined types of traffic.


### 04.  Which TCP flag is used to make the listening program respond immediately?
    
- [ ]  ACK    
- [ ]  URG    
- [ ]  RST    
- [x]  PSH   

> When the Push (PSH) flag is set, the transmitting device wants the receiving device to push currently buffered data to the application on the receiving end as soon as possible.


### 05.  _________are identified as ports 49152 through 65535.
    
- [ ]  Sockets    
- [ ]  System ports    
- [x]  Ephemeral ports    
- [ ]  User ports   

> Ephemeral Ports are identified as ports 49152 through 65535. Ephemeral ports are used as temporary ports for private transfers.
    

--- 
> [The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking/) {Week-3} 

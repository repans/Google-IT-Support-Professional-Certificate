``` 
  # Do not copy if you are taking the test.
``` 
--- 
 
# The Five-Layer Network Model    
##### Graded Quiz. • 2h . • 10 total points 
----- 


Use the following scenario to answer the 10 questions below: 

You have 3 networks (A, B, and C) and 2 routers (Y and Z). 

Network A has an address space of 10.1.1.0/24 and is connected to router Y, using the interface 10.1.1.1.

Network B has an address space of 192.168.1.0/24 and is connected to Router Y, using the interface 192.168.1.254. Network B is also connected with router Z, using the interface of 192.168.1.1. 

Network C has an address space of 172.16.1.0/24 and is connected to router Z, using the interface 172.16.1.1. The diagram below represents these connections and interfaces.

![network](https://github.com/repans/Google-IT-Support-Professional-Certificate/assets/89868933/e3e9d0da-e5e5-4abf-928e-63a41235bfc2)


### 01.  Computer 1 on network A, with the IP address of 10.1.1.8, wants to send a packet to Computer 2, with the IP address of 10.1.1.10. On which network is computer 2?
    
- [ ]  Network B    
- [ ]  Not present    
- [x]  Network A    
- [ ]  Network C     


### 02.  What information is computer 1 looking at in the ARP table on Router Y?
    
- [ ]  TTL value    
- [ ]  Destination MAC address    
- [x]  MAC address    
- [ ]  Port number


### 03.  Which layer constructs the IP datagram?
    
- [ ]  Application layer    
- [x]  Network layer    
- [ ]  Data layer    
- [ ]  Physical Layer


### 04.  What information is in the payload section of the TCP segments?
    
- [ ]  Handshake    
- [ ]  The MAC address of Computer 1    
- [x]  The application layer data    
- [ ]  ART Table


### 05.  When constructing the Ethernet datagram to send the packet from computer 1 to its gateway (Router Y), what information needs to be in the destination MAC address?
    
- [ ]  Computer 2’s MAC address    
- [x]  Router Y’s MAC address    
- [ ]  Router Z’s MAC address    
- [ ]  Computer 1’s MAC address


### 06.  Computer 1 on Network A sends a packet to Computer 2 on Network C. What's the last step that Router Z does after receiving the Ethernet frame?
    
- [x]  Strips away the Ethernet frame, leaving the IP datagram. Performs a checksum calculation against the entire datagram     
- [ ]  Sends back the packages to router Y for confirmation    
- [ ]  Calculates a checksum and compares this checksum with the one in the Ethernet frame header    
- [ ]  Decrements the TTL by 1, calculates a new checksum, and makes a new IP datagram. This new IP datagram is again encapsulated on a new Ethernet frame.


### 07.  Computer 1 on network A, with IP address of 10.1.1.10, wants to send a packet to Computer 2, with IP address of 192.168.1.14. If the TTL value was set to 64 at the beginning, what is the value of the TTL once it reaches its destination?
    
- [x]  63    
- [ ]  61    
- [ ]  0    
- [ ]  65


### 08.  Computer 1 on network B, with IP address of 192.168.1.121, wants to send a packet to Computer 2, with IP address of 10.1.1.8. Taking in consideration that computer 1 is sending a request to a web server on computer 2, listening on port 80, and the source port on computer 1 is 5000, which of the following contains the correct information for the first TCP segment of data?
    
- [x]   Source Port: 5000    
        Destination Port: 80    
        Sequence Number: 1    
        Acknowledgment Number: 2    
    
- [ ]   Source Port: 80    
        Destination Port: 5000     
        Sequence Number: 1    
        Acknowledgment Number: 1     
    
- [ ]   Source Port: 80    
        Destination Port: 5000    
        Sequence Number: 1    
        Acknowledgment Number: 2     
    
- [ ]   Source Port: 8081   
        Destination Port: 50    
        Sequence Number: 4   
        Acknowledgment Number: 1    


### 09.  Computer 1 on network B, with IP address of 192.168.1.121, wants to send a packet to Computer 2, with IP address of 172.16.1.57. Which of the following has the correct IP datagram information for the fields: Version, minimum Header Length, Source IP, and Destination IP?
    
- [ ]   Version: 4    
        Header Length: 32   
        Source IP Address: 10.1.1.1   
        Destination IP address: 172.16.1.1     
    
- [ ]   Version: 5     
        Header Length: 16   
        Source IP Address: 10.1.1.0/24.   
        Destination IP address: 10.1.1.0/23.     
    
- [ ]   Version: 6    
        Header Length: 20   
        Source IP Address: 8a:1a:2b:3c:4d:5f     
        Destination IP address: 2a:2b:3c:4d:8f       
     
- [x]   Version: 4    
        Header Length: 20     
        Source IP Address: 192.168.1.121    
        Destination IP address: 172.16.1.57    


### 10.  When referring to RJ45, we are referring to ________.
    
- [x]  cable plug    
- [ ]  network identification    
- [ ]  router velocity    
- [ ]  ethernet port     


--- 
> [The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking/) {Week-3} 

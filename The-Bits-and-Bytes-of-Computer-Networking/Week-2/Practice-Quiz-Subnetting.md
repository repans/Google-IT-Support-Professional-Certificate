```
  # Do not copy if you are taking the test.
```
--- 

# Subnetting   
##### Practice Quiz • 6 min • 5 total points 
----- 


### 01.  What does CIDR stand for?
    
- [ ]  Classful Interlink-Destination Routing    
- [ ]  Class Interconnect Destination Routing    
- [ ]  Classful Identification Routing    
- [x]  Classless Inter-Domain Routing  


### 02.  Which of the following is a correct form of CIDR notation?
    
- [ ]  192.168.1.0\24    
- [ ]  192.168.1.0:24    
- [x]  192.168.1.0/24    
- [ ]  192.168.1.0 + 255.255.255.0   
> CIDR notation uses a forward slash and then lists the numbers of bits in the subnet mask. 

### 03.  How many octets does a subnet mask have?
    
- [ ]  2    
- [ ]  3    
- [ ]  1    
- [x]  4   


### 04.  Consider the following scenario:

Your IP address is 192.168.8.34, and your subnet mask is 255.255.0.0. What part of the subnet mask represents the subnet ID?
    
- [x]  The first two octets of the subnet mask, 255.255    
- [ ]  The last two octets of the subnet mask, 0.0    
- [ ]  255.255.0.1    
- [ ]  192.168.0.254  
> The first two octets are all ones in binary (11111111,11111111). This tells the router that the first two octets of the IP address are the subnet ID.

### 05.  How many possible host IDs do you always lose per network?
    
- [ ]  12    
- [ ]  8    
- [ ]  4    
- [x]  2   
  
> You always lose two host IDs per network. For example, the subnet mask of 255.255.255.0 has the last octet available for host IDs (256 potential hosts). But remember, zero is generally not used, and 255 is normally reserved as a broadcast address.This means that, really, only the numbers 1-254 are available for assignment to a host. 
        

--- 
> [The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking/) {Week-2} 

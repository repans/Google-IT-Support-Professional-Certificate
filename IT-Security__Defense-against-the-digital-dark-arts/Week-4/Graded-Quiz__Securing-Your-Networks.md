```
  # Do not copy if you are taking the test.
```
--- 

# Securing Your Networks    
##### Graded Quiz • 34 min • 10 total points 
----- 

### 01. What does tcpdump do?    
- [ ] Brute forces password databases
- [ ] Handles packet injection
- [ ] Generates DDoS attack traffic
- [x] Performs packet capture and analysis   
> tcpdump captures and analyzes packets for you, interpreting the binary information contained in the packets and converting it into a human-readable format.


### 02. What can protect your network from DoS attacks?
- [ ] DHCP Snooping
- [x] Flood Guard
- [ ] Dynamic ARP Inspection
- [ ] IP source Guard    
> Flood guards provide protection from DoS attacks by blocking common flood attack traffic when it's detected.  


### 03. What occurs after a Network Intrusion Detection System (NIDS) first detects an attack? 
- [x] Triggersalerts 
- [ ] Disables network access 
- [ ] Blocks traffic 
- [ ] Shuts down   
> A NIDS only alerts when it detects a potential attack.   


### 04. What does a Network Intrusion Prevention System (NIPS) do when it detects an attack? 
- [x] It blocks the traffic. 
- [ ] It does nothing. 
- [ ] It attacks back. 
- [ ] lt triggers an alert.   
> An NIPS would make adjustments to firewall rules on the fly, and drop any malicious traffic detected.  


### 05. How do you protect against rogue DHCP server attacks?  
- [ ] Dynamic ARP Inspection  
- [ ] IP Source Guard 
- [x] DHCP Snooping  
- [ ] Flood Guard   
> DHCP snooping prevents rogue DHCP server attacks. It does this by creating a mapping of IP addresses to switch ports and keeping track of authoritative DHCP servers. 


### 06. What underlying symmetric encryption cipher does WEP use?     
- [ ] RSA   
- [ ] AES   
- [x] RC4   
- [ ] DES  


### 07. What traffic would an implicit deny firewall rule block?   
- [ ] Outbound traffic only   
- [ ] Nothing unless blocked   
- [ ] Inbound traffic only   
- [x] Everything that is not explicitly permitted or allowed


### 08. What allows you to take all packets from a specified port, port range, or an entire VLAN and mirror the packets to a specified switch port?   
- [ ] DHCP Snooping   
- [ ] Promiscuous Mode   
- [x] Port Mirroring   
- [ ] Network hub   
> Port mirroring allows you to capture traffic on a switch port transparently, by sending a copy of traffic on the port to another port of your choosing.   


### 09. What kind of attack does IP Source Guard (IPSG) protect against?   
- [ ] DoS attacks   
- [ ] Rogue DHCP Server attacks   
- [x] IP Spoofing attacks   
- [ ] ARP Man-in-the-middle attacks   
> IP Source Guard protects against IP spoofing. It does this by dynamically generating ACLs for each switch port, only permitting traffic for the mapped IP address for that port.    


### 10. What can be configured to allow secure remote connections to web applications without requiring a VPN?   
- [x] Reverse proxy   
- [ ] RC4    
- [ ] Web browser   
- [ ] NIDS   


--- 
> [IT Security: Defense against the digital dark arts](https://www.coursera.org/learn/it-security/) {Week-4} 

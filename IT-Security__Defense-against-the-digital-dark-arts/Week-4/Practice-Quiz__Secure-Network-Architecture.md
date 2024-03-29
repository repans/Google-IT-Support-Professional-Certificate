```
  # Do not copy if you are taking the test.
```
--- 

# Secure Network Architecture   
##### Practice Quiz • 14 min • 7 total points 
----- 

### 1. Why is normalizing log data important in a centralized logging setup?   
- [ ] Log normalizing detects potential attacks.   
- [x] Uniformly formatted logs are easier to store and analyze.  
- [ ] The data must be decrypted before sending it to the log server.   
- [ ] Itsdifficult to analyze abnormal logs.   
> Logs from various systems may be formatted differently. Normalizing logs is the practice of reformatting the logs into a common format, allowing for
easier storage and lookups in a centralized logging system.


### 2. What type of attacks does a flood guard protect against? Check all that apply. |
- [ ] Malware infections   
- [x] DDoS attacks    
- [ ] Man-in-the-middle attacks   
- [x] SYN floods   
> A flood guard protects against attacks that overwhelm networking resources, like DoS attacks and SYN floods.


### 3. What does DHCP Snooping protect against?
- [ ] Data theft   
- [x] Rogue DHCP server attacks   
- [ ] DDoS attacks   
- [ ] Brute-force attacks.   
> DHCP snooping is designed to guard against rogue DHCP attacks. The switch can be configured to transmit DHCP responses only when they come from the DHCP server's port.   


### 4. What does Dynamic ARP Inspection protect against?
- [x] ARP poisoning attacks    
- [ ] Rogue DHCP server attacks    
- [ ] DDoS attacks    
- [ ] Malware infections     
> Dynamic ARP inspection protects against ARP poisoning attacks by watching for ARP packets. If an ARP packet doesn't match the table of MAC address and IP address mappings generated by DHCP snooping, the packet will be dropped as invalid or malicious.  


### 5. What does IP Source Guard protect against?   
- [ ] DDoS attacks    
- [ ] Brute-force attacks   
- [x] IP spoofing attacks    
- [ ] Rogue DHCP server attacks   
> Right on! IP Source Guard prevents an attacker from spoofing an IP address on the network. It does this by matching assigned IP addresses to switch ports,and dropping unauthorized traffic. 


### 6. What does EAP-TLS use for mutual authentication of both the server and the client? |
- [ ] Biometrics   
- [ ] One-time passwords   
- [ ] Usernames and passwords   
- [x] Digital certificates   
> The client and server both present digital certificates, which allows both sides to authenticate the other, providing mutual authentication.  


### 7. Why is it recommended to use both network-based and host-based firewalls? Check all that apply.
- [x] For protection against compromised hosts on the same network   
- [x] For protection for mobile devices, like laptops   
- [ ] For protection against man-in-the-middle attacks   
- [ ] For protection against DDoS attacks    
> Using both network- and host-based firewalls provides protection from external and internal threats. This also protects hosts that move between trusted and untrusted networks, like mobile devices and laptops.   


--- 
> [IT Security: Defense against the digital dark arts](https://www.coursera.org/learn/it-security/) {Week-4} 

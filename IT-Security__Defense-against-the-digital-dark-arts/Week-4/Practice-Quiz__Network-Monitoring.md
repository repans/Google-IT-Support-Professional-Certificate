```
  # Do not copy if you are taking the test.
```
--- 

# Network Monitoring    
##### Practice Quiz • 10min • 5 total points 
----- 
### 1. What does tcpdump do?
- [x] Captures packets
- [ ] Generates packets
- [x] Analyzes packets and provides a textual analysis
- [ ] Encrypts your packets
> Tcpdump is a popular, lightweight command line tool for capturing packets and analyzing network traffic. 


### 2. What does Wireshark do differently from tcpdump?
- [ ] It can write packet captures to a file
- [x] It has a graphical interface
- [ ] It can capture packets and analyze them
- [x] It understands more application-level protocols
> tcpdump is a command line utility, while wireshark has a powerful graphical interface. While tcpdump understands some application-layer protocols, wireshark expands on this with a much larger complement of protocols understood.


### 3. What factors should you consider when designing an IDS installation?
- [x] Traffic bandwidth
- [x] Storage capacity
- [ ] Internet connection speed 
- [ ] OS types in use 
> It's important to understand the amount of traffic the IDS would be analyzing. This ensures that the IDS system is capable of keeping up with the volume of traffic. Storage capacity is important to consider for logs and packet capture retention reasons.


### 4. What is the difference between an Intrusion Detection System and an Intrusion Prevention System?
- [ ] They are the same thing.
- [ ] An IDS can detect malware activity on a network, but an IPS can't
- [x] An IDS can alert on detected attack traffic, but an IPS can actively block attack traffic.
- [ ] An IDS can actively block attack traffic, while an IPS can only alert on detected attack traffic.
> An IDS only detects intrusions or attacks, while an IPS can make changes to firewall rules to actively drop or block detected attack traffic.


### 5. What factors would limit your ability to capture packets?
- [x] Network interface not being in promiscuous or monitor mode
- [ ] Anti-malware software
- [ ] Encryption
- [x] Access to the traffic in question
> If your NIC isn't in monitor or promiscuous mode, it'll only capture packets sent by and sent to your host. In order to capture traffic, you need to be able to access the packets. So, being connected to a switch wouldn't allow you to capture other clients' traffic. 


--- 
> [IT Security: Defense against the digital dark arts](https://www.coursera.org/learn/it-security/) {Week-4} 

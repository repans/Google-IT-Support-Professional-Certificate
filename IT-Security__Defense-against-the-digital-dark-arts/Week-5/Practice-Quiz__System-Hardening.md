```
  # Do not copy if you are taking the test.
```
--- 

# System Hardening    
##### Practice Quiz • 20 min • 10 total points 
----- 

### 01. What is an attack vector?   
- [x] A mechanism by which an attacker can interact with your network or systems     
- [ ] The classification of attack type   
- [ ] The direction an attack is going in   
- [ ] The severity of the attack   
> An attack vector can be thought of as any route through which an attacker can interact with your systems and potentially attack them.


### 02. Disabling unnecessary components serves which purposes? Check all that apply.   
- [x] Closing attack vectors   
- [x] Reducing the attack surface   
- [ ] Making a system harder to use   
- [ ] Increasing performance   
> Every unnecessary component represents a potential attack vector. The attack surface is the sum of all attack vectors. So, disabling unnecessary components closes attack vectors, thereby reducing the attack surface.


### 03. What's an attack surface?    
- [ ] The total scope of an attack   
- [ ] The target or victim of an attack   
- [ ] The payload of the attack    
- [x] The combined sum of all attack vectors in a system or network   
> The attack surface describes all possible ways that an attacker could interact and exploit potential vulnerabilities in the network and connected systems.


### 04. A good defense in depth strategy would involve deploying which firewalls?   
- [ ] Host-based firewalls only    
- [x] Both host-based and network-based firewalls   
- [ ] Network-based firewalls only    
- [ ] No firewalls    
> Defense in depth involves multiple layers of overlapping security. So, deploying both host- and network-based firewalls is recommended. 


### 05. Using a bastion host allows for which of the following? Select all that apply.    
- [x] Having more detailed monitoring and logging     
- [x] Enforcing stricter security measures    
- [x] Applying more restrictive firewall rules      
- [ ] Running a wide variety of software securely   
> Bastion hosts are special-purpose machines that permit restricted access to more sensitive networks or systems. By having one specific purpose, these systems can have strict authentication enforced, more firewall rules locked down, and closer monitoring and logging.


### 06. What benefits does centralized logging provide? Check all that apply.    
- [ ] It prevents database theft.   
- [x] It helps secure logs from tampering or destruction.   
- [ ] It blocks malware infections.   
- [x] It allows for easier logs analysis.   
> Centralized logging is really beneficial, since you can harden the log server to resist attempts from attackers trying to delete logs to cover their tracks. Keeping logs in place also makes analysis on aggregated logs easier by providing one place to search, instead of separate disparate log systems.   


### 07. What are some of the shortcomings of antivirus software today? Check all that apply. 
- [ ] It only detects malware, but doesn't protect against it. 
- [ ] It only protects against viruses. 
- [ ] It's very expensive. 
- [X] It can't protect against unknown threats. 
> Antivirus software operates off a blacklist, blocking known bad entities. This means that brand new, never-before-seen malware won't be blocked.   


### 08. How is binary whitelisting a better option than antivirus software?
- [ ] It's cheaper.
- [ ] It's not better. It's actually terrible.
- [X] It can block unknown or emerging threats.
- [ ] It has less performance impact.
> By blocking everything by default, binary whitelisting can protect you from the unknown threats that exist without you being aware of them.   


### 09. What does full-disk encryption protect against? Check all that apply.
- [X] Tampering with system files
- [ ] IP spoofing attacks
- [ ] Malware infections
- [X] Data theft
> With the contents of the disk encrypted, an attacker wouldn't be able to recover data from the drive in the event of physical theft. An attacker also wouldn't be able to tamper with or replace system files with malicious ones.    


### 10. What's the purpose of escrowing a disk encryption key?
- [ ] Preventing data theft
- [ ] Protecting against unauthorized access
- [X] Performing data recovery
- [ ] Providing data integrity
> Key escrow allows the disk to be unlocked if the primary passphrase is forgotten or unavailable for whatever reason.   


--- 
> [IT Security: Defense against the digital dark arts](https://www.coursera.org/learn/it-security/) {Week-5} 

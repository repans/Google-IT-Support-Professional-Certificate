```
  # Do not copy if you are taking the test.
```
--- 

# Logging   
##### Practice Quiz • 8 min • 5 total points 
----- 

### 1. If you were investigating login issues on a Windows computer, which portion of the Event Viewer logs would be a good place to start your investigation?

- [ ] Security
- [ ] System
- [x] Application and Services

> The Security log would be a good place to start when troubleshooting login issues.


### 2. In what log files can you find information about bootup errors? Select all that apply.

- [ ] /var/log/auth.log
- [ ] /var/log/mail.log
- [x] /var/log/syslog
- [x] /var/log/kern.log

> You can find log information about bootup issues in kern.log and the syslog.


### 3. In what log files can you find information about authentication errors?

- [ ] /var/log/mail.log
- [ ] /var/log/kern.log
- [ ] /var/log/syslog
- [x] /var/log/auth.log

> The auth.log file contains authentication log messages.


### 4. For an ssh connection to work, which of the following need to be true? Check all that apply.

- [x] The SSH server is running on the host you want to connect to.  
- [x] You need to specify a hostname to SSH into.  
- [ ] VPN needs to be set up.  
- [x] SSH is installed on client.

> To SSH into a remote host, you'll need all of these things setup.


### 5. What command do you use to view error logs in real time?

- [ ] -kill
- [x] Tail -f
- [ ] /var/log/auth.log
- [ ] Less var/log/syslog

>`tail -f` is used to view error logs in real time.


--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-6} 

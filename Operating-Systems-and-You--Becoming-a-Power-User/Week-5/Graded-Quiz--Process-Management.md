```
  # Do not copy if you are taking the test.
```
--- 

# Process Management   
##### Graded Quiz • 30min • 10 total points 
----- 

### 1. You launch notepad.exe from a Powershell command line. Which of the following is true?

- [ ] The notepad.exe process is the parent process for Powershell.
- [ ] The Powershell process will terminate when the notepad.exe process terminates.
- [x] The Powershell process is the parent process for notepad.exe.
- [ ] The notepad.exe process will terminate when the Powershell process terminates.


### 2. When a process completes its task, what happens? Select all that apply.

- [ ] The process goes into a suspended state.
- [ ] The process releases all the resources it was using to its parent.
- [x] The process releases all the resources it was using back to the kernel.
- [x] The process terminates automatically.


### 3. Which of the following process information can you find in Windows Task Manager? Select all that apply.

- [ ] What time the process started
- [x] What application or image the process is running
- [x] The memory resources the process is using
- [x] The CPU resources the process is using


### 4. When using the ps -x command to check the status of a process in Linux, how would you know if a process is suspended (stopped)?

- [ ] There is a letter R under the STAT field.
- [x] There is a letter T under the STAT field.
- [ ] There is a letter S under the COMMAND field.
- [ ] There is a letter S under the STAT field.


### 5. What is the default action of the SIGINT signal?

- [ ] To restart the process that is signaled
- [ ] To put the process that is signaled into a sleep state
- [ ] To suspend the process that is signaled
- [x] To terminate the process that is signaled


### 6. You launch notepad.exe from a PowerShell command prompt. Later, you use Process Explorer to restart the notepad.exe process? After restart, what is the parent process of notepad.exe?

- [x] Process Explorer (procexp.exe)
- [ ] smss.exe
- [ ] PowerShell (powershell.exe)
- [ ] notepad.exe


### 7. In Linux, what signal is sent when you enter the kill pid command?

- [ ] SIGINT
- [ ] SIGTSTP
- [x] SIGTERM
- [ ] SIGKILL

> Correct

### 8. What happens to background apps while a foreground app is in use on iOS and Android?

- [ ] The background apps will take turns running in the background to use less processing power.
- [x] The OS will suspend background mobile apps.
- [ ] The background apps continue to run normally.
- [ ] The OS will terminate the background apps.


### 9. In Windows, what information is displayed by the Resource Monitoring tool? Select all that apply.

- [x] Information about particular resources on the system (like CPU, Memory, and Network usage)
- [ ] System hardware properties
- [x] Process information along with data about the resources that the process is consuming
- [ ] Information about current time and how long your system’s been running


### 10. Which of the following Linux commands lists open files and what processes are using them?

- [ ] top  
- [x] lsof  
- [ ] ps -ef  
- [ ] uptime   



--------------------------
## (Alternative Questions) 


### 1. Which of the following statements are true about child processes in Windows? Select all that apply.
   
- [x] A child process can be terminated by clicking on the X button in the top right corner of the application.
- [ ] A child process is dependent on its parent process until the child process is terminated.
- [ ] A child process can be terminated by running the taskkill /pid command in the CLI.
- [x] A child process inherits environment variables and settings from its parent.

### 2. In the following Linux command, which is the parent process and which is the child?

```bash
$ less /etc/myfile | grep Hello
```
   
- [ ] The parent is grep and the child is less.   
- [ ] The parent is /etcand the child is myfile.    
- [x] The parent is less and the child is grep.   
- [ ] The parent is less and the child is /etc/myfile.   


### 3. Which of the following methods can be used to get information on processes that are running in Windows? Select all that apply.

- [x] From the PowerShell prompt, use the Get-Process commandlet.
- [x] From the CLI, use the tasklist command.
- [x] Use the Windows Task Manager.
- [ ] From the CLI, use the ps command.


### 4. When using the ps -x command to check the status of a process in Linux, how would you know if a process is suspended (stopped)?

- [ ] There is a letter S under the STAT field.
- [ ] There is a letter R under the STAT field.
- [ ] There is a letter S under the COMMAND field.
- [x] There is a letter T under the STAT field.


### 5. Which of the following statements are true about SIGINT? Select all that apply.

- [x] It is a signal that exists in both Windows and Linux.
- [ ] It can be sent at the CLI by typing the sigint command.
- [x] It is an interrupt signal that can be sent to a process that is running.
- [x] It can be sent at the CLI by pressing the CTRL+C keys.


### 6. You launch notepad.exe from a PowerShell command prompt. Later, you use Process Explorer to restart the notepad.exe process? After restart, what is the parent process of notepad.exe?

- [ ] smss.exe
- [ ] PowerShell (powershell.exe)
- [ ] notepad.exe
- [x] Process Explorer (procexp.exe)


### 7. In Linux, what signal is sent when you enter the kill pid command?

- [ ] SIGINT
- [ ] SIGTSTP
- [ ] SIGKILL
- [x] SIGTERM


### 8. In iOS and Android, what’s the first thing you should try when troubleshooting a misbehaving app?

- [ ] Close apps, one at a time, starting with the foreground app.
- [ ] Close apps, one at a time, starting with the least recently used app.
- [ ] Uninstall apps, one at a time, starting with the least recently used app.
- [x] Check for an app that is using a lot of battery.


### 9. Which of the following Powershell commands will sort processes by amount of non-paged memory, in descending order?

- [ ] Get-Process| Sort CPU -descending | Select -property ID, ProcessName
- [ ] Get-Process| Sort -property ID, ProcessName
- [ ] Get-Process| Sort WS -ascending | Select -property ID, ProcessName
- [x] Get-Process| Sort NPM -descending | Select -property ID, ProcessName


### 10. What does the top command do in Linux? Select all that apply.

- [x] It provides a snapshot of total tasks currently running or idling.
- [x] It provides information on process CPU and memory usage.
- [ ] It lists the top ten largest files on the system.
- [x] It lists the top processes that are using the most resources on a machine.




--------------------------
## (More Alternative Questions) 


### 1. When Windows boots up, what is the first non-kernel process that starts?

- [ ] Powershell.
- [x] The smss.exe process
- [ ] The csrss.exe process.
- [ ] The winlogon process.

### 2. When a process completes its task, what happens? Select all that apply.

- [x] The process terminates automatically.
- [ ] The process releases all the resources it was using to its parent.
- [x] The process releases all the resources it was using back to the kernel.
- [ ] The process goes into a suspended state.

### 3. How do you find a process PID number in Windows Task Manager?

- [ ] Select a process from the process list.
- [ ] Click on the Processes tab.
- [x] Click the Details tab.
- [ ] Task Manager will not show PID numbers (you have to use the tasklist command or the Get-Process commandlet).


### 4. Which of the following methods will provide information on processes that are running in Linux? Select all that apply.

- [x] List the contents of the /proc directory.
- [x] Use the ps -x command.
- [ ] Use the ls command.
- [ ] List the contents of the /etc directory.


### 5. Which of the following statements are true about SIGINT? Select all that apply.

- [x] It is an interrupt signal that can be sent to a process that is running.
- [x] It is a signal that exists in both Windows and Linux.
- [x] It can be sent at the CLI by pressing the CTRL+C keys.
- [ ] It can be sent at the CLI by typing the sigint command.


### 7. What are the two most common ways to terminate a process in Linux at the CLI? Select two options.

- [x] Use the kill pid command.
- [ ] Use the terminate process command.
- [ ] Use the end process command.
- [x] Use the kill -KILL pid command.


### 10. Which of the following Linux commands shows information about the current time, how long your system's been running, how many users are logged on, and what the load average of your machine is?

- [x] uptime
- [ ] lsof
- [ ] ps -ef
- [ ] top


--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-5} 

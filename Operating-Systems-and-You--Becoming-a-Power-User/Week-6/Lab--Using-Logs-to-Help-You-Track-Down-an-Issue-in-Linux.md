```
  # Do not copy if you are taking the test.
```
--- 

# Using Logs to Help You Track Down an Issue in Linux    
##### Graded Lab • 1h • 50 total points 
----- 


Here are the steps needed to be done in that lab:

## Task 1: Low disk space    

Recommendations: Go through the lab instructions in order to solve this objective. 

--------- 

## Task 2: Finding and deleting files

Error log: 

> May 30 15:47:11 a432deuf8994 root: Qwiklab Error: There is a corrupted file found in /home/lab/corrupted_file. Remove this file.


To solve this error we have to delete/remove file with: 

```bash
rm /home/lab/corrupted_file
```

-------
## Task 3: Updating software that's out-of-date

We have an error regarding vlc update: 
> May 30 15:47:11 a432deuf8994 root: Qwiklab Error: VLC - Package out of date, upgrade to the latest version.

Open a terminal and run the following commands:

1. Update the package lists:
    
    ```bash
    sudo apt update
    ```
    
2. Upgrade the installed packages, including VLC:
    
    ```bash
    sudo apt upgrade vlc
    ```
    

If there is an update available for VLC, it will be downloaded and installed. After the process is complete, VLC will be updated to the latest version available in the Debian repositories.

Note that you may need to enter your password when prompted for sudo privileges. 

In case if you got into an error that indicates that there are unmet dependencies preventing the installation or upgrade of VLC. You can try running the suggested command **`apt --fix-broken install`** to resolve the dependency issues.

Open a terminal and run the following command:

```bash
sudo apt --fix-broken install
```

This command will attempt to fix any broken dependencies by installing the necessary packages or resolving conflicts. Once the process is complete, you can retry the VLC upgrade command:

```bash
sudo apt upgrade vlc
```

If the issue persists or if there are still unmet dependencies, you may need to manually resolve them by installing the missing packages or finding alternative solutions. 

---------------

## Task 4: Finding and terminating specific processes

Error log: 
>  May 30 15:47:11 a432deuf8994 root: Qwiklab Error: Process: [bash /home/totally_not_malicious] is malicious, terminate the process immediately!


To terminate a running Bash process with the name **`/home/totally_not_malicious`**, you can use the **`kill`** command followed by the process ID (PID) of the process. Here are the steps:

1. First, you need to find the PID of the Bash process. You can use the **`pgrep`** command to search for the process ID based on the process name. Run the following command:
    
    ```bash
    pgrep -f "/home/totally_not_malicious"
    ```
    
    This will display the PID of the matching process.
    
2. Once you have the PID, you can use the **`kill`** command with the PID to terminate the process. Run the following command, replacing **`<PID>`** with the actual PID you obtained in the previous step:
    
    ```bash
    sudo kill <PID>
    ```
    
    In my case, PID was 315. So I used: 
    
    ```bash
    sudo kill 315
    ```
    
    This will send a termination signal to the process, causing it to terminate.
    

Please note that terminating a process abruptly can result in data loss or other unintended consequences. Make sure you are terminating the correct process and that it is safe to do so.

-------- 


## Task 5: Modifying file permissions

Error log: 
> May 30 15:47:11 a432deuf8994 root: Qwiklab Error: Permission Denied: /home/lab/super_secret_file.txt


To change the permissions of a file in Linux, you can use the **`chmod`** command. Here's an example of how to change the permissions of the file **`/home/lab/super_secret_file.txt`**:

```bash
chmod <permissions> /home/lab/super_secret_file.txt
```

Replace **`<permissions>`** with the desired permission settings. The permissions are represented by a combination of letters and symbols that specify read (r), write (w), and execute (x) permissions for the owner, group, and others.

For example, if you want to give execute, read and write permissions to everyone i.e. want to make it public (777):

```
chmod 777 /home/lab/super_secret_file.txt
```

Make sure you have appropriate permissions or use **`sudo`** to execute the **`chmod`** command if you encounter a "Permission denied" error.




--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-6} 

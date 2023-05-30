```
  # Do not copy if you are taking the test.
```
--- 

# Using Logs to Help You Track Down an Issue in Windows    
##### Graded Lab • 1h • 50 total points 
----- 

Here are the steps needed to be done in that lab:

### Task 1: Low disk space    

Recommendations: Go through the lab instructions in order to solve this objective. 

---------

### Task 2: For Corrupted File -      
 
 **Method 1:** Go to `C:\Users\directory`, in my case it was `C:\Users\corrupted_file` and delete the corrupted file.       
 **Method 2:** Delete it from powershell with following command:       
 ```
 Remove-Item -Path "C:\Users\corrupted_file" -Force
 ```

----------

### Task 3: Update VLC

**Method 1:** Update from powershell with `choco`    
```
choco upgrade vlc -y
```

**Method 2:** Please open Google chrome, and search for VLC download and click on the first link to download and install VLC then click on check my progress. 

---------

### Task 4: End malicious processes   

**Method 1:** Do it from powershell    
```
Stop-Process -Name totally_not_malicious -Force
```

**Method 2:** Open Windows search bar and type Task manager, and then search for totally_not_malicious(32bit) in the processes tab. Right click on it and press the End task. 

----------

### Task 5: Fix Permissions 

Go to C`:\Users\directory\Temp` (in my case it was `C:\Users\Temp`) where file `super_secret_file.txt` is present. Right-click on the text file. Go to Security, Click on the edit button to change the permission. In the Permissions for Everyone, click on the checkbox in front of Write to Allow the permission on the file. Click on Apply, then click on OK. 

--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-6} 

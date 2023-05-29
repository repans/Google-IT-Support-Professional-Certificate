```
  # Do not copy if you are taking the test.
```
--- 

# Filesystem Types   
##### Practice Quiz • 30min • 9 total points 
----- 

### 1. Which of the following is a characteristic of the FAT32 filesystem? Check all that apply.

- [x] It's read and write compatible with Windows, Mac, and Linux OSes.
- [ ] It supports files up to 8GB in size.
- [x] Its filesystem size can't be larger than 32GB.
- [ ] It doesn't support files larger than 4GB. 
 
> The FAT32 filesystem is great for cross-platform compatibility, but has lots of limitations that don't make it useful for large data storage. 
  
  
### 02. What’s the difference between a GPT and MBR partition table? Check all that apply.

- [x] MBR only allows you to have volume sizes of 2TBs or less.
- [x] GPT allows you to have volume sizes of 2TBs or greater.
- [x] GPT allows you to have a large number of partitions.
- [ ] MBR is the new standard for partition tables.
 
> MBR works with volumes up to 2TB. 
> GPT offers a much greater maximum volume than MBR. 
> GPT, the newer partitioning standard, offers nearly unlimited partitions.  


### 03. Before you can store files on a hard drive, which of the following has to be done? Check all that apply.

- [x] Partition the disk
- [x] Mount the filesystem.
- [ ] Nothing: hard drives can be used to store files out of the box.
- [x] Format a filesystem. 

> Before you can start using a hard drive to store files, you’ll need to partition the disk, format a filesystem, then mount the filesystem. 


### 04. What is the name of the tool that ships with Windows and lets you partition a disk and format a file system?

- [ ] NTFS
- [ ] Allocation Unit Size
- [ ] Volume label:
- [x] The Disk Management Utility 

> The Disk Management Utility is a Windows tool that lets you partition and format a disk. 


### 05. What does Windows OS use to provide the physical memory available in the computer to applications running on the computer?

- [ ] NTFS
- [x] Virtual memory
- [ ] GUID
- [ ] Disk partitioning

> Virtual memory is what the OS uses to provide physical memory available in the computer to applications running on the computer.  


### 06. What’s the terminal-based tool you can use to manage disks right from the command line?

- [ ] Fsutil
- [x] Diskpart
- [ ] Mkdir
- [ ] Chkdsk

>  Diskpart is a terminal based tool built for managing disks right from the command line.


### 07. Which of the following commands in Windows will create a symbolic link called "cauliflower" to a file named "broccoli.txt?"
 
- [x] mklink cauliflower broccoli.txt
- [ ] mklink /H cauliflower broccoli.txt
- [ ] mklink broccoli.txt cauliflower

> Diskpart is a terminal based tool built for managing disks right from the command line. 


### 08. In Linux, what's the difference between the commands df and du? Check all that apply.

- [ ] du is used to undelete files in a directory.
- [x] du is used to find the amount of disk usage on a specific directory.
- [x] df is used to find the amount of free space on an entire machine.
- [ ] df is used to delete files in a directory. 

> The df, or disk free, command is used to find the amount of free space on an entire machine, while the du, or disk usage, command is used to find the disk usage on a specific directory. 


### 09. In Linux, what's the difference between a hardlink and a symlink (Symbolic Link)? Check all that apply.

- [x] A symlink points to a filename.
- [x] If you change the original name of the file, a hard link will still work. 
- [ ] A symlink adds an entry to the MFT that points to the linked file number instead of the   
- [x] A hardlink points to a linked file number. 

> Symlinks are used to point to filenames, while hardlinks point to linked file numbers. 
> Symlinks are used to point to filenames, while hardlinks point to linked file numbers. 






--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-4} 

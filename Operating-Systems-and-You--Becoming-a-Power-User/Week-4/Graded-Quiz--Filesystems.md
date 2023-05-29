```
  # Do not copy if you are taking the test.
```
--- 

# Filesystems   
##### Graded Quiz • 30min • 10 total points 
----- 


### 01. What happens when you format a filesystem on a partition?

- [ ] Your machine switches between operating systems.
- [ ] You mount a new physical storage device.
- [ ] You eject a storage device.
- [x] The partition becomes a volume.



### 02. What is the maximum volume size for an MBR partition?

- [ ] 1024 megabytes.
- [ ] Two gigabytes.
- [x] Two terabytes.
- [ ] One terabyte.


### 03. The Windows Disk Management Utility provides which of the following? Select all that apply.

- [x] A utility to make modifications to the disk and partitions on a computer
- [x] Information about a computer's disks and disk partitions, as well as their file systems
- [ ] A command line interface
- [x] Information about the free and total capacity of disks and partitions on a computer


### 04. In Linux, when running parted in interactive mode, what happens when you enter the command mklabel gpt?

- [ ] You mount a partition on the selected disk.
- [x] You specify a partition table type for the selected disk.
- [ ] You rename the selected disk.
- [ ] You specify the file system format for a partition on the selected disk.


### 05. When managing memory, where does the operating system keep the most commonly accessed data pages?

- [x] In RAM
- [ ] On the hard drive
- [ ] In a special hidden file on the root partition of a volume called page file dot sys
- [ ] In the cloud


### 06. In Linux, when running parted in interactive mode, what happens when you enter the command mkpart primary linux-swap 5GiB 100%? Select all that apply.

- [ ] You enable swap on the selected device.
- [x] You create a new disk partition.
- [ ] You mount a swap partition.
- [x] You format a disk partition for swap space.


### 07. How does a shortcut link to another file?

- [ ] By referencing the other file's reference number
- [ ] By referencing the other file's location on the hard drive
- [ ] By referencing the other file's name
- [x] By referencing a copy of the other file



### 08. What is the Linux equivalent to Window's Master File Table (MFT)?

- [ ] ipod table
- [ ] ilink table
- [x] inode table
- [ ] ipath table


### 09. Which of the following are common risks for file corruption?

- [x] System failures
- [x] Sudden computer shut offs
- [ ] Hitting the eject button in the OS
- [x] Software bugs


### 10. Some versions of Linux will automatically run fsck on your computer to check for issues and attempt to auto-repair the file system. In these cases, when will your system automatically run fsck?

- [x] Any time you boot your computer.
- [ ] At whatever time you schedule your system to run fsck.
- [ ] Only when you update your Linux kernel.
- [ ] Only when the operating system sets a bit in a metadata file that indicates there's corruption.


--------------------------
## (Alternative Questions) 



### 01. What happens when you format a filesystem on a partition?

- [x] The partition becomes a volume.
- [ ] Your machine switches between operating systems.
- [ ] You mount a new physical storage device.
- [ ] You eject a storage device.


### 02. How many GPT partitions can you have on a disk?

- [ ] Five
- [ ] Sixteen
- [ ] Four
- [x] As many as you want


### 03. When partitioning a disk and formatting a filesystem, what happens if you choose the "full format" option? Select all that apply.

- [x] The formatting process will take longer.
- [x] Windows will scan the target drive for errors and bad sections.
- [ ] The formatting process will complete in less time.
- [ ] The allocation unit size will be larger.


### 04. In Linux, what information will be displayed about a computer’s disks when the sudo parted -l command is executed in the CLI? Select all that apply.

- [x] The sizes of the disk partitions    
- [ ] The security permissions for each partition    
- [x] The number of partitions on each of the computer’s disks    
- [x] The partition table types for each disk     


### 05. Fill in the blank: Virtual memory dedicates an area of the hard drive to use a storage base for blocks of data called _____.

- [ ] base storage
- [x] pages
- [ ] databases
- [ ] RAM


### 06. What is a swap file or swap space?

- [ ] An online forum for swapping files
- [ ] A file that acts as a drive partition
- [x] A dedicated area of the hard drive used for virtual memory
- [ ] An Exchange file


### 07. What is the identifier that indexes a file's entry in the MFT?

- [x] The file record number
- [ ] The volume
- [ ] The filename
- [ ] The creation timestamp


### 08. What is the Linux equivalent to symbolic links in Windows?

- [x] softlinks
- [ ] inodes
- [ ] hardlinks
- [ ] filenames


### 09. Which features of Windows NTFS filesystem help minimize file corruption?

- [x] The NTFS log journaling process
- [x] The fsutil self-healing utility
- [x] The chkdsk /F command
- [ ] The fsck command


### 10. Some versions of Linux will automatically run fsck on your computer to check for issues and attempt to auto-repair the file system. In these cases, when will your system automatically run fsck?

- [ ] Only when the operating system sets a bit in a metadata file that indicates there's corruption.
- [ ] Only when you update your Linux kernel.
- [x] Any time you boot your computer.
- [ ] At whatever time you schedule your system to run fsck.


----------------------
## (More Alternatives)


### 06. In Linux, what happens when you enter the command sudo swapon /dev/sdb1?

- [ ] You format a disk partition for swap space.
- [ ] You create a new disk partition.
- [x] You enable swap on the selected device.
- [ ] You mount a swap partition. 


### 07. What file attributes are stored in the Master File Table (MFT)? Select all that apply.

- [x] File creation time stamps
- [x] File data locations
- [ ] Language used in the file data
- [x] Whether or not a file is read-only


### 09. Which of the following commands will run the check disk utility and fix any problems it finds?

- [ ] chkfix 
- [x] chkdsk /F
- [ ] fsck 
- [ ] chkdsk



--- 
> [Operating Systems and You: Becoming a Power User](https://www.coursera.org/learn/os-power-user/) {Week-4} 

# Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

---

## 3.a) Installation and Configuration of Oracle VirtualBox

### Aim:
To install and configure Oracle VM VirtualBox.

### Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space

### Steps:

1. **Download Oracle VM VirtualBox:**
   - Visit [Oracle VirtualBox Official Site](https://www.virtualbox.org/)
   - Download installer for your OS (Windows/macOS/Linux).

2. **Install Oracle VM VirtualBox (Example: Windows):**
   - Launch Installer → Allow Changes → Click `Next`.
   - Choose Installation Options → Click `Next`.
   - Accept Network Interface Warning → Click `Yes`.
   - Click `Install`.
   - Finish Installation and Launch VirtualBox.

3. **Configure VirtualBox:**
   - Open VirtualBox.
   - Click `New` → Name VM → Select Type (Linux/Windows) and Version.
   - Allocate:
     - Minimum 2 GB RAM
     - Create Virtual Hard Disk (20 GB recommended).
   - Start Virtual Machine and provide ISO to install OS.

### Result:
Thus, Oracle VM VirtualBox was installed successfully.

---

## 3.b) Installation and Configuration of Kali Linux

### Aim:
To install and configure Kali Linux in Oracle VirtualBox.

### Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image

### Steps:

1. **Download Kali Linux ISO:**
   - Visit [Kali Linux Official Site](https://www.kali.org/get-kali/)
   - Download 64-bit ISO (Installer version).

2. **Create a New Virtual Machine:**
   - Open VirtualBox → Click `New`.
   - Name: "Kali Linux" → Type: `Linux` → Version: `Debian (64-bit)`.

3. **Allocate Memory:**
   - Minimum 2 GB RAM (recommended 4 GB).

4. **Create Virtual Hard Disk:**
   - Select `VDI (VirtualBox Disk Image)`.
   - Choose `Dynamically allocated`.
   - Set Disk size to 20 GB or more.

5. **Configure ISO Image:**
   - Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6. **Start Installation:**
   - Boot Virtual Machine → Choose `Graphical Install`.
   - Set Language, Region, Keyboard.
   - Configure Network → Set Hostname (e.g., kali).
   - Set root password.
   - Disk Partitioning: Use entire disk → All files in one partition.
   - Install System → Install GRUB Bootloader → Finish Installation.

7. **Login to Kali Linux:**
   - Use root credentials.

8. **(Optional) Install Guest Additions:**
   - Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

### Snapshots:
<p align="center">
  <img src="https://github.com/user-attachments/assets/24d2c3a3-a4ce-4398-95ad-1188da101cee" alt="AWS Account Creation Snapshot" width="600"/>
</p>
<p align="center"><strong>Snapshot 1: Installing Oracle VirtualBox</strong></p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/ac1c369e-f183-4516-bf2c-37e3990d6b85" alt="AWS Account Creation Snapshot" width="600"/>
</p>
<p align="center"><strong>Snapshot 2: Adding Kali Linux (Guest OS)</strong></p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/7f0e91a7-7ec8-4a83-80a3-4fdc1c58755e" alt="AWS Account Creation Snapshot" width="600"/>
</p>
<p align="center"><strong>Snapshot 3: Kali Running in VirtualBox</strong></p>

### Result:
Thus, Kali Linux guest OS was installed and configured successfully.

---

## 3.c) Execution of Linux Commands in Kali

### About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are **case-sensitive**.

### Linux Commands:

#### 1. ls Command
The ls command is used to display a list of content of a directory.
##### Syntax: ls
![image](https://github.com/user-attachments/assets/302cb3d1-f87b-4ade-984b-3c47615e6e14)

#### 2. pwd Command
The pwd command is used to display the location of the current working directory.
##### Syntax: pwd
![image](https://github.com/user-attachments/assets/479ff722-c8b0-43bf-8c30-e8fba51e87d3)


#### 3. mkdir Command
The mkdir command is used to create a new directory under any directory.
##### Syntax: mkdir <directory_name>
![image](https://github.com/user-attachments/assets/03499d49-3bec-4a7e-bbe2-ab9f117427ce)

#### 4. rmdir Command
The rmdir command is used to delete a directory.
##### Syntax: rmdir <directory_name>
![image](https://github.com/user-attachments/assets/f80d31c8-5b6a-4405-a07d-f50cdecb08e2)


#### 5. cd Command
The cd command is used to change the current directory
##### Syntax: cd <directory_name>
![image](https://github.com/user-attachments/assets/e4938600-497b-437a-853c-d5463665af4b)


#### 6. cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.
##### Syntax: cat [options] [file_name]
![image](https://github.com/user-attachments/assets/4dc47b9c-0c93-424e-b510-b7987ac70bb6)


#### 7. cp Command
The cp command is used to copy a file or directory.
##### Syntax: cp <source> <destination>
![image](https://github.com/user-attachments/assets/3f427704-a426-4607-81be-d96ba959e884)


#### 8. gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.
##### Syntax: gedit <file_name>
![image](https://github.com/user-attachments/assets/f5fd4e50-9e63-47f5-86fd-ae79362d572a)


#### 9. su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.
##### Syntax: su <user_name>
![image](https://github.com/user-attachments/assets/6f1ea072-5273-4726-8afe-74b1a87f245f)


#### 10. mv Command
The mv command is used to move a file or a directory form one location to another location.
##### Syntax: mv <source> <destination>
![image](https://github.com/user-attachments/assets/10c5f737-36bb-42b9-9f83-e5f41416444c)


#### 11. rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.
##### Syntax: rename 's/old/new/' files
![image](https://github.com/user-attachments/assets/8913107c-7f2e-484a-984d-47eefb3537a8)


#### 12. head Command
The head command displays the first 10 lines of a file.
##### Syntax: head <file_name>
![image](https://github.com/user-attachments/assets/eae1eb08-bf41-4e14-a1fb-00b80f95cee8)


#### 13. tail Command
The tail command displays the last 10 lines of a file.
##### Syntax: tail <file_name>
![image](https://github.com/user-attachments/assets/63202571-4cb9-4504-b630-d69ee8d9f340)


#### 14. id Command
The id command is used to display user and group IDs.
##### Syntax: id
![image](https://github.com/user-attachments/assets/7b13b813-e420-482b-add6-edc1daae703d)

#### 15. grep Command
The grep command searches for a pattern inside files.
##### Syntax: command | grep <pattern>
![image](https://github.com/user-attachments/assets/f59c1786-72ff-4e90-b682-12ceb1b4da05)


#### 16. tr Command
The tr command translates or deletes characters.
##### Syntax: command | tr 'old' 'new'
![image](https://github.com/user-attachments/assets/84cbd7e7-b31b-4092-bc98-e2350e5d70e7)


#### 17. chmod Command
The chmod command is used to change file permissions.
##### Syntax: chmod <permissions> <file_name>

#### 18. tar Command
The tar command is used to create or extract archive files.
##### Syntax: tar [options] [archive-file] [file]

#### 19. chown Command
The chown command changes the ownership of a file or directory.
##### Syntax: chown <owner> <file_name>
![image](https://github.com/user-attachments/assets/e4e3b35c-4258-4ddd-b6dc-c5b1da9dba9c)


#### 20. make Command
The make command is used to build and manage projects automatically.
##### Syntax: make [options] [target]
![image](https://github.com/user-attachments/assets/2114b2e0-642d-4b13-9915-a5e0cf10f86e)


#### 21. ifconfig Command
The ifconfig command is used to configure network interfaces.
##### Syntax: ifconfig [options] [interface]
![image](https://github.com/user-attachments/assets/328a7ca8-138c-4fd9-96d9-c8e664b1790c)


#### 22. chmod 777 Command
The chmod 777 command gives full permissions to everyone for a file or folder.
##### Syntax: chmod 777 <file/folder_name>
```$chmod -R 777 /path/to/file/or/folder```

#### 23. host Command
The host command is used to perform DNS lookup.
##### Syntax: host <domain_name_or_ip>
![image](https://github.com/user-attachments/assets/9482f6b9-947f-4635-a139-c0c26957e845)


#### 24. gzip Command
The gzip command compresses files to save space.
##### Syntax: gzip <file_name>
![image](https://github.com/user-attachments/assets/22035351-cdc4-436d-8a84-7ebf043efb2d)


#### 25. sort Command
The sort command sorts lines of a text file alphabetically or numerically.
##### Syntax: sort <file_name>
![image](https://github.com/user-attachments/assets/233243ef-3c74-4bbc-bbd8-5b03e756b1b2)


#### 26. cal Command
The cal command displays a calendar in the terminal.
##### Syntax: cal
![image](https://github.com/user-attachments/assets/f9acb87f-f6c4-40e8-952a-9f03a4748d86)


#### 27. clear Command
The clear command clears the terminal screen.
##### Syntax: clear
![image](https://github.com/user-attachments/assets/37fa7f39-2715-47fe-99dd-f27f6f43e320)


#### 28. mail Command
The mail command is used to send emails from the terminal.
##### Syntax: mail -s "subject" recipient_email
![image](https://github.com/user-attachments/assets/107f71e1-e9f3-45ef-8a19-f5907e790ae9)


#### 29. df Command
The df command displays the amount of available disk space.
##### Syntax: df
![image](https://github.com/user-attachments/assets/4131f8f2-b16a-4ebd-8d5b-e330874aaa78)


#### 30. find Command
The find command is used to search for files and directories.
##### Syntax: find . -name "*.file_extension"


### Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.

---

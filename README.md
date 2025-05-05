# Introduction
## What is an OS?
An **OS** (Operating System) is the core software that sits between your computer’s hardware and applications. 
It manages resources (CPU, memory, storage, I/O), provides a user interface, and offers common services 
(like file management and networking) so programs can run without having to control hardware directly.

## What is a UNIX based operating system?
A **UNIX-based operating system** is one that follows the core design and standards of the original UNIX system (developed at Bell Labs).  

### **Key Features:**  
✔ **POSIX-compliant** (follows UNIX standards)  
✔ **Multi-user & multi-tasking** (handles multiple users and processes)  
✔ **Stable & secure** (reliable for servers and critical systems)  
✔ **Command-line focused** (powerful terminal and scripting)  

### **Examples:**  
- **macOS** (certified UNIX)  
- **Solaris** (Oracle)  
- **AIX** (IBM)  
- **HP-UX** (HPE)  

### **UNIX-based vs. UNIX-like:**  
- **UNIX-based** = Directly derived from UNIX or certified (e.g., macOS, Solaris).  
- **UNIX-like** = Behaves like UNIX but isn’t certified (e.g., Linux, BSD). 

## Basic Linux Commands
### Getting Started with Linux Commands
``` bash
pwd                 # Print the current directory
ls                  # Command for listing all the files in current directory
ls -l               # Long format listing, means it shows all the files with other details
echo "Hello, Linux" # Print text to stand out.
man ls              # All the manuals for ls
```

### Commands for Navigating directories
``` bash
cd /var/log        # Command for directly navigating to a particular directory
cd ..              # Navigate to the previous directory
cd                 # Navigate to the home directory
cd ~/Downloads     # Go back to home directory and then navigate to downloads
```

### File extension commands in Linux
``` bash
touch report.txt    # Command to create a report file
touch script.sh     # Command for creating a shell script file
chmod +x script.sh  # In order to to make a shell script excutable, we need this command
rm script.sh        # To delete the shell scipt
ls *.sh             # Command to list all the files which has the extesion .sh
```



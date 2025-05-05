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
cat report.txt      # To see the content of the file
rm script.sh        # To delete the shell scipt
ls *.sh             # Command to list all the files which has the extesion .sh
file report.txt     # To get the type of the file
echo "hello world" > report.txt     # Command for writing to a certain file
mv report.txt report.jpg    # In order to change the type of a file or the name of the file  
mv /from/folder/report.txt report.jpg   # It is taking the .txt file in the previous folder
                                        # renaming it to .jgp format and then putting it
                                        # on the current directory
```

### Moving and Copy in Linux
``` bash
mkdir new-directory            # Creates a new directtory
mv file1.txt file2.txt new-directory      # Moves file1.txt and file2.txt to new-directory
cp file1.txt file2.txt         # Copy the content of file1 to file2
```

### Update Files
``` bash
# Assume We are in the Desktop folder. There are two files file1.txt and file2.txt
# The same two file are also present inside the tools folder which is inside desktop
# If we want to move file1.txt and file2.txt to tools if and only if the files
# inside the Desktop folder has been updated.

mv -u file1.txt file2.txt tools
mv -uv file1.txt file2.txt tools        # If one wants to see the details of the update
```

### Removing Directories
``` bash
rmdir emptydir      # Remove empty directory 
rm -r directory     # In order to delete a non-empty directory, we have to recursively 
                    # delete the directory
```

### Redirection and Standard Output
``` bash
echo "Done" > output.log       # A new log file creation
echo "Appending more text" >> output.log      # In order to add more text on top of it
                                              # we have to use >> notation 
```

### Redirecting Standard Error
``` bash
grep foo *.txt 2> erorrs.ext       # First it searches for all the .txt files and it searches for foo
                                   # If it finds it it will print in the terminal. If it does not, it
                                   # will print
```
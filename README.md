# Command Line Cheat Sheet

## File and Directory Operations
- **`ls`**: List files and directories  
  Example: `ls`
- **`cd`**: Change directory  
  Example: `cd /path/to/directory`
- **`pwd`**: Print current working directory  
  Example: `pwd`
- **`cp`**: Copy files  
  Example: `cp source.txt destination.txt`
- **`mv`**: Move files  
  Example: `mv old_name.txt new_name.txt`
- **`rm`**: Remove files  
  Example: `rm file.txt`
- **`touch`**: Create files  
  Example: `touch newfile.txt`
- **`mkdir`**: Create directory  
  Example: `mkdir newdir`
- **`rmdir`**: Remove directory  
  Example: `rmdir olddir`
- **`cat`**: View contents of file  
  Example: `cat file.txt`
- **`echo`**: Print  
  Example: `echo "Hello, World!"`

## File Permissions and Ownership
- **`chmod`**: Change file permissions  
  Example: `chmod +x file.sh`
- **`chown`**: Change ownership  
  Example: `chown user:group file.txt`

## Process Management
- **`ps`**: Display processes  
  Example: `ps aux`
- **`top`**: Process and system usage  
  Example: `top`
- **`kill`**: Kill process  
  Example: `kill -9 PID`

## Disk Usage
- **`df -h`**: Disk free (human readable)  
  Example: `df -h`
- **`du`**: Disk usage  
  Example: `du -sh /path/to/directory`

## Help and Documentation
- **`man`**: Command manual  
  Example: `man ls`
- **`history`**: Command history  
  Example: `history`

## Download and Archive
- **`wget`**: Download files from web  
  Example: `wget http://example.com/file.txt`
- **`zip`**: Create zip archive  
  Example: `zip archive.zip file1.txt file2.txt`
- **`unzip`**: Extract zip archive  
  Example: `unzip archive.zip`

## Shortcuts and Utilities
- **`alias`**: Create shortcut  
  Example: `alias ll="ls -l"`
- **`reboot`**: Reboot system  
  Example: `reboot`
- **`shutdown`**: Shutdown system  
  Example: `shutdown now`

## Text Editors
- **`vi filename`**: Create or edit file  
  Example: `vi file.txt`
- **`vi -R filename`**: Open in read-only mode  
  Example: `vi -R file.txt`

## Counting and Printing
- **`wc`**: Count words in a file  
  Example: `wc file.txt`
- **`cd~`**: Go to home directory  
  Example: `cd ~`
- **`lpstat`**: Show printer queue details  
  Example: `lpstat`
- **`mail`**: Check for mails  
  Example: `mail`
- **`ping`**: Show ping  
  Example: `ping google.com`

## Grep Variants
- **`grep`**: Search pattern in file  
  Example: `grep 'pattern' file.txt`
- **`grep -v`**: Lines that don't match pattern  
  Example: `grep -v 'pattern' file.txt`
- **`grep -i`**: Ignore case  
  Example: `grep -i 'pattern' file.txt`
- **`grep -c`**: Count matching lines  
  Example: `grep -c 'pattern' file.txt`

## Arithmetic and Relational Operators
- **Arithmetic operators**: `+,-,*,/,%,=,==,!=`
  ```bash
  echo $((2 + 3))

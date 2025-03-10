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

- **`cat`**: View contents of a file  
  Example: `cat file.txt`

- **`echo`**: Print text  
  Example: `echo "Hello, World!"`

- **`grep`**: Search pattern in a file  
  Example: `grep 'pattern' file.txt`

## File Permissions and Ownership
- **`chmod`**: Change file permissions  
  Example: `chmod +x file.sh`

- **`chown`**: Change file ownership  
  Example: `chown user:group file.txt`

## Process Management
- **`ps`**: Display processes  
  Example: `ps aux`

- **`top`**: Show processes and system usage  
  Example: `top`

- **`kill`**: Kill process  
  Example: `kill -9 PID`

## Disk Usage
- **`df -h`**: Disk free space (human readable)  
  Example: `df -h`

- **`du`**: Disk usage  
  Example: `du -sh /path/to/directory`

## Help and Documentation
- **`man`**: Command manual  
  Example: `man ls`

- **`history`**: Command history  
  Example: `history`

## Download and Archive
- **`wget`**: Download files from the web  
  Example: `wget http://example.com/file.txt`

- **`zip`**: Create a zip archive  
  Example: `zip archive.zip file1.txt file2.txt`

- **`unzip`**: Extract a zip archive  
  Example: `unzip archive.zip`

## Shortcuts and Utilities
- **`alias`**: Create a shortcut  
  Example: `alias ll="ls -l"`

- **`reboot`**: Reboot the system  
  Example: `reboot`

- **`shutdown`**: Shutdown the system  
  Example: `shutdown now`

## Text Editors
- **`vi filename`**: Open or create a file with `vi`  
  Example: `vi file.txt`

- **`vi -R filename`**: Open a file in read-only mode  
  Example: `vi -R file.txt`

## Miscellaneous Commands
- **`wc`**: Count words in a file  
  Example: `wc file.txt`

- **`cd ~`**: Go to home directory  
  Example: `cd ~`

- **`lpstat`**: Show printer queue details  
  Example: `lpstat`

- **`mail`**: Check for mails  
  Example: `mail`

- **`ping`**: Check network connectivity  
  Example: `ping google.com`

## `grep` Variants
  GREP stands for globally search for a regular expression and it prints the matching lines as result.
- **`grep`**: Search pattern in file  
  Example: `grep 'pattern' file.txt`

- **`grep -v`**: Lines that don't match pattern  
  Example: `grep -v 'pattern' file.txt`

- **`grep -i`**: Ignore case when searching  
  Example: `grep -i 'pattern' file.txt`

- **`grep -c`**: Count matching lines  
  Example: `grep -c 'pattern' file.txt`

## Operators
### Arithmetic Operators
- `+`, `-`, `*`, `/`, `%`, `=`, `==`, `!=`  
  Example: `echo $((2 + 3))`

### Relational Operators
- `-eq`, `-ne`, `-gt`, `-lt`, `-ge`, `-le`  
  Example: `[ 5 -eq 5 ]`

### File Checks
- **`-r filename`**: Check if file is readable  
  Example: `[ -r file.txt ] && echo "Readable"`

- **`-w filename`**: Check if file is writable  
  Example: `[ -w file.txt ] && echo "Writable"`

- **`-x filename`**: Check if file is executable  
  Example: `[ -x file.sh ] && echo "Executable"`

- **`./filename`**: Execute the file  
  Example: `./script.sh`

## File Location and Contents
- **`whereis filename`**: Show file location  
  Example: `whereis filename`

- **`tail filename`**: Show end of a file  
  Example: `tail filename`

- **`head filename`**: Show beginning of a file  
  Example: `head filename`

## User Management
- **`useradd`**: Add user  
  Example: `useradd username`

- **`usermod`**: Modify user attributes  
  Example: `usermod -aG groupname username`

- **`userdel`**: Delete user  
  Example: `userdel username`

## VIM Commands
- **`vi filename`**: Open file in `vi`  
  Example: `vi filename`

- **`vi -R filename`**: Open file in read-only mode  
  Example: `vi -R filename`

### Navigation
- `k,j,h,l`: Navigate within `vi`

### Editing
- **`i`**: Insert mode
- **`o`**: Open a new line below the cursor
- **`x`**: Delete character under cursor
- **`d^`**: Delete from cursor to beginning of line
- **`d$`**: Delete from cursor to end of line
- **`dd`**: Delete the entire current line
- **`cc`**: Remove line content and enter insert mode
- **`yy`**: Copy (yank) the entire line
- **`p`**: Paste below cursor

## Text Processing
- **`awk`**: Pattern scanning and processing language
  
  Print the first column:
  Example: `awk '{print $1}' file.txt`

  Print lines 2 to 5:
  Example: `awk 'NR >= 2 && NR <= 5' file.txt`

  Print each line with its line number:
  Example: `awk '{print NR, $0}' file.txt`

  Process multiple files and print their name:
  Example: `awk '{print FILENAME, $0}' file1.txt file2.txt`

  Use the BEGIN block to initialize something before processing lines:
  Example: `awk 'BEGIN {print "Processing file..."} {print $1} END {print "Finished processing"}' file.txt`
  
- **`sed`**: Stream editor for filtering and transforming text

  Replace the first occurrence of "old" with "new" in each line of file.txt:
  Example: `sed 's/old/new/g' file.txt`

  Replace all occurrences of "old" with "new" in each line:
  Example: `sed 's/old/new/g' file.txt`

  Delete the 3rd line in the file:
  Example: `sed '3d' file.txt`
  
  Print the first 5 lines:
  Example: `sed -n '1,5p' file.txt`


- **`cut`**: Remove sections from each line of files  
  Example: `cut -d' ' -f1 file.txt`

  Extract the first 5 characters from each line:
  Example: `cut -c 1-5 file.txt`

  Extract bytes from beginning to end of line
  Example: `cut -b 2-4 file.txt`

  Extract first field 
  Example: `cut -f 1 state.txt`

cd

    Definition: Change directory.
    Example:

    cd /path/to/directory

pwd

    Definition: Print current working directory.
    Example:

    pwd

cp

    Definition: Copy files or directories.
    Example:

    cp source.txt destination.txt

mv

    Definition: Move or rename files or directories.
    Example:

    mv oldname.txt newname.txt

rm

    Definition: Remove files or directories.
    Example:

    rm file.txt

touch

    Definition: Create an empty file or update the timestamp of a file.
    Example:

    touch newfile.txt

mkdir

    Definition: Create a new directory.
    Example:

    mkdir new_directory

rmdir

    Definition: Remove empty directory.
    Example:

    rmdir empty_directory

cat

    Definition: View contents of a file.
    Example:

    cat file.txt

echo

    Definition: Print text to the terminal.
    Example:

    echo "Hello, World!"

grep

    Definition: Search for a pattern in a file.
    Example:

    grep "search_pattern" file.txt

chmod

    Definition: Change file permissions.
    Example:

    chmod +x script.sh

chown

    Definition: Change ownership of a file.
    Example:

    chown user:group file.txt

Process Management
ps

    Definition: Display process information.
    Example:

    ps aux

top

    Definition: Display system and process information.
    Example:

    top

kill

    Definition: Terminate a process.
    Example:

    kill 1234

Disk Usage
df -h

    Definition: Show disk space usage in human-readable format.
    Example:

    df -h

du

    Definition: Show disk usage of files or directories.
    Example:

    du -sh directory/

System Management
reboot

    Definition: Restart the system.
    Example:

    reboot

shutdown

    Definition: Shut down the system.
    Example:

    shutdown now

man

    Definition: Show the manual for a command.
    Example:

    man ls

history

    Definition: Show command history.
    Example:

    history

Networking
ping

    Definition: Send ICMP echo requests to a host.
    Example:

    ping google.com

wget

    Definition: Download files from the web.
    Example:

    wget http://example.com/file.txt

File Compression
zip

    Definition: Create a ZIP archive.
    Example:

    zip archive.zip file1.txt file2.txt

unzip

    Definition: Extract files from a ZIP archive.
    Example:

    unzip archive.zip

User Management
useradd

    Definition: Add a new user.
    Example:

    useradd username

usermod

    Definition: Modify user account.
    Example:

    usermod -aG sudo username

userdel

    Definition: Delete a user account.
    Example:

    userdel username

File Viewing
tail

    Definition: Display the last part of a file.
    Example:

    tail -n 10 file.txt

head

    Definition: Display the first part of a file.
    Example:

    head -n 10 file.txt

VIM Text Editor
vi

    Definition: Open a file for editing.
    Example:

    vi filename

vi -R

    Definition: Open a file in read-only mode.
    Example:

    vi -R filename

Navigation Commands:

    k - Move cursor up.
    j - Move cursor down.
    h - Move cursor left.
    l - Move cursor right.

Editing Commands:

    i - Enter insert mode.
    o - Open a new line below the cursor.
    x - Delete the character under the cursor.
    d^ - Delete from cursor to the beginning of the line.
    d$ - Delete from cursor to the end of the line.
    dd - Delete the entire line.
    cc - Change the entire line content and enter insert mode.

Copy and Paste:

    yy - Copy the current line.
    p - Paste the copied line.

Searching & Filters
grep -v

    Definition: Search lines that do not match the pattern.
    Example:

    grep -v "pattern" file.txt

grep -i

    Definition: Perform a case-insensitive search.
    Example:

    grep -i "Pattern" file.txt

grep -c

    Definition: Count the number of matching lines.
    Example:

    grep -c "pattern" file.txt

Permissions & File Checks
-r, -w, -x

    Definition: Check file readability, writability, and executability.
    Example:

    -r file.txt   # Check if file is readable
    -w file.txt   # Check if file is writable
    -x file.txt   # Check if file is executable

./filename

    Definition: Execute a file in the current directory.
    Example:

    ./script.sh

whereis

    Definition: Locate a command's binary, source, or manual page.
    Example:

    whereis ls

Arithmetic & Relational Operators
Arithmetic Operators:

    +, -, *, /, %, =, ==, !=
        Example:

        result=$((3 + 5))

Relational Operators:

    -eq, -ne, -gt, -lt, -ge, -le
        Example:

        if [ $a -gt $b ]; then echo "a is greater"; fi

Printing to Terminal
lpstat

    Definition: Display printer queue details.
    Example:

    lpstat -p

mail

    Definition: Check or send mail from the terminal.
    Example:

    mail user@example.com

wc

    Definition: Count words, lines, and characters in a file.
    Example:

    wc file.txt

cd ~

    Definition: Navigate to the home directory.
    Example:

cd ~

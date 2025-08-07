# Linux Command Line Examples

This document includes various Linux command-line examples to help reinforce your learning.

---

## 🗂️ Basic File and Directory Commands

```bash
# Go to home directory
cd ~

# Make a new folder called Projects and go inside it
mkdir Projects
cd Projects

# Create a file and write text in it
echo "This is my first text file" > file1.txt

# View contents of a file
cat file1.txt

# List files and directories
ls

# List with details (long format)
ls -l

# List including hidden files
ls -a

# Make nested directories
mkdir -p Project1/src

# Remove a file
rm file1.txt

# Remove a directory
rmdir Project1/src
```

---

## 📝 File Editing

```bash
# Open a file in nano editor
nano notes.txt

# Append to a file
echo "Another line" >> notes.txt

# Copy a file
cp notes.txt backup.txt

# Move or rename a file
mv backup.txt backup_renamed.txt
```

---

## 🔍 Finding Things

```bash
# Find a file by name
find . -name "notes.txt"

# Search inside a file
grep "line" notes.txt

# Count words, lines, characters in a file
wc notes.txt
```

---

## 🔐 File Permissions

```bash
# Check permissions
ls -l

# Make a script executable
chmod +x script.sh

# Change file permissions (read/write/execute)
chmod 755 script.sh
```

---

## 🧠 Other Useful Commands

```bash
# Show present working directory
pwd

# Display calendar
cal

# Show current date and time
date

# Show who is logged in
who

# Show last login info
last

# Clear terminal screen
clear
```

---

## 🧪 Shell Scripting Basics

```bash
# Create a simple script
echo -e '#!/bin/bash\necho "Hello from script!"' > hello.sh

# Make it executable
chmod +x hello.sh

# Run the script
./hello.sh
```

---

## 🧑‍💻 User Management

```bash
# Create a new user with a home directory
sudo useradd -m username

# Set password for the user
sudo passwd username

# Add user with a specific shell and comment
sudo useradd -m -s /bin/bash -c "Full Name" username

# Check if user exists in /etc/passwd
grep username /etc/passwd

# View user list from passwd file
cat /etc/passwd

# Switch to another user
su username

# View home directories
ls /home
```

---

## 🧾 Viewing System Info & History

```bash
# Show command history
history

# Find location of binaries
whereis useradd
whereis adduser

# View binary as text (not readable normally)
cat /usr/sbin/useradd
cat /usr/sbin/adduser
```

---

Keep experimenting and have fun exploring Linux! 🚀

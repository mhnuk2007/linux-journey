
# 🐧 Linux Command Line – Practice Notes for Beginners

Mastering the Linux terminal, one command at a time! Here's a growing collection of my command-line examples, including file operations, shell scripting, user management, and switching users.

---

## 🗂️ File & Directory Basics

```bash
cd ~                      # Go to home
mkdir Projects            # Make Projects folder
cd Projects
echo "Hello" > file1.txt  # Create file with content
cat file1.txt             # View file
ls -la                    # List all (detailed)
rm file1.txt              # Delete file
mkdir -p demo/src         # Nested folders
rmdir demo/src            # Remove empty dir
```

---

## 📝 File Editing & Management

```bash
nano notes.txt                    # Edit file
echo "Another line" >> notes.txt # Append
cp notes.txt backup.txt          # Copy
mv backup.txt renamed.txt        # Rename/Move
```

---

## 🔍 Search & Inspect

```bash
find . -name "notes.txt"   # Find file
grep "line" notes.txt      # Search inside file
wc notes.txt               # Count lines, words, chars
```

---

## 🔐 File Permissions

```bash
ls -l                   # View permissions
chmod +x script.sh      # Make executable
chmod 755 script.sh     # Set rwxr-xr-x
```

---

## 🧠 System Info & Misc

```bash
pwd       # Current directory
cal       # Calendar
date      # Date/time
who       # Who's logged in
last      # Last login info
clear     # Clear screen
```

---

## 🧪 Shell Script Basics

```bash
echo -e '#!/bin/bash\necho "Hi!"' > hello.sh
chmod +x hello.sh
./hello.sh
```

---

## 👤 User Management

```bash
sudo useradd -m newuser             # Create user
sudo passwd newuser                # Set password
sudo useradd -m -s /bin/bash -c "Full Name" user2
grep user2 /etc/passwd             # Confirm user
cat /etc/passwd                    # All users
ls /home                           # Home directories
```

---

## 🔁 Switching Users

```bash
su - username          # Switch to another user (ask password)
sudo su                # Become root (with sudo access)
sudo -i                # Root shell
whoami                 # Show current user
exit                   # Return to previous user
```

---

## 📂 Binary & History Commands

```bash
history                      # Show all commands used
whereis useradd              # Find binary location
cat /usr/sbin/useradd        # View binary (raw)
```

---

💡 *Learning by doing makes it stick! I’m using this journal to build my confidence in Linux for DevOps and system-level development.*

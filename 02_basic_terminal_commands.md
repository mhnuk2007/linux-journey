# Section 2: Get to Know the Terminal

This section introduces you to the Linux terminal and various commands that help navigate, manage, and view files effectively.

---

## 📚 Learned Commands

### 🖥️ Terminal Management
```bash
clear        # Clears the terminal window
reset        # Resets terminal settings
```

---

## 🔍 Getting Help
```bash
whatis ls                # One-line help for a command
ls --help                # Brief help on the ls command
man ls                   # Open manual page for ls
info ls                  # Alternative detailed help for ls
apropos directory        # Search commands related to 'directory'
```

---
## 📜 Command History
```bash
history                  # Display command history
```
---

## 📂 Navigation
```bash
pwd                      # Show the full path of the current directory
cd /home/user/Documents  # Change to Documents folder
cd ..                    # Move one level up
```
---
## 📄 Viewing Directory Contents
```bash
ls                       # List folder contents
ll                       # Detailed listing including hidden files
ls -la                   # Same as ll
```
---
## 📁 File and Folder Management
```bash
mkdir Projects           # Create a new folder called Projects
mkdir -p Test/Inner      # Create nested folders
tree                     # Show directory structure as a tree
touch file.txt           # Create an empty file
echo "Hello World"       # Print text to the terminal
echo "Hello File" > file.txt  # Save text to a file
cat file.txt             # Display contents of file.txt
```
---

## 📑 Copying, Moving, and Removing
```bash
cp file.txt backup.txt   # Copy a file
cp -r Projects Projects_backup  # Copy folder recursively
mv backup.txt old.txt    # Rename a file
mv old.txt /tmp          # Move a file to another folder
rm file.txt              # Delete a file
rm -r Projects           # Delete a folder and its contents
```
---
## 📖 Viewing File Contents
```bash
more file.txt            # View contents page-by-page
less file.txt            # Similar to more, but more advanced navigation
head file.txt            # View first 10 lines of a file
head -n 5 file.txt       # View first 5 lines
tail file.txt            # View last 10 lines
tail -n 5 file.txt       # View last 5 lines
```
---

## 🔗 Useful Link
(Romeo and Juliet - Project Gutenberg)[https://www.gutenberg.org/files/1112/1112-0.txt]
---

## 📝 Section Summary
In this section, you learned the essential commands to navigate the Linux terminal, manage files and directories, view file contents, and get help on commands. These skills form the foundation for working effectively in Linux.

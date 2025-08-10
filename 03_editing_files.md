# 📝 Section 3: Editing Files in the Terminal

Welcome! This guide introduces you to two essential command-line text editors: **Nano**, the friendly beginner's choice, and **Vim**, the powerhouse for developers. Mastering one of these is a fundamental skill for working on remote servers or within a terminal-focused workflow.

---

## 🗒️ Nano: The Simple & Intuitive Editor

Nano is a user-friendly editor perfect for quick edits and beginners. Its biggest advantage is the always-visible menu of commands at the bottom of the screen.

> **💡 Pro-Tip:** You don't need to memorize Nano commands! The most common ones are always displayed at the bottom. `^` means `Ctrl`.

### Launching Nano

To open an existing file or create a new one, use the `nano` command followed by the filename:

```bash
nano my_notes.txt
```

### Basic Commands

Here are some of the most common commands in Nano. The `^` symbol represents the `Ctrl` key.

| Command    | Action                                                                 |
|------------|------------------------------------------------------------------------|
| `Ctrl + O` | Saves the file (Write**O**ut).                                         |
| `Ctrl + X` | E**x**its the editor. If you have unsaved changes, it will prompt you to save. |
| `Ctrl + G` | Opens the help menu (**G**et Help).                                    |
| `Ctrl + W` | Searches for text within the file (**W**here is).                      |
| `Ctrl + K` | **K**uts (cuts) the current line.                                      |
| `Ctrl + U` | **U**ncuts (pastes) the last cut line.                                 |

---

## 🚀 Vim

Vim is a powerful and highly customizable text editor that can significantly boost your productivity once you get past its initial learning curve. It operates in different "modes" for various tasks.

### Vim's Modes

-   **Normal Mode**: The default mode. Used for navigation, copying, pasting, and deleting text. You can't type text directly in this mode.
-   **Insert Mode**: This is where you type and edit text, similar to a standard text editor.
-   **Visual Mode**: Used for selecting blocks of text to act upon.
-   **Command-Line Mode**: Used to run commands, like saving, quitting, and searching.

### Launching Vim

To open a file or create a new one, use the `vim` command:

```bash
vim filename.txt
```

### Basic Commands

#### Switching Modes

| Key     | Mode Switch          | Action                               |
|---------|----------------------|--------------------------------------|
| `i`     | Normal -> Insert     | **I**nserts text before the cursor.  |
| `a`     | Normal -> Insert     | **A**ppends text after the cursor.   |
| `Esc`   | Insert -> Normal     | Exits Insert mode and returns to Normal mode. |
| `v`     | Normal -> Visual     | Enters **V**isual mode.              |
| `:`     | Normal -> Command    | Enters Command-line mode.        |

#### Saving and Exiting

These commands are used from **Command-Line Mode** (after pressing `:` from Normal mode).

| Command | Action                                           |
|---------|--------------------------------------------------|
| `:w`    | **W**rites (saves) the file.                     |
| `:wq`   | **W**rites (saves) and **q**uits.                |
| `:q`    | **Q**uits. This won't work if you have unsaved changes. |
| `:q!`   | **Q**uits without saving, discarding all changes. |

#### Navigation (Normal Mode)

While you can use arrow keys, the traditional Vim way is to use the home row keys, which keeps your hands on the main part of the keyboard.

| Key | Action |
|-----|--------|
| `h` | Left   |
| `j` | Down   |
| `k` | Up     |
| `l` | Right  |

#### Editing (Normal Mode)

These commands are used from **Normal Mode**.

| Key  | Action                                                |
|------|-------------------------------------------------------|
| `x`  | Deletes the character under the cursor.               |
| `dd` | **D**eletes the entire line.                          |
| `yy` | **Y**anks (copies) the current line.                  |
| `p`  | **P**astes the copied or deleted text after the cursor. |

---

## 🎓 VimTutor

VimTutor is a fantastic interactive tutorial that comes with Vim. It guides you through the core concepts and commands in a structured, hands-on environment. It is highly recommended as the best way to start learning Vim.

### Launching VimTutor

To start the tutorial, simply run this command in your terminal:

```bash
vimtutor
```

This opens a special file within Vim with clear instructions. Follow the prompts and perform the tasks directly in the file to learn by doing. The tutorial takes about 25-30 minutes to complete.

# 🐧 Section 1: Installing and Setting Up Ubuntu/Linux

This section covers the basics of getting Linux installed and ready for use.

---

## 1️⃣ Downloading Ubuntu

- Visit [Ubuntu Downloads](https://ubuntu.com/download/desktop)
- Choose the desired version (LTS recommended for stability)
- Download the ISO file

---

## 2️⃣ Creating a Bootable USB

**Tools:**
- **Windows:** Rufus, BalenaEtcher
- **Mac/Linux:** BalenaEtcher, `dd` command

Example using `dd`:
```bash
sudo dd if=ubuntu.iso of=/dev/sdX bs=4M status=progress
```
> Replace `/dev/sdX` with your USB device path.

---

## 3️⃣ Booting from USB

- Insert the USB into your computer
- Restart and enter **BIOS/UEFI** (usually F2, F12, Del, Esc during boot)
- Change boot order to prioritize USB
- Save and reboot

---

## 4️⃣ Installing Ubuntu

- Choose **Try Ubuntu** or **Install Ubuntu**
- Set:
  - Language
  - Keyboard layout
  - Time zone
  - Partition settings (automatic or manual)
  - Username & password
- Wait for installation to complete
- Restart and remove USB

---

## 5️⃣ Post-Installation Setup

Update system:
```bash
sudo apt update && sudo apt upgrade -y
```

Install essential tools:
```bash
sudo apt install git curl vim build-essential -y
```

---

## 6️⃣ Creating a New User (Optional)

```bash
sudo adduser newusername
sudo usermod -aG sudo newusername
```

---

✅ **Next Steps:**  
Move to learning basic Linux commands and navigating the terminal.

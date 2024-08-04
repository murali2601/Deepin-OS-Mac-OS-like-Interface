# Deepin-OS-Mac-OS-like-Interface

# Switch from Windows to Deepin OS

## Introduction

Welcome to the guide on switching from Windows, a paid software, to Deepin OS, a free Linux distribution that looks and feels similar to both Windows and macOS. Deepin OS is known for its beautiful and user-friendly interface and can run efficiently on PCs or laptops with less than 2GB of RAM.

## Prerequisites

- A USB drive with at least 2GB of storage.
- Internet connection for downloading the Deepin OS ISO file.
- A PC or laptop with less than 2GB of RAM.

## Step-by-Step Installation Guide

### Step 1: Download the ISO File

1. Visit the [Deepin OS download page](https://www.deepin.org/en/download/).
2. Download the appropriate ISO file for your system.

### Step 2: Create a Bootable USB Drive

1. **Windows Users**: Use a tool like [Rufus](https://rufus.ie/) to create a bootable USB drive.
   - Open Rufus and select your USB drive.
   - Select the downloaded ISO file.
   - Click "Start" to create the bootable USB drive.

2. **Linux Users**: Use the `dd` command or a tool like [Etcher](https://www.balena.io/etcher/).
   - Open Etcher and select your USB drive.
   - Select the downloaded ISO file.
   - Click "Flash!" to create the bootable USB drive.

### Step 3: Boot from the USB Drive

1. Insert the bootable USB drive into your PC or laptop.
2. Restart your computer and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete, or Esc during startup).
3. Change the boot order to prioritize booting from the USB drive.
4. Save the changes and exit the BIOS/UEFI settings. Your computer should now boot from the USB drive.

### Step 4: Install Deepin OS

1. Follow the on-screen instructions to install Deepin OS.
2. Choose the option to erase the existing operating system (Windows) and install Deepin OS.
3. Set up your user account and password.
4. Complete the installation process.

### Step 5: Post-Installation Setup

1. Remove the USB drive and restart your computer.
2. Log in to your new Deepin OS system.
3. Update the system by opening a terminal and running:
   ```sh
   sudo apt update && sudo apt upgrade -y
   ```

## Additional Resources

- [Deepin OS Documentation](https://wiki.deepin.org/)
- [Deepin Community Forum](https://bbs.deepin.org/en)

## Conclusion

Congratulations on making the switch to Deepin OS! We hope you find this guide helpful. If you encounter any issues or have questions, feel free to reach out to the community forums or check the documentation link provided above.

---

Feel free to modify this template to better suit your specific needs and preferences.

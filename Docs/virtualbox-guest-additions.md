# VirtualBox Guest Additions

## Introduction

VirtualBox Guest Additions improves the experience of using a virtual machine. It provides better display support and allows the virtual machine to work smoothly with the host system.

---

## Why I Installed Guest Additions

I installed Guest Additions to get the following features:

- Better screen resolution
- Full screen mode
- Better mouse integration
- Shared clipboard
- Drag and drop support

---

## Installation Steps

### Step 1

Start the Windows 11 virtual machine.

### Step 2

In the VirtualBox menu click:

```
Devices → Insert Guest Additions CD Image
```

### Step 3

Open File Explorer and open the Guest Additions CD.

### Step 4

Run:

```
VBoxWindowsAdditions.exe
```

as Administrator.

### Step 5

Complete the installation and restart the virtual machine.

---

## Notes

At first nothing happened after inserting the Guest Additions CD image.

I manually opened the CD from File Explorer and started the installation by running the setup file.

After restarting the virtual machine the installation was completed successfully.

---

## Result

Guest Additions was installed successfully.

The Windows virtual machine now supports better display resolution and improved mouse integration.

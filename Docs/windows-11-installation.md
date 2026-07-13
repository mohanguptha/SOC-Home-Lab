# Windows 11 Installation

## Introduction

Windows 11 is used as the victim machine in this SOC Home Lab. It generates Windows Event Logs that are collected by Splunk using the Splunk Universal Forwarder.

---

## Virtual Machine Configuration

| Setting | Value |
|---------|-------|
| Operating System | Windows 11 Pro |
| Memory | 8 GB |
| Processor | 4 CPUs |
| Storage | 80 GB |
| Network | NAT |

> **Note:** Your values may be different depending on your system configuration.

---

## Installation Steps

### Step 1

Download the Windows 11 ISO from the Microsoft website.

### Step 2

Create a new virtual machine in Oracle VirtualBox.

### Step 3

Allocate memory CPU and storage for the virtual machine.

### Step 4

Attach the Windows 11 ISO file.

### Step 5

Start the virtual machine and complete the Windows installation.

### Step 6

Create a local user account.

Username:

```text
soc_test
```

### Step 7

Complete the initial Windows setup and privacy settings.

---

## Result

Windows 11 was installed successfully and the virtual machine booted without any issues.

---

## Notes

While creating the local user account Windows asked me to sign in with a Microsoft account.

To continue with a local account I selected the option to create a local user instead.

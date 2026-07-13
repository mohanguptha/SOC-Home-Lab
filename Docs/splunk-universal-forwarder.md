# Splunk Universal Forwarder Installation

## Introduction

The Splunk Universal Forwarder is used to send Windows Event Logs from the Windows 11 virtual machine to Splunk Enterprise.

It works as a lightweight agent that collects logs from the endpoint and forwards them to the SIEM.

---

## Why I Installed Splunk Universal Forwarder

I installed the Universal Forwarder so that Windows Event Logs could be collected and viewed in Splunk Enterprise.

Without the forwarder, Splunk cannot receive logs from the Windows virtual machine.

---

## System Information

| Component | Details |
|----------|---------|
| Operating System | Windows 11 Pro |
| Universal Forwarder Version | 9.4.3 |
| Splunk Enterprise Version | 10.4.1 |

---

## Installation Steps

### Step 1

Download Splunk Universal Forwarder from the official Splunk website.

### Step 2

Run the installer as Administrator.

### Step 3

Accept the license agreement.

### Step 4

Select **On-premises Instance**.

### Step 5

Choose **Local System** as the installation option.

### Step 6

Leave the Deployment Server settings empty.

### Step 7

Configure the Receiving Indexer.

| Setting | Value |
|---------|-------|
| Host | Host Machine IP Address |
| Port | 9997 |

### Step 8

Complete the installation.

---

## Configuration

After the installation I configured the Universal Forwarder to collect Windows Event Logs by creating an **inputs.conf** file.

The configuration was saved in:

```
C:\Program Files\SplunkUniversalForwarder\etc\system\local\
```

---

## Result

The Universal Forwarder connected successfully to Splunk Enterprise and Windows Event Logs started appearing in Splunk.

---

## What I Learned

- Learned how the Universal Forwarder sends logs to Splunk Enterprise.
- Understood the difference between Splunk Enterprise and Splunk Universal Forwarder.
- Learned how to configure a receiving indexer.

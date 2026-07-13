# Sysmon Installation

## Introduction

Sysmon is a Windows system monitoring tool developed by Microsoft Sysinternals. It provides detailed information about system activity and records events that are not available in normal Windows Event Logs.

I installed Sysmon to improve log collection and increase visibility into system activities.

---

## Why I Installed Sysmon

The default Windows Event Logs provide useful information but they do not record every activity.

Sysmon provides additional events such as:

- Process Creation
- Network Connections
- File Creation
- Registry Changes
- Driver Loading
- Process Termination

These events help security analysts monitor endpoint activity more effectively.

---

## Software Information

| Component | Version |
|----------|---------|
| Sysmon | Latest |
| Configuration | SwiftOnSecurity Sysmon Configuration |

---

## Installation Steps

### Step 1

Download Sysmon from the Microsoft Sysinternals website.

### Step 2

Extract the downloaded ZIP file.

### Step 3

Download a Sysmon configuration file.

### Step 4

Open Command Prompt as Administrator.

### Step 5

Run the following command to install Sysmon.

```cmd
Sysmon64.exe -accepteula -i sysmonconfig-export.xml
```

### Step 6

Verify that Sysmon is installed successfully.

Open:

```
Event Viewer
→ Applications and Services Logs
→ Microsoft
→ Windows
→ Sysmon
→ Operational
```

---

## Result

Sysmon was installed successfully.

The Sysmon Operational log started recording Windows system events.

---

## What I Learned

- Learned how Sysmon improves Windows monitoring.
- Learned how Sysmon records detailed endpoint events.
- Understood why Sysmon is commonly used in SOC environments.

---

## References

- Microsoft Sysinternals
- SwiftOnSecurity Sysmon Configuration

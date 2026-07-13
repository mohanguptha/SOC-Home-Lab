# Lab Validation

## Introduction

After completing the installation and configuration of all components I verified that the SOC Home Lab was working correctly.

This validation helped me confirm that the virtual machines and Splunk environment were configured successfully.

---

## Validation Checklist

| Component | Status |
|----------|--------|
| Oracle VirtualBox | ✅ Completed |
| Windows 11 Virtual Machine | ✅ Completed |
| Kali Linux Virtual Machine | ✅ Completed |
| Splunk Enterprise | ✅ Installed |
| Splunk Universal Forwarder | ✅ Installed |
| Sysmon | ✅ Installed |
| Windows Event Log Forwarding | ✅ Working |
| Network Configuration | ✅ Verified |

---

## Verification Results

### Windows Virtual Machine

- Windows 11 installed successfully.
- Local user account created.
- Guest Additions installed.
- Windows Event Logs generated successfully.

---

### Kali Linux Virtual Machine

- Kali Linux installed successfully.
- Internet connection verified.
- Connected to the same virtual network.

---

### Splunk Enterprise

- Splunk Enterprise installed successfully.
- Web interface accessible.
- Receiving port configured.
- Windows Event Logs received successfully.

---

### Splunk Universal Forwarder

- Installed successfully.
- Connected to Splunk Enterprise.
- Windows Event Logs forwarded successfully.

---

### Sysmon

- Installed successfully.
- Sysmon Operational logs available in Event Viewer.

> **Note:** Sysmon event forwarding to Splunk is still being reviewed. Windows Event Logs are being collected successfully.

---

## Project Outcome

This project helped me understand how different SOC tools work together.

I learned how to build a virtual lab configure Windows and Linux virtual machines install Splunk Enterprise configure the Universal Forwarder install Sysmon and forward Windows Event Logs to Splunk.

Building this lab also improved my troubleshooting skills because I solved several configuration issues during the setup process.

---

## Skills Practiced

- Virtual Machine Setup
- Oracle VirtualBox
- Windows 11
- Kali Linux
- Splunk Enterprise
- Splunk Universal Forwarder
- Sysmon
- Windows Event Logs
- Network Configuration
- Troubleshooting

## References

- Microsoft Learn
- Microsoft Sysinternals
- Splunk Documentation
- Oracle VirtualBox Documentation
- Kali Linux Documentation

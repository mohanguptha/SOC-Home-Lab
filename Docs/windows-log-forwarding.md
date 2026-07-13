# Windows Log Forwarding

## Introduction

After installing Splunk Enterprise Splunk Universal Forwarder and Sysmon the next step was to forward Windows Event Logs to Splunk.

This allows logs generated on the Windows virtual machine to be collected and viewed from a single place.

---

## Why Log Forwarding Is Important

Log forwarding is one of the most important parts of a SOC environment.

Instead of checking logs on every computer security analysts collect logs in a central location where they can monitor and investigate events more efficiently.

---

## Configuration Steps

### Step 1

Open Splunk Enterprise.

### Step 2

Enable receiving on port **9997**.

```
Settings
→ Forwarding and Receiving
→ Configure Receiving
```

### Step 3

Create the **inputs.conf** file.

Location:

```text
C:\Program Files\SplunkUniversalForwarder\etc\system\local\
```

### Step 4

Configure the required Windows Event Logs.

Example:

```ini
[WinEventLog://Security]
disabled = 0

[WinEventLog://System]
disabled = 0

[WinEventLog://Application]
disabled = 0
```

### Step 5

Restart the Splunk Universal Forwarder service.

### Step 6

Open Splunk Enterprise and verify that Windows Event Logs are received.

---

## Result

The Windows Event Logs were successfully forwarded to Splunk Enterprise.

I verified that Security System and Application logs were available in Splunk.

---

## Notes

During the lab setup I spent time checking the Universal Forwarder configuration and verifying that the Windows Event Logs were forwarded correctly.

This helped me understand how log forwarding works between the endpoint and the SIEM.

---

## Key Takeaways

- Learned how Windows Event Logs are forwarded to Splunk.
- Understood the purpose of the Universal Forwarder.
- Learned how to verify that logs are received successfully.

---

## References

- Splunk Documentation
- Microsoft Windows Event Log Documentation

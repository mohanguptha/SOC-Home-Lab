# Network Configuration

## Introduction

Network configuration is an important part of this SOC Home Lab. All virtual machines must communicate with each other while also having internet access.

I configured the virtual machines using Oracle VirtualBox NAT Network.

---

## Why I Used NAT Network

I used NAT Network because it allows multiple virtual machines to communicate with each other and also provides internet access.

This made it easier to build and manage the lab environment.

---

## Network Topology

```
                 Internet
                     │
                     │
             VirtualBox NAT Network
                     │
      ┌──────────────┴──────────────┐
      │                             │
      │                             │
 Windows 11 Pro               Kali Linux
      │
      │
Splunk Universal Forwarder
      │
      ▼
Splunk Enterprise
(Host Machine)
```

---

## Virtual Machine Network Settings

### Windows 11

| Setting | Value |
|---------|-------|
| Adapter | Adapter 1 |
| Attached To | NAT Network |

### Kali Linux

| Setting | Value |
|---------|-------|
| Adapter | Adapter 1 |
| Attached To | NAT Network |

---

## IP Address Verification

After starting both virtual machines I verified that they received IP addresses successfully.

| Machine | IP Address |
|---------|------------|
| Windows 11 | 10.0.2.3 |
| Kali Linux | 10.0.2.15 |

> **Note:** IP addresses may be different depending on your VirtualBox configuration.

---

## Network Verification

I verified that both virtual machines were connected to the same network.

The Windows virtual machine was also able to forward logs to Splunk Enterprise successfully.

---

## Result

The network configuration was completed successfully.

Both virtual machines had internet access and the Windows virtual machine was able to communicate with Splunk Enterprise.

---

## Key Takeaways

- Learned how to configure NAT Network in Oracle VirtualBox.
- Learned how to connect multiple virtual machines.
- Understood the importance of network configuration in a virtual lab.

## References

- Oracle VirtualBox Documentation

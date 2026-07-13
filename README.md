# SOC Home Lab

## Overview

This repository shows the complete process of building my SOC Home Lab.

I created this lab to learn how Security Operations Center (SOC) works in a real environment. It helped me understand how different SOC tools work together and how Windows logs are collected and monitored using Splunk.

The main goal of this project is to build a working SOC lab from scratch and document every step.

---

## Table of Contents

- [Lab Environment](#lab-environment)
- [Project Goals](#project-goals)
- [Lab Architecture](#lab-architecture)
- [Project Documentation](#project-documentation)
- [Current Progress](#current-progress)
- [Future Improvements](#future-improvements)

---

## Lab Environment

| Component | Technology |
|-----------|------------|
| Hypervisor | Oracle VirtualBox |
| SIEM | Splunk Enterprise |
| Log Forwarding | Splunk Universal Forwarder |
| Endpoint Monitoring | Sysmon |
| Victim Machine | Windows 11 Pro |
| Linux Machine | Kali Linux |

---

## Project Goals

- Build a SOC Home Lab
- Install Windows 11
- Install Kali Linux
- Install Splunk Enterprise
- Install Splunk Universal Forwarder
- Install Sysmon
- Forward Windows Event Logs to Splunk
- Verify log collection

---

## Lab Architecture

> Architecture diagram will be added after completing the lab.

---

## Project Documentation

| Document | Description |
|----------|-------------|
| Lab Planning | Project planning and objectives |
| Windows Installation | Windows 11 virtual machine setup |
| Guest Additions | VirtualBox Guest Additions |
| Splunk Enterprise | Splunk installation |
| Universal Forwarder | Forwarder installation |
| Sysmon | Sysmon installation |
| Windows Log Forwarding | Log forwarding configuration |
| Kali Linux | Kali Linux installation |
| Network Configuration | Virtual network setup |
| Lab Validation | Final validation |

---

## Current Progress

- ✅ Oracle VirtualBox Installed
- ✅ Windows 11 Installed
- ✅ Kali Linux Installed
- ✅ Splunk Enterprise Installed
- ✅ Splunk Universal Forwarder Installed
- ✅ Sysmon Installed
- ✅ Windows Event Log Forwarding
- ⚠️ Sysmon Forwarding (Under Review)

---

## Future Improvements

- Complete Sysmon log forwarding
- Add Splunk dashboards
- Expand the lab with additional virtual machines
- Continue improving the lab environment

---

This repository focuses only on building and configuring the SOC Home Lab.

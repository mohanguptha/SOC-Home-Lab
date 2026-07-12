# SOC Home Lab

## Overview

This repository shows the complete process of building my SOC Home Lab.

I created this lab to learn how Security Operations Centers (SOC) work in a real environment. It helps me practice SIEM tools, Windows event logging, endpoint monitoring and log collection.

The main goal of this project is to build a working SOC lab from scratch and understand how different tools work together.

---

## Lab Environment

| Component | Technology |
|-----------|------------|
| Hypervisor | Oracle VirtualBox |
| SIEM | Splunk Enterprise |
| Log Forwarding | Splunk Universal Forwarder |
| Endpoint Monitoring | Sysmon |
| Victim Machine | Windows 11 Pro |
| Attacker Machine | Kali Linux |

---

## Project Goals

- Build a SOC Home Lab
- Install Windows 11 Pro in VirtualBox
- Install Kali Linux in VirtualBox
- Install Splunk Enterprise
- Install Splunk Universal Forwarder
- Install Sysmon
- Forward Windows Event Logs to Splunk
- Check that logs are received successfully

---

This repository is only for building and configuring my SOC Home Lab. I will create separate repositories for attack simulations alert investigations and incident reports.

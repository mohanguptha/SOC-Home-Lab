# Lab Planning

## Introduction

I built this SOC Home Lab to learn how Security Operations Center (SOC) tools work in a real environment. Instead of only watching tutorials I wanted to build the lab by myself and understand how each component works.

This project helped me learn how to install, configure and connect different tools that are commonly used by SOC analysts.

---

## Lab Objective

The main objective of this project is to build a working SOC Home Lab that can collect Windows logs using Splunk.

By building this lab i learned how to:

- Create virtual machines
- Install Windows 11 and Kali Linux
- Install Splunk Enterprise
- Install Splunk Universal Forwarder
- Install Sysmon
- Forward Windows Event Logs to Splunk
- Verify that logs are collected successfully

---

## Lab Architecture

The lab contains three main components.

| Machine | Purpose |
|----------|---------|
| Windows 11 | Generates Windows Event Logs |
| Kali Linux | Linux virtual machine used in the lab |
| Splunk Enterprise | Collects and displays Windows logs |

---

## Software Used

| Software | Version |
|----------|---------|
| Oracle VirtualBox | Latest |
| Windows 11 Pro | 24H2 |
| Kali Linux | Latest |
| Splunk Enterprise | 10.4.1 |
| Splunk Universal Forwarder | 9.4.3 |
| Sysmon | Latest |

---

## Learning Outcome

After completing this lab I understand how Windows logs are collected and forwarded to Splunk. I also learned how different components work together in a SOC environment.

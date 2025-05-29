# Elevate-Labs-Task3

# 🔒 Vulnerability Assessment using Nessus Essentials

## 📘 Overview

This repository contains the results of a basic vulnerability scan performed on a personal computer using **Tenable Nessus Essentials**. The objective of the scan was to identify potential security weaknesses in a typical host environment as part of cybersecurity learning and evaluation.

---

## 🛠️ Tools Used

- **Tool:** Tenable Nessus Essentials (Free Version)
- **Scan Type:** Basic Network Scan
- **Scan Target:** `192.168.29.45` (Local Machine)
- **Operating System:** [Insert your OS: Windows/Kali/Ubuntu]
- **Scan Date:** May 29, 2025

---

## 🔍 Scan Summary

| Severity | Count |
|----------|-------|
| Critical | 0     |
| High     | 0     |
| Medium   | 3     |
| Low      | 0     |
| Info     | 40    |
| **Total**| **43**|

---

## 📑 Key Findings

### 🟡 Medium Severity Issues:
1. **[SSL Certificate Cannot Be Trusted](https://www.tenable.com/plugins/nessus/51192)**  
2. **[SSL Self-Signed Certificate](https://www.tenable.com/plugins/nessus/57582)**  
3. **[SMB Signing Not Required](https://www.tenable.com/plugins/nessus/57608)**

### ℹ️ Informational (Examples):
- [Operating System Fingerprint Detected](https://www.tenable.com/plugins/nessus/209654)  
- [SSL/TLS Cipher Suites Info](https://www.tenable.com/plugins/nessus/156899)  
- [Host FQDN Resolution](https://www.tenable.com/plugins/nessus/12053)  
- [Web Server Version Detection](https://www.tenable.com/plugins/nessus/10107)  
- [Strict Transport Security (STS) Detection](https://www.tenable.com/plugins/nessus/42822)

## 📄 Report Summary

The scan revealed the following key issues (examples below — replace with your actual results):

- 🔴 **Critical**: Open SSH with weak encryption algorithms
- 🔶 **High**: Outdated Apache server version with known CVEs
- 🟡 **Medium**: SSL certificate is self-signed
- 🟢 **Low**: ICMP timestamp response enabled

> View full list in the PDF report below.

[MyPC_1wqhey.pdf](https://github.com/user-attachments/files/20502032/MyPC_1wqhey.pdf)



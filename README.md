# Vulnerable-_-nessus-scan-report
# 🔍 Nessus Vulnerability Scan Report

This repository contains the output of a vulnerability assessment conducted using **Tenable Nessus Essentials** on a local or network system. This scan is part of a cybersecurity learning and assessment project.

---

## 🧰 Tool Information

- **Scanner:** [Nessus Essentials](https://www.tenable.com/products/nessus)
- **Version:** 10.x (or your version)
- **Platform:** Windows / Kali Linux
- **Scan Type:** Basic Network Scan / Localhost Audit

---

## 🎯 Target Scope

| Target        | IP Address     | OS/Service Scanned       |
|---------------|----------------|---------------------------|
| Local Machine | 127.0.0.1      | Windows 10                |
| Other (if any)| 192.168.X.X    | Web Server / FTP / etc.   |

---

## 🧾 Summary of Findings

| Risk Level | Count |
|------------|-------|
| Critical   | 2     |
| High       | 5     |
| Medium     | 8     |
| Low        | 12    |
| Info       | 15    |

> Replace these numbers with actual values from your scan.

---

## 🐛 Sample Critical Vulnerabilities

1. **Remote Code Execution via SMBv1**
   - CVE: CVE-2017-0144
   - Plugin ID: 100921
   - Solution: Disable SMBv1 or apply Microsoft patch.

2. **Unpatched Windows OS**
   - Vulnerable to multiple CVEs.
   - Recommendation: Perform system updates via Windows Update.

---

## 📂 Files Included

| File Name                            | Description                                |
|--------------------------------------|--------------------------------------------|
| `Day - 3 Vulnerable Scanning.pdf`    | Exported PDF report of the scan            |
| `my system_Scan`                   | Raw scan data (XML format)                 |
| `README.md`                          | Description of this scan                   |

---

## 📌 Purpose

This report is part of:
- Cybersecurity training / internship
- Personal skill development
- Bug bounty preparation
- Home network audit

---

## 🛡️ Recommendations

- Regularly patch all systems.
- Disable unnecessary ports and services.
- Perform scans periodically.
- Use a host-based firewall.
- Harden systems using CIS Benchmarks.

---

## 📚 References

- [Tenable Documentation](https://docs.tenable.com/)
- [NIST Vulnerability Database](https://nvd.nist.gov/)
- [Common Vulnerabilities and Exposures (CVE)](https://cve.mitre.org/)
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)

---

## 📅 Scan Date

**August 7, 2025**

---

## 📌 Author

- Name: *Abinash*
- Internship: *Cyber Forensics Internship / Personal Project*
- Email: *abinashkavi24@gmail.com*

---

## 📢 Disclaimer

> This scan was conducted in a controlled environment. Do not perform scans on systems without permission.

# 🛡️ OSCP / PEN-200 Master Pentesting Database

## 🎯 Overview

This repository is a structured study database for OffSec PEN-200 (OSCP).
It contains personal notes, methodologies, checklists, and penetration testing references covering the full lifecycle of ethical hacking.

Based on: **OffSec PEN-200 (Kali Linux)**
Philosophy: **Try Harder — OffSec Mindset**

---

## 📚 Table of Contents

| #  | Module                            |
| -- | --------------------------------- |
| 01 | Penetration Testing Methodology   |
| 02 | Report Writing                    |
| 03 | Information Gathering — Passive   |
| 04 | Information Gathering — Active    |
| 05 | Vulnerability Scanning            |
| 06 | Web Application Attacks           |
| 07 | SQL Injection                     |
| 08 | Client-Side Attacks               |
| 09 | Exploit Research & Fixing         |
| 10 | Antivirus Evasion                 |
| 11 | Password Attacks                  |
| 12 | Windows Privilege Escalation      |
| 13 | Linux Privilege Escalation        |
| 14 | Port Redirection & SSH Tunneling  |
| 15 | Metasploit Framework              |
| 16 | Active Directory Enumeration      |
| 17 | Active Directory Attacks          |
| 18 | Active Directory Lateral Movement |
| 19 | Active Directory Persistence      |
| 20 | Shells & File Transfers           |
| 21 | Reporting Templates               |
| 22 | OSCP Exam Checklists              |
| 23 | Essential Resources & Tools       |

---

## 🔍 01 — Penetration Testing Methodology

### 🧭 The Pentesting Lifecycle (OffSec Model)

1. **Scoping & Engagement Rules**

   * Define in-scope IPs, domains, and targets
   * Identify restrictions and legal boundaries

2. **Information Gathering**

   * Passive reconnaissance (OSINT)
   * Active reconnaissance (direct scanning)

3. **Vulnerability Scanning**

   * Automated scanning tools
   * Manual validation of findings

4. **Exploitation**

   * Gain initial access (foothold)

5. **Post Exploitation**

   * System enumeration
   * Credential harvesting
   * Data extraction

6. **Privilege Escalation**

   * User → Root / SYSTEM / Domain Admin

7. **Lateral Movement / Pivoting**

   * Move across internal networks and hosts

8. **Reporting**

   * Document every step with evidence
   * Ensure reproducibility

---

### 🧠 Core Mindset (OffSec Philosophy)

* **Try Harder** — never stop at first failure
* **Enumerate More** — most misses come from poor enumeration
* **Methodology > Tools** — process matters more than tools
* **Document Everything** — if it’s not written, it didn’t happen

---

## 📝 02 — Report Writing

### 📌 Best Practices

* Take screenshots immediately after every critical step
* Each proof must include:

  * `whoami`
  * `hostname`
  * `ip a` / `ipconfig`
  * flag (if available)
* Use structured note tools like:

  * Obsidian
  * CherryTree
  * Notion

---

### 📄 Report Structure

1. Cover Page (Title, Date, Engagement)
2. Executive Summary
3. Methodology
4. Findings
5. Exploitation Steps
6. Evidence (Screenshots)
7. Remediation Recommendations

---

## 👤 About the Author

**Mostafa Ibrahim**
Cybersecurity Student | Pentester | Red Team Learner

🔗 LinkedIn: [www.linkedin.com/in/mostafa-ibrahim-60b543341](http://www.linkedin.com/in/mostafa-ibrahim-60b543341)

---

## ⚖️ Disclaimer

This repository is for **educational purposes only**.
All techniques are intended for use in authorized environments such as labs and legal penetration testing engagements.

---

## 🛠️ Status

Maintained actively as part of OSCP PEN-200 preparation journey.

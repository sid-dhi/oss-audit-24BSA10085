# oss-audit-24BSA10085
**Student Name:** Siddhisharma  
**Roll Number:** 24BSA10085  
**Course:** Open Source Software (OSS NGMC)  
**Chosen Software:** Git  
**Submission Date:** 30 March 2026

---

## 📌 Project Overview

This project is a complete open-source audit of **Git** – a distributed version control system created by Linus Torvalds in 2005. The audit explores:

- Origin story and the problem Git solved
- License analysis (GPL v2 and the four freedoms)
- Ethical reflection on open source software
- Linux footprint (installation, directories, permissions)
- FOSS ecosystem mapping (dependencies, community, governance)
- Comparison with proprietary alternative (Perforce)

Alongside the written report, this repository contains **five shell scripts** that demonstrate practical Linux skills including system reporting, package inspection, disk auditing, log analysis, and an interactive manifesto generator.

---

## 📁 Repository Structure
oss-audit-24BSA10085/
├── README.md
├── script1_system_identity.sh
├── script2_package_inspector.sh
├── script3_disk_auditor.sh
├── script4_log_analyzer.sh
└── script5_manifesto.sh


---

## 📜 Scripts Description

| # | Script Name | Purpose | Key Concepts |
|---|-------------|---------|---------------|
| 1 | `script1_system_identity.sh` | Displays Linux distribution, kernel version, logged-in user, uptime, and OS license | Variables, `echo`, command substitution `$()` |
| 2 | `script2_package_inspector.sh` | Checks if Git is installed, shows version/license, prints philosophy using case statement | `dpkg`, `grep`, `case` statement |
| 3 | `script3_disk_auditor.sh` | Loops through system directories, reports size, owner, and permissions | `for` loop, `du -sh`, `ls -ld`, `awk` |
| 4 | `script4_log_analyzer.sh` | Reads a log file, counts keyword occurrences, displays last 5 matching lines | `while read` loop, `if-then`, counters, `$1`, `$2` |
| 5 | `script5_manifesto.sh` | Asks interactive questions, generates personalized manifesto text file | `read -p`, string concatenation, file writing `>`, `date` |

---

## 💻 Requirements / Dependencies

- **Operating System:** Linux (Ubuntu 22.04 LTS or later recommended)
- **Shell:** Bash (`#!/bin/bash`)
- **Installed Packages:**
  - `git` (for Script 2)
  - `dpkg` (comes with Ubuntu/Debian)
  - Standard Linux utilities: `ls`, `du`, `awk`, `grep`, `cat`, `date`

# Pen-Testing-Report-Template
A reusable DOCX & Markdown template for planning, executing, and reporting penetration tests aligned with NIST SP 800-115.

## Project Overview
This project delivers a fully-featured penetration testing plan and report template covering every test phase, from rules of engagement and reconnaissance through exploitation, findings, and remediation. It’s dual-format: a polished Word (`.docx`) template for client deliverables and a plain-text Markdown version for code-centric workflows.

---

## Tools Used
- **Kali Linux**  
  - **Nmap** (host discovery, port & service enumeration)  
  - **Nikto**, **Dirb**, **WPScan** (web vulnerability scanning)  
  - **OpenVAS** (comprehensive CVE-driven vulnerability assessment)  
  - **Metasploit Framework** (exploitation modules)  
  - **Social-Engineer Toolkit (SET)** (phishing/credential harvesting)  
- **Windows 10 VM** (web application testing, Sysmon, Winlogbeat)  
- **Native OS utilities**: `ping`, `traceroute`, `dig`, `nslookup` for banner grabbing & network fingerprinting  
- **Microsoft Word** (`.docx` version) + **Pandoc** (for generating the Markdown equivalent)  

---

## Skills Demonstrated
- 📋 **Test Planning & Documentation**  
  Crafting a clear Rules of Engagement and structured report layout  
- 🔍 **Reconnaissance & Enumeration**  
  Performing passive (OSINT) and active scans to map live hosts and services  
- 🛠 **Vulnerability Discovery & Analysis**  
  Using automated scanners (Nikto, OpenVAS) and custom probes (Dirb, WPScan)  
- 🚀 **Exploitation Simulation**  
  Executing real-world attacks via Metasploit and SET to validate impact  
- 📊 **Reporting & Risk Communication**  
  Documenting findings with CVSS ratings, evidence appendices, and actionable remediation  
- 🔄 **Cleanup & Post-Test Remediation**  
  Guidelines for log sanitization, credential resets, and service restoration  

---

## Description
1. **Executive Summary** & **Document Revision History**  
2. **Rules of Engagement**: Scope, timing, authorization  
3. **Methodology**: Recon, discovery, exploitation, post-exploitation cleanup  
4. **Findings & Evidence**: CVSS-rated vulnerabilities, screenshots, logs  
5. **Recommendations**: Prioritized remediation steps  
6. **Appendices**: Full scan exports, tool outputs, configuration snapshots  



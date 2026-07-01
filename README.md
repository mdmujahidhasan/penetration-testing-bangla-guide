<div align="center">

# 🛡️ Penetration Testing — সম্পূর্ণ গাইড

### Complete Beginner to Professional Documentation

![Language](https://img.shields.io/badge/Language-Bengali-blue?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Professional-brightgreen?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-2.0-orange?style=for-the-badge)
![Topic](https://img.shields.io/badge/Topic-Cybersecurity-critical?style=for-the-badge)

একটি সম্পূর্ণ শিক্ষামূলক ডকুমেন্টেশন — কী, কেন, কীভাবে এবং কী কী প্রয়োজন

</div>

---

## 📚 সূচিপত্র (Table of Contents)

- [১. Cybersecurity কী?](#১-cybersecurity-কী)
- [২. Penetration Testing কী?](#২-penetration-testing-কী)
- [৩. কেন করা হয়?](#৩-penetration-testing-কেন-করা-হয়)
- [৪. Penetration Tester কে?](#৪-penetration-tester-কে)
- [৫. উদ্দেশ্য](#৫-penetration-testing-এর-উদ্দেশ্য)
- [৬. ধরন (Types)](#৬-penetration-testing-এর-ধরন)
- [৭. Methodology (ওভারভিউ)](#৭-penetration-testing-methodology-ওভারভিউ)
- [৮. ধাপে ধাপে প্রক্রিয়া (Step 1–10)](#৮-ধাপে-ধাপে-প্রক্রিয়া-step-1--step-10)
- [৯. প্রয়োজনীয় দক্ষতা](#৯-penetration-tester-হতে-যা-জানতে-হবে)
- [১০. গুরুত্বপূর্ণ Tools](#১০-গুরুত্বপূর্ণ-tools)
- [১১. Kali Linux কেন?](#১১-kali-linux-কেন)
- [১২. Report Writing](#১২-report-writing)
- [১৩. Severity](#১৩-severity-গুরুত্বের-মাত্রা)
- [১৪. Standards](#১৪-penetration-testing-standards)
- [১৫. Certifications](#১৫-certifications)
- [১৬. Career Path](#১৬-career-path)
- [১৭. Lab Setup](#১৭-lab-setup)
- [১৮. Learning Roadmap](#১৮-learning-roadmap)
- [১৯. Soft Skills](#১৯-একজন-ভালো-penetration-tester-এর-soft-skills)
- [২০. আইন ও নৈতিকতা](#২০-আইন-ও-নৈতিকতা-legal--ethics)
- [২১. OWASP Top 10](#২১-owasp-top-10-web-security)
- [২২. Deliverables](#২২-pentest-এর-deliverables)
- [২৩. Frameworks](#২৩-frequently-used-frameworks)
- [২৪. পরিভাষা (Glossary)](#২৪-পরিভাষা-glossary)
- [২৫. নমুনা রিপোর্ট টেমপ্লেট](#২৫-নমুনা-রিপোর্ট-টেমপ্লেট)
- [২৬. সাধারণ ভুল](#২৬-সাধারণ-ভুল-যা-এড়ানো-উচিত)
- [২৭. FAQ](#২৭-প্রায়শই-জিজ্ঞাসিত-প্রশ্ন-faq)
- [২৮. চূড়ান্ত সারসংক্ষেপ ও রোডম্যাপ](#২৮-চূড়ান্ত-সারসংক্ষেপ-ও-রোডম্যাপ)

---

## ১. Cybersecurity কী?

Cybersecurity হলো এমন একটি ব্যবস্থা যার মাধ্যমে নিচের বিষয়গুলোকে সাইবার আক্রমণ (Cyber Attack) থেকে নিরাপদ রাখা হয়:

- 💻 Computer
- 🖥️ Server
- 🌐 Website
- 📱 Mobile
- ☁️ Cloud
- 🔌 Network
- 🗄️ Data

Cybersecurity-এর একটি গুরুত্বপূর্ণ ও ব্যবহারিক অংশ হলো — **Penetration Testing**।

> **💡 মনে রাখবেন:** Cybersecurity শুধু "হ্যাকিং ঠেকানো" নয় — এটি Prevention, Detection, Response এবং Recovery — এই চারটি স্তম্ভের সমষ্টি।

---

## ২. Penetration Testing কী?

সহজ ভাষায়, **Penetration Testing (Pentest)** হলো একটি অনুমোদিত (Authorized) Cyber Attack, যেখানে একজন Ethical Hacker ইচ্ছাকৃতভাবে কোনো System-এ আক্রমণ করে তার দুর্বলতা (Vulnerability) খুঁজে বের করেন।

### 🏠 সহজ উদাহরণ

ধরুন আপনার একটি বাড়ি আছে। আপনি একজন Security Expert-কে বললেন — *"আমার বাড়িতে ঢোকার চেষ্টা করুন।"*

তিনি যা করলেন:
- দরজা পরীক্ষা করলেন
- জানালা পরীক্ষা করলেন
- ছাদ পরীক্ষা করলেন

যেখানে দুর্বলতা পেলেন, আপনাকে জানিয়ে দিলেন। ঠিক একই কাজ Digital World-এ করা হয় — শুধু দরজা-জানালার বদলে থাকে সার্ভার, ওয়েবসাইট, নেটওয়ার্ক আর অ্যাপ্লিকেশন।

---

## ৩. Penetration Testing কেন করা হয়?

| ✅ কারণ |
|---|
| Hacker-এর আগে দুর্বলতা খুঁজে বের করতে |
| Security বাড়াতে |
| Customer Data নিরাপদ রাখতে |
| Financial Loss কমাতে |
| Compliance পূরণ করতে |
| Business Reputation রক্ষা করতে |

---

## ৪. Penetration Tester কে?

Penetration Tester হলো এমন একজন **Ethical Hacker** যিনি নিচের বিষয়গুলো পরীক্ষা করে Vulnerability বের করেন:

`Website` · `Server` · `Mobile App` · `API` · `Network` · `Cloud`

---

## ৫. Penetration Testing-এর উদ্দেশ্য

| # | উদ্দেশ্য | ব্যাখ্যা |
|---|---|---|
| 1️⃣ | **Find Vulnerability** | দুর্বলতা বের করা |
| 2️⃣ | **Verify Security** | Security ঠিক আছে কিনা যাচাই করা |
| 3️⃣ | **Risk Assessment** | Risk কত বড় তা নির্ণয় করা |
| 4️⃣ | **Exploit Safely** | নিয়ন্ত্রিতভাবে Attack সম্ভব কিনা যাচাই করা |
| 5️⃣ | **Report** | বিস্তারিত রিপোর্ট প্রদান করা |

---

## ৬. Penetration Testing-এর ধরন

| ধরন (Type) | বিবরণ |
|---|---|
| 🌍 **External** | ইন্টারনেট থেকে Attack — Website, Firewall, VPN |
| 🏢 **Internal** | Company Network-এর ভিতর থেকে Testing |
| 🌐 **Web Application** | ওয়েবসাইট পরীক্ষা |
| 📱 **Mobile Application** | Android ও iOS অ্যাপ পরীক্ষা |
| 🔌 **Network** | LAN, WAN ও WiFi পরীক্ষা |
| 📶 **Wireless** | WiFi Security পরীক্ষা |
| 🔗 **API** | REST API ও GraphQL পরীক্ষা |
| ☁️ **Cloud** | AWS, Azure, GCP পরীক্ষা |
| 📷 **IoT** | Camera, Router, Smart TV পরীক্ষা |

---

## ৭. Penetration Testing Methodology (ওভারভিউ)

Professional Pentest সাধারণত নিচের ধাপগুলো অনুসরণ করে চলে:

```
Planning → Reconnaissance → Scanning → Enumeration → Vulnerability Analysis
   → Exploitation → Privilege Escalation → Post Exploitation
   → Reporting → Remediation → Retesting
```

---

## ৮. ধাপে ধাপে প্রক্রিয়া (Step 1 – Step 10)

<details>
<summary><b>ধাপ ১ — Planning</b></summary><br>

Client-এর সাথে আলোচনা করে নির্ধারণ করা হয়: `Scope` · `Target` · `Timeline` · `Rules` · `Permission`
</details>

<details>
<summary><b>ধাপ ২ — Reconnaissance (Information Gathering)</b></summary><br>

**Passive Recon:** Google, WHOIS, DNS, LinkedIn, GitHub, Shodan

**Active Recon:** Ping, Traceroute, DNS Lookup, Port Scan
</details>

<details>
<summary><b>ধাপ ৩ — Scanning</b></summary><br>

Target-এ কোন Port খোলা আছে দেখা হয় (22, 80, 443, 3306, 3389)।

**Tool:** `Nmap` · `Masscan` · `Rustscan`
</details>

<details>
<summary><b>ধাপ ৪ — Enumeration</b></summary><br>

Service সম্পর্কে বিস্তারিত জানা হয় — SMB, FTP, SSH, SNMP, LDAP।
</details>

<details>
<summary><b>ধাপ ৫ — Vulnerability Analysis</b></summary><br>

**Tool:** `Nessus` · `OpenVAS` · `Nikto` · `Burp Scanner` · `Nuclei`
</details>

<details>
<summary><b>ধাপ ৬ — Exploitation</b></summary><br>

দুর্বলতা কাজে লাগিয়ে Access নেওয়া হয়: SQL Injection, Command Injection, XSS, LFI, RCE, Buffer Overflow
</details>

<details>
<summary><b>ধাপ ৭ — Privilege Escalation</b></summary><br>

Low User → Root / Administrator হওয়ার চেষ্টা করা হয়।
</details>

<details>
<summary><b>ধাপ ৮ — Post Exploitation</b></summary><br>

শুধু অনুমোদিত সীমার মধ্যে: Persistence, Lateral Movement, Credential Collection, Impact Analysis
</details>

<details>
<summary><b>ধাপ ৯ — Reporting</b></summary><br>

Report-এ থাকে: Executive Summary, Risk Level, CVSS Score, Finding, Screenshot, PoC, Recommendation
</details>

<details>
<summary><b>ধাপ ১০ — Retesting</b></summary><br>

Fix করার পরে আবার Test করে নিশ্চিত করা হয় যে দুর্বলতা সমাধান হয়েছে।
</details>

---

## ৯. Penetration Tester হতে যা জানতে হবে

### 🌐 Networking
`OSI Model` `TCP/IP` `DNS` `DHCP` `HTTP/HTTPS` `ARP` `ICMP` `FTP/SSH/SMTP` `Routing` `Switching` `Subnetting` `VPN` `Firewall` `Proxy` `Load Balancer`

### 🐧 Linux
`Commands` `Permissions` `Users` `Services` `SSH` `Cron` `Logs` `Bash`

### 🪟 Windows
`Active Directory` `PowerShell` `CMD` `Registry` `SMB` `NTFS Permission` `Event Logs`

### 💻 Web
`HTML/CSS/JS` `HTTP` `Cookie/Session` `JWT` `REST API` `GraphQL` `CORS`

### 🗄️ Database
`MySQL` `PostgreSQL` `MSSQL` `MongoDB` `SQLite`

### 🧑‍💻 Programming (গুরুত্ব অনুযায়ী)

| ভাষা | গুরুত্ব |
|---|---|
| Python | ⭐⭐⭐⭐⭐ |
| Bash | ⭐⭐⭐⭐ |
| PowerShell | ⭐⭐⭐⭐ |
| JavaScript | ⭐⭐⭐ |
| C | ⭐⭐⭐ |
| PHP | ⭐⭐ |
| Go | ⭐⭐ |

---

## ১০. গুরুত্বপূর্ণ Tools

| ক্যাটাগরি | Tools |
|---|---|
| 🔍 **Recon** | Nmap, Masscan, Rustscan, Amass, Subfinder, Assetfinder, Whois, theHarvester, Shodan, Maltego |
| 🌐 **Web** | Burp Suite, OWASP ZAP, Nikto, ffuf, Gobuster, Dirsearch, WhatWeb |
| 💥 **Exploitation** | Metasploit, SQLMap, Hydra, John, Hashcat, CrackMapExec (NetExec), Impacket |
| 📶 **Wireless** | Aircrack-ng, Kismet, Bettercap |
| 🔑 **Password** | Hydra, Hashcat, John the Ripper |
| 🏢 **Active Directory** | BloodHound, Certipy, NetExec, Rubeus, Mimikatz *(শুধুমাত্র অনুমোদিত ল্যাবে)* |

---

## ১১. Kali Linux কেন?

- ✅ ৬০০+ Security Tools প্রি-ইনস্টলড
- ✅ Preconfigured
- ✅ সম্পূর্ণ Free ও Open Source
- ✅ Linux Based — স্ক্রিপ্টিং সহজ
- ✅ Industry-তে Professional Standard

---

## ১২. Report Writing

একটি Professional Report-এ থাকে:

`Executive Summary` `Scope` `Methodology` `Findings` `Severity` `Screenshot` `Recommendation` `Appendix`

> **📝 পরামর্শ:** রিপোর্ট এমনভাবে লিখুন যেন একজন Non-Technical ম্যানেজারও Executive Summary পড়ে ঝুঁকি বুঝতে পারেন, আবার একজন ডেভেলপারও Technical অংশ থেকে ঠিক কী Fix করতে হবে তা বুঝতে পারেন।

---

## ১৩. Severity (গুরুত্বের মাত্রা)

| Severity | ব্যাখ্যা |
|---|---|
| 🔴 **Critical** | তাৎক্ষণিক ও গুরুতর ক্ষতির সম্ভাবনা — অবিলম্বে সমাধান প্রয়োজন |
| 🟠 **High** | গুরুত্বপূর্ণ ঝুঁকি — দ্রুত সমাধান প্রয়োজন |
| 🟡 **Medium** | মাঝারি ঝুঁকি — পরিকল্পনা করে সমাধান করা উচিত |
| 🟢 **Low** | সীমিত প্রভাব — সময় সুযোগমতো সমাধান করা যায় |
| ⚪ **Informational** | সরাসরি ঝুঁকি নয়, তবে সচেতনতার জন্য উল্লেখযোগ্য |

---

## ১৪. Penetration Testing Standards

- **PTES** (Penetration Testing Execution Standard)
- **OWASP** Web Security Testing Guide (WSTG)
- **NIST** SP 800-115
- **OSSTMM** (Open Source Security Testing Methodology Manual)

---

## ১৫. Certifications

| স্তর | সার্টিফিকেশন |
|---|---|
| 🟢 Beginner | Google Cybersecurity, ISC2 CC, CompTIA Security+ |
| 🟡 Intermediate | eJPT, PNPT, CompTIA PenTest+ |
| 🟠 Advanced | OSCP, OSEP, CRTO, CRTP, CPTS |
| 🔴 Expert | OSCE³, GXPN |

---

## ১৬. Career Path

```
IT Support → System Administrator → Network Engineer → SOC Analyst
   → Junior Penetration Tester → Penetration Tester → Senior Penetration Tester
   → Red Team Operator → Security Consultant → Security Architect
```

---

## ১৭. Lab Setup

```
VMware / VirtualBox → Kali Linux → Windows → Metasploitable
   → OWASP Juice Shop → DVWA → OWASP Broken Web Apps
   → VulnHub → Hack The Box → TryHackMe → PortSwigger Web Security Academy
```

---

## ১৮. Learning Roadmap

```
Computer Basics → Networking → Linux → Windows → Programming → Web → Database
   → Cybersecurity Basics → Kali Linux → Nmap → Burp Suite → OWASP Top 10
   → Web Exploitation → Privilege Escalation → Active Directory → Cloud Security
   → CTF Practice → Bug Bounty → Professional Penetration Testing → OSCP
```

---

## ১৯. একজন ভালো Penetration Tester-এর Soft Skills

`Problem Solving` `Critical Thinking` `Curiosity` `Patience` `Report Writing` `Communication` `Documentation` `Teamwork` `Time Management` `Continuous Learning`

---

## ২০. আইন ও নৈতিকতা (Legal & Ethics)

> **⚠️ গুরুত্বপূর্ণ:** Penetration Testing শুধুমাত্র লিখিত অনুমতি (Written Authorization) নিয়ে করতে হবে। অনুমতি ছাড়া কোনো সিস্টেমে স্ক্যান, এক্সপ্লয়ট বা প্রবেশের চেষ্টা করা আইনগতভাবে অপরাধ হতে পারে।

সর্বদা মেনে চলুন:
- Scope মেনে চলুন
- পরীক্ষার সময় ডেটা নষ্ট করবেন না
- প্রয়োজনীয় প্রমাণ সংগ্রহ করুন, কিন্তু অপ্রয়োজনীয় ডেটা কপি করবেন না
- দায়িত্বশীলভাবে Vulnerability রিপোর্ট করুন (Responsible Disclosure)

---

## ২১. OWASP Top 10 (Web Security)

1. Broken Access Control
2. Cryptographic Failures
3. Injection
4. Insecure Design
5. Security Misconfiguration
6. Vulnerable and Outdated Components
7. Identification and Authentication Failures
8. Software and Data Integrity Failures
9. Security Logging and Monitoring Failures
10. Server-Side Request Forgery (SSRF)

---

## ২২. Pentest-এর Deliverables

`Rules of Engagement` `Scope Document` `Test Plan` `Evidence` `Vulnerability Report` `Executive Summary` `Technical Report` `Remediation Guide` `Retest Report`

---

## ২৩. Frequently Used Frameworks

`MITRE ATT&CK` `CVSS` `CVE` `CWE` `CAPEC` `OWASP Testing Guide` `PTES` `NIST Cybersecurity Framework`

---

## ২৪. পরিভাষা (Glossary)

| Term | ব্যাখ্যা |
|---|---|
| **Vulnerability** | সিস্টেমে থাকা দুর্বলতা, যা কাজে লাগিয়ে আক্রমণ করা সম্ভব |
| **Exploit** | Vulnerability কাজে লাগিয়ে প্রবেশের কোড বা কৌশল |
| **Payload** | Exploit সফল হওয়ার পর টার্গেটে চালানো প্রকৃত কোড |
| **Zero-day** | এমন দুর্বলতা যা এখনো নির্মাতা জানে না বা প্যাচ হয়নি |
| **Shell** | টার্গেটে কমান্ড চালানোর জন্য পাওয়া অ্যাক্সেস |
| **Reverse Shell** | টার্গেট নিজে থেকে Attacker-এর মেশিনে সংযোগ পাঠায় |
| **Bind Shell** | টার্গেটে একটি Port খোলা থাকে, Attacker সেখানে সংযোগ করে |
| **Privilege Escalation** | সীমিত অ্যাক্সেস থেকে Admin/Root-এ পৌঁছানোর প্রক্রিয়া |
| **Lateral Movement** | এক সিস্টেম থেকে নেটওয়ার্কের অন্য সিস্টেমে প্রবেশ |
| **Social Engineering** | মানুষের মনস্তত্ত্ব ব্যবহার করে তথ্য হাতানোর কৌশল |
| **Red Team** | প্রকৃত আক্রমণকারীর মতো আচরণ করে নিরাপত্তা যাচাইকারী দল |
| **Blue Team** | নিরাপত্তা রক্ষা ও প্রতিরোধকারী দল |
| **Purple Team** | Red ও Blue Team-এর সমন্বয়কারী দল |
| **CVSS Score** | দুর্বলতার গুরুত্ব ০–১০ স্কেলে প্রকাশের মানদণ্ড |
| **Bug Bounty** | দুর্বলতা খুঁজে দেওয়ার বিনিময়ে পুরস্কার প্রদানের কর্মসূচি |

---

## ২৫. নমুনা রিপোর্ট টেমপ্লেট

```markdown
### Finding #01 — [দুর্বলতার নাম]

- Title: SQL Injection in Login Form
- Severity: Critical / High / Medium / Low / Informational
- CVSS Score: 9.8
- Affected Asset: URL / IP / Endpoint
- Description: দুর্বলতাটি কী এবং কেন এটি ঝুঁকিপূর্ণ
- Steps to Reproduce: ধাপে ধাপে বিবরণ
- Proof of Concept (PoC): স্ক্রিনশট / কমান্ড আউটপুট
- Impact: সফল হলে কী ক্ষতি হতে পারে
- Recommendation: কীভাবে সমাধান করা যায়
- References: OWASP / CWE / CVE লিংক
```

---

## ২৬. সাধারণ ভুল যা এড়ানো উচিত

- ❌ লিখিত অনুমতি ছাড়া টেস্টিং শুরু করা
- ❌ Scope-এর বাইরে থাকা সিস্টেমে স্ক্যান/এক্সপ্লয়ট চালানো
- ❌ শুধু Tool চালিয়ে ফলাফল বিশ্বাস করা, Manual Verification না করা
- ❌ প্রতিটি ধাপে Screenshot/Evidence সংগ্রহ না করা
- ❌ Report-এ শুধু কারিগরি ভাষা ব্যবহার করা
- ❌ Networking ও Linux-এর ভিত্তি মজবুত না করেই Tool শেখা শুরু করা
- ❌ একটি মাত্র Tool/Technique-এর উপর অতিরিক্ত নির্ভরশীলতা
- ❌ Client-এর ডেটা অপ্রয়োজনে সংগ্রহ/সংরক্ষণ করা
- ❌ Retesting ও Remediation Verification উপেক্ষা করা
- ❌ নিয়মিত অনুশীলন (CTF/Lab) ছাড়া শুধু তত্ত্ব পড়া

---

## ২৭. প্রায়শই জিজ্ঞাসিত প্রশ্ন (FAQ)

<details>
<summary><b>Penetration Testing শিখতে কি প্রোগ্রামিং জানা বাধ্যতামূলক?</b></summary><br>
শুরুতে বাধ্যতামূলক না হলেও, পেশাদার পর্যায়ে Python ও Bash-এর মতো ভাষা জানা অত্যন্ত গুরুত্বপূর্ণ — Automation ও কাস্টম Script লেখার জন্য প্রয়োজন হয়।
</details>

<details>
<summary><b>Penetration Testing এবং Ethical Hacking কি একই জিনিস?</b></summary><br>
কাছাকাছি হলেও পুরোপুরি এক নয়। Ethical Hacking একটি বিস্তৃত ধারণা, আর Penetration Testing হলো নির্দিষ্ট Scope ও Methodology অনুসরণ করে করা কাঠামোবদ্ধ টেস্টিং প্রক্রিয়া।
</details>

<details>
<summary><b>Bug Bounty করার জন্য কি Certification লাগবে?</b></summary><br>
বাধ্যতামূলক না হলেও Certification দক্ষতা প্রমাণ করতে সাহায্য করে। Bug Bounty-তে মূলত ব্যবহারিক দক্ষতা ও প্রমাণিত ফলাফলই বেশি গুরুত্বপূর্ণ।
</details>

<details>
<summary><b>OSCP করার আগে কী কী শেখা উচিত?</b></summary><br>
Networking, Linux, Windows Administration, Web Fundamentals এবং Nmap ও Burp Suite-এর মতো মৌলিক Tool-এ দক্ষতা অর্জনের পর, TryHackMe ও Hack The Box-এ পর্যাপ্ত অনুশীলন করে OSCP-তে অংশ নেওয়া উচিত।
</details>

<details>
<summary><b>নিজের ল্যাব ছাড়া কি Penetration Testing শেখা সম্ভব?</b></summary><br>
সম্ভব নয় বললেই চলে। বাস্তব অনুশীলন ছাড়া শুধু তত্ত্ব পড়ে দক্ষতা অর্জন করা যায় না — VirtualBox/VMware দিয়ে নিজের ল্যাব তৈরি করা জরুরি।
</details>

---

## ২৮. চূড়ান্ত সারসংক্ষেপ ও রোডম্যাপ

একজন Professional Penetration Tester হতে হলে দক্ষ হতে হবে:

`Computer Fundamentals` · `Networking` · `Linux/Windows Administration` · `Programming` · `Web Technologies` · `Databases` · `Cryptography Basics` · `Vulnerability Assessment` · `Exploitation Techniques` · `Privilege Escalation` · `Active Directory Security` · `Cloud Security` · `Kali Linux & Tools` · `Report Writing` · `Legal & Ethical Practices`

> নিয়মিত **CTF, ল্যাব ও বাস্তবসম্মত অনুশীলন** — এই তিনটিই দীর্ঘমেয়াদে সবচেয়ে বড় পার্থক্য তৈরি করে।

---

<div align="center">

### 📌 এই ডকুমেন্টকে আরও উন্নত করতে

১০০–২০০ পৃষ্ঠার পূর্ণাঙ্গ বই বানাতে চাইলে প্রতিটি টুলের Live Command Example, স্ক্রিনশটসহ ওয়াকথ্রু, ল্যাব এক্সারসাইজ, পূর্ণ রিপোর্ট টেমপ্লেট এবং বাস্তব Case Study যোগ করা যেতে পারে।

**⭐ যদি এই ডকুমেন্টেশন কাজে লাগে, একটি স্টার দিতে ভুলবেন না!**

</div>

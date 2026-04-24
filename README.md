# 🔐 Password Cracking & Credential Attack Suite

## 📌 Password Policy Testing and Credential Security Assessment Toolkit

A comprehensive cybersecurity toolkit designed to simulate **password attacks** and perform **credential security assessments** in a controlled and ethical environment. This project helps understand how attackers exploit weak passwords and how defenders can strengthen authentication systems.

---

## 📖 Project Overview

Weak passwords remain one of the most critical vulnerabilities in modern systems. This toolkit demonstrates real-world attack techniques such as:

- Dictionary Attacks  
- Brute-Force Attacks  
- Credential Stuffing  
- Password Hash Analysis  

It provides a **hands-on learning platform** for cybersecurity students, ethical hackers, and penetration testers.

---

## 🎯 Project Objectives

- Develop a **dictionary generator** for password testing  
- Extract password hashes from **Linux (/etc/shadow)** and **Windows (SAM)**  
- Build a **brute-force simulation engine**  
- Analyze password strength using **entropy & complexity**  
- Generate a **security audit report** with mitigation strategies  

---

## ⚙️ Key Modules

### 📂 Dictionary Generator
- Creates custom wordlists using:
  - Names, DOBs, patterns  
  - Common passwords  
- Supports mutations:
  - Leet-speak (e.g., `@`, `3`)  
  - Upper/lowercase variations  
  - Numbers & symbols  

---

### 🔑 Hash Extraction Module
- Extracts password hashes from:
  - Linux `/etc/shadow`  
  - Windows SAM & SYSTEM files  
- Identifies hashing algorithms:
  - MD5  
  - SHA-512  
  - NTLM  

---

### 🚀 Brute-Force Simulator
- Simulates password cracking attempts  
- Supports:
  - a–z, A–Z, 0–9, symbols  
- Provides:
  - Estimated time-to-crack  
  - Password resistance metrics  

---

### 🧠 Password Strength Analyzer
- Evaluates:
  - Complexity  
  - Entropy  
  - Predictability  
- Detects weak/dictionary-based passwords  
- Suggests improvements  

---

### 📊 Report Generation
- Generates detailed audit reports:
  - Weak passwords detected  
  - Attack simulation results  
  - Security recommendations  

---

## 🛠️ Technologies Used

### Programming
- Python (Primary)
- Bash (Optional)

### Libraries & Tools
- `hashlib`
- `crypt` / `passlib`
- `reg.exe`
- Reference Tools:
  - John the Ripper  
  - Hashcat  

### Documentation
- MS Word / Google Docs  
- Draw.io (Flowcharts)  

---


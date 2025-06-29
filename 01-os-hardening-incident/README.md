# Security Incident Report – OS Hardening & Web Defacement

## 📄 Description
This project simulates a brute-force attack followed by web defacement via malware injection on a Linux-based server. It demonstrates how weak access controls can lead to full system compromise.

## 🧰 Tools & Skills
- Tools: Manual log review, Linux CLI
- Skills: Incident response, OS hardening, detection of web compromise

## 🧪 Scenario
A default admin account without 2FA was brute-forced. The attacker gained access to the web directory and injected malicious code, redirecting visitors to an external phishing site.

## 📊 Key Evidence
- Suspicious login at 03:41 AM from IP 103.80.3.21
- Webpage defacement with `<script>` redirect tags
- DNS query spike to `notasecurepage.top`

## ✅ Outcome & Mitigation
- Enforce strong passwords and MFA
- Limit login attempts and monitor failed auth logs
- Patch web server and restrict web folder permissions

## 📚 References
- MITRE ATT&CK: T1110 (Brute Force), T1059 (Command and Scripting Interpreter)

# Ethical Hacking Lab Assessment

## 📄 Full Technical Report
👉 [View Report](./report/ethical-hacking-report.pdf)

## Overview
Hands-on penetration testing engagement conducted in a controlled lab environment to identify, exploit, and mitigate system vulnerabilities.

## 🔑 Key Phases
- Reconnaissance (Passive + Active)
- Scanning (Nmap, NSE)
- Vulnerability Analysis
- Exploitation (MS17-010 / EternalBlue)
- Post Exploitation (Persistence, Keylogging)
- Covering Tracks

## 🔍 Key Findings
- Identified critical SMB vulnerability (MS17-010 / EternalBlue)
- Discovered open ports and exposed services through network scanning
- Weak system configurations increased attack surface
- Lack of monitoring enabled stealthy post-exploitation persistence

## ⚠️ Security Impact
- Full system compromise possible
- Unauthorized access to sensitive data
- Potential lateral movement within the network
- Risks to confidentiality, integrity, and availability (CIA triad)

## 🛡️ Mitigation Strategies
- Apply security patches (MS17-010 fix)
- Disable unnecessary services and close unused ports
- Implement IDS/IPS and monitoring systems
- Enforce strong access controls
- Apply network segmentation

## 🛠️ Tools Used
- Kali Linux
- Nmap
- Metasploit
- Wireshark

## 📌 Conclusion
This project demonstrates a complete penetration testing lifecycle, highlighting how vulnerabilities can be identified, exploited, and mitigated in a controlled environment.

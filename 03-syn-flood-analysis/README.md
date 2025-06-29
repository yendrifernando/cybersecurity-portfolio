
---

### 📁 03-syn-flood-analysis/README.md

```markdown
# SYN Flood Attack Analysis – TCP Exploitation Report

## 📄 Description
This project explains how SYN flood attacks exploit the TCP handshake, causing denial-of-service (DoS) by exhausting server resources.

## 🧰 Tools & Skills
- Tools: Wireshark (simulated), TCPDump concepts
- Skills: Network layer analysis, DoS detection, protocol understanding

## 📊 Attack Pattern
- Repeated SYN packets without completing 3-way handshake
- Server SYN queue saturation and unresponsive state observed

## 📘 TCP Flow Diagram
Included: Handshake diagram + SYN flood visualization

## ✅ Outcome & Mitigation
- Enable SYN cookies on the server
- Adjust backlog queue size
- Configure rate limits via firewall

## 📚 MITRE Reference
- T1499.001 (Endpoint DoS: OS Exhaustion Flood)


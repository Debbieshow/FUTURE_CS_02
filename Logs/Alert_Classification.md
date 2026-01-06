# Alert Classification Log

This document serves as a centralised log for the classification and prioritization of malicious activity detected on the host. It also shows the precise SPL search fragments used for detection.

| Alert Title | Severity | Priority | Affected Host | SPL Search Fragment |
| :--- | :--- | :--- | :--- | :--- |
| 🔴 **Ransomware** | Critical | 1 | `WIN-08TJOV6NBK0` | `action="malware*" threat="ransomware*"` |
| 🔴 **Rootkit Sig** | Critical | 1 | `WIN-08TJOV6NBK0` | `action="malware*" threat="rootkit*"` |
| 🟠 **Trojan Det** | High | 2 | `WIN-08TJOV6NBK0` | `action="malware*" threat="trojan*"` |
| 🟠 **Worm Infe** | High | 2 | `WIN-08TJOV6NBK0` | `action="malware*" threat="Worm*"` |
| 🟡 **Spyware A** | Medium | 3 | `WIN-08TJOV6NBK0` | `action="malware*" threat="spyware*"` |

---

[⬅️ Back to Project Overview](../README.md)

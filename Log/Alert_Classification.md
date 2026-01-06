# Alert Classification Log

This log summarizes the malware threats identified using Splunk. Each alert was triaged based on severity and the specific threat behavior detected on the host.

| Alert Title | Severity | Priority | Affected Host | SPL Search Fragment |
| :--- | :--- | :--- | :--- | :--- |
| 🔴 **Ransomware Behaviour** | Critical | 1 | `WIN-08TJOV6NBK0` | `threat="ransomware*"` |
| 🔴 **Rootkit Signature** | Critical | 1 | `WIN-08TJOV6NBK0` | `threat="rootkit*"` |
| 🟠 **Trojan Detected** | High | 2 | `WIN-08TJOV6NBK0` | `threat="trojan*"` |
| 🟠 **Worm Infection Attempt** | High | 2 | `WIN-08TJOV6NBK0` | `threat="Worm*"` |
| 🟡 **Spyware Alert** | Medium | 3 | `WIN-08TJOV6NBK0` | `threat="spyware*"` |

---
**Triage Logic:**
* 🔴 **Red:** Immediate system isolation required (Critical impact).
* 🟠 **Orange:** Escalated for full system scan and removal (High impact).
* 🟡 **Yellow:** Full scan for removal of malicious components and user credential reset (Medium impact).

[⬅️ Back to Project Overview](../README.md)

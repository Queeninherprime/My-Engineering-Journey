# Domain 5 — Security Operations


---

## 1. Encryption
| Type | How It Works | Example |
|---|---|---|
| **Symmetric** | Same key to encrypt and decrypt | AES |
| **Asymmetric** | Public key encrypts, private key decrypts | RSA |
| **Hashing** | One-way, cannot be reversed | SHA-256, MD5 |

**Data States:**
- **Data at Rest** — Stored data → encrypt hard drives
- **Data in Transit** — Moving data → use TLS/HTTPS
- **Data in Use** — Being processed → hardest to protect

---

## 2. System Hardening
- Remove all unnecessary software
- Apply patches and updates regularly
- Disable unused ports and services
- Enforce strong password policies
- Enable detailed logging and monitoring

---

## 3. Social Engineering Attacks
| Attack | Description |
|---|---|
| **Phishing** | Deceptive email to steal credentials |
| **Vishing** | Voice phishing over phone |
| **Smishing** | SMS/text phishing |
| **Tailgating** | Following someone into a secure area |
| **Pretexting** | Fabricating a scenario to gain trust |

---

## 4. Security Tools
| Tool | Full Name | Purpose |
|---|---|---|
| **SIEM** | Security Info & Event Management | Collect and analyze logs |
| **EDR** | Endpoint Detection & Response | Detect malware on devices |
| **DLP** | Data Loss Prevention | Prevent data leaks |
| **Vuln Scanner** | Vulnerability Scanner | Find system weaknesses |
| **SOAR** | Security Orchestration & Response | Automate IR tasks |

---

## 5. Configuration Management
- **Baseline** — Standard secure configuration for all systems
- **Change Management** — Controlled process for making changes
- **Patch Management** — Keeping all systems up to date

---

## Real World Connection
> SIEM knowledge directly connects to KC7 — Azure
> Data Explorer is essentially a SIEM I use daily.
> Encryption explains why ransomware is so devastating.
> Social engineering is the attack vector in multiple
> KC7 investigations including CloutHaus and Valdoria.

---

## Key Terms
AES, RSA, SHA-256, Symmetric vs Asymmetric,
Hashing, Data at rest/transit/use,
SIEM, EDR, DLP, SOAR,
Social engineering, Hardening,
Patch management, Change management

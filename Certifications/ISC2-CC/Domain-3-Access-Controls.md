# Domain 3 — Access Controls Concepts


---

## 1. Core Principles
- **Least Privilege** — Only minimum access needed for the job
- **Need to Know** — Access only to info required for your role
- **Separation of Duties** — No single person controls everything
- **Defense in Depth** — Multiple layers of security controls

---

## 2. Access Control Models
| Model | Full Name | How It Works | Example |
|---|---|---|---|
| **DAC** | Discretionary | Owner controls access | Shared folder |
| **MAC** | Mandatory | System enforces security labels | Government/military |
| **RBAC** | Role-Based | Access by job role | Hospital staff |
| **ABAC** | Attribute-Based | Access by attributes | Time, location, device |

---

## 3. Authentication Factors
| Factor | Type | Example |
|---|---|---|
| Something you **know** | Knowledge | Password, PIN |
| Something you **have** | Possession | Smart card, token |
| Something you **are** | Inherence | Fingerprint, face |

- **MFA** — Multi Factor Authentication (2 or more factors)
- **SSO** — Single Sign On (one login for multiple systems)

---

## 4. Physical Access Controls
- Badges and keycards
- Biometrics (fingerprint, retina scan)
- Security guards
- CCTV cameras
- Mantrap / airlock doors

---

## 5. Logical Access Controls
- Firewalls
- ACLs (Access Control Lists)
- Passwords and PINs
- Encryption
- Digital certificates

---

## Real World Connection
> RBAC is how SOC teams get access to SIEM tools.
> Least privilege limits damage from insider threats.
> MFA is the #1 defense against phishing attacks
> which I investigate regularly in KC7.

---

## Key Terms
DAC, MAC, RBAC, ABAC,
MFA, SSO, Least privilege,
Need to know, Separation of duties,
ACL, Physical vs Logical controls

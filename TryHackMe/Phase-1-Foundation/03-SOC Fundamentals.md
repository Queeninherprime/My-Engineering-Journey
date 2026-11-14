# TryHackMe - SOC Fundamentals

## 📋 Overview
A documentation of my progression and hands-on investigation exercises completed in the **SOC Fundamentals** room on TryHackMe. This room focuses on the core responsibilities, workflows, and log analysis techniques used by Security Operations Center (SOC) analysts.

---

## 🔍 Key Concepts & Learnings
* **Security Operations Center (SOC) Roles:** Understanding tier-based triage, alert monitoring, and incident response lifecycles.
* **Log Analysis:** Interpreting network and system logs to reconstruct security events.
* **Vulnerability Assessment Identification:** Recognizing network probing, port scans, and scanner signatures (such as Nessus vulnerability scans).

---

## 📝 Hands-On Investigation Example: Analyzing Alert Logs

### Scenario: Investigating an Internal Network Alert
During the alert investigation exercise, logs were analyzed to determine the root cause of high-frequency traffic hitting an internal target.

* **Timeframe Analyzed:** June 12, 2024 (13:25 - 18:25)
* **Source IP / Host:** `10.0.0.8` (`NESSUS`)
* **Destination IP / Host:** `10.0.0.3` (`JOE PC`)
* **Traffic Pattern:** Multiple connection probes across standard service ports (e.g., FTP, SSH, HTTP, HTTPS) originating from a single source port (`6927`).

### 🔎 Conclusion / Trigger Identification
* **Trigger Event:** **Vulnerability Scan** (Nessus Scanner)
* **Analysis:** The logs explicitly identified the source host name as `NESSUS`, indicating an authorized or simulated vulnerability scan targeting `JOE PC` (`10.0.0.3`). The sequential port-probing behavior is a classic signature of vulnerability assessment tools mapping open ports and services.

---

## 🚀 Conclusion
Completing this room strengthened my practical skills in triaging security alerts, reading traffic logs, and distinguishing between malicious reconnaissance and authorized security scanning tools.

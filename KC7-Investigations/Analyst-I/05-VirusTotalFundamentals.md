# Investigation 05 — VirusTotal Fundamentals
**Platform:** KC7 Cyber
**Path:** Security Analyst I — Module 5
**Badge:** VirusTotal Fundamentals
**Badge ID:** 64977
**Date Completed:** June 10, 2026
**Difficulty:** Easy | **Time:** ~1.5 hours

---

## What This Module Covered
Learning how to use VirusTotal as a core
threat intelligence tool in cybersecurity
investigations — analyzing files, URLs,
IP addresses and domains for malicious
indicators.

---

## What Is VirusTotal?
VirusTotal is a free online service that
analyzes files, URLs, domains and IP
addresses using 70+ antivirus engines
and threat intelligence tools simultaneously.
SOC analysts use it daily to determine
whether a file or URL is malicious.

---

## Key Skills Learned

### File Analysis
- Submit suspicious files to VirusTotal
- Interpret detection ratio results
- Read antivirus engine verdicts
- Understand file hash values (MD5, SHA256)
- Identify malware families from detections

### URL and Domain Analysis
- Analyze suspicious URLs for malware
- Check domain reputation scores
- Identify malicious redirect chains
- Investigate domain registration details

### IP Address Analysis
- Check IP reputation against threat feeds
- Identify known malicious IP ranges
- Correlate IPs with attack campaigns
- Use passive DNS data for investigation

### Hash Analysis
- Use file hashes as IOCs
- Search for known malware by hash
- Understand why hashes identify files
- Apply hash lookup in investigations

---

## VirusTotal Key Features Used

| Feature | Purpose |
|---|---|
| Detection tab | Shows which AV engines flagged file |
| Details tab | File metadata and hash values |
| Relations tab | Connected URLs, domains, IPs |
| Behavior tab | What the file does when executed |
| Community tab | Analyst notes and comments |

---

## How This Connects To KC7 Investigations
> VirusTotal is one of the primary
> external tools used in KC7 investigations
> to verify whether indicators of compromise
> (IOCs) are known malicious artifacts.
> When I find a suspicious IP or file hash
> in log data I can immediately check it
> against VirusTotal to confirm malicious intent.

---

## Real World SOC Application
> In a real SOC environment VirusTotal
> is used daily for:
> → Malware triage during incidents
> → Threat hunting for known IOCs
> → Enriching alert data with context
> → Verifying phishing URLs and attachments
> → Building threat intelligence reports

---

## MITRE ATT&CK Connection
| Technique | How VirusTotal Helps |
|---|---|
| T1566 Phishing | Analyze malicious email attachments |
| T1204 User Execution | Check files users are tricked into running |
| T1071 C2 Traffic | Investigate suspicious IP/domain connections |

---

## Badge
**VirusTotal Fundamentals**
Badge ID: 64977
Earned: June 10, 2026
Platform: KC7 Cyber

# 04 - Red Team Fundamentals

**Room Link:** [Red Team Fundamentals on TryHackMe](https://tryhackme.com/room/redteamfundamentals)  
**Date Completed:** November 16, 2026  

## 🎯 Room Objective
Understand the fundamentals of red team engagements, how they differ from standard penetration testing, and the frameworks used to emulate real-world threat actors.

---

## 🧩 Red Team Engagement Cells
A full red team exercise relies on three distinct groups working around a defined Rules of Engagement (RoE):
* **Red Cell (Offensive):** Simulates real-world attackers by emulating their Tactics, Techniques, and Procedures (TTPs) to test defenses quietly.
* **Blue Cell (Defensive):** The internal security team (SOC analysts, incident responders) responsible for detecting, containing, and defending the target network.
* **White Cell (Referee):** Acts as the neutral mediator between the Red and Blue cells—monitoring boundaries, enforcing the Rules of Engagement, and scoring the exercise.

---

## 🔗 Lockheed Martin Cyber Kill Chain
The Cyber Kill Chain breaks down a cyberattack into 7 sequential stages. Breaking any single link stops the attack:

| Stage | Description |
| :--- | :--- |
| **1. Reconnaissance** | Gathering intelligence on the target (OSINT, employee info, network scanning). |
| **2. Weaponization** | Coupling collected info/exploits with a deliverable payload (e.g., an infected document). |
| **3. Delivery** | Transmitting the weaponized payload to the target (phishing email, malicious web link, USB drop). |
| **4. Exploitation** | Triggering a vulnerability (technical flaw or human error) to execute malicious code. |
| **5. Installation** | Installing malware or backdoors on the target system to maintain persistent access. |
| **6. Command & Control (C2)** | Establishing a remote communication channel to manipulate and control the compromised system. |
| **7. Actions on Objectives** | Achieving the final mission goal (e.g., deploying ransomware, exfiltrating sensitive data). |

---

## 🛠️ Tools Mentioned
* **Mimikatz:** A post-exploitation tool commonly used by attackers (and red teams) to dump plaintext passwords, password hashes, and Kerberos tickets from Windows memory (LSASS) to escalate privileges or move laterally.

## 💡 Key Takeaways
While **SOC Fundamentals** taught me how defenders monitor alerts and investigate incidents, **Red Team Fundamentals** showed me the attacker's step-by-step playbook. Understanding each stage of the Cyber Kill Chain makes it much easier to see where Blue Teams can build detections to break an attack before it reaches the final objective.
**Room Link:** [Red Team Fundamentals on TryHackMe](https://tryhackme.com/room/redteamfundamentals)  
**Date Completed:** November 16, 2026  

## 🎯 Room Objective
Understand the fundamentals of red team engagements, how they differ from standard penetration testing, and the frameworks used to emulate real-world threat actors.

---

## 🧩 Red Team Engagement Cells
A full red team exercise relies on three distinct groups working around a defined Rules of Engagement (RoE):
* **Red Cell (Offensive):** Simulates real-world attackers by emulating their Tactics, Techniques, and Procedures (TTPs) to test defenses quietly.
* **Blue Cell (Defensive):** The internal security team (SOC analysts, incident responders) responsible for detecting, containing, and defending the target network.
* **White Cell (Referee):** Acts as the neutral mediator between the Red and Blue cells—monitoring boundaries, enforcing the Rules of Engagement, and scoring the exercise.

---

## 🔗 Lockheed Martin Cyber Kill Chain
The Cyber Kill Chain breaks down a cyberattack into 7 sequential stages. Breaking any single link stops the attack:

| Stage | Description |
| :--- | :--- |
| **1. Reconnaissance** | Gathering intelligence on the target (OSINT, employee info, network scanning). |
| **2. Weaponization** | Coupling collected info/exploits with a deliverable payload (e.g., an infected document). |
| **3. Delivery** | Transmitting the weaponized payload to the target (phishing email, malicious web link, USB drop). |
| **4. Exploitation** | Triggering a vulnerability (technical flaw or human error) to execute malicious code. |
| **5. Installation** | Installing malware or backdoors on the target system to maintain persistent access. |
| **6. Command & Control (C2)** | Establishing a remote communication channel to manipulate and control the compromised system. |
| **7. Actions on Objectives** | Achieving the final mission goal (e.g., deploying ransomware, exfiltrating sensitive data). |

---

## 🛠️ Tools Mentioned
* **Mimikatz:** A post-exploitation tool commonly used by attackers (and red teams) to dump plaintext passwords, password hashes, and Kerberos tickets from Windows memory (LSASS) to escalate privileges or move laterally.

## 💡 Key Takeaways
While **SOC Fundamentals** taught me how defenders monitor alerts and investigate incidents, **Red Team Fundamentals** showed me the attacker's step-by-step playbook. Understanding each stage of the Cyber Kill Chain makes it much easier to see where Blue Teams can build detections to break an attack before it reaches the final objective.

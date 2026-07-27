# Lesson 4. Who's Who in Cybersecurity: Red, Blue, Purple

**Tags:** `#CyberLabEN` `#Block01_LegalEthics` `#Careers`

---

## 🎯 Why

Before diving deep into pentesting, it helps to see the whole map of cybersecurity roles. You'll understand where you stand, who you'll work with, and where you can grow. Pentesting is just one of the doors.

## 📖 Explanation

Cybersecurity splits into two big sides and one that connects them:

### 🔴 Red Team (offense)
Simulate attacks to find holes before criminals do:
- **Penetration Tester** — finds and exploits vulnerabilities, writes reports
- **Red Teamer** — simulates real targeted attacks (APT), stealthy, long-term
- **Bug Bounty Hunter** — finds bugs for rewards on platforms

### 🔵 Blue Team (defense)
Protect and investigate:
- **Security Analyst (SOC)** — monitors, responds to incidents
- **Incident Responder** — investigates attacks as they happen
- **Threat Hunter** — proactively hunts for threats in the network
- **Security Engineer** — designs and builds defenses

### 🟣 Purple Team (the link)
Not separate people but a way of working: Red and Blue collaborate, attackers show defenders how to catch them.

> Important: Red and Blue often share tools (the same Wireshark, the same logs), but the goal is opposite — one looks for a way in, the other closes it.

## 🧠 Remember

> A pentester and a SOC analyst aren't enemies — they're two sides of the same coin. A good pentester understands how defense thinks; a good defender understands how attackers think. That's why this course has both Red and Blue blocks.

## 🔤 Key Terms

- **Red Team** — offensive team
- **Blue Team** — defensive team
- **Purple Team** — Red and Blue working together
- **SOC (Security Operations Center)** — security monitoring center
- **Incident Response** — responding to incidents

## 💻 Commands

This lesson is an overview of roles. But let's practically look at a tool used by BOTH sides — Red and Blue — to grasp the "shared tools" idea.

```bash
whoami
cat /etc/passwd

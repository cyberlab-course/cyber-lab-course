# Lesson 5. Pentest Methodology: The 5 Stages of Any Attack

**Tags:** `#CyberLabEN` `#Block01_LegalEthics` `#Methodology`

---

## 🎯 Why

A pentest isn't chaotically "poking at tools" — it's a clear sequence of stages. Understanding this sequence is what separates a pro from a beginner who runs nmap and doesn't know what's next. This lesson is the map the ENTIRE course is built on.

## 📖 Explanation

Every attack (legal or not) goes through the same stages. Memorize them and you'll always know "what to do next":

| # | Stage | What happens |
|---|-------|--------------|
| 1️ | **Information Gathering** | Collect public data: domains, emails, employees, tech. This is OSINT. Not attacking yet. |
| 2️⃣ | **Enumeration / Scanning** | Actively find what's open: ports, services, versions, directories. nmap, gobuster. |
| 3️⃣ | **Exploitation** | Use a vulnerability to get initial access. The first shell. |
| 4️⃣ | **Privilege Escalation** | Go from limited user to admin/root. Horizontally or vertically. |
| 5️⃣ | **Post-Exploitation** | Persistence, pivoting, data collection, covering tracks, and always — the report. |

This is the skeleton of our course: blocks go in exactly this order — recon → scanning → exploitation → privesc → post-exploitation.

## 🧠 Remember

> If you're stuck on a real machine, return to this map and ask: "which stage am I on and what should come next?" 90% of beginner dead-ends are from skipping a stage (e.g., exploiting before finishing enumeration).

## 🔤 Key Terms

- **Information Gathering** — reconnaissance
- **Enumeration** — listing/scanning services
- **Exploitation** — exploiting a vulnerability
- **Privilege Escalation** — gaining higher privileges
- **Post-Exploitation** — actions after getting access

## 💻 Commands

One representative command per stage — so you see how the methodology looks in practice.

```bash
whois example.com
nmap -sV 10.10.10.5
searchsploit apache 2.4.49
sudo -l
crontab -l

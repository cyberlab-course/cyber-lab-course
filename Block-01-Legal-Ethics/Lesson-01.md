# Lesson 1. What Is Pentesting & Why You Can't Attack Without Permission

**Tags:** `#CyberLabEN` `#Block01_LegalEthics` `#RulesOfEngagement`

---

## 🎯 Why

Before you touch nmap, Burp Suite, or any other tool, you need to understand one thing: **pentesting without written permission is a crime** — even if you "just looked" or "wanted to help." This is the foundation of the entire course.

## 📖 Explanation

Penetration testing (pentest) is an **authorized** simulation of an attack on a system to find vulnerabilities before a real attacker does.

The key word is **authorized**. The difference between a pentester and a criminal isn't the tools (both may have Kali Linux and Metasploit) — it's a single document: **authorization to test**.

Think of it this way: you have a key to someone else's apartment. Entering without asking is breaking and entering. Entering because the owner asked you to check the lock and signed a document is consultancy work. The tool (the key) is the same. The difference is permission.

**What a legal pentest consists of:**

| Component | Meaning |
|-----------|---------|
| **Scope** | Which exact IPs/domains you're allowed to test |
| **Rules of Engagement** | When you can test, which techniques are allowed |
| **Written authorization** | A verbal "yes" is not enough |

## 🧠 Remember

> No signed authorization means no pentest. It's just illegal access to someone else's system (under the US Computer Fraud and Abuse Act and similar laws worldwide).

Even TryHackMe and HTB are a form of permission: by registering, you agree to attack only their machines, not anything else on the internet.

## 🔤 Key Terms

- **Penetration Testing (Pentest)** — an authorized simulated attack
- **Scope** — the boundaries of allowed testing
- **Rules of Engagement (RoE)** — the rules for conducting the test
- **Authorization** — formal permission

## 💻 Commands

```bash
whois tryhackme.com
dig tryhackme.com
nslookup tryhackme.com

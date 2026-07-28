# Lesson 7. Hacking Tools and the Law: The Malware Statute

**Tags:** `#CyberLabEN` `#Block02_Jurisdiction` `#Law`

---

## 🎯 Why

Your Kali box has hundreds of tools, many able to build payloads, exploits, and malicious files. This raises a question that scares beginners: am I already breaking the law just by having these installed? Let's draw the line clearly.

## 📖 Explanation

Most countries have a "malware statute" — a law against creating, using, or distributing malicious programs designed for unauthorized destruction, blocking, modification, copying of data, or defeating security controls. (US: parts of the CFAA; many countries: a dedicated article.)

The key word again is **unauthorized**. Like the access law, it looks not at the tool itself but at the **purpose and permission**.

A plain example:

- `msfvenom` generating a reverse shell for **your** lab machine with your permission — a learning tool
- the same `msfvenom` to infect someone else's computer without consent — now it's malicious-program use

So Metasploit, Burp, sqlmap by themselves are **not** "malware" in the legal sense. Maliciousness comes from **intent and authorization**. A knife in a chef's hand vs a robber's — same object, different crime.

**One nuance: distribution.** Writing real malware and publishing it "for education" can fall under the malware statute even without a specific victim. That's why in this course we do **NOT** write working malware or publish it.

## 🧠 Remember

> The tool doesn't make you a criminal — intent and authorization do. But creating and especially distributing real malicious programs is dangerous even "for educational purposes." Practice only in your own lab and on authorized platforms.

> 📌 Educational material, not legal advice.

## 🔤 Key Terms

- **Malware** — malicious program
- **Dual-use tool** — usable for both defense and attack
- **Payload** — the delivered code
- **Intent** — a legally decisive factor

## 💻 Commands

Let's see how many "dual-use tools" already ship with Kali — to grasp the scale and why purpose, not possession, is what matters.

```bash
ls /usr/share/
which msfvenom nmap sqlmap

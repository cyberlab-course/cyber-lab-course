# Lesson 6. The Law and Pentesting: What Counts as Unauthorized Access

**Tags:** `#CyberLabEN` `#Block02_Jurisdiction` `#Law`

---

## 🎯 Why

In Lesson 1 we said: pentesting without permission is a crime. Now the specifics: WHICH law is broken and what it means. Without this, "legal/illegal" is just words. You need to know the exact line you can't cross.

## 📖 Explanation

Almost every country has a computer-crime law built around one core idea: **unauthorized access**. A few examples:

| Country / Region | Main law |
|------------------|----------|
| USA | Computer Fraud and Abuse Act (CFAA) |
| UK | Computer Misuse Act 1990 |
| EU members | National laws under the Cybercrime Directive |
| Most others | An equivalent statute |

The shared key concept is **authorization**. The law doesn't punish "hacking for curiosity" in the abstract — it punishes accessing someone else's protected data without the owner's permission. Even just **copying or viewing** protected data can count.

Your permission (scope, contract) is exactly what turns "unauthorized access" into lawful testing.

**Jurisdiction matters too:** the law that applies can depend on where you are, where the target is, and where the data lives. Attacking a server in another country can put you under multiple legal systems at once.

## 🧠 Remember

> The owner's authorization is the legal line between a pentester's job and a criminal charge. No authorization = an offense, even if you broke nothing and "just copied" something.

> 📌 This is educational material to understand boundaries, not legal advice. For specific situations, consult a lawyer.

## 🔤 Key Terms

- **Unauthorized access** — the core of most computer-crime laws
- **Jurisdiction** — which legal system applies
- **CFAA / Computer Misuse Act** — example national laws
- **Critical Information Infrastructure (CII)** — specially protected systems

## 💻 Commands

Practice here isn't attacking — it's learning to check who owns a resource before doing anything.

```bash
whois example.com
dig example.com +short

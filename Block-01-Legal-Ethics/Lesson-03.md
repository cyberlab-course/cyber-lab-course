# Lesson 3. Scope and Rules of Engagement — The Lines You Can't Cross

**Tags:** `#CyberLabEN` `#Block01_LegalEthics` `#RulesOfEngagement`

---

## 🎯 Why

Permission to pentest isn't "do whatever you want." It's a document with clear boundaries: what to test, when, and with which methods. Crossing those lines — even accidentally — turns legal work into a violation. This lesson is about reading and respecting those boundaries.

## 📖 Explanation

Before any pentest, the client and tester agree on two things:

**Scope** — what exactly can be tested:
- specific IP addresses and ranges
- specific domains and subdomains
- specific applications

Anything not in scope is off-limits. Even if you "stumbled on it by accident."

**Rules of Engagement (RoE)** — how you can test:
- when (e.g., only at night, so business isn't disrupted)
- which techniques are allowed (DoS? social engineering? physical access?)
- what to do if you find a critical vulnerability right now
- emergency contacts

**Three testing types by amount of information:**

| Type | Description |
|------|-------------|
| **Black box** | No internal info, like a real attacker (realistic but slow) |
| **White box** | You have source and access (fast bug-finding, less realistic) |
| **Grey box** | Partial info (a balance of speed and realism) |

## 🧠 Remember

> Going out of scope is a violation even if you broke or stole nothing. The mere act of scanning outside allowed boundaries is already a contractual and legal problem.

A signed **Statement of Work** and scoping document must exist before you start. No signature, no test.

## 🔤 Key Terms

- **Scope** — the boundaries of allowed testing
- **Rules of Engagement (RoE)** — the rules for conducting the test
- **Statement of Work (SoW)** — the document describing the work
- **Black / White / Grey box** — testing types by amount of information

## 💻 Commands

This lesson is about documents, not tools. But there's one practical skill — learning to check whether an IP falls within the allowed range.

```bash
nmap -sL 10.10.10.0/24

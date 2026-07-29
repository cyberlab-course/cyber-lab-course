# Lesson 11. Working Legally as a Pentester: Freelance vs In-House

**Tags:** `#0xRootEN` `#Block02_Jurisdiction` `#Career`

---

## 🎯 Why

You've learned the laws and boundaries. Now the practical question: how do you actually start working as a pentester without breaking anything? Freelance or in a company — each path has its own legality rules. Let's cover what to check BEFORE taking your first job.

## 📖 Explanation

There are two main paths to working as a pentester:

### 1️⃣ In-house (company employee)

You're staff, testing your employer's systems. Legality comes from:

- an employment contract
- an internal authorization to run tests
- a clearly defined scope from management

**Pro:** legally simpler, the company carries responsibility. **Con:** limited to one infrastructure.

### 2️⃣ Freelance / contractor (external pentester)

You work under a contract with a client. Legality comes from:

- a testing services contract
- a signed authorization letter
- a document with scope and Rules of Engagement
- sometimes an NDA

**Pro:** varied projects, higher income. **Con:** all legal responsibility is on you — no papers, no protection.

### Checklist BEFORE any job

| ✅ | Check |
|----|-------|
| ☐ | Written permission from whoever REALLY owns the system? |
| ☐ | Does the person ordering have the right to authorize it? |
| ☐ | Is the scope defined precisely (IPs, domains, off-limits)? |
| ☐ | Are time windows and forbidden techniques specified? |
| ☐ | Is the "critical vuln found" procedure written down? |

## 🧠 Remember

> The most common legal mistake of a beginner freelancer — starting a test when the client is NOT the system's owner. For example, being asked to "check a competitor's site" or "test a server we rent." Always verify: does the client have the right to authorize a test of THIS specific system?

> 📌 Educational material, not legal advice.

## 🔤 Key Terms

- **In-house** — an employee inside the company
- **Contractor / Freelancer** — external hired tester
- **Authorization letter** — written permission
- **NDA (Non-Disclosure Agreement)**
- **Statement of Work (SoW)** — the work description

## 💻 Commands

A practical skill — recording your work (when you started, what you did) for your own protection. A simple way to log terminal actions.

```bash
script -a pentest_log_$(date +%F).txt
exit

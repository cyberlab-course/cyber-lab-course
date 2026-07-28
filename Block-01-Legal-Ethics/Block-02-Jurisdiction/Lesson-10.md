# Lesson 10. Personal Data: What to Do With What You Find

**Tags:** `#CyberLabEN` `#Block02_Jurisdiction` `#PersonalData`

---

## 🎯 Why

During a pentest you almost always run into personal data: user databases, emails, passports, card numbers. What may you do with it, and what is absolutely forbidden? A mistake here turns a legal pentester into a data-protection offender. Let's cover the rules of handling.

## 📖 Explanation

Personal data processing is regulated everywhere — **GDPR** in the EU, national data-protection laws elsewhere. **Personal data (PII)** is any information relating to an identifiable person: name, address, phone, email, passport, health data, biometrics, etc.

**Key principle for a pentester:** you found a hole exposing PII — that's a finding you must **DOCUMENT** (as vulnerability evidence), but must **NOT** bulk-download, copy to yourself, store, or use.

Handling PII correctly on a pentest:

- Found a vulnerability exposing a PII database → record the **fact** (screenshot of structure, a couple of anonymized records as proof)
- Do **NOT** dump the whole database "to show it's serious"
- In the report, describe the **vulnerability**, not people's actual data
- **Anonymize** examples (replace real data with XXX)

**Why it matters:** even if you test a system legally under contract, bulk-copying PII and storing it is a separate violation beyond "a security check." Your scope is to find the hole, not to collect a database.

GDPR fines for mishandling personal data are among the largest in the world.

## 🧠 Remember

> Personal data found during a test is vulnerability evidence, not your trophy. Record the fact minimally, anonymize, don't bulk-download. "I downloaded the whole database to show scale" is a violation, not good work.

> 📌 Educational material, not legal advice.

## 🔤 Key Terms

- **Personal Data (PII)** — personally identifiable information
- **Data minimization** — take only what's necessary
- **Anonymization** — removing identifying details
- **Data breach** — a data leak

## 💻 Commands

A practical skill — anonymizing data in output before putting it in a report. Here's a simple sed example.

```bash
echo "john@mail.com, +15551234567" | sed -E 's/[a-z]+@/XXX@/; s/[0-9]{10}/XXXXXXXXXX/'

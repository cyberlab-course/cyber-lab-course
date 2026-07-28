# Lesson 8. Critical Infrastructure (CII): The Red Line

**Tags:** `#CyberLabEN` `#Block02_Jurisdiction` `#CII`

---

## 🎯 Why

Some systems must never be touched without special authorization — even if you stumble onto them during recon. That's critical infrastructure. The penalties for attacking it are the harshest of all. This lesson is about recognizing it and staying away.

## 📖 Explanation

**Critical Information Infrastructure (CII)** means the systems society and the state depend on. Most countries protect it with dedicated laws and heavier penalties (US: parts of CFAA + sector rules; UK: CNI framework; EU: NIS2 Directive; and national equivalents worldwide).

CII objects usually cover:

| Sector | Examples |
|--------|----------|
| Healthcare | hospitals, medical systems |
| Energy | power plants, grids |
| Transport | aviation, rail, metro |
| Finance | banks, payment systems |
| Communications | telecom, ISPs |
| Defense | military industry |
| Nuclear | nuclear power |
| Government | public services |

**Why it's a separate "red line":** a mistake on an ordinary website is a data leak. A mistake on a CII object could mean a hospital halting, a city losing power, transport failing. That's why the law punishes attacks on CII more severely than ordinary unauthorized access.

**Practical takeaway:** if during recon (even legal Bug Bounty) you realize the target is a bank, hospital, power system, or government service — stop and check whether it's in the allowed scope. Many Bug Bounty programs explicitly exclude CII systems.

## 🧠 Remember

> CII isn't "a harder target" — it's "a target you can't touch without special authorization." Accidentally hit a CII object during a test — stop immediately, document, report to the client. Don't "explore a bit more out of curiosity."

> 📌 Educational material, not legal advice.

## 🔤 Key Terms

- **Critical Information Infrastructure (CII)**
- **Critical National Infrastructure (CNI)**
- **SCADA / ICS** — industrial control systems
- **Out of scope** — outside allowed boundaries

## 💻 Commands

Practice — learning to tell what sector a target belongs to from indirect signs, BEFORE any active action.

```bash
whois <domain>
dig <domain> +short
curl -sI https://<domain>

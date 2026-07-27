# Lesson 2. Responsible Disclosure

**Tags:** `#CyberLabEN` `#Block01_LegalEthics` `#ResponsibleDisclosure`

---

## 🎯 Why

You found a vulnerability — now what? A wrong move turns a great find into a legal problem for you. This lesson is about reporting bugs so you get a thank-you, not a lawsuit.

## 📖 Explanation

**Responsible Disclosure** is the process where a researcher reports a found vulnerability to the system owner privately, gives time to fix it, and only then (or never) publishes the details.

The opposite is **Full Disclosure** (publishing immediately, without warning). This almost always creates the risk that attackers exploit the flaw before a patch is out.

**Difference between Responsible Disclosure and Bug Bounty:**

| Type | Meaning |
|------|---------|
| **VDP** (Vulnerability Disclosure Program) | A "found a bug → report here" channel, no money |
| **Bug Bounty** | The same, but with payment per vulnerability (HackerOne, Bugcrowd) |

**The standard disclosure lifecycle:**

1. You find a vulnerability
2. You report it to the owner privately (email / VDP form)
3. You give a reasonable time to fix (often **90 days** — the industry standard)
4. After the patch — you may publish details (if the policy allows)

## 🧠 Remember

> Publishing vulnerability details before a patch is out — even with good intentions — can be used by attackers and legally treated as aiding an attack.

A company having no public VDP policy does **NOT** equal permission to test its systems.

## 🔤 Key Terms

- **Responsible Disclosure** — private reporting, then delayed publication
- **Full Disclosure** — immediate full publication
- **Vulnerability Disclosure Program (VDP)** — a reporting channel
- **Safe Harbor** — legal protection for good-faith researchers

## 💻 Commands

```bash
searchsploit apache 2.4.49
curl https://services.nvd.nist.gov/rest/json/cves/2.0?cveId=CVE-2021-41773

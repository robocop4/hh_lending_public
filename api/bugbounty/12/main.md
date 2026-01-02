# Bug Bounty Program — Zoho

## Product Overview

Zoho is a global software company offering a wide range of cloud-based business, productivity, and collaboration products used by millions of customers worldwide. Protecting customer data is Zoho’s top priority, and security is deeply integrated into the design, development, and operation of all Zoho services and owned assets.

---

## Bug Bounty & Vulnerability Reward Program Summary

Zoho operates a **Vulnerability Reward Program (VRP)** to continuously improve the security of its products and infrastructure. Security researchers are encouraged to responsibly report potential vulnerabilities, and Zoho may offer monetary rewards at its discretion based on factors such as severity, impact, and exploitability.

Participation in the program implies acceptance of the official **Bug Bounty Terms and Conditions**.

---

## Program Eligibility

Participation is open to most individuals, except if:

- You are under 14 years old (minors must have parental or legal guardian consent)
- You are a resident of a US-sanctioned country
- You are a current Zoho employee or were employed by Zoho within the last 6 months
- You are an immediate family member of a Zoho employee

---

## Responsible Research & Disclosure Rules

Participants must adhere to responsible disclosure practices:

- Avoid privacy violations, service disruption, data destruction, or degradation of user experience
- Do not perform DDoS testing or any activity that may cause outages or instability
- Use only accounts you own or have explicit permission to use
- Stop testing immediately if unauthorized or sensitive data is accessed and notify Zoho
- Do not exploit vulnerabilities beyond proof-of-concept testing
- Allow Zoho reasonable time to investigate and remediate issues before public disclosure

Failure to follow these rules may result in immediate disqualification.

---

## Submitting a Vulnerability

- Vulnerabilities must be submitted through Zoho’s official submission channel
- Reports should include:
  - A clear vulnerability description
  - Reproduction steps
  - Proof-of-concept (PoC)

Zoho reviews submissions within **3 business days**, prioritizes by severity, and notifies reporters once an issue is resolved. If multiple reports describe the same issue, only the **first valid submission** is eligible for a bounty.

---

## Bounty Rewards & Payments

- Bounties are awarded **at Zoho’s discretion**
- Reward amounts depend on severity, impact, and exploitability
- Payment methods:
  - INR wire transfer (India)
  - USD via PayPal (outside India)
  - USD Amazon gift cards
- Indian participants receive payments after 10% TDS deduction
- Bounties must be claimed within **3 months** of eligibility
- Participants are responsible for applicable taxes

---

## Ownership & Legal Terms

- Reporters grant Zoho a **non-exclusive, perpetual, royalty-free license** to use submissions for vulnerability analysis and remediation
- Zoho is **not liable** for any indirect, incidental, or consequential damages related to participation in the program

---

## Scope

### In Scope

- All Zoho-branded products and services (zoho.com)
- All ManageEngine products (manageengine.com)
- Site24x7
- Qntrl
- TrainerCentral
- Vani
- Arattai
- Ulaa Browser
- Zakya
- Zoho Corporation–owned assets

### Out of Scope / Exclusions

Examples of issues **not eligible** for bounty rewards include (but are not limited to):

- Missing best practices without exploitable impact
- Self-XSS, username/email enumeration
- Clickjacking on non-sensitive or unauthenticated pages
- Logout or unauthenticated CSRF
- Low-impact error messages or non-sensitive information disclosure
- Missing security headers without direct impact
- Automated scan results without validation
- Social engineering or phishing attacks
- Physical-access attacks
- Known vulnerable libraries without proven exploitability
- CSV injection, broken link hijacking
- Unicode/Punycode phishing risks
- Missing rate limits without security impact
- EXIF data in uploads
- Bypassing pricing or paid features
- Third-party 0-day vulnerabilities within 10 days of disclosure
- Issues not affecting latest versions of modern browsers or platforms
- Accepted risks or intended features, including:
  - Applications running as SYSTEM
  - Privileged query/script execution features
  - UDP-based unauthenticated protocols
  - Security issues limited to rooted or jailbroken devices

---

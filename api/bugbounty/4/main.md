# site.pro — Short Project & Bug Bounty Summary

Site.pro is a cloud-based website builder with a visual drag-and-drop editor and a set of templates that allows you to quickly create landing pages, corporate websites, and simple online stores. The platform offers features such as the ability to create an unlimited number of websites, connect your own domain, free SSL, email, and built-in tools for e-commerce and multilingualism. Recent releases emphasize AI-powered features to speed up design

## Program goal
Encourage responsible security research on the main site.pro domain and reward valid reports that meaningfully reduce user or service risk.

## Where to submit reports
- Registration in the bounty program is **required**.
- Submit the vulnerability by **creating a support/security ticket** and **choose any available category** when filing the report.
- Provide a **detailed, reproducible** report (one vulnerability per report unless chaining is required to show impact).

## Scope (in-scope)
- **Domain:** `site.pro` — **main domain only** (subdomains like `tw.site.pro` are out of scope).
- Vulnerabilities that materially impact security or user privacy, for example:
  - Remote Code Execution / unauthorized server access (RCE).
  - XSS with proven script execution on assets that have critical functionality.
  - Server-side vulnerabilities that disclose critical/confidential data (e.g., memory leaks, insecure direct object references).
  - Authentication bypass or privilege escalation.
  - Injection vulnerabilities (SQL, command, etc.).
  - Any other issue that can lead to loss of user privacy or serious service compromise.

## Out of scope
Typical low-impact or non-exploitable findings, including but not limited to:
- Disclosure of non-sensitive information (e.g., product version).
- Missing best-practice protections **without** demonstrated real impact (e.g., absent CSRF token, missing CSP directives) unless a clear exploit is shown.
- CSRF on unauthenticated or non-sensitive forms; CSRF on self-hosted instances (unless present on public servers).
- Self-XSS and trivial client-side issues (EXIF data, content/text injection without attack vector).
- Issues requiring MITM or physical access.
- Missing HTTP cookie flags, DNSSEC, or email records (SPF/DKIM/DMARC) alone.
- Missing rate-limiting **without** demonstrated impact.
- Weak password complexity policies (by themselves).
- Vulnerabilities in 3rd-party software unless they cause an in-scope impact.
- Stolen credentials, phishing/social engineering, duplicate reports, previously public or previously reported issues, and issues requiring unlikely victim interaction.

## Program rules & disclosure policy (high level)
- Provide clear, step-by-step reproduction and PoC; vague reports are ineligible.
- Submit one vulnerability per ticket (unless multiple are required to show impact).
- Only the **first** valid reporter of a duplicate issue is awarded.
- Multiple symptoms caused by one root cause → single bounty.
- Social engineering and attacks harming user data or service availability (DDoS, spamming, destructive tests) are prohibited.
- Give the vendor reasonable time to fix issues before public disclosure.
- Interact only with accounts you own or have explicit permission to test.

## Rewards (EUR) — by severity & example impact
- **Critical — 400–500 EUR**  
  Example: direct server or DB access, full admin takeover (remote root/RCE with persistent control).
- **High — 200–300 EUR**  
  Example: ability to modify other users’ data, serious privilege escalation.
- **Medium — 100–200 EUR**  
  Example: actions performed on behalf of other users without victim interaction; access to critical user data (payment details, contact info).
- **Low — 10–100 EUR**  
  Example: issues that are unlikely to harm users or have limited impact but still represent a flaw.

## Payment timing & requirements
- Payment is made **within 10 working days** after the reporter provides an **invoice**.
- The invoice must include required "Bill to" information (company billing details) to process payment.

---

**Notes / Tips for reporters:** include PoC steps, impact description, screenshots or logs where helpful, and avoid noisy or destructive scanning. Reports that cannot be reproduced will not be rewarded.

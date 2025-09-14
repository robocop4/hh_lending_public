# Tillitis Bug Bounty — Program Summary

**Summary**  
Tillitis follows Kerckhoffs’s principle: product design, tooling and security features are open. The Tillitis Bug Bounty Program invites responsible security researchers to report vulnerabilities that could materially affect the security or integrity of TKey devices and related apps. Reports should be sent to **security@tillitis.se** (use the PGP key if necessary). The Tillitis Team will investigate, remediate, and — when applicable — reward the first valid reporter.

---

## Eligibility
The program covers Tillitis hardware devices and device apps:

- **Covered hardware:** TKey, TKey Unlocked, TKey Programmer.  
- **Covered software:** All apps that can run on TKey (device apps and client apps listed on https://tillitis.se/download).  
- **Excluded:** Tillitis public websites (they are out of scope).  
- Vulnerability severity is assessed against Tillitis’ threat model.

---

## Devices Bug Bounty — Scope & Examples

**Primary focus:** flaws that could enable secret extraction (e.g., private keys, UDS).

**In-scope (Devices):**
- Hardware attacks on TKey, TKey Unlocked, TKey Programmer (e.g., cold/warm boot attacks).
- Software/firmware attacks on device firmware.
- Examples:
  - Warm-boot extraction of secrets from TKey hardware.
  - Bypass of Unique Secret Storage (USS).
  - Arbitrary code execution in firmware mode (with or without physical access).
  - Memory or information leakage that exposes secrets.

---

## App Bug Bounty — Scope & Examples

**Focus:** critical vulnerabilities in official apps provided for TKey.

**In-scope (Apps):**
- Software attacks on apps listed on the official downloads page.
- Examples:
  - Leakage of secrets (UDS, private keys).
  - Arbitrary code execution on the TKey in app mode (with or without physical access).

---

## Out-of-Scope
- Vulnerabilities in third-party device apps (still please report them to security@tillitis.se — Tillitis requests notification even if not eligible).  
- Issues in Tillitis websites (explicitly out of scope).  
- Reports violating the Responsible Disclosure rules below.

---

## Responsible Disclosure Policy (summary)
When you submit a report you agree to coordinated disclosure:

- Do not perform testing that causes unauthorized access, storage, sharing, or destruction of Tillitis or user data.
- Do not conduct social engineering, spam, or other actions that impact users or employees.
- Do not publicly disclose details of the vulnerability before Tillitis has had a chance to remediate (unless Tillitis provides prior written permission).
- All communications must go through **security@tillitis.se** (use PGP as needed). Do **not** contact Tillitis staff via personal emails or social media unless explicitly instructed.

The Tillitis Team aims to respond within **two working days**.

---

## Submission Process
Provide a clear, reproducible report including:

- A concise description of the issue.
- Step-by-step reproduction instructions or a working proof-of-concept.
- Any supporting logs, traces, or test artifacts.
- One report per distinct issue (do not submit duplicates).

Low-quality or incomplete reports may slow down triage and remediation.

---

## Remediation & Disclosure
- Tillitis will acknowledge reports and provide updates during triage and remediation.
- Tillitis follows a **90-day disclosure policy**: they aim to fix issues within 90 days of receipt. If fixed sooner and mutually agreed, disclosure may occur earlier.
- Prior to public disclosure, Tillitis will, where possible, share a draft description with the reporter. If disagreement arises, Tillitis will seek to resolve it (including mediation if necessary).

---

## Reward (Bounty) Information
- Eligibility for a reward requires:
  - Being the **first** reporter of the valid vulnerability.
  - The issue being confirmed as a valid security vulnerability.
  - Compliance with program rules and responsible disclosure requirements.
- Bounty amounts are discretionary and depend on severity, impacted data, exploitability, report quality, and user/brand risk.
- Typical bounty range: **€100 — €10,000**. Payments are made in EUR, USD, or SEK per researcher preference.
- Researchers are responsible for any applicable taxes.
- Ineligible: reports originating from or submitted from jurisdictions under Swedish export sanctions/trade restrictions, or where submission violates local laws.

---

## Hall of Fame
If you wish, Tillitis can list your real name or a pseudonym on their Hall of Fame in mutual agreement.

---

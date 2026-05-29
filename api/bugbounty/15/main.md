# About Company
Synology is a Taiwanese IT company founded in 2000 that specializes in network-attached storage (NAS), backup systems, and video surveillance solutions. The company’s best-known products are the DiskStation and RackStation lines, which are popular among both home users and small and medium-sized businesses.

# Synology Security Bug Bounty Program

Synology collaborates with security researchers to maintain and strengthen the safety of its products and services. The Security Bug Bounty Program rewards researchers who identify potential vulnerabilities and work with Synology to ensure customer security.  

---

## Scope

The program accepts reports only for Synology products and web services. Out-of-scope reports generally do not qualify for rewards, but critical vulnerabilities may be considered.  

**Components in Scope:**

| Category | Included Products / Services |
|----------|-----------------------------|
| Operating Systems | Synology DiskStation Manager (DSM), Synology Router Manager (SRM) |
| Software & C2 Cloud Services | Synology-developed software packages, related mobile apps, and Synology C2 cloud services |
| Web Services | All major Synology web services |

---

## How to Submit a Report

1. Contact Synology using the Bounty Program contact form.  
2. Encrypt your report using Synology’s PGP key.  
3. Include a detailed proof of concept (PoC) and ensure the vulnerability can be reproduced.  
4. Keep descriptions concise—a short PoC link is preferred over long videos.  

**Reward eligibility requires:**

- First valid report of a previously unknown vulnerability  
- Vulnerability is verifiable, replicable, and a valid security issue  
- Compliance with the program’s terms and regulations  

---

## Reward Table

| Severity | Vulnerability Type | Operating Systems | Software & C2 Cloud Services | Web Services |
|----------|------------------|-----------------|-----------------------------|--------------|
| **Critical** | Zero-click pre-auth RCE | $30,000 | $10,000 | $5,000 |
| | Zero-click pre-auth arbitrary file read/write | $9,000 | $4,600 | $2,400 |
| **Important** | 1-click pre-auth RCE | $8,000 | $4,000 | $2,000 |
| | Zero-click normal-user-auth RCE | $7,500 | $3,900 | $1,900 |
| | Zero-click normal-user-auth arbitrary file r/w | $6,500 | $3,400 | $1,700 |
| | Zero-click pre-auth RCE (AC:H) | $6,500 | $3,400 | $1,700 |
| | 1-click pre-auth RCE (AC:H) | $5,000 | $2,500 | $1,325 |
| | Pre-auth SQL injection | $3,800 | $1,950 | $1,025 |
| | 1-click normal-user-auth RCE (AC:H) | $2,600 | $1,350 | $725 |
| | Pre-auth stored XSS | $2,600 | $1,350 | $725 |
| **Moderate** | Normal-user-auth stored XSS | $1,350 | $733 | $417 |
| | Normal-user-auth SQL injection | $1,200 | $607 | $353 |
| | Admin-auth vulnerabilities | $100 | $100 | $100 |

*Notes: Rewards are maximum potential amounts. Each report is evaluated individually. Low-severity issues or suggestions may receive only acknowledgment.*

---

## Acknowledgment

Synology values contributions from security researchers and aims to reward significant findings fairly. All reports are treated with careful evaluation and discretion.

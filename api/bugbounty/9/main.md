## Jenkins Bug Bounty Summary

**Product Overview:**  
Jenkins is an open-source automation server widely used for building, testing, and deploying software. The Jenkins Security Team manages vulnerability reports and coordinates responsible disclosure to maintain platform security.

---

### 🔒 Scope of the Bug Bounty Program

**In Scope:**
- **Jenkins Core** (including official installers and Docker images)
- **Jenkins Plugins** published by the Jenkins project  
  (those listed on [plugins.jenkins.io](https://plugins.jenkins.io) or hosted under the `jenkinsci` GitHub organization)
- **Official Jenkins Components** (e.g. Docker images for Jenkins agents)
- **Jenkins Infrastructure Projects**  
  (repositories under the `jenkins-infra` GitHub organization, such as jenkins.io)

**Out of Scope:**
- CloudBees Jenkins products (report directly to CloudBees)
- Jenkins X (report to the Jenkins X team)
- Non-security issues or expected behaviors in Jenkins or its infrastructure  
  Examples include:
  - Vulnerabilities requiring *Overall/Administer* permissions  
  - Non-sensitive cookies missing `Secure` or `HttpOnly` flags  
  - Harmless network requests without attacker control  
  - Vulnerabilities in dependencies without working exploits  
  - Log entries with secrets only at debug levels  
  - Public file listings or configurations on Jenkins mirrors and infrastructure sites  

---

### 🚫 Non-Issues (Common False Reports)
The following **do not count as vulnerabilities**:
- Arbitrary code execution by admins (expected behavior)
- Outdated PoCs for already-fixed plugin issues (over 13 months old)
- False positives in antivirus detections for certain Jenkins libraries
- Exposure of non-sensitive information on public Jenkins sites
- Public access to Jenkins infrastructure repos and file listings (intentional)

---

### 🧩 Plugin Security
- The Jenkins Security Team acts as an intermediary between reporters and plugin maintainers.
- Maintainers are responsible for fixes, with Jenkins Security assisting in review and coordination.
- High-impact plugins coordinate releases with Jenkins Security to ensure prompt disclosure.

---

### ⚙️ Issue Handling Process
- Reports are submitted via the **Jenkins SECURITY project** in the issue tracker, visible only to the reporter and security team.
- Alternative: send details via email to `jenkinsci-cert@googlegroups.com`.
- The team usually responds **within 1 working day**, and always within **3 working days**.
- Valid issues receive **CVE identifiers** once fixes are ready or disclosure deadlines approach.
- Reporters are credited in official advisories.

---

### 🤝 Coordinated Disclosure
- Jenkins follows **responsible disclosure** practices.  
- If your report has a public deadline, inform the team early to align with Jenkins’ monthly release cycle.

---

### 🧾 Attribution Policy
- Reporters are publicly credited in Jenkins security advisories (unless they prefer anonymity).

---

### 💰 Bug Bounty / Rewards
- **Currently, Jenkins does not offer any monetary rewards or gifts** for vulnerability reports.  
- The program operates as a **responsible disclosure initiative**, not a paid bounty.

---

### 📢 Security Advisories
- Official advisories for Jenkins core and plugins are published on the Jenkins website and distributed via mailing lists and in-app notifications.

---

**Summary:**  
The Jenkins security reporting program emphasizes **responsible disclosure**, **private reporting**, and **transparent advisories**, but **does not provide financial rewards**. Reports should focus on actual vulnerabilities in Jenkins core, official plugins, or infrastructure — excluding expected administrative behavior or benign configuration issues.

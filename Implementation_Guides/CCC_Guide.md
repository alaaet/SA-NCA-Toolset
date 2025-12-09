# ☁️ The "No-Boring-Stuff" Guide to NCA CCC (Cloud Cybersecurity Controls)

> **"There is no cloud, it's just someone else's computer."**  
> — *Ancient Sysadmin Proverb*

Welcome, brave Compliance Officer. You are here because you want to use the Cloud in Saudi Arabia without the NCA turning your traffic lights red. Let's get you compliant.

---

## 🎭 Who Are You? (Identity Check)
First, let's figure out which side of the table you sit on. The NCA CCC applies to two types of people:

1.  **CSP (Cloud Service Provider)**: You *own* the servers. You sell the cloud. (e.g., SITE, STC Cloud, Google Cloud KSA).
2.  **CST (Cloud Service Tenant)**: You *rent* the servers. You use the cloud. (e.g., A government ministry, a hospital, a bank).

🛑 **This guide is primarily for the TENANTS (CSTs).**  
*If you are a Provider, most of this still applies, but you have about 3x more work to do. Good luck.*

---

## 🏛️ The 4 Pillars of CCC
The NCA didn't just throw controls at a wall. They built a temple. Here are the four pillars holding up your cloud security:

### 1. Governance (The "Boss" Stuff)
*   **Roles (1-1)**: You need a "Cloud Czar". Someone must be responsible. If everyone is responsible, no one is.
    *   *Action*: Update your RACI chart. Add "Cloud Security Manager".
*   **Compliance (1-3)**: You must follow the law.
    *   *Action*: Check your contracts. If your provider breaks the law, you go down with them.
*   **HR (1-4)**: Hire good people. Screen them.
    *   *Action*: Background checks for anyone with `sudo` access.

### 2. Defense (The "Shields Up" Stuff)
*   **Asset Management (2-1)**: You can't protect what you don't know you have.
    *   *Action*: Run a discovery scan. Find that rogue AWS bucket from 2019.
*   **Identity (2-2)**: Passwords are dead. Long live MFA.
    *   *Action*: Enforce MFA everywhere. No exceptions for the CEO.
*   **Cryptography (2-5)**: Encrypt it like you're hiding it from your in-laws.
    *   *Action*: Encrypt data at rest (on disk) and in transit (HTTPS/TLS). maintain your own keys if you're paranoid (and you should be).

### 3. Resilience (The "Plan B" Stuff)
*   **Backups (3-1)**: Clouds evaporate. Data shouldn't.
    *   *Action*: Test your restores. A backup you haven't restored is just a rumor.
*   **Business Continuity**: When the internet breaks, do you still have a business?

### 4. Third-Party (The "Vendor" Stuff)
*   **Supply Chain (4-1)**: Your cloud provider has vendors too.
    *   *Action*: Ask for their certifications (ISO 27001, CSA STAR, NCA certification). Trust, but verify.

---

## 📜 The Golden Rules of KSA Cloud
If you remember nothing else, remember these three rules:

1.  **Data Sovereignty is King**: 🇸🇦 Government data stays in the Kingdom.
    *   *Rule*: Do not host "Secret" or "Top Secret" data on a public cloud. PERIOD.
    *   *Rule*: For "Restricted" data, use NCA-authorized CSPs only.

2.  **Shared Responsibility is a Trap**:
    *   The Provider secures the **Cloud** (infrastructure).
    *   YOU secure **what's IN the Cloud** (data, apps, users).
    *   *Don't assume they are backing up your database.*

3.  **Log Everything**:
    *   If a hack happens and you have no logs, did it strictly speaking happen? Yes, and you are in trouble.
    *   *Action*: Stream your cloud logs to your local SIEM.

---

## ✅ The "Get Me Compliant" Checklist
- [ ] **Classify your Data**: Know what you are moving (Public, Restricted, Secret).
- [ ] **Choose the Right Class**:
    *   Class C (Public Data) -> Global Clouds ok.
    *   Class B (Restricted) -> Local KSA Clouds only.
    *   Class A (Secret) -> Private Government Clouds involved.
- [ ] **Update Contracts**: Ensure your SLA guarantees uptime and data ownership.
- [ ] **Turn on MFA**: Seriously, do it now.
- [ ] **Encrypt Data**: Click the checkbox. It's usually free.
- [ ] **Audit**: Run a vulnerability scan against your cloud instance.

---
*Disclaimer: This is a high-level creative guide. For the exact legal text, please refer to the 76-page PDF that you are trying to avoid reading.*

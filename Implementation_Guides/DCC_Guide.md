# 💾 DCC (Data Cybersecurity Controls) - The "Data is Oil" Guide

> **"Data is like garbage. You’d better know what you are going to do with it before you collect it."**  
> — *Mark Twain (probably)*

Welcome to the **DCC**. While ECC protects the *systems* and CCC protects the *cloud*, DCC protects the *gold* inside them: **Your Data**.

---

## 🔄 The Data Lifecycle (The Circle of Life)
The NCA wants you to protect data at every stage of its life. You can't just encrypt it once and forget it.

1.  **Creation/Generation**: When you create a file, you must classify it immediately. (Public, Restricted, Secret, Top Secret).
2.  **Processing/Use**: Who is looking at it? Are they authorized? (DLP agents are watching).
3.  **Storage**: Where does it live? Is the hard drive encrypted? Is the database secure?
4.  **Transmission/Sharing**: Emailing a spreadsheet? **STOP**. Encrypt it first. Use secure channels.
5.  **Archiving**: Old data needs love too. Secure your backups.
6.  **Destruction**: When you delete a file, is it *really* gone? (Hint: "Delete" key = No. "Wiping/Degaussing" = Yes).

---

## 🚫 Data Classification (The Sorting Hat)
You **MUST** have a data classification policy.
*   **Top Secret (Red)**: Damage strictly to national security.
*   **Secret (Amber)**: Heavy damage to the entity or nation.
*   **Restricted (Green)**: Internal use only.
*   **Public (White)**: Post it on Twitter if you want.

*If everything is "Confidential", then nothing is.*

---

## 🛠️ Key Controls (How to survive)
### 1. DLP (Data Loss Prevention)
*   Install DLP sensors on emails and endpoints.
*   Stop people from uploading "Client_Database_v2.xlsx" to their personal Google Drive.

### 2. Encryption
*   **At Rest**: BitLocker, TDE (Transparent Data Encryption).
*   **In Transit**: TLS 1.2 or 1.3 only. SSL is dead.

### 3. Masking & Anonymization
*   Developers do not need real customer credit card numbers to test their code. Use dummy data. Mask the sensitive fields.

---

## 📋 The "Data Defender" Checklist
- [ ] **Classify**: Tag every document. Yes, even the lunch menu (Public).
- [ ] **Clean House**: Delete data you don't need. Hoarding data is a security risk.
- [ ] **Encrypt USBs**: Force encryption on all removable media.
- [ ] **Audit Access**: Who accessed the CEO's payroll file? You should know.

---
*Disclaimer: Data leakage is the fastest way to make headlines. Don't be a headline.*

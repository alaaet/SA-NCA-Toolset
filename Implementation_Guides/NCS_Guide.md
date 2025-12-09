# 🔐 NCS (National Cryptographic Standards) - The "Math Class" Guide

> **"Mathematics is the queen of science, and encryption is the queen of keeping secrets."**

Welcome to the **NCS** (National Cryptographic Standards). This isn't a strategy document; it's a technical manual on how to lock your data so tightly that even a supercomputer gets a headache.

---

## 📅 The Levels (Choose Your Difficulty)
The NCS defines two levels of strength. You must pick one based on your data classification.
1.  **MODERATE**: Good for most commercial/civilian needs. (128-bit security).
2.  **ADVANCED**: For highly sensitive/Top Secret data. (256-bit security).

---

## 🚫 The "Deprecation" Graveyard
Stop using these. Immediately.
*   **MD5**: Broken. Dead. Buried.
*   **SHA-1**: Collision attacks exist. Do not use.
*   **DES / 3DES**: Too slow, too weak.
*   **SSL v3 / TLS 1.0 / TLS 1.1**: Vulnerable to Poodle, Beast, etc.
*   **RSA 1024**: Too easy to factor.

---

## ✅ The Approved List (Use These)

### 1. Symmetric Encryption (The Fast Stuff)
*   **AES (Advanced Encryption Standard)**:
    *   **Moderate**: AES-128.
    *   **Advanced**: AES-256.
*   **Modes**: GCM (Galois/Counter Mode) is preferred because it gives you Authenticated Encryption (confidentiality + integrity). Avoid ECB mode (it shows patterns).

### 2. Asymmetric Encryption (Keys and Certs)
*   **RSA**:
    *   **Moderate**: Minimum 3072-bit keys. (2048 is becoming risky).
    *   **Advanced**: Don't use RSA. Use ECC.
*   **ECC (Elliptic Curve)**:
    *   **Moderate**: NIST P-256.
    *   **Advanced**: NIST P-384 or P-521.

### 3. Hashing (Fingerprints)
*   **SHA-2**: SHA-256 or SHA-512.
*   **SHA-3**: The new cool kid. SHAKE128/256.

### 4. Protocols (Data in Transit)
*   **TLS**: Version 1.2 is the *minimum*. Version 1.3 is preferred.
*   **SSH**: Version 2 only.
*   **VPN**: IPsec with AES-GCM.

---

## 📋 The "Crypto" Checklist
- [ ] **Scan**: Run a scan (like SSL Labs or Nmap) on your public IPs. Are you supporting TLS 1.0? Turn it off.
- [ ] **Check Certs**: Are your internal certificates using RSA-2048? Plan to migrate to 3072 or ECC.
- [ ] **Developers**: Check your code. Are you using `MessageDigest.getInstance("MD5")`? Fix it.
- [ ] **Databases**: Enable TDE (Transparant Data Encryption) with AES-256.

---
*Disclaimer: Rolling your own crypto is a recipe for disaster. Use standard libraries. Do not invent "MySuperCipher".*

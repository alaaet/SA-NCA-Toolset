# 🏡 TCC (Telework Cybersecurity Controls) - The "Work From Home" Guide

> **"There is no place like home (access)."**

Welcome to the **TCC**. This is the guide for when your office is your living room, and your biggest threat actor is your cat walking on the keyboard.

---

## 🌎 The Scope
TCC applies to:
*   **Remote Access**: VPNs, RDP, VDI.
*   **BYOD (Bring Your Own Device)**: Using your personal iPad for work.
*   **Mobile Devices**: Company phones.
*   **Cloud Collaboration**: Teams, Zoom, Slack (if used for official work).

---

## 🛡️ The "Pajama Defense" Strategy

### 1. Identity is the New Perimeter
*   **MFA (Multi-Factor Authentication)**: If you implement NOTHING else, implement this. Remote access without MFA is basically an open door.
*   **Concurrent Logins**: Prevent the same user from logging in from 5 different countries at once.

### 2. The Device (Your Weapon)
*   **MDM (Mobile Device Management)**: If you give an employee a phone, you must be able to wipe it remotely if they lose it at a coffee shop.
*   **BYOD**: If you allow personal devices, you must have a containerized app (sandboxed) for work data. Do not let work data mix with personal photos.
*   **Encryption**: Full Disk Encryption (BitLocker/FileVault) is mandatory for laptops.

### 3. The Network (The Tube)
*   **VPN**: Use it. Split-tunneling is risky; full-tunneling is safer but slower. Choose wisely based on risk.
*   **Public Wi-Fi**: "Free Airport Wi-Fi" is a trap. Ban it or mandate VPN use.

---

## 🚫 The "Don't Do It" List
1.  **Shared Accounts**: "Admin / Password123" shared by 10 remote admins. No.
2.  **Split Tunneling for Sensitive Data**: Don't let them access "Secret" data while simultaneously torrenting movies on the same connection.
3.  **Local Admin**: Don't give remote users local admin rights. They will install malware.

---

## 📋 The "Remote Ready" Checklist
- [ ] **Policy**: Write a Telework Policy. HR needs to sign off.
- [ ] **VPN**: Ensure it's patched. VPN concentrators are high-value targets.
- [ ] **Endpoint Protection**: Your corporate Antivirus/EDR must work even when the user is offline or off-VPN.
- [ ] **Awareness**: Train users: "If the CEO emails you asking for gift cards, it's a scam."

---
*Disclaimer: Working from home is comfortable. Getting breached from home is uncomfortable.*

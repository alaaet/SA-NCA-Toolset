# 🤖 CGIoT (Cybersecurity Guidelines for Internet of Things) - The "Smart Toaster" Guide

> **"The 'S' in IoT stands for Security."**  
> — *An Internet joke that is painfully true*

Welcome to the **CGIoT**. This is for anyone who thinks it's a good idea to connect a refrigerator to the internet. If it computes and connects, but isn't a server or a laptop, it's likely IoT.

---

## ❓ What is in Scope?
*   **Smart Cameras**: (Please change the default password).
*   **Sensors**: Temperature, humidity, motion.
*   **Smart Building/City Tech**: Lighting, parking sensors.
*   **Wearables**: Smartwatches, badges.
*   **Medical Devices**: Pacemakers (Yes, really).

---

## 🛑 The "Please Don't Do This" List
1.  **Default Passwords**: If your camera password is `admin/admin`, you are the problem.
2.  **Public Exposure**: Why is your printer accessible from the entire internet? Stop that.
3.  **No Updates**: A device that cannot be patched is a time bomb.

---

## 🛡️ Key Guidelines (How to not build a Botnet)
### 1. Identify & Inventory
*   You probably have 500 more IoT devices than you think. Scan your network.
*   Is that a Raspberry Pi under the desk? Unplug it.

### 2. Network Segmentation (The "Petting Zoo" Approach)
*   **Rule**: IoT devices are untrusted.
*   **Action**: Put them in their own VLAN. A specific "IoT Zoo" where they can talk to the internet (if needed) but **NOT** to your internal HR server or Financial Database.
*   *If the coffee machine gets hacked, it shouldn't be able to read the CEO's email.*

### 3. Manufacturer Principles (For the Builders)
*   If you *build* IoT:
    *   No hardcoded credentials.
    *   Secure boot (verify the firmware).
    *   Encrypt data.

---

## 📋 The "Smart" Checklist
- [ ] **Change Defaults**: `123456` is not a password.
- [ ] **Isolate**: Create a Guest/IoT Wi-Fi network.
- [ ] **Disable UPnP**: Your router doesn't need to auto-open ports for your lightbulbs.
- [ ] **Physical Security**: Can someone walk up and plug a USB into your smart kiosk? Tape it shut.

---
*Disclaimer: Remember, the botnet doesn't care if it's a supercomputer or a toothbrush. A CPU is a CPU. Secure them all.*

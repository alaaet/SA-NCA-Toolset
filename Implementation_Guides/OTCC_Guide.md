# 🏭 OTCC (Operational Technology Cybersecurity Controls) - The "Don't Blow Up The Plant" Guide

> **"IT Security prevents data loss. OT Security prevents physics from happening to you."**

Welcome to the **OTCC**. This is for the folks wearing hard hats, dealing with PLCs, SCADA, and systems that can actually explode.

---

## 🏗️ IT vs. OT (Know the Difference)
*   **IT (Information Technology)**: Priorities = Confidentiality, Integrity, Availability (CIA).
*   **OT (Operational Technology)**: Priorities = **Safety**, **Availability**, Integrity, Confidentiality.
    *   *If an IT server crashes, you lose email. If an OT server crashes, you might lose a refinery.*

---

## 📊 The Levels (How scared should you be?)
The OTCC divides facilities into 3 levels based on impact:
*   **Level 1 (High)**: Catastrophic. Loss of life. National security impact. (e.g., Nuclear plant, National Grid).
*   **Level 2 (Medium)**: Significant impact. Hard to fix.
*   **Level 3 (Low)**: Bad, but manageable.

*You need a "Facility Level Identification Tool" to figure this out. Good luck.*

---

## 🛑 Key Controls (Safety First)
### 1. Risk Management (The "What If" Game)
*   Integrate Cyber Risk with **Process Hazard Analysis (PHA)**.
*   Ask: "If a hacker flips this bit, does the tank overflow?"

### 2. The "Air Gap" (Network Segmentation)
*   **Purdue Model**: Learn it. Love it.
*   **Level 3.5 (DMZ)**: Nothing talks from the Internet (Level 5) to the Plant Floor (Level 1) without passing through a DMZ.
*   **One-Way Diodes**: For high criticality, data flows OUT, nothing flows IN.

### 3. Testing (FAT/SAT)
*   **Factory Acceptance Testing (FAT)**: Hack it before it leaves the factory.
*   **Site Acceptance Testing (SAT)**: Hack it when it arrives.
*   **Change Management**: Never patch a live PLC without testing. Verify in a lab first.

### 4. Incident Response
*   Your playbook is different. "Rebooting" a blast furnace is not a valid containment strategy.

---

## 📋 The "Hard Hat" Checklist
- [ ] **Inventory**: Map every PLC, HMI, and Sensor.
- [ ] **Segregate**: Unplug the control network from the office network. Seriously.
- [ ] **Disable USBs**: Glue the ports shut if you have to. Stuxnet taught us this lesson.
- [ ] **Backup**: Have offline backups of your logic and setpoints.
- [ ] **Vendor Access**: Watch your vendors. They are your biggest risk vector.

---
*Disclaimer: In OT, safety is paramount. Do not implement security controls that prevent the emergency stop button from working.*

# Establishing a System Baseline (Security+ Practice Lab)

This project documents my hands-on experience completing the **"Establishing a Baseline"** lab scenario as part of a Security+ certification course via Practice-Labs.

## Objective

The goal of this lab was to implement and analyze system baselines as a foundational component of security hardening and change detection.

## Key Tasks

- Identified critical system files and services to monitor
- Captured a baseline using built-in Windows tools (e.g., `Systeminfo`, `WMIC`, or `Get-EventLog`)
- Configured auditing or hashing tools to detect file and registry changes
- Validated baseline integrity post-reboot and simulated minor changes to test detection

## Tools & Commands Used

- `Systeminfo`, `Tasklist`, `WMIC`, `Get-FileHash`, `Auditpol`
- Windows Event Viewer
- Baseline comparison tools

## Skills Demonstrated

- Understanding of baseline importance in security monitoring
- Familiarity with Windows system auditing tools
- Ability to document and verify a known-good system state
- Change detection and anomaly identification

## Screenshots

Key points of the lab have been documented and can be found in the `/screenshots` directory.

---

## 🧠 What I Learned

As someone growing into cybersecurity and IT, this lab helped me understand more than just tools — it taught me how important preparation and consistency are. Establishing a system baseline isn’t just a checkbox task — it’s how organizations create trust in their infrastructure.

I learned:
- How to think like a defender by identifying “known good” system states
- The real-world value of documenting everything — especially in incident response
- How simple changes (like a new service or file hash) can signal compromise
- That attention to detail is a critical IT skill, and good habits now = fewer disasters later

Completing this lab reinforced why baseline integrity matters, and gave me confidence that I could contribute to a real-world SOC or blue team environment.



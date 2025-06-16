# plc-chemical-process-project
PLC Ladder Logic for a chemical process using Siemens TIA Portal
# PLC Ladder Logic – Chemical Process Automation

This project demonstrates a PLC-based control system for a chemical process, implemented using Siemens TIA Portal.

---

## 🧠 Project Overview

- **Platform**: Siemens TIA Portal
- **CPU Used**: Siemens S7-313C-2 DP
- **Language**: LAD (Ladder Logic)
- **Blocks Used**: OB1 (Main), with multiple networks
- **Functions**:
  - Manual/Auto mode switching
  - State machine logic using memory words (`%MW0`, `%MW2`, `%MW4`)
  - Level sensor input logic (`%I125.x`)
  - Pump and solenoid output control (`%Q124.x`)
  - Timer-based maintenance logic using `TON`

---

## 📄 Files

- `PROJECT.pdf` – Contains the full ladder logic from the OB1 block, with comments and memory mapping

---

## ⚙️ Features Implemented

- Logic for three states per process line
- Input logic using level sensors and switches
- Output logic controlling pumps and solenoids
- Timer block for delayed operation
- Maintenance override switch

---

## 📌 Notes

This project was developed for educational and training purposes using Siemens TIA Portal. If you'd like to contribute improvements or adaptations for different PLC hardware, feel free to fork the repo.

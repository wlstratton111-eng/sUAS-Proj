# 🛸 Custom FPV Quadcopter Build — 6S 5" Freestyle Drone

This repository documents the end-to-end design, build, and test of a custom 5" FPV quadcopter. Built for performance and tuning experience, the project uses a 6S powertrain, high-thrust motors, and wireless configuration via the SpeedyBee stack. The goal was to develop hands-on root-cause analysis skills and deeper familiarity with modern flight control systems.

---

## 📌 Project Goals

- Design and assemble a 5" 6S quadcopter for FPV freestyle/racing
- Learn PID tuning and flight log analysis using Betaflight
- Apply real-world systems engineering to a personal aerospace project
- Improve hands-on experience with EMI mitigation, signal wiring, and firmware setup

---

## 📦 Components & Bill of Materials

| Subsystem       | Component                                                                                                       | Notes                                                                                     |
|-----------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| **Flight Stack** | **SpeedyBee F405 V4 Stack**<br>30x30 FC + 4-in-1 55A ESC + Bluetooth | Wireless Betaflight config, blackbox + barometer, perfect for DJI/analog, 6S capable |
| **Motors**       | **Axisflying AE2207 V2 1860KV (x4)**                                                                             | 2207 stator for 5" props, 6S rated, strong torque curve, 5mm shaft                        |
| **Battery**      | **TATTU R-Line V4.0 6S 1050mAh 130C LiPo**                                                                      | High-discharge, race-grade pack with XT60 connector                                      |
| **Propellers**   | **Gemfan Hurricane 51477 (5.1", 3-blade)**                                                                      | Popular 5" prop for 2207 motors, good balance of thrust and efficiency                   |
| **Frame**        | **ImpulseRC ApexDC EVO 5" Frame Kit**                                                                           | Durable carbon fiber frame with excellent stack protection and smooth flight feel        |

---

## 🧱 System Overview

- **Voltage**: 6S (22.2V)
- **Motors**: 1860KV, 2207-class
- **ESC**: 4-in-1 55A DShot
- **FC**: F405 MCU, Barometer, Blackbox
- **Weight**: ~[Insert AUW]g (with battery)
- **Firmware**: Betaflight (wirelessly configured via SpeedyBee)
- **Flight Style**: Freestyle / Acro / Manual FPV

---

## 🛠️ Build Process

### 1) Frame Construction
- ![Link to Frame](../docs/01_frame_assembly.md)

---

## 💻 Software & Configuration

- **Configurator**: Betaflight 4.4+
- **Firmware Target**: `SpeedyBeeF405`
- **Wireless Setup**: All configuration done via SpeedyBee mobile app
- **Modes Configured**: Acro, Horizon, Beeper, Turtle Mode

---

## 📊 Tuning & Testing

| Test | Purpose | Results |
|------|---------|---------|
| N/A | N/A | N/A |

---

## 🔍 Debugging & Root-Cause Analysis

| Issue | Diagnosis | Fix |
|-------|-----------|-----|
| N/A | N/A | N/A |

---

## 📸 Media

- 📷 Build photos in `images/`
- 📹 FPV flight footage [YouTube link here]
- 📁 Blackbox logs in `logs/`
- 🖼️ Wiring diagrams and block diagrams in `diagrams/`

---

## 🧠 Lessons Learned

- How to tune PID loops and filters for flight stability
- Debugging electrical noise and power issues
- Importance of clean wiring and good documentation
- How to use Betaflight CLI and blackbox logs for iteration

---

## 📇 About Me

**Will Stratton**  
- Aerospace Engineer (Auburn University) | Minor in Computer Science  
- FAA Part 107 Certified Remote Pilot  
- Passionate about systems engineering, flight testing, and autonomy  
- [LinkedIn](https://www.linkedin.com/in/william-stratton-wlstratton) | [Email](mailto:wlstratton111@gmail.com)

---

## 🏷️ Tags

`#FPV` `#Quadcopter` `#Betaflight` `#DIYDrone` `#AerospaceEngineering` `#RootCauseAnalysis` `#sUAS`

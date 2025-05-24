# PROJECT: ModuMic
Modular Mic is a customizable, swappable-head microphone system with USB-C, Bluetooth, and AUX support. Designed with an intuitive dual-mode UI (Beginner/Advanced) for recording, playback, and sound visualization. Built from scratch for versatility and great audio performance.
## Project Concept
Modular Mic is a **swappable microphone system** designed with recording versatility, mechanical ingenuity, and wireless adaptability in mind.

Mic heads screw on via camera-lens-like threading (left-hand/right-hand threads) for distinct profiles such as **cardioid** and **omnidirectional**. A built-in UI supports waveform display, audio recording/playback, and mixing, with **Beginner** and **Advanced** modes.

## Features
-  Modular mic heads via left/right-hand threaded connectors
-  Analog + digital signal path with optional EQ or gain stages per head
-  Dual-mode UI (Beginner and Advanced)
-  USB-C, Bluetooth, and AUX support
-  Optional sound-dampening foam layers (inspired by Rode PodMic)

## Inspiration
A mix of the **Rode PodMic** aesthetic, modular camera gear, and modern Bluetooth + USB audio interfaces.

## Technical Stack
- **ESP32-S3** for BLE + USB + embedded control
- **Codec IC (e.g., ES8388)** for high-quality audio
- Rust / C++ firmware (depending on BLE stack stability)
- Custom SolidWorks-designed housing
- KiCad-based custom mixed-signal PCB

## Estimated BOM
| Component                     | Cost       |
|------------------------------|------------|
| ESP32-S3 module              | $6–$8      |
| Mic capsules (Omni + Cardioid) | $10–$20  |
| Custom threaded connector    | $10        |
| Display + UI buttons/knob    | $10–$15    |
| Codec IC (e.g., ES8388)      | $10–$15    |
| Battery + PMIC               | $10–$20    |
| PCB (4-layer)                | $70        |
| Misc components + passives   | $15–$20    |
| **Total**                    | **$140–300** depending on funding

## Milestones
### 05/24 - Part Concept Began & Timeline for Project is being fleshed out (tasklist for more defined goals)

---

## Goals
- [ ] Design 2 modular mic profiles
- [ ] Complete schematic in KiCad
- [ ] Layout and order PCB
- [ ] Prototype modular threading system
- [ ] Develop dual-mode UI
- [ ] Final firmware for recording + streaming

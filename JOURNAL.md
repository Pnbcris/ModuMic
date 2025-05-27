---
title: "ModuMic"
author: "Cristian Hernandez"
description: "ModuMic is a customizable microphone with swappable heads and multiple connectivity options, designed for flexible recording and user-friendly control."
created_at: "2025-05-24"
---

# May 24th: Creating Task List | Starting Design
![image](https://github.com/user-attachments/assets/18aac9da-086e-479d-a8ae-b2eef6873391)

organize my thoughs & provide reasoning for project decisions to effectively use my time and minimize drastic changes (2 hours)
-
## Questions + Reasoning
### Q: **Why attempt to make a microphone to have the ability to record with multiple sound patterns?**

A: To give users flexible control over audio capture; from isolating vocals and minimizing background noise with a cardioid pattern, to capturing immersive, full-room sound with omnidirectional mode. This versatility enables everything from solo recordings to group sessions, even allowing 8D audio effects when played through multiple speakers. 

### Q: **Why make the microphone have so many connectivity options? Wouldn't one or two satisfy?**

A: Because no single connection will fit every use case. Multiple options ensure the mic works seamlessly across different setups - wireless for convenience, AUX for real-time use, and USB-C for high-quality digital audio and power. By maximizing compatibility, flexibility, and user freedom.

----------------------------------------------------------------------------------------------------------------------

# May 25th: Simplifying + Refining Design Intent; Begin Hardware 

narrowing down the desired features to include as part of the microphone has been difficult, and recieving opinions from other HackClubbers helps a lot with thinking the possible designs. Doing a bit more research on PCB design methods, using 2 PCB's as opposed to just one simplifies switching profiles, allowing for switching between Cardioid & Omnidirectional function desirably. Additionally, by discarding wifi cabailities steming from the microphone itself allows for less battery draw and simplify the pcb design.

Adding a companion deck, similar to those used with audio mixers, could enable a lighter mic design and add features for connected devices. It would handle sound control, making it easier to switch audio profiles and mic patterns. Also, the initial concept of adding swappable capsule/heads via thread + magnetic pin detection may overcomplicate my end goal. If I can make it all into one custom build, it'll lower costs and save time on manufacturing the parts, giving me more time to focus on the software and tuning the profiles.

## Sourcing Material/Hardware to test prototype

I plan on utilizing my Rasberry Pi 4B from a previous project to serve as a prototype companion deck and test compatibility to the ESP32, which will be the microphones processor & since I also had it from a previous project, I may as well reuse & do connectivity tests.

Update: I went to MicroCenter to purchase a few missing components to get the microcontroller to function independently (below are the products purchased)

| Product                         | Description                                                                 | Cost   |
|---------------------------------|-----------------------------------------------------------------------------|--------|
| IPSG DC-DC STEP DOWN MODULE     | Used to step down voltage from a 9V battery to output only 3.7V (indicated operating voltage for the ESP32) | $5.99  |
| LKG INDUS T SHAPE 9V BATTERY SNAP     | 9V battery snap connector designed for securely attaching wires to a step-down voltage converter | $1.49  |
| IPSG INLAND JPR WIRE 20CM 3PK     | Extra M-M, F-M and F-F jumper wires to connect components to Mic prototype | $4.99  |
| IPSG USB A TO MICRO-B CABLE     | USB A ->  Micro-B used to upload code + program ESP32 Directly from laptop  | $2.99  |

Sales TOTAL : $16.89 (after tax)
Images: 

| ITEM 1                     | ITEM 2                     | ITEM 3                     | ITEM 4                     |
|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
| ![image](https://github.com/user-attachments/assets/e652e9e8-0241-48ac-ba16-a4880b6d8c35) | ![image](https://github.com/user-attachments/assets/40fabd25-4d0f-4eca-82b6-cdd3e9affaf4)   |  ![image](https://github.com/user-attachments/assets/da1e2e3d-228c-46c1-9a67-c5a01e2a43ba)  | ![image](https://github.com/user-attachments/assets/00e5409e-9382-4e99-8f34-321ebeecf7a1)  |




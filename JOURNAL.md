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

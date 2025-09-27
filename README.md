# Green Lantern Battery 🔋💡

## 📖 Project Description

The **Green Lantern Battery Project** is a custom electronics build that brings the Green Lantern’s iconic power source to life.  
The system uses microcontroller-based control (Arduino Nano), RFID tag detection, glowing LED effects, and synchronized audio playback.

When a Green Lantern ring with an RFID tag is brought near the lantern, the system powers up:

- LEDs fade in with a breathing glow effect to simulate charging energy.
- The DFPlayer Mini module triggers a sound effect stored on a microSD card.
- The light and sound stay active as long as the ring remains nearby.
- Removing the ring instantly fades out the glow and stops playback.

The project emphasizes **interactivity** (tag presence detection). It serves as both a prop replica and a hands-on learning project for combining **electronics, firmware, and design engineering**.

---

## ✨ Features

- Glow effect (breathing LEDs or diffused RGB)
- RFID-triggered activation (sound + LED animation)
- Modular design

---

## ⚙️ Hardware Used

- Arduino Nano
- DFPlayer Mini + microSD for sound effects
- RFID module (MFRC522) + tags
- LEDs + resistor network (diffuser for glow effect)
- Speaker (8Ω 1–3W recommended)

---

## 🔌 Wiring Overview

- RFID → microcontroller SPI pins
- DFPlayer Mini → UART pins
- LED (with resistor) → PWM pin

---

## ▶️ Demo

https://www.youtube.com/watch?v=GqTXzMdnqlU

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

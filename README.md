# 🌞 OpenLumen – DIY LED Longevity Panels  
*Build light, not hype.*

OpenLumen is an open-source project that empowers makers to build their own **multi-spectral LED panels** for **health, mood, and longevity**.  
Rather than selling magic boxes, we’re open-sourcing everything — from hardware designs to the peer-reviewed research behind each function.

Use OpenLumen to:
- Wake up before sunrise with natural light.
- Generate vitamin D safely without going outside.
- Run red-light or near-infrared sessions for recovery.
- Try green-light therapy for migraines.
- Experiment with 40 Hz flicker for cognitive research.

---

## ⚙️ What OpenLumen Is

A modular system of LED panels + smart controller firmware that lets users **replicate therapeutic light environments** backed by science.

Each spectral mode is justified with published research (see [`research.md`](./docs/research.md)), so you can understand *why* specific wavelengths, intensities, and exposure times were chosen.

---

## ✨ Core Features

| Category | Description | Typical Specs |
|-----------|-------------|----------------|
| **🌅 Dawn Simulation** | Gradual ramp-up to 250 lux pre-wake light improves alertness and mood. | 30 min ramp, warm white LEDs |
| **☀️ Morning / Daylight Mode** | 10 000 lux full-spectrum light for circadian entrainment and seasonal affective support. | 20–30 min after waking |
| **💊 Vitamin D Mode** | Narrowband UV-B (~295 nm) with built-in dose limiter based on Holick’s rule. | < 100 J/m², interlocked UV section |
| **🔴 Red / NIR Therapy** | 630–850 nm LEDs for photobiomodulation – mitochondrial stimulation, wound healing, skin rejuvenation. | 10–30 mW/cm² for 5–20 min |
| **💚 Green Light for Migraine** | 525 ± 10 nm reduces headache frequency and pain intensity. | 1–2 h daily at comfortable brightness |
| **🔵 Blue Light for Acne** | 415 nm antibacterial LED destroys *P. acnes* via porphyrin photoactivation. | 6 min daily per area |
| **⚡ 40 Hz Gamma Flicker** | Non-invasive brainwave entrainment mode under active research for cognitive health. | 40 Hz flicker, ~150 lux |
| **🧠 Custom Mode Builder** | Combine wavelengths, pulses, and brightness levels into your own protocols. | All programmable |

---

## 🧩 Hardware Overview

- Modular LED tiles (white, red, green, blue, NIR, UV-B)  
- Microcontroller or SBC driver board with PWM + pulse control  
- Onboard temperature & light sensors  
- Touchscreen or web UI  
- Safety interlocks for UV modules  
- Open schematic and PCB design files (KiCad)

**Optional Modules**
- External ambient light sensor (auto-brightness)
- MQTT / Home Assistant integration
- BLE / Wi-Fi app for mobile control

---

## 🔬 Why It Matters

Light isn’t just illumination — it’s information for your biology.  
OpenLumen bridges the gap between **DIY engineering** and **biological literacy**:

- Every wavelength mode is based on peer-reviewed data.  
- All intensities and durations are traceable to known fluence and lux values.  
- Users can verify, replicate, and contribute data from their own setups.

---

## 🧠 Project Goals

1. **Open Science** – Bring transparency to light therapy by linking claims to citations.  
2. **Personalization** – Enable users to adjust timing, intensity, and wavelength to fit their goals and environments.  
3. **Affordability** – Provide a build-it-yourself alternative to $1000+ commercial panels.  
4. **Safety** – Implement interlocks, timers, and UV dose controls meeting IEC 62471 guidelines.  
5. **Community** – Foster collaboration between makers, engineers, clinicians, and researchers.

---

## 🛠️ Development Roadmap

| Stage | Description | Status |
|-------|--------------|--------|
| ✅ Research Compilation | Literature summary & safe exposure limits | In Progress |
| 🧩 Hardware Specification | LED selection, drivers, power design | In progress |
| 💻 Firmware & UI | PWM control, pulse modulation, schedule system | Planned |
| 🧪 Prototype Testing | Optical calibration, user feedback | Planned |
| 🧰 DIY Kits & Docs | Complete assembly instructions + BOM | Planned |

---

## 🤝 Contributing

We welcome pull requests and data contributions!

- Share circuit improvements or firmware modules.  
- Submit your measured irradiance or user protocol data.  
- Help refine open safety standards for hobbyist light projects.

---

## ⚠️ Disclaimer

OpenLumen is for **educational and experimental** purposes.  
It is **not a medical device** and does not claim to diagnose, treat, or cure any condition.  
Always use UV protection and follow safety guidelines.  
Consult a qualified professional before attempting therapeutic use.

---

## 🧾 License Summary

| Part | License | Notes |
|------|----------|-------|
| Hardware / Firmware / Software | **PolyForm Noncommercial 1.0.0** (free for personal & educational use) | Commercial use requires a license from Don't Die Gloriously |
| Documentation & Research | **CC BY-SA 4.0** | Open for sharing and adaptation with attribution |
| Commercial Use | **By Agreement** | Contact [licensing@dontdiegloriously.com](mailto:licensing@dontdiegloriously.com) |

© 2025 Don't Die Gloriously – All rights reserved for commercial use.

---

**OpenLumen** – *open light for open minds.*

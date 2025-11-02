# 🧪 OpenLumen Research Overview
*Evidence-based reference for the design of DIY LED longevity panels.*

---

## 1. Bright-Light Therapy and Circadian Entrainment

**Purpose:** Realign circadian rhythm, improve alertness and mood, and support wakefulness when natural sunlight is unavailable.

- **10 000 lux morning light** – Clinical light boxes for Seasonal Affective Disorder (SAD) typically emit 10 000 lux of diffuse light.  
  The **Mayo Clinic** recommends using such light **within the first hour after waking**, for **20–30 minutes**, at a distance of **40–60 cm (16–24 inches)**.  
  The light should filter out UV.  
  → [Mayo Clinic: Seasonal Affective Disorder Treatment](https://www.mayoclinic.org/diseases-conditions/seasonal-affective-disorder/in-depth/seasonal-affective-disorder-treatment/art-20048298) :contentReference[oaicite:0]{index=0}

- **Dawn Simulation** – Gradual pre-wake light increase improves alertness and subjective well-being.  
  Laboratory studies found that a gradual increase to ~250 lux before wake-up improved alertness compared with static or dim light exposure.  
  → [Industrial Health Study – Dawn Simulation](https://pmc.ncbi.nlm.nih.gov/articles/PMC5136610/) :contentReference[oaicite:1]{index=1}

- **Melatonin-friendly evening light** –  
  A 2025 randomized study compared 3-hour exposures to **blue (464 nm)** vs **red (631 nm)** LEDs.  
  Salivary melatonin dropped significantly under blue light but recovered under red light, demonstrating that **red light minimally disrupts circadian rhythm**.  
  → [Comparative Effects of Red and Blue LED Light on Melatonin Levels – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12113466/) :contentReference[oaicite:2]{index=2}

**Design implication:**  
Include programmable “Daylight” (~10 000 lux) and “Evening” (red/amber) modes, plus an automatic **30-minute sunrise sequence** up to ~250 lux.

---

## 2. Sunlight Replication and Vitamin D Synthesis

**Goal:** Enable safe vitamin D production using controlled UV-B emission.

- **Vitamin D Action Spectrum** –  
  Vitamin D synthesis peaks at **~295 nm**, effective range **290–315 nm**, via UV-B conversion of 7-dehydrocholesterol to pre-vitamin D₃.  
  → [NIWA: Action Spectrum for Vitamin D Synthesis PDF](https://niwa.co.nz/sites/default/files/action_spectrum_for_vit_d_synthesis.pdf) :contentReference[oaicite:3]{index=3}

- **Safe Dosing (“Holick’s Rule”)** –  
  One *minimal erythema dose (MED)* of whole-body UV exposure (~mild pinkness) ≈ 10 000–25 000 IU of vitamin D₃.  
  Exposing ¼ of the body to ¼ of an MED yields ≈ 1 000 IU.  
  → [The Relationship between UV Exposure and Vitamin D Status – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3257661/) :contentReference[oaicite:4]{index=4}

- **UV-B LED safety example:**  
  A 2025 veterinary study used **295 nm LEDs** delivering **80–360 J/m² daily**, considered safe under Holick’s limits.  
  → [Effects of UV-B Light Exposure During Automatic Milking – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11776301/) :contentReference[oaicite:5]{index=5}

**Design implication:**  
Use narrowband 295 nm LEDs with hardware interlocks, dose timers, and protective filters; cap exposure to ≤ 100 J/m².

---

## 3. Photobiomodulation (Red + Near-Infrared Light)

**Purpose:** Mitochondrial stimulation, wound healing, skin rejuvenation, and neuroprotection.

- **Mechanism:**  
  Light in the **600–1100 nm** range stimulates cytochrome c oxidase, enhancing ATP production and nitric-oxide signaling.  
  → [Photobiomodulation: Shining a Light on Depression – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11671386/) :contentReference[oaicite:6]{index=6}

- **Typical Parameters:**  
  - Irradiance: **10–30 mW/cm²**  
  - Energy density: **0.1–15 J/cm²**  
  - Pulse frequency: **1–3000 Hz**  
  → Same source:contentReference[oaicite:7]{index=7}

- **Skin Rejuvenation Trial:**  
  Volunteers treated twice weekly with **611–650 nm** or **570–850 nm** broadband light improved skin smoothness and collagen density.  
  → [Controlled Clinical Trial – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3926176/) :contentReference[oaicite:8]{index=8}

- **Wound Healing:**  
  Mouse studies: **820 nm** produced the best healing, closing wounds 3–4 days faster than shorter wavelengths at 1–2 J/cm².  
  → [Low-Level Light Stimulates Wound Healing – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC2935798/) :contentReference[oaicite:9]{index=9}

**Design implication:**  
Include 630–660 nm and 820–850 nm LEDs, selectable fluence 1–10 J/cm², and optional pulsed mode for thermal management.

---

## 4. Green Light Therapy for Migraine and Pain

**Clinical Data:**  
A crossover trial (29 participants) compared white vs green LED exposure (525 ± 10 nm).  
- Duration: 1–2 h daily for 10 weeks.  
- Results: Significant reduction in headache days and improved quality of life.  
→ [Evaluation of Green Light Exposure on Headache Frequency – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC8034831/) :contentReference[oaicite:10]{index=10}

**Design implication:**  
Add a low-intensity green-light mode (around 525 nm) for 1–2 h comfort sessions.

---

## 5. Blue Light Therapy for Acne and Skin Conditions

**Mechanism:**  
*Propionibacterium acnes* produces porphyrins that absorb **blue light (~415 nm)**; activation releases singlet oxygen that kills bacteria.

- **Clinical Efficacy:**  
  A self-applied 414 nm LED device used 6 min per day for 8 weeks significantly reduced acne lesions.  
  → [Clinical Efficacy of Self-Applied Blue Light Therapy – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC2923954/) :contentReference[oaicite:11]{index=11}

**Safety note:**  
Avoid prolonged or late-evening exposure due to blue light’s melatonin suppression.

---

## 6. Gamma-Frequency (≈ 40 Hz) Light Flicker for Neurological Health

**Concept:** Non-invasive entrainment of neural gamma rhythms (~40 Hz) may help reduce amyloid-β and tau in Alzheimer’s models.

- **Animal Data:**  
  1 h/day of 40 Hz flicker reduced amyloid and tau accumulation.  
  → [Study on 40 Hz Non-Invasive Light Therapy – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC10600489/) :contentReference[oaicite:12]{index=12}

- **Human Case Studies:**  
  40 Hz stimulation (208–435 lumens at 30 cm) entrained EEG gamma rhythms more effectively than 60 Hz or 80 Hz flicker.  
  → [Gamma Band Light Stimulation – PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC6700637/) :contentReference[oaicite:13]{index=13}

**Design implication:**  
Add programmable flicker (30–60 Hz range) with adjustable duty cycle; default to ~150 lux for comfort.

---

## 7. Other Potential Functionalities

| Function | Wavelength | Notes |
|-----------|-------------|-------|
| **Blue Light for Neonatal Jaundice** | ~460 nm | Used clinically to photo-isomerize bilirubin; for research only. |
| **UV-A / PUVA Therapy for Psoriasis** | 311 nm UV-B or UVA + Psoralen | Requires medical supervision; not for consumer devices. |
| **Pulsed Audio/Light Stimulation** | 40 Hz combined photic + auditory | May enhance gamma entrainment; under active study. |

---

## 8. Key Wavelengths and Parameters Summary

| Mode | Wavelength(s) | Typical Intensity / Dose | Reference |
|------|----------------|--------------------------|------------|
| Morning Light | Full-spectrum white (5000–6500 K) | 10 000 lux for 20–30 min | Mayo Clinic:contentReference[oaicite:14]{index=14} |
| Dawn Simulation | Warm white ramp to 250 lux | 30 min ramp pre-wake | Industrial Health:contentReference[oaicite:15]{index=15} |
| Evening / Red Light | 631 nm | Avoid blue (~460 nm) | Melatonin study:contentReference[oaicite:16]{index=16} |
| Vitamin D | 295 nm UV-B | ≤ 100 J/m² | NIWA + Holick:contentReference[oaicite:17]{index=17}:contentReference[oaicite:18]{index=18} |
| PBM (Red/NIR) | 630–850 nm | 10–30 mW/cm²; 1–15 J/cm² | PBM review:contentReference[oaicite:19]{index=19} |
| Skin Rejuvenation | 611–650 nm / 570–850 nm | 8–50 J/cm² | Clinical trial:contentReference[oaicite:20]{index=20} |
| Wound Healing | 635–820 nm | 1–2 J/cm² | Mouse study:contentReference[oaicite:21]{index=21} |
| Migraine Relief | 525 ± 10 nm | 1–2 h/day | Green LED trial:contentReference[oaicite:22]{index=22} |
| Acne Therapy | 414–420 nm | 6 min/day | Blue light study:contentReference[oaicite:23]{index=23} |
| Gamma Flicker | 40 Hz | ~150 lux | Human EEG study:contentReference[oaicite:24]{index=24} |

---

## 9. Safety & Design Principles

- Follow **IEC 62471** photobiological safety standards for lamp exposure.  
- Include hardware interlocks for UV + high-intensity blue modes.  
- Require eye protection and limit session durations.  
- Implement thermal monitoring and automatic timeouts.  
- Provide clear user documentation and educational prompts in the UI.

---

## 📚 References

For the complete list of scientific sources that inform OpenLumen’s wavelength selections, exposure parameters, and design principles, see:

- [**Full Reference Library (Markdown)**](./references.md) – A human-readable table of all peer-reviewed papers and institutional sources used in this project.  
- [**Structured Source Data (JSON)**](./research_sources.json) – Machine-readable citation metadata for use in documentation pipelines or web UIs.

These resources are continuously updated as new studies emerge and OpenLumen expands into new light-based applications.

---

*Prepared for the OpenLumen Project by Don't Die Gloriously – 2025.*  
*All citations link to open-access or peer-reviewed sources.*

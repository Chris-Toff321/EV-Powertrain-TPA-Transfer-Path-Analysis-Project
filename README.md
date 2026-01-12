# EV Powertrain Transfer Patah Analysis

## An engineering-level Transfer Path Analysis (TPA) study that identifies, quantifies, and virtually optimizes structure-borne and airborne noise paths in an EV powertrain.


---
## Scope
- Path-based NVH analysis of an electric powertrain
- Separation of structure-borne and airborne contributions
- Contribution ranking at the interior receiver
- Engineering-oriented TPA model validation
- Support for virtual NVH optimization and prediction


## Overview

This repository documents an **engineering-level Transfer Path Analysis (TPA) project** focused on the noise and vibration contribution analysis of an **electric vehicle (EV) powertrain system**.

The project demonstrates how **structure-borne and airborne transmission paths** can be accurately identified, quantified, and virtually optimized using measurement-based TPA methods combined with advanced modeling techniques.


---

## Project Objectives

- Identify dominant **noise and vibration transmission paths** in an EV powertrain
- Quantify **individual path contributions** to interior noise
- Separate **structure-borne** and **airborne** noise mechanisms
- Validate TPA model accuracy using **time-domain synthesis**
- Support **virtual modification and NVH performance prediction**

---

## Methodology

The project applies **measurement-based Transfer Path Analysis (TPA)** with the following workflow:

1. **Excitation identification**  
   - Inverse matrix method used to calculate operational forces
   - Structure-borne excitations derived from accelerometer data
   - Airborne excitations derived from sound pressure / volume velocity

2. **Transfer function measurement**
   - Structural transfer functions measured under static conditions
   - Acoustic transfer functions measured in a semi-anechoic environment

3. **TPA model synthesis**
   - Separation of structure-borne and airborne paths
   - Time-domain reconstruction of binaural interior signals
   - Order-based and frequency-based contribution analysis

4. **Model validation**
   - Comparison between measured and synthesized binaural signals
   - Verification using motor orders and PWM switching harmonics

---

## Test Configuration (High-Level)

- **Vehicle type:** Battery electric vehicle (2WD)
- **Powertrain:** PMSM electric drive unit
- **Key structure-borne paths:**  
  - Left powertrain mount  
  - Right powertrain mount  
  - Rear powertrain mount
- **Airborne paths:**  
  - Multiple microphone positions surrounding the powertrain(motor)
- **Receiver:**  
  - In-cabin binaural artificial head system

> Note: All vehicle-specific and proprietary identifiers have been anonymized.

---

## Key Findings

### Structure-Borne Noise
- Dominant below **1 kHz**
- Strong contributions observed from **left and rear mounts**
- Motor orders (16, 24, 48) significant below mid-frequency range
- PWM-related harmonics (±12 orders) clearly transmitted via mounts

### Airborne Noise
- Dominant in **mid-to-high frequency range**
- Major radiation from **bottom and rear surfaces** of the powertrain
- Motor orders (24, 48, 96) clearly identifiable
- PWM switching frequency (~8 kHz) contributes to both airborne and structure-borne paths

---

## Virtual Modification & Prediction

Based on the validated TPA model, the project demonstrates:

- **Virtual modification of Acoustic Transfer Functions (ATF)**
- **Mount isolation performance prediction**
- Identification and mitigation of a **~3200 Hz resonance band**
- Comparison of noise contributions **before and after virtual changes**

These steps illustrate how TPA can be used not only for diagnosis, but also for **engineering decision support and development acceleration**.

---

## EMTF Extension

The project further discusses the use of **EMTF (Equivalent Mount Transfer Function)** concepts to:

- Bridge test-bench data and full-vehicle NVH performance
- Enable real-time path switching and contribution visualization
- Support early-stage NVH development and prediction

---

## Engineering Value

- Combines **objective data and subjective auralization**
- Enables **path-level sound quality assessment**
- Reduces dependency on repeated vehicle-level testing
- Supports **model-based NVH development for EV platforms**

---




## Files in This Repository



## Intended Audience

- Automotive NVH engineers  
- Acoustics and vibration engineer and specialists  
- EV powertrain development engineers, automotive R&D professionals
- Researchers working on BTPA, TPA, OTPA, EMTF, or NVH modeling  

---

## Disclaimer

This repository is intended for **technical demonstration and knowledge sharing only**.

- All data shown are project-specific and anonymized
- No confidential vehicle parameters or OEM-sensitive information are disclosed
- The content does not represent any official position of an OEM or supplier
- Do not use any data, images, or text from this repository for commercial promotion or profit-oriented purposes.

---

## Contact

For technical discussion or professional exchange:

- NVH / Acoustics Engineer  
- Focus areas: TPA, EV NVH, sound quality, virtual NVH development  

---

*If you find this project useful, feel free to star or fork the repository.*

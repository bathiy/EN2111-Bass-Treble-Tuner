# 🎵 Low-Power Hi-Fi Class-AB Audio Amplifier

This project is a **low-power Hi-Fi audio amplifier** designed using **Class AB topology**, implemented as part of the EN2111 – Electronic Circuit Design module at the University of Moratuwa.

## 📘 Overview

This project demonstrates the design, simulation, and implementation of a **Class AB audio amplifier system**, including a **pre-amplifier**, **Baxandall tone controller**, and **power amplifier** to drive an 8Ω speaker. The focus was on achieving high-fidelity sound output with low distortion and adjustable bass/treble response.

---

## 👨‍💻 Team Members

| Name                        | Index No     |
|-----------------------------|--------------|
| BANDARA M.G.S.S.           | 220064U      |
| BANDARA G.A.M.I.K.         | 220059J      |
| KULASINGHE H.P.G.N.A.      | 220334A      |
| ANURADHA D.M.B.P.          | 220036L      |

---

## 🔧 Features

- **Pre-Amplifier Stage** using TL072 Op-Amp  
- **Baxandall Tone Control** with adjustable Bass and Treble  
- **Class AB Power Amplifier** using LM386 and complementary BJTs  
- **Dual Power Supply** operation for better headroom  
- **Breadboard Prototype** and **Oscilloscope Measurements**  
- **Frequency Response & FFT Analysis**  
- Addressed **Crossover Distortion** issues in Class AB  

---

## 🛠️ Circuit Stages

### 1. Pre-Amplifier
- Input buffer with high-pass filtering
- Gain: ~21.58 dB
- TL072 used for low-noise, high slew rate

### 2. Baxandall Tone Controller
- Active tone control circuit
- Adjustable bass (~400–1000 Hz) and treble (~3 kHz)
- TL072 with potentiometers for tone shaping

### 3. Power Amplifier (Class AB)
- LM386 drives a BJT push-pull stage (2N3904 & 2N3906)
- Output power: ~1.57W into 8Ω speaker
- Efficiency: ~65.4%
- Estimated bandwidth: ~10 Hz to 150 kHz

---

## 🧪 Measurements & Results

- **Tested on Breadboard**
- **Waveform analysis** done for 400 Hz, 1 kHz, and 3 kHz
- **FFT analysis** showed presence of harmonics due to crossover distortion
- Controlled gain, tone, and volume observed in oscilloscope outputs
- **Crossover distortion** at high frequencies (15–20 kHz) due to transistor mismatch

---

## ⚙️ Simulations

- Simulated using **Proteus** and **LTSpice**
- Frequency response of tone control stage analyzed

---

## 📌 Lessons Learned

- Importance of **proper transistor biasing** in Class AB designs
- How **resistor selection** affects bias points and amplifier stability
- Trade-offs between power efficiency, distortion, and gain
- Techniques to **reduce crossover distortion** in analog audio amps

---

## 📅 Submission Info

- **Module**: EN2111 – Electronic Circuit Design  
- **University**: University of Moratuwa, Sri Lanka  
- **Submission Date**: 2025.06.01  
- **Group No.**: 04

---

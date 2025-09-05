# 🎶 5-Band Analog Equalizer  
  
[![CAD](https://img.shields.io/badge/Enclosure-SolidWorks-lightgrey)](#)  
[![Team](https://img.shields.io/badge/Collaboration-Team%20Project-purple)](#)  

A **5-Band Analog Audio Equalizer** built from scratch as part of an **Analog Design Project**.  
This project explores **audio signal processing using analog circuitry**, enabling users to shape and enhance sound across five distinct frequency bands.  

---

## ✨ Features  

- **5-Band Frequency Control**  
  - 60–300 Hz (Low)  
  - 300–1000 Hz (Low-Mid)  
  - 1–4 kHz (Mid)  
  - 4–10 kHz (High-Mid)  
  - 10–20 kHz (High)  

- **Precision Signal Processing**  
  - Buffered input audio  
  - Bandpass filtering for each frequency range  
  - Summed output for balanced and clean audio  

- **Audio Performance**  
  - Designed with **TL072 Op-Amps** for low-noise, high-fidelity sound  

- **User-Friendly Design**  
  - **LED indicators** for real-time band monitoring  
  - Custom **enclosure design** for a sleek, professional finish  

---

## 🛠️ Technologies & Tools  

- **Circuit Simulation & Design:** LTSpice / Multisim  
- **Prototyping:** Breadboard implementation  
- **PCB Design:** Altium Designer  
- **Enclosure Design:** SolidWorks / CAD tools  
- **Components:** TL072 Op-Amps, Resistors, Capacitors, Potentiometers, LEDs  

---

## 🚀 Getting Started  

1. **Build the Circuit** – Assemble the bandpass filters and buffering stages on a breadboard.  
2. **Test the Frequency Response** – Use a signal generator + oscilloscope to verify band cutoffs.  
3. **Integrate LED Indicators** – Connect LED driver circuit for real-time monitoring.  
4. **Assemble PCB & Enclosure** – Transfer the circuit to PCB and fit into the designed enclosure.  
5. **Enjoy Your Music!** 🎶  


---

## 📂 Repository Structure  

```bash
├── schematics/        # Circuit diagrams and LTSpice/Multisim files
├── pcb_layout/        # PCB design files (Altium)
├── enclosure/         # CAD models and renders
├── docs/              # Reports, notes, frequency response graphs
└── README.md          # Project documentation

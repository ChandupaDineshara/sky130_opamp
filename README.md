# Low-Power Single-Ended Operational Amplifier | Sky130 PDK

This project is part of **CMOS Analog IC Design and Simulation ’25 (Assignment 4)**.  
The objective is to design and simulate a **low-power single-ended operational amplifier** in the **SkyWater 130nm PDK**, intended to function as a **unity-gain buffer for low-frequency analog signals (1–10 kHz)**.

---

## 📌 Design Objectives
- **Technology**: Sky130 CMOS
- **Supply Voltage**: 1.7 V – 1.9 V  
- **Nominal Input Common-Mode Range**: (VDD/2 - 0.2 V) – (VDD/2 + 0.2 V)  
- **Load Capacitance**: 25 pF  
- **Input Signal**: < 0.4 Vpp, 1–10 kHz  
- **Performance Targets**:
  - DC Gain ≥ 60 dB  
  - GBW ≥ 1 MHz  
  - Phase Margin > 60°  
  - Slew Rate > 1 V/µs  
  - Input Offset < 3 mV  
  - Quiescent Current < 100 µA  
  - Disable Current < 2 nA  
  - Final Layout Area ≤ 140 µm × 80 µm  

---

## 🚀 Current Progress
- ✅ **Schematic drawn**  
- ✅ **Initial hand calculations** done for rough sizing  
- ✅ **Practice layout** completed *(⚠️ not the final layout — only to familiarize with layout design tools)*  

---

## 🔄 Workflow Plan
1. **Schematic simulations** (DC, AC, transient, stability, corners, Monte Carlo)  
2. **Refinement** of device sizing until target specifications are met  
3. **Final layout design**  
4. **Verification**:
   - DRC (Design Rule Check)  
   - LVS (Layout vs. Schematic)  
   - Post-layout simulations  

---

## 📷 Project Snapshots
- **Schematic**  
  ![Schematic](./images/schematic.png)  

- **Practice Layout (Not Final)**  
  ![Layout](./images/layout.png)  
  > ⚠️ This layout is only for practice and familiarization, not the final verified design.  

---

## 📅 Next Steps
- Complete schematic-level simulations  
- Finalize layout  
- Run DRC & LVS checks  
- Perform post-layout simulation  

---






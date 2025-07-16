# Breadboard Power Supply Module 

A compact, dual-output breadboard power supply that delivers **regulated 5V and 3.3V** from a 12V DC input. Designed for electronics prototyping, embedded systems, and educational projects.

## Overview

This custom PCB module is designed to fit alongside a standard breadboard and provide clean, stable power rails via male headers and screw terminals. The module uses **LM7805** and **LM317** linear regulators, along with standard passive components, to output 5V and 3.3V from a single 12V barrel jack input.

Ideal for powering:
- Microcontrollers (Arduino, ESP32, etc.)
- Sensors and modules
- Digital/analog circuits
- Educational breadboard projects

---
## Breadboard Power Supply Images
### Top View
<img width="769" height="765" alt="BPS_Topview1" src="https://github.com/user-attachments/assets/38d13522-cb3f-4307-bf5b-d9808a783a09" />

### Bottom View
<img width="883" height="741" alt="BPS_Bottomview" src="https://github.com/user-attachments/assets/431efa9c-c8a0-434a-8c26-70ab66b3734a" />

### Front View
<img width="1176" height="822" alt="BPS_Frontview" src="https://github.com/user-attachments/assets/a1d1bf9d-d823-48f6-afe2-00679739ce99" />

### Schematic Capture
<img width="2124" height="1114" alt="BPS_Schematic_Capture" src="https://github.com/user-attachments/assets/a1383d8e-269e-4053-91c7-ffdb21a372ab" />

### PCB Layout
<img width="1036" height="1100" alt="BPS_PCB_Layout" src="https://github.com/user-attachments/assets/a732697f-206e-4120-bbfc-d7b2bb3cc456" />

---

## Specifications

| Feature                | Description                             |
|------------------------|-----------------------------------------|
| **Input Voltage**      | 12V DC (Barrel Jack)                    |
| **Output Voltages**    | 5V (LM7805), 3.3V (LM317)               |
| **Current Output**     | Up to 1A (with heatsinks)               |
| **LED Indicator**      | Red LED (power-on status)               |
| **Switch**             | EG1218 toggle switch                    |
| **Connectors**         | Screw terminals & 2.54mm pin headers    |
| **Capacitors**         | 10µF, 0.1µF, and 1µF for decoupling     |
| **PCB Type**           | 2-layer, through-hole design            |
| **Breadboard Ready**   | Outputs connect directly to breadboard  |

---

## Components Used

- **LM7805** – 5V linear voltage regulator
- **LM317** – Adjustable linear regulator (configured for 3.3V)
- **Capacitors** – 10µF, 0.1µF, 1µF
- **Resistors** – 330Ω, 560Ω
- **LED** – Power indicator
- **EG1218 switch** – On/off control
- **DC Barrel Jack** – Power input
- **Pin Headers & Screw Terminals**

---

## Files Included

- `BPS_Schematic_Capture.png` – Circuit schematic
- `BPS_Topview1.png` – 3D top view of the PCB
- `BPS_Bottomview.png` – 3D bottom view of the PCB
- `KiCad/` – Source files for schematic and PCB layout (optional)
- `Gerber/` – Gerber files for fabrication (optional)

---

## Getting Started

1. Connect a **12V DC adapter** to the barrel jack.
2. Toggle the switch to power on the board.
3. Use the screw terminals or headers to connect **3.3V and 5V** rails to your breadboard.
4. Observe the LED indicator for power status.

>  For currents approaching 1A, heatsinks are recommended on the regulators.

---

## Skills Demonstrated

- Circuit design and voltage regulation  
- Component selection and schematic capture (KiCad)  
- Footprint assignment and ERC/DRC validation  
- PCB layout, teardrop optimization, and routing  
- 3D modeling and design review  
- Design for manufacturability (DFM)





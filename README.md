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





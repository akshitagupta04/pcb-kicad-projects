# Simple LED Circuit – KiCad PCB Design 

## Overview
<p align="justify">
This project is my first complete Printed Circuit Board (PCB) design, created entirely in KiCad 9.0. It is simple LED circuit based on a beginner tutorial. The project involved drawing a schematic, designing the board layout, and generating the manufacturing files. 
</p> 

---

## Circuit Description
This is a basic circuit showing how to connect an LED to a power source with a current-limiting resistor. The design uses through-hole components. 

- **Power Input:** 9V battery (designed with a two-pin header for a battery clip connection)
- **Current Limiting Resistor:** 470Ω
- **LED Indicator:** 2V Red LED 

---

## Tools Used
- **KiCad:** For schematic capture, PCB layout, and Gerber file generation. 

---

## Design Process
The board was designed in KiCad following these steps:
 
1. **Schematic Capture:** <p align="justify"> Drew the circuit diagram, placed the battery, resiator, and LED symbols, and connected their pins with wires. Annotated the schematic to give components unique values (resistor value = 470 (ohm), battery value = 9V, LED value = 2V RED). 
</p> 

2. **Footprint Assignment:** <p align="justify"> Assigned physical footprints from the KiCad library to each schematic symbol (e.g., a ***Resistor_THT*** footprint for the resistor, ***LED_THT*** for the LED, and a ***Connector_PinHeader_2.54mm*** for the battery connection). 
</p>

3. **Electrical Rules Check (ERC):** <p align="justify"> Checked the schematic to confirm no electrical errors were present.
</p>

4. **Bill of Materials (BOM):** 

---

## Learning Outcomes 

---

## Repository Structure 

---

## Credits and Acknowledgement 
This design was made by following the tutorial below. The project structure and steps are based rntirely on this guide. 

- **Tutorial:** [KiCad Tutorial: Make Your First Printed Circuit Board](https://www.build-electronic-circuits.com/kicad-tutorial/)
- **Author:** Oyvind Dahl, Build Electronic Circuits
 

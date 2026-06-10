# Simple LED Circuit – KiCad PCB Design 

## Overview
<p align="justify">
This project is my first complete 2-layer Printed Circuit Board (PCB) design, created entirely in KiCad 9.0. It is simple LED circuit based on a beginner tutorial. The project involved drawing a schematic, designing the board layout, and generating the manufacturing files. 
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

4. **Bill of Materials (BOM):** <p align="justify"> Generated the BOM from the schematic, listing all components with values, footprints, and datasheet links.
</p>

5. **PCB Layout:** <p align="justify"> Opened the board editor, placed the footprints in an organized way, and drew copper tracks to connect them according to the schematic. 
</p>

6. **Board Outline:** <p align="justify"> Drew the physical edge of the board on the Edge.Cuts layer. 
</p>

7. **Design Rules Check (DRC):** <p align="justify"> Checked the layout for physical errors, like tracks placed too close, to confirm no physical errors were present. 
</p>

8. **Manufacturing Output:** <p align="justify"> Generated the Gerber and Drill files needed for fabrication, and the Footprint Position (.pos) file for automated assembly. 
</p>

---

## Repository Structure

```text
/01-kicad-simple-led-circuit/
 ├────── gerber-files/   # Manufacturing files (Gerber, Drill and Footprint position)
 ├────── pcb-layout/     # Board layout files
 ├────── schematic/      # schematic and BOM files
 ├────── system-design/  # images of the board from 3D view
 └────── Readme.md       # Readme file 
``` 
---

## Learning Outcomes
<p align="justify">
By completing this project, I learned the standard KiCad workflow: schematic capture, component to footprint mapping, PCB layout, design rule checking, and generation of manufacturing output. This forms the base for all future designs. 
</p>

---

## Credits and Acknowledgement 
This design was made by following the tutorial below. The project structure and steps are based rntirely on this guide. 

- **Tutorial:** [KiCad Tutorial: Make Your First Printed Circuit Board](https://www.build-electronic-circuits.com/kicad-tutorial/)
- **Author:** Oyvind Dahl, Build Electronic Circuits
 

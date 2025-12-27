# Flight Controller Project

This repository contains the final design of a **flight controller**, including the BOM, schematic, PCB layout, and 3D model preview.  
This design uses a **4-layer PCB** for stable power distribution and signal integrity.  
---

## Bill of Materials (BOM)

Below is the list of essential components used in the flight controller. These are the components required for proper operation:

| Designator(s)              | Quantity       | Component Name / Description                                |
|-----------------------------|---------------|-------------------------------------------------------------|
| C1, C10, C14, C2, C3, C4, C5, C9 | JLCPCB PCBA | 100nF 0402 Ceramic Capacitor                                 |
| C11                        | JLCPCB PCBA   | 2.2nF 0402 Ceramic Capacitor                                |
| C12                        | JLCPCB PCBA   | 10uF/50V 1206 Ceramic Capacitor                              |
| C13                        | JLCPCB PCBA   | 150pF 0402 Ceramic Capacitor                                  |
| C15                        | JLCPCB PCBA   | 22uF/16V 1206 Ceramic Capacitor                               |
| C16, C17                   | JLCPCB PCBA   | 10uF 0805 Ceramic Capacitor                                   |
| C6, C7                     | JLCPCB PCBA   | 20pF 0402 Ceramic Capacitor                                   |
| C8                         | JLCPCB PCBA   | 10nF 0402 Ceramic Capacitor                                   |
| D1, D2                     | JLCPCB PCBA   | SS34 Schottky Diode                                           |
| D3, D5                     | JLCPCB PCBA   | Red LED 0603                                                 |
| D4                         | JLCPCB PCBA   | Blue LED 0603                                                |
| D6                         | JLCPCB PCBA   | S7 Diode SOD-123                                             |
| J1                         | JLCPCB PCBA   | 3-pin Header Pad (SBUS)                                      |
| J2                         | JLCPCB PCBA   | USB-C Receptacle, Palconn UTC16-G, USB2.0                    |
| J3                         | JLCPCB PCBA   | 3-pin Header Pad (PPM)                                       |
| J4                         | JLCPCB PCBA   | 6-pin Header Pad (OUT)                                       |
| J5, J6                     | JLCPCB PCBA   | 2-pin Connector Pad                                          |
| J7                         | JLCPCB PCBA   | 4-pin Connector Pad                                          |
| L1                         | JLCPCB PCBA   | 15uH / 3A Power Inductor, SMD Neosid SM-PIC0602H            |
| NT1                        | JLCPCB PCBA   | Net Tie, 2 pads SMD 2.0mm                                   |
| Q1                         | JLCPCB PCBA   | 1P NPN Transistor, SOT-23, MMBT2222A                        |
| R1, R2                     | JLCPCB PCBA   | 10kΩ 0402 Resistor                                           |
| R10                        | JLCPCB PCBA   | 24kΩ 0402 Resistor                                           |
| R11, R12, R18, R9          | JLCPCB PCBA   | 100kΩ 0402 Resistor                                          |
| R13                        | JLCPCB PCBA   | 200kΩ 0402 Resistor                                          |
| R14                        | JLCPCB PCBA   | 39kΩ 0402 Resistor                                           |
| R15                        | JLCPCB PCBA   | 150Ω 0402 Resistor                                           |
| R16                        | JLCPCB PCBA   | 330Ω 0402 Resistor                                           |
| R17                        | JLCPCB PCBA   | 260Ω 0402 Resistor                                           |
| R19                        | JLCPCB PCBA   | 12kΩ 0402 Resistor                                           |
| R20, R21                   | JLCPCB PCBA   | 5.1kΩ 0402 Resistor                                          |
| R3, R4, R5, R6             | JLCPCB PCBA   | 4.7kΩ 0402 Resistor                                          |
| R7, R8                     | JLCPCB PCBA   | 22Ω 0402 Resistor                                            |
| SW1                        | JLCPCB PCBA   | SPST Push Button Switch B3U-1000P                            |
| U1                         | JLCPCB PCBA   | STM32F103C8T6 Microcontroller, LQFP-48, 7x7mm               |
| U2                         | JLCPCB PCBA   | MPU-6050 3-axis Gyroscope & Accelerometer, QFN-24 4x4mm      |
| U3                         | JLCPCB PCBA   | MP1584 Buck Converter, SOIC-8                                  |
| U4                         | JLCPCB PCBA   | AZ1117-3.3V Voltage Regulator, SOT-89-3                       |
| Y1                         | JLCPCB PCBA   | 8MHz Crystal Oscillator, SMD 3225 4-pin                      |



> The BOM above is based on the `bom.csv` file in the repository.  

---

## Schematic


<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/9325a1ec-2ce2-4775-a86c-718ce7f457de" />


---

## PCB Layout and 3D Preview


<img width="432" height="421" alt="image" src="https://github.com/user-attachments/assets/2fe1d3b3-6c85-42af-9b1f-fb77fd71e1bd" />

<img width="978" height="677" alt="image" src="https://github.com/user-attachments/assets/9bc5d845-e7ca-4320-8891-12dca43aa4cd" />



---



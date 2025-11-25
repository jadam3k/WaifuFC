# Flight Controller Project

This repository contains the final design of a **flight controller**, including the BOM, schematic, PCB layout, and 3D model preview.  
This design uses a **4-layer PCB** for stable power distribution and signal integrity.  
---

## Bill of Materials (BOM)

Below is the list of essential components used in the flight controller. These are the components required for proper operation:

| # | Component | Description | Quantity |
|---|-----------|-------------|---------|
| U1 | STM32F103C8T6 | Main microcontroller, handles flight logic and communication | 1 |
| U2 | MPU-6050 | IMU sensor for orientation and acceleration | 1 |
| U3 | MP1584 | Voltage regulator for stable supply voltage | 1 |
| C1–C5, C9, C10, C14 | 100nF capacitors | Decoupling capacitors for IC power stability | 8 |
| Y1 | 8MHz crystal | Clock for the microcontroller | 1 |
| J1 | SBUS connector | Receiver input | 1 |
| J2 | USB-C connector | Programming and telemetry interface | 1 |

> The BOM above is based on the `bom.csv` file in the repository.  

---

## Schematic


<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/9325a1ec-2ce2-4775-a86c-718ce7f457de" />


---

## PCB Layout and 3D Preview


<img width="432" height="421" alt="image" src="https://github.com/user-attachments/assets/2fe1d3b3-6c85-42af-9b1f-fb77fd71e1bd" />

<img width="978" height="677" alt="image" src="https://github.com/user-attachments/assets/9bc5d845-e7ca-4320-8891-12dca43aa4cd" />



---



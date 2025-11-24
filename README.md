# Flight Controller Project

This repository contains the final design of a **flight controller**, including the BOM, schematic, PCB layout, and 3D model preview.  

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

![PCB Schematic](path/to/your/schematic.png)  
*Insert your schematic image here.*

---

## PCB Layout and 3D Preview

![PCB Layout](path/to/your/pcb_layout.png)  
*Insert top/bottom layer PCB images here.*

![3D Model](path/to/your/3d_model.png)  
*Insert 3D model preview here.*

---

## Notes

- This design uses a **4-layer PCB** for stable power distribution and signal integrity.  
- All components listed in the BOM are **essential for the flight controller to operate**.  
- Optional components (LEDs, switches, mounting holes) are not included in this minimal BOM.  

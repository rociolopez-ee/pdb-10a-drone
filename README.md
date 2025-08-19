# 🔋 Drone Power Distribution Board

A 2-layer power distribution PCB designed for lightweight drones. Capable of distributing up to **10A of current**, this board is optimized for compact layouts and robust power handling.

## 📐 Board Specifications

- **Layers**: 2  
- **Board Size**: 2.0924 x 3.4843 in (5.31 x 8.85 cm)  
- **Max Current**: 10A  
- **Application**: Power regulation and distribution for quadcopters or fixed-wing drones  
- **Copper Weight**: 2 oz  
- **Input Voltage Range**: 7V–25V (3S–6S LiPo)

## 🛠️ Features

- Input via XT60 or direct-solder pads
- Multiple output rails (ESCs, accessories, BEC)
- Wide ground and V+ copper pours for high current
- Mounting holes for vibration-isolated installation
- Compatible with common LiPo packs and drone frames

## 📁 Repository Contents

- `/schematics/` – Schematic files (.kicad_sch)
- `/pcb_layout/` – PCB layout files (.kicad_pcb) + Gerbers
- `/BOM/` – Bill of Materials (CSV or Excel)
- `/images/` – Board renderings and layout previews

## 🖼️ Preview

![Top Layer Render](images/top-render.png)  
*Top view of the 2-layer power board*

## 👩‍💻 Designed by

[Rocio Lopez](https://github.com/rociolopez)

---

> 🛑 Disclaimer: This board has been tested with 10A continuous current. Please verify all design tolerances if adapting for higher current applications.

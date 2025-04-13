# PCB for Drone Development ✈️🛠️

This project focuses on the design and fabrication of a custom drone PCB that doubles as a structural component (motor mount). It aims to simplify wiring, save space, and make drone assembly cleaner and more modular.

---

## 📌 Overview

This PCB was designed with precise mechanical and electrical constraints:

- Modeled in **Fusion 360** to ensure the PCB fits within drone dimensions
- Includes connectors for sensors and motors
- Acts as a mounting plate for motors
- Designed in **Altium Designer** and validated using **PCBWay**

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Fusion 360 | 3D modeling for physical dimensions |
| Altium Designer | PCB schematic and layout |
| PCBWay | Gerber validation & manufacturing |
| LTspice | Optional electrical simulations |

---

## 🔧 Design Flow

1. **Mechanical Modeling**  
   A basic drone frame and PCB mount were designed in Fusion 360 to define size and hole placements.

2. **Schematic Creation**  
   Header pins were added for ESCs, motors, power distribution, and sensor integration.

3. **PCB Layout & 3D Alignment**  
   Components were arranged to match the frame design. Mount holes and trace routing were optimized.

4. **Gerber Export**  
   The final layout was exported as Gerber files and uploaded to **PCBWay** for manufacturing checks.

---

## 📂 Project Structure

Custom-PCB-Drone/

├── Fusion_360_Model/

│   └── drone_base.f3d

├── Altium_Design_Files/

│   ├── Schematic/

│   ├── PCB_Layout/

│   └── BOM/

├── Gerbers/

│   └── PCBway_Validated/

├── Images/

│   ├── 3D_Rendered_PCB.png

│   └── Real_PCB_Photo.jpg

└── README.md

---

## 📐 Design Highlights

- 4 motor connectors placed symmetrically on arms
- Central power distribution section
- Sensor headers arranged for modular placement
- Mounting holes aligned with frame structure

---

## 📸 Screenshots

![3D model using Fusion 360](/Image/fusion.png)
![Schematics](/Image/circ.png)
![3D model of PCB](/Image/pcb3d.png)
![2D model of PCB](/Image/pcb2d.png)



---

## 🔍 Future Scope

- Add ESC circuits directly on-board
- Include onboard IMU/barometer sensors
- Support for 4-layer design with better power integrity

---

## 📬 Contact

**Sharan Karthick**  
📧 official.sharankarthick@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/sharan-karthick)  
🔗 [GitHub](https://github.com/Sharankarthick)

---

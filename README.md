## KiCad Mini Projects

**KiCad Mini Projects** is a growing collection of hardware PCB designs built entirely in KiCad. Each project is **fully completed through all stages of the PCB design cycle** — including schematic capture, PCB layout, 3D rendering, and BOM generation.

> **Please Note:** These designs are **not physically fabricated**, but they are fully compliant with JLCPCB manufacturing constraints and are ready to be manufactured.

---

### Goals

- **Build professional PCB designs in KiCad**
- **Practice embedded and analog layout skills**
- **Demonstrate ability to complete full design cycles**
- **Showcase experience for hardware/embedded engineering positions**

---

### Structure

Each project includes:
- `KiCad_files/` **Schematic (.kicad_sch)** and **Layout (.kicad_pcb)**
- `BOM/` **Bill of Materials (JLCPCB Ready) and/or Amazon Links**
- `exports/` **3D Render** and **PNG Files**
- `libraries/` **KiCad symbol/footprint libraries for any external components**
- `datasheets/` **Datasheets for key project components**
- `DESC.md` **Explaining design overview and results**

---

### Projects

| Project | Description | MCU / Chipset |
|---------|-------------|----------------|
| [USB to Serial Converter](./USB_to_Serial_Converter) | USB-C to 3.3V UART bridge with CH340C + ESP32 headers | CH340C + ESP32 |
| [ESP32 AI Camera](./ESP32_AI_CAM) | Modular ESP32-CAM board with SSD1306 OLED, servo headers, and boot support | ESP32-CAM |

*More projects coming soon*

---

### Skills Learned

- **Schematic Capture and Circuit Design**  
  Developed the ability to translate functional requirements into accurate schematics, including power regulation, signal conditioning, GPIO expansion, and sensor/peripheral interfacing.

- **PCB Layout and Routing (2-Layer Boards)**  
  Gained hands-on experience in component placement, DRC-compliant routing, via management, and trace width calculations for power and signal paths — with attention to EMI, clearance, and manufacturability.

- **Power Delivery and Grounding Strategy**  
  Implemented clean power distribution and ground practices using voltage regulators, decoupling capacitors, via stitching, and star grounding — supporting both 3.3V and 5V domains.

- **Connector and Peripheral Integration**  
  Integrated modules like ESP32, USB-C, OLED displays, servo headers, and custom footprints while accounting for mechanical constraints and pinout accuracy.

- **BOM Management and Design Documentation**  
  Created organized project folders with schematics, layout files, 3D renders, and visuals. Included part sourcing (BOM & Amazon links), custom footprints/symbols, and detailed READMEs.

- **Open Hardware & GitHub Workflow**  
  Practiced modular project documentation and GitHub repo structure with clear commits, license files, and image previews — aligned with open-source hardware sharing standards.

---

### License

All designs in this repository are released under the [MIT License](./LICENSE). You are free to use, modify, and share them.

---

> This repository is a live portfolio of my PCB Design learning progress

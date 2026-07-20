# Low-Latency Stadium Audio System

A custom ESP32-based wireless audio receiver project exploring live stadium commentary streaming over a local wireless network.

This project currently focuses on **system architecture**, **software prototype validation**, and **custom PCB design** for the receiver hardware.

---

# Project Overview

The objective of this project is to explore a compact wireless audio receiver that can receive live commentary inside a sports stadium.

Instead of beginning directly with hardware development, the communication concept was first validated using VLC Media Player over a local Wi-Fi network. After validating the streaming concept, a custom ESP32 receiver PCB was designed using KiCad.

The project currently includes:

- System architecture
- Software prototype validation
- Complete schematic
- Custom PCB design
- Gerber generation

Hardware fabrication and testing are planned as the next phase.

---

# Problem Statement

In large sports stadiums, spectators often struggle to hear live commentary clearly because of crowd noise and the lack of synchronized personal audio systems.

This project explores how a compact wireless receiver could be used to deliver commentary to individual users over a local wireless network.

---

# Proposed Workflow

Research
↓

System Architecture
↓

VLC Prototype Validation
↓

Component Selection
↓

Schematic Design
↓

PCB Design
↓

Gerber Generation
↓

PCB Fabrication *(Planned)*
↓

Hardware Assembly *(Planned)*
↓

Firmware *(Planned)*
↓

Testing *(Planned)*

---

# System Architecture

<p align="center">
<img src="stadium.drawio.png" width="900">
</p>

The receiver architecture consists of:

Commentary Source

↓

VLC Streaming Server

↓

Local Wi-Fi Network

↓

ESP32 Receiver PCB

↓

DAC

↓

Audio Amplifier

↓

Speaker / Earphone

---

# Prototype Validation (VLC)

Before designing the PCB, the communication concept was validated using VLC Media Player.

## Prototype Setup

| Item | Description |
|------|-------------|
| Audio Source | MacBook |
| Streaming Software | VLC Media Player |
| Receiver | Smartphone |
| Network | Local Wi-Fi / Mobile Hotspot |

### Streaming protocols explored

- HTTP
- RTP
- UDP

### Objective

- Verify wireless audio streaming
- Understand streaming behaviour
- Validate project feasibility before hardware design

The VLC prototype successfully demonstrated wireless audio streaming over a local network and helped validate the system architecture before PCB development.

---

# PCB Design

After validating the communication concept, a custom receiver PCB was designed using KiCad.

The PCB currently includes:

- ESP32-WROOM module
- USB Type-C power input
- Audio DAC section
- Audio amplifier section
- Push buttons
- Status LEDs
- Power regulation
- Ground plane
- Antenna keep-out region

---

## 3D PCB View

<p align="center">
  <img src="3D_Front_View.png" width="700">
</p>


---

## PCB Top Layer

<p align="center">
  <img src="Pcb_TopLayer.png" width="700">
</p>

---

## PCB Bottom Layer

<p align="center">
  <img src="Pcb_BottomLayer.png" width="700">
</p>


---

## Complete Schematic

<p align="center">
  <img src="Schematic_Diagram.png" width="700">
</p>

---

# Hardware Components Used In The PCB Design

| Component | Purpose |
|-----------|---------|
| ESP32-WROOM-32E | Main Controller |
| PCM5102A | Digital-to-Analog Converter |
| PAM8403 | Audio Amplifier |
| AP2112K-3.3 | 3.3V Voltage Regulator |
| USB Type-C | Power Input |
| Push Buttons | User Controls |
| LEDs | Status Indication |
| Passive Components | Filtering & Power Distribution |

---

# Design Work Completed

✔ System research

✔ System architecture

✔ VLC prototype

✔ Component selection

✔ Complete schematic

✔ PCB layout

✔ Component placement

✔ PCB routing

✔ Ground plane implementation

✔ Design Rule Check (DRC)

✔ 3D PCB verification

✔ Gerber generation

---

# Current Project Status

| Stage | Status |
|--------|--------|
| Research | ✅ Completed |
| Block Diagram | ✅ Completed |
| VLC Prototype | ✅ Completed |
| Component Selection | ✅ Completed |
| Schematic Design | ✅ Completed |
| PCB Design | ✅ Completed |
| PCB Routing | ✅ Completed |
| DRC Review | ✅ Completed |
| 3D Verification | ✅ Completed |
| Gerber Files | ✅ Generated |
| PCB Fabrication | ⏳ Planned |
| Hardware Assembly | ⏳ Planned |
| Firmware Development | ⏳ Planned |
| Hardware Testing | ⏳ Planned |

---

# Software & Tools

- KiCad
- VLC Media Player
- Draw.io
- GitHub

---

# Repository Structure

```
low-latency-stadium-audio-system
│
├── README.md
│
├── images
│   ├── stadium.drawio.png
│   ├── 3D_Front_View.png
│   ├── Pcb_TopLayer.png
│   ├── Pcb_BottomLayer.png
│   └── Schematic_Diagram.png
│
├── pcb
│
├── schematic
│
├── gerber
│
└── docs
```

---

# Future Work

- Fabricate the PCB
- Assemble hardware
- Develop ESP32 firmware
- Integrate audio pipeline
- Validate complete hardware
- Measure end-to-end latency
- Design enclosure

---

# Author

**Krish Fotariya**

Electronics & Telecommunication Engineering Student

Interested in:

- PCB Design
- Embedded Systems
- ESP32 Development
- Hardware Design
- Wireless Audio Systems

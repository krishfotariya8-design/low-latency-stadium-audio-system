# Low-Latency Stadium Audio System

A custom ESP32-based wireless audio receiver project exploring live stadium commentary streaming over a local wireless network.

The project currently focuses on **system architecture**, **wireless streaming prototype validation**, and **custom PCB design** for the receiver hardware.

---

# Project Overview

The objective of this project is to explore a compact wireless audio receiver capable of delivering synchronized live stadium commentary to individual spectators over a local wireless network.

Instead of beginning directly with hardware development, the communication concept was first validated using VLC Media Player over a local Wi-Fi network. Once the streaming concept was successfully demonstrated, a custom ESP32-based receiver PCB was designed using KiCad.

The project currently includes:

- System architecture
- Prototype validation using VLC
- Hardware component selection
- Complete schematic design
- Custom PCB layout
- 3D PCB verification
- Gerber generation

Hardware fabrication, firmware development, and testing are planned for the next phase.

---

# Problem Statement

In large sports stadiums, spectators often struggle to hear live commentary due to crowd noise and the absence of synchronized personal audio systems.

This project explores the feasibility of delivering real-time commentary through a compact ESP32-based wireless receiver connected over a local wireless network.

---

# Proposed Development Workflow

Research

↓

System Architecture

↓

Prototype Validation (VLC)

↓

Hardware Component Selection

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

ESP32 Firmware Development *(Planned)*

↓

Hardware Testing *(Planned)*

---

# System Architecture

<p align="center">
<img src="images/stadium.drawio.png" width="900">
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

PCM5102A DAC

↓

PAM8403 Audio Amplifier

↓

3.5 mm Audio Jack / Earphone

---

# Prototype Validation

Before designing the receiver hardware, the communication concept was validated using VLC Media Player over a local wireless network.

## Prototype Setup

| Item | Description |
|------|-------------|
| Audio Source | MacBook |
| Streaming Software | VLC Media Player |
| Receiver | Smartphone |
| Network | Local Wi-Fi / Mobile Hotspot |

### Streaming Protocols Evaluated

- HTTP
- RTP
- UDP

### Validation Objectives

- Validate wireless audio streaming
- Evaluate streaming behaviour
- Verify project feasibility before hardware development

The VLC prototype successfully demonstrated wireless audio streaming over a local network and provided confidence to proceed with the custom hardware design.

---

# PCB Design

Following successful prototype validation, a custom ESP32-based receiver PCB was designed using KiCad.

The PCB currently includes:

- ESP32-WROOM-32E module
- USB Type-C power input
- PCM5102A DAC
- PAM8403 audio amplifier
- AP2112K-3.3 voltage regulator
- 3.5 mm audio output jack
- Push buttons
- Ground plane implementation
- Antenna keep-out region

The PCB has been completed, verified using KiCad's 3D Viewer, and manufacturing Gerber files have been generated.

---

# 3D PCB View

<p align="center">
<img src="./images/3dview%20final.png" width="750">
</p>

---

# PCB Top Layer

<p align="center">
<img src="images/top_layer_final.png" width="750">
</p>

---

# PCB Bottom Layer

<p align="center">
<img src="images/bottom%20layer%20final.png" width="750">
</p>
---

# Complete Schematic

<p align="center">
<img src="images/schematic%20final.png" width="750">
</p>
---

# Hardware Components Used

| Component | Purpose |
|-----------|---------|
| ESP32-WROOM-32E | Main Controller |
| PCM5102A | Digital-to-Analog Converter (DAC) |
| PAM8403 | Audio Amplifier |
| AP2112K-3.3 | 3.3V Voltage Regulation |
| USB Type-C Connector | Power Input |
| 3.5 mm Audio Jack | Audio Output |
| Push Buttons | User Controls |
| Passive Components | Filtering, Decoupling & Power Distribution |

---

# Design Work Completed

✅ Literature Research

✅ System Architecture

✅ VLC Streaming Prototype

✅ Hardware Component Selection

✅ Complete Schematic Design

✅ PCB Layout Design

✅ Component Placement

✅ PCB Routing

✅ Ground Plane Implementation

✅ Design Rule Check (DRC)

✅ 3D PCB Verification

✅ Gerber Generation

---

# Current Project Status

| Stage | Status |
|--------|--------|
| Literature Research | ✅ Completed |
| System Architecture | ✅ Completed |
| VLC Prototype Validation | ✅ Completed |
| Hardware Component Selection | ✅ Completed |
| Schematic Design | ✅ Completed |
| PCB Layout | ✅ Completed |
| PCB Routing | ✅ Completed |
| Design Rule Check (DRC) | ✅ Completed |
| 3D PCB Verification | ✅ Completed |
| Gerber Generation | ✅ Completed |
| PCB Fabrication | ⏳ Planned |
| Hardware Assembly | ⏳ Planned |
| ESP32 Firmware Development | ⏳ Planned |
| Hardware Testing | ⏳ Planned |

---

# Software & Tools

- KiCad 9
- VLC Media Player
- Draw.io
- Git
- GitHub

---

# Future Work

- Fabricate the custom PCB
- Assemble the receiver hardware
- Develop ESP32 firmware
- Integrate the complete audio pipeline
- Validate wireless audio reception
- Measure end-to-end latency
- Design a compact enclosure

---

# Author

**Krish Fotariya**

Electronics & Telecommunication Engineering Student

### Areas of Interest

- PCB Design
- Embedded Systems
- ESP32 Development
- Hardware Design
- Wireless Audio Systems

---

## License

This project is intended for educational and research purposes.

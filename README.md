# 🧩 Open Hardware CAD

Welcome to **Open Hardware CAD** — my personal collection of KiCad-based hardware design projects, custom footprints, and 3D-modeled PCB assemblies.

This repository documents my journey as a **Computer Engineering student learning PCB design, layout, and hardware integration** — one circuit at a time. Every folder here represents a project, experiment, or custom component I’ve designed from scratch using **KiCad 8**.

---

## 🎯 Purpose

This repo isn’t just a dump of PCB files — it’s a **living showcase of progress**.  
Here, I document:
- My approach to modular PCB design  
- How I create and verify **custom footprints** and **3D-aligned headers**  
- How each project evolves from schematic → board layout → rendered model  

The goal: to build an open and structured record of my learning in embedded systems, electronics, and computer hardware design.

---

## 🧱 Repository Structure

Each folder includes:
- A **KiCad project or footprint file** (`.kicad_mod` or `.kicad_pcb`)  
- A **3D render** (`preview.png`) showing the board or footprint  
- A short **README.md** explaining the technical details, specs, and what I learned

---

## 🧠 Featured Projects

### ⚙️ Arduino Nano Header Footprint
A custom-built dual-header footprint for socket-mounted Arduino Nano boards, created from datasheet dimensions and manually aligned to a 0.600” row spacing.  
- Includes silkscreen pin labels for D0–D13, A0–A7, VIN, +5V, GND  
- Designed for plug-in modular boards  
- Fully 3D verified in KiCad’s viewer  

---

### 🧩 TMC2209 V3 Stepper Driver Footprint
A dual 8-pin footprint for TMC2209 stepper motor driver modules, with careful separation between VM (motor voltage) and VDD (logic voltage).  
- Compatible with BigTreeTech and common driver layouts  
- Includes labeled silkscreen for EN, TX, RX, STEP, DIR, VDD, VM, and GND  
- 3D aligned for precise socket insertion  

---

## 📘 How to Use These Files

1. Clone or download the repository:  
   ```bash
   git clone https://github.com/<your-username>/open-hardware-cad.git
In KiCad:

Go to Preferences → Manage Footprint Libraries → Add Existing Library

Select the .pretty or .kicad_mod file you want to use

View in 3D: press Alt + 3 to open the 3D Viewer and verify mechanical alignment.

---

## 🌱 My Goals for This Repo
Continue adding new KiCad projects and custom parts

Improve design consistency and documentation for each project

Explore PCB fabrication and assembly workflows

Eventually combine these designs into full open-source hardware systems

---

## 👤 About Me
Pavan Kannan

🎓 Major: Computer Engineering

🎓 Minor: Mechatronics Engineering

⚙️ Interests: Embedded Systems, Open Hardware, PCB Design, Power Electronics

---

## 🪪 License
Released under the MIT License — free for personal and academic use.

If you find this repo useful or inspiring, please ⭐ it or share it with others in the hardware community.

---

“Every great design starts with a blank board — and curiosity.”
— Open Hardware CAD

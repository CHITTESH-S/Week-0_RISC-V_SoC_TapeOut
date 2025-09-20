## Week-0 - Digital VLSI SoC Design, Planning and Tools Installation

---

## 📘 Overview

This week marks the initiation of your journey into Digital VLSI System on Chip (SoC) design. The focus is on setting up the essential tools and understanding the foundational concepts that underpin the design process.

## 🎯 Objectives

Conceptual Understanding: Grasp the principles of Digital VLSI SoC design.

Toolchain Setup: Install and configure necessary EDA tools.

Version Control: Set up GitHub repositories for project management.

---

## 🧠 Conceptual Framework

Design Philosophy

The core philosophy of this program is to maintain functional equivalence across all stages of the design process:

>O0 = O1 = O2 = O3 = O4

This ensures that the design's functionality remains consistent from high-level specifications to final silicon implementation.

---

## 📊 Processor Compilation Stages

| Stage  | Description                                | Key Artifact                      |
| ------ | ------------------------------------------ | --------------------------------- |
| **O0** | High-level C application code.             | Executable C model specification. |
| **O1** | Chip behavior defined in C.                | Reference for RTL design.         |
| **O2** | RTL hardware description in Verilog.       | Synthesizable RTL code.           |
| **O3** | Integration of processor with peripherals. | Complete SoC design.              |
| **O4** | RTL2GDS Flow, DRC/LVS Checks, Tape Out, Final fabricated chip.                     | Silicon implementation.           |

## Design Flow

1. **Chip Modeling (C)**: Define chip behavior in C, serving as the blueprint.

2. **RTL Design (Verilog)**: Convert C model to RTL description, partitioning into processor and peripherals.

3. **ASIC Synthesis**: Translate RTL to gate-level netlist, integrating macros and analog IPs.

4. **Physical Design (RTL-to-GDS)**: Floorplanning, placement, routing, and generation of GDSII file.

5. **Tape-Out**: Perform DRC/LVS checks and send final GDSII to foundry.

6. **Tape-In**: Fabricate silicon wafers, cut into dies, and package into final chip.

---

## 🛠️ Toolchain Installation

System Requirements:  
- Ubuntu 20.04+ (✅ I used Ubuntu 22.04)  
- Minimum Req.: 6 GB RAM, 50 GB HDD, 4 vCPU

## Tools to Install: 

**Yosys**: RTL synthesis tool.

**Icarus Verilog**: Verilog simulation tool.

**GTKWave**: Waveform viewer.

**Ngspice**: Circuit-level SPICE simulation engine.

**Magic**: VLSI layout editor and design rule checker.

**OpenLane**: Complete RTL-to-GDSII ASIC design flow tool.

---

📂 GitHub Repository

- Week-0 Repository: https://github.com/CHITTESH-S/Week-0_RISC-V_SoC_VSD/

- Main Repository: https://github.com/CHITTESH-S/RISC-V_SoC_TapeOut_VSD/

---

✅ Summary of Installed Tools

| Tool           | Description                                 | Status       |
| -------------- | ------------------------------------------- | ------------ |
| Yosys          | RTL synthesis tool for digital circuits     | ✔️ Installed |
| Icarus Verilog | Verilog simulation and testbench execution  | ✔️ Installed |
| GTKWave        | Waveform viewer for simulation results      | ✔️ Installed |
| Ngspice        | Circuit-level SPICE simulation engine       | ✔️ Installed |
| Magic          | VLSI layout editor and design rule checker  | ✔️ Installed |
| OpenLane       | Complete RTL-to-GDSII ASIC design flow tool | ✔️ Installed |

---

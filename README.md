# 🌟 RISC-V SoC Tapeout – Week-0: Digital VLSI SoC Design, Planning and Tools Installation  

---

## 📘 Overview  

This week marks the **initiation of the journey into Digital VLSI System-on-Chip (SoC) design**.  
The primary focus is on:  

🏗️ **Setting up essential open-source EDA tools**

📚 **Understanding the foundational design flow concepts**

🔗 **Preparing a systematic environment for the tapeout journey**  

---

## 🎯 Objectives  

- 🧩 **Conceptual Understanding**: Grasp the principles of **Digital VLSI SoC design** and its end-to-end flow.  
- 🛠️ **Toolchain Setup**: Install and configure the **open-source EDA toolchain** required for RTL → GDSII.  
- 🔒 **Version Control**: Initialize and manage **GitHub repositories** for structured project documentation.  

---

## 🧠 Conceptual Framework  

### 🏛️ Design Philosophy  

The core philosophy of this program is to maintain **functional equivalence across all design stages**:  

> O0 = O1 = O2 = O3 = O4  

This ensures that **chip functionality remains consistent** from the high-level specification down to **final silicon implementation**.  

---

## 📊 Processor Compilation Stages  

| 🔢 Stage | 📖 Description                                | 📂 Key Artifact                      |
| -------- | --------------------------------------------- | ------------------------------------ |
| **O0**   | High-level C application code                 | Executable C model specification     |
| **O1**   | Chip behavior modeled in C                    | Reference model for RTL design       |
| **O2**   | RTL hardware description in Verilog           | Synthesizable RTL code               |
| **O3**   | Processor + peripherals integrated            | Complete SoC design                  |
| **O4**   | RTL2GDS flow → DRC/LVS checks → Tapeout       | Silicon-ready chip                   |

---

## 🔄 Design Flow  

1. 🖥️ **Chip Modeling (C)** → Define chip behavior in **C language** as a golden reference.  
2. 🧾 **RTL Design (Verilog)** → Convert C model to synthesizable **RTL Verilog** and partition into **processor & peripherals**.  
3. ⚙️ **ASIC Synthesis** → Translate RTL into **gate-level netlist** with Yosys, integrating standard cells, macros, and IPs.  
4. 📐 **Physical Design (RTL-to-GDS)** → Perform floorplanning, placement, clock-tree synthesis, and routing to generate **GDSII layout**.  
5. ✅ **Tape-Out** → Run **DRC/LVS checks** to ensure design correctness before sending GDSII to foundry.  
6. 🏭 **Tape-In** → Silicon wafer fabrication, die cutting, and packaging into **final chips**.  

---

## 🛠️ Toolchain Installation  

**System Requirements**  
💻 **OS**: Ubuntu 20.04+ (✅ I used Ubuntu 22.04)  

🧮 **Minimum Specs**: 6 GB RAM, 50 GB HDD, 4 vCPUs  

### 📦 Installed Tools  

⚡ **Yosys** → RTL synthesis engine for logic synthesis.  

🧑‍💻 **Icarus Verilog** → Simulator for RTL + testbenches.  

📊 **GTKWave** → Waveform viewer for simulation outputs.  

🔌 **Ngspice** → SPICE-level circuit & mixed-signal simulation.  

🖌️ **Magic** → Layout editor & Design Rule Check (DRC) / LVS.  

🚀 **OpenLane** → Complete RTL-to-GDSII ASIC design automation flow.  

---

## ✅ Summary of Installed Tools  

| 🛠️ Tool          | 📖 Description                                | 📌 Status       |
| ---------------- | --------------------------------------------- | --------------- |
| **Yosys**        | RTL synthesis for digital circuits            | ✔️ Installed    |
| **Icarus Verilog** | RTL simulation + testbench execution        | ✔️ Installed    |
| **GTKWave**      | Waveform visualization of test results        | ✔️ Installed    |
| **Ngspice**      | SPICE-based analog & mixed-signal simulation  | ✔️ Installed    |
| **Magic**        | VLSI layout editor + DRC/LVS checks           | ✔️ Installed    |
| **OpenLane**     | RTL-to-GDSII automated flow                   | ✔️ Installed    |

---

## 🌐 Achievements in Week-0  

⚡ Installed and verified all **open-source EDA tools**.  

🧪 Ran **sample RTL simulations** and verified outputs in GTKWave.  

🔁 Successfully synthesized small RTL designs with Yosys.  

📂 Organized repositories for **Week-0, Week-1, and main tapeout journey**.  

📌 Understood the **importance of version control, environment setup, and path variables**.  

---

## 🙌 Acknowledgements  

👨‍🏫 **Kunal Ghosh** – VSD SoC Program Mentor  

🧑‍🤝‍🧑 **Open-source EDA Community** – Tool contributors & maintainers  

🌍 **RISC-V & Efabless Ecosystem** – Enabling open tapeout programs  

---

## 🔗 References & Resources

💡 I sincerely thank all the organizations and their key members for making this program possible:

- 🧑‍🏫 **VLSI System Design (VSD)** – [Kunal Ghosh](https://www.linkedin.com/in/kunal-ghosh-vlsisystemdesign-com-28084836/) for mentorship and vision.
- 🤝 **Efabless** – [Michael Wishart](https://www.linkedin.com/in/mike-wishart-81480612/) & [Mohamed Kassem](https://www.linkedin.com/in/mkkassem/) for enabling collaborative open-source chip design.
- 🏭 [**Semiconductor Laboratory (SCL)**](https://www.scl.gov.in/) – for PDK & foundry support.
- 🎓 [**IIT Gandhinagar (IITGN)**](https://www.linkedin.com/school/indian-institute-of-technology-gandhinagar-iitgn-/?originalSubdomain=in) – for on-site training & project facilitation.
- 🛠️ **Synopsys** – [Sassine Ghazi](https://www.linkedin.com/in/sassine-ghazi/) for providing industry-grade EDA tools under C2S program.

---

## 🔗 Repository Links  

👉 **Week-1 Repository Link:** https://github.com/CHITTESH-S/Week-1_RISC-V_SoC_TapeOut

👉 **Main Repository Link:** https://github.com/CHITTESH-S/RISC-V_SoC_TapeOut_VSD

👨‍💻 **Contributor**: [Chittesh S](https://github.com/CHITTESH-S)  

---

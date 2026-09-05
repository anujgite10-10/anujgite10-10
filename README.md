<div align="center">
  <img src="https://raw.githubusercontent.com/anujgite10-10/rl-driven-security-verification-riscv-soc/main/physical_design/3d_soc_routing_overview.png" alt="SoC Physical Design Layout" width="100%">

  <h1 align="center">Anuj Gite</h1>

  <p align="center">
    <b><code>VLSI & RTL Design</code> | <code>Hardware Architecture</code> | <code>Edge AI</code></b>
  </p>

  <p align="center">
    <a href="mailto:anuj.gite23@spit.ac.in"><img src="https://img.shields.io/badge/Email-anuj.gite23%40spit.ac.in-00f0ff?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://linkedin.com/in/anuj-gite-3b24b8295"><img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  </p>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=00f0ff&height=60&section=header" width="100%">
</div>

### ⚡ Architecture & Profile

```systemverilog
`timescale 1ns / 1ps

module anuj_gite_profile #(
    parameter DATA_WIDTH = 32,
    parameter DOMAIN     = "VLSI_FRONTEND"
)(
    input  logic clk,
    input  logic rst_n,
    output logic [255:0] engineer_capabilities
);

    // ⚡ PROFESSIONAL SUMMARY
    // RTL Designer & FPGA Engineer with hands-on experience in custom RISC-V 
    // ISA extensions, accelerator designs, and HLS-based hardware IP development.
    
    always_ff @(posedge clk or negedge rst_n) begin
        if (!rst_n) begin
            engineer_capabilities <= '0;
        end else begin
            engineer_capabilities <= {
                SYNTHESIS, 
                TIMING_CLOSURE, 
                PHYSICAL_DESIGN, 
                EDGE_AI
            };
            
            // Demonstrated expertise
            national_hackathon_wins <= 11;
        end
    end

endmodule
```

---

### 🛠️ Technical Toolkit

**Programming Languages & HDLs**
<br>
<img src="https://img.shields.io/badge/Verilog-153D70?style=for-the-badge&logo=v&logoColor=white">
<img src="https://img.shields.io/badge/SystemVerilog-00599C?style=for-the-badge&logo=s&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/Embedded_C-FF9900?style=for-the-badge&logo=microchip&logoColor=white">

**Hardware & FPGA**
<br>
<img src="https://img.shields.io/badge/RISC--V-000000?style=for-the-badge&logo=riscv&logoColor=white">
<img src="https://img.shields.io/badge/Xilinx_Artix--7-E30014?style=for-the-badge&logo=xilinx&logoColor=white">
<img src="https://img.shields.io/badge/Zynq--7000-E30014?style=for-the-badge&logo=xilinx&logoColor=white">
<img src="https://img.shields.io/badge/PYNQ--Z2-E30014?style=for-the-badge&logo=xilinx&logoColor=white">
<img src="https://img.shields.io/badge/Intel_Cyclone--V-0068B5?style=for-the-badge&logo=intel&logoColor=white">
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
<img src="https://img.shields.io/badge/RTL_Design-4B0082?style=for-the-badge&logo=microchip&logoColor=white">
<img src="https://img.shields.io/badge/IoT_System_Dev-00979D?style=for-the-badge&logo=arduino&logoColor=white">

**EDA Tools & Software**
<br>
<img src="https://img.shields.io/badge/Xilinx_Vivado-E30014?style=for-the-badge&logo=xilinx&logoColor=white">
<img src="https://img.shields.io/badge/Vitis_HLS-E30014?style=for-the-badge&logo=xilinx&logoColor=white">
<img src="https://img.shields.io/badge/Intel_Quartus-0068B5?style=for-the-badge&logo=intel&logoColor=white">
<img src="https://img.shields.io/badge/QuestaSim-00A9E0?style=for-the-badge&logo=siemens&logoColor=white">
<img src="https://img.shields.io/badge/COMSOL-104A73?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/Ansys-FFB71B?style=for-the-badge&logo=ansys&logoColor=white">
<img src="https://img.shields.io/badge/Proteus-1A6D99?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/MATLAB-D35400?style=for-the-badge&logo=mathworks&logoColor=white">
<img src="https://img.shields.io/badge/Simulink-D35400?style=for-the-badge&logo=mathworks&logoColor=white">

**Verification**
<br>
<img src="https://img.shields.io/badge/UVM-101010?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/Constrained--Random-0052CC?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/Functional_Coverage-4CAF50?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/Testbench_Dev-607D8B?style=for-the-badge&logo=c&logoColor=white">

**AI & Machine Learning**
<br>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white">
<img src="https://img.shields.io/badge/LangGraph-121212?style=for-the-badge&logo=graphql&logoColor=white">
<img src="https://img.shields.io/badge/LangSmith-121212?style=for-the-badge&logo=c&logoColor=white">
<img src="https://img.shields.io/badge/Neural_Networks-E34F26?style=for-the-badge&logo=c&logoColor=white">

---

### 🚀 Core IP & Featured Projects

#### 🔒 [RL-Driven Security Verification RISC-V SoC](https://github.com/anujgite10-10/rl-driven-security-verification-riscv-soc)
> **RTL-to-GDSII | SkyWater 130nm | Reinforcement Learning | OpenROAD**
> 
> An end-to-end framework for designing, verifying, and physically implementing a security-hardened RISC-V SoC. Features a closed-loop AI verification engine using an RL Agent to fuzz the processor and an LLM for gap analysis. Achieved 100% functional and security coverage, complete with full timing closure, zero DRC, and LVS clean signoff on the SkyWater 130nm node.

<details>
<summary><b>View Architecture Diagram</b></summary>
<br>

```mermaid
flowchart LR
    classDef bus fill:#333,stroke:#000,stroke-width:1px,color:#fff,font-weight:bold
    
    subgraph Core Logic
        Fetch --> Decode --> Execute
        Execute <--> RegFile
        Execute --> LSU
    end
    
    LSU --> PMP
    Fetch --> PMP
    PMP -- Authorized --> AXI[AXI4-Lite Bus]:::bus
    
    AXI <--> SRAM
    AXI <--> UART
    AXI <--> GPIO
```
</details>

#### 🌱 [SkyView - FPGA-Accelerated Sensor Fusion](https://github.com/navya-sinha-dot/Google_Solution_challenge) | [Live Demo](https://google-hack-kgp5.vercel.app/)
> **Verilog | Xilinx ZC706 | ESP32 | MQTT | LoRa**
> 
> * Designed and implemented FPGA-accelerated sensor fusion and rain-prediction logic in Verilog on a Xilinx ZC706; achieved 4.2× processing throughput over an ARM Cortex-A9 software baseline at ~18k LUTs, ~25k FFs, 50 DSP48s, and 25 BRAMs on the Zynq fabric.
> * Built the surrounding IoT sensing and telemetry layer (ESP32 field nodes, LoRa uplink, MQTT dashboard) to feed live field data into the FPGA-accelerated pipeline.
> * Developed a solar-powered IoT field sensing system on ESP32, integrating 8 environmental, soil, and weather sensors over I2C and SPI; achieved sub-5-minute crop anomaly alert.

#### ⚙️ [NeurISA - Custom RISC-V ISA Extension](https://github.com/VLSI-TECH-WITH-ANOUSHKA/sakec-chipmonk-hackathon-troubleshooters)
> **Verilog | NEORV32 | ModelSim | Zynq-7000 ZC706**
> 
> * Extended the NEORV32 RISC-V soft-core processor with 12+ custom SIMD instructions for hardware-accelerated CNN and ML inference, designing the instruction encoding, decode logic, and datapath extensions in Verilog HDL.
> * Implemented and validated the full design targeting the Zynq-7000 ZC706 FPGA board in Vivado; achieved 13.3× inference speedup versus software baseline on MNIST.

#### 🩻 [Real-Time MRI Analysis - CNN Inference Pipeline](https://github.com/anujgite10-10/cnn_accelerator) | [Project Details](https://drive.google.com/file/d/1-Xm94dDitEUGF6MnpPqjKqL1Uro7rSw0/view?usp=sharing)
> **HLS | Xilinx Artix-7 | AXI4-Stream | MicroBlaze**
> 
> * Implemented a CNN inference accelerator as a complete System-on-Chip (SoC) on the Xilinx Artix-7 (xc7a50tcpg236-1) FPGA for real-time MRI data interpretation.
> * Designed a custom HLS-generated 3×3 convolution and ReLU hardware engine, integrated with a MicroBlaze soft processor using AXI4-Stream interfaces and an AXI DMA engine for high-throughput, zero-copy data streaming.

#### 🔋 GridGuard - Smart Energy Management Device
> **ESP32 | AT90E26 | Raspberry Pi | C**
> 
> * Prototyped an IoT energy monitoring device integrating AT90E26 metering IC, ESP32, and Raspberry Pi; improved solar self-consumption efficiency by 18% through real-time load scheduling firmware.

#### 🧠 Real-Time Robotic Hand Mirroring Using Bionic Retina and SNNs (Ongoing) | [Project Details](https://drive.google.com/file/d/1K6O8k_4XHty6On3K_Cmbxp8NMWCZv5Lx/view?usp=sharing)
> **PYNQ-Z2 FPGA | SystemVerilog | Xilinx Vivado**
> 
> * Designing a custom SoC-based neuromorphic vision pipeline on the PYNQ-Z2 FPGA, integrating a spike-encoding retina model, a cortical spiking neural network for gesture classification, and a spike-to-PWM actuation interface as custom IP blocks connected via AXI to the Zynq processing system.
> * Verified the full RTL pipeline (frame ingestion through spike-to-PWM output) using a SystemVerilog testbench in Xilinx Vivado simulation (xsim).

---

### 💼 Professional Experience

```text
 __________________________________________________________________
| COMPANY                    | ROLE                       | TENURE |
|============================|============================|========|
| Smowcode                   | System Integration Intern  | 3 mos  |
|  > Developed embedded C drivers for hardware peripherals (SPI)   |
|  > Handled system-level validation of embedded platforms         |
|----------------------------|----------------------------|--------|
| Go-Green Technologies      | Research Intern            | 3 mos  |
|  > Developed embedded firmware for ESP32 microcontrollers        |
|  > Validated custom PCBs and supported board bring-up            |
|____________________________|____________________________|________|
```

---

### 🏆 Achievements & Hackathon Wins

| Rank | Competition | Domain |
| :---: | :--- | :--- |
| 🥈 **2nd** | **Google Solution Challenge 2026** (Google, India) | Global |
| 🥈 **2nd** | **AMD Slingshot 2026 Regional Round** (AMD, India) | Hardware/FPGA |
| 🥇 **1st** | **Agnels Tech Mania 2026 Hackathon** | Hardware |
| 🥈 **2nd** | **BugBuster 2.0 National Hardware Hackathon 2025** (520+ teams) | Hardware Verification |
| 🥇 **1st** | **Synergy Hackathon (Elexathon), Crescendo 2025** | Electronics |
| 🥇 **1st** | **GIT Hackathon** | IoT Domain |
| 🥇 **1st** | **National Case Study Competitions** (IIT Madras & IIM Lucknow) | Strategy |
| 🥈 **2nd** | **Intellify 3.0 Hackathon, Marwadi University** (120+ teams) | General |
| 🥈 **2nd** | **Agritech 2026 Hackathon**, KJ Somaiya School of Engineering | AgriTech |
| 🏅 **Top 100** | **DIR-V Grand Challenge 2025** (1392 teams) | RISC-V SoC |
| 🎖️ **Best Sim** | **BugBuster 3.0** | Simulation |

---

### 🎓 Education

**Bachelor of Technology -- Electronics and Telecommunications Engineering**
*Sardar Patel Institute of Technology (S.P.I.T.), Mumbai* (2023 -- 2027)
* **Honors:** Research | **Minor:** Management (SPJIMR)
* **Relevant Coursework:** Computer Architecture, Mixed-Signal Integrated Circuits, Embedded Systems, Verilog, Digital VLSI, ASIC Verification.

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00f0ff&height=60&section=footer" width="100%">
</div>

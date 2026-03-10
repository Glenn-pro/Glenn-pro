# Hi, I'm Shan-Cheng Yang (Glenn) 
**Firmware Engineer | Communication Algorithms | Embedded Systems**

[![NCU](https://img.shields.io/badge/M.S.-National_Central_University-blue?style=flat-square)](#)
[![Experience](https://img.shields.io/badge/Experience-2_Years_FAE-success?style=flat-square)](#)
[![Focus](https://img.shields.io/badge/Focus-Baseband_Firmware_%7C_IoT-orange?style=flat-square)](#)

I am currently pursuing my M.S. in Communication Engineering at **National Central University (NCU)**. Prior to my graduate studies, I spent two years as a **Field Application Engineer at Lasertec**, where I specialized in system validation, optical algorithm parameter tuning, and root-cause analysis for high-precision inspection tools. 

My engineering passion lies at the intersection of **hardware interfaces, low-level C programming, and communication algorithms**. I build robust embedded systems from bare-metal MCUs up to Linux-based edge gateways.

---

### 🛠️ Tech Stack & Architecture

- **Low-Level Programming:** `C` (Pointer Arithmetic, Bit Manipulation, Memory Management)
- **Embedded OS & Hardware:** `Linux` (Raspberry Pi), ` MCU` (Arduino)
- **Hardware Interfaces & Protocols:** `UART`, `I2C`, `SPI`, `GPIO`, `LoRa`, `MQTT`
- **Scripting & Automation:** `Python` (Hardware Automation, Sensor Data Parsing), `MATLAB`
- **Domain Knowledge:** Channel Coding (LDPC, Hamming Code), Signal Validation, System Debugging

---

### 🏆 Featured Projects

#### 📡 [1] Channel Coding Simulators: LDPC (1023,781) & Extended Hamming
* **Tech:** `C`, `GCC`, `Algorithm Implementation`
* **Details:** Built highly optimized, memory-efficient baseband channel coding simulators from scratch.
  * **LDPC:** Implemented SPA/MSA iterative decoding with Syndrome Early Stopping mechanism. Achieved zero memory leaks through strict pointer lifecycle management.
  * **Hamming:** Implemented $O(1)$ Lookup Table (LUT) decoding and flat-array bit-masking to maximize CPU cache efficiency and eliminate branch prediction penalties.

#### 🌐 [2] Distributed IoT Monitoring System (InnoServe Awards - 3rd Place)
* **Tech:** `Raspberry Pi (Linux)`, `Arduino (MCU)`, `Python`, `LoRa`, `MQTT`
* **Details:** Designed and deployed a multi-site greenhouse monitoring system with a strictly separated architecture:
  * **Edge Gateway (Host):** Configured a Raspberry Pi to handle UART payload parsing, threshold-based logic, and MQTT data aggregation.
  * **Sensor Nodes (Target):** Developed C-based firmware on MCUs to process raw sensor I/O and transmit data via LoRa. 

---

### 💼 Professional Experience 

**Field Application Engineer | Lasertec** *(Dec 2021 - Oct 2023)*
- **System Validation:** Owned high-priority optical inspection projects, increasing the new mask defect capture rate from 54% to 98% through iterative algorithm tuning.
- **Root-Cause Analysis:** Conducted step-by-step debugging for abnormal tool behaviors, reducing the false defect count from 26% to 7% and keeping the overall hardware failure rate below 4%.

---
📫 **Contact Me:** s3909673@gmail.com

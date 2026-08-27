# Dhruvesh Kamble

**Electronics & Telecommunication Engineer** · VIT Pune · CGPA 8.97  
Embedded Systems · VLSI · ARM Cortex-M · STM32 · ESP32 · Bare-Metal Programming

---

## About

ECE (2026) graduate with a primary focus on embedded firmware development — bare-metal drivers, peripheral interfacing, and real hardware validation. I work directly with registers, not just abstractions. On the VLSI side, I have hands-on experience taking RTL through a full physical implementation flow using open-source tools targeting Sky130.

Multiple IEEE publications. Internship experience in industrial hardware. Currently building out the embedded portfolio.

---

## Embedded Systems

| Repository                                                                                             | Description                                                                                                                                                                                                                                                                                                                                                                        | Stack                                                             |
| ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [PWM-Motor-Control-STM32](https://github.com/Dhruveshdk/PWM-Motor-Control-STM32)                       | Bare-metal PWM firmware for STM32 Nucleo-F411RE, developed as part of an industry-sponsored AGV motor-control study. Includes a companion MATLAB/Simulink PI controller model for closed-loop speed analysis and control strategy validation.                                                                                                                                      | Embedded C · STM32 · MATLAB/Simulink · Control Systems            |
| [UART-Commanded-DC-Motor-Controller](https://github.com/Dhruveshdk/UART-Commanded-DC-Motor-Controller) | Bare-metal STM32 firmware that accepts UART ASCII commands to control a DC motor through PWM speed regulation and GPIO-based direction control, implemented entirely through direct register access without HAL/CubeMX.                                                                                                                                                            | Embedded C · STM32 · UART · PWM · Bare-metal                      |
| [STM32-UART-Command-Line-Interface](https://github.com/Dhruveshdk/STM32-UART-Command-Line-Interface)   | Firmware-based command-line interface for the STM32F411RE that accepts typed commands from a PC serial terminal over UART and responds with actions or system data. Supports GPIO control for the onboard LED and relay, ADC value reading, and system-status reporting. The UART receive path is fully interrupt-driven using a circular ring buffer with no polling or blocking. | Embedded C · STM32 · UART · Interrupts · Ring Buffer · ADC · GPIO |
| [embedded-c-coding-bank](https://github.com/Dhruveshdk/embedded-c-coding-bank)                         | Curated C coding problems for embedded software interviews — researched and collected based on patterns that commonly appear in tests and interviews. Solving and pushing solutions one by one as I prepare.                                                                                                                                                                       | C · Embedded C                                                    |
| *More coming*                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                    |                                                                   |



---

## VLSI / Digital Design

| Repository | Description | Stack |
|---|---|---|
| [ro-puf-sky130](https://github.com/Dhruveshdk/ro-puf-sky130) | Complete RTL-to-GDS implementation of a Ring Oscillator PUF in Sky130. 256 ROs, OpenLane flow, zero DRC/LVS violations, 48.49% uniformity, 49.95% uniqueness. | Verilog · OpenLane · Sky130 · Magic · KLayout |
| [PUF](https://github.com/Dhruveshdk/PUF) | Arbiter PUF design and simulation | Verilog |

---

## Other

| Repository | Description |
|---|---|
| [Route-Planner](https://github.com/Dhruveshdk/Route-Planner) | Dijkstra-based shortest delivery route planner with MySQL-generated reports |

---

## Skills

**Embedded Platforms**  
STM32 (ARM Cortex-M4) · ESP32 · Arduino UNO · PIC18F — bare-metal and HAL

**Peripherals & Protocols**  
GPIO · PWM · ADC · Timers · Interrupts · UART · SPI · I²C · CAN (conceptual)

**VLSI & Digital Design**  
Verilog · OpenLane · Yosys · Magic · KLayout · Sky130 PDK · Static Timing Analysis

**Languages**  
Embedded C · Python

**Tools & IDEs**  
STM32CubeIDE · Keil µVision · MPLAB X · Proteus · EasyEDA · Git

**Debug & Test**  
Oscilloscope · Multimeter · UART serial debugging

---

## Publications

- **NeuroDrive: An EEG-Based System for Virtual Driving and Robotic Car Navigation** — IEEE ACOIT 2025 [[IEEE Xplore]](https://ieeexplore.ieee.org/document/11436410)
- **SmartSight: Image Captioning-Driven Assistive Mobility System** — ICICV 2025 [[IEEE Xplore]](https://ieeexplore.ieee.org/document/11085572)
- **Design and Development of an IoT-Enabled Remote-Controlled Hovercraft for Efficient Land and Water Mobility** — ICACRS 2024 [[IEEE Xplore]](https://ieeexplore.ieee.org/abstract/document/10841674)
- **Low-Density Parity Check (LDPC) Architecture Using Verilog** — ICCTDC 2025 [[IEEE Xplore]](https://ieeexplore.ieee.org/document/11158053)
- *RO-PUF ASIC Implementation in Sky130* — under preparation

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhruvesh%20Kamble-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/dhruvesh-kamble-bb0312256)
[![GitHub](https://img.shields.io/badge/GitHub-Dhruveshdk-181717?style=flat&logo=github)](https://github.com/Dhruveshdk)
[![EWskills](https://img.shields.io/badge/EWskills-Dhruvesh%20Kamble-FF6B35?style=flat)](https://www.ewskills.com/user/DhruveshKamble)


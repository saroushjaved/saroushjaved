<div align="center">

# Soroush Javed Sulehri

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&duration=3200&pause=900&color=00F5D4&center=true&vCenter=true&width=900&lines=FPGA+architecture+%2F%2F+real-time+DSP+%2F%2F+RTL+design;Hardware-software+co-design+for+efficient+accelerators;Reconfigurable+computing+%2F%2F+embedded+systems)](https://git.io/typing-svg)

**Electrical Engineer | FPGA & RTL Design | Real-Time DSP | Hardware-Software Co-Design**

I am an electrical engineer with over three years of experience in FPGA-based DSP systems, RTL design, and hardware-software co-design. My research interests include FPGA architecture and reconfigurable computing, with a focus on arithmetic efficiency, resource utilization, and data movement in hardware accelerators.

I build FPGA accelerators, embedded firmware, and tools for hardware validation. Alongside this work, I develop full-stack applications, community projects, and experimental software.

[![Email](https://img.shields.io/badge/Email-soroushjavedsulehri%40gmail.com-00F5D4?style=for-the-badge&logo=gmail&logoColor=black)](mailto:soroushjavedsulehri@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-saroushjaved-181717?style=for-the-badge&logo=github)](https://github.com/saroushjaved)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Soroush_Javed-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/soroush-javed/)
[![IEEE](https://img.shields.io/badge/IEEE_IBCAST_2024-Publication-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://doi.org/10.1109/IBCAST61650.2024.10877257)

</div>

---

## Research & Engineering Focus

- **FPGA architecture and reconfigurable computing:** efficient arithmetic, resource-aware RTL, and accelerator architectures.
- **Real-time digital signal processing:** fixed-point FFT, FIR/IIR filtering, DDC/DUC, and adaptive decimation.
- **Data movement and SoC integration:** streaming datapaths, buffering, AXI/DMA transfers, and programmable-logic integration with embedded software.
- **Verification and hardware validation:** self-checking testbenches, reference models, automated board testing, and laboratory validation.
- **Heterogeneous acceleration:** genome pre-alignment filtering across CPU, FPGA, and cloud platforms.

<div align="center">

![FPGA](https://img.shields.io/badge/FPGA-00F5D4?style=flat-square&logo=xilinx&logoColor=black)
![SystemVerilog](https://img.shields.io/badge/Verilog_/_SystemVerilog-111827?style=flat-square)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=flat-square&logo=python&logoColor=1f2937)
![DSP](https://img.shields.io/badge/Real--Time_DSP-00629B?style=flat-square)
![Embedded](https://img.shields.io/badge/Embedded_Systems-FF006E?style=flat-square)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Cloud](https://img.shields.io/badge/Cloud_Deployment-3A86FF?style=flat-square)

</div>

---

## Professional Experience

### Embedded Systems Developer · Angular Spring
**August 2026 - Present**

- Developing an automated PCBA testing framework for Zynq-7000 systems, covering power-rail monitoring, ADC verification, environmental sensors, and SoC diagnostics.
- Implemented memory verification routines for QSPI/SPI Flash, eMMC, SD, and DDR, with read/write testing, error detection, and CLI-based result logging.

### Assistant Manager - Embedded Systems Engineer · Resolve Pvt Ltd
**September 2023 - August 2026**

- Developed and validated two FPGA-based real-time DSP systems on Xilinx Zynq-7000 and Zynq UltraScale+ MPSoC platforms.
- Designed streaming and buffering architectures connecting ADC/DAC interfaces, FPGA logic, DMA, and processor memory.
- Implemented and verified Verilog DSP pipelines for DDC/DUC, FIR/IIR filtering, buffering, and FFT-based spectral analysis, with attention to resource utilization and timing.
- Developed bare-metal C/C++ firmware for FPGA peripheral control, AXI/DMA transfers, and hardware-software interface debugging.
- Modeled RF and DSP algorithms in MATLAB, then performed fixed-point implementation and quantization analysis.
- Conducted laboratory and field validation of baseband DSP systems, evaluating spectral performance, signal quality, and subsystem operation.

---

## Selected Research & FPGA Projects

### [BAAD: Bandwidth-Aware Adaptive Decimation System](https://github.com/saroushjaved/BAAD)
**2026 - Present | Verilog · Zynq UltraScale+ ZCU102 · Embedded C · Qt/C++ · MATLAB**

- Designed an adaptive DSP system integrating a 129-tap DDC FIR filter, FFT-based bandwidth estimator, and three-stage CIC decimator.
- Implemented adaptive control selecting decimation factors of 1, 2, 4, 8, or 16 using bandwidth estimates, hysteresis, guard-band constraints, and fail-safe operation.
- Developed embedded firmware, a Qt/C++ control and telemetry application, and MATLAB tools for configuration, signal capture, and performance evaluation; performed RTL verification and FPGA implementation analysis.

### [NEXHUS-FFT: Fixed-Point Radix-2 FFT Accelerator](https://github.com/saroushjaved/nexhus-fft)
**2026 - Present | SystemVerilog · Fixed-Point DSP · AXI · C++**

- Designed a 1,024-point radix-2 DIT FFT accelerator with 16-bit Q1.15 arithmetic, complex butterfly operations, rounding, scaling, and saturation.
- Built a modular architecture with pipelined butterfly units, BRAM-based in-place computation, twiddle-factor ROM, AXI4-Lite control, and AXI4 memory interfaces.
- Developed a C++ fixed-point reference model and self-checking SystemVerilog testbenches, achieving bit-exact agreement across all 1,024 bins for impulse, sinusoidal, and mixed-signal test vectors.
- Related work: [nexhus](https://github.com/saroushjaved/nexhus).

### [Heterogeneous Acceleration of Sneaky Snake Genome Pre-Alignment Filtering](https://github.com/saroushjaved/sneaky-snake-algo)
**2022 - 2023 | Verilog · C++/OpenMP · Virtex-7 VC707 · Microsoft Azure**

- Implemented and benchmarked genome pre-alignment filtering across multicore CPUs, FPGA hardware, and cloud infrastructure.
- Designed a modular accelerator decomposing 100-base-pair sequence processing into 13 eight-bit subproblems using shifted Hamming-distance logic, hierarchical leading-zero counters, and comparator networks.
- Synthesized, simulated, and validated the FPGA implementation in Vivado, using 3,686 LUTs and 1,931 flip-flops for a 100-bp, edit-distance-5 configuration while meeting timing constraints.
- Additional implementation: [Sneaky_Snake_Cloud_Implementation](https://github.com/saroushjaved/Sneaky_Snake_Cloud_Implementation).

---

## Publication

M. Adnan, S. J. Sulehri, M. A. Akhtar, and M. Aqil, **“Accelerating Genome Sequence Analysis via Pre-Alignment Filtering: A Review of Sneaky Snake Algorithm,”** in *2024 21st International Bhurban Conference on Applied Sciences and Technology (IBCAST)*, IEEE, 2024, pp. 209-215.

Presented at **IBCAST 2024**. The work examines implementation and performance trade-offs for Sneaky Snake genome pre-alignment filtering across CPU, FPGA, and cloud environments.

DOI: [10.1109/IBCAST61650.2024.10877257](https://doi.org/10.1109/IBCAST61650.2024.10877257)

---

## Education

**BSc Electrical Engineering (Electronics)**<br>
Pakistan Institute of Engineering and Applied Sciences (PIEAS) · **September 2019 - June 2023**

- **CGPA: 3.62/4.00**
- **GPA: 4.00/4.00** in semesters 7 and 8.

---

## Technical Skills

| Area | Skills & Tools |
| --- | --- |
| FPGA & RTL | Verilog/SystemVerilog, parameterized RTL, datapath and control logic, synthesis, timing analysis, Vivado Block Design, DSP slices, BRAM |
| Digital Signal Processing | Fixed-point arithmetic, FFT, FIR/IIR filters, DDC/DUC, quantization analysis, real-time pipelines |
| SoC & Embedded | Zynq-7000, Zynq UltraScale+ MPSoC, Virtex-7/VC707, Kintex-7, STM32, bare-metal C/C++, FreeRTOS, AXI, DMA, SPI/QSPI, UART, Ethernet |
| Verification & Validation | RTL simulation, testbench development, FPGA debugging, automated hardware testing, ADC verification, DDR/Flash validation |
| Languages & Applications | C/C++, Python, MATLAB, JavaScript, Embedded C/C++, Qt/C++ |
| Toolchains & Profiling | Vivado, Vitis/SDK, Intel Quartus, Icarus Verilog, ModelSim, Intel VTune, MATLAB Profiler, custom performance analysis |
| Web & Databases | Django, PostgreSQL, SQLite, WordPress, Bootstrap |
| Development & Deployment | Git/GitHub, Linux/Ubuntu, Nginx, DigitalOcean, Microsoft Azure, Google Cloud Platform |

---

## More Things I Build

| Project | Focus |
| --- | --- |
| [FPGA_Projects](https://github.com/saroushjaved/FPGA_Projects) | FPGA experiments, reusable learning artifacts, and a hardware portfolio hub. |
| [ella](https://github.com/saroushjaved/ella) | Application engineering, user experience, and systems thinking. |
| [theanimeradio](https://github.com/saroushjaved/theanimeradio) | A Django community project for anime recommendations, lists, and polls. |

---

## Academic Engagement & Leadership

- **Indigenous & Secure Digital System Design School, Namal University (2025):** participant.
- **IBCAST 2024, Murree:** research presenter.
- **Recent Advances in Electrical Engineering & Computer Sciences, PIEAS (2022):** participant.
- **Chairperson, IEEE Student Branch PIEAS (2022-2023):** led a 50+ member student team and coordinated technical and community initiatives.
- **Microsoft Learn Student Ambassador, PIEAS (2020-2023):** organized workshops and supported the student learning community; Beta ambassador during 2021-2023.
- **Certifications:** Data Science in Python, Data Visualization in Python, and Python Programming.

---

## GitHub Activity

<div align="center">

![Soroush's GitHub stats](https://github-readme-stats.vercel.app/api?username=saroushjaved&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=saroushjaved&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Get in Touch

I welcome research and engineering collaborations in **FPGA architecture, reconfigurable computing, DSP acceleration, hardware-software co-design, embedded tooling, and genome-analysis systems**. I also enjoy building useful software and creative community projects.

- **Email:** [soroushjavedsulehri@gmail.com](mailto:soroushjavedsulehri@gmail.com)
- **Additional email:** [soroushjaved@gmail.com](mailto:soroushjaved@gmail.com)
- **LinkedIn:** [soroush-javed](https://www.linkedin.com/in/soroush-javed/)
- **GitHub:** [saroushjaved](https://github.com/saroushjaved)

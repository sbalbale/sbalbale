# Hey, I'm Sean Balbale. 👋

**Rower. Researcher. Engineer.**  
ECE + CS @ Trinity College (Class of 2027) · seanbalbale.com

---

I got into engineering because I wanted to understand how things *actually* work — not just how to use them. That instinct runs through everything I build: bare-metal Assembly on an 8051, real-time C++ firmware on a Nordic nRF52840, and enterprise-scale Spring Boot services running in production at companies like Bullhorn and Sonos. The problems are different at each layer — but the methodology isn't.

That said, I don't think the most interesting engineering questions are purely technical. My published research argues that existing privacy frameworks are structurally inadequate for immersive XR environments that extract behavioral biometrics without active consent — and proposes a "Bodyright" framework to address it. Hardware constraint and legal philosophy. They're not as far apart as they look.

---

## 🔧 What I'm Building

**[Edge-Compute Pacing Node](https://github.com/sbalbale)** *(Senior Capstone — Fall 2026 / Spring 2027)*  
A bare-metal fatigue-prediction device for endurance athletes. Runs a discrete-time W′ balance model (Skiba et al., 2012) as a first-order Euler update in C/C++ on FreeRTOS — targeting ≤100 ms sensor-to-LED latency with zero cloud dependency. Nordic nRF52840 + ANT+/BLE 5. The open research question: how does Euler-step sampling frequency affect W′ accuracy against the continuous-time ground truth?

**[Personal Portfolio](https://seanbalbale.com)** *(seanbalbale.com)*  
Full-stack Next.js / React / TypeScript, deployed on Vercel with CI/CD on every push. Custom backend API route for contact handling, dark/light theming, and an embedded PDF resume viewer.

**[Remote MCP Server — Obsidian Vault Integration](https://github.com/sbalbale)**  
TypeScript MCP (Model Context Protocol) server exposing a personal knowledge vault over a secure remote endpoint. Bearer token auth, deployed via Cloudflare Tunnel / Tailscale, orchestrated with Docker Compose multi-profile configuration.

---

## 🛠️ Tech Stack

**Languages**  
`Java` `Python` `C` `C++` `TypeScript` `JavaScript` `Assembly (8051 / MIPS)` `Verilog` `SQL` `MATLAB` `LaTeX`

**Backend**  
`Spring Boot 3` `Jakarta EE` `JUnit 5` `Mockito` `REST APIs` `Node.js`

**Frontend / Full-Stack**  
`React` `Next.js` `Tailwind CSS` `AngularJS`

**Cloud & DevOps**  
`AWS` `Kubernetes` `Docker` `Linux` `Git` `CI/CD` `Log4j2` `Slurm` `MPI`

**Embedded / Hardware**  
`Nordic nRF52840` `Arduino` `8051` `Intel Cyclone V FPGA` `FreeRTOS` `BLE 5` `ANT+` `SPI/I2C` `NI-DAQ` `LTspice` `Oscilloscopes` `Logic Analyzers`

**Mechanical / CAD**  
`SolidWorks` `FDM 3D Printing (Klipper)` `Laser Cutters` `Precision Metrology Calibration`

---

## 📂 Selected Projects

| Project | Stack | Description |
|---|---|---|
| **[Embedded Heart Rate Monitor](https://github.com/sbalbale)** | Assembly (8051) | Bare-metal firmware handling interrupt-driven ADC sampling and real-time BCD display — no C runtime, no OS. |
| **[Haptic Horizon](https://github.com/sbalbale)** | C++, Arduino | Wearable haptic navigation system for the visually impaired; encodes distance and direction as distinct vibration patterns via HC-SR04 + haptic motor. |
| **[Project Aletheia](https://github.com/sbalbale)** | React, TypeScript | Interactive XR privacy manifesto demonstrating concrete biometric tracking risks; implements Zero-Knowledge architectures as a technical proof-of-concept for the "Bodyright" framework. |
| **[Robotic Control via FPGA](https://github.com/sbalbale)** | Verilog | Hardware-software co-design on an Intel Cyclone V — logic modules for motor control, sensor interfacing, and real-time feedback. |
| **[HPC Cluster](https://github.com/sbalbale)** | Slurm, MPI, Linux | Assembled and configured a personal three-node cluster from Lenovo ThinkStation P340s; benchmarked parallel workloads with MPI for coursework and personal use. |
| **["Fail Early and Often" Roguelite](https://youtu.be/aftX408l35E)** | Python | Term project for CMU CS 15-112: procedural map generation, enemy AI waves, cone-of-vision mechanics, and a full inventory system. ~25 hours of solo development. |

---

## 📄 Research

**"Embodied Harms and Inferred Data: Redefining Privacy in Extended Reality"**  
*The International Journal of Law, Ethics, and Technology* — In Production (Expected Late May 2026)  

Argues that BIPA, GDPR, and existing notice-and-choice frameworks are structurally inadequate for immersive environments that passively extract behavioral biometrics — gaze patterns, locomotion data, physiological signals — without active consent. Deconstructs the "inference gap," analyzes the Apple–Meta privacy dichotomy as an anti-competitive moat, and proposes a "Bodyright" framework that reclassifies biometric data as an inalienable extension of human sovereignty rather than an extractable raw material.

🏆 **Alumni Prize in English Composition** — Trinity College Department of English, May 2026

---

## 📬 Connect

- 🌐 [seanbalbale.com](https://seanbalbale.com)
- 💼 [linkedin.com/in/seanbalbale](https://www.linkedin.com/in/seanbalbale/)
- 📧 sean.balbale@trincoll.edu

If you're working on something interesting — or just want to talk hardware, cloud infrastructure, or why the "notice-and-choice" privacy model is broken — reach out. I read everything.

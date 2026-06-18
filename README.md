# FPGA-Based Student ID Sequencer & 7-Segment Decoder

## Project Overview
This repository contains a hardware-driven design that implements a modular Finite State Machine (FSM) to process and sequence a 9-digit student ID based on digit parity constraints, outputting real-time state transitions directly to a physical display.

### The Engineering Challenge
Embedded and industrial environments often require zero-latency visual feedback for monitoring real-time system status codes or incoming sensor data. Relying on software-based display drivers can introduce unwanted timing jitter and unnecessary CPU overhead.

### The Solution
By offloading the control logic directly to hardware, this design implements a 4-bit to 7-segment decoder alongside a sequential FSM. This hardware-level execution guarantees low-latency, predictable performance—bridging digital logic processing with physical system feedback.

---

## Technical Features
* **Modular FSM Architecture:** Developed sequential logic routines in hardware to track and transition states based on even/odd digit constraints.
* **Hardware-Level Decoding:** Designed a 4-bit binary to 7-segment display (SSD) decoder module to bypass software overhead and enable high-speed visual output.
* **Hardware Verification:** Synthesized and flashed the validated logic directly onto physical hardware to verify state outputs.

---

## Tech Stack
* **Design & Synthesis:** Intel Quartus Prime
* **Hardware Target:** Altera DE10-Lite FPGA Board
* **Languages:** VHDL / Verilog
* **Simulation & Verification:** Questa Intel FPGA Edition

# Student-ID-Sequencer
Engineered a Finite State Machine (FSM) using VHDL to sequence a 9-digit student ID. The project utilizes sequential logic to transition states based on digit parity and integrates a Seven-Segment Display (SSD) for real-time visual output.

FPGA-Based 7-Segment Decoder
Problem
Embedded systems and industrial machinery often require low-latency, real-time visual feedback to monitor sensor data or system status codes. Traditional software-based display drivers can introduce timing jitter and excessive CPU overhead, which is unacceptable in time-sensitive manufacturing or safety-critical robotics environments.  

Solution
I implemented a hardware-based 4-bit to 7-segment decoder that converts binary signals directly into visual output. By utilizing direct hardware logic, this implementation ensures deterministic, high-speed performance, providing immediate feedback for incoming digital signals. This design highlights my ability to bridge the gap between "pure" signal processing and physical machine interaction, a skill vital for developing robust industrial control systems.  

Tech StackDesign/Synthesis Tool: Intel Quartus Prime  
Hardware: DE10-Lite
Languages/Methods: Verilog/VHDL  
Simulation/Verification: Questa

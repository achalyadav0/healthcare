# Healthcare
FPGA-Based Biomedical Data Acquisition Prototype

📌 Project Overview

This project is a prototype FPGA-based biomedical data acquisition system designed to demonstrate real-time, deterministic sensor interfacing using hardware description logic.

The system uses an FPGA (Verilog HDL) to acquire data from a biomedical sensor via I2C, process it in hardware, and transmit results to a PC using UART.
The project emphasizes hardware parallelism, timing determinism, and clean protocol-level design, rather than high-level software abstraction.

⚠️ This is a prototype / academic project, not a medical-grade system.

🎯 Project Goals
	•	Learn and apply FPGA-based design methodology
	•	Implement UART and I2C protocols from scratch
	•	Interface a real biomedical sensor
	•	Demonstrate deterministic timing and low-latency data flow
	•	Build a clean, well-documented hardware project

⸻

🧠 Why FPGA (Instead of Microcontroller)?
	•	True parallel execution of logic
	•	Deterministic timing (no interrupts, no OS jitter)
	•	Better scalability for multi-sensor systems
	•	Hardware-level control over protocols

⸻

🛠️ Technologies Used
	•	Hardware Description Language: Verilog HDL
	•	Target Platform: FPGA (Spartan-6 / Artix-7 equivalent)
	•	Protocols Implemented:
	•	UART (TX)
	•	I2C (Master, Read-only)
	•	Simulation: Vivado / ModelSim
	•	Version Control: Git & GitHub
  
🚧 Current Project Status
	•	Project structure initialized
	•	GitHub collaboration setup
	•	Verilog fundamentals
	•	Clock divider module
	•	UART transmitter
	•	I2C master
	•	Sensor integration
	•	Threshold alert logic
	•	System integration & testing PC
  ⸻
  
🗺️ Development Roadmap 
	1.	Verilog & FPGA fundamentals
	2.	Clock divider + simulation
	3.	UART transmitter (debug backbone)
	4.	I2C master (single sensor)
	5.	Biomedical sensor interfacing
	6.	Hardware threshold logic
	7.	System integration
	8.	Documentation & demo
  ⸻
  
🧪 Verification Strategy
	•	Simulation-first approach
	•	Each module verified independently using testbenches
	•	Waveform inspection before hardware deployment
	•	Hardware testing only after simulation passes

  
📌 Notes
	•	No Vivado project files or bitstreams are tracked in GitHub
	•	All designs are written from scratch for learning and clarity
	•	Scope is intentionally limited to ensure completion and correctness

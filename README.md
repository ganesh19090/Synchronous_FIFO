# Synchronous FIFO (Verilog)

## 📌 Overview
This project implements a **Synchronous FIFO (First In First Out)** memory buffer in Verilog.  
The design supports configurable depth and width, and includes status signals for **full**, **empty**, **overflow**, **underflow** and **concurrent** conditions.  

A testbench is provided to verify the functionality using simulation.

---

## 🛠️ Features
- Parameterized data width and depth
- Write and Read operations synchronized to clock
- Status flags:
  - **Full**
  - **Empty**
  - **Overflow**
  - **Underflow**
  - **Concurrent**
- Verified with a testbench and ModelSim simulation

---

## 📂 Project Structure
Synchronous_FIFO/
── src/
   └── syn_fifo.v          # FIFO RTL
── tb/
  └── tb.v                # Testbench
├── sim/
  └── run.do              # Simulation script (ModelSim/Questa)
├── README.md               # Project description
└── waveform.png            # (Optional) Add a screenshot of simulation results

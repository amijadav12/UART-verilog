# UART Design in Verilog (FPGA Implementation)

## 📌 Overview
This project implements a Universal Asynchronous Receiver Transmitter (UART) protocol using Verilog HDL. 
The design includes UART Transmitter (TX), UART Receiver (RX), and a Baud Rate Generator.

The UART operates at 9600 baud rate with 8 data bits, no parity, and 1 stop bit (8N1 format).

---

## ⚙️ Features
- UART Transmitter (TX)
- UART Receiver (RX)
- Baud Rate Generator
- FSM-based Control Logic
- Synthesizable RTL Design
- FPGA Tested
- Simulation Testbench Included

---

## 🛠 Tools Used
- Verilog HDL
- Xilinx Vivado
- Target FPGA: (Write your board name here)
- Clock Frequency: 100 MHz
- Baud Rate: 9600

---

## 📂 Project Structure
- uart_tx.v
- uart_rx.v
- baudrate.v
- top_module.v
- constraints.xdc
- testbench.v

---

## 🧠 Learning Outcomes
- Hierarchical RTL Design
- FSM Design
- Serial Communication Protocol
- FPGA Implementation Flow
- Timing & Baud Rate Calculation

---

## 📸 Future Improvements
- Configurable Baud Rate
- Parity Bit Support
- FIFO Buffer Integration

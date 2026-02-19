UART Design in Verilog (FPGA Implementation)
📌 Overview

This project implements a Universal Asynchronous Receiver Transmitter (UART) in Verilog HDL for FPGA deployment.
The design includes:

UART Transmitter (TX)

UART Receiver (RX)

Baud Rate Generator

The UART operates at 9600 baud, 8 data bits, No parity, 1 stop bit (8N1) format.
Designed for a 100 MHz system clock and verified on FPGA hardware.

⚙️ Key Features

9600 Baud Communication (8N1)

16× Oversampling Receiver

FSM-Based TX & RX Architecture

Clock Enable–Based Baud Generation (No Derived Clocks)

Fully Synthesizable RTL

Hardware Validated on FPGA

Simulation Testbench Included

🛠 Development Environment

HDL: Verilog

Toolchain: Xilinx Vivado

Target FPGA: Nexys 4 DDR (Artix-7) 

System Clock: 100 MHz

Baud Rate: 9600
🧠 Technical Highlights

Finite State Machine (FSM) implementation for TX and RX

16× oversampling for reliable RX sampling

Parameterized baud rate division

Asynchronous active-low reset

Metastability mitigation via RX synchronization

Modular hierarchical design

🎯 Learning Outcomes

UART Protocol Implementation

RTL Hierarchical Design

FSM Design Techniques

Baud Rate Calculation from High-Frequency Clock

FPGA Synthesis & Timing Considerations

Hardware Debugging & Validation

🚀 Future Enhancements

Configurable Baud Rate (Parameterized)

Parity Bit Support

FIFO Buffer Integration

Error Detection (Framing Error)

Interrupt-Based Ready Signal

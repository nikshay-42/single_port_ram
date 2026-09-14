<img width="1551" height="473" alt="image" src="https://github.com/user-attachments/assets/22c37bb1-0f34-45dd-b1f5-d5c49a015d20" />

<img width="1541" height="723" alt="image" src="https://github.com/user-attachments/assets/469dce77-14fb-48b3-a667-4bcd137a6a84" />
# Single-Port RAM

This project implements a **Single-Port Random Access Memory (RAM)** using Verilog HDL. The design supports storing and reading data from different memory locations using a single access port.

## Project Overview

A Single-Port RAM uses one port for both read and write operations. The memory location is selected using an address, while control signals determine whether data is written or read.

This project includes:

- Verilog RTL design of Single-Port RAM
- Read and write operations
- Address-based memory access
- Verilog testbench for verification
- Simulation and waveform analysis

## Features

- Single-port memory architecture
- Synchronous write operation
- Address-based data storage
- Data read from selected memory locations
- Testbench-based verification
- Simulation waveform available for analysis

## Working Principle

### Write Operation

When the write enable signal is active, the input data is stored in the memory location specified by the address.

```text
Clock + Write Enable + Address + Data
                ↓
             Memory


# Single-Port RAM

A simple **Single-Port RAM** design implemented using **Verilog HDL**.



## Files
- `single_port_ram.v` - RAM design
- `single_port_ram_tb.v` - Testbench
- `README.md` - Documentation

## Simulation
The design was simulated and verified using waveform analysis to confirm correct read and write operations.

## Author
**Nikshay-42**


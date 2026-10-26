# 32-bit 5-Stage Pipelined RISC-V RV32I Processor

## Project Overview
This project focuses on the design and simulation of a 32-bit RISC-V RV32I processor using Verilog HDL. The design explores a five-stage instruction pipeline and techniques to handle data hazards.

## Key Features
- 32-bit RISC-V processor architecture
- Five-stage pipeline: IF, ID, EX, MEM and WB
- Data forwarding for handling data dependencies
- Hazard detection logic
- Modular Verilog HDL design
- Simulation using Xilinx ISE tools

## Pipeline Architecture

1. **IF – Instruction Fetch:** Fetches the instruction.
2. **ID – Instruction Decode:** Decodes the instruction and reads registers.
3. **EX – Execute:** Performs ALU operations.
4. **MEM – Memory Access:** Accesses data memory when required.
5. **WB – Write Back:** Writes results to the register file.

## Technologies Used
- Verilog HDL
- Xilinx ISE
- RTL simulation and waveform analysis

## Repository Contents
- `PC_.v` – Single Cylcle RISC V Complete code
- `Pipelined_RISC_V.v` – Pipelined 5 Stage RISC V processor Complete Code
- `Risc_V.v` – Pipelined 5 Stage RISC V processor with Forward and Hazard unit Complete Code

## Project Status
RTL design and simulation work are in progress. FPGA implementation and hardware validation will be documented after completion.

## Author
Abhimanyu

## Future Improvements
- Expand instruction-level verification
- Add automated testbenches and test cases
- Validate forwarding and hazard detection scenarios
- Complete FPGA implementation and hardware testing

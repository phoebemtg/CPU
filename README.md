## Overview
This project is a custom-designed CPU capable of executing real RISC-V instructions. Implemented in Logisim Evolution, this project bridges the gap between software and hardware by providing hands-on experience with CPU architecture, digital logic design, and instruction execution.

## Features
- Fully Functional CPU: Capable of executing RISC-V instructions.
- Modular Design: Includes ALU, Control Unit, Register File, Data Path, and Memory Interface.
- Instruction Execution: Supports arithmetic, branching, memory operations, and more.
- Hands-on with Logisim & Venus: Designed using Logisim Evolution and tested with Venus.

## Technologies Used
- Logisim Evolution: For designing and simulating digital logic circuits.
- RISC-V Assembly: For testing CPU functionality.
- Venus Simulator: Used to validate instruction execution.

## Setup Instructions

1. Install Logisim Evolution: Download and install Logisim Evolution from here.
2. Clone the Repository:
3. Open the Project in Logisim:
  - Launch Logisim Evolution.
  - Open the .circ file containing the CPU design.
4. Run the Simulation:
  - Load sample RISC-V machine code into the instruction memory.
  - Step through execution using Logisim's simulation controls.

## Usage
- Load RISC-V Instructions: Write assembly code and assemble it using Venus.
- Execute Instructions: Step through the CPU execution cycle in Logisim.
- Debugging: Monitor registers, memory, and control signals in Logisim.

## Architecture Design

### CPU Components
- ALU: Handles arithmetic and logical operations.
- Control Unit: Generates control signals based on instruction opcodes.
- Register File: Stores temporary values for instruction execution.
- Data Path: Ensures smooth data flow between components.
- Memory Interface: Supports load and store operations.

### Instruction Execution Cycle
- Instruction Fetch: Retrieves the next instruction from memory.
- Instruction Decode: Decodes the instruction and generates control signals.
- Execution: Performs ALU operations or determines branch decisions.
- Memory Access: Handles load and store instructions.
- Write Back: Writes results back to the register file.

## Supported Instructions

R-Type: ADD, SUB, AND, OR, XOR, SLL, SRL, etc.

I-Type: ADDI, ANDI, ORI, LW, JALR, etc.

S-Type: SW, SH, SB (store instructions).

B-Type: BEQ, BNE, BLT, BGE (branching instructions).

U-Type: LUI, AUIPC (immediate-based instructions).

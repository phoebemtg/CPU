In Project 3: CS61CPU, I designed and built a CPU capable of executing real RISC-V instructions. This project bridges the gap between software and hardware, providing hands-on experience with CPU architecture, digital logic design, and instruction processing.

Features: 

- Fully functional CPU capable of executing RISC-V instructions

- Implementation of data path and control logic

- Support for ALU operations, branching, memory access, and more

- Hands-on experience with Logisim and Venus


Implementation Details: 

- The CPU was implemented using Logisim Evolution, following a modular approach to design each key component:

- ALU: Handles arithmetic and logical operations.

- Control Unit: Manages the execution flow based on instruction opcodes.

- Register File: Stores temporary data for processing.

- Data Path: Connects all components and ensures smooth data flow.

- Memory Interface: Enables load and store operations for data access.

Architecture Design:

- The CPU design follows a simple, single-cycle architecture:

- Instruction Fetch: Retrieves the next instruction from memory.

- Instruction Decode: Decodes the instruction and generates control signals.

- Execution: Performs ALU operations or determines branch decisions.

- Memory Access: Handles load and store instructions.

- Write Back: Writes results back to the register file.


Key features:

- Support for R-type, I-type, S-type, B-type, and U-type instructions.

- Efficient control logic for handling conditional branches.

- Optimized data path to minimize delays.




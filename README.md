# DESIGN-A-BASIC-ALU-SUPPORTING-OPERATIONS-LIKE-ADDITION-SUBTRACTION-AND-OR-AND-NOT

**COMPANY**: CODITECH IT SOLUTIONS

**NAME**:NISHTHA SHRIRANG PARANDE

**INTERN ID**: CT08FOI

**DOMAIN**: VLSI

**BATCH DURATION**: December 25th, 2024 to January 25th, 2025.

**MENTOR NAME**: NEELA SANTHOSH

**Basic ALU Design Using Verilog**

**Description**
This repository contains the design and implementation of a basic Arithmetic Logic Unit (ALU) using Verilog. The ALU supports fundamental operations such as addition, subtraction, AND, OR, and NOT. The repository also includes a testbench to verify the functionality of the ALU and a simulation report to document the results.

**Contents**
ALU.v: Verilog code for the ALU module.
ALU_tb.v: Testbench for the ALU.
simulation_report.txt: Simulation results showing the output of the ALU for different operations.

**ALU Operations**
The ALU performs the following operations based on the provided opcode:
Addition (opcode = 3'b000): Adds two 4-bit inputs.
Subtraction (opcode = 3'b001): Subtracts the second 4-bit input from the first.
AND (opcode = 3'b010): Bitwise AND operation on two 4-bit inputs.
OR (opcode = 3'b011): Bitwise OR operation on two 4-bit inputs.
NOT (opcode = 3'b100): Bitwise NOT operation on the first 4-bit input.

**Testbench**
The testbench (ALU_tb.v) provides a comprehensive set of test cases to verify the ALU's functionality. It monitors the signals and prints the results of various operations.

**Simulation Report**
The simulation report (simulation_report.txt) contains the output of the ALU for different test cases, demonstrating the correctness of the design.

**Getting Started**
To run the simulation, you can use any Verilog simulation tool such as ModelSim. Follow these steps:
Clone the repository: git clone <repository_url>
Navigate to the repository directory: cd Basic_ALU_Design
Open the simulation tool and load the testbench file: ALU_tb.v
Run the simulation and observe the results.

**Author**
Md Ahmed Mentor: Neela Santhosh

**Acknowledgments**
Thanks to Coditech IT Solutions for providing the internship opportunity.

**OUTPUT OF THID ALU **
![Image](https://github.com/user-attachments/assets/d309ec51-8edb-44b4-ad15-5ce910eadf9d)
![Image](https://github.com/user-attachments/assets/2a251b86-4914-42ce-8475-89b2d6476152)

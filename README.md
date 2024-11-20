# EXP5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot 2024-11-20 200913](https://github.com/user-attachments/assets/c333ae42-b05a-4bcc-848c-7bb57ad882be)

#### Area report:
![Screenshot 2024-11-20 200936](https://github.com/user-attachments/assets/22c5aac1-1822-4993-8e54-eb163dfa1de5)

#### Power Report:
![Screenshot 2024-11-20 200945](https://github.com/user-attachments/assets/8e02fb8c-acf8-489c-a1cc-d14958662c68)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

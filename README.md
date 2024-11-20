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
![Screenshot 2024-11-20 221311](https://github.com/user-attachments/assets/10d072a6-ea8d-4506-82ee-e4580de07f8e)


#### Area report:
![Screenshot 2024-11-20 221353](https://github.com/user-attachments/assets/da906688-86ad-4d08-ae82-7ac5ac6b6da8)

#### Power Report:
![Screenshot 2024-11-20 221340](https://github.com/user-attachments/assets/f3c5ff56-1027-4f12-ba4d-e9b7c094ed04)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

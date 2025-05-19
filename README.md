# 32Bit-ALU_Synthesis

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

![Screenshot 2025-05-19 161119](https://github.com/user-attachments/assets/a7545ea2-52ca-490b-92ed-75a172b09b1f)


#### Area report:


#### Power Report:

![Screenshot 2025-05-19 163120](https://github.com/user-attachments/assets/657b5a5c-6ec1-4923-8743-453d13394feb)


#### timing Report:
![Screenshot 2025-05-19 163030](https://github.com/user-attachments/assets/9b8fadd1-911a-4bed-864c-a5dae76b03d5)



#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.

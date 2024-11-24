# EXP6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![image](https://github.com/user-attachments/assets/42ad80af-3ef7-47b8-86e9-e897c7ec9892)with <img src="https://github.com/user-attachments/assets/42ad80af-3ef7-47b8-86e9-e897c7ec9892" width="100" height="100">
### Area report:
![image](https://github.com/user-attachments/assets/80708571-b450-4fb7-bc18-f2078a15b13c)
### Power Report:
![image](https://github.com/user-attachments/assets/d3407040-f40b-4c5d-b77b-a2e2947abf50)


### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

# Traffic_light_controller_Synthesis

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

Synthesis RTL Schematic :

![WhatsApp Image 2024-11-18 at 10 25 25_10df0394](https://github.com/user-attachments/assets/e640b52d-b0da-4cb9-8054-e34b449d0e50)

Area report:
![WhatsApp Image 2024-11-18 at 10 25 26_026055e9](https://github.com/user-attachments/assets/51fbea6d-0643-4270-88dc-d145023a5f5a)

Power Report:

![WhatsApp Image 2024-11-18 at 10 25 26_8a2cc029](https://github.com/user-attachments/assets/1f6f18f7-f0c9-4bea-a160-02907dfcd5cb)

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.

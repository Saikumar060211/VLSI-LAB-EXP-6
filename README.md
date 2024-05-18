# SCHEMATIC ENTRY AND SIMULATION OF CMOS INVERTER, CMOS NAND and CMOS NOR USING CADENCE TOOL                                                                                      

# AIM
To design and simulate the CMOS inverter and observe the DC and transient responses using cadence tool.

# APPARATUS REQUIRED:
 1.Laptop with MobaXterm
 2.Cadence tool

# PROCEDURE
# Procedure for Commands to get into Cadence
1. Right Click and open the terminal window
2. Type the following commands as follows and press enter. i) tcsh ii) source /home/install/cshrc iii)
virtuoso

# Procedure for Schematic simulation using Cadence
1. Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2. Close the 2nd window
3. Use 1st window i.e virtuoso window(CIW) for further processing. i) Create a New Library ii) Create
Schematic Cell view. iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view. v)
Analog simulation by spectre

# Procedure for Creating New Library
a) File –New – Library b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing
technology library, Click OK c) Attach the library to the technology library gpdk045.Click OK

# Create Schematic Cell view
a) Go to 1st window i.e virtuoso(CIW) b) File-New-Cell view c) Setup the new file form, Library: Select
the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic d) Type: Schematic
press OK e) Add the required components from the libraries and make the connections. f) Go to
instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens
the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin h) Make the connections by using fixed narrow wire key i)
Click Check and Save button

# Creating the Symbol for schematic Cell view
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view
window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now
Symbol generation form appears. Click Ok If No changes required c. A new window with with default
symbol is created. d. Edit the symbol if you want to give actual symbol shape else continue. i. Execute
Create-Cell view-from cell view ii. Library Name and Cell Name must be same which you have used for
schematic. Press OK iii. Check for the position of pin side.Prss OK iv. Edit for the shape by CreateShape-Choose required options to edit

# Creating the new test cell view
a) Go to CIW window, Execute File-New-Cell view b) Setup the new file form Library: Select the one
you a created. Cell: Cell name must be different from the name used in schematic cell view. Ex:
Inverter_test View: Schematic Type: Schematic press OK Analog simulation by SPECTRE. a. In test cell
view window b. Launch – ADE L(Analog Design Environment) c. Execute Setup—
Simulation/directory/Host A new window opens d. Set the simulation window to spectre and click ok e.
Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat
then press OK. f. Execute Analysis – Choose. A window opens. g. Select the type and set the
specifications and press OK h. Execute Output s—to be plotted – Select on Schematic i. Then Select the
INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse j. Execute
Simulation -- Net list and Run

# INVERTER

https://private-user-images.githubusercontent.com/160314881/331234993-e7278808-2830-4f7d-877f-1d3205fa6490.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTU4Njg1MjQsIm5iZiI6MTcxNTg2ODIyNCwicGF0aCI6Ii8xNjAzMTQ4ODEvMzMxMjM0OTkzLWU3Mjc4ODA4LTI4MzAtNGY3ZC04NzdmLTFkMzIwNWZhNjQ5MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUxNlQxNDAzNDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZTQwMzEwMzJkNzViNTMzMjRiZTBmN2EzZDM4OTJmZWE5M2ViNThjZmFjY2UxODBiZDFkYzM1N2FlYzA4YmZmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.hKb039Vct7wdNOyOo63A-39Ax_moiMC3GxqpKFZBH04

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


![WPS Photos(1)](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/c2d18432-64a1-4b50-98e0-09d75461f33e)


ANALOG SIMULATION WITH SPECTRA:

Starting the simulation environment:

1.In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso analog design environment (ADE) simulation window appears.
Choosing a simulator:

1.In the simulation window (ADE) execute setup – simulator / directory / host.

2.In the choosing simulator form, set the simulator field to specra and click ok.

3.In the simulation window (ADE) execute the setup model libraries.

To complete, move the cursor and click ok.

Choosing Analysis:

1.Click the choose- Analysis icon in the simulation window (ADE).

2.The choosing analysis form appears.

3.To Setup the transient analysis.

a.In the analysis section select tron.

b.Set the stop time as 100ns

c.Click at the moderate or enabled button and the bottom and then click apply.

4.To set for DC analysis

a.In the analysis section select DC.

b.Turn on save DC operating point.

c.Turn on the component parameters.

d.Double click the select Vpulse source or Type V0 (capital V zero).

e.Select the DC voltage in the select window parameter and click in the form start and stop voltages are 0 to 1.8.

f.Select the enable button and click apply and then click ok.

Selecting output for plotting:

1.Execute the o/p’s to be plotted  -select on sschematic in the simulation window.

2.Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with the cursor after selecting.

Running the simulation:

1.Execute the simulation Netlist and run in the simulation window to start the simulation on the icon. This will create the netlist as well as run the simulation.

2.When the simulation finishes the transient and DC plots automatically will be popped up along with netlist.



![WPS Photos(1)](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/d2b0da9d-e05e-4387-8ebd-5e599458b297)


![WPS Photos3](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/94933613-5e83-4c98-85c7-3c61a462ad73)



CMOS NAND GATE

NAND SCHmatic

![WPS Photos6](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/36c161a0-eb38-49b6-901b-6971e3616a1a)


NAND TEST CELL VIEW

![WPS Photos7](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/f46287ff-b86f-4b19-a593-9f85c4709baf)


NAND SIMULATION WITH SPECTRA


![WPS Photos8](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/45dfa853-6889-4368-b2cf-5374378a6140)







CMOS NOR GATE

NOR SCHEMATIC

![WPS Photos(9)](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/2169a189-aeb8-43e2-9c03-4cb13912a342)






NOR TEST CELL VIEW

![WPS Photos(10)](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/ab9d82cf-6b2b-47b8-af58-f46a9e71f6d3)


NOR SIMULATION WITH SPECTRA

![WPS Photos(11)](https://github.com/CalebSamraj14/VLSI-LAB-EXP-6/assets/163808923/ca0d0123-8544-4693-9377-1702e4058300)




# EE 464 PROJECT#2

## Simulation and Design of the Hardware Project

### Deadline: 31/03/2019 23:59

In this project you are going to work with your hardware project partners (2-3 people per team). If you haven't selected your projects, please fill [this spreadsheet](https://docs.google.com/spreadsheets/d/1HgNVN4wFpfH8vbBwCHcy3HoVSP6NIBR18eRuBtWIT0I/edit?usp=sharing) as soon as possible.

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project.

## Q1) Design of an Isolated Power Supply

In this step, you need to simulate the topology you had previously chosen for your hardware project. Input, output voltages and power requirements are the same for the hardware requirements.

a) Simulate the converter and show its proper steady-state operation.

b) Design a transformer (choose [core material and geometry](https://docs.google.com/spreadsheets/d/1HXe-ban1QV2iynLcxp-vsHEPFjtSYkQUeh2KFEf1brs/edit?usp=sharing), number of turns, operating flux density etc) and estimate its equivalent circuit parameters. Explain the design procedure in detail. The cores given in the link will be available for you to borrow, but you can use any commercially available core.  

c) Simulate the converter with ideal switches and transformer (including Lm of course). Calculate the main parameters of the converter and show the relevant graphs.

d) Calculate the minimum load current you can work without getting into the DCM, and calculate the min-max transformer current.

e) Simulate the transformer with parasitic components and non-ideal switches to observe the voltage-current oscillations in the switches. Although it is encouraged to choose the switch that you will use, you can make the simulations with any non-ideal switches. The idea is just to observe the voltage-current stress in the switches. Design any snubbers if required. Again, you may refer to application notes for this purpose.

f) Calculate the efficiency of your converter (including transformer and switching losses) at 100%, 75%, 50% and 25% load conditions at the rated voltage.

g) Show the converter works within the given input voltage limits and satisfies the output ripple limits.

h) Preliminary Component Selection: Choose the components that you will use in the hardware implementation (i.e. switches, diodes, capacitors etc.) and justify your selection by referring to the relevant specs from the components' data-sheet and your simulation results.
.


# EE 464 Homework #1

## Magnetic Design of the Hardware Project

### Deadline: 24/03/2024 23:59

In this project you are going to work with your hardware project partners. 

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the homework.

## Q1) Magnetic Design of an Isolated Power Supply

In this step, you need to simulate the topology you had previously chosen for your hardware project. Input, output voltages and power requirements are the same for the hardware requirements. You do not need to explain topology and semiconductor device selection in this homework.

a) Select a duty cycle range for your topology. For this selection, find the turns ratio of transformer.

b) Design a transformer and estimate its equivalent circuit parameters. Explain the design procedure in detail. The cores given in the link will be available for you to borrow, but you can use any commercially available core.

- Choose [core material and geometry](https://docs.google.com/spreadsheets/d/1EulnohgTt6JBoSweeZXwY2xUHmFE42yt89FN3Kc15gA/edit?usp=sharing). Clearly indicate the reasoning behind choosing the core.
- Find the primary and secondary number of turns. Calculate the magnetizing inductance of the transformer.
- Chose  [AWG cable](https://www.powerstream.com/Wire_Size.htm) according to switching frequency and current of each winding.
- Calculate the fill factor of the transformer with the chosen cable. Is it a reasonable value? Then, calculate the cable DC and AC resistances and copper loss of the transformer.
- Calculate the core loss of the transformer using core loss formulas given by the manufacturer and compare it with previously found copper loss value. Does your design require new iterations?

c) Simulate the converter with ideal switches and transformer (including Lm of course). Calculate the main parameters of the converter and show the relevant graphs.

d) Calculate the minimum load current you can work without getting into the DCM, and calculate the min-max transformer current. (Your hardware design may be work in DCM, this question is just for homework).

e) Simulate the transformer with parasitic components (transformer leakage inductance etc.) and non-ideal switches to observe the voltage-current oscillations in the switches. Although it is encouraged to choose the switch that you will use, you can make the simulations with any non-ideal switches. The idea is just to observe the voltage-current stress in the switches. Design any snubbers if required. You may refer to application notes for this purpose.

f) Calculate the efficiency of your converter (including transformer and semicondutor losses) at 100%, 50% and 25% load conditions for both voltage limits.




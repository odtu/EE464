# EE 464 PROJECT#2

## Draft Version

## Isolated Converters & Controller Design

### Deadline: 19/04/2018 23:59

In this project you are going to work with your hardware project partners (2-3 people per team). If you haven't selected your projects, please fill [this spreadsheet](https://docs.google.com/spreadsheets/d/1KAVsJwLUg4EU7Spf6T_P4cAQa5IwYKrkkvP4pl3IBME/edit?usp=sharing) as soon as possible.

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project.


### Q2) Full-Bridge Converter

Design a full bridge converter with the following specs:

- Input Voltage: 48 V
- Output Voltage: -15 V
- Load: Series R-L Load ( 1.2 Ω, 3mH)
- Switching frequency: 20 kHz

a) Implement the converter using bi-polar voltage switching PWM controller. Ideals switches may be assumed.Show that the converter vacancy generate both positive and negative voltages by choosing two example situations.

b) Now produce the same voltage levels as in (a) but using uni-polar voltage switching PWM strategy. 

c) For the positive voltage outputs in parts (a) and (b), take the Fourier-transform(FFT), to show it harmonic components. Compare and comment the results.

d) Now assume, your switches have finite turn-on and turn-off time, and you need to implement 2µs dead time between top and bottom switching instants. Using a uni-polar PWM switching strategy, compare the output voltage for a output reference voltage of 12 V, with and without the dead-time. Compare and comment the results.

e) You are now required to generate a sinusoidal voltage output with a peak voltage of 36V at 400 Hz. Plot the output voltage and current. You may add and additional filter in the output if required. Repeat the sinusoidal output generation with the dead-time. Compare and comment the results.

f) Also discuss the effect of the dead time by comparing the fundamental component of sinusoidal output with and without the dead time. You can also present the harmonic components of both signals by taking FFT of the voltage waveforms.


## Q1) Isolated Converter Simulation

In this step, you need to simulate the topology you had previously chosen for your hardware project. Input, output voltages and power requirements are same for the hardware requirements.

a) Simulate the converter and show its proper steady-state operation.

b) Design a transformer (choose core material and geometry, number of turns etc) and estimate its equivalent circuit parameters. You can use commercially available cores and related application note.  Explain the design procedure in detail.

c) Calculate the minimum load current you can work with without getting into the DCM?

d) Simulate the transformer with non-ideal switches to observe the voltage-current oscillations in the switches. Although it is encouraged to choose the switch that you will use, you can make the simulations with any non-ideal switches. The idea is just to observe the voltage-current stress in the switches. Design any snubbers if required. Again, you may refer to application notes for this purpose.

e) Calculate the efficiency for your converter at 100%, 75%, 50% and 25% load conditions.

f) Preliminary Component Selection: Choose the components that you will use in the hardware implementation (i.e. switches, diodes, capacitors etc.) and justify your selection by referring to the relevant specs from the components' data-sheet and your simulation results.


### Q2) Controller Design

###Bonus:
Implement this section with your actual hardware topology to get a 25pts bonus for this part!

For the specs you have chosen in the hardware project, now design a buck, buck-boost or boost converter to get the same output voltage. You can slightly modify your specs if required (for example 230 VAC, can be assumed as 200V dc etc.).

a) For the converter, obtain the controller transfer function analytically, then plot the bode-plot and its implications.

b) Obtain the same characteristics,using the computer simulation that you choose. You can find useful links in the lecture slides.

c) Design a Type-II controller that will produce enough transient stability for your converter. Determine the circuits parameters and implement a closed-loop control for constant output voltage.

d) Show the performance of the controller by:

    i- A step change from half load to full load
    ii-A 10% step reduction or increment in the supply voltage

e) Discuss the transient performance vs. accuracy and other observations you made during the design process.



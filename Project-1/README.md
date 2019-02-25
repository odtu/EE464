# EE 464 PROJECT#1

## Ćuk Converter and Full-Bridge DC/DC Converter

### Deadline: 07/03/2018 23:59


Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project.

### Q1) Ćuk Converter

Design a Ćuk converter with the following specs:

- Input Voltage: 9 V
- Output Voltage: -12 V
- Output Current: 3 A
- Switching frequency: 100 kHz
- Max. Output voltage ripple: 2%

You need to complete the following steps:

Build the converter and prove its correct operation by supplying switching waveforms for the ON and OFF operating modes. 

a) Choose a suitable (and reasonable) capacitor and inductance that can produce the output within given tolerances under steady state operation (Under CCM). Support your decision with analytical calculations. You are not required to find commercial components, but please choose realistic values (i.e. instead of using 21.45 µF use a 22 µF capacitor). You are free to suggest any commercial components as a bonus.

b) Plot waveforms of the input current of the Ćuk converter, and also plot the input current for a similar sized buck-boost converter. Comment and compare the input currents.

c) Calculate the inductor current and capacitor voltage ripples analytical and compare them with your simulations results.

d) Assume your input voltage is not constant anymore, but it has a 6th harmonic (300 Hz) in the form as:

Vin= 9 + 1.sin(2.π.300t)

So that, the input voltage varies between 8 V and 10 V. Design a controller that the output voltage is kept within the limits given above. Show the proper operation of your controller by showing the variation of the duty cycle and also the output voltage waveform.

e) Now assume the input voltage is increased from 9 V to 11 V instantenously (as a step) with the same controller that you designed in part (c). Plot the output voltage waveform and comment on the performance of the controller.

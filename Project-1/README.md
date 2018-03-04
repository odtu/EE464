# EE 464 PROJECT#1

## Ćuk Converter and Full-Bridge DC/DC Converter

### Deadline: 19/03/2018 23:59


Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project.

### Q1) Ćuk Converter

Design a Ćuk converter with the following specs:

- Input Voltage: 12 V
- Output Voltage: -15 V
- Load Power: 60 W
- Switching frequency: 150 kHz
- Max. Output voltage ripple: 1%

You need to complete the following steps:

Build the converter and prove its correct operation by supplying switching waveforms for the ON and OFF operating modes. 

a) Choose the minimum size of capacitor and inductances that can give produce steady state operation (Under CCM). You are not required to find commercial components, but please choose realistic values (i.e. instead of using 21.45 µF use a 22 µF capacitor), you are free to suggest any commercial components as a bonus.

b) Plot the waveform of the input current, and also plot the input current for a similar sized buck-boost converter. Comment on the differences.

C) Now assume your input voltage is not constant, but it has a 6th harmonic (300 Hz) in the form as:

Vin= 12 + 2.sin(2.π.300t)

So that, the input voltage varies between 10 V and 14 V. Design a controller that the output voltage is kept within the limits given above. Show the proper operation of your controller by showing the variation of the duty cycle and also the output voltage waveform.

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
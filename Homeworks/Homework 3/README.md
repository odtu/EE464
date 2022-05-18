# EE 464 Homework#3

## Single Phase Inverters

### Deadline: 29/05/2022 23:59

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project. Open a **private repository**, which you will put all your work into. Please add [Ogün](https://github.com/OgunAltun) as a collaborator.


**1)** A battery bank with 400V DC ratings is utilized to energize a single phase AC load with 50 Hz, 230 V<sub>rms</sub> requirements.  The battery will be interfaced with the load via a single phase full bridge voltage source inverter. The load is modelled by series connection of 10 Ω and 10 mH.

**a)** Find the amplitude modulation ratio (m<sub>a</sub>) for this operation.

**b)** For each case below, simulate the inverter in Simulink with bipolar PWM method. Find the frequency modulation ratio. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results.

* f<sub>s</sub>=1500 Hz
* f<sub>s</sub>=980 Hz

**c)** Now change the modulation method to unipolar PWM and simulate the inverter in Simulink for the same cases. Find the frequency modulation ratio. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results.

* f<sub>s</sub>=1500 Hz
* f<sub>s</sub>=980 Hz

**2)** Assume that nominal battery voltage is decreased to 300V and the same load is driven.

**a)** Find the amplitude modulation ratio (m<sub>a</sub>) for this operation.

**b)** Simulate this operation in Simulink. Use bipolar PWM method and f<sub>s</sub>=1500 Hz. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results with V<sub>dc</sub>=400V case.


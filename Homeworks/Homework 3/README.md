# EE 464 Homework#3

## Single Phase Inverters

### Deadline: 26/05/2023 23:59

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project. Open a **private repository**, which you will put all your work into. Please add [Ogün](https://github.com/OgunAltun) as a collaborator.


**1)** A battery bank with 600V DC ratings is utilized to energize a single phase AC load with 50 Hz, 400 V<sub>rms</sub> requirements.  The battery will be interfaced with the load via a single phase full bridge voltage source inveter. The load is modelled by series connection of 12 Ω and 25 mH.

**a)** Find the amplitude modulation ratio (m<sub>a</sub>) for this operation.

**b)** For each case below, simulate the inverter in Simulink with bipolar PWM method. Find the frequency modulation ratio. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results.

* f<sub>s</sub>=1800 Hz
* f<sub>s</sub>=780 Hz

**c)** Now change the modulation method to unipolar PWM and simulate the inverter in Simulink for the same cases. Find the frequency modulation ratio. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results.

* f<sub>s</sub>=1800 Hz
* f<sub>s</sub>=780 Hz

**2)** Assume that nominal battery voltage is decreased to 500V and the load requirements are same.

**a)** Find the amplitude modulation ratio (m<sub>a</sub>) for this operation.

**b)** Simulate this operation in Simulink. Use bipolar PWM method and f<sub>s</sub>=1800 Hz. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the harmonics you observed and compare the results with V<sub>dc</sub>=600V case.

**3)** What is the minimum battery voltage that can provide the output requirements? Simulate the inverter for this operation condition. Plot the inverter output voltage and current for 2 fundamental cycles. Also plot the FFT of the inverter output voltage and current. Comment on the results.


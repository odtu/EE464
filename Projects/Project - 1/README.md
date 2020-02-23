# EE 464 PROJECT#1

## Device Parameters

### Deadline: 08/03/2020 23:59

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project. Open a **private repository**, which you will put all your work into. Please add me(/ozank), Furkan(/furkankarakaya) or other Furkan(/tokgozfurkan) as a collaborator.

Your boss at Hebelsan requires you to design a converter which reduces 16 V DC to 12 V DC. The design options that you have for this task are Buck-Boost Converter, Ćuk Converter and SEPIC Converter. The converter should be able to supply 24 W at switching frequency of 50 kHz. Moreover, output voltage ripple should not be greater than 2%. You will be examining each of these three topologies in order to find the best converter for the application.

**1) Buck-Boost Converter Design**<br />

  **a)** Find the required duty cycle to have 12 V output voltage assuming CCM operation.

  **b)** Determine the value of inductance for converter to be in CCM operation with 10% ripple current.

  **c)** Find the output capacitance value in order to have 2% output voltage ripple.

  **d)** According to your calculations, find commercial products for inductors, capacitors and semiconductors from [Digikey](https://www.digikey.com/). Explain your reasoning for selections.

  **e)** Validate your results by constructing the designed buck-boost converter in Matlab/Simulink environment **with non-idealities,** meaning ESR values of capacitors and inductors, switching device's parameters, which you can find in the datasheets of the products and plot the following waveforms:
  * Output voltage
  * Input current
  * Inductance current

**f)** Comment on the results and explain if you observe any discrepancy from analytical calculations.


**2) Ćuk Converter Design**<br />
  **a)** Analytically prove that V<sub>out</sub>/V<sub>in</sub> transfer function of the Ćuk converter is equal to D/(1-D) in CCM.

  **b)** Find the output voltage ripple formula analytically and calculate the required output capacitor, C<sub>2</sub> , value in order to have 2% voltage ripple.

  **c)** Find the value of L<sub>1</sub>, L<sub>2</sub> inductances by assuming 10% ripple current.

  **d)** Find the value of C<sub>1</sub> capacitor by assuming 10% ripple voltage.

  **e)** According to your calculations, find commercial products for capacitors, inductors and semiconductors from [Digikey](https://www.digikey.com/). Explain your reasoning for selections.

  **f)** Construct the Ćuk converter in Simulink **with non-idealities** and check if the circuit meets the requirements. Plot the following waveforms:

  * Output voltage
  * C<sub>1</sub> voltage
  * L<sub>1</sub>, L<sub>2</sub> currents

**g)** Comment on the input current waveforms of the Ćuk converter and buck-boost converter.

**h)** Comment on the results and explain if you observe any discrepancy from analytical calculations.

![](cuk.png)

**3) SEPIC Converter Design**<br />
**a)** Analytically prove that V<sub>out</sub>/V<sub>in</sub> transfer function of the SEPIC converter is equal to D/(1-D) in CCM.

**b)** Find the output voltage ripple formula analytically and calculate the required output capacitor, C<sub>2</sub> , value in order to have 2% voltage ripple.

**c)** Find the value of L<sub>1</sub>, L<sub>2</sub> inductances by assuming 10% ripple current.

**d)** Find the value of C<sub>1</sub> capacitor by assuming 10% ripple voltage.

**e)** According to your calculations, find commercial products for inductors, capacitors and semiconductors from [Digikey](https://www.digikey.com/).

**f)** Construct the SEPIC converter in Simulink **with non-idealities** and check if the circuit meets the requirements. Plot the following waveforms:

* Output voltage
* C<sub>1</sub> voltage
* L<sub>1</sub>, L<sub>2</sub> currents

**g)** Comment on the results and explain if you observe any discrepancy from analytical calculations.

![](sepic.png)

**4) Final Decision** <br />

**a)** Create a table which shows all the circuit components that you have used in your design with their costs.

**b)** According to your analytical calculations and simulation results, list the advantages and disadvantages of each converter topology.

**c)** Which one of these three topologies would you choose considering circuit components used in the circuit? Explain why did you choose that specific topology and why did not you choose other two topologies.

**d)** What might be the case in which other two topologies are more suitable?


**5) Bonus** How much time did you spend for this homework? (Bonus)

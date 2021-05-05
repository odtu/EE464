# EE 464 Homework#2

## Full Bridge Isolating Converter Design

### Deadline: 16/05/2020 23:59

Please check [evaluation.md](evaluation.md) for other details and evaluation criteria about the project. Open a **private repository**, which you will put all your work into. Please add [Ogün](https://github.com/OgunAltun) as a collaborator.

Your boss at Hubelsan was very satisfied with your previous design. After giving you a salary bonus -there is no free lunch-, he asked you to design a 200 W full bridge isolating converter with 24 V<sub>in</sub> and 48 V<sub>out</sub> with 1% output voltage ripple at 50 kHz.

**1) Circuit parameters**<br />

  **a)** Assuming operating duty cycle is 0.4, find the turns ratio of the transformer.

  **b)** Find the required inductance value so that the filter inductor current ripple is 10% of the average inductor current.

  **c)** Find the output capacitor value to meet the output voltage ripple requirements. Do not just use the formula, show derivaton. 

  ![](fullbridge.png)

**2) Magnetic Design**<br />

The total loss of magnetic components -transformer and inductor- should not exceed 25 W and fill factor of the cores should not be less than 30%.

It is strongly advised to use programs such as Matlab or Excel, since magnetic design can be a tedious job which may require a few iterations to find the optimum parameters. A simple script would save you from losing your precious hours.

  **a)** Design your transformer with cores which can be found on [Magnetics](https://www.mag-inc.com/Products/Ferrite-Cores/Ferrite-Shapes). Clearly indicate the reasoning behind choosing the core. Find the primary and secondary number of turns. Calculate the magnetizing inductance of the transformer. (Hint: Magnetics has some great design guides for inductor and transformer designs. Please have a look at those guidelines.)

  **b)** With current density being 4 A/mm<sup>2</sup>, find an [AWG cable](https://www.powerstream.com/Wire_Size.htm) according to the switching frequency and current value. Firstly, calculate the fill factor of the transformer with the chosen cable. Is it a reasonable value? Then, calculate the cable DC and AC resistances and copper loss of the transformer (Proximity can be ignored).  

  **c)** Calculate the core loss of the transformer using core loss formulas given by the manufacturer and compare it with previously found copper loss value. Does your design require new iterations?

  **d)** Design the output inductor with cores on [Magnetics](https://www.mag-inc.com/Products/Powder-Cores/Kool-Mu-Cores). Find the required number of turns and make sure that core is not saturated by checking the DC bias curves of the material.

  **e)** Choose appropriate AWG cable for the design with 4 A/mm<sup>2</sup> current density and calculate the fill factor. Is it a reasonable value? Then, calculate the cable DC and AC resistances and copper loss of the inductor.

  **f)** Calculate the core loss of the inductor and compare it with previously found copper loss value. Does your design require new iterations?

**3) Simulation**<br />

**Important Note:** MOSFET and transformer are current based modelled in Simulink. Series connection of these components may results in unexpected simulations. You can conncect parallel output capacitance to the MOSFETs so that simulation works well.

**a)** Construct a simulation on Simulink with calculated cable resistances of the inductor and transformer. Check if the circuit meets the requirements. Plot the following waveforms. Comment on the results and explain if you observe any discrepancy from analytical calculations. Also find the required rating of the semiconductors and capacitor according to simulation. Yo do not need to select commercial products.

* V<sub>o</sub>
* V<sub>x</sub>
* V<sub>L</sub>
* i<sub>L</sub>
* V<sub>sw1</sub>

**b)** Real transformers have leakage inductances as a small portion of the magnetizing inductance. What would you observe in real case scenario with leakage inductances. Comment on it.

**c)** Suppose that duty cycles of SW1-SW2 switch group and  SW3-SW4 switch group are not idendital. What could this difference results in? Propose a method to solve this problem.

**4) Bonus** How much time did you spend for this homework?

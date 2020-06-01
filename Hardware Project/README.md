# EE464 Hardware Project

### Deadlines (To be postponed)
- Complete Simulation Report - 16th of March
- Presentation for Feedback Session - 23rd of March
- Final Report - 28th of June
- Final Presentation - 29th of June - 1st of July


Specs for the hardware project are listed below. You need to form a group of 3 students and reserve the project that you choose. You are not allowed to have a group with any of your group members from the first semester.

Once you determined your group members, please write it up in [this spreadsheet](https://docs.google.com/spreadsheets/d/1HgNVN4wFpfH8vbBwCHcy3HoVSP6NIBR18eRuBtWIT0I/edit?usp=sharing).
Also put the project number you would like to work on. Maximum two teams can pick the same project. First come first served.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Project No</th>
            <th>FLY #1</th>
            <th>FLY #2</th>
            <th>FLY #3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=7>
                FLYBACK
            </td>
            <td rowspan=1>Minimum Input Voltage (V)</td>
            <td>24</td>
            <td>24</td>
            <td>200 Vac</td>
        </tr>
        <tr>
                <td rowspan=1>Maximum Input Voltage (V)</td>
                <td>48</td>
                <td>48</td>
                <td>240 Vac</td>
        </tr>
        <tr>
                <td rowspan=1>Output Voltage (V)</td>
                <td>15</td>
                <td>10</td>
                <td>5</td>
       </tr>
       <tr>
                <td rowspan=1>Output Power (W)</td>
                <td>60</td>
                <td>60</td>
                <td>60</td>
       </tr>
       <tr>
                <td rowspan=1>Output Volt. Peak-to-Peak Ripple (%)</td>
                <td>4</td>
                <td>4</td>
                <td>5</td>
       </tr>
       <tr>
                <td rowspan=1>Line Regulation (%)</td>
                <td>2</td>
                <td>2</td>
                <td>3</td>
       </tr>
       <tr>
                <td rowspan=1>Load Regulation (%)</td>
                <td>2</td>
                <td>2</td>
                <td>3</td>
       </tr>
    </tbody>
<tbody>
    <tr>
        <th></th>
        <th>Project No</th>
        <th>FOR #1</th>
        <th>FOR #2</th>
        <th>FOR #3</th>
    </tr>
    <tr>
        <td rowspan=7> FORWARD </td>
        <td rowspan=1>Minimum Input Voltage (V)</td>
        <td>24</td>
        <td>24</td>
        <td>200 Vac</td>
    </tr>
    <tr>
            <td rowspan=1>Maximum Input Voltage (V)</td>
            <td>48</td>
            <td>48</td>
            <td>240 Vac</td>
    </tr>
    <tr>
            <td rowspan=1>Output Voltage (V)</td>
            <td>15</td>
            <td>10</td>
            <td>5</td>
   <tr>
            <td rowspan=1>Output Power (W)</td>
            <td>48</td>
            <td>48</td>
            <td>48</td>       
   </tr>
   <tr>
            <td rowspan=1>Output Volt. Peak-to-Peak Ripple (%)</td>
            <td>2</td>
            <td>2</td>
            <td>3</td>
   </tr>
   <tr>
            <td rowspan=1>Line Regulation (%)</td>
            <td>2</td>
            <td>2</td>
            <td>3</td>
   </tr>
   <tr>
            <td rowspan=1>Load Regulation (%)</td>
            <td>2</td>
            <td>2</td>
            <td>3</td>
   </tr>
   </tr>
</tbody>
</table>



Here are some important notes:

- Project specs are arranged such that there is not a significant difference in difficulty of implementation.

- Closed loop control is a must. Projects without a closed loop control will not be accepted.

- Digital controllers (Arduino, Raspberry etc.) are STRICTLY forbidden for any case.

- You may also have a power conversion scheme in your mind. (Required for work, summer practice, for your hobby project etc.) You can propose other topologies and specs outside the ones listed above. Make sure the new project you propose involves some kind of magnetic design (because all of the above have).

- Project development phase and final results must be open source. You are required to share the knowledge by properly prepared reports. All simulation files, PCB design files, bill of materials, design regarding magnetic elements should be made available as open access.

- After succeeding the voltage level conversion, you will probably want to pursue additional merits for your converter. These may include:

    * Higher efficiency
    * Compact design
    * High power density
    * Employing soft switching techniques


- All of the additional converter merits and any other effort that you put outside this project definition will be awarded in grading, accordingly.

- Line regulation is the deviation of percent output voltage when input voltage is changed from its minimum to maximum or vice versa.

- Load regulation is the deviation of percent output voltage when load current is changed from 10% to 100% or vice versa.

- Converters on stripboard are okay if it is working, but we expect you to start early and exhibit your final design on a PCB.

- TI shares a lot of its designs, in detail. Please check: http://www.ti.com/general/docs/refdesignsearchresults.tsp

- It is strongly advised to read application notes about your project topology. You can find converter designs on web and (partly) utilize their solution by properly citing them. Do not try to find an overall design to evade the design effort. We also have a large collection of converter designs published online.

- Most of the power companies (especially TI) send free samples.

- Based on your hardware experience in EE463, you should remember that it is vital to prepare your shopping list early. Contact local and international component dealers as soon as possible.

- The magnetic cores listed in [this spreadsheet](https://docs.google.com/spreadsheets/d/1HXe-ban1QV2iynLcxp-vsHEPFjtSYkQUeh2KFEf1brs/edit?usp=sharing) will be available in our laboratory. You can borrow those cores and return them at the end of the semester. Those magnetic cores are from Magnetics. For detailed information about the cores, you can visit the manufacturer website. Additionally, you can also use other magnetic cores if you wish.


### ~~Option-A: Hardware Implementation~~

~~This option lets you stick with the original hardware implementation plan, but the bonus points and the deadlines will be modified accordingly. However, there is still uncertainty about whether the university will be opened in the summer period or not, so I think it is a safer bet to go with the option-B.~~

### Option-B: Detailed Design and Simulation

Instead of hardware implementation you are required to make detailed simulations and PCB layout design for your project. The draft plan is as follows:

- **PCB Design:** You are required to design detailed printed circuit board design using [KiCad](https://www.kicad-pcb.org/), which is an open-source and free software.
You need to implement and present the following in your design:

- The circuit of your design in KiCad
- PCB layout design, and the [gerber](https://en.wikipedia.org/wiki/Gerber_format) files for production ( (How to PCBs work?)[https://www.youtube.com/watch?v=H9pGbLJknDk])
- Prepare a Bill of Materials (BOM) for the components that you used. You can use [one of KiCad's BOM tools](https://www.baldengineer.com/kicad-bom-introduction.html) or external tools.
- (Bonus) Get a quote for manufacturing 1000 pieces of your converter. Get the prices of the components that you used (you can used   [DigiKey](https://www.digikey.com/), or iinternal tools of KiCad). Get a PCB manufacturing quote from [PCBWay](https://www.pcbway.com/), ((From Idea to PCB)[https://www.youtube.com/watch?v=35YuILUlfGs]).
- (Bonus) Generate a [3D view](https://kicad-pcb.org/discover/3dviewer/) of your design.

- **Detailed Simulations:* You are required to improve the accuracy of your initial design simulations by including to following:

- Non-ideal semiconductor characteristics (conduction loss, switching time forward voltage etc)
- Non-ideal characteristics of your magnetic design such as coil resistance, leakage inductance (can be assumed 1-2% of the magnetizing inductance)
- Non-ideal characteristics of the filter elements such as capacitor and inductor.


Please don't try to include all these parameters at once. Add them one by one verifying the results at every step

- (Bonus) Derive the transfer function of the circuit and construct a compensator for closed loop control.
- (Bonus) Obtain the open loop bode-plot of your converter (you can use Matlab or LTSpice). You may assume ideal switches for this stage.
- (Bonus) If you can find the spice models of your controller, model the circuit with the controller under different operating conditions (You cans start by checking the [TINA tool from TI](http://www.ti.com/tool/TINA-TI)). Add the compensator that you have designed previously to the simulation and observe closed loop control system. 

- **Efficiency and Thermal Analysis**

- Get the overall losses in your system (MOSFET, diode losses, transformer losses). Support your calculations with analytical calculations and simulation results.
- Get the total losses for each semiconductor and choose a suitable heat-sink
- Develop a thermal circuit and estimate the operating temperature under full load at the worst case.



### Grading

#### To be announce later

Project Outcomes:
- **Preliminary Simulation Report and Presentation (20 pts):** A report that presents your design decisions, computer simulations, and component selection for the all parts of the project. Similar grading rules apply with previous projects (i.e. format, number of commits etc.) Each team should present their topology selection and project design. They should describe how they selected critical components and their plan for design and manufacturing. They should come up with their wounded transformers and inductors and basic experimental verifications.

- **Complete Design Report (40 pts):** A report that presents your design decisions, computer simulations, and component selection. Similar grading rules apply with previous projects (i.e. format, number of commits etc.). Reports and all relevant files should be submitted from GitHub.

- **Test Results (10 pts):** This section can be added into the design report, or submitted as a separate report. It should contain your results with the load running (data can be collected on the demo day, but preferably earlier) The report can contain any other useful tests (efficiency figures, start-up, ripple content, step-load response, low-voltage operation etc.). Discussions on discrepancies between simulation and experimental results.

- **Demo Day (30 pts):** Each team is expected to present their prototype in the demo day. If you have a prototype, but somehow if it doesn't work on the demo day, you will get zero points from this part. However, if you don't come up with a prototype, or convince me that you put enough effort in building a prototype, you will get zero points from the all hardware project (yes, even if you had the design report). In the demo day, I expect you to demonstrate following features:

    - To be able to support the rated load for 2 minutes
    - Reasonable ripple free output voltage levels even with the load is varied
    - To have reasonable efficiency (Input and output power should be measured)


#### Bonus Parts

You can get extra points in any of the following:

- **Efficiency Bonus:** The bonus point will be calculated based on this formula: 100 * (Efficiency)<sup>2</sup> - 45 + I<sub>o</sub>. Note that you may get negative efficiency bonus depending on your converter efficiency and rated output current.

- **Current Mode Control Bonus:** Implement a closed loop using current mode control such as average mode control or peak current control. This bonus cannot be got with only a voltage mode control.

- **Analog Controller IC:** Projects with an integrated circuit analog controller (such as TL494) will be rewarded with extra point.

- **PCB Bonus:** Implementing the project on a printed circuit board (PCB) will be rewarded.

- **Industrial Design Bonus:** The expected volumes for each converter is different because of different ratings. The team's effort to minimize the volume will be evaluated separately. Compact and user friendly projects will be rewarded.

- **Soft Starting:** Applying soft starting techniques will be rewarded.

- **Single Supply:** The projects which are able to operate fully with just one supply (and no powerbanks) will be rewarded.

- **Synchronous Switching:** The projects applying synchronous switching on secondary side will be rewarded with extra point.

- **Non-Isolated Output:** If the isolation between the input side and output side is broken for any reason, you will get a penalty with negative bonus.

- **Utilization:** Tight semiconductor ratings will be rewarded. (?)

- **Video:** Although video submission is not mandatory, you are free to submit a video for your project duration. Again feel free to get funny, and creative as well as describing your projects. More than one video bonuses can be awarded.

- **Karma Bonus:** This bonus will be awarded to one person who helps most to everyone during the project period. This bonus will be awarded by the results of anonymous voting on ODTUClass.

The table given below shows the bonus points.

<table>
    <tbody>
        <tr>
            <td rowspan=12>BONUS</td>
            <td rowspan=1>Efficiency</td>
            <td> 100 * (Efficiency)<sup>2</sup> - 45 + I<sub>o</sub></td>
        </tr>
        <tr>
                <td rowspan=1>Current Mode Control</td>
                <td>30</td>
        </tr>
        <tr>
                <td rowspan=1>Analog controller IC</td>
                <td>10</td>
       </tr>
        <tr>
                <td rowspan=1>PCB</td>
                <td>25</td>
       </tr>
       <tr>
                <td rowspan=1>Industrial Design</td>
                <td>20</td>
       </tr>
       <tr>
                <td rowspan=1>Soft Starting</td>
                <td>15</td>
       </tr>
       <tr>
                <td rowspan=1>Single Supply</td>
                <td>30</td>
       </tr>
       <tr>
                <td rowspan=1>Synch Switching</td>
                <td>30</td>
       </tr>
       <tr>
                <td rowspan=1>Non-Isolated Output</td>
                <td>-30</td>
       </tr>
       <tr>
                <td rowspan=1>Utilization</td>
                <td>15</td>
       </tr>
       <tr>
                <td rowspan=1>Video</td>
                <td>25</td>
       </tr>
       <tr>
                <td rowspan=1>Karma</td>
                <td>10</td>
       </tr>
    </tbody>
<tbody>
</tbody>
</table>


### Frequently Asked Questions

- Do I need to buy all the components?

No, we will provide some mostly used components, but not all of them. Please check the [available component list](https://github.com/odtu/ee463/blob/master/Hardware-Project/components.md).

- Can I use the lab before demo day?

Yes, you will be able to use power electronics lab. The machinery lab can be used after EE362 lab sessions are finished. However, this semester you are going to be allowed to use the laboratories only for work hours.

- Who can I get in touch to use the laboratories?

You can get in touch with only course assistants (check keysan.me/ee464) and me.

- What equipment will be available for us in the lab?

You will be able to use oscilloscope, power supply, soldering station, function generator and variacs.

- Can I also work at nights in the lab?

Unfortunately, due to safety regulations, you have to work only under technician supervision during working hours.

### Hints:

For all hints please have a look at the [tips document](https://github.com/odtu/ee463/blob/master/Hardware-Project/tips.md).

Have a look at the hardware project presentation by course assistants [here](https://prezi.com/zqhrvmqz0ik5/ee463-hardware-project/).

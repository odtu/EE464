# EE464 Hardware Project


Specs for the hardware project are listed below. You need to form a group of 2/3 students and reserve the project that you choose. You are not allowed to have a group with any of your group members from the first semester.

Once you determined your group members, please write it up in [this spreadsheet](https://docs.google.com/spreadsheets/d/1HgNVN4wFpfH8vbBwCHcy3HoVSP6NIBR18eRuBtWIT0I/edit?usp=sharing).
Also put the project number you would like to work on. One group per project is allowed. First come first served.

<table>
    <thead>
        <tr>
            <th></th>
            <th>Project No</th>
            <th>FLY #1</th>
            <th>FLY #2</th>
            <th>FLY #3</th>
            <th>FLY #4</th>
            <th>FLY #5</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=7>**FLYBACK**</td>
            <td rowspan=1>Minimum Input Voltage (V)</td>
            <td>24</td>
            <td>24</td>
            <td>24</td>
            <td>24</td>
            <td>24</td>
        </tr>

        <tr>
                <td rowspan=1>Maximum Input Voltage (V)</td>
                <td>48</td>
                <td>48</td>
                <td>48</td>
                <td>48</td>
                <td>48</td>
        </tr>
        <tr>
                <td rowspan=1>Output Voltage (V)</td>
                <td>5</td>
                <td>5</td>
                <td>10</td>
                <td>10</td>
                <td>12</td>
       <tr>
                <td rowspan=1>Output Power (W)</td>
                <td>30</td>
                <td>30</td>
                <td>60</td>
                <td>60</td>
                <td>70</td>
       </tr>
       <tr>
                <td rowspan=1>Output Volt. Peak-to-Peak Ripple (%)</td>
                <td>4</td>
                <td>4</td>
                <td>4</td>
                <td>4</td>
                <td>4</td>
       </tr>
       <tr>
                <td rowspan=1>Line Regulation (%)</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
       </tr>
       <tr>
                <td rowspan=1>Load Regulation (%)</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
                <td>2</td>
       </tr>
       </tr>
    </tbody>
<tbody>
    <tr>
        <th></th>
        <th>Project No</th>
        <th>FOR #1</th>
        <th>FOR #2</th>
        <th>FOR #3</th>
        <th>FOR #4</th>
        <th>FOR #5</th>
    </tr>
    <tr>
        <td rowspan=7>**FORWARD**</td>
        <td rowspan=1>Minimum Input Voltage (V)</td>
        <td>24</td>
        <td>24</td>
        <td>24</td>
        <td>24</td>
        <td>24</td>
    </tr>

    <tr>
            <td rowspan=1>Maximum Input Voltage (V)</td>
            <td>48</td>
            <td>48</td>
            <td>48</td>
            <td>48</td>
            <td>48</td>
    </tr>
    <tr>
            <td rowspan=1>Output Voltage (V)</td>
            <td>5</td>
            <td>5</td>
            <td>10</td>
            <td>10</td>
            <td>12</td>
   <tr>
            <td rowspan=1>Output Power (W)</td>
            <td>20</td>
            <td>20</td>
            <td>40</td>
            <td>40</td>
            <td>50</td>
   </tr>
   <tr>
            <td rowspan=1>Output Volt. Peak-to-Peak Ripple (%)</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
   </tr>
   <tr>
            <td rowspan=1>Line Regulation (%)</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
   </tr>
   <tr>
            <td rowspan=1>Load Regulation (%)</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
            <td>2</td>
   </tr>
   </tr>
</tbody>
</table>

Here are some important notes:

- Line regulation is the deviation of percent output voltage when input voltage is changed from its minimum to maximum or vice versa.

- Load regulation is the deviation of percent output voltage when load current is changed from 10% to 100% or vice versa.

- Project specs are arranged such that there is not a significant difference regarding the implementation difficulty. Each project belongs to a converter topology has the same current rating.

- Project development phase and final results must be open source. You are required to share the knowledge by properly prepared reports. All simulation files, PCB design files, bill of materials, design regarding magnetic elements should be made available as open access.

- After succeeding the voltage level conversion, you will probably want to pursue additional merits for your converter. These may include:

    * Higher efficiency
    * Compact design
    * High power density
    * Employing soft switching techniques


- All of the additional converter merits and any other effort that you put outside this project definition will be awarded in grading, accordingly.

- You may also have a power conversion scheme in your mind. (Required for work, summer practice, for your hobby project etc.) You can propose other topologies and specs outside the ones listed above. Make sure the new project you propose involves some kind of magnetic design (because all of the above have).

- Converters on breadboard are okay but we expect you to start early and exhibit your final design on a PCB.

- TI shares a lot of its designs, in detail. Please check: http://www.ti.com/general/docs/refdesignsearchresults.tsp

- It is strongly advised to read application notes about your project topology. You can find converter designs on web and (partly) utilize their solution by properly citing them. Do not try to find an overall design to evade the design effort. We also have a large collection of converter designs published online.

- Most of the power companies (especially TI) send free samples.

- Based on your hardware experience in EE463, you should remember that it is vital to prepare your shopping list early. Contact local and international component dealers as soon as possible.

- The magnetic cores listed in [this spreadsheet](https://docs.google.com/spreadsheets/d/1HXe-ban1QV2iynLcxp-vsHEPFjtSYkQUeh2KFEf1brs/edit?usp=sharing) will be available in our laboratory. You can borrow those cores and return them at the end of the semester. Those magnetic cores are from Magnetics. For detailed information about the cores, you can visit the manufacturer website. Additionally, you can also use other magnetic cores if you wish.


### Grading

Project Outcomes:

- **Design Report (50 pts):** A report that presents your design decisions, computer simulations, and component selection. Similar grading rules apply with previous projects (i.e. format, number of commits etc.). Reports and all relevant files should be submitted from GitHub.

- **Test Results (20 pts):** This section can be added into the design report, or submitted as a separate report. It should contain your results with the load running (data can be collected on the demo day, but preferably earlier) The report can contain any other useful tests (efficiency figures, start-up, ripple content, step-load response, low-voltage operation etc.). Discussions on discrepancies between simulation and experimental results.

- **Demo Day (30 pts):** Each team is expected to present their prototype in the demo day. If you have a prototype, but somehow if it doesn't work on the demo day, you will get zero points from this part. However, if you don't come up with a prototype, or convince me that you put enough effort in building a prototype, you will get zero points from the all hardware project (yes, even if you had the design report). In the demo day, I expect you to demonstrate following features:

    - To be able to support the rated load for 2 minutes
    - Reasonable ripple free output voltage levels even with the load is varied
    - To have reasonable efficiency (Input and output power should be measured)


#### Bonus Parts

You can get extra points in any of the following:

- **Efficiency Bonus:** The bonus point will be calculated based on this formula: 100 * (Efficiency)<sup>2</sup> - 40. Note that, for the projects having efficiency below approximately 63%, the bonus point will be negative.

- **Feedback Bonus:** Implement a closed loop voltage controller that can keep the output voltage constant for given range of input voltage and with step changes in the output load (i.e. from 10% load to full load). For that purpose you can use either a digital controller or analog controller. The digital controller will be rewarded with 20 pts whereas the analog controller will be rewarded with 40 pts.

- **PCB Bonus:** Implementing the project on a printed circuit board (PCB) will be rewarded with 30 pts.

- **Compactness Bonus:** The expected volumes for each converter is different because of different ratings. The team's effort to minimize the volume will be evaluated separately. Compact projects will be rewarded with 15 pts.


- **Soft Starting:** Applying soft starting techniques will be rewarded with 15 pts.

- **Single Supply:** The projects which are able to operate fully with just one supply will be rewarded with 30 pts.

- **Non-Isolated Output:** If the isolation between the input side and output side is broken for any reason, 15 pts will be subtracted from overall point. Therefore, the reward is -15 pts.

- **Video:** Although video submission is not mandatory, you are free to submit a video for your project duration. Again feel free to get funny, and creative as well as describing your projects. More than one bonuses can be awarded.

The table given below shows the bonus points.

<table>

    <tbody>
        <tr>
            <td rowspan=9>**BONUS**</td>
            <td rowspan=1>Efficiency</td>
            <td>100 * (Efficiency)<sup>2</sup> - 40</td>
        </tr>

        <tr>
                <td rowspan=1>Closed Loop Digital Controller</td>
                <td>20</td>
        </tr>
        <tr>
                <td rowspan=1>Closed Loop Analog Controller</td>
                <td>40</td>

       <tr>
                <td rowspan=1>Printed Circuit Board (PCB)</td>
                <td>30</td>

       </tr>
       <tr>
                <td rowspan=1>Compactness</td>
                <td>15</td>

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
                <td rowspan=1>Non-Isolated Output</td>
                <td>-15</td>
       </tr>
       <tr>
                <td rowspan=1>Video</td>
                <td>25</td>
       </tr>
    </tbody>
<tbody>
</tbody>
</table>

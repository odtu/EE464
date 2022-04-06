# EE464 Hardware Project

### Deadlines
- Complete Simulation Report - 8th of May
- Presentation for Feedback Session - 9th of May
- Hardware Demo - 17th of June
- Final Report - 1st of July
- Video - 1st of July


In this project you are going to design an isolated DC-DC converter for the specs given below. You are not limited to use any topology. See the bonus part for the topology bonus. 
You need to form a group of 3 students and select an isolated converter. You are not allowed to have a group with any of your group members from the first semester.
Once you determined your group members, please write it up in [this spreadsheet](https://docs.google.com/spreadsheets/d/1wVn8rC1ijDssq3Wuj-eHOGAtKjgqvEfb5lax2LLcCy4/edit?usp=sharing).

### Specs:

Specifications of the project are listed as follows:

 - **Minimum Input Voltage**: 24 V
 - **Maximum Input Voltage**: 48 V
 - **Output Voltage**: 15 V
 - **Output Power**: 45 W
 - **Output Voltage Peak-to-Peak Ripple**: 3%
 - **Line Regulation**(Deviation of percent output voltage when input voltage is changed from its minimum to maximum or vice versa): 3%
 - **Load Regulation**(Deviation of percent output voltage when load current is changed from 10% to 100% or vice versa): 3%

Here are some important notes:

- Closed loop control is a must. Projects without a closed loop control will not be accepted.

- Project development phase and final results must be open source. You are required to share the knowledge by properly prepared reports. All simulation files, PCB design files, bill of materials, design regarding magnetic elements should be made available as open access.

- After succeeding the voltage level conversion, you will probably want to pursue additional merits for your converter. These may include:

    * Higher efficiency
    * Compact design
    * High power density
    * Employing soft switching techniques

- All of the additional converter merits and any other effort that you put outside this project definition will be awarded in grading, accordingly.

- Converters on stripboard are okay if it is working, but we expect you to start early and exhibit your final design on a PCB.

- TI shares a lot of its designs, in detail. Please check: http://www.ti.com/general/docs/refdesignsearchresults.tsp

- It is strongly advised to read application notes about your project topology. You can find converter designs on web and (partly) utilize their solution by properly citing them. Do not try to find an overall design to evade the design effort. We also have a large collection of converter designs published online.

- Most of the power companies (especially TI) send free samples.

- Based on your hardware experience in EE463, you should remember that it is vital to prepare your shopping list early. Contact local and international component dealers as soon as possible.

- The magnetic cores listed in [this spreadsheet](https://docs.google.com/spreadsheets/d/1HXe-ban1QV2iynLcxp-vsHEPFjtSYkQUeh2KFEf1brs/edit?usp=sharing) will be available in our laboratory. You can borrow those cores and return them at the end of the semester. Those magnetic cores are from Magnetics. For detailed information about the cores, you can visit the manufacturer website. Additionally, you can also use other magnetic cores if you wish.

### Grading

Project Outcomes:

- **Simulation and Magnetic Design Report (15 pts):** A report that presents your design decisions, computer simulations, and component selection for the all parts of the project. You are also required to start the magnetic design for your project. You need to start building your transformer/inductor and include the preliminary results (measured magnetizing inductance, leakage inductance etc.) in the report. Similar grading rules apply with previous projects (i.e. format, number of commits etc.)

- **Presentation for Feedback Session (15 pts):** Each team should present their topology selection and project design. They should describe how they selected critical components and their plan for design and manufacturing. They should come up with their wounded transformers and inductors and basic experimental verifications.

- **Complete Design Report (25 pts):** A report that presents your design decisions, computer simulations, and component selection. Similar grading rules apply with previous projects (i.e. format, number of commits etc.). Reports and all relevant files should be submitted from GitHub.

- **Test Results (15 pts):** This section can be added into the design report, or submitted as a separate report. It should contain your results with the load running (data can be collected on the demo day, but preferably earlier). The report can contain any other useful tests (efficiency figures, start-up, ripple content, step-load response, low-voltage operation etc.). Discussions on discrepancies between simulation and experimental results.

- **Demo Day (30 pts):** Each team is expected to present their prototype in the demo day. If you have a prototype, but somehow if it doesn't work on the demo day, you will get zero points from this part. However, if you don't come up with a prototype, or convince us that you put enough effort in building a prototype, you will get zero points from the all hardware project (yes, even if you had the design report). In the demo day, You are expexted to demonstrate following features:

    - To be able to support the rated load for 2 minutes
    - Reasonable ripple free output voltage levels even with the load is varied
    - To have reasonable efficiency (Input and output power should be measured)


#### Bonus Parts

You can get extra points in any of the following:

- **Topolgy Bonus:** Unique topologies will be rewarded. If you select a converter topology that no other groups use, you will be awarded by full bonus. If only two groups use the same topology, half bonus will be given for each. If three or more groups use the same topology, no bonus will be given for those groups.

- **Single Supply:** The projects which are able to operate fully with just one supply (and no powerbanks) will be rewarded.

- **Non-Isolated Output:** If the isolation between the input side and output side is broken for a reason like non-isolated feedback, you will get a penalty with negative bonus. Non-isolated converter topologies will not be accepted.

- **Current Mode Control Bonus:** Implement a closed loop using current mode control such as average mode control or peak current control. This bonus cannot be got with only a voltage mode control.

- **Efficiency Bonus:** The bonus point will be calculated based on this formula: 100 * (Efficiency)<sup>2</sup> - 64. Note that you get negative efficiency bonus if your converter efficiency is less tan 80%.

- **Analog Controller IC:** Projects with an integrated circuit analog controller will be rewarded with extra point.

- **PCB Bonus:** Implementing the project on a printed circuit board (PCB) will be rewarded.

- **Industrial Design Bonus:**  Enclose your design in a plastic/metal box (like one of [those](https://www.altinkaya.com.tr/Proje_Kutulari.html), not in a shoe box) and label input/outputs with proper connections for safe operation. You can design and 3D print your housing by using 3D printer available in our department. You can contact with [Mesut Özer](https://eee.metu.edu.tr/personel/mesut-ozer) for details of 3D printing process or you can use the 3D printer in the Ground Lab. Secure the board and connections so that it does not get damaged when it is subjected to vibrations.

- **Compactness Bonus:** A bonus will be awarded to a project with the smallest volume (including all cabling, control circuitry, filters, connectors etc). This bonus will be available if your design ensures the industrial design bonus criteria.

- **Utilization:** Tight semiconductor ratings will be rewarded.

- **Video:** Although video submission is not mandatory, you are free to submit a video for your project duration. Again feel free to get funny, and creative as well as describing your projects. More than one video bonuses can be awarded.

- **Karma Bonus:** This bonus will be awarded to one person who helps most to everyone during the project period. This bonus will be awarded by the results of anonymous voting on ODTUClass.


### Frequently Asked Questions

- Do I need to buy all the components?

No, we will provide some mostly used components, but not all of them. Please check the [available component list](https://github.com/odtu/ee464/blob/master/Hardware%20Project/components.md).

- Can I use the lab before demo day?

Yes, you will be able to use power electronics lab. The machinery lab can be used after EE362 lab sessions are finished. **You are going to be allowed to use the laboratories only for work hours.**

- Who can I get in touch to use the laboratories?

You can get in touch with only course assistants (check keysan.me/ee464).

- What equipment will be available for us in the lab?

You will be able to use oscilloscope, power supply, soldering station, function generator and variacs.

- Can I also work at nights in the lab?

Unfortunately, due to safety regulations, you have to work only under technician supervision during working hours.

### Hints:

For all hints please have a look at the [tips document](https://github.com/odtu/ee464/blob/master/Hardware%20Project/tips.md).

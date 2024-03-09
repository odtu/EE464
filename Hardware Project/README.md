# EE464 Hardware Project

### Deadlines
- Complete Simulation Report - 15th of April
- Presentation for Feedback Session - TBA
- Hardware Demo - 31st of May
- Final Report - 9th of June


In this project you are going to design an isolated DC-DC battery charger for the specs given below. You are not limited to use any topology. See the bonus part for the topology bonus. 
You need to form a group of 3 students and select an isolated converter. You are not allowed to have a group with all of your group members from the first semester.

### Specs:

Specifications of the project are listed as follows:

 - **Minimum Input Voltage**: 20 V
 - **Maximum Input Voltage**: 40 V
 - **Output Voltage**: 12 V
 - **Output Power**: 60 W
 - **Output Voltage Peak-to-Peak Ripple**: 3%
 - **Line Regulation**(Deviation of percent output voltage when input voltage is changed from its minimum to maximum or vice versa): 3%
 - **Load Regulation**(Deviation of percent output voltage when load current is changed from 10% to 100% or vice versa): 3%

Here are some important notes:

- Closed loop control is a must. Projects without a closed loop control will not be accepted.

- You cannot use any other power supply for control circuits etc.

- Project development phase and final results must be open source. You are required to share the knowledge by properly prepared reports. All simulation files, PCB design files, bill of materials, design regarding magnetic elements should be made available as open access.

- **After succeeding the voltage level conversion**, you will probably want to pursue additional merits for your converter. These may include:

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

- The magnetic cores listed in [this spreadsheet](https://docs.google.com/spreadsheets/d/1EulnohgTt6JBoSweeZXwY2xUHmFE42yt89FN3Kc15gA/edit?usp=sharing) will be available in our laboratory. You can borrow those cores and **return** them at the end of the semester. Those magnetic cores are from Magnetics. For detailed information about the cores, you can visit the manufacturer website. Additionally, you can also use other magnetic cores if you wish.

### Grading

Project Outcomes:

- **Simulation and Magnetic Design Report (15 pts):** A report that presents your design decisions, computer simulations, and component selection for the all parts of the project. You are also required to start the magnetic design for your project. You need to start building your transformer/inductor and include the preliminary results (measured magnetizing inductance, leakage inductance etc.) in the report. Similar grading rules apply with previous projects (i.e. format, number of commits etc.)

- **Presentation for Feedback Session (15 pts):** Each team should present their topology selection and project design. They should describe how they selected critical components and their plan for design and manufacturing. They should come up with their wounded transformers and inductors and basic experimental verifications.

- **Demo Day (30 pts):** Each team is expected to present their prototype in the demo day. If you have a prototype, but somehow if it doesn't work on the demo day, you will get zero points from this part. However, if you don't come up with a prototype, or convince us that you put enough effort in building a prototype, you will get zero points from the all hardware project (yes, even if you had the design report). In the demo day, You are expexted to demonstrate following features:

    - To be able to support the rated load for 2 minutes
    - Reasonable ripple free output voltage levels even with the load is varied
    - To have reasonable efficiency (Input and output power should be measured)

- **Complete Design Report and Test Results(40 pts):** A report that presents your design decisions, computer simulations, and component selection.  It should contain your results with the load running (data can be collected on the demo day, but preferably earlier). The report must contain other useful tests (efficiency figures, start-up, ripple content, step-load response, low-voltage operation etc.). Discussions on discrepancies between simulation and experimental results.

#### Bonus Parts

You can get extra points in any of the following.

- **Topolgy Bonus:** Unique topologies will be rewarded. If you select a converter topology that no other groups use, you will be awarded by full bonus. If only two groups use the same topology, half bonus will be given for each. If three or more groups use the same topology, no bonus will be given for those groups. Interleaved operation, synchronous switching or soft switching thechnices may be accepted for this bonus. Contact course assistant for more information.

- **Non-Isolated Output:** If the isolation between the input side and output side is broken for a reason like non-isolated feedback, you will get a penalty with negative bonus. Non-isolated converter topologies will not be accepted.

- **Current Mode Control Bonus:** Implement a closed loop using current mode control such as average mode control or peak current control. This bonus cannot be got with only a voltage mode control.

- **Efficiency Bonus:** The bonus point will be calculated based on this formula: 100 * (Efficiency)<sup>2</sup> - 64. Note that you get negative efficiency bonus if your converter efficiency is less tan 80%.

- **Analog Controller IC:** Projects with an integrated circuit analog controller will be rewarded with extra point.

- **Controller Response Bonus:** Fast and accurate controllers will be rewarded. Input voltage step response and load step response will be investigated.

- **PCB Bonus:** Implementing the project on a printed circuit board (PCB) will be rewarded.

- **Industrial Design Bonus:**  Enclose your design in a plastic/metal box (like one of [those](https://www.altinkaya.com.tr/Proje_Kutulari.html), not in a shoe box) and label input/outputs with proper connections for safe operation. You can design and 3D print your housing by using 3D printer available in our department. You can contact with [Mesut Özer](https://eee.metu.edu.tr/personel/mesut-ozer) for details of 3D printing process or you can use the 3D printer in the Ground Lab. Secure the board and connections so that it does not get damaged when it is subjected to vibrations.

- **Compactness Bonus:** A bonus will be awarded to a project with the smallest volume (including all cabling, control circuitry, filters, connectors etc). This bonus will be available if your design ensures the industrial design bonus criteria.

- **Utilization:** Tight semiconductor ratings will be rewarded.

- **Karma Bonus:** This bonus will be awarded to one person who helps most to everyone during the project period. This bonus will be awarded by the results of anonymous voting on ODTUClass.


### Frequently Asked Questions

- Do I need to buy all the components?

No, we will provide some mostly used components, but not all of them. Please check the [available component list](https://github.com/odtu/ee464/blob/master/Hardware-Project/components.md).

- Can I use the lab before demo day?

Yes, you will be able to use power electronics lab. The machinery lab can be used after EE362 lab sessions are finished. **You are going to be allowed to use the laboratories only for work hours.**

- Who can I get in touch to use the laboratories?

You can get in touch with only course assistants (check keysan.me/ee464).

- What equipment will be available for us in the lab?

You will be able to use oscilloscope, power supply, soldering station, function generator and variacs.

- Can I also work at nights in the lab?

Unfortunately, due to safety regulations, you have to work only under technician supervision during working hours.

### Hints:

For all hints please have a look at the [tips document](https://github.com/odtu/ee464/blob/master/Hardware-Project/tips.md).

# Past Years' Projects

### 2023 Teams

- [Mind The Cap](https://github.com/segozcan/Mind-The-Cap)
- [Hiper-Optik Basküler Converter](https://github.com/yenescaliskan/EE464_Term_Project)
- [uGAN Powertronics](https://github.com/gamzeceliikk/UGAN-Powertronics)
- [Dragonfly](https://github.com/ozanakturk/Dragonfly)
- [Optimus Primary Winding](https://github.com/ahmetcan-akuz/Optimus-Primary-Winding)
- [Klerans](https://github.com/Isaersoz/Klerans)
- [FlyTech](https://github.com/mehmethakanyel/Flytech)
- [Autobots](https://github.com/Mehmet-Emre-Dogan/EE464_2022-2023_TermProject)
- [Backflyp](https://github.com/ahmetfurkangursoy/EE464-TermProject)

### 2022 Teams

- [EMK](https://github.com/kkaya674/EE464-TermProject)
- [Powerpuff Girls](https://github.com/gnszhr/EE464-Hardware-Project)
- [FlyForward](https://github.com/sametyakut/EE464-TERM-RPOJECT)
- [Group 2](https://github.com/soysalper/METU-EE464-TermProject)
- [2 Orta 1 Sade](https://github.com/Musa1088/EE464_HardwareProject)
- [Power Converters](https://github.com/EmrCln/EE464_Term-Project)


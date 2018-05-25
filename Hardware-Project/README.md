# EE464 Hardware Project

### Deadline: 6th of June

Specs for the hardware project are listed below. You need to form a group of 2/3 students and reserve the project that you choose. You are not allowed to have a group with any of your group members from the first semester.

Once you determined your group members, please write it up in [this spreadsheet](https://docs.google.com/spreadsheets/d/1KAVsJwLUg4EU7Spf6T_P4cAQa5IwYKrkkvP4pl3IBME/edit?usp=sharing). 
Also put the project number you would like to work on. One group per project is allowed. First come first served.

|Project No|Vin (V) |Vout (V)|Pout (W)|Topology|
|---|---|---|---|---|
|1|48|12|80|Forward or Flyback|
|2|48|12|80|Forward or Flyback|
|3|48|24|100|Forward or Flyback|
|4|48|24|100|Forward or Flyback|
|5|24|12|80|Forward or Flyback|
|6|24|12|80|Forward or Flyback|
|7|12|48|80|Forward or Flyback|
|8|230 AC|9|10|Forward or Flyback|
|9|230 AC|15|15|Forward or Flyback|
|10|48|12|80|Phase-Shifted Full Bridge|
|11|48|24|100|Phase-Shifted Full Bridge|

Here are some important notes:

- Project specs are arranged such that there is not a significant difference regarding the implementation difficulty. Low voltage applications require higher output power where high voltage (line voltage) projects are low power. 

- Project development phase and final results must be open source. You are required to share the knowledge by properly prepared reports. All simulation files, PCB design files, bill of materials, design regarding magnetic elements should be made available as open access.

- After succeeding the voltage level conversion, you will probably want to pursue additional merits for your converter. These may include:

    - Higher efficiency
    - Compact design
    - High power density
    - Multi-output design (especially for project 9)
    - Employing soft switching techniques (especially for project 10-11)
    - Providing more output power than required

- All of the additional converter merits and any other effort that you put outside this project definition will be awarded in grading, accordingly.

- You may also have a power conversion scheme in your mind. (Required for work, summer practice, for your hobby project etc.) You can propose other topologies and specs outside the ones listed above. Make sure the new project you propose involves some kind of magnetic design (because all of the above have).

- Converters on breadboard are okay but we expect you to start early and exhibit your final design on a PCB.

- TI shares a lot of its designs, in detail. Please check: http://www.ti.com/general/docs/refdesignsearchresults.tsp

- You can find converter designs on web and (partly) utilize their solution by properly citing them. Do not try to find an overall design to evade the design effort. We also have a large collection of converter designs published online.

- Most of the power companies (especially TI) send free samples.

- Based on your hardware experience in EE463, you should remember that it is vital to prepare your shopping list early. Contact local and international component dealers as soon as possible.


### Grading

Project Outcomes:

- Design Report (50 pts): A report that presents your design decisions, computer simulations, and component selection. Similar grading rules apply with previous projects (i.e. format, number of commits etc.). Reports and all relevant files should be submitted from GitHub.

- Test Results (20 pts): This section can be added in to the design report, or submitted as a separate report. It should contain your results with the load running (data can be collected on the demo day, but preferably earlier) The report can contain any other useful tests (efficiency figures, start-up, ripple content, step-load response, low-voltage operation etc.). Discussions on discrepancies between simulation and experimental results.

- Demo Day (30 pts): Each team is expected to present their prototype in the demo day. If you have a prototype, but somehow if it doesn't work on the demo day, you will get zero points from this part. However, if you don't come up with a prototype, or convince me that you put enough effort in building a prototype, you will get zero points from the all hardware project (yes, even if you had the design report). In the demo day I expect you to demonstrate following features:

    - To be able to support the rated load for 2 minutes
    - Reasonable ripple free output voltage levels even with the load is varied
    - To have reasonable efficiency (Input and output power should be measured)


#### Bonus Parts

You can get extra points (25 pts for each) in any of the following:

- Feedback Bonus: Implement a voltage controller  that can keep the output voltage constant even if the input voltage is varied by 25%, and with step changes in the output load (i.e. from no load to full load)

- Highest Efficiency Bonus: The design with the highest efficiency.

- Over-Current Protection Bonus: Feedback loop to limit the output current to specified limits.

- Compactness Bonus: Although the power ratings, and the expected volumes for each converter is different. The team's effort to minimize the volume will be evaluated separately. 

- Best Packaging/PCB Bonus: Design with best packaging, interface and PCB will get this bonus.

- Video: Although video submission is not mandatory, you are free to submit a video for your project duration. Again feel free to get funny, and creative as well as describing your projects. More than one bonuses can be awarded.




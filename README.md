# NucSIM
Simulate operations of Pressurised Water Reactor and attached Steam Turbine for Power Generation.

This simulation represents a rather basic model of a 3500MW(thermal) Pressurised Water Nuclear Reactor and associated Steam Turbine for power generation.\
\
It is still very much a work in progress but currently can simulate operation of a PWR reactor from mode 5 condition (cold shut down) until mode 1 (power operations) and then up to full load. Some of the area/items already implemented include;

- 4-loop PWR reactor
- Pressuriser with heater and spray controllers
- Reactor Source/Intermediate/Power range flux meters
- Chemical and Volume Control system (CVCS) with borating/dilution control
- Estimation of criticality
- Effects of all components +/- of reactivity (although still working to get the negative reactivity effects of Iodine/Xenon accurate)
- 4 x Steam Generators
- Emergency Cooling Water system, with cold leg accumulator, LP/HP Emergency cooling pumps and containment spray pumps
- Alarm/Event, Trip/SCRAM and Runback systems
- simplified Condensate and Feedwater Systems
- simplified Main Cooling Water, Service Water and Closed Cooling Water systems
- simulation of various faults (Fallen rod, Ejected rod, Turbine trip, RCP trip and Runback, LOCA (Loss of Collant Accident)

Please find some current screenshots below.

![Opening Screen view](/Screenshots/ReactorControl.png)

![Opening Screen view](/Screenshots/PrimaryCircuit.png)

![Opening Screen view](/Screenshots/Steam_Turbine_300MW.png)

![Opening Screen view](/Screenshots/Reactor_Control_25pct_load.png)

![Opening Screen view](/Screenshots/Pressuriser.png)

![Opening Screen view](/Screenshots/Steam_Generator_1.png)

![Opening Screen view](/Screenshots/Reactor_Control_100pct_load.png)

The following is my to-do list;

- complete operations manual
- tidy up each screen and add trending where appropriate
- standardise KKS plant coding for all equipment
- improve Iodine/Xenon negative effect on reactivity modelling
- add further faults that may be experienced into the simulation

I will upload some videos of simulator operation in the near future and hope to have this project finished before the end of 2024.

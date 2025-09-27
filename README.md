# NucSIM
Simulate operations of Pressurised Water Reactor and attached Steam Turbine for Power Generation.

This simulation represents a rather basic model of a 3500MW(thermal) Pressurised Water Nuclear Reactor and associated Steam Turbine for power generation. It is not meant as a complete simulator training system, but just as a proof of concept of what is possible.\
\
It is still very much a work in progress but currently can simulate operation of a PWR reactor from mode 5 condition (cold shut down) until mode 1 (power operations) and then up to full load. Some of the areas/items already implemented include;

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
- simulation of various faults (Fallen rod, Ejected rod, Turbine trip, RCP trip and Runback, LOCA (Loss of Coolant Accident)

Minimum System requirements are;
- Apple M1 Pro
- 14-inch (3024 x 1964) screen
- macOS 11 Big Sur

[[Download latest version at my website - https://richardspowergenerationpage.com](https://richardspowergenerationpage.com/?page_id=73)]

Please find some current screenshots below.

![Opening Screen view](/Screenshots/ReactorControl.png)

![Opening Screen view](/Screenshots/PrimaryCircuit.png)

![Opening Screen view](/Screenshots/Steam_Turbine_300MW.png)

![Opening Screen view](/Screenshots/Reactor_Control_25pct_load.png)

![Opening Screen view](/Screenshots/Pressuriser.png)

![Opening Screen view](/Screenshots/Steam_Generator_1.png)

![Opening Screen view](/Screenshots/Reactor_Control_100pct_load.png)

The following is my to-do list;

- complete operations manual - done
- improve Iodine/Xenon negative effect on reactivity modelling
- add further faults that may be experienced into the simulation

Please find videos of simulator operation below - first is reactor startup from cold until full load, and second is reactor response to a large break loss of coolant accident.

[![Example video](https://img.youtube.com/vi/oIUNryUayWU/0.jpg)](https://youtu.be/oIUNryUayWU)

[![Example video](https://img.youtube.com/vi/eyKUxV_y2rk/0.jpg)](https://youtu.be/eyKUxV_y2rk)

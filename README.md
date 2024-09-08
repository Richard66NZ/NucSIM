# NucSIM
Simulation of Pressurised Water Reactor and attached Steam Turbine for Power Generation

This simulation represents a rather basic model of a 3500MW(thermal) Pressurised Water Nuclear Reactor and associated Steam Turbine for power generation.\
\
It is still very much a work in progress but currently can simulate operation of a PWR reactor from mode 5 condition (cold shut down) until mode 1 (on load) and then up to full load. Some of the area/items already implemented include;

- 4-loop PWR reactor
- Pressuriser with heater and spray controllers
- Reactor SOurce/Intermediate/Power range flux meters
- Chemical and Volume Control system (CVCS) with borating/dilution control
- Estimation of criticality
- Effects of all components +/- of reactivity (although still working to get the negative reactivity effects of Iodine/Xenon accurate)
- 4 x Steam Generators
- Emergency Cooling Water system, with cold leg accumulator, LP/HP Emergency cooling pumps and containment spray pumps
- Alarm/Event, Trip/SCRAM and Runback systems
- simlified Condensate and Feedwater Systems
- simplified Main Cooling Water, Service Water and Closed Cooling Water systems
- simulation of various faults (Fallen rod, Ejected rod, Turbine trip, RCP trip and Runback, LOCA (Loss of Collant Accident)


![Opening Screen view](/Screenshots/About.png)

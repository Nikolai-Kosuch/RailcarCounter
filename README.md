# RailcarCounter
Sensorboard to count the number of passing Railcars by counting the number of axis.

Each sensor board supports up to two Hall effect sensors (S1A/B and S2A/B). The analog signals from these sensors are amplified by an LM358P operational amplifier. A CH32V003 microcontroller from WCH processes the amplified signals and transmits the results via I²C (Two-Wire Interface) to a central control unit. 

There are currently two versions of the sensor PCB available: a Minimal Version and an Extended Version. The Minimal Version includes only the essential components required to detect passing railcars. In contrast, the Extended Version offers additional features, such as a power supply selection—allowing the user to choose between 3.3V or a higher voltage via a configurable voltage divider. It also includes indicator LEDs: one for each Hall sensor to show analog signal activity, and five additional LEDs connected to the microcontroller, which can be used to indicate operational readiness and other system states.

![Unbenannt](https://github.com/user-attachments/assets/7a30448c-ff46-4e94-b565-e61d51452972)
![Unbenannt](https://github.com/user-attachments/assets/2fae549b-1096-4812-89d2-091416fdb915)

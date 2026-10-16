# ME4015-ThermostatProject
Arduino IDE Code - In order for this code to function properly please wire your hardware with the following connections and install the library's mentioned below for proper functionality of the dimmer modules and TC.

V328 Thermocouple
GND	--> BB Groun
VCC	-->	BB 5V
SCK	-->	D6
CS	-->	D5
SO	-->	D4
Robot DYN AC Dimmer Module (FAN)
VCC	-->	BB 5V
GND	-->	BB Groun
ZC	-->	D2
PSM	--> D9
Robot DYN AC Dimmer Module (Light/Heater)
VCC	BB 5V
GND	BB Groun
ZC	-->	D2
PSM	-->	D10

Arduino uno
5V	BB 5V
GND	BB Groun
Other Connections listed above
 	 
Install:
RBDdimmer by RobotDyn (GitHub: RobotDynOfficial/RBDDimmer)
MAX6675 library (Adafruit or RobTillaart)

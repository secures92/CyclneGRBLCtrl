CyclneGRBLCtrl
==============

![Pic](http://carlosgs.es/sites/default/files/Cyclone_first_year_12b_GRBLcontrollerBoard_bySamuelKranz.jpg)
From design to manufactured pcb


FAQ
---

Will your board be machinable on the cyclone ?
- Hopefully yes.. smallest trace is 12mil. maybe double sided will be a bit tricky..

What processor is used ? 
- the same as the arduino uno - Atmega 328 - the board will be fully compatible to the arduino uno r3 and grbl.. all the pins are useable.. except the bootloader.. (Im using the FT230X so the arduino bootloader wont work- maybe the serial converter will be changed .. I have to think about it)..

Will you use the stepstick drivers for the steppers ? 
- of course i´ll use the stepstickdrivers.. (x,y,z), there is also a mosfet for the spindle.. and three endstops .. everything can also be connected over the pins (ability to use external components e.g. spindle driver, motor driver, lcd, even the serial converter to use a bluetooth module..)

Is Z-Probing supported?
- the z probing wont have a seperate connector.. (GRBL dont support it atm) but it can be added through a unused pin..

How to get a PCB?
- http://oshpark.com/shared_projects/NCN02WgN

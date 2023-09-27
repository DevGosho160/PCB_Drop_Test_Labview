# Data Acquisition - PCB Drop Test
Run instructions

Pressurize system
Place safety pin into Touch Test
Turn Touch Test on
Connect trigger banana pins to DMM(Voltage measurement)
Make sure PXIe is on
Configure auto operation: number of drops, drop height, and set a rest period of 75 seconds
Open DataAcquisition.vi in PCBDropTestSystem folder
Set the number of drops and add the filepath of the output file to the path textbox. The final element of the filepath must be a .lvm file (C:\Users\localuser\Documents\data.lvm)
Turn trigger and BK Meter on
Start DataAcquisition.vi
Start Auto Operation
Run Tests
After VI stops, turn off the trigger, Touch Test, and BK Meter, put safety pin away
Depressurize the system

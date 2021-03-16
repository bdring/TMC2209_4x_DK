## TMC2209 4 Axis Grbl_ESP32 CNC Controller

This is a simple to set up and use CNC controller with 4 built in Trinamic TMC2209 stepper motor drivers. It is designed to run Grbl_ESP32 firmware. Read more about that here.

### Standard ESP32 Dev Kit Socket

The controller uses a standard ESP32 dev kit socket for module in the 2x19 format. It has an extra socket to allow the use of 0.9" wide and 1.0" wide versions.

### TMC2209 Drivers

These strong and super quiet stepper motor drivers. The firmware is in full control of the drivers. This allows you to set things like microstepping level and current without jumpers and potentiometers. Sensorless end stops are supported. There are interactive tuning features to help set this up.

The 4 drivers can be set up for XYZA axes or any axis can be ganged for XYYZ type machines. 

### Inputs

There are 4 inputs. They are labeled for XY & Z limit limit switches and a probe, but they can be used for any type of input, such as XYZA or XYZ + feed hold, etc.

### Outputs 

There are 4 outputs built into the controller. These are level shifted to 5V and can source or sink up to 25mA.  These can be used for spindle or laser PWMs. They can also be used to drive relay circuits. 

### CNC Output Modules.

The 4 outputs mentioned above are also wired to a standard CNC output module socket. This allows the use of many specialized modules, like RS485, 0-10V, Relays, High current MOSFETs, etc. This gives a lot of flexibility to this controller. 

### Micro SD Card

There is a micro SD socket. This allows gcode to be run without connected device.

### Laser Power Connector

There is a an extra connector that simply outputs the main power on a 2 terminal connector. This would typically used to power a low power laser module.

### Input Voltage

There is a pluggable terminal block for the input voltage. This is limited to 12V on version 2.0. Future versions will support 12V-24V.



 
# Arduino Based Mini CNC Plotter



CNC plotter machine is basically a 2.5 axis CNC machine, it have two stepper motor on both X & Y axis and a servo motor at Z axis.
A pen is connected on Y-axis and Z-axis is used to make pun up & down.
As name suggest plotter machine obvious draw or plotting a drawing as per given instruction.
To give instruction to machine what to draw a special type of code called G-code is required.
Image will be converted to G-code with the help of special type of software.
afterwards this G-code sends to controller and controller commands motors how to move.
As result machine will draw image on paper.

# Software/Application Used
*Arduino IDE v1.6.3 - Used for programming the Arduino.
*Processing v3.3 - Used to open GCTRL.pde file based on Java
*Inkscape v0.48.5 - Used to convert vector graphics to GCODE instruction files

Software/Application Used
*CNC code for Arduino
*GCTRL Processing code
*AFMotor Library for Arduino
*Makerboat GCODE Inkscape Extension

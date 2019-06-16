# PSX Controller to DB15 Adapter.

This is an Arduino sketch converting PSX controller inputs to discrete outputs. I desinged it for Arcade Supergun use but it could be adapted for use in many other control applications that require discrete outputs. This code is dependent on the PSX.h library. You need to install that library in order to compile the sketch. https://github.com/dcunited001/arduino-psx/blob/master/Psx.h

# Instructions

The upload the .ino file to an Arduino Uno or similar compatible device and connect the I/O pins according to the layout described in the .ino file. If you wish to remap the buttons you can modify the pin selections in the file to suit your needs. 

# Custom PCB Info.

I have designed several prototype PCBs for this project. Currently they are available as Multi Console to DB15 adapters. They use the same DB15 pinout as Undamned's DB15 USB Decoders. You can order the most current version from <a href="https://oshpark.com/shared_projects/9CTTduIO">Oshpark</a> 

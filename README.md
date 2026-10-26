A simple MiSTer FPGA Lightpen:

![alt text](https://github.com/Jokippo/Lightpen_MiSTer/blob/main/Images/RGB2XYZ_Pen.jpg?raw=true)
![alt text](https://github.com/Jokippo/Lightpen_MiSTer/blob/main/Images/Assembled_PCB.jpg?raw=true)

This Lightpen is based on a OPL811-OC light sensor. The sensor and a button are directly connected to the user port. 

Gerber files for the PCB and .stl files for the case are provided.

![alt text](https://github.com/Jokippo/Lightpen_MiSTer/blob/main/Images/Schematic.PNG?raw=true)


Parts:
```
1x OPL811-OC available on mouser.com
1x 6x6x4.5mm tactile button
1x Right angle 3 position 2.54mm header 
2x 220ohm through hole resistor or 0603 SMD
1x 0.1uF MLCC through hole capacitor or 0603 SMD
1x USB-A cable
```

Instructions:

Important!!! Slide the 3d printed screw on cap over the USB cable before soldering.

- Bend the leads of the through hole components towards the middle of the PCB and cut them flush. There isn't much space on the bottom. 

- The bottom of the header should be at the same height as the top of the pcb. You can use a right angle header or float a straight one with some solder blobs.

- The USB cable can be secured by tightly twisting 3 bare twist tie wires through the 3 provided hole pairs. The holes are grounded so either include the cable shield under the bare twist ties, or solder it to usb ground.

![alt text](https://github.com/Jokippo/Lightpen_MiSTer/blob/main/Images/TwistTies.jpg?raw=true)

- Insert the sensor as shown in the picture. Ground -> top pin, 5v -> middle pin, Signal -> bottom pin.

![alt text](https://github.com/Jokippo/Lightpen_MiSTer/blob/main/Images/Sensor_insert.jpg?raw=true)

- The button should be inserted with the buttonhole of the case pointing downwards, the round part of the button downwards, and the sloped part of the button pointing towards the screw hole of the case. Hold the case slightly angled with the tip downwards and tap the button slowly towards the buttonhole.

- Insert the PCB with the button pointing downwards. Then screw on the cap.

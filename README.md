# Bench Building Documentation


<span style="font-size: 1.5em; font-weight: 700;">Introduction:</span> <br>
Once you’ve built a PANOPTES unit, you don’t want to take it apart and rebuild it again. To train people without dismantling a fully assembled unit, we use the bench build process. This approach allows trainees to learn how to build the unit from scratch without having to disassemble an existing one.  

In the Bench-Build, there are some key components that are required for the proper operation of the bench-build.  <br>
They are the:  
Actual mount (in our case, an Ioptron equatorial mount). <br>
Raspberry Pi (The 4 is used as of now, although the 5 might be used in future). <br>
Arduino Uno. <br>
24V Protected Switch Shield Infineon. <br>
Power Supply. <br>
12V-5V Converter. <br>
Wires. <br>
Terminals. <br>
An internet connection. <br>

To train trainees to use the POCS command line you can use a monitor and keyboard, or you can also SSH into the pi using another device.

<span style="font-size: 1.5em; font-weight: 700;">Electrical connections:</span> <br>
The components that are listed above, including the desktop, are used here to be connected to each other. They will be divided into power connections, and data connections.

<span style="font-size: 1.2em; font-weight: 700;">Power Connections:</span> <br>
The connections are mainly between the Power Supply and the Terminals. After that, it is connections between the Terminals, the Pi and the Arduino. All other power connections are between the Arduino and the other modules.

<span style="font-size: 1.2em; font-weight: 700;">Data Connections:</span> <br>
The connections are mainly between the Pi and the Arduino in the first instance in order to download the software into the Arduino, and then it is between the Pi and the Mount and its assorted modules.










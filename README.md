# RadioDek
RadioDek is a device that utilizes the serial line functionality of the Arduino board and the native Python that the app is written in to be able to automate the flow of power in you shack in the form of "Deks" with the click of a button in your computers system tray!

2. 4 relays rated at least 12V@20A with a 5V drive power.

3. Any device capable of being programed with the Arduino IDE

4. A computer.

5. Basic knowledge of the Arduino and Python programing languages (only if you plan to compile it your self).  

if you want to customize the menu entry's and what serial port the program uses you will have to compile the code your self.  I will leave instructions for how to do that per system below. 

The circuit:
relay 1: drive pin connected to digital pin 12.
relay 2: drive pin connected to digital pin 11.
relay 3: drive pin connected to digital pin 14(A0).
relay 4: drive pin connected to digital pin 15(A1).

Note that you can change this config in the Arduino firmware before uploading but these are the plug'n'play settings.
Digital pin 13 and digital pin 10 are set to high on startup and can be used and a 5V power source for your relay drive if you opted to the module style relays like me.

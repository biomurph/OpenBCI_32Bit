# OpenBCI_32Bit
# This repo is for testing OpenBCI 32bit code with Arduino 1.6.4 or later IDE.

Make sure you have the latest Arduino IDE installed on your computer.

Select the folder that is for your OS.
The chipkit-core folder that is located inside should be placed in your
    Documents/Arduino/hardware
folder. If you don't have a hardware folder, go ahead and make one.

place the OpenBCI_32 folder inside your
    Documents/Arduino
folder.

Then re-start the Arduino IDE. You should see a long list of chipKIT compatible boards in the Tools-Boards drop down menu. Select OpenBCI 32 (!) as your board.

Select the OpenBCI_32bit program from your scketch folder.
Plug in the OpenBCI Dongle, making sure that it's slide switch is on the GPIO6 side.
power up your OpenBCI 32bit board, and then put it into bootloader mode:
    Press and hold the RST button
    Press and hold the PROG button
    Release the RST button
    Release the PROG button
    
No you can upload the sketch to your OpenBCI 32bit board! Brilliant!

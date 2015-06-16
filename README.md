# OpenBCI_32Bit
# This repo is for testing OpenBCI 32bit code with Arduino 1.6.4 or later IDE.

Make sure you have the latest Arduino IDE installed on your computer.

Go here https://github.com/biomurph/chipKIT-core-prebuilt and select the folder that is for your OS.
The chipkit-core folder that is located inside should be placed in your
    Documents/Arduino/hardware
folder. If you don't have a hardware folder, go ahead and make one.

There are two library folders here:
    OpenBCI_32  is the base OpenBCI library
    OBCI32_SD is the library that allows for SD card writing
Place them into your
        Documents/Arduino/libraries
folder. If you don't have a libraries folder, go ahead adn make one.

place the OpenBCI_32bit_SD folder inside your
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



---
title: How to Build/Setup a microDrum
lang: en
---
Note: Thanks go out to WesleyS for putting together the original instructions
from which this wiki post is taken. The original post can be found
[here](http://microdrum.net/forum/viewtopic.php?f=18&t=215).

### Step 1: Setting up the environment

* Install the [Arduino IDE](http://arduino.cc/en/Main/Software).

* Now plug the Arduino up to the computer. The drivers should have been installed
  when the IDE was set up. If not, just manually update the driver.

* To make sure the board is working correctly we're going to upload an example
  sketch to the board Called blink. It simply makes an onboard LED blink every second.

To do this:

* Open the Arduino application

* Go to File > Examples > 01.Basics > Blink and click on it.

* Then go to Tools > Board and select your board (Arduino Uno). 

* Next, select your Serial Port.

* Go to Tools > Serial Port and there should only be one option. Make sure it is checked.

* Also, write down what COM# it is(COM 3, COM5, or similar) 

* Finally, upload the program.

* Underneath the File/Edit options there are two circles, one with a checkmark
  and one with an arrow pointing to the right.

* Click the one with the arrow pointing to the right. In the bottom right of the
  window you will see a progress bar. Once it says "done uploading", a small LED
  labeled "L" on the right hand side of the board will be blinking.

* If it is everything is working and we can move to the microDrum program. 

If you need pictures or additional instructions for what was done above, go [here](http://arduino.cc/en/guide/windows)

### Step 2: Uploading the microDrum Firmware

* Make sure your Arduino is still connected.
* Extract the "microDRUM_ConfigTool_v1.0.zip" and "microDRUM_Firmware_v1.0.zip".
* Run the "microDrum.exe" file.
* Under the Setup tab click the "Select COM" option. From the dropdown menu
  underneath the "Select COM" option select the same COM as serial port you
  selected in the Arduino IDE(the number you wrote down).

* Now under the Setup tab select "Update Firmware". A new window will pop up.
  Select the "Uno" in the Box labeled Arduino. Then select your COM port.
* At the top there is an empty box that says "Firmware" to the left of it.
  To the right of the box there is a small box with three periods in it.
* Click that button and navigate to where you extracted the "microDRUM_Firmware_v1.0"
  folder and chose the "microDRUM_Firmware_v1.0.mhd" file.

* Now click "Update".
* The box below the update button will give you some information.
  At the bottom it will either say the upload was a success or it failed.
* If it was a success, skip to step 5, if not follow along below:
* [Download XLoader](http://russemotto.com/xloader/XLoader.zip)
* Extract the zip and run "XLoader.exe"
* Go to your "microDRUM_Firmware_v1.0.mhd" file and rename it to
  "microDRUM_Firmware_v1.0.hex"
* On XLoader click the "..." botton and select to your recelently renamed
  "microDRUM_Firmware_v1.0.hex" Select your COM# and Uno(ATmega328) in the dropdown menu.
* Make sure the Baud Rate is at 115200, then click upload.
* It will say done and you have now uploaded the firmware.

### Step 3: Construction

* Go ahead and unplug the Arduino for now.
* Take the solderless breadboard and insert the multiplexer with the little "u" at the top.
* Use some of the 22 gauge wire and connect the top right pin to the + on the breadboard.
* Then use wire to connect the positive and negatives on both sides of the breadboard. 

* Now connect the three pins on the bottom left of the multiplexer to the - column. 

* Get a 1 Meg Ohm resistor and put it on the bottom of the breadboard with one
  end one the breadboard and the other on the - column.
* Now get a jumper wire and connect it to the multiplexer. Put it on the third
  pin on the left side and connect the other side to the resistor.
* Use another jumper to connect the other end of the resistor to the Analog 0 In on the Arduino. 

* Take the 120 Ohm resistor and put one end on the breadboard and the other end on the + column.
* Use a jumper to connect the other end of the resistor to the "Reset" on the Arduino. 

* Take a jumper and connect it to the pin on the botton right side of the multiplexer.
  The other end of the jumper goes to the Digital In 4 on the Arduino.
* Use another jumper and put it on the pin above the previous on, and connect it to Digital Pin 3.
* Take a final jumper and put it on the pin above that one, the third from the
  bottom on the right side of the multiplexer. Then connect it to Digital Pin 2 on the Arduino.

* Now take a jumper and put it in the + column. Connect the other end to the 5v on the Arduino.
* Use another jumper to connect the - column to Gnd on the Arduino. 

### Step 4: Construction continued

All of the remaining open pins on the multiplexer can be used as inputs.

* If you plug the Arduino into the computer and go to the monitor tab you will
  see that signals are being shown even though nothing is triggering it. 

* To get that to stop use wire to ground all of the open pins but one. I left
  the top left pin open. 

* Now get the piezo, solder, wire, and the soldering iron.

* Solder a piece of wire to the white part of the piezo and another to the brass ring. 

* Strip about half an inch of wire on the end not connected to the piezo.

* The wire that is soldered to the brass ring goes to the - column and the other
  goes to the open multiplexer pin. 

That's it for construction and set-up! Now you need to configure each piezo for
sensitivity and sound.

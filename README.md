
------------------------------------------------------------------------
README for Project 01
------------------------------------------------------------------------
* BUILD INSTRUCTIONS:
    1. collect all of the needed hardware devices
    2. solder the pocketbeagle pins (4 rows) and connect the UB & UI and ID & GND also by soldering them together
    3. use the micro USB adapter to connect the female USB 
    4. connect a button to pin P2_1 (the PWM)
    5. solder the vl53l0x pins
    6. wire the vl53l0x to the button for power, the ground rail and SCL and SDA to the POCKETBEAGLE
    
* OPERATION INSTRUCTIONS:
    1. press the push button to activate the sensor
    2. cover the vl53l0x with your hand at different heights and play some beautiful notes on your themenin
------------------------------------------------------------------------
<h3> VL53L0x: </h3>

- sudo sudo pip3 install adarfruit-circuitpython-vl53l0x

After having downloaded the library on your PocketBeagle, the code that can be found on https://learn.adafruit.com/adafruit-vl53l0x-micro-lidar-distance-sensor-breakout/python-circuitpython at the bottom of the page will print the distance. You can run the code by typing "sudo python3 buzzer" in buzzer.py on the buzzer directory in your Cloud9 terminal. Note that you should configure pins before running this file. 

<h2> Software Operation Instructions </h2>
To run the code for my project, complete the following steps.

- git clone https://github/com/Guido-Domenico-De-Santis/ENGI301
- cd /var/lib/cloud9/ENGI301/buzzer
- sudo ./run
  - If this does not work, the file may not be executable. Run the following line to solve the issue, and then you should be able to run the code using the sudo ./run command.

To make the code run automatically on boot, run the following commands.

Restart the PocketBeagle by running ```sudo reboot``` to make sure that it runs automatically on boot.


You can run the following command to restart the PocketBeagle and test that the code runs automatically on boot.


# BattleBot-Mk2
Siddhler diddler

# About
Currently, our Winter BattleBot code is located in /src/main.cpp. We will need to make updates to this file. The heart of our computer vision code will be located in the /cam/ folder. We will use a Raspberry Pi to process vision computations, and we will continue to use an ESP-32 WROOM to handle controller input and motor output. Our goals will include updating the main.cpp to handle our new weapons, as well as developing a system to navigate our bot using computer vision. 

# Current To-Do
Familiarize yourself with the code, just get a general idea of what everything does. If you have any questions, make sure to ask.

# Controls
PS4 controller inputs are as follows:

Left joystick: directional control. Stick will move bot forward and backward, as well as rotate the bot in place. Bot speed will change with joystick inclination.
Square: toggles the drum motor on and off
Cross: toggles the flipper up or down
Circle: toggles safe mode on/off. When off, motors lose power and flipper will remain in its current position.
PS Button: E-Stop. This will permanently pause motors and flipper will remain in its same position. To resume operation, must reset the ESP32

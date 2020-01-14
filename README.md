# ArcadeStick.MCUF28027
This RTOS needs to be loaded on to the F28027 
The PC needs to run the following python program https://github.com/jle-santos/Serial-Joystick

The Piccolo is flashed with the joystick program and can be plugged into any computer. 
However, for the commands to be read appropriately by Windows, few programs are required to be installed by the user.  

The vJoy API allows any program to mimic a gamepad. [4] In this application, it allows Windows to think that the Piccolo is a real gamepad. The API is used in conjunction with our protocol to properly parse the inputs. However, these programs are not natively in Windows and must be installed before proceeding.

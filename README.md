# vernier_hand_grip
Code for interfacing with the Vernier Go Direct Hand Dynamometer via Python.

Some scripts and files are pulled from the godirect-examples repository found [here](https://github.com/VernierST/godirect-examples/tree/main/python). This repository has EXCELLENT documentation--refer to them for more specific info.  

Some basic steps to get started:  

1. Get Device Information  
Run `get_device_info.py` with the Vernier device plugged in to get the device name and sensor numbers to be able to input into functions.  
2. Basic code for collecting data and saving to csv can be found in the `gdx_getting_started` python files.  
**Note**: You'll need the gdx folder and its contents to interface with the nice API they created so copy it into your working directory and call it like a module.  

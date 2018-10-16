# DIY-GM-Detector
Code for the DIY GM Detector. Contains the Android app, all its code, and the Python 2 code necessary to run the Raspberry Pi. 

Basic commands file is a short list of instructions in case of confusion

GeigerKit.py is the basic Python code to run the detector

Geiger_Auto.py is the Bluetooth enabled version that requires command line controls, outlined in the Basic commands file

DIY_Map.zip is the zipped file of all the Java code for the app. Use Android Studio to view it

app-debug.apk is the actual app. To use it, change your android security settings to allow app downloads from unknown sources and use your web browser to download and install the app. 

The two .zip files, arduino.zip and libraries.zip, are both used for an arduino voltage boost setup. This is for a slightly older design. Using the arduino as a voltage boost will require editing the Python code and turning off the pwm feature within the code.

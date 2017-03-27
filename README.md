#This is version 1 of git example.

-------------------------------------------
		Acoustic Sensor using RPi3
-------------------------------------------

Table of Content
1. Configuration Instructions
2. Installation Instructions
...


1. Configuration Instructions

This section contains 2 parts: hardware configuration and software configuration.

1.1 Hardware configuration

This project is biult on a Raspberry Pi3, with a USB sound card and a microphone.
Ethernet connection is recommeded. If an older version of Raspberry Pi is used,
certain change might be necessary.

First you have to set USB sound card as default audio device. Blah blah...

Second you need to downgrade the alsa-utils from 1.0.28 to 1.0.25. To do so, ....


2. Installation Instructions
.....

3. Operation instructions

After the installation, simply execute "./wave.a" in the project folder.


4. List of project files

The project contains following files:
--README.md 	: 	this file
--makefile 		: 	the makefile of this project
--wave.c 		:	the module containing functions about wave processing
--wave.h		:	the header of wave.c
--screen.c		:	the module containing functions about screen manipulation
--screen.h		:	the header of screen.c
--comm.c		: 	the communication module using libcurl
--comm.h		: 	the header file of comm.c
--main.c		: 	contains main() function
--sound.php		:	the server page to receive data
--show.html		: 	the server page visualizes data		

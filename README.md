# OST-Morse-Box

**NOTE** : check out the extra functions in the new version: Decoder, AF Generator and Iambic A & B keyer modes, 
see :
https://github.com/on7dq/OST-Morse-Box-DG 

Also a new version of the WIndows Control Program has been written, now including a fun game, see :
https://github.com/on7dq/OST-Morse-Box-V3

Oh, and we made some videos too ! Check them out at my YouTube channel.
Start with this video https://youtu.be/ROU9pVeI86k

![book212cover](https://user-images.githubusercontent.com/17215772/215432889-d6ac3934-f121-4c28-a317-8a4a4f6fa4c6.jpg)



OST is the local UBA amateur radio club in the city of Ostend, Belgium.

The OST Morse Box is a versatile circuit that you can fit between the microphone and the microphone input of any transceiver.
It was mainly designed for use with a VHF/UHF transceiver, but can be used for many other purposes.

The main goal is to be able to hold CW practice sessions on the 2m or 70cm band, where the students themselves can reply to the teacher in FM-modulated CW. Another use is to make a few practice QSO's in a safe environment, before "throwing yourself" on the HF bands ...

In addition, the circuit contains a number of extra features, making this a very interesting club-building project.

![Block Diagram](https://github.com/on7dq/OST-Morse-Box/blob/master/Block%20diagram.jpg)

By using an inexpensive Arduino Nano the following functions are available:

	DDS Tone-Generator in software, for a perfectly pure sine wave 
	Microphone is switched off while transmitting CW to avoid disturbing background noise
	Automatic activation of the transceiver PTT
	Adjustable DELAY for the PTT, from 0.5 ... 10 seconds
	Variable CW speed of 5 ... 25 words per minute (WPM)
	OLED display to read the set parameters and texts
	Keying with Straight Key, Paddle or a built-in Touch Paddle!
	Paddle polarity settable to NORMAL / REVERSE
	Built-in "Keep Alive" circuit for use with a Power Bank
	Adaptable to all existing transceivers, using the appropriate microphone plugs (male and female)
	  (The basic model is based on the widely distributed RJ-45 connectors) 
	Power via the USB connection of the Arduino, via the microphone jack or from an external power supply
	Use as a separate electronic keyer for transceivers without a built-in keyer
	Random CW generator, display characters in the serial monitor and on the OLED display.
	Beacon function, can also be used as a memory keyer (1 memory of 80 characters).
	Additional functions can be set via AT commands via the serial monitor
	Entering and transmitting text via the serial monitor
	Windows program for controlling the OST Morse Box (then no need for the Arduino IDE)
	Built-in TEST function for touch paddle

All files needed for making the PCB are in the zipfile above. Make it yourself, order from a local manufacturer,
or order them cheaply in China (send a mail to ON7DQ for more info).
You can also change the PCB to your liking, it was developed with the free edition of DipTrace (https://diptrace.com/)

NOTE : the PCB has been updated to use a more common relay than you see in the manual and on the pictures. 

If you or your club make one or more of these PCB's, please send us a mail, we would love to hear from you: how many were built, were you succesful, what did you like or dislike?
We would like to keep track of how many of these Morse Boxes were built.

Versatility: not all options are mandatory, those who wish to do so, can partially fill the PCB to obtain only the desired functions. This is clearly indicated in the construction manual.

This is what the full option PCB looks like. External components are an OLED display, speaker, touch paddle contacts, LED's and some buttons and switches. And your own straight key or paddle of course!

![PCB Assembled](https://github.com/on7dq/OST-Morse-Box/blob/master/PCB%20Assembled.jpg)

The software and the development of the PCB layout were done by OST club member Gilbert, ONL12523. Great work!
I just came up with the idea for the Morse Box ... built the first prototype, and wrote the documentation.

Good luck in building, and have fun using the OST Morse Box!

Luc, ON7DQ - June 2020

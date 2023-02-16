# Remote-Control

After being  inspired by the PS3 remote design, I decided to design my own remote control.
I started by searching for the means of communication used in PS3s and found that it uses bluetooth so I searched for equivalents to use with the microcontroller atmega328p. 

My remote consists of 8 buttons and 2 joysticks divided equally between the two sides,it also consists of pins for the hc-05 bluetooth module, along with the microcontroller in the middle  and its pins for the programmer. There is also a  power circuit to adapt our input  voltage to the voltage needed for our circuit. 

Uart is a peer to peer means of communication that is used between the microcontroller and the bluetooth module.

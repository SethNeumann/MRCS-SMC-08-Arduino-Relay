8 channel tortoise driver after Chubb's SMC-12 with Arduino relay input

One of the common use cases for our Arduino Relay Controller is setting up a yard or staging ladder. An Arduino relay is often used
to control power on tracks by steering or simply turning power on or off. Another case is to use the SPDT contacts of a common "Arduino
Relay" to control MTB's MPx series switch machines. This board controls 8 Tortoise-by-Circuitron (TM) stall motors using the circuit 
described by Dr Bruce Chubb MMR in his CMRI Application Handbook V 3.0, pages 7-12 thru 7-17, available from JLC Enterprises 
[this is an excellent reference on Model Railroad control and signaling and should be in the library of EVERY model railroader interested 
in electronics]. 

The design of the SMC is modular where a single LM324 quad Op Amp/Comparator controls a pair of Tortii. I have implemented 8 circuits and provided an input
connector compatible with the most common 8 channel Arduino Relay. In this way your code on the Arduino Relay Controller doesn't need to know
whether the device is a Tortoise or an MPx, you simply use the appropriate board.

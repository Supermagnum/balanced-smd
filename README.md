# balanced-smd
A small PCB that uses two TL082CDE4 op amps to amplify a signal from a contact microphone.

It has balanced output,input and should run on +48 phantom power. Shielded cable must with 3 leads be used for connection to the piezo crystals. Please use 0,5 W metal film resistors with 1% tolerance or better and audio quality capacitors.
C0G (NP0) or X7R capacitors is very good.

It is important that the circuit board is mounted inside a metal box, and Ø2mm conducting metal standoffs are used. The corner pads of the PCB board is reserved for that. Of course the PCB board and components must not come in contact with any metal surface expect the standoffs.

	
The circuit may benefit from a Zobel network, that is a 680 pF capacitor and a 150 ohms resistor in series between pin 2 and 3 on the output connector.
It should avoid high frequency oscillation in the mic cable. 

Schematic diagram:
https://github.com/Supermagnum/balanced-smd/blob/main/smd-balanced.pdf

Component side picture with switch settings versus gain in dB:
https://github.com/Supermagnum/balanced-smd/blob/main/front.jpg

Back side:
https://github.com/Supermagnum/balanced-smd/blob/main/back.jpg

Aisler link:
https://aisler.net/p/YIWINLSK
Aisler can suply this assembled with the SMD components in place.

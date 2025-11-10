# IR Object Detection Circuit
I created a simple IR object detection circuit using an IR LED, photodiode, and LM358 as a comparator.  When an object comes near, the IR light reflects onto the photodiode, which changes its voltage. The LM358 compares this with a reference set by a potentiometer, and when the threshold is reached, the indicator LED turns ON.

# Circuit diagram
![Circuit diagram](https://github.com/Karthikeyanmac/IR-Object-Detection-Circuit/blob/main/Circuit%20diagram.png)\

# Connections

1) Connect the negative end of IR LED to one end of 100 Ω resistor.

2) Connect the postive end of IR LED to positive of power supply(5-9v).

3) Connect the negative end of Photodiode to power supply.

4) Connect the positive end of Photodiode to one end of 10 kΩ resistor.

5) Connect both resistors' another ends to ground(negative of power supply).

6) Connect pin 1 of LM358 to one end of 330k ohm resistor.

7) Connect pin 2 of LM358 to 10k potentiometer's output pin.

8) Connect the vcc of potentiometer to (+) and Ground terminal to (-) of power supply.

9) Connect pin 3 of LM358 to photodiode's positive.

10) Connect pin 4 of LM358 to (+) of power supply.

11) Connect pin 8 of LM358 to (-) of power supply.

12) Leave all the remaining pins of LM358.

13) Connect the another end of 330k resistor to LED's anode.

14) Connect LED's cathode to (-) of power supply. 

# IR output
![IR output](https://github.com/Karthikeyanmac/IR-Object-Detection-Circuit/blob/main/IR%20output.png)

For demo video visit my linked in profile www.linkedin.com/in/karthikeyan-s-80b6862b0

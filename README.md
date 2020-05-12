# 8bitFullAdder

This file consists of an 8 bit Ripple Carry full adder 

The full adder was designed to operate via a ripple carry manner. The lowest level of the 8-bit full adder is the 1-bit adder which takes in two inputs gives out the output and the carry out. The design that was selected for the 1 bit was made almost completely with transistors and not with gates. The only gate used were NOT gates for the inputs and outputs of the 8-bit ripple carry design. This saved power and area and also had less delay compared to the design with gates. There were in total 216 transistors in the 8-bit full adder. 

 The ripple carry adder should be used when the design meets timing constraints because the ripple carry adder takes the least amount of energy and is also easier to build compared to the other architectures. In terms of area this is also a good implementation compared to using logic gates since it uses transistors alone to make 1-bit adders. When faster adders are required, carry-increment and carry-skip architectures work well for 8–16 bit lengths. The delay for the carry-ripple, carry-skip and carry-increment architectures depend on the fanout and wire loads as well as the number of logic levels. In terms of area since there were 216 transistors each with width The total approximate area is 2,354,400 nm2. It is not possible to calculate the exact area but if the areas of all the transistors in the 8-bit Full Adder are taken in this is the area.  

## Delay 

The delay according to the simulation testbench is 1.56 ns for the 8 bit Full adder.  

## Power Consumption 

In terms of power is approximately the cost is 24.963 microwatt. This is calculated simply by using P=VI , now by simulating the current being pulled into the FA and using VDD of 1, one can calculate the power consumption of 1 full adder. 

## Improvements 

The main improvements would occur in the Full adder. For the full adder a better solution for speed will be carry increment or carry skip. In order to save area for the ripple carry the whole 8-bit could also be done in a transistor level. Since, none of these were constraints for the project, ripple-carry was used due to its simplicity. Not using logic gates for the 1-bit adder also saved area and power for the ripple carry architecture. 

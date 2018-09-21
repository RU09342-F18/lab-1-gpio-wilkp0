# Multiple Blink

## MSP430G2553

For multiblink 2 LED where instantiated. The first LED on port 1 bit 0 and the second on port 1 bit 0. Both were turned on using the or statement. In order for the 2 LED to blink at the same time but at different rates two if statements where used in an infinite while loop. The if statements only turned on the LED once the integers incremented from 0 to the desired time. Once they reached the limit the an xor was performed to turn to toggle the LED and then the interger was set back to 0. 

##MSP430FR2311

This microcontoller used the same idea, again just using different ports and bits from the G2553. This microcontroller used ports 1 and 2 bit 0 as the output for the LED.

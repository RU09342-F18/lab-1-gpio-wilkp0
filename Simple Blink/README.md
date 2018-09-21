## MSP430F5529
For every project, the watchdog must be turned off with the same line of code except for the 432 board. To simply blink an LED BIT 1 was initiated using an "or" to set the needed bit to 1 making it an output. This ouput was the LED. 
Next a endless for loop was created so that the LED can toggle until turned off. The LED was toggeled using 'Xor' which toggled bit 1 of port 1. To viusally see the LED blink a delay was added. Without the LED would look on, becuase it is blinking so quickly.

## MSP430G2553
The same steps were used for this board excpet the ouput was bit 0 and not 1, so it was toggeld instead. 

# Button Blink
### MSP432P401R

For this microcontroller stopping the watchdog was different but, provided by Code Composer. Again the LED was delcared as an output, but the button was set to 0 making it an input. By '&' the opposite of the bit (~) the bit was set to 0 and activated the button. The LED was on port 1 and bit 0. Next the button was instantiated by enabling the resistor and setting it to a pull up resitor. The button was also in port 1 but bit 1. Everytime the button was pused the state would change. Since the button bounces when pressed, the LED would turn off and on inconsistently. To solve this problem a delay was added, which waited for the button to debounce and then chnaged the state. 

### MSP432G2553

The origianl watch dog was used for the 430. All the same rules applied excpet for the adressing. The LED light was in port 1 and bit 0. The button was located in port 1,but at bit 3 instead.   


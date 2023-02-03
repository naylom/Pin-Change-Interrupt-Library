# Pin-Change-Interrupt-Library
Arduino library to enable interrupts to be set on any digital Pin on Uno

The arduino documentation (https://www.arduino.cc/reference/en/language/functions/external-interrupts/attachinterrupt/) says by deafult you can only use 2
pins for interrupts on the Uno, this enables any digital pin to be used. Makes the Uno more flexible.

A maximum of MAX_PCI_PINS (defined as 8 ) can have interrupts set concurrently

N.B. Tested on Uno only, may work on other AVR based arduinos

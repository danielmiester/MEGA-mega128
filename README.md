# MEGA-mega128
A friend put a bug in my head to create a "visible" atmega8 style chip similar to the Monster 6502 (https://monster6502.com/) I don't want to go transistor level, as the Monster 6502, but a hybrid approach will be used to hide the boring parts.

# Requirements:
* LEDs on interesting busses and registers to indicate state
* LEDs on io "pins" to indicate level and mode (In/Out, 0/1, pullup enabled)
* Implement CPU instructions that make sense for given hardware (IE: skip over DES encryption instructions)
* Implement all digital IO ports, analog IO can be ignored
* Hybrid approach can be utilized: PLCs/ICs/modules or other simulation can be used for "uninteresting" tidbits such as RAM/ROM/Address selectors
* Assembly should be able to run nearly any arduino program
* Arduino bootloader should work as expected
* Clock should run as fast as possible
* clock should offer single step mode
* clock should offer fast step (10hz)
* "Fuses" to be implemented as jumpers, dips, or other switch mechanism 


## Nice to haves
* LCD to give assembly mnemonic of currently executing instruction, with optional lookup of IO register mnemonics

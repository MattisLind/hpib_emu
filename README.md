# hpib_emu
HPIB disk and tape emulator for HP and Tektronix computers

This project aims at creating a HPIB diskemulator that can be used with either Tektronix and HP computers. The hardware is to be based 
on the standard 75160 and 75162 interface chips, some glue PLD and a uCOntroller like a STM32F103 or possibly the bigger STM32F407 with built in 
SDIO interface for simple and better performing SD card performance.

To this date a lab connector and 75160 / 75162 module has been built that can be connected using wiring to a breadboard and uController 
board. The intention is to take best of bread ideas from other HPIB projects.

# JTAG_To_UPDI 
This repository includes a schematic and PCB of a simple circuit designed based on Arduino Nano to program the ATTINY processors using UPDI pin. 

UPDI is a communication protocol developed by Microchip for programming and debugging their tinyAVR and megaAVR microcontrollers.

The circuit and code available in this repository for the JTAG to UPDI program have been developed based on the main JTAG2UPDI available @ https://github.com/ElTangas/jtag2updi. 
The circuit in this repository utilizes an Arduino Nano for UPDI programming preparation.
I have also used an FT232RL IC to provide the USB to serial UART interface. To achieve this, connect the TX pin of the processor to RX pin of the PCB, and the RX pin of the processor to the TX pin in this circuit. A USB micro connector transfers data from the processor to the computer through a USB port. 

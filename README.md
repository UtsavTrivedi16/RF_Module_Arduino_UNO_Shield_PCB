# Introduction
PCB shield for Arduino Uno/Leonardo boards that allows Atmega based processors to send packets via RFM69HCW. This will potentially be used for future students of COMPSYS301 course at The University of Auckland. [Here is a glimpse of the Pacman robot used in the course](https://www.youtube.com/watch?v=HsrKt_Cxeg4). The robot used RF as well as light sensors to navigate paths. This is the Master Module that sends packets of map location information to the [slave module sitting on robot](https://github.com/UtsavTrivedi16/RF-Module-MicroController-Integration-PCB).

## Tools
Made on EasyEDA. Exported for Altium and EasyEDA

## Code Libraries for RFM69HCW
[LowPowerLab](https://github.com/LowPowerLab/RFM69)  
[RadioHead](https://www.airspayce.com/mikem/arduino/RadioHead/classRH__RF69.html)

## Power and IO
1) UNO/Leonardo digital IO port exposed with dedicated pins for LED, OE and Interrupt.
2) SPI Probe Area for debugging using Digital Probes.
3) 5V dedicated Power from Arduino. 3.3V Voltage Regulator and Logic Level Translators for SPI interface.

## Example Application
[Garage Home Automation](https://lowpowerlab.com/guide/garagemote/)  
[IoT Home Automation](https://lowpowerlab.com/guide/gateway/)

## Files Included
1) Schematics and PCB docs for Altium and EasyEDA.
2) Gerber Files for manufacturers.
3) PDFs of schematic, bottom and top layer for easy viewing.

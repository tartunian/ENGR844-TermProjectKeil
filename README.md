# ENGR844-TermProject

This project is based on another Github project: https://github.com/nihit30/ENC28J60-Library

## Changes:
Moved startup files to root of project.
Moved Ethernet driver files to drivers/enc28j60 folder.
Added missing lwipopts file.
Ethernet address in enc28j60.c has been changed.
IP address in main.c has been changed.


## Original README shown below.

# Target Platform: EK-TM4C123GXL w/ ENC28J60
 
 Target uC:       TM4C123GH6PM
 
 System Clock:    40 MHz
 
 # Hardware configuration:
 
 ENC28J60 Ethernet controller

 MOSI (SSI2Tx) on PB7

 MISO (SSI2Rx) on PB6

 SCLK (SSI2Clk) on PB4

 ~CS connected to PB1



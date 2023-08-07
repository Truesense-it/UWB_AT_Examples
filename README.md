# ATIF-examples

This repository contains examples for the ATIF firmware running on Truesense's UWB Development Kit Vulkano and T-Tag boards.
The firmware implements a programming interface based on AT commands over UART that can be used to configure, run and monitor various types of UWB ranging sessions.
The ATIF firmware and related documentation  is availble to registered customers of Truesense UWB Development Kit at https://ultrawideband.truesense.it/support


# Pre-requisites

In order to run the examples in this repository from a PC you will need a serial terminal emulator such as Putty for Windows or minicom for Linux. 
The terminal emulator shall be configured using the following parameters:

 - **Speed**: 115200 Baud 
 - **Data bits**: 8 
 - **Stop bits**: 1 
 - **Parity**: None 
 - **HW Flow control**: disabled

The ATIF firmware expects a newline character ('\n') as the terminator for each AT command so you may need to configure your serial terminal emulator accordingly. Anyway, the firmware tries to convert other termination sequencies such as '\r' or '\r\n'
 
## Documentation

The syntax for AT commands implemented by the ATIF firmware is available in PDF format under the docs folder of this repository.

## TODO

**DCU150**:

 - DL-TDOA examples 
 - Multi-sessionn example

**DCU040**:
- add support for NVM Session storage


# stm32_bluepill_blinky

Serial communication with PC using Waveshare PL2303 trasiever.

Termite (serial port terminal for PC) - https://www.compuphase.com/software_termite.htm
Required drivers for transiever - https://www.waveshare.com/wiki/File:PL2303_Windows_Driver.7z 

Created in STM32CubeIDE for STM32Duino "Blue Pill" HW-267 based on STM32F103CBT6 MCU. 


### To run/modify this project locally:

* clone this repository to your STM32CubeIDE workspace
* in STM32CubeIDE `File > New > STM32 Project From Existing STM32CubeMX Configuration File (.ioc)`
* choose .ioc file from cloned repository
* build and run the project
# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware - [FluidNC](https://github.com/bdring/FluidNC)


![NCMate4](https://user-images.githubusercontent.com/10495848/145067609-8ef39956-5bb4-4081-9541-c956c663a5fe.PNG)

## Features
### NCMate-4
- 100 x 150mm 4 layer PCB
- 4 stepper module slots for up to 4 independent axes or dual motors on one axis
  - Standard Pololu/StepStick or similar style driver modules
  - Trinamic SPi driver modules 
  - External drivers with pulse/direction (isolated)inputs through onboard passthrough solder jumpers
- 4 outputs for RC Servos, that can be confgured as additional independant axes in FluidNC
- 1 flexible Spinlde interface for 0-10V controlled spindle drivers, DC spindle motors or RC ESC powered spindle motors
- 2 power outputs, to control relays or other loads powered from the main supply from your CNC code
- 4 isolated digital outputs with isolated 5V power supply
- 6 isolated low impedance digital inputs with isolated 5V power supply, for limit switches, probe sensors and others
- 2 fan connectors, pwm controlled, 5V or supply voltage selectable through jumper
- Onboard ESP32 WROOM 32 module with 16MB onboard flash, wifi or bluetooth enabled by firmware
- Onboard SD card slot for computerless gcode execution
- 12-24V input (more possible but not tested)

## Status
The first batch of NCMate-4 has been ordered in December 21 and is currently tested.
Any comment, suggestion or any other feedback to make NCMate better is welcome.

## Build or Buy
- You can download gerber files from Github and produce the PCB on your own.
- You can contact me to get a fully assembled board, as long as I have some on stock. Price without driver modules but everyhing else is around USD 80 plus shipping. 
- NCMate is designed in EasyEDA and shared here: https://easyeda.com/luethich80/FlowNC-MK1. You can clone the EasyEDA project, make changes as you like and order the PCB on your own. The design is using parts only which are normally in stock for assembly at JLCPCB, so you can order your board directly from EasyEDA including assembly if desired.




# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware: [FluidNC](https://github.com/bdring/FluidNC)


![NCMate4](https://user-images.githubusercontent.com/10495848/145067609-8ef39956-5bb4-4081-9541-c956c663a5fe.PNG)

## Features
### NCMate-4
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

## Status
The first batch of NCMate-4 is ordered and currently in testing. Any comment or feedback is appreciated to make NCMate better.

## Build or Buy
NCMate is deisgned in EasyEDA and shared here: https://easyeda.com/luethich80/FlowNC-MK1
You can clone the files, make changes and order the PCB (and assembly if parts avalable) on your own, or contact me to get a quotation for a fully assembled board




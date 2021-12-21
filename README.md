# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware - [FluidNC](https://github.com/bdring/FluidNC)

## Get your NCMate
- You can download gerber files from Github and produce the PCB on your own.
- I alwas try to have some assembled boards on stock. Get in touch with me for to check inventory and prices: luethich80@gmail.com
- NCMate is designed in EasyEDA and shared (Link below in the versions). You can clone the EasyEDA project, make changes as you like and order the PCB on your own. All designs are using parts which are normally in stock for assembly at JLCPCB, so you can order your board directly from EasyEDA including assembly if desired.

## NCMate-4
The original NCMate - [EasyEDA Project](https://easyeda.com/luethich80/FlowNC-MK1)

![NCMate4](https://user-images.githubusercontent.com/10495848/145067609-8ef39956-5bb4-4081-9541-c956c663a5fe.PNG)

### Features
- 100 x 150mm 4 layer PCB
- 4 stepper module slots for up to 4 independent axes
  - Standard Pololu/StepStick or similar style driver modules
  - Trinamic SPI driver modules 
  - External drivers with pulse/direction (isolated)inputs through onboard passthrough solder jumpers
- 4 outputs for RC Servos, that can be confgured as additional independant axes in FluidNC
- 1 flexible spindle interface for 0-10V controlled spindle drivers, DC spindle motors or RC ESC powered spindle motors
- 2 power outputs, to control relays or other loads powered from the main supply from your CNC code
- 4 isolated digital outputs with isolated 5V power supply
- 6 isolated low impedance digital inputs with isolated 5V power supply, for limit switches, probe sensors and others
- 2 fan connectors, pwm controlled, 5V or supply voltage selectable through jumper
- Onboard ESP32 WROOM 32 module with 16MB onboard flash, wifi or bluetooth enabled by firmware
- Onboard SD card slot for computerless gcode execution
- 12-24V input (more possible but not tested)

### Versions and know issues
**Version 1.4**
- Changes
  - 5V DC/DC converter fixed
  - Added esp32 reset curcuitry for easy esptool.py programming
  - Changed passthrough - Enable signal can be passed to motor connectors now.
- Known Issues
  - No known issues
    
**Version 1.3**
- Changes
  - First public version
- Known Issues
  - 5V DC/DC Converter hooked up incorrectly. Produces 7.5V output voltage which breaks the digital isolators. 
  - No esptool.py reset circuitry makes programming cumbersome



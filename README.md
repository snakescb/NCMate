# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware - [FluidNC](https://github.com/bdring/FluidNC)

## Get your NCMate
- You can download gerber files from Github and produce the PCB on your own.
- I always try to have some assembled boards. Get in touch with me for prices. I sell the boards with no warranty, as this is a non-profit opensource project. If you are interested, contact me on luethich80@gmail.com.
- NCMate is designed in EasyEDA and shared to the public (Link below in the versions). You can clone the EasyEDA project, make changes as you like and order the PCB on your own. All designs are using basic parts whenever possible which are normally in stock at JLCPCB, so you can order your PCB only or assembled boards directly through EasyEDA.
- Note: Ppinheaders and connectors are normally excluded from the BOM's, so they need to be purchased and soldered separately.

## NCMate-Control
NCMate-Control is the logic board of NCMate. It is design as a compact yet robust board and includes everything essential to run simple baseboards for different use-cases

![top](https://user-images.githubusercontent.com/10495848/224637335-af7e8a46-daec-4151-9601-31aafb47d865.PNG)
![bottom](https://user-images.githubusercontent.com/10495848/224637544-39097ebf-6ba4-49cd-99df-e1485fb33221.PNG)

### Features
- 40 x 50mm 4 layer PCB
- 3.5A 5V DC/DC Converter with 19-60V input voltage range
- ESP32-WROOM-32D 16MB controller module
- 4 I2SO shift registers
- 3.3V / 5V I2SO output voltage selectable through solder jumper
- All ESP32 GPIO's, 32 I2SO Outputs, 5V and 3.3V on pinheaders to baseboard
- 4 outputs for RC Servos, that can be confgured as additional independant axes in FluidNC

### Versions and know issues
**Version 1.1**
- Changes
  - First public version
- Known Issues
  - No known issues
   





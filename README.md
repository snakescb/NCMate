# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware - [FluidNC](https://github.com/bdring/FluidNC)


## Get your NCMate's
- You can download gerber files from Github and produce the PCB on your own.
- I always try to have some assembled boards. Get in touch with me for prices. I sell the boards with no warranty, as this is a non-profit opensource project. If you are interested, contact me on luethich80@gmail.com.
- NCMate is designed in EasyEDA and shared to the public (Link below in the versions). You can clone the EasyEDA project, make changes as you like and order the PCB on your own. All designs are using basic parts whenever possible which are normally in stock at JLCPCB, so you can order your PCB only or assembled boards directly through EasyEDA.
- Note: Pinheaders and connectors are normally excluded from the BOM's, so they need to be purchased and soldered separately.

## NCMate-Control
NCMate-Control is the logic board of NCMate. It is design as a compact yet robust board and includes everything essential to run  baseboards adopted for different use-cases

<p float="left">
  <img src="https://user-images.githubusercontent.com/10495848/224637335-af7e8a46-daec-4151-9601-31aafb47d865.PNG" height="400" />
  <img src="https://user-images.githubusercontent.com/10495848/224637544-39097ebf-6ba4-49cd-99df-e1485fb33221.PNG" height="400" /> 
</p>

#### Features
- 40 x 50mm 4 layer PCB
- 3.5A 5V DC/DC Converter with 9-60V input voltage range
- ESP32-WROOM-32D 16MB controller module
- 4 I2SO shift registers
- 3.3V / 5V I2SO output voltage selectable through solder jumper
- All ESP32 GPIO's, 32 I2SO Outputs, 5V and 3.3V on pinheaders to baseboard

#### Versions and know issues
**Version 1.1**
- Changes
  - First public version
- Known Issues: None
- [EasyEDA Project](https://oshwlab.com/luethich80/FlowNC-MK1_copy_copy)

## NCMate-Mini-6-Basic 
Compact baseboard which supports a variety of machines with up to 6 external stepper axes.

![base top](https://github.com/snakescb/NCMate/assets/10495848/c053f316-8630-4232-b262-6103179bdaf8)
![base bottom](https://github.com/snakescb/NCMate/assets/10495848/e8c8289f-c88f-479c-9001-ac01a977b57f)

#### Features

- 40 x 50mm 4 layer PCB
- 3.5A 5V DC/DC Converter with 9-60V input voltage range
- ESP32-WROOM-32D 16MB controller module
- 4 I2SO shift registers
- 3.3V / 5V I2SO output voltage selectable through solder jumper
- All ESP32 GPIO's, 32 I2SO Outputs, 5V and 3.3V on pinheaders to baseboard

#### Versions and know issues
**Version 1.1**
- Changes
  - First public version
- Known Issues: None
- [EasyEDA Project](https://oshwlab.com/luethich80/FlowNC-MK1_copy_copy)

# NCMate Picture Pictures
Controller mounted on the Mini-6-Basic Baseboard, with and without wooden housing

![IMG_2041](https://github.com/snakescb/NCMate/assets/10495848/3b365da5-6d17-4a77-8681-0929224e6f37)
![IMG_2043](https://github.com/snakescb/NCMate/assets/10495848/63959542-0ee6-450d-bfa2-86aa6a60653e)
![IMG_2042](https://github.com/snakescb/NCMate/assets/10495848/94a6f78b-53db-4fd8-b76e-ed6feda97dc9)
![IMG_2044](https://github.com/snakescb/NCMate/assets/10495848/a263196d-1207-4504-95c3-19437af4c424)

Some 3d Renders out of Fusion360

  
    
   





# NCMate
Motion controller hardware - Inspired by the awesome FluidNC CNC control firmware - [FluidNC](https://github.com/bdring/FluidNC). This deisgn is split into a controller and a baseboard module, supporting the idea that the controller module has everything FluidNC can offer, but the baseboards may be taylormade to the type of machines you run. In current state I designed one baseboard only, the Mini-6-Basic, which are in use in all my machines so far.

## NCMate-Control
NCMate-Control is the logic board of NCMate. It is design as a compact yet robust board and includes everything essential to run  baseboards adopted for different use-cases

<p float="left">
  <img src="https://github.com/snakescb/NCMate/assets/10495848/4e0ddb6e-2012-45f3-a64d-57142183567c" height="500" />
  <img src="https://github.com/snakescb/NCMate/assets/10495848/dd02505b-c576-45fe-89c7-e5060342fdd8" height="500" /> 
</p>

#### Features
- 40 x 50mm 4 layer PCB
- 3.5A 5V switching DC/DC Converter with 9-60V input voltage range
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

- Final Modul 90 x 70mm, 4 layer
- PCB includes "Break-Away" addon boards which stack to the base PCB, see pictures below
- Logically separated functions (axes, digital inputs, digital outpus, spindle, power) on decicated, pluggable connectors
- 6 step, direction, enable, 5V outputs
- 0-10V output with 2 isolated outputs and trim potentiometer for spindles
- RS485 port for spindles
- 4 isolated digital inputs with isolated 5v power supply
- 4 non-isolated digital inputs
- 4 non-isolated digital outpus
- 2 digital power outputs for switching relays or pwm spindles from the dc power source
- Power connector
- USB-C connector to ESP32 on control board, with ESP32 reset logic

#### Versions and know issues
**Version 1.1**
- Changes
  - First public version
- Known Issues: None
- [EasyEDA Project](https://oshwlab.com/luethich80/baseboard-mini-6-basic)

## Get your own NCMate
- You can download gerber files from Github and produce the PCB on your own.
- I always try to have some assembled boards. Get in touch with me for prices. I sell the boards with no warranty, as this is a non-profit opensource project. If you are interested, contact me on luethich80@gmail.com.
- NCMate is designed in EasyEDA and shared to the public (Link below in the versions). You can clone the EasyEDA project, make changes as you like and order the PCB on your own. All designs are using basic parts whenever possible which are normally in stock at JLCPCB, so you can order your PCB only or assembled boards directly through EasyEDA.
- Note: Pinheaders and connectors are normally excluded from the BOM's, so they need to be purchased and soldered separately.

# NCMate Pictures
Controller mounted on the Mini-6-Basic Baseboard, with and without wooden housing

![IMG_2041](https://github.com/snakescb/NCMate/assets/10495848/3b365da5-6d17-4a77-8681-0929224e6f37)
![IMG_2043](https://github.com/snakescb/NCMate/assets/10495848/63959542-0ee6-450d-bfa2-86aa6a60653e)
![IMG_2042](https://github.com/snakescb/NCMate/assets/10495848/94a6f78b-53db-4fd8-b76e-ed6feda97dc9)
![IMG_2044](https://github.com/snakescb/NCMate/assets/10495848/a263196d-1207-4504-95c3-19437af4c424)

Some 3d Renders out of Fusion360, with 3d printable frameparts and rendered in acrylic housing.
Final size including case made from 2mm thick material: 94mm x 74mm x 33mm

![NCMate-Mini-6_2023-Dec-01_09-41-53AM-000_CustomizedView32159782820](https://github.com/snakescb/NCMate/assets/10495848/38c1f8ee-7e0d-4707-8dd3-949abdaf3e90)
![NCMate-Mini-6_2023-Mar-12_11-36-07AM-000_CustomizedView3633665913](https://github.com/snakescb/NCMate/assets/10495848/d4866ff4-d414-4f38-b84d-4bdb57b800e5)






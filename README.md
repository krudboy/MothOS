#harware used in my variation
ESP32-S3 Development Board 2.4G Wifi Module for Arduino ESP IDF ESP32-S3-WROOM-1 N8R2 N16R8 44Pin Type-C 8M PSRAM ESP32 S3
(https://www.aliexpress.com/item/1005007520936918.html)

TTP229 1/4/8/16Channel Jog Digital Touch Button Sensor Capacitive Switch Modules Accessories for Arduino
(https://www.aliexpress.com/item/1005007534045183.html)

12 16 Key 4*4 4*3 Membrane Switch Keypad 4 x 4 4 x 3 Matrix Array Matrix keyboard membrane switch keypad for arduino
(https://www.aliexpress.com/item/1005003154853881.html)

0.96 Inch OLED Display Module SSD1306 I2C IIC SPI Serial 128X64 LCD 4 Pin YellowBlue WhiteBlue for Arduino(Pin Headers Soldered)
(https://www.aliexpress.com/item/1005007389730469.html)

PCM5102 PCM5102A DAC Sound Card Board pHAT 3.5mm Stereo Jack 24 Bits Digital Audio Module for for Raspberry Pi Beyond
(https://www.aliexpress.com/item/1005004215170923.html)



# Important Notes:
* ESP32 S3 with 512kb RAM and 4MB Flash Required if building DIY MothSynths
* When compiling sketch, select PARTITION SCHEME / HUGE APP from Arduino IDE tools menu, otherwise the app wont fit on your esp32

# MothSynth
MothSynth is an opensource, ultracheap music making platform based on a few components DIY enthusiasts might find in their drawers. Available in pre-assembled, PCB schematic and DIY module forms. Scroll down for GitHub and Schematics.

There are a few ways to get your hands dirty with MothSynth, build one yourself from modules easily obtainable from Amazon or AliExpress, manufacture your own PCB, or purchase one from our store.

MothOS, the default Arduino compatible software, currently supports 4 tracks, 2 drum machine banks, 10 instrumets and 5 effects (delay, lowpass, phaser, reverb and overdrive), but who knows where developers will take it! Check out our GitHub and Schematics below!

To upload your own samples to MothSynth, clone the GitHub repo, convert your samples with sample converter and replace .h files in /Samples directory of MothOS Arduino Project.

Sample Converter, pre-assembled boards, schematics and usage info: (https://mothsynth.com/).


# DIY Instructions:
If you're building your own MothSynth, You'll need the following commontly available modules, you'll just need to modify pin assignments in the MothOS project:
- ESP32S3 Dev Board
- Max98357 Breakout Board
- Arduino Compatible Keypad
- 4 LEDs + Required Resistors

![](https://www.mothsynth.com/images/easy.jpg)

# PCB Schematic
![](https://www.mothsynth.com/images/schematic.jpg)

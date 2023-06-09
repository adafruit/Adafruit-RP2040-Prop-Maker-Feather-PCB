## Adafruit RP2040 Prop-Maker Feather with I2S Audio Amplifier PCB

<a href="http://www.adafruit.com/products/5768"><img src="assets/5768-00.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit RP2040 Prop-Maker Feather with I2S Audio Amplifier. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5768

### Description

The Adafruit Feather series gives you lots of options for a small, portable, rechargeable microcontroller board. By picking a feather and stacking on a FeatherWing you can create advanced projects quickly. One popular combo is our Feather M4 or Feather RP2040 with a Prop-Maker FeatherWing on top to create animatronics or props that boot up instantly and can drive LEDs, and small speakers.

We've used the Prop-Maker FeatherWing to make lots of lil robots, swords, and other prop projects. However, what if we made it even easier for people to make props? What if we made it so many projects can be built with minimal or no soldering at all? Yeah that would be pretty nice!

Thus, the creation of the Feather P2040 Prop-Maker: an all-in-one combination of the Feather RP2040 with a Prop-Maker FeatherWing with a few tweaks based on feedback from expert prop-builders. Perfect for fitting into your next prop build! This Feather will unlock the prop-maker inside all of us, with tons of stuff packed in to make sabers & swords, props, toys, cosplay pieces, and more.

We looked at hundreds of prop builds, and thought about what would make for a great low-cost (but well-designed) add-on for our Feather boards. Here's what we came up with:

* Terminal Block NeoPixel Port - With easy-to-use screw terminals you can quickly connect and disconnect your NeoPixel strips and rings. This port provides high current drive from either the Feather Lipoly or USB port, whichever is higher. A 5V level up-shifter gives you a clean voltage signal to reduce glitchiness no matter what chip you're using. You can also cut power to the entire strip instantly to reduce quiescent power, thanks to a separate control transistor.
* MAX98357 I2S 3 Watt Class D Audio Amplifier - Drive any 4-8Ω speaker, up to 3 Watts, for sound effects. Audio comes out on two of the terminal blocks so you can screw in any wires to a speaker you like - we're partial to this small 3W speaker with pre-attached wires. Thanks to the I2S digital inputs, you'll get excellent audio quality
* Triple-Axis Accelerometer with Tap Detection - The LIS3DH is our favorite accelerometer, you can use this for detection motion, tilt, or taps. Here's an example of a lightsaber that makes sounds when swung or hit. We have code for this chip in both Arduino and CircuitPython.
* Extra Button or Output Pin - One more pin on the terminal screw block can be used for button input or digital output, for activation or a simple LED.
* Servo Connection - Plug any hobby servo with 3 wires into the 0.1" spaced header, and you can have quick motion control.
* Low power mode! The power system for the NeoPixels and speaker amplifier can be controlled by a pin to cut power to them, so you have lower power usage when the prop is in sleep or off mode (but can wake up fast by listening to the button press or accelerometer data).

At the Feather's heart is an RP2040 chip, clocked at 133 MHz and at 3.3V logic, the same one used in the Raspberry Pi Pico. This chip has a whopping 8 MB of onboard QSPI FLASH and 264K of RAM!  There's even room left over for a STEMMA QT connector for plug-and-play of I2C devices.

To make it easy to use for portable projects, we added a connector for any of our 3.7V Lithium polymer batteries and built in battery charging. You don't need a battery, it will run just fine straight from the USB Type C connector. But, if you do have a battery, you can take it on the go, then plug in the USB to recharge. The Feather will automatically switch over to USB power when it's available.

Here're some handy specs! You get:

* Measures 52.1mm x 22.8mm x 12.2mm / 2.1" x 0.9" x 0.5 without headers soldered in
* Light as a (large?) feather - ~7grams
* RP2040 32-bit Cortex M0+ dual core running at ~133 MHz @ 3.3V logic and power
* 264 KB RAM
* 8 MB SPI FLASH chip for storing files, images, and CircuitPython/MicroPython code storage. No EEPROM
* Tons of GPIO! 21 x GPIO pins with following capabilities:
	* Four 12-bit ADCs (one more than Pico)
	* Two I2C, Two SPI, and two UART peripherals, we label one for the 'main' interface in standard Feather locations
	* 16 x PWM outputs - for servos, LEDs, etc
* Built-in 200mA+ lipoly charger with charging status indicator LED
* Pin #13 red LED for general purpose blinking
* RGB NeoPixel for full-color indication.
* On-board STEMMA QT connector that lets you quickly connect any Qwiic, STEMMA QT or Grove I2C devices with no soldering!
* Both Reset button and Bootloader select button for quick restarts (no unplugging-replugging to relaunch code)
* USB Type C connector lets you access built-in ROM USB bootloader and serial port debugging
* 3.3V regulator with 500mA peak current output and power enable pin
* 4 mounting holes
* 12 MHz crystal for perfect timing.
* Prop-Making section with I2S 3W audio amplifier, 5V NeoPixel level shifting, accelerometer, servo port, and terminal blocks for fast solder-free connections.

Comes assembled and tested, with some header. You'll need a soldering iron to attach the header if you'd like to use it on a breadboard!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

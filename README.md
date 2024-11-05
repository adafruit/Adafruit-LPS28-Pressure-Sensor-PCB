## Adafruit LPS28 Pressure Sensor - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6067"><img src="assets/6067.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LPS28 Pressure Sensor - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6067

### Description

We stock a large number of barometric pressure sensors, and they all have slight differences: some are ported, some are tiny, some are popular and precise and some are low cost. The Adafruit LPS28 (LPS28DFW) Pressure Sensor is unique in that it can handle a much higher range of pressures: almost every other sensor we've encountered tops out at about 1260 hPa. That means they're totally fine for measuring altitude for most human endeavours, we tend to stay above sea level. However, for some scientific or deep-water uses, 1260 will not cut it! That's why we're happy to stock a sensor that can go down to 4060 hPa - that's as low as -43,000 feet below sea level in air or 40 meters underwater. 

We covered the LPS28DFW sensor on our EYE ON NPI video segment, and liked it so much we turned it into a product!

That makes this a good sensor for use with underwater devices or robots, as it can tell your depth from the pressure readings. Of course, its also still a great sensor for altitude sensing out of the water: with a 24-bit sensor and the ability to discern absolute pressure changes of ±0.5 hPa at the highest quality readings, good for less than 1 centimeter of altitude. (Like all pressure sensors, the actual altitude-above-sea-level depends on the days' pressure at sea level) Or, if you need speed, it can do up to 200 samples per second, without filtering and averaging.

The sensor comes with a little metal port, so you could connect a thin tubing to it for measuring pressure far from where it is soldered. The sensor element within the package has potting gel good up to 10,000 hPa of pressure and protection against some harsh chemicals - check the datasheet for more information to make sure you can use it to measure pressure of the liquid or gas you need.

To make life easier when working with this fancy sensor, we've taken the LPS28 and put it onto a breakout PCB along with support circuitry to let you use this little wonder with 3.3V (Feather/Raspberry Pi) or 5V (Arduino/ Metro328) logic levels. Additionally since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro and you can use our CircuitPython/Python or Arduino drivers to easily interface with the LPS28 and make approximate approximations of proximity in no time! QT Cable is not included, but we have a variety in the shop

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

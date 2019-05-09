# Adafruit CC3000 Breakout PCB

<a href="http://www.adafruit.com/products/1510"><img src="assets/image.jpg?raw=true" width="500px"></a>

This is the PCB for the Adafruit CC3000 WiFi Breakout
Format is EagleCAD schematic and board layout

For more details, check out the product page at

* http://www.adafruit.com/products/1510
* http://www.adafruit.com/products/1469

For years we've seen all sorts of microcontroller-friendly WiFi modules but none of them were really Adafruit-worthy. Either they were too slow, or too difficult to use, or required signing an NDA, or had limited functionality, or too expensive, or too large. So we shied away from carrying any general purpose microcontroller-friendly WiFi boards.

NO LONGER! The CC3000 hits that sweet spot of usability, price and capability. It uses SPI for communication (not UART!) so you can push data as fast as you want or as slow as you want. It has a proper interrupt system with IRQ pin so you can have asynchronous connections. It supports 802.11b/g, open/WEP/WPA/WPA2 security, TKIP & AES. A built in TCP/IP stack with a "BSD socket" interface. TCP and UDP in both client and server mode, up to 4 concurrent sockets. It does not support "AP" mode, it can connect to an access point but it cannot be an access point.

Please note that the CC3000 module is being phased out and [we suggest the WINC1500 as a replacement - it has SSL support, soft-AP capability, and is more reliable.](https://www.adafruit.com/products/2999).

We wrapped this little silver module in a tidy breakout board. It has an onboard 3.3V regulator that can handle the 350mA peak current, and a level shifter to allow 3 or 5V logic level. This version of the CC3000 breakout does not have an onboard antenna - instead we placed a standard uFL connector so that an external 2.4GHz antenna can be used. You will need to purchase a [uFL to RP-SMA adapter cable](http://www.adafruit.com/products/852) and a [2.4GHZ 'WiFi' antenna to use](http://www.adafruit.com/products/944)!
See below for these items. This option can give you better range and makes it easier to enclose in a box. We use the same route and layout as TI's eval board, however, this module is no longer automatically FCC certified when an external antenna is used.

Each order comes with one fully assembled and tested breakout and a small stick of header you can use to solder in and plug into a breadboard. We don't have a detailed tutorial yet but to get you started, we've got a fully working Arduino library that is based off of TI's codebase but adapted for use with the AVR. We also have example code showing how to scan the SSID's, connect to your access point and run DHCP, do a DNS lookup to IP address, ping a site and connect to a remote TCP socket such as a website and print out the page.

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution

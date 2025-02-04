# Inspo-Bot
A robot that autonomously writes inspirational material on a notecard. This project is for **Comet Hack 2021**, a hardware & software competition hosted by IEEE-UTD.

<img src="https://github.com/crsz20/Inspo-Bot/blob/master/logo.png" alt="Logo" width="400">

###

## Objectives
- [ ] Assemble robot with 3D printed parts
- [ ] Interface Arduino Uno with the stepper motors
- [ ] Program stepper motors to write letters & lift the pencil
- [x] Obtain acess to a REST API offering inspiring quotes
- [ ] Relay quotes from the ESP to the Arduino
- [x] Display messages with the ESP's OLED screen

## Technologies
* [QuoteJoy API](https://rapidapi.com/lattice-data-lattice-data-default/api/quotejoy) - A database of inspirational quotes
* ESP8266 Library (2.7.4) - by ESP8266 Community via Boards Manager
* ESP8266 and ESP32 OLED Driver for SSD1306 Display (4.2.0) - by ThingPulse via Library Manager

## Hardware, Equipment, & Tools
1. [Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3)
2. [MakerFocus ESP8266 OLED WiFi Development Board](https://www.amazon.com/MakerFocus-ESP8266-Development-Display-Support/dp/B076JDVRLP/ref=sr_1_15?dchild=1&keywords=ESP8266&qid=1618627783&sr=8-15#customerReviews)
3. CAD modeling for 3D printing
4. Three stepper motors

<img src="https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/520x330/604a3538c15e081937dbfbd20aa60aad/a/0/a000066_featured_1_2.jpg" alt="Arduino Uno" width="400">

<img src="https://images-na.ssl-images-amazon.com/images/I/61PGIz41iaL._AC_SL1200_.jpg" alt="MakerFocus ESP8266 OLED WiFi Development Board" width="400">


Note: You may need [drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) to set up a virtual COM port.

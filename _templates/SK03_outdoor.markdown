---
title: SK03
category: plug
type: Outdoor Plug
standard: us
link: https://www.amazon.com/Benuo-Wireless-Waterproof-Smartphone-Anywhere/dp/B07CG7MBPV
image: https://user-images.githubusercontent.com/5904370/57955597-99416b00-78f6-11e9-8838-7da9498c6a30.png
template: '{"NAME":"SK03 Outdoor","GPIO":[17,0,0,0,133,132,0,0,131,57,56,21,0],"FLAG":0,"BASE":57}' 
link_alt: 
---

SK03 Outdoor Smart Plug which can be found as different brand names on Amazon.  The ESP8266 module inside is a TYWE3S by Tuya. The power monitoring is a HLW8012 much like the original Sonoff POW and other power monitoring modules.

Pull the four rubber pads off the bottom to expose the screws and the unit opens up.  Unscrew the small screws from the board and it comes out of the case. The relay is close to the soldering points on the Tuya module but it can be done if you are careful.  GPIO0 is the button on the underside so you do not need to solder to that point, just hold the button during boot for your flashing process like you would with a Sonoff Basic.  

digiblurDIY did a livestream showing this device, soldering and flashing process (split in two videos): [Part 1](https://www.youtube.com/watch?v=C5_BqptJA_w)  and [Part 2](https://www.youtube.com/watch?v=ca7P9TR9r68)

As of firmware 6.3.0.11, the SK03 is available for use in the module configuration. 

Information regarding the standard soldering and pinouts for the TYWE3S module:

![tywe3s_3](https://user-images.githubusercontent.com/3240875/43324698-669affd6-917a-11e8-8e06-c800741bfb68.png)
![chip_wires](https://raw.githubusercontent.com/digiblur/TuyaDimmer-Tasmota/master/SK03_Outdoor_Flashing_Pinout.jpg)


![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/SK03-1.jpg)
![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/SK03-2.jpg)
![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/SK03-3.jpg)
![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/SK03-4.png)
![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/SK03-5.png)
![](https://github.com/digiblur/TuyaDimmer-Tasmota/raw/master/tasmota_example.JPG)




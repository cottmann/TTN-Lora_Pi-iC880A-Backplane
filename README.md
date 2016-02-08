Lora TTN Backplane for iC880A and Raspberry Pi Zero
=================================================

Eagle PCB files for a [Things Network](http://thethingsnetwork.org/) Lora Gateway.

Provides a backplane to mount
* IMST iC880A LoRaWAN Concentrator 868MHz (http://www.wireless-solutions.de/products/long-range-radio/ic880a)
* Raspberry Pi Zero. 

Notes
-----------

1 The Pi Zero does not have a fuse, so the iC880A is powered through the Pi. 
You can also power *the whole unit* through two pads provided on the board (but then don't also power the Pi). 

2 For setup see https://github.com/ttn-zh/ic880a-gateway -- but you need to set the gateway_ID in local_conf.json manually, because the script looks for the MAC address of the ethernet port, but you need the MAC of the WLAN dongle. 

License Information
-------------------
Created by Tobias Cottmann, 2016

This library is released under the [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license. 
You are welcome to use this library for commercial purposes.

If you use this for your project and find it useful, please send me an email with the link. 
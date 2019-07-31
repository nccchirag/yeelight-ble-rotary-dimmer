# Yeelight Bluetooth Rotary Dimmer Switch

**Intent**<br/>
To be able to use the dimmer switch with other smart home devices and applications eg. [home-assistant](https://github.com/home-assistant/home-assistant)

**Setup Required**
- [YLXD02YL](https://www.aliexpress.com/item/32877610806.html) - Yeelight Ceiling Light [Yeelight 650]
- [YLKG08YL](https://www.aliexpress.com/item/32989801042.html)- Yeelight Smart Dimmer Switch [Paste Version]
- Rooted Android Phone with developer options enabled
  - Bluetooh HCI snoop log enabled
- [BLE Scanner App](https://play.google.com/store/apps/details?id=com.macdom.ble.blescanner)
- [nrf Connect App](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp)

**Hardware**
- [Rotary Encoder](https://www.sparkfun.com/products/15083)
- [BLE Chip Telink Semi TLSR8267](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8267-E_Product%20Brief%20for%20Telink%20BLE%20SoC%20TLSR8267.pdf)

**Protocol Reverse Engineering Open Issue**
- [Issue #1](https://github.com/nccchirag/yeelight-ble-rotary-dimmer/issues/1)

**References**
- https://github.com/leopck/Yee-Light-Blue
- https://github.com/rytilahti/python-yeelightbt
- https://github.com/Marcocanc/mi-lamp-re
- https://medium.com/machine-learning-world/how-i-hacked-xiaomi-miband-2-to-control-it-from-linux-a5bd2f36d3ad
- http://nilhcem.com/iot/reverse-engineering-simple-bluetooth-devices
- https://blog.attify.com/the-practical-guide-to-hacking-bluetooth-low-energy/
- https://github.com/oliexdev/openScale/wiki/How-to-reverse-engineer-a-Bluetooth-4.x-scale

**Other Solution**
- ESP32 based new pcb which can fit in the same plastic housing
  - Deep Sleep
  - LiPo battery
  - HTTP programmable actions

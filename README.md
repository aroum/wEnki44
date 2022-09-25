# wEnki44

wEnki44 is a wireless version of Enki42 with a useless appendix.

Gerber files and STL models can be downloaded in [releases](https://github.com/aroum/wEnki44/releases).

## Typing

youtube video (click pic) by [@krikun98](https://github.com/krikun98)

[![Watch the video](https://img.youtube.com/vi/zcw8uevsyJg/maxresdefault.jpg)](https://youtu.be/zcw8uevsyJg)

## wEnki42

**Q:** Why is the pcb logo "wEnki42" even though the keyboard is called "wEnki44"?

**A:** This is a call to break off the useless appendix and use the [Watchman’s Layouts ](https://github.com/aroum/Watchman-layouts).

## Inspiration

* [nrfMicro](https://github.com/joric/nrfmicro)
* [Jian](https://github.com/KGOH/Jian-Info)
* [enki42](https://www.reddit.com/r/ErgoMechKeyboards/comments/qeq2qg/enki42_slim_ergo_keyboard/)
  
## Features

* 44/42 keys
* Kailh Choc V1 switches
* Choc spacing
* Direct pins 
* Wireless
* Full body Tenting case with magnets
* Power switch and reset button
* NFC tag
  

# Firmware

[wEnki44 zmk config](https://github.com/krikun98/zmk-config/tree/wEnki44) by [@krikun98](https://github.com/krikun98)

You can use firmware from [Jorian840](https://github.com/krikun98/jorian840), they are fully compatible. 

# BOM

| Item                                                                   | Quantity | Remarks                              |
| ---------------------------------------------------------------------- | -------: | ------------------------------------ |
| [Kailh Choc V1](https://aliexpress.ru/item/32959996455.html)           | 44/42    | switches                             |
| [Keycaps](https://aliexpress.ru/item/33026798318.html)                 | 44/42    | 1U (choc spacing)                    |
| [SMD button 3x4x2mm](https://aliexpress.ru/item/1005003812819985.html) | 2        | for reset                            |
| [MSK-12C02](https://aliexpress.ru/item/1005001398386692.html)          | 2        | Power switch                         |
| [702035](https://aliexpress.ru/item/1005003738158239.html)             | 2        | Or any battery size up to 21x47x8.8mm|
| [Magnets](https://aliexpress.ru/item/1005002757445161.html)            | 50-70    | disc 7x2 mm                          |
| [Bumpers](https://aliexpress.ru/item/4001188580018.html)               | 28       | 5x2 mm                               |
| [NFC-tag Ntag213](https://aliexpress.ru/item/1005001731694350.html)    | 1-2      | for top case                         |

[Holyiot 18010](https://aliexpress.ru/item/32951888809.html) is used as a BLE module. 

All everything else is the same to [nrfMicro](https://github.com/joric/nrfmicro/wiki/Components)

Interactive BOM is located ```/pcb/ibom```

# NFC

You can program an NFC tag to connect to a keyboard or open a KLE using the [NFC Tools](https://play.google.com/store/apps/details?id=com.wakdev.wdnfc) app


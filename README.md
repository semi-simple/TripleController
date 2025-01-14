# Triple Controller to USB

Based on [DaemonBite Retro Controllers](https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB) by combining the NES/SNES and Genesis projects together for a specific wiring layout to support 3 different controllers with a single Arduino Pro Micro.

PCB Kits + Assembled units available on [Tindie](https://www.tindie.com/products/timville/triple-controller-classic-gaming-usb-adapter/)

3D Case files were designed by [Dinierto Designs](https://www.etsy.com/shop/DiniertoDesigns) and are available on [Thingiverse](https://www.thingiverse.com/thing:5011783)

Included Controller Map File should be placed in `/media/fat/config/inputs`

## V2 Wiring Diagram

![TripleController-V2 1-Layout](https://user-images.githubusercontent.com/31223405/163745351-3b86d7f5-2a6d-496b-9ffa-7e4f6356e45c.PNG)

V2 Current Draw Readings from DIO Pin 16:
* Arduino Rated Max:      40mA
* Krikzz Joyzz: 			    38mA
* 8BitDo M30: 			      29mA
* SEGA 3-Button: 			    3mA
* SEGA 6-Button: 			    3mA
* Retrobit 6-Button: 		  2mA

## Tested Controllers

The following controllers have been personally tested and are supported with the Triple Controller. All listed devices also fit when using the 3D Case as well.

NES:
* OEM NES Controller
* OEM NES PowerPad
* 8BitDo N30 2.4G Receiver
* 8BitDo NES Retro Receiver

SEGA / Genesis:
* OEM SEGA Master System 2-Button Controller
* OEM Genesis 3-Button Controller
* OEM Genesis 6-Button Controller
* 8BitDo M30 2.4G Receiver
* 8BitDo Genesis Retro Receiver
* Krikzz Joyzz

SNES:
* OEM SNES Controller
* OEM SFC Controller
* OEM SNES NTT Controller
* 8BitDo SN30 2.4G Receiver
* 8BitDo SNES Retro Receiver

## V2 Controller Button Mapping
```
Button   NES        SNES       GENESIS
---------------------------------------------
01       B          B          B
02       A          A          A
03       N/A        Y          Y
04       N/A        X          X
05       N/A        L          Z
06       N/A        R          C
07       SELECT     SELECT     MODE
08       START      START      START
09       N/A        N/A        HOME (8BitDo)
```

## MiSTer Home Menu Suggestion
* **NES:** SELECT + DOWN
* **SNES:** SELECT + DOWN
* **GENESIS:** MODE + DOWN

*Note: SELECT + DOWN = HOME on 8BitDo N30*

## Tested Parts
* **SNES (90 degree model):** [AliExpress](https://www.aliexpress.com/item/32838396935.html) *(Min Qty of 2)*
* **NES:** [AliExpress](https://www.aliexpress.com/item/1005003699734963.html) *(Min Qty of 2)*
* **SEGA / GENESIS:** [AliExpress](https://www.aliexpress.com/item/1005003699497865.html) *(Min Qty of 1)*
* **Micro USB Arduino Pro Micro (3-18v model, reinforced):** [AliExpress](https://www.aliexpress.com/item/32888212119.html)
* **Micro USB Arduino Pro Micro (reinforced):** [Amazon](https://www.amazon.com/gp/product/B01HCXMBOU/) *(Pack of 3)*
* **USB C Arduino Pro Micro (Type C model, reinforced):** [AliExpress](https://www.aliexpress.com/item/32887074671.html), [Sparkfun](https://www.sparkfun.com/products/15795)
* **1x12 Female Header:** [Digi-Key](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC121LFBN-RC/807231)

## PCB + Assembled Examples
![unassembled](https://user-images.githubusercontent.com/31223405/134262489-26a5180b-2c78-4ba8-993b-f7132f75200f.jpg)
![built](https://user-images.githubusercontent.com/31223405/134262494-764370c2-681a-4ca3-b86f-3c8e0dfe66e6.jpg)

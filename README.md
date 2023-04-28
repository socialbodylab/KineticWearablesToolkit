# Kinetic Wearables Toolkit


## Table of contents
* [General info](#general-info)
* [In Use](#in-use)
* [Servo 90 Degree](#servo-90-degree)
* [Servo Flex Base](#servo-flex-base)
* [Servo Linear Adaptor](#servo-linear-adaptor)
* [Micro Stepper Motor](#micro-stepper-motor)
* [Solenoid](#solenoid)
* [BOM](#bill-of-materials)
* [Status](#status)
* [License](#license)
* [Contact](#contact)

## General info
These designs make up a wearable electronics toolkit for electronically animating clothing and accessories using several types of small electric motors for fashion, design and DIY electronics. The toolkit offers several kinds of motion in multiple axes using 3D printed parts and lightweight, inexpensive motor/actuators with multiple attachment options. This toolkit represents the result of our initial work in this area, and provides a basis for building wearable prototypes, finished designs, and for developing further design considerations through experimentation and testing.

## In Use

![Example image](./2020-Feb-15-800px-KWT-04.jpg)

Above: Some elements of the toolkit. Black arrows illustrate direction of movement.

## Servo 90 Degree

![Servo 90 Degree](./servo-90-degree.jpg)

* Using a common 9g micro servo motor
* Pivots in base add support for higher loads
* 3D printable in PLA or other rigid material. We use polycarbonate.
* Attaches with pin/slot or strap


## Servo Flex Base

![Servo Flex Base](./micro-servo-flex.jpg)

* 9g micro servo motor is attached using M2 bolts
* 3D printable in TPU or other flexible material. We use Ninjaflex.
* Attaches with pin/slot in a fixed position or can be mounted with a strap

## Servo Flex Tilt Base

![Servo Flex Tilt Base](./micro-servo-flex-tilt.jpg)

* 9g micro servo motor can be installed in multiple orientations, without tools
* 3D printable in TPU or other flexible material. We use Ninjaflex.
* Attaches with pin/slot in a fixed position or can be rotated under a strap.


## Servo Linear Adaptor

![Example Image](./servo-linear-with-rail.jpg)

![Linear adaptor with ring](./servo-linear-with-ring.jpg)

* 9g micro servo motor drives a wheel which drives a rail of any length.
* Rail can be curved as shown in first image above
* Rail can be straight as shown in second image above
* Flexible tire is not included in the CAD model above. We used a rubber grommet.
* As with Servo Flex Base above, servo can be 180 degree or continuous type motor.
* Linear adaptor is 3D printable in PLA or other rigid material.
* Linear adaptor bolts to flexible base in one of two orientations.
* Base uses pin/slot to attach to fabric.

## Micro Stepper Motor

![Micro stepper motor](./micro-stepper.jpg)

![Micro stepper motor back](./micro-stepper-back.jpg)


* Uses small x27.168 stepper motor (Switec X 27 series)
* Attaches to cloth using lapel pin (not shown)
* 3D printable in PLA or other rigid material
* Suitable for moving very light loads only

## Solenoid

![Solenoid](./solenoid.jpg)

* Uses small 5V solenoid (e.g. https://www.digikey.ca/product-detail/en/sparkfun-electronics/ROB-11015/1568-1592-ND/6163694)
* Soloid is press fit in either mount, flat or 90 degree.
* Mount is 3D printable in TPU or other flexible material.
* We recommend 3D printing (FDM) with square aperture of each part facing up to avoid the need for support structures.
* Be mindful of heat buildup if solenoid is energized at a high duty cycle.


## Bill of Materials
This bill of materials is shown in the photo "Complete Toolkit.jpg". The stepper motor can be made to work without the stepper motor driver featherwing shown.

|  **Fabricated parts:** |  |  |  |  |
| --- | --- | --- | --- | --- |
|  Part/Assembly | Qty | Material |  |  |
|  Micro servo flex base | 1 | TPU/Ninjaflex |  |  |
|  Micro servo flex tilt base | 1 | TPU/Ninjaflex |  |  |
|  micro stepper rotobrooch | 1 | PLA |  |  |
|  Servo 90 deg base | 1 | TPU/Ninjaflex |  |  |
|  Solenoid v3 (both parts) | 1 | TPU/Ninjaflex |  |  |
|  Servo linear adaptor | 1 | TPU/Ninjaflex and PLA |  |  |
|  Servo linear rail (various sizes available) | 1 | PLA |  |  |
|   |  |  |  |  |
|   |  |  |  |  |
|  **Purchased parts:** |  |  |  |  |
|   |  |  |  |  |
|  Part | Qty | Price/ea | Supplier | Link |
| Gauge stepper motor | 1 | $4.99/ea  | Tanin Auto Electronix | https://www.taninautoelectronix.com/product/x27-168-switec-juken-gm-gmc-chevrolet-stepper-motor/ |
|   | 1 | $19.99 with optional breakout board | Tindie | https://www.tindie.com/products/TheRengineer/analog-gauge-stepper-breakout-board |
|  Pull solenoid 5V | 1 | $5.50 | Digikey/Sparkfun | https://www.digikey.com/en/products/detail/sparkfun-electronics/ROB-11015/6163694 |
|  180 degree servo | 1 | $5.00 | Digikey/DF Robotics | https://www.digikey.com/en/products/detail/dfrobot/SER0049/13280116  |
|  Full rotation servo | 1 | $7.50 | Digikey/Adafruit Industries | https://www.digikey.com/en/products/detail/adafruit-industries-llc/2442/5774227 |
|  M2x0.4 bolt x 10mm (SHCS or BHCS) | 10 | $0.08/ea | Fastenal | https://www.fastenal.com/product/details/0134599 |
|  3/8"ID x 5/8"OD Black Rubber Grommet |  | $0.52/ea | Fastenal | https://www.fastenal.com/product/details/11120335 |
|   |  |  |  |  |
|   |  |  |  |  |
|  **Not included (but may be needed for full build)** |  |  |  |  |
|  LiPoly battery |  |  |  |  |
|  Arduino microcontroller |  |  |  |  |
|  Hookup wire |  |  |  |  |
|  Velcro® Brand Self-Grip Straps - 3⁄4" x 75' |  | $37/75 feet | Uline | https://www.uline.com/Product/ProductDetailRootItem?modelnumber=S-8136 |

## Status
Project is: _released_

## License
Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)

## Contact
Created by [@socialbodylab](https://www.socialbodylab.com) - feel free to contact us!

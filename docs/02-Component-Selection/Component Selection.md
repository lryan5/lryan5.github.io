---
title: Component Selection
---
## Overview

The following are the components I have selected for my subsystem and the reason as to why I chose them.


## IR Sensor

#### Photo Transistor
| Solution | Pros | Cons |
|-----------|------|------|
![BPW34](BPW34.jpg) <br>Option 1 <br>Vishay BPW34 Through Hole Photo Transistor <br>$1.23 each <br>[link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/BPW34/1681149) | * Small Size <br> * More precise distance  | * More expensive <br> * Higher viewing angle

| Solution | Pros | Cons |
|-----------|------|------|
![BPW96B](BPW96B_sml.jpg) <br>*Option 2 <br> *Vishay BPW96B Through Hole Photo Transistor <br> *$0.95 each <br> [link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/BPW96B/4071185?s=N4IgTCBcDaIEIAUDqBOAbHEBdAvkA) | *Less expensive <br> *Lower Viewing angle | *Less precise distance <br> *Large size

| Solution | Pros | Cons |
|-----------|------|------|
![OPB732](OPB732.jpg) <br>Option 3 <br>TT Electronics OPB732 Through Hole IR LED <br> $4.61 each <br>[link](https://www.digikey.com/en/products/detail/tt-electronics-optek-technology/OPB732/1637069) | • Currently have 1 device<br>• Setup is known | • Short viewing distance<br>• More expensive |

**Choice:** Option 2: Vishay BPW96B Through Hole Photo Transistor

**Rationale:** For our products operation we don’t need a precise distance calculation. As long as the IR sensor can detect an object within a set range, the product’s operation can be activated. Also, option 2 will be able to pick up the signals we want without interference due to its lower viewing angle. Option 2 is less expensive than the other choices, allowing our customers to pay less for the finished device.


#### IR LED
| Solution | Pros | Cons |
|-----------|------|------|
![TSAL6100](TSAL6100.jpg) <br>Option 1<br>TSAL6100 Through Hole IR LED<br>$0.49 each<br>[link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSAL6100/1681338) | • High radiant intensity<br>• Lower viewing angle | • Need to construct housing<br>• Need to create an attachment to PIC |

| Solution | Pros | Cons |
|-----------|------|------|
![TSAL6200](TSAL6200.jpg) <br>Option 2 <br>TSAL6200 Through Hole IR LED<br>$0.49 each<br> [link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSAL6200/1681339?s=N4IgTCBcDaICoGUCCAZAbGADJkBdAvkA) | • Higher stock<br>• Stable over operating temperature | • Higher viewing angle<br>• Lower radiant intensity<br>• Need to construct housing<br>• Need to create an attachment to PIC |

| Solution | Pros | Cons |
|-----------|------|------|
![OPB732](OPB732.jpg) <br>Option 3<br>TT Electronics OPB732 Through Hole IR LED<br>$4.61 each<br>[link](https://www.digikey.com/en/products/detail/tt-electronics-optek-technology/OPB732/1637069) | • Currently have 1 device<br>• Setup is known | • Short viewing distance<br>• Expensive |

**Choice:** Option 1: TSAL6100 Through Hole IR LED

**Rationale:** This LED Is easier to work with and should give more exact results than the other options. The product shouldn’t be triggered automatically; with the narrow viewing angle of this LED, only a small area will be the trigger area compared to the TSAL6200. Also, the range of this LED is far greater than the OPB732, making operation of the product easier for the end user.

#### Op Amp for Photo Transistor

| Solution | Pros | Cons |
|-----------|------|------|
![MCP6022](MCP6022.jpg) <br>Option 1<br>Microchip MCP6022-I/P Through Hole Op Amp<br>$1.86 each<br>[link](https://www.digikey.com/en/products/detail/microchip-technology/MCP6022-I-P/417828) | • High frequency gain bandwidth<br>• Has the number of circuits needed | • Higher price<br>• Slow shipping speed |

| Solution | Pros | Cons |
|-----------|------|------|
![OP295GPZ](OP295GPZ.jpg) <br>Option 2<br>Analog Devices OP295GPZ Through Hole Op Amp<br>$12.82 each<br>[link](https://www.digikey.com/en/products/detail/analog-devices-inc/OP295GPZ/820348) | • Has the number of circuits needed<br>• Smaller size | • Higher price<br>• Lower frequency gain bandwidth |

| Solution | Pros | Cons |
|-----------|------|------|
![MCP6004](MCP6004.jpg) <br>Option 3<br>Microchip MCP6004-I/P Through Hole Op Amp<br>$0.59 each<br>[link](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?s=N4IgTCBcDaILIGEAKA2ADGgLAWgJIHokQBdAXyA) | • Lower price<br>• Currently have 1 device | • Lower frequency gain bandwidth<br>• Has more circuits than necessary |

**Choice:** Option 3 Microchip MCP6004-I/P Through hole Op Amp

**Rationale:** The MCP6004-I/P is easier to work with because we have worked with in the past and know the general setup that is required to make it function. Making our product more affordable for the customer, the op-amp is significantly less expensive than the competitors and will be able to complete its task. 

## LED

#### Red LED

| Solution | Pros | Cons |
|-----------|------|------|
![LEDDC-5RED](LEDDC-5RED.jpg) <br>Option 1<br>Lumimax LEDDC-5RED Through Hole LED<br>$0.08 each<br>[link](https://www.digikey.com/en/products/detail/lumimax-optoelectronic-technology/LEDDC-5RED/26680666) | • Less expensive<br>• Less pins<br>• Only one color | • Clear |

| Solution | Pros | Cons |
|-----------|------|------|
![QBL8RGB60D0-2897](QBL8RGB60D0-2897.jpg) <br>Option 2<br>QTB QBL8RGB60D0-2897 Through Hole LED<br>$1.06 each<br>[link](https://www.digikey.com/en/products/detail/qt-brightek-qtb/QBL8RGB60D0-2897/10441184) | • Multiple colors<br>• Diffused | • More expensive<br>• More complicated to code |

| Solution | Pros | Cons |
|-----------|------|------|
![QBL8RGB25C0](QBL8RGB25C0.jpg) <br>Option 3<br>QTB QBL8RGB25C0 Through Hole LED<br>$1.16 each<br>[link](https://www.digikey.com/en/products/detail/qt-brightek-qtb/QBL8RGB25C0/10441180) | • Multiple colors<br>• Only takes a single LED housing instead of 2 | • More expensive<br>• Clear |

**Choice:** Option 2: QTB QBL8RGB60D0-2897 Through Hole LED

**Rationale:** An RGB LED will only take up on spot on the product making it look nicer than if it were two separate LEDS of differing colors. The diffused housing of option 2 hides the electronics inside the LED housing making the product more visually appealing.

#### Blue LED
Using RGB LED

## Button

#### Button 1

| Solution | Pros | Cons |
|-----------|------|------|
![DTS-62N-V](DTS-62N-V.jpg) <br>Option 1<br>Diptronics 113-DTS-62N-V Through Hole Tactile Switch<br>$0.23 each<br>[link](https://www.mouser.com/ProductDetail/Diptronics/DTS-62N-V?qs=gTYE2QTfZfSKTB5KYn%252Brkw%3D%3D) | • Less expensive<br>• Currently have product | • Small size<br>• Not visually appealing |

| Solution | Pros | Cons |
|-----------|------|------|
![D6R10](D6R10.jpg) <br>Option 2<br>C&K D6R10 F2 LFS Through Hole Pushbutton Switch<br>$1.62 each<br>[link](https://www.digikey.com/en/products/detail/c-k/D6R10-F2-LFS/1466347) | • Easy-to-push size<br>• Simple pin layout | • More expensive<br>• Very long lead time |

| Solution | Pros | Cons |
|-----------|------|------|
![KS11R23CQD](KS11R23CQD.jpg) <br>Option 3<br>C&K KS11R23CQD Through Hole Pushbutton Switch<br>$2.84 each<br>[link](https://www.digikey.com/en/products/detail/c-k/KS11R23CQD/332672) | • Easy-to-push size<br>• Eye-catching color | • More expensive<br>• Odd pin layout |

**Choice:** Option 3: C&K KS11R23CQD Trough hole switch pushbutton

**Rationale:** Option 3 was chosen due to the eye catching color and indented contact point, indicating it is a button. Although the cost is higher and the layout is more complicated than the other options, this switch has a shorter lead time than option 2 and is easier to press than option 1.

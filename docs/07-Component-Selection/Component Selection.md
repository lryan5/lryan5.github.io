---
title: Component Selection
---

# IR Sensor
## Photo Transistor
| Solution | Pros | Cons |
|-----------|------|------|
![BPW34](BPW34.jpg) <br>Option 1 <br>Vishay BPW34 Through Hole Photo Transistor <br>$1.23 each <br>[link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/BPW34/1681149) | * Small Size <br> * More precise distance  | * More expensive <br> * Higher viewing angle

| Solution | Pros | Cons |
|-----------|------|------|v
![BPW96B](BPW96B_sml.jpg) <br>*Option 2 <br> *Vishay BPW96B Through Hole Photo Transistor <br> *$0.95 each <br> [link](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/BPW96B/4071185?s=N4IgTCBcDaIEIAUDqBOAbHEBdAvkA) | *Less expensive <br> *Lower Viewing angle | *Less precise distance <br> *Large size

| Solution | Pros | Cons |
|-----------|------|------|
![OPB732](OPB732.jpg) <br>Option 3 <br>TT Electronics OPB732 Through Hole IR LED <br> $4.61 each <br>[link](https://www.digikey.com/en/products/detail/tt-electronics-optek-technology/OPB732/1637069) | • Currently have 1 device<br>• Setup is known | • Short viewing distance<br>• More expensive |

**Choice:** Option 2: Vishay BPW96B Through Hole Photo Transistor

**Rationale:** For our products operation we don’t need a precise distance calculation. As long as the IR sensor can detect an object within a set range, the product’s operation can be activated. Also, option 2 will be able to pick up the signals we want without interference due to its lower viewing angle. Option 2 is less expensive than the other choices, allowing our customers to pay less for the finished device.


## IR LED
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

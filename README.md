# XXL_ButtonBox (WIP)

![](images\PXL_20260126_205109274.MP.jpg)

## Parts

| Item               | Variant                                   | Price  | Units<br/>needed | Total Price | Link                                                  |
|--------------------|-------------------------------------------|--------|------------------|-------------|-------------------------------------------------------|
| Square Buttons     | Red¹ - 6.3V - 1NO1NC - Momentary Reset    | 0,33€  | 12               | 3,96€       | https://de.aliexpress.com/item/1005006677441335.html  |
| Square Buttons     | Blue¹ - 6.3V - 1NO1NC - Momentary Reset   | 0,33€  | 12               | 3,96€       | https://de.aliexpress.com/item/1005006677441335.html  |
| Square Buttons     | Yellow¹ - 6.3V - 1NO1NC - Momentary Reset | 0,33€  | 12               | 3,96€       | https://de.aliexpress.com/item/1005006677441335.html  |
| Mini Buttons       | Black                                     | 2,79€  | 4                | 2,79€       | https://de.aliexpress.com/item/4000638162034.html     |
| Mini Buttons       | White                                     | 2,79€  | 4                | 2,79€       | https://de.aliexpress.com/item/4000638162034.html     |
| Self-Rest Switches | Red MTS-123 - 5pcs                        | 2,59€  | 4                | 2,59€       | https://de.aliexpress.com/item/1005003560952632.html  |
| Switch             | ---                                       | 2,45€  | 1                | 2,45€       | https://de.aliexpress.com/item/32809087410.html       |
| Potentiometer      | 1K Ohm                                    | 2,55€  | 1                | 2,55€       | https://de.aliexpress.com/item/1005006659172507.html  |
| Rotary Encoder     | 20MM Plum handle                          | 2,85€  | 4                | 2,85€       | https://de.aliexpress.com/item/1005005983134515.html  |
| Caps               | White                                     | 1,35€  | 5                | 1,35€       | https://de.aliexpress.com/item/1005005983134515.html  |
| ABS Box²           | 290-210-100mm                             | 23,79€ | 1                | 23,79€      | https://de.aliexpress.com/item/1005005728138924.html  |
| Arduino Pro Micro  | 1PCS-32U4-TYPE-C                          | 5,49€  | 2                | 10,98€      | https://de.aliexpress.com/item/1005008999310880.html  |

Some of the items already come in packs, if it's not the case I would anyway buy 1-2 extra in case of a broken item.  
When ordering every "Choice" product at once you should be way above the free shipping order value (for Germany it's 10€), so in theory you only have to pay shipping for the buttons.

¹ = When ordering from this seller try asking if you can order in one color and after that send a message with the colors you actually want. Doing this can save a few bucks of shipping coast.  
² = The price of the box can vary very much, with some luck and coupons this can be below 20€. If you have a 3D printer you of course can print a box yourself.

## Tools
- Soldering Kit + Tools
- Wires
- Solder
- Drill (not needed when 3D printing a box)

## Notes
During the building I adjusted some of the wiring, but the wiring scheme shows what I am using at the end.  

At first I wanted to use an Arduino Mega because a Pro Micro doesn't have enough pins, but I didn't manage the Mega to be recognized as a joypad in windows because it's missing an important component (yes I tried using UnoJoy). 
Because of that I ended up using two Pro Micros, one for all the buttons and switches and one for the encoder.

## Wiring

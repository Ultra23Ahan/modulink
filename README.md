## This specific repository is for the motor part of modulink.

What modulink is:

# ModuLink

ModuLink is a 90% 3d printed and modular system. It is a system of motors, gears, gearboxes, and many other components that can be used to create anything your heart desires.

# Usage Instructions

Make anything you want!

## Features

- Modular design
- Easy to assemble(Mostly)
- Easy to disassemble
- Easy to modify
- Easy to print
- Easy to use

## Components

### Motors

Motors are the main components of the ModuLink system. They are used to move the gears and gearboxes. The motors use a planetary gearbox, which leverage a few weak DC motors to create a stronger and more torque-ful motor.

### Gears

Gears are just standard gears. They are used to create the gearboxes. The motors rotate the gears.

### Gearboxes

Gearboxes are made up of gears, and the outer frame which holds the gears. The gearbox can be used to trade torque for speed, or vice versa. You can only have both if you have some small DC motors that produce more torque than the original intended ones.

## Why I made this

I wanted to make use of the random DC motors I owned so that I could create gear systems for my future projects and other random stuff, and I thought it would be fun to make a modular system that I could use to build anything I wanted.
I learnt about a planetary gearbox(from the [Torospin - Ruco by Kocyns](https://makerworld.com/en/models/2257094-torospin-ruco)) which can increase or decrease torque depending on where you rotate it from, and thus created this.

Images of the CAD designs:
![](/images/readme/1.png)
![](/images/readme/2.png)

BOM(Bill of Materials) for this project:

| Item Name                                                                    | Purpose                    | Misc. Notes                                                                                                                    | Price (1u INR) | Price (1u USD) | Quantity | Link                                                                                             | Shipping (INR) | Final Price (INR) | Final Price (USD) | Total Price (INR) | Total Price (USD) |
| ---------------------------------------------------------------------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | -------------: | -------------: | -------: | ------------------------------------------------------------------------------------------------ | -------------: | ----------------: | ----------------: | ----------------: | ----------------: |
| SONY VTC6 18650 3000mAh Li-ion Battery                                       | Batteries                  | This might seem like overkill but if I have a good battery I can optimize it for worse batteries. It also has better capacity. |            699 |    7.396042739 |        2 | https://robu.in/product/sony-vtc6-18650-li-ion-3000-mah-battery/                                 |              0 |              1398 |       14.79208548 |              1760 |       18.62235483 |
| 2S 20A Balance Version Li-Ion BMS 18650 Lithium-Ion Battery Protection Board | BMS                        | N/A                                                                                                                            |             99 |    1.047508199 |        1 | https://makerbazar.in/products/18650-bms-lithium-battery-protection-board?variant=48251033059568 |             60 |               159 |       1.682361653 |                   |                   |
| 18650 × 2 Battery Holder with Cover and On/Off Switch with DC Jack           | Battery holder             | N/A                                                                                                                            |             77 |   0.8147285993 |        1 | https://robu.in/product/18650-x-2-battery-holder-with-cover-and-on-off-switch-with-dc-jack/      |              0 |                77 |      0.8147285993 |                   |                   |
| 2S 8.4V 2A 18650 Lithium Battery Charger Module Type-C                       | For charging the batteries | N/A                                                                                                                            |            126 |    1.333192253 |        1 | https://robu.in/product/2s-8-4v-2a-18650-lithium-battery-charger-module-type-c/                  |              0 |               126 |       1.333192253 |                   |                   |

This is the BOM for me, but it may be different for you as I already own the motors, and you may own some of these such as the batteries, thus this is not a comprehensive BOM that works for everyone. This BOM is also available as [a file](./BOM.csv)

Notes:
No PCB file as there are no PCBs(custom) for this project.
No guide for attaching componenst as this is just the inside of the motor and those instudtions will be there in the repo for the motor shell.

## Wiring

![](/images/readme/wiring.jpeg)

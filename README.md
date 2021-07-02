# Two Tree's Bluer V2

### Currennt mods from stock
- [X] Installed
- [ ] Planned

### Status
- [X] PEI magnetic sheet
- [X] BLTouch
  - [X] [Bed springs replaced with solid spacers](https://www.aliexpress.com/item/1005001334825937.html)
- [X] [Raspberry Pi 4B](https://www.pishop.us/product/raspberry-pi-4-model-b-4gb/)
  - [X] [5V Power Supply](https://www.amazon.com/gp/product/B07S9G8SG5)
    - [X] mounted on side of case with industrial strength velcro (works great)
  - [X] [Raspberry Pi camera V2](https://www.pishop.us/product/raspberry-pi-camera-module-v2/)
    - [X] [Camera Mount](https://www.thingiverse.com/thing:2845586)
    - I need to find a different camera mount
    - I don't like the location of this one
    - [ ] [BLTouch needs a cover as the light is too bright for the camera](https://www.thingiverse.com/thing:4634422)
  - [ ] [5V LED Lights](https://www.amazon.com/gp/product/B091T2GHFD)
- [X] [MKS Robin Nano V3](https://www.aliexpress.com/item/1005002074259790.html)
  - [ ] Raspberry Pi GPIO direct connected to board
    - [ ] Move Raspberry Pi underneath if I can get the direct connect worked out
    - I tried to get this working during install but was unable to
    - I am concerned about how well WiFi will work underneath in an all metal case
  - [X] Extra USB removed so board can be used w/o modifying case
  - [X] TMC2209 stepper drivers
- [X] [Klipper Firmware](https://www.klipper3d.org/)
  - [X] [Moonraker](https://github.com/Arksine/moonraker)
  - [X] [Fluidd UI](https://github.com/cadriel/fluidd)
- [X] [V6 Hotend](https://www.aliexpress.com/item/4000054903441.html)
  - [X] [Makeshift cooling system](https://www.thingiverse.com/thing:4602733)
  - [ ] [Migrate to titan extruder that is on my E3 currently](https://www.thingiverse.com/thing:3769819)
    - This is printed but not installed. I really like this cooling system
- [ ] [Chain Link going up to bed](https://www.thingiverse.com/thing:4842636)
  - Before I stumbled upon this I was concered the wires from the bed would be a wear point for failure
- [ ] This printer really needs a cable management sysetem
  - I have yet to find a cable management system for the Bluer that seems practical/decent
- [ ] [Belt driven dual Z axis single](https://github.com/kevinakasam/BeltDrivenEnder3)
  - This is the last big upgrade I have planned
- [ ] [Fysetc S6 if/when the Nano V3 dies](https://www.aliexpress.com/item/4000345369228.html)
  - I had a [MKS Robin E3P](https://www.amazon.com/gp/product/B08PHG78FZ/) have a critical failure on my Ender 3 that could have burned my house down
  - A MOSFET on the board died and fell max AMPS to the hotend under I physically shut off power to the printer
  - When it was turned back on again, before the firmware could boot up, the same behavior continued
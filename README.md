# Clock Divider (Binary)

This module reduces a clock signal by powers of two.

This is an original design featuring a three-layer stackup with a front face, a layer for all the jacks, and a power/processing layer where all the SMD components are layed out.

As with other modules in this line, this mult features:
* Polarity protection so that a backward power header doesn't fry anything (twin series schotty diodes: BAT54SL),
* Full surface mount design.

The KiCAD project here uses the library/footprints [found in my companion repo](https://github.com/thismatters/EurorackKiCAD).

## Width

11hp on an [Intellijel 1U rack](https://intellijel.com/support/1u-technical-specifications/).

## Inputs

Jacks:
* Input
* Reset

## Outputs

There are 6 output jacks each outputting a clock signal reduced by the labeled fraction.

## Adjustment

No adjustment required.

## Vendors

There are part numbers in the [BOM](clkdiv.csv) for many of the parts (not for basic passives though) at the following vendors:

* [Mouser](https://www.mouser.com): Needs no introduction. Get your ICs from here (or [digikey](https://www.digikey.com)).
* [Tayda Electronics](https://www.taydaelectronics.com/): Good supplier for passive components; audio jacks, and potentiometers. Their audio jacks are slightly smaller than the thonkiconn from thonk.
* [Love My Switches](https://lovemyswitches.com/): Has [really good knobs](https://lovemyswitches.com/anodized-aluminum-knob-the-lo-fi-1-4-smooth-shaft-12-5mm-od/) to go on those potentiometers!
* [OSHPark](https://oshpark.com/): Fast and (relatively) cheap PCB manufacturer.
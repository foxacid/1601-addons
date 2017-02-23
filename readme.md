## 1601 Clone Add-Ons

This repository contains a front panel design and divider add-on (circuit design by [Matthias Herrmann aka Fonik](http://www.modular.fonik.de/)) for the [1601 clone project by Kipling](https://www.muffwiggler.com/forum/viewtopic.php?t=110640).

## One Thousand Six Hundred and One Panel 

Just like the [TTSH](http://www.thehumancomparator.net/) panel, this 1601 front panel design is inspired by the ARP 2600 'Grey Meanie' layout and colour scheme. The layout fits Kiplings 1601 clone PCBS Rev 1-3. Additionally there is a provision for 6 extra jacks above the power switch to accomodate the Clock Divider add-on.

![Panel](/docs/ttsh_style_panel.png?raw=true)

## Divider PCB

The Clock Divider is based on an original Design by Matthias Herrmann [Original Schematic](http://www.modular.fonik.de/pdf/SimpleDividerSCH.pdf) that has been updated for mostly SMD components (SOIC, SOT23, 0805). The clock-divider folder contains the Eagle source files and Gerbers generated with [Seeed Studio](https://www.seeedstudio.com/) design rules. It contains only board mounted components and requires a unipolar +15V power source.

There is a provision for normalising Gate Output 2 to the divider's clock input. It's up to the builder to decide this. There are also provisions for LED indicators and a manual Reset button. Those are not present on the panel.

Caveat emptor: PCB design v0.9 is currently being manufactured and therefore **untested**.

![PCB bottom](/docs/divider_bottom.png?raw=true) ![PCB top](/docs/divider_top.png?raw=true)

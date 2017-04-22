# 1601 Clone Add-Ons

This repository contains a front panel design and divider add-on (circuit design by [Matthias Herrmann aka Fonik](http://www.modular.fonik.de/)) for the [1601 clone project by Kipling](https://www.muffwiggler.com/forum/viewtopic.php?t=110640).


## One Thousand Six Hundred and One Panel 

Just like the [TTSH](http://www.thehumancomparator.net/) panel, this 1601 front panel design is inspired by the ARP 2600 'Grey Meanie' layout and colour scheme. To match the TTSH, the text is set in 9pt Helvetica (white on RAL 7016 Anthrazitgrau).

The layout fits Kiplings 1601 clone PCBS Rev 1-3. Additionally there is a provision for 6 extra jacks above the power switch to the right to accomodate the Clock Divider add-on.


![Panel](/docs/ttsh_style_panel.png?raw=true)


## Divider PCB

The Clock Divider is based on an [original design by Matthias Herrmann](http://www.modular.fonik.de/pdf/SimpleDividerSCH.pdf) - thanks Matthias! The clock-divider folder contains the EAGLE source files and Gerbers generated with [Seeed Studio](https://www.seeedstudio.com/) design rules. A unipolar +15V power source is required.

There is a provision for normalising Gate Output 2 to the divider's clock input. There are also provisions for LED indicators and a manual Reset button. Those are not present on the front panel.

 - - - -
**Caveat emptor: PCB design v0.9 is currently untested.**
 - - - -

### PCB

![PCB bottom](/docs/divider_bottom.png?raw=true) ![PCB top](/docs/divider_top.png?raw=true)


### Bill of Materials

Name                 |  Value       |  Package 
-----------------    | ------------ | ------------
***Capacitors***     |              |         
C1                   |  100uF       |  Radial, 2.5mm spacing                         
C2                   |  0.1µF       |  0805    
C3                   |  0.1µF       |  0805    
C5                   |  0.01µF      |  0805   
***Semiconductors*** |              |         
D1-D4                |  1N4148      |  DO35 
Q1-Q7                |  BC850       |  SOT23
IC1                  |  4024D       |  SO14    
IC2                  |  4069D       |  SO14    
***Resistors***      |              |        
R1                   |  47K         |  0805    
R2                   |  10K         |  0805    
R3                   |  47K         |  0805    
R4                   |  100K        |  0805    
R5                   |  100K        |  0805    
R6                   |  10K         |  0805    
R7                   |  10K         |  0805    
R8                   |  47K         |  0805    
R10                  |  2K2         |  0805    
R11                  |  1K          |  0805    
R12                  |  2K2         |  0805    
R13                  |  2K2         |  0805    
R14                  |  1K          |  0805    
R15                  |  2K2         |  0805    
R16                  |  2K2         |  0805    
R17                  |  1K          |  0805    
R18                  |  2K2         |  0805    
R19                  |  2K2         |  0805    
R20                  |  1K          |  0805    
R21                  |  2K2         |  0805
***Jacks***          |              |    
CLOCK                |  PJ301BM     |  Thonk Jack     
RESET                |  PJ301BM     |  Thonk Jack   
F/2                  |  PJ301BM     |  Thonk Jack         
F/4                  |  PJ301BM     |  Thonk Jack         
F/8                  |  PJ301BM     |  Thonk Jack         
F/16                 |  PJ301BM     |  Thonk Jack         

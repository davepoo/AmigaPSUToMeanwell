# Amiga PSU To Meanwell
KiCad design for a PCB for a board to mount a Meanwell RT50-B PSU inside an external Amiga PSU A300/600 case.

# Known case compatibility:
A300/600 Power Supply - P-No: 391029-02

Its possible that this design also works in the A1200 PSU but i don't have one to verify that.

![Picture of front of PCB](https://github.com/davepoo/AmigaPSUToMeanwell/blob/master/KiKadAmigaMeanwell/Renders/FrontBackV101.jpg)

# A600 PSU Variants

There are 5 variants of the A600 PSU listed in the service manual, I have only tested the -02 variant (UK Plug), but i would imagine that all these other variants are mechanically the same, so would probably work just as well with this adaptor

![A600 Service Manual](https://archive.org/details/A600_System_Schematics_1992-04_Commodore/page/n9/mode/2up)

PSU Part numbers:

* 391329-01
* 391329-02 - UK Plug (240V)
* 391329-03
* 391329-04
* 391329-05

# A500+ PSU possibly is compatible?

From visual appearances (i don't have one to look at in person), it is possible the A500+ PSU might be mechancially identical to the A600 PSU and therefore might also be compatible with this PCB.

![A500+ Service Manual](https://www.amigawiki.org/lib/exe/fetch.php?media=de:models:a500plus_service_manual_2014.pdf)

PSU Part numbers:

* 321503-01
* 321503-02 - UK Plug (240V)
* 321503-03
* 321503-04
* 321503-05

# Parts
The PCB was designed for these connecters, by any suitable 2.54mm pitch connectors will do the job.

* Molex, KK 254, 6410, 2 Way, 1 Row, Straight PCB Header - https://uk.rs-online.com/web/p/pcb-headers/4838461/
* Molex, KK 254, 6410, 5 Way, 1 Row, Straight PCB Header - https://uk.rs-online.com/web/p/pcb-headers/1707104/

# YouTube
* Meanwell PSU To Amiga Adpator PCB v1.01 Changes - https://youtu.be/RRZ41WjXUbk
* Meanwell PSU To Amiga Adpator PCB Design in KiCad - https://youtu.be/qDFmNK3edf4

# PCBWay 
The v1.01 board is shared on PCBWay where i got the prototypes manufactured 

https://www.pcbway.com/project/shareproject/A600_PSU_to_Meanwell_RT50_B_Adaptor_board.html


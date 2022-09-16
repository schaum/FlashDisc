# FlashDisc

You can view the interactive BOM of the Flashdisc by an interpreter like this: 

http://htmlpreview.github.io/?https://github.com/schaum/FlashDisc/blob/main/FlashDisc-BOM.html

## PCB Version 3 Fixes

The PCB of version 3 needs some fixes. The micro-processor needs to be decoupled from the motor-driver next to it. Cut the two 5V supply-tracks of the chip with a sharp knife and connect the power of the chip to 5V on the board as far as possible from the motor driver with some wire, for example to the small pad marked here with a green dot:

![PCB-v3-fix](KorrekturPCB-V3.jpg)
# Xbox 360 Corona-4GB-NAND-Extension-QSB
A QSB Board to help protect the fragile tiny Header Pads of the Corona 4GB NAND

We have all been there.  Hurrying too fast and a wire gets pulled and rips up a pad.
For new folks soldering, I can take a long time to develop the patience and control to not rip up solder pads.

To help out with Flashing the 4GB Nand on Xbox 360 Corona Boards, this QSB provides larger and strong solder pads for the programmer.

This QSB was designed to work with 4GB Nand eMMC Programmers designed by [@Element18592](https://github.com/Element18592) (He is a huge inspiration for me)
It has the color of wires to use with the Xflasher-360 and also the number values that will be used with a SD Tool V2.2 or the 4GB USB Tool
https://themodshop.co/shop/hardware.html

This QSB will also work perfectly with the PicoFlasher.   WeekendModder has a great diagram for this - https://weekendmodder.com/picoflasher.html

** Make sure to use lots of flux.  Also do not hold your iron on the board for more than 2 seconds at a time

To solder the Header portion to the Xbox 360, Align the board up with the markings and apply heat one of the header pads on the xbox 360.
Apply solder so it melts to this pad, when you have enough solder melted, drag your iron along the pad to the QSB and hold it next to the QSB.
The Solder will jump and make a bridge between the pads and the QSB

![image](https://user-images.githubusercontent.com/70423454/155852250-eef964d4-2525-4463-a301-cab1ad949bdb.png)

![image](https://user-images.githubusercontent.com/70423454/155852265-2fb41352-2d71-4396-be04-8865dee1d20b.png)

The above Nand Extension QSB will work perfectly with the PICO but it does have extra pads that the PICOFlash does not use.

To help with this, we also have a PICO Edition which has only the required pads and only requires 5 wires to be soldered.

![image](https://user-images.githubusercontent.com/70423454/157532132-eafd329e-1cf8-4137-afca-641a41d8559d.png)

I recommend OshPark if you are in the United States to order the boards if you only need a small batch.  
JLCPCB is also a great choice and can do larger batches for less.  Shipping is also cheaper if you can wait for the slow boat.  :)
I recommend 1 mm for the board width but it is not critical.

There is an optional 0805 SMD LED pad and companion 0805 SMD resistor pad that will light up when the power is plugged in.
It will not impact any flashing with or without but looks nice.  (ง •̀_•́)ง

It is recommended to use a fine soldering bit as the pads are small. Size 900M-T-I is a great choice.

I welcome all feedback and critiques as I alway strive to make products easier and the experience better for everyone.

Check out my modding adventures at https://www.facebook.com/GeekIslandGaming

Special thanks to Weekend Modder and Xtralife Mods for the support!!

https://www.facebook.com/ExtraLife-Modification-Services-103652372230020

Product is Licensed but can be used free for Commerical Use.  Just please don't make changes to the Gerber Files.
https://www.gnu.org/licenses/gpl-3.0.txt

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=97YFBJX4NXA8W)

**--Change Log--**
3/10/2022 
- Found that the silkscreen on the PICO Edition had the Orange Pad marked as GP9 instead of GP7.  Changed to match Weekend Modders Color Scheme.
- Released V2.6 Gerbers to include these changes.

3/9/2022 
- My Gerber Export had the title border included which made OSHPark think the entire sheet was to be printed.  This has been fixed and confirmed working
- Added a Green/GP21 Pad on the Pico Edition that can be soldered to the Xbox 360 and then to the PICO.

2/28/2022 
- Added SilkScreen lines to help align the pads on the Xbox 360.
- Added a Ground Plane on the top and bottom of the board.
- Version 2 Official Released.  Created a release on GitHub.

2/26/2022 - Added to the SilkScreen "the PicoFlasher" as it will works with this QSB Board (Colors are the same too)  :D

2/25/2022 - Moved the C up to the top with Green.  Changed Geek Island Logo.


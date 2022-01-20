# 24 pin to 26 PIN FFC Adapter
24 pin 1.25mm to 26 pin 1.00mm F-F FFC Floppy Adapter

# NOTE:  THIS IS CURRENTLY IN DRAFT

## Background:

This is a FFC adapter to adapt older 24 pin 1.25mm FFC floppy systems (Korg, Tandy 1100FD, etc) to a current 26 pin 1.00mm FFC floppy drive.  The 1.25mm floppy drives were all belt driven, and the difficulty of finding belts and replacing them dictates that many people refurbishing older equipment would benefit from just swapping out the drive for a 1.00mm servo-driven floppy drive (i.e. one that doesn't need a belt).

So, I made this adapter to allow people to use their older equipmetn with a more current 1.00mm floppy drive.

## Pinout

Tandy 1100FD 24 pin pinout: http://www.acrpc.net/documents/1100FD_drive.PDF

Teac 26 pin Floppy drive pinout: http://www.bitsavers.org/pdf/teac/FD-05HF-8830.pdf  (page #5)

| 26 Pin #	| 24 Pin #	| Pin Description |
| :- | :- | :- |
| 1	| 1	| VCC	|
| 3	| 2	| VCC	|
| n/c	| 3	| n/c |	
| 5	| 4	| VCC |	
| 5	| 5 | VCC	(tie together) |
| n/c |	6 |	n/c |	
| 15 | 7 | GND |	
| 17 | 8 | GND	|
| 26 | 9 | /SIDE1	|
| 23 | 10	| GND	|
| 24 | 11	| /RDATA |	
| 22 | 12	| /WPT |
| 20 | 13	| /TRK00 |
| 18 | 14	| /WGATE |
| 25 | 15	| GND	(tie together) |
| 16 | 16	| /WDATE |
| 25 | 17	| GND	(tie together) |
| 14 | 18	| /STEP	|
| 12 | 19	| /DIR |
| 10 | 20	| /MOTENABLE |	
| n/c	| 21 |	n/c	|
| 4	| 22 | /DRVSEL |
| 2	| 23 | /INDEX	 |
| 6	| 24 | /DSKCHG	|

### Unused pins:

On the 26 pin connector, pins 7, 11, 13, 19, and 21 are not connected. Pin #8 (READY) and pin #9 (HD OUT/MEDIA) on the 26 pin connector are not connected to the 24 pin connector.

## PCB Printing & BOM:  

### PCB Printing
OSH Park, Seeedstudio, PCBWay, etc, can print the PCBs for you.  Simply upload the zip file from this repository.  
* [OSH Park](https://oshpark.com/) is very inexpensive for users in the USA to get three boards made quickly.  
* [SeeedStudio](https://www.seeedstudio.com/fusion.html) allows you to get 10 boards for US $4.90 plus shipping
* [PCBWay](http://www.pcbway.com) also is a great board house

### BOM
TBD

## Usage
Please see the attached license.  Feel free to use and remix as needed.

## Donations
Are not needed, but feel free to send me some coffee money or something **$acadiel** on Cash App or **acadiel** on Venmo.


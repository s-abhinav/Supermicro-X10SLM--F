================================================
FOR <filename>.zip
================================================
	1. Save this file to your computer.

	2. extract the files to a DOS bootable device (such as a bootable USB stick, or CD).

	2. Boot to a DOS prompt and type AMI.BAT BIOSname.###.

	4. Do not interrupt the process until the flashing is complete.

	5. After you see the message of BIOS has completed the update, unplug the AC, clear the CMOS and plug in the AC and power on the system.

	6. Go to the BIOS setup screen and press F9 to load the default and press F10 to save and exit.
	



================================================
Super.ROM (see user's manual for details)
================================================
Recovery Bios from a USB Device/Drive

If the BIOS fi le is corrupted and the system is not able to boot up, this feature will
allow you to recover the BIOS image using a USB-attached device. A USB Flash
Drive or a USB CD/DVD ROM/RW drive may be used for this purpose. Please note
that a USB Hard Disk drive is NOT supported at this time. Follow the procedures
below recover the BIOS.


1. Using a different system, copy the "Super.ROM" binary image file

   into a USB fl ash device or a writable CD/DVD disc's Root "\" Directory.


2. Insert the USB device that contains the new BIOS binary image (¡§super.rom¡¨)
 
   and power the system down.

3. While powering on the system, press and hold <Ctrl> and <Home> simultaneously

   on your keyboard until the USB device's LED indicator comes on. This

   will take a few seconds or up to one minute.

4. Once the USB device's LED is on, release the <Ctrl> and <Home> keys. The

   system may generate beep codes to indicate that the BIOS ROM fi rmware

   is being reprogrammed. The screen will also display a message as shown

   below. DO NOT INTERRUPT THIS PROCESS!

5. When the Boot Sector Recovery Process is complete, the system will reboot

   automatically

6. When DOS prompt appear, please type AMI.BAT BIOSname.###.

7. Do not interrupt the process until the flashing is complete.

8. After you see the message of BIOS has completed the update, unplug the AC, clear the CMOS and plug in the AC and power on the system.

   then press F1 to go to the BIOS setup screen and press F9 to load the default and press F10 to save and exit.






** If the BIOS flash failed, you can contact our RMA dept. to have the bios chip reprogrammed.
This will require shipping the board to our RMA dept. for BIOS reprogramming.  
The RMA dept's email address is rma@supermicro.com





BIOS Name = PPPPPSSY.MDD

*********Here is a New BIOS Naming Convention****************

BIOS name     : PPPPPSSY.MDD

PPPPP          : 5-Bytes for project name

SS                 : 2-Bytes supplement for PPPPP

Y                   : Year,  9 -> 2009, 0-> 2010, 1->2011

MDD               : Month / Date



E.g. BIOS Build Date: 2010/1/15

X8ST3-F -> X8ST30.115

X8SIL-F -> X8SIL0.115
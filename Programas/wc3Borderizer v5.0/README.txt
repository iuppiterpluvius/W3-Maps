================================================================
wc3Borderizer v5.0
Author: Cohadar 
Date: 2008.11.04
================================================================
This program requires java >= 1.5 to work properly
================================================================


================================================================
DISCLAIMER

This program is distributed as is. You use it at your own risk.
The creator is not liable for any damage, data loss, loss of
profits or any other kind of loss or damage while using this
software. It has been tested thoroughly and scanned for viruses.


================================================================
DESCRIPTION

wc3Borderizer creates default bordered icons for game warcraft 3.
Input files are read from "input" directory.
Input files can be any GIF, PNG, JPEG, BMP or TGA images.
Input files are automatically resized.

Output files will be in standard wc3 texture format - BLP
BLP's will be created inside "ReplacableTextures" directory
If directory does not exist it will be created automatically.


================================================================
INSTALLATION

Simply drop the files included in this archive in a folder
and it's ready to use.

Note that this tool is using border images from borders folder,
if you change those images program output will change.

Also note that WC3B.jar is not sealed and that source is included.


================================================================
USAGE

Windows users:
Put the images you want to borderize inside "input" directory
click on the wc3Borderizer.bat

Linux and Mac users:
Put the images you want to borderize inside "input" directory
Give wc3Borderizer.sh executable privileges
click on the wc3Borderizer.sh

Note:
On some systems it is possible to run the program by directly clicking
onto WC3B.jar


================================================================
ADVANCED
Borederizer has two options: <java -jar WC3B.jar -j -s>
-j generate jpeg files (for easy output preview)
-s generate bonus shaded versions of Command and Autocast buttons

You can delete this options from wc3Borderizer.bat or wc3Borderizer.sh
if you don't need them


================================================================
CREDITS & REFERENCES

I would like to thank:

PitzerMike for his help on finding some important code and documentation

Anthony Dekker for his Neural Network Quantizator
URL = http://members.ozemail.com.au/~dekker/NEUQUANT.HTML

Reality Interactive for their free TGA decoder
URL = http://www.realityinteractive.com 


================================================================
CHANGES
v5.0 
   Switched from command line to GUI interface

v4.2
   Passive buttons now have standard PASBTN prefix
   Infocard icons now have standard infocard- and infocard-neutral- prefixes
   Borderizer now also generates Disabled passive buttons DISPASBTN

v4.1
   Fixed flipped TGA problem

v4.0
   Removed BLPaletter dependency == full platform independence
   Increased java dependency from 1.4 to 1.5
   Restored BMP support
   Added TGA support

v3.1
   Added parameter routing to BLPaletter

v3.0
   wc3b can now process multiple files at one.
   reduced java dependancy from java 1.6 to java 1.4(and above)

v2.2
   fixed .jpg issue
   dropped support for .bmp - bmp files make too much problems
   Made totally new algorithm for disabled icons 
   to make them look more like in game ones.
   Better demo.

v2.1
   Some improvements for Mac users

v2.0
    Add infocard border generation

v1.0
    Added shaded versions for BTN and autocast BTN.

v0.1
    Basic borders support


================================================================
CONTACT

Make bug reports in the editing tools forum at
http://www.wc3campaigns.net
You may also write me an e-mail to cohadar@yahoo.co.uk

Cohadar
# Cromemco SBASIC Guest Book
I developed this simple application on my Cromemco Z-2D computer in prepartion for the Vintage Computer Festival Midwest 18 (which took place Sept 9-10, 2023). I wanted to make something that would demostrate using the computer at the show, and would write data back to the accompanying Cromemco HDD-11 (IMI 7710) hard drive. This guest book application worked really well and I ended up with 65 signatures (although a couple were tests/dups - I'll just leave them). There were even a few youtube-famous content creators that stopped by to sign the guest book - see if you can spot them..

# The program
The code ended up being just a little over 100 lines of BASIC code. If found the book ["An Introduction to Strucutred BASIC for the Cromemco C-10"](https://deramp.com/downloads/mfe_archive/010-S100%20Computers%20and%20Boards/00-Cromemco/40-Cromemco%20Software/SBASIC%20Structured%20Basic/An%20Introduction%20to%20Structured%20BASIC%20for%20the%20Cromemco%20C-10.pdf) to be very helpful while learning the particulars of this flavor of BASIC. Especially the "Files" chapter and sections on reading & writing sequential file structures. The book offered some good example code and it didn't take long adopt these examples into making a usable guest book application.

# Files
* **GUESTBK.BAS**: This is the save file from SBASIC of the program source code itself. Interestlying, this is a binary file format - not just a text file of the BASIC code. I must be loaded with the SBASIC.COM editor
* **GUESTBK.TXT**: This is a text dump of the source code which can be viewed from any computer.
* **GUESTBK.DAT**: This is the actual data file that was written to as the signatures were added. It is also a binary format, and can be read/written to using GET & PUT BASIC functions.
* **ENTRIES.TXT**: This is a dump of all the guest book entries collected at VCFMW.

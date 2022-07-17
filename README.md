# compileit-xcmds
CompileIt source code for a bunch of HyperCard XCMDs from the late 90ies.

# Prerequisites
To build this, you need

* HyperCard 2.4.1 (earlier versions of 2.x may work too)
* CompileIt 2.6.1 (You can get [CompileIt!](http://ittybittycomputers.com/IttyBitty/CompileIt/index.html)
  from the [original author's web site](http://ittybittycomputers.com/))
* A Mac to run it on (or an emulator like Basilisk II or SheepShaver)
* StuffIt 5 to unpack the `.sit` files
* The HyperCard stack in the `CheapVersionControl.sit` archive in this repository
  to copy the files back from the data fork into the resource fork, and
  to convert the source files back from UTF8 with LF to MacRoman with CR line endings.
  (Its "Revert" button can be used to do this, but you may have to tell your Mac that the
  c! files are `TEXT` files using ResEdit or PC Exchange)
# HsF2012
Files to bring HsForth for DOS into closer compliance with ANS/ISO Forth (but not completely)

This code is here for those few who may have an interest in using HsForth by the late James Kalihan, of Springboro Ohio
but want a system that uses more ANS Forth word names than those used by the original HsForth.

HSForth was a fast full featured system for DOS at the time when Intel still used the segmented archictecture. 
HsForth was made to allow the programmer to break the 64K/16 bit barrier by dividing the system in a CODE segment for Assembler words,
a LISTS segment for threaded code, a Forths segment for the name dictionary and a separate stack segment for the parameter 
and return stacks.

I have written the LIB\ files here so they can create a new HsForth system if you have the HsForth Kernel.
The end result will be HSF2012.EXE which includes the assembler and a lots free space to play with.

INSTRUCTIONS:
------------

1. In your HsForth root directory create a folder called LIB

Assumed directory:
       ...\"anydir"\HSFORTH.EXE

       ...\"anydir"\LIB\...
                       ALL SOURCE FILES...


2. Move all the hsf2000 files to the directory ..\LIB\

3. Start the HSFORTH kernel called HSFORTH.EXE from the directory that contains \LIB\

4. In the HSFORTH console type:  FLOAD FORTH12.HSF
   a) the HsFORTH Path will be set to \LIB by this file so everything will load correctly

5. Press enter key when prompted by the compiling process.

6. When the compile completes, start the program at the command line with:   HSF2012 <enter>


HSF2012.EXE is NOT compatible with the HSForth Auto Optimizer NOR any other original HsForth source files

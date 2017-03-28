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

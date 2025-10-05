# EDSAC_FORTH
FORTH for EDSAC, an OS on the oldest programmable computer

The code here can be run on the EDSAC simulator (google it! but currently at https://www.dcs.warwick.ac.uk/~edsac/)

**If you just want to see it work, you can open "Demo vERRandIMMEDIATEandTAPE.txt" in the EDSAC simulator, and follow the instructions at the beginning of the file.** 

You can read the GOING DEEPER section to try the interpreter REPL.

I wrote this over a year or so intending to make a Jonesforth style doc on how to use it and how it was developed. 
But I haven't cleaned it up yet, so to really use it you'll have to read EDSAC FORTH.txt to see a running thought process as I developed it and how to use it. I hope to fix that.


GOING DEEPER
------------
If you want a taste of the interpreter, run Demo vL8S the same way. After the start demo code runs, you will be in the interpreter.
You open an new file, and this file will be your command line input.
Type "C.GRT.HI.NAM.PCD.RET.E.." and then press "Reset", you have run the standar FORTH equivalent of 
": GREET HI WORD PRINTWORD EXIT ;"
If you then replace the contents of your file with 
"GRT.FOX.."
that will print out 
HI FOX
and wait for more input(because .. means end of line in EDSAC FORTH)

 

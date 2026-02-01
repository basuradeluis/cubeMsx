This a little experiment I did, based on user Tsoding (https://github.com/tsoding) work video, showing how to calculate the depth and project 3-d points on 2-d screen.


I strongly recomend see the great video at  https://www.youtube.com/watch?v=qjWkNZ0SXfo and source code and instructions at
https://github.com/tsoding/formula
where he explains everything.


[![Screenshot_20260201_205125](./imgs/Screenshot_20260201_205125.png)]
[![Screenshot_20260201_205232_run.png](./imgs/Screenshot_20260201_205232_run.png)]

This is a (partial) implementation of his work in MSX-BASIC.
Due to slow cpu, the program does not move or rotate automatically the cube.
You can do it using the keys
+f forward
+b backward
+g rotate one way
+h rotate other way

Keep in mind, this program may have problems. Like poor optimization, no comments and similar things.

##Files
To extract the source, I used "llist" command in OpenMsx

I also include a OpenMsx (saved under Linux) savestate with the program written.
The list of source code was made using "llist" msx-basic command. And the Printer

Also I entered
save "cube1.bas",a
with a "virtual casete", generated. *Although I havent tested*.
Wav file atached.

##Printer configuration

See https://www.msx.org/forum/msx-talk/openmsx/export-basic-listing
Press F10 on OpenMsx.


set printerlogfilename /path/to/store/printer.txt
plug printerport logger
In msxbasic use "llist"




##References:
https://map.grauw.nl/articles/basic_tips_tricks.php

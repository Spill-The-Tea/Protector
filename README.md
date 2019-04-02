# Protector
UCI protocol compatible Chess Engine

## Original Source Code
Can be found on sourceforge, (here)[https://sourceforge.net/p/protector/code/HEAD/tree/]

## Purpose of this Fork
  The Purpose of this fork is to make compilation mac compatible. All changes should be </br>
  relatively non-functional.

## Instructions to Compile Protector on Mac



  
## TERMS OF USE

Protector is free, and distributed under the GNU General Public License(GPL). </br>
Essentially, this means that you are free to do almost what you want with the program, </br>
including distributing it among your friends, making it available for download from your </br>
web site, selling it (either by itself or as part of some bigger software package), or </br>
using it as the starting point for a software project of your own. </br>

Please note that these terms do not apply for the contents of the two files "egbt.cpp" and "tbdecode.h". </br>
These files contain software from a third party (Eugene Nalimov and Andrew Kadatch) and they are not an </br>
integral part of Protector but an optional supplement. The only real limitation is that whenever you </br>
distribute Protector in some way, you must always include the full source code, or a pointer to where </br>
the source code can be found.  If you make any changes to the source code, these changes must also be </br>
made available under the GPL.

For full details, read the copy of the GPL found in the file named Copying.txt.

## COPYRIGHTS

Please note that the sources for the endgame table access from Eugene Nalimov and Andrew Kadatch are NOT </br>
distributed under GPL. In order to use them for any other purpose than building Protector you will need </br>
an own separate permission from Eugene Nalimov and Andrew Kadatch (see the copyright remarks in their </br>
files [egtb.cpp and tbdecode.h] for more details).

## CREDITS

Protector is based on many great ideas from the following people: </br>
Fabien Letouzey (pvnodes, blending of opening and endgame values, eval params), </br>
Thomas Gaksch (pvnode extensions, extended futility pruning, space attack eval), </br>
Robert Hyatt (consistent hashtable entries), Stefan Meyer-Kahlen (UCI), </br>
Gerd Isenberg/Lasse Hansen (magic bitboards), </br>
Marco Costabla/Tord Romstad/Joona Kiiski (Glaurung/Stockfish sources), </br>
Vasik Rajlich/Larry Kaufman (singlemove extensions, op/eg integer arithmetics, values for material imbalances in Rybka/Robbolito) </br>
and Andrew Kadatch/Eugene Nalimov (endgame tablebases). </br>
Without their contributions Protector would not be what it is. Thank you so much.

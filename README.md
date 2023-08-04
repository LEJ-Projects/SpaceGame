# SpaceGame
A 3D space battle simulation written in BASIC for the TRS-80 Model 100 or the NEC PC-8201A.

Revision History:

2023_08_04 Line 4560 was updated in all three versions to replace E2=2 with E2>1 so program exits if there were more than 2 energy banks destroyed.

The list of files is as follows:

Readme.txt:  This file.  (Updated 8/4/23)

SPCGAM.ba.txt:   Commented version of the BASIC program.   This is the version recommended for the online emulator, CloudT.  (Updated 8/4/23)

SGM100.DO:  This is the same as SPCGAM.ba.txt except all comments have been removed except for the first two lines.   This is the version that should be run on the actual hardware for the TRS-80 Model 100 or equivalent (except for NEC).  (Updated 8/4/23)

SG_NEC.DO.  This is the same as SGM100.DO version except all PRINT@z statements were changed to LOCATEx,y:PRINT statements.  Whatever z had been is converted to x and y. (Updated 8/4/23)

SpaceGame.pdf:  A brief history of the game followed by a manual, program description and appendices consisting of a variable list and subroutine list.

CloudT_LoadingInstructions.docx: A word document containing specialized instructions for loading SPCGAM.ba.txt on the online emulator.

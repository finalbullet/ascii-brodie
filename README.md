ascii-brodie
============

Ascii Brodie in BBC BASIC

FACE:

    MODE 4
    VDU 23,240,231,70,22,6,8,0,0,99
    PRINT TAB(20,10);CHR$(240);
    PRINT


SIDE VIEW:

    MODE 4
    VDU 23,240,4,12,27,107,59,7,4,12
    VDU 23,241,4,56,64,96,112,16,16,48
    X=10:Y=20
    PRINT TAB(X,Y);CHR$240;
    PRINT TAB(X+1,Y);CHR$241;
    PRINT


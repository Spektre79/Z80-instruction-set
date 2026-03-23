File z80_iset.dat contains Z80 CPU instruction set database itself.
Its a text file with exact formatting described in z80_iset.txt and can be used for direct load and configuration of Z80 emulation.
It also contains corrected timings down to machine cycles which ease up the contention emulation problems.

I used this for my ZX Spectrum emulator with machine cycle timing precision which allowed more native peripherial emulation without hacks.
Like FDC, AY, etc. using existing firmwares instead of injected data/code based on call addresses etc ...

related SO links:

https://stackoverflow.com/a/18911590/2521214
https://stackoverflow.com/a/19218993/2521214

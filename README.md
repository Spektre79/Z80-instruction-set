File z80_iset.dat contains Z80 CPU instruction set database itself.
Its a text file with exact formatting described in z80_iset.txt and can be used for direct load and configuration of Z80 emulation.
It also contains corrected timings down to machine cycles which ease up the contention emulation problems.

I used this for my ZX Spectrum emulator with machine cycle timing precision which allowed more native peripherial emulation without hacks.
Like FDC, AY, etc. using existing firmwares instead of injected data/code based on call addresses etc ...

related links:

SO related links:

  https://stackoverflow.com/a/18911590/2521214
  https://stackoverflow.com/a/19218993/2521214

ZEXALL exerciser 

  http://mdfs.net/Software/Z80/Exerciser/

Beware above ZEXALL is for 64KB RAM (CP/M like) environment so if you have any ROM present the results will have different checksums.
There is also corrected ZEXALL for original ZX Spectrum 48K out there IIRC its called ZEXFIX

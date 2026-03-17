# Analóg interfész modul

Feladata:
Egy rajta lévő TRS (tip-ring-sleeve) 3.5 mm-es Jack input jelét felerősíti, hogy később az [analóg jelgenerátor modul](./modul-jelgen.md) fel tudja használni, mint bemeneti jel.

A jel először bandpass szűrésen esik át. A felső cutoff 20kHz kell hogy legyen, az alsó pedig 20Hz.

Az erősítés egy TL072-essel történik, az erősítés 10x 0 és VPWR (~18V) között, REF (~8V jó potméter beállítás esetén) referenciával.


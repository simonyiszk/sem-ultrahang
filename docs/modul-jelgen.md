# Jelgenerátor modul

Feladata:
A bejövő `ANALOG_IN` jelet pulzusszélesség-modulálja (PWM). Az analóg jelet az analóg interfész _(TODO: link)_ modul állítja elő. Az outputok összesen maximum 8 H-híd modulba _(TODO: doksi?)_ mennek át, a bemeneti tápfeszültséggel (`VPWR`) és a földdel (`GND`) együtt.

A H-hidak hajtják meg a hangszórókat.

PCB:
![](./img/modul-jelgen-inputs.png)

Inputok és tesztpontok:
![](./img/modul-jelgen-inputs.png)

Outputok: `VPWR, GND, PWM`

Schematic:
![](./img/modul-jelgen-buf-cmp.png)
![](./img/modul-jelgen-osc.png)

# Ultrahangos hangszóró

## Célkitűzés 
A projekt során egy ultrahangos irányított hangszórót tervezünk és valósítunk meg először analóg, majd digitális elektronikai alkatrészek felhasználásával.
Az elkészült hangszórót standolásokon bemutatható kísérleti eszköznek szánjuk, az öncélú szórakozáson kívül (zenehallgatás) akusztikával kapcsolatos fizikai kísérletek szemléltetésére, mint például:
- hanghullámok terjedésének és tulajdonságainak vizsgálata
- ultrahangos lebegtetés

## Analóg verzió
A rendszer blokkvázlata az alábbi ábrán látható:
![blockdiagram](https://github.com/user-attachments/assets/28c76410-812d-485c-b464-9e39f947d41e)
A jelforrást egyelőre nem specifikáltuk.
Az analóg verzióban PWM modulátort és a hozzá tartozó oszcillátort műveleti erősítőkkel valósítjuk meg.
Kapcsolóüzemű végerősítőfokozat gyanánt H-hidat, a prototípusban TC4427 típusú gate-meghajtó IC-t használunk. Hangszóróként az internetről rendelt 40 kHz rezonanciafrekvenciájú ultrahangos adó szolgál.

### Mérföldkövek

- [ ] **PWM modulátor műveleti erősítővel**
  - [X] Integrátor építése és mérése
  - [X] Hiszterézises komparátor építése és mérése
  - [X] Komplett prototípus megépítése breadboard-on
  - [ ] **Dokumentálás**
  - [ ] **Áramkörtervezés**
- [X] Jelforrás specifikációja
  - [X] Szükséges terveznivalók
- [X] Végfok
  - [X] H-híd tervezése (szükséges egyáltalán?)
- [ ] Hangszórómátrix
- [ ] Rendszerintegráció
  - [ ] NYÁK tervezés
  - [ ] Gyártás
  - [ ] Beültetés

### Side quest-ek
- [X] **Ultrahangos lebegtető**
  - [X] TC4427 tesztje
  - [X] **Oszcillátor aszimmetrikus táplálásának megoldása**
  - [X] **Hullámhossz meghatározása a pozicionáláshoz**
  - [X] Önjáró prototípus megépítése (amihez csak táp kell, és működik)
- [ ] Tápegység tervezése
  - TBD

## Digitális verzió
(Még nem tartunk itt... egyébként a [2025-ös tanfolyampanelt](https://github.com/simonyiszk/sem-armpanel-2025) szeretnénk hozzá használni.)

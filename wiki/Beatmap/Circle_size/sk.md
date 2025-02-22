---
tags:
  - CS
  - key count
no_native_review: true
---

# Veľkosť kruhov

*Pre regulácie okolo veľkosti kruhov, pozri: [Kritéria celkového umiestnenia](/wiki/Ranking_Criteria)*

**Veľkosť kruhov** (***CS***) je [beatmapové](/wiki/Beatmap) nastavenie obtiažnosti, ktoré mení veľkosť [trafiteľných objektov](/wiki/Hit_object). Hodnoty veľkosti kruhov majú rozsah od 0 do 10, ale iba hodnoty od 2 do 7 môžu byť vybraté v [editore beatmap](/wiki/Client/Beatmap_editor). Iné hodnoty môžu byť vybrané pomocou manuálnej zmeny [.osu súboru](/wiki/osu!_File_Formats/Osu_(file_format)) mapy.

## osu!

V osu!, veľkosť kruhov mení veľkosť kruhov a sliderov, kde väčšie hodnotu robia tieto objekty menšie. Spinnery nie sú afektované veľkosťou kruhov. Veľkosť kruhov sa vypočíta pomocou tohto vzorca:

`r = 54.4 - 4.48 * CS`

Kde `r` je polomer meraný v [osu!pixeloch](/wiki/osu!pixel), a `CS` ja hodnota veľkosti kruhu.

## osu!taiko

V osu!taiko, veľkosť kruhov neafektuje hru.

## osu!catch

V osu!catch, veľkosť kruhov určuje veľkosť chytača a ovocia.

## osu!mania

V osu!mania, veľkosť kruhov referuje počet tlačidiel.

## Efekty modov

Sú dva mody, ktoré môžu zmeniť veľkosť kruhov:

- [Easy](/wiki/Game_modifier/Easy): Rozpolí hodnotu CS.
- [Hard Rock](/wiki/Game_modifier/Hard_Rock): Vynásobí hodnotu CS 1.3, na maximálnu hodnotu 10.

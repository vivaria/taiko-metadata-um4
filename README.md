# taiko-metadata

A repo for tracking changes to 'data.json' metadata files. These changes will be proposed for future UM/OM releases.

> **Note**: Personally, I primarily play 10* Oni songs, and so these songs will typically be where I discover (and fix) inaccuracies. But, these inaccuraries are likely to be present in other difficulties, too.

## Non-metadata changes

- [ ] Anata to Tu-lat-tat-ta♪: Duplicate songs (`Nijiro_Songs\manpu2`, `XB1DLC_Songs\manpu9`)
- [ ] Mekadesu.: Audio is very loud (relative to other songs).
- [ ] LECEIL GLISSANDO: Audio is loud, but also distorted/clipped-sounding. In particular, the bass drum beats sound crunchy and harsh compared to [sample Nijiro recordings](https://www.youtube.com/watch?v=VK4NJGqOFbk).

## Songs missing from UM4

UM4 is missing some newer songs (AC/NS2 Music Pass), as well as some obscure older songs (AC7, Oira April Fools app).

- AC7
  - [ ] ROTTERDAM NATION -FOO MIX-
- Oira April Fools app
  - [ ] Kuro Vyrn no Tsubasa
  - [ ] The Ultimate
- NS2-only
  - [ ] MEGALOVANIA (Ura)
  - [ ] THE FIXER
- Nijiro + NS2 Music Pass
  - [ ] Akiba 20XX
  - [ ] exTora Trap!!
  - [ ] Overd
  - [ ] Roppon no Bara to Sai no Uta
  - [ ] VIVIVIVID
  - [ ] YOAKE
- Nijiro-only
  - [ ] Agent Hustle and Dr. Hassle
  - [ ] Aragami
  - [ ] Arc
  - [ ] BATTLE NO. 1
  - [ ] Carmen Prelude (Ura)
  - [ ] Challengers
  - [ ] Chimimouryou
  - [ ] Dragon of Divinity ~Shinryu~
  - [ ] Dragon of Time ~Kokuryu~
  - [ ] Hello, Mr. JOKER
  - [ ] Ka
  - [ ] Kyourandotou
  - [ ] Libera Ray
  - [ ] Matsuyoi Night Bug
  - [ ] Misdeed -la bonte de Dieu et l’origine du mal-
  - [ ] Player's High
  - [ ] R.I.P. Hero
  - [ ] Shinsei to Nue
  - [ ] Spectral Rider
  - [ ] SUPERNOVA
  - [ ] Unlimited Games
  - [ ] We are! (Ura)
  - [ ] Zouo to Shuuaku no Hanataba

## TJA to BIN conversion failures
 
I was able to add many of the above songs using TJA to BIN conversion (see `TJAConverts/` folder). However, some TJA2BIN conversions resulted in failures or broken songs:

- Conversion failures (https://github.com/Fluto/TakoTako/issues/22)
  - [ ] Kuro Vyrn no Tsubasa: Failure with no error log 
  - [ ] Carmen Prelude: Failure with error in log 
- BPM desychronization (https://github.com/Fluto/TakoTako/issues/16)
  - [ ] Roppon no Bara to Sai no Uta
  - [ ] Kyourandotou
  - [ ] R.I.P. Hero
  - [ ] Dragon of Time Kokuryu
  - [ ] Zouo to Shuuaku no Hanataba
  - [ ] Aragami
  - [ ] And potentially others... (some BPM desyncs can be very subtle)

# 🔨 Młot na idole

Generator inwektyw w stylu Fryderyka Nietzschego. Uderza młotem i wydaje wyrok —
obelga to dźwięk, jaki wydaje uderzony, wydrążony idol.

**Strona na żywo:** https://szafran00.github.io/mlot-na-idole/

## Co to robi

Składa gramatycznie poprawne polskie obelgi z banków słów rozpisanych na osiem
„krojów" wzorowanych na retoryce Nietzschego (*Zmierzch bożyszcz*, *Antychryst*,
*Ecce homo*, *Poza dobrem i złem*):

| krój | przykład |
|---|---|
| z naciskiem | *ostatecznie przebiegły chrześcijanin* |
| w najwyższym stopniu | *najbardziej pouczająca ofiara chrześcijaństwa* |
| z ogonem | *nieszczęście w szlafroku* |
| podwójne ostrze | *spróchniały, zrozpaczony dekadent* |
| jednym słowem | *nieporozumienie* |
| wróg czegoś | *oszczerca życia* |
| pełny wyrok | *znużony dekadent na glinianych nogach* |
| prosty cios | *jadowita tarantula* |

## Liczby

- **249 133** unikalnych kombinacji (liczone na żywo z banków słów).
- **0** błędów zgodności rodzajowej na 9 000 losowań (test w Node i w przeglądarce).
  Każdy przymiotnik ma trzy formy rodzajowe, każdy rzeczownik zapisany rodzaj —
  łączenie jest sterowane gramatyką, nie na ślepo.

## Technika

Jeden plik `index.html` — czysty HTML/CSS/JS, bez zależności, bez frameworka,
bez zasobów zewnętrznych. Motyw ciemny i jasny, responsywny, dostępny z klawiatury
(spacja / enter uderza), z poszanowaniem `prefers-reduced-motion`.

---

Zbudowane z [Claude Code](https://claude.com/claude-code).

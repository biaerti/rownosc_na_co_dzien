# Plansze styl – jak używać w DaVinci Resolve

## Co zawiera plansze_styl.setting

Fusion macro z:
- **Tło:** ciemny granatowy-antracyt #0D0F1A (nie pure black – daje głębię)
- **Tekst główny:** Montserrat Bold, off-white #F5F5F5, rozmiar 8.5%, interlinea 1.4
- **Tekst pomocniczy:** Montserrat Regular, szary #B8B8B8, rozmiar 4.8%, pod linią akcentu
- **Linia akcentu:** cienka pozioma linia, domyślnie ciepły amber #E8924C, 50% szerokości ekranu
- Pozycja linii: między tekstem głównym a pomocniczym

## Jak wgrać macro do Resolve

### Metoda A – Import przez Fusion
1. Otwórz Fusion page (kliknij nazwę clipu → Fusion)
2. W menu Fusion: **File → Import → Macro...**
3. Wybierz `plansze_styl.setting`
4. Macro pojawi się w bibliotece po lewej (Effects Library → Macros)
5. Przeciągnij macro na flow – pojawi się node `PlanszeStyl`
6. Podłącz output do `MediaOut1`

### Metoda B – Copy-paste (szybciej)
1. Otwórz `plansze_styl.setting` w notatniku
2. Zaznacz cały tekst (Ctrl+A) i skopiuj (Ctrl+C)
3. Otwórz Fusion page w Resolve
4. Kliknij w puste miejsce na flow i wklej (Ctrl+V)
5. Nodes pojawią się – połącz `MergeFinalna` → `MediaOut1`

## Jak edytować tekst na planszy

Po wgraniu macro:
- Kliknij node `PlanszeStyl`
- W Inspector po lewej będziesz widział:
  - **Tekst główny** – wpisz tu główne zdanie (np. „Jeden mechanizm.")
  - **Tekst pomocniczy** – opcjonalne zdanie pod linią (zostaw puste jeśli nie potrzebujesz)
  - **Akcent R/G/B** – kolor linii akcentu (domyślnie amber, możesz zmienić)

## Jak animować wejście tekstu (fade in)

W Fusion na nodzie `TekstGlowny`:
1. Przejdź do Inspector → `Size`
2. Kliknij PPM na `Size` → „Animate"
3. Na klatce 0: Size = 0, Opacity = 0
4. Na klatce 12 (0.5s przy 25fps): Size = 0.085, Opacity = 1
5. To samo na nodzie `TekstSub` z 5-klatkowym opóźnieniem

Albo prościej: użyj **Dissolve** node przed `MediaOut1` i zrób fade in/out na poziomie clipu w Edit page.

## Kolory akcentu – gotowe wartości RGB (0–1)

| Kolor | R | G | B | Zastosowanie |
|---|---|---|---|---|
| Amber (domyślny) | 0.91 | 0.57 | 0.30 | Energiczny, ciepły |
| Niebieski | 0.24 | 0.55 | 0.89 | Spokojniejszy, instytucjonalny |
| Biały | 0.90 | 0.90 | 0.90 | Minimalistyczny |
| Czerwony | 0.85 | 0.22 | 0.22 | Alarmujący (dla „Milczenie nie chroni.") |

## Rozmiary tekstu – wartości do kopiowania

Wszystko jako % wysokości ekranu (jak w Fusion):

| Zastosowanie | Font | Style | Size |
|---|---|---|---|
| Krótkie uderzające zdanie (1 linia) | Montserrat | Bold | 0.10 |
| Standardowa plansza (2–3 linie) | Montserrat | Bold | 0.085 |
| Długi cytat lub definicja | Montserrat | Regular | 0.060 |
| Tekst pomocniczy / podpis | Montserrat | Regular | 0.048 |
| Numer telefonu | Montserrat | Bold | 0.120 |

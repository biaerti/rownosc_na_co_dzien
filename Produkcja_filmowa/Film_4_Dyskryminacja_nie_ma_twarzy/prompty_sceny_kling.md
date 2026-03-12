# Prompty scen – Kling AI VIDEO 3.0 | Film 4

## Uwagi ogólne

- Sylwetki/twarze: **faces not clearly visible** – odwrócone, backlit, lub poza kadrem
- Brak rekwizytów tekstowych (bez plakatów, tablic, napisów w kadrze)
- Styl: photorealistic, not animated
- **S3 (pętla tekstowa)** – wyłącznie DaVinci Resolve, nie Kling

---

## Formaty w Kling

| Scena | Format Kling | Dlaczego |
|---|---|---|
| S2a, S2b, S2c, S2d | **1:1 (square, 1080×1080)** | Dwa panele obok siebie w 16:9 – każdy panel ~960×1080, generujemy 1:1 i przycinamy w Resolve |
| S4 (szef) | **16:9** | Pełnoekranowa scena |
| S5a, S5b | **16:9** | Pełnoekranowe |

### Jak złożyć split screen w Resolve (S2)
1. Wgraj oba 1:1 clipy (np. S2a + S2b) jako dwie ścieżki wideo
2. Clip A (lewa): Transform → Position X = -0.25 (przesuń w lewo o połowę)
3. Clip B (prawa): Transform → Position X = +0.25 (przesuń w prawo o połowę)
4. Oba skalowane do 0.5 szerokości lub zostaw 1:1 – wypełnia 16:9
5. **Freeze frame lewego clipu:** prawy przycisk na klipie A → „Freeze Frame" na ostatniej klatce
   lub użyj Speed Change → Freeze na ostatniej sekundzie
6. Clip B zaczyna się 1s po uruchomieniu Clip A (żeby efekt freeze był widoczny)

---

## SCENA 2a – Blokers LEWA strona | 1:1 | 5s

Lewa połowa Para 1. Blokers z osiedla, atakuje werbalnie.

```
Square format 1:1. Gritty urban housing estate stairwell or courtyard,
aggressive male silhouette in a dark hoodie and tracksuit, stocky build,
stands with confrontational posture leaning forward, one arm pointing
accusingly toward someone off-screen to the right, mouth open as if shouting,
face not clearly visible or heavily backlit by dim overhead light,
dark moody atmosphere, harsh concrete walls, shallow depth of field,
photorealistic, cinematic
-- no readable text, no posters, no watermark, not animated, no clean modern interior
```

---

## SCENA 2b – Gej pogardliwy PRAWA strona | 1:1 | 5s

Prawa połowa Para 1. INNA postać niż S2a. Stylowy mężczyzna patrzy z góry na kogoś poniżej kadru.

```
Square format 1:1. Modern clean interior, a stylishly dressed young white
Caucasian man in his late 20s in fashionable clothes stands with an expression
of contempt and superiority, his chin slightly raised, looking down toward the
lower frame with a cold dismissive expression, the person he looks at is
off-screen below, his posture is upright and detached, one hand in pocket
or arms loosely crossed, light skin, styled dark or light brown hair,
European features, soft modern interior lighting, medium shot, photorealistic
-- no face of looked-at person visible, no readable text, no watermark,
not animated, no Asian features
```

---

## SCENA 2c – Wierzący blokuje biuro LEWA strona | 1:1 | 5s

Lewa połowa Para 2. Konserwatywny mężczyzna blokuje wejście do biura.

```
Square format 1:1. Office corridor with a glass-panel door to an executive
office, a formal male silhouette in a dark blazer with a small cross pendant
visible on his lapel or around his neck stands in the doorway blocking
the entrance, a female silhouette in professional office attire stands
in front of him facing the door with her hand slightly raised as if about
to enter, the man's arm and body block the way, firm dismissive gesture,
faces not clearly visible, office corridor lighting, medium shot, photorealistic
-- no readable text on walls or doors, no watermark, not animated
```

---

## SCENA 2d – Kobieta odchodzi z randki PRAWA strona | 1:1 | 5s

Prawa połowa Para 2. INNA postać niż S2c. Scena na randce w kawiarni – kobieta wstaje z pogardą i odchodzi.

```
Square format 1:1. Cozy cafe or restaurant interior, warm ambient lighting,
two people on a date at a small table, a man in his 30s sits at the table
with a small silver cross necklace visible at his collar, a woman in her 30s
is in the process of standing up from her chair, she looks back at him with
a cold contemptuous expression, slight eye-roll or sneer, her body clearly
turned away to leave, the man remains seated looking after her with a confused
expression, medium shot capturing both at the table, photorealistic, candid feel
-- no readable text, no watermark, not animated
```

---

## Uwagi do montażu S2 w Resolve

**Para 1:** S2a (lewa) + S2b (prawa)
- S2a gra przez 4s → freeze na ostatniej klatce
- S2b zaczyna się w 3s (1s nakładki, żeby freeze S2a był widoczny przed wejściem S2b)
- Oba widoczne przez ~1s razem → fade out

**Para 2:** S2c (lewa) + S2d (prawa)
- Ta sama technika – S2c freeze, S2d wchodzi

**Między parami:** 0.5s czarny ekran lub dissolve

---

## SCENA 4 – Szef odpycha postacie | Multi-Shot Custom | 16:9

Patrz `bohaterowie_referencje.md` po assety: Szef, Biuro oraz 5 postaci.
Wszystkie shoty wgrywać z character_reference: **Szef** + **Biuro** (environment reference).

**STRUKTURA Multi-Shot Custom (5 shotów × ~1.5s = ~7.5s łącznie):**

### Shot 4-A – Szef przy biurku (establishing, 3s)
```
16:9. Executive office interior, a middle-aged man in his 50s in a dark charcoal
suit with white shirt, slightly heavy build, short grey-streaked dark hair,
sits at a large desk at 3/4 angle toward camera, serious authoritative expression,
desk with papers and laptop, large window behind him with soft natural light,
establishing shot, medium shot, photorealistic
-- no readable text on papers or screen, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

### Shot 4-B – Gej odrzucony (1.5s)
```
16:9. Same executive office doorway, the middle-aged suited man stands at the
open door, arm raised in a firm stop gesture, blocking a young man in his late
20s in neat modern clothing with a small rainbow-colored lanyard visible around
his neck, the young man pauses at the threshold and looks down, door begins to
close, same office lighting, medium shot, photorealistic
-- no readable text, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

### Shot 4-C – Wierzący odrzucony (1.5s)
```
16:9. Same executive office doorway, same suited man at the door, arm raised in
the same stop gesture, a man in his 40s in a collared shirt and trousers with a
small silver cross pendant visible approaches and is turned away, door closing,
same lighting and angle, photorealistic
-- no readable text, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

### Shot 4-D – Kobieta odrzucona (1.5s)
```
16:9. Same executive office doorway, same suited man repeats the dismissive
stop gesture, a woman in her 30s to 40s in professional office attire and blazer
approaches and is turned away, she briefly looks up before the door closes,
same office lighting and angle, photorealistic
-- no readable text, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

### Shot 4-E – Ciemnoskóry odrzucony (1.5s)
```
16:9. Same executive office doorway, same suited man at the door with the same
firm stop gesture, a dark-skinned man in his 30s to 40s in well-fitted professional
business attire approaches and is turned away, door closes, same lighting and angle,
photorealistic
-- no readable text, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

### Shot 4-F – Starsza kobieta odrzucona (1.5s)
```
16:9. Same executive office doorway, same suited man at the door with the same
firm dismissive stop gesture, an older woman in her 60s to 70s in neat everyday
clothing or a simple jacket with grey or white hair approaches the doorway and
is turned away, she pauses with a calm dignified expression before the door
closes firmly, same office lighting and angle, photorealistic
-- no readable text, no watermark, not animated
```
*[Use: Szef character reference + Biuro environment reference]*

---

## SCENA 5a – Ekrany medialne | Single | 16:9 | 5s

```
16:9. Dark room filled with multiple glowing television screens and smartphones
showing flickering news content, screens overlap and illuminate the darkness
with blue and white light, visual overload and noise, no readable text on
any screen, chaotic flickering, cinematic, photorealistic
-- no readable text on any screen, no watermark, not animated
```

**Alternatywa:** materiał stockowy Pexels/Pixabay: „news screens dark room" / „media overload"

---

## SCENA 5b – Samotna sylwetka | Single | 16:9 | 8s

```
16:9. Dark corner of a bare room, a lone human silhouette sits on the floor
with knees drawn up close to the chest, back against the wall, head bowed,
completely still, only a thin strip of light from under a door casts a sliver
of illumination across the floor, very slow push in toward the figure,
heavy silent atmosphere, no other elements, photorealistic, emotional
-- no faces visible, no readable text, no watermark, not animated
```

---

## SCENA 7 – Centrum Wsparcia (konsultacja) | Single | 16:9 | 8s

### ASSET: Pomieszczenie (IMAGE reference – wgraj jako style_reference)

Zdjęcie z ul. Bierutowskiej wgraj bezpośrednio jako **style_reference** do promptu wideo.
Jeśli Kling pozwala na image reference dla środowiska – wgraj je. Jeśli nie – użyj poniższego prompt do wygenerowania podobnego pomieszczenia jako osobny IMAGE asset.

**Prompt IMAGE do wygenerowania assetu pokoju (jeśli potrzebujesz):**
```
Small minimalist consultation room, white walls, grey carpet floor,
compact white desk with a laptop and a small notebook, grey office chair
behind the desk, two simple white visitor chairs in front of the desk,
glass-panel door on the left side partially open showing a corridor,
fluorescent ceiling light, clean and calm atmosphere, no people,
wide angle shot from the doorway, photorealistic, sharp focus
-- no readable text on walls, no watermark
```
Zapisz jako: `ref_pokoj_centrum.jpg`

---

### Prompt wideo S7 (wgraj ref_pokoj_centrum.jpg jako style_reference)

```
16:9. Small consultation room with white walls and grey carpet, glass door
visible on the left, compact white desk with a laptop and papers,
a woman in her early 30s with professional appearance sits behind the desk
as a counselor, she leans slightly forward with an attentive and warm expression,
across from her at the desk sits a second white Caucasian person partially
visible from behind or side, they have just finished filling out a form,
the counselor nods and speaks gently, soft fluorescent ceiling light,
intimate calm atmosphere, medium two-shot or slight over-the-shoulder angle,
photorealistic, documentary feel
-- no readable text on papers or laptop screen, no watermark, not animated
```

**Alternatywa Shot B (szersze ujęcie, widać drzwi):**
```
16:9. View from just inside a small consultation room looking toward the desk,
glass door frame visible on the left edge of frame, white walls, grey carpet,
a woman counselor in her 30s sits at a white desk with a laptop, a client
sits across from her, both Caucasian, the counselor holds a pen and reviews
a completed form with the client, warm attentive atmosphere, fluorescent
ceiling light, documentary handheld feel, photorealistic
-- no readable text, no watermark, not animated
```

---

## Jeśli scena nie wychodzi po 2 próbach

**S2a – twarz zbyt widoczna:** dodaj „face completely hidden by shadow and backlight, only outline visible"

**S2b – brak pogardliwego wyrazu:** dodaj „chin raised in disdain, slight sneer, cold eyes looking downward"

**S2c – drzwi biura nie wychodzą:** zmień na „office hallway, man in blazer stands in front of a closed door with arms crossed, woman faces him from in front"

**S4 Multi-Shot – postaci się mieszają między shotami:** przejdź na Single shot dla każdej postaci osobno, zmontuj w Resolve (5 × 1.5s cięcia)

**S5b – za jasno:** dodaj „extremely dark scene, near-total darkness, only silhouette visible, film noir"

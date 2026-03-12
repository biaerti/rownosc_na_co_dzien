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
| S4 (5 × ręka wyklucza) | **16:9** | Pełnoekranowe, każdy shot osobno |
| S5a, S5b | **16:9** | Pełnoekranowe |
| S7 (3 × konsultacja) | **16:9** | Pełnoekranowe, wgraj ref_pokoj_centrum.jpg jako style_reference |

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
Square format 1:1. Gritty urban housing estate stairwell or concrete courtyard,
aggressive white Polish man in his 30s, light skin, shaved head or very short hair,
stocky build, wearing a dark hoodie and tracksuit, stands with confrontational
posture leaning forward, one arm pointing accusingly toward someone off-screen
to the right, mouth open as if shouting, face partially visible showing anger,
dark moody atmosphere, harsh concrete walls, dim overhead light,
shallow depth of field, photorealistic, cinematic
-- white Caucasian man, light skin, no dark skin, no readable text, no posters,
no watermark, not animated
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
Square format 1:1. Office corridor with a glass-panel door to an office,
a white Polish man in his 40s to 50s, light skin, dark or greying hair,
wearing a formal collared shirt with a small silver cross pendant visible
at his collar, stands in the doorway blocking the entrance with his arm
and body, a white woman in professional office attire stands in front of
him facing the door with her hand slightly raised as if about to enter,
the man's firm dismissive gesture blocks her way, office corridor lighting,
medium shot, photorealistic
-- white Caucasian man, light skin, Polish appearance, no Asian features,
no dark skin on the man, no readable text on walls or doors, no watermark,
not animated
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

## SCENA 4 – Abstrakcyjna ręka wyklucza | 5 × Single | 16:9

**Koncepcja:** każda postać w swojej własnej sytuacji życiowej.
Anonimowa ręka/ramię wchodzi z krawędzi kadru i wykonuje gest wykluczenia.
Twarzy wykluczającego **nigdy nie widać** – tylko ramię i dłoń.
Motyw ręki jest ten sam w każdym ujęciu → ten sam mechanizm, różne ofiary.

Każdy shot: **Single, 16:9, 2s**.
Montaż: 5 shotów ciętych szybko w Resolve (~0.3s przejście między nimi).

---

### Shot 4-1 – Gej wykluczony | Single | 16:9 | 2s

Sytuacja: spotkanie towarzyskie, bar lub impreza. Mężczyzna z tęczowym elementem.

```
16:9. Social gathering or bar interior, warm ambient light, a white Caucasian
man in his late 20s with light skin, styled hair, smart casual clothing and
a small rainbow pin or lanyard visible, stands slightly apart from a group,
from the right edge of frame an anonymous arm in a sleeve extends and
makes a firm palm-out STOP gesture directly at him, blocking him from
the group, he pauses mid-step and looks down, the arm belongs to someone
off-screen whose face is never visible, medium shot, photorealistic
-- no readable text, no watermark, not animated, white man light skin
```

---

### Shot 4-2 – Wierzący wykluczony | Single | 16:9 | 2s

Sytuacja: miejsce publiczne lub spotkanie. Mężczyzna z krzyżykiem.

```
16:9. Public space or community meeting room, neutral lighting, a white Polish
man in his 40s with light skin, dark or greying hair, collared shirt and a
small silver cross pendant visible at his collar, stands facing a group or
a desk, from the left edge of frame an anonymous arm in a sleeve enters
and points dismissively away from the group, gesturing him to leave,
he turns slightly with a quiet dignified expression, the face of the
person pointing is never visible, medium shot, photorealistic
-- white Caucasian man, light skin, no Asian features, no readable text,
no watermark, not animated
```

---

### Shot 4-3 – Kobieta wykluczona | Single | 16:9 | 2s

Sytuacja: sala konferencyjna. Kobieta zostaje pominięta przy stole.

```
16:9. Corporate conference room, several suited figures seated at a table
seen from behind or as silhouettes, a white Caucasian woman in her 30s
to 40s with light skin in a professional blazer stands holding papers
ready to present, from the top edge of frame an anonymous hand enters
and waves her away dismissively, she freezes mid-gesture and her
expression falls, medium shot, photorealistic
-- no readable text on papers, no watermark, not animated
```

---

### Shot 4-4 – Ciemnoskóry mężczyzna wykluczony | Single | 16:9 | 2s

Sytuacja: restauracja lub sklep. Elegancki mężczyzna przy wejściu.

```
16:9. Restaurant entrance or upscale store, warm interior lighting visible
through a door, a dark-skinned man in his 30s to 40s in well-fitted smart
casual clothing stands at the entrance looking in with a composed expression,
from the right edge of frame an anonymous arm in a dark sleeve extends
with a flat palm gesture blocking his entry, he stops and looks at the
hand with quiet resignation, the face of the blocking person is off-screen,
medium shot, photorealistic
-- no readable text, no watermark, not animated
```

---

### Shot 4-5 – Starsza kobieta wykluczona | Single | 16:9 | 2s

Sytuacja: gabinet lekarski lub urząd. Kobieta czeka i zostaje pominięta.

```
16:9. Medical waiting room or government office corridor, fluorescent lighting,
a white older woman in her 60s to 70s with grey or white hair in neat everyday
clothing sits in a waiting chair with a number ticket or folder in her hands,
she looks up expectantly, from the right edge of frame an anonymous arm
enters and points past her to someone further away, skipping over her,
she looks down at her hands with a resigned expression, medium shot,
photorealistic
-- white older woman, light skin, no readable text on ticket or folder,
no watermark, not animated
```

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

## SCENA 7 – Centrum Wsparcia (konsultacje) | Multi-Shot Custom | 16:9 | ~10s

### ASSET: Pokój (style_reference)

**Wgraj drugie zdjęcie pokoju (bez plakatów, czyste białe ściany)** jako style_reference do każdego shotu S7.

Jeśli potrzebujesz wygenerować IMAGE asset zamiast wgrywać zdjęcie:
```
Small minimalist consultation room, white walls, dark grey carpet floor,
compact white rectangular desk, grey padded office chair behind the desk,
two simple white plastic visitor chairs in front, glass-panel door with
dark grey metal frame on the left side partially open showing a white
corridor wall, fluorescent LED ceiling strip light, clean empty modern
atmosphere, wide angle shot from the doorway looking in, photorealistic
-- no text, no posters, no people, no watermark
```
Zapisz jako: `ref_pokoj_centrum.jpg`

---

### Shot 7-A – Interwentka z kobietą (establishing, 3s)

```
16:9. Small consultation room with white walls, dark grey carpet, white desk,
glass door on left, fluorescent ceiling light, a white Caucasian woman
in her mid 30s with brown hair and warm professional appearance sits behind
the desk as a counselor leaning slightly forward, across from her sits a
white Caucasian woman in her 40s partially visible from the side or behind,
the counselor listens attentively with a gentle empathetic expression,
papers on the desk between them, medium two-shot, photorealistic,
documentary handheld feel
-- no readable text on papers, no watermark, not animated
```
*[Use: ref_pokoj_centrum.jpg jako style_reference]*

---

### Shot 7-B – Interwentka z mężczyzną (2s)

```
16:9. Same small consultation room, white walls, grey carpet, white desk,
glass door on left, same white Caucasian woman counselor in her 30s sits
behind the desk, now across from her sits a white Caucasian man in his
40s to 50s seen from behind or profile, the counselor nods with an
understanding expression as he speaks, the man's posture is tense then
slowly relaxing, medium two-shot, photorealistic
-- no readable text, no watermark, not animated
```
*[Use: ref_pokoj_centrum.jpg jako style_reference]*

---

### Shot 7-C – Szeroki pokój, po zakończeniu (2s)

```
16:9. Same small consultation room from the doorway, white walls, dark grey
carpet, glass door frame visible on left, white desk with papers on it,
the white Caucasian counselor woman in her 30s sits at the desk and hands
a leaflet or paper to a client whose back is to the camera, calm resolved
atmosphere, slightly warmer than the beginning of the session, natural
end-of-meeting moment, wide medium shot from near the doorway, photorealistic
-- no readable text on papers or leaflet, no watermark, not animated
```
*[Use: ref_pokoj_centrum.jpg jako style_reference]*

---

## Jeśli scena nie wychodzi po 2 próbach

**S2a – twarz zbyt widoczna:** dodaj „face completely hidden by shadow and backlight, only outline visible"

**S2b – brak pogardliwego wyrazu:** dodaj „chin raised in disdain, slight sneer, cold eyes looking downward"

**S2c – drzwi biura nie wychodzą:** zmień na „office hallway, man in blazer stands in front of a closed door with arms crossed, woman faces him from in front"

**S4 Multi-Shot – postaci się mieszają między shotami:** przejdź na Single shot dla każdej postaci osobno, zmontuj w Resolve (5 × 1.5s cięcia)

**S5b – za jasno:** dodaj „extremely dark scene, near-total darkness, only silhouette visible, film noir"

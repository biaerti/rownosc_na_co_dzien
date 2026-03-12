# Bohaterowie i assety – Film 3: "Nitka"

Masz już wygenerowane bazy. Wszystkie warianty robisz przez Image mode z attached reference.

---

## POSTACIE – warianty z DuszekBaza jako reference

Wgraj bazowego ludka jako Element → tag: `Characters`, name: `DuszekBaza`.
Następnie w Image mode: attach DuszekBaza + wklej poniższy prompt.
Każdy wynik wgraj jako osobny Element.

---

### WYKLUCZONY – bladobłękitny, smutny (sceny S1–S8)

Ten charakter to DuszekBaza z inną ekspresją – kolor NIE zmienia się (baza już jest bladoniebieska).

```
Same character style as reference. Keep the same soft pale icy blue body and drape color
exactly as in the reference. Change only the expression: eyes drooping downward with small
pupils, heavy eyelids, eyebrow-like shapes angled down toward the center creating a
sad defeated look. Body posture slightly hunched, shoulders drooping. Keep the same ghost
drape shape, same hand and foot style, same eye size and structure. Same Pixar 3D render quality.
```

**Element:** Name `Wykluczony` | Tag `Characters`
**Description:** `soft pale icy blue ghost drape, sad drooping eyes hunched posture, Pixar 3D`

---

### POMAGIER – złocisty żółty, spokojny (wszystkie sceny)

```
Same character style as reference. Change the body and drape color to warm golden
yellow, rich and saturated. Keep the gentle smile from the reference. Eyes: steady
and calm, pupils centered and confident, eyebrow-like shapes level – expression of
quiet warmth and determination. Upright relaxed posture. Same ghost drape shape,
same hand and foot style, same Pixar 3D render quality.
```

**Element:** Name `Pomagier` | Tag `Characters`
**Description:** `golden yellow ghost drape, calm warm smile upright posture, Pixar 3D`

---

### SPRAWCA1 – bordowy, zarozumiały (klika wyrzucenie POMAGIERA w S7)

```
Same character style as reference. Change the body and drape color to deep dark
burgundy red. Expression: eyes slightly narrowed, small sharp pupils, eyebrow-like
arches angled inward creating a smug dismissive look. One arm slightly raised as if
pointing or gesturing. Same ghost drape shape, same Pixar 3D render quality.
```

**Element:** Name `Sprawca1` | Tag `Characters`
**Description:** `dark burgundy red ghost drape, smug narrowed eyes arm raised, Pixar 3D`

---

### SPRAWCA2 – fuksja/różowy, drwiący (klika wyrzucenie WYKLUCZONEGO w S3)

```
Same character style as reference. Change the body and drape color to hot pink
fuchsia, vivid and saturated. Expression: eyes slightly narrowed with a mocking
raised eyebrow arch, small sharp pupils, superior look. One arm positioned as if
hand on hip. Same ghost drape shape, same Pixar 3D render quality.
```

**Element:** Name `Sprawca2` | Tag `Characters`
**Description:** `hot pink fuchsia ghost drape, mocking raised brow hand on hip, Pixar 3D`

---

### SPRAWCA3 – głęboki fiolet, zimny

```
Same character style as reference. Change the body and drape color to deep dark violet,
rich and saturated. Expression: eyes narrowed with a cold superior gaze, very small pupils,
eyebrow arches in a slow dismissive arch, expressionless and indifferent. Arms hanging
slightly forward, still posture. Same ghost drape shape, same Pixar 3D render quality.
```

**Element:** Name `Sprawca3` | Tag `Characters`
**Description:** `deep dark violet ghost drape, cold narrowed eyes still posture, Pixar 3D`

---

## MIECZE ŚWIETLNE – warianty (tag: Items)

Każdy mieczyk generujesz w Image mode. MieczZielony jako baza – żółty i czerwony generujesz z MieczZielony attached.
Mieczyk powinien być prosty, zaokrąglony, Pixar-style – nie realistyczny Star Wars, ale sympatyczny kijek świetlny.
Czarne tło żeby asset był czysty.

---

### MIECZYK ZIELONY – baza

Generuj bez referencji.

```
A single glowing lightsaber-style energy stick, floating vertically on a pure black
background. Simple cylindrical shape with a rounded top, short chunky handle at the
bottom. The blade glows vivid green with a soft volumetric halo around it, like neon
light. Pixar-style 3D render, clean and simple, no text, no watermark.
No realistic details – cute and rounded, like a toy from an animated film.
```

**Element:** Name `MieczZielony` | Tag `Items`
**Description:** `glowing green lightsaber stick rounded Pixar 3D, black background`

---

### MIECZYK ŻÓŁTY

Generuj z **MieczZielony attached jako reference**.

```
Same lightsaber stick style as reference. Change the blade and glow color to warm
amber yellow-orange. Keep the same shape, same rounded top, same handle, same
soft volumetric halo. Only the color changes – from green to amber yellow.
```

**Element:** Name `MieczZolty` | Tag `Items`
**Description:** `glowing amber yellow lightsaber stick rounded Pixar 3D, black background`

---

### MIECZYK CZERWONY

Generuj z **MieczZielony attached jako reference**.

```
Same lightsaber stick style as reference. Change the blade and glow color to deep
vivid red. Keep the same shape, same rounded top, same handle, same soft volumetric
halo. Only the color changes – from green to deep red.
```

**Element:** Name `MieczCzerwony` | Tag `Items`
**Description:** `glowing deep red lightsaber stick rounded Pixar 3D, black background`

---

## SCENY – elementy lokacji (tag: Scenes)

Światy są trzema stanami tego SAMEGO pustkowia. Każdy kolejny world generujesz z referencją do poprzedniego żeby teren był identyczny.

**Kolejność generowania:** SwiatJasny → SwiatCiemny (ref: SwiatJasny) → SwiatOdrodzenie (ref: SwiatCiemny)

---

### SwiatJasny – baza (sceny S1–S6)

Generuj bez referencji – to jest baza.

```
stylized surreal 3D CGI landscape made of smooth flowing terrain with glowing
light waves embedded in the ground, minimal organic hills, wide empty space,
subtle luminous lines flowing through the ground like energy streams,
soft ambient lighting, dreamy atmosphere, pastel purple and blue palette,
very clean environment with almost no objects, cinematic depth,
Pixar-style soft 3D rendering, no characters, no text, no watermark

no flowers, no trees, minimal environment
```

**Element:** Name `SwiatJasny` | Tag `Scenes`
**Description:** `surreal 3D pastel purple-blue barren terrain, glowing ground lines, minimal Pixar style`

---

### SwiatCiemny (sceny S7–S8 – deszcz, wykluczenie, cięcie nitki)

Generuj z **SwiatJasny attached jako reference**.

```
Same terrain and landscape style as reference. Make the atmosphere dark and rainy –
heavy rain falling, puddles forming on the glowing ground lines, sky overcast with
dark grey-purple storm clouds, the soft light waves on the ground now dim and cold,
overall palette shifted to cold grey-blue with hints of deep violet, oppressive heavy
atmosphere, no characters, no text
```

**Element:** Name `SwiatCiemny` | Tag `Scenes`
**Description:** `same barren terrain as SwiatJasny but dark rainy stormy, cold grey-violet, dim ground lines`

---

### SwiatOdrodzenie (sceny S9–S10 – żółta nitka, kwiatek, słońce)

Generuj z **SwiatCiemny attached jako reference**.

```
Same terrain and landscape style as reference. The storm is clearing – a single golden
ray of sunlight breaks through the clouds in the background. On the barren glowing ground
in the foreground, one small flower is blooming upward, its petals catching the light.
The ground light waves are warming from cold grey to soft amber-green. Atmosphere shifts
from oppressive to quietly hopeful. No characters, no text.
```

**Element:** Name `SwiatOdrodzenie` | Tag `Scenes`
**Description:** `same barren terrain, one flower blooming, golden sun ray breaking through clouds, hopeful`

---

## Pełna lista elementów do stworzenia

| Element | Tag | Jak wygenerować |
|---|---|---|
| `DuszekBaza` | Characters | Wgraj gotowego bazowego ludka |
| `Wykluczony` | Characters | Image mode + DuszekBaza reference |
| `Pomagier` | Characters | Image mode + DuszekBaza reference |
| `Sprawca1` | Characters | Image mode + DuszekBaza reference (bordowy – klika S7) |
| `Sprawca2` | Characters | Image mode + DuszekBaza reference (fuksja – klika S3) |
| `Sprawca3` | Characters | Image mode + DuszekBaza reference (fiolet – pasywny) |
| `MieczZielony` | Items | Image mode, bez reference – baza |
| `MieczZolty` | Items | Image mode + **MieczZielony** reference |
| `MieczCzerwony` | Items | Image mode + **MieczZielony** reference |
| `SwiatJasny` | Scenes | Image mode, bez reference – baza |
| `SwiatCiemny` | Scenes | Image mode + **SwiatJasny** reference |
| `SwiatOdrodzenie` | Scenes | Image mode + **SwiatCiemny** reference |

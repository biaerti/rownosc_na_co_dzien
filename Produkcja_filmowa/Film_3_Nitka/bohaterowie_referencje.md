# Bohaterowie i assety – Film 3: „Nitka"

## Logika assetów

Film opiera się na 5 gotowych duszkach + 3 miecze + 1 miecz podwójny + 3 krainy.
Duszki są już wgrane w Kling. Miecze i krainy generuj według instrukcji poniżej.

---

## POSTACIE – gotowe assety w Kling

### WYKLUCZONY – `WYKLUCZONY- blue`

**Nazwa w Kling:** `WYKLUCZONY- blue`
**Tag:** Characters

**Wygląd (do opisu w promptach):**
`small soft pale grey-blue ghost figure, large round warm brown eyes, sad drooping posture, small rounded body with flowing pale blue drape`

**Description assetu (ustaw w Kling):**
`small pale grey-blue ghost figure with large round brown eyes, sad drooping expression, small rounded Pixar 3D body with flowing drape`

**Rola w filmie:** Zostaje w tyle, jest wykluczony, dostaje pomoc od Żółtego. Główny bohater.

---

### POMAGIER – `Pomagier - yellow`

**Nazwa w Kling:** `Pomagier - yellow`
**Tag:** Characters

**Wygląd (do opisu w promptach):**
`warm golden yellow ghost figure, large round blue eyes, gentle kind expression, round plump body with flowing golden yellow drape`

**Description assetu (ustaw w Kling):**
`warm golden yellow ghost figure with large round blue eyes, gentle kind warm smile, plump rounded Pixar 3D body with flowing golden drape`

**Rola w filmie:** Na początku w grupie, potem zostawia grupę i pomaga Wykwluconemu. Kluczowy bohater.

---

### SPRAWCA1 – `Sprawca - burgun red`

**Nazwa w Kling:** `Sprawca - burgun red`
**Tag:** Characters

**Wygląd (do opisu w promptach):**
`dark burgundy-red ghost figure, narrowed sharp eyes, one arm extended or raised, smug dominant posture, flowing dark red drape`

**Description assetu (ustaw w Kling):**
`dark burgundy-red ghost figure with narrowed sharp eyes, one arm raised gesturing, smug dominant posture, Pixar 3D flowing drape`

**Rola w filmie:** Jeden z wykluczających sprawców, dominujący lider grupy.

---

### SPRAWCA2 – `Sprawca2 - pink`

**Nazwa w Kling:** `Sprawca2 - pink`
**Tag:** Characters

**Wygląd (do opisu w promptach):**
`hot pink fuchsia ghost figure, angry furrowed brow, confrontational posture, vivid pink flowing drape`

**Description assetu (ustaw w Kling):**
`hot pink fuchsia ghost figure with angry furrowed brow, confrontational aggressive posture, Pixar 3D flowing drape`

**Rola w filmie:** Jeden z wykluczających sprawców.

---

## MIECZE ŚWIETLNE – do wygenerowania (tag: Items)

Generuj w Image mode. MieczZielony jako baza – pozostałe generuj z nim jako reference.
Czarne tło żeby asset był czysty.

---

### RaczkaWylaczona – wyłączona rączka (brak ostrza)

Generuj z **MieczZielony attached jako reference**.

```
Same handle shape and style as reference. REMOVE the blade entirely — no blade,
no glow, no light emission. Only the short chunky cylindrical handle remains,
dark and inert. The handle is slightly darker than the reference, matte finish.
Floating vertically on pure black background. Pixar 3D toy-like style.
No text, no watermark.
```

**Element:** Name `RaczkaWylaczona` | Tag `Items`
**Description:** `short dark lightsaber handle only, no blade, no glow, inert matte finish, chunky Pixar 3D toy-like, black background`

*(Opis do wklejenia w Kling — 92 znaki, mieści się w limicie 100)*

---

### MieczZielony – baza

Generuj **bez referencji**.

```
A single short glowing lightsaber-style energy stick, floating vertically on a pure
black background. Simple chunky cylindrical blade with a rounded tip, short rounded
handle at the bottom. The blade glows vivid bright green with a soft volumetric
neon halo around it. Pixar-style 3D render, clean cute rounded design like a toy
from an animated film. No text, no watermark, no realistic details.
```

**Element:** Name `MieczZielony` | Tag `Items`
**Description:** `short glowing vivid green lightsaber stick, rounded blade with soft neon green halo, chunky handle, Pixar 3D toy-like, black background`

---

### MieczZolty

Generuj z **MieczZielony attached jako reference**.

```
Same lightsaber stick shape and style as reference. Change only the blade and glow
color to warm amber-yellow. Keep the same chunky rounded shape, same handle, same
soft volumetric halo. Only the color changes from green to warm amber-yellow.
```

**Element:** Name `MieczZolty` | Tag `Items`
**Description:** `short glowing amber-yellow lightsaber stick, same shape as MieczZielony, warm yellow neon halo, Pixar 3D, black background`

---

### MieczCzerwony

Generuj z **MieczZielony attached jako reference**.

```
Same lightsaber stick shape and style as reference. Change only the blade and glow
color to deep vivid red. Keep the same chunky rounded shape, same handle, same
soft volumetric halo. Only the color changes from green to deep cold red.
```

**Element:** Name `MieczCzerwony` | Tag `Items`
**Description:** `short glowing deep red lightsaber stick, same shape as MieczZielony, cold red neon halo, Pixar 3D, black background`

---

### MieczPodwojny – podwójne ostrze (jak Darth Maul)

Generuj z **MieczZielony attached jako reference**.

```
Same lightsaber style as reference. This is a DOUBLE-BLADED lightsaber staff:
glowing vivid green blades extend from BOTH ends of a central cylindrical handle.
The staff floats horizontally on a pure black background. Both blades glow with the
same vivid green neon halo. Same Pixar 3D toy-like style, chunky rounded design.
No text, no watermark.
```

**Element:** Name `MieczPodwojny` | Tag `Items`
**Description:** `double-bladed green lightsaber staff, glowing vivid green blades extending from both ends of central handle, horizontal floating, Pixar 3D, black background`

---

## KRAINY – do wygenerowania (tag: Scenes)

Trzy stany tego SAMEGO pustkowia. Generuj po kolei – każdy z referencją poprzedniego.

**Kolejność:** SwiatJasny → SwiatCiemny (ref: SwiatJasny) → SwiatOdrodzenie (ref: SwiatCiemny)

---

### SwiatJasny – baza

Generuj **bez referencji**.

```
Stylized surreal 3D CGI landscape, smooth flowing barren terrain with luminous
energy streams glowing softly in the ground surface, minimal organic hills in the
background, wide empty open space, pastel purple and soft lavender sky, dreamy
calm atmosphere, subtle ambient glow from the ground lines, cinematic depth,
Pixar-style soft 3D rendering. No characters, no flowers, no trees. No text,
no watermark.
```

**Element:** Name `SwiatJasny` | Tag `Scenes`
**Description:** `surreal 3D barren terrain, glowing energy streams on ground, pastel purple-lavender sky, dreamy atmosphere, Pixar style, no characters`

---

### SwiatCiemny

Generuj z **SwiatJasny attached jako reference**.

```
Same terrain, same barren landscape, same ground energy streams as reference.
Transform the atmosphere: dark stormy sky with heavy grey-purple storm clouds,
heavy rain falling across the entire scene, puddles forming on the glowing ground,
the ground energy streams now cold and dim, overall palette shifted to cold grey-blue
with deep violet shadows, heavy oppressive atmosphere. No characters, no text.
```

**Element:** Name `SwiatCiemny` | Tag `Scenes`
**Description:** `same barren terrain as SwiatJasny but dark rainy stormy, heavy rain, cold grey-violet palette, dim ground streams, no characters`

---

### SwiatOdrodzenie

Generuj z **SwiatCiemny attached jako reference**.

```
Same terrain and barren landscape as reference. The storm is clearing: a single
warm golden ray of sunlight breaks through the parting clouds in the background.
In the foreground, one small vivid flower blooms upward from the glowing ground.
The ground energy streams warm from cold grey to soft amber-green. The sky shifts
from dark to soft blue-purple with golden edges. Quietly hopeful atmosphere.
No characters, no text.
```

**Element:** Name `SwiatOdrodzenie` | Tag `Scenes`
**Description:** `same barren terrain, storm clearing, single golden sunray, one small flower blooming, ground streams warming amber-green, hopeful atmosphere, no characters`

---

## Pełna lista assetów

| Element | Tag | Status |
|---|---|---|
| `WYKLUCZONY- blue` | Characters | **GOTOWY w Kling** |
| `Pomagier - yellow` | Characters | **GOTOWY w Kling** |
| `Sprawca - burgun red` | Characters | **GOTOWY w Kling** |
| `Sprawca2 - pink` | Characters | **GOTOWY w Kling** |
| `MieczZielony` | Items | Do wygenerowania – baza |
| `MieczZolty` | Items | Do wygenerowania + MieczZielony ref |
| `MieczCzerwony` | Items | Do wygenerowania + MieczZielony ref |
| `MieczPodwojny` | Items | Do wygenerowania + MieczZielony ref |
| `SwiatJasny` | Scenes | Do wygenerowania – baza |
| `SwiatCiemny` | Scenes | Do wygenerowania + SwiatJasny ref |
| `SwiatOdrodzenie` | Scenes | Do wygenerowania + SwiatCiemny ref |

---

## Opis postaci w promptach – ściągawka

Używaj tych opisów w promptach żeby Kling wiedział o którą postać chodzi:

| Asset | Opis w promptach |
|---|---|
| `WYKLUCZONY- blue` | `the small pale grey-blue ghost figure (Wykluczony)` |
| `Pomagier - yellow` | `the warm golden yellow ghost figure (Pomagier)` |
| `Sprawca - burgun red` | `the dark burgundy-red ghost figure` |
| `Sprawca2 - pink` | `the hot pink fuchsia ghost figure` |

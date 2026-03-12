# Bohaterowie – referencje dla Kling AI (Create Element)

## Jak wypełnić Create Element

1. Wgraj główne zdjęcie (front-facing) jako pierwsze
2. "Add additional angles (from 1 to 3)" – wgraj 1-2 dodatkowe kąty tej samej postaci
3. Tag: **Characters** dla postaci, **Scenes** dla lokacji
4. Name: krótka nazwa (Marta, Kacper, etc.)
5. Description: max 100 znaków – kluczowe cechy wyglądu (NIE rola w historii)

---

## MARTA – Obserwatorka

**Element description (wklej do pola opisu, max 100 znaków):**
```
teenage girl, dark wavy brown hair, thin glasses, green hoodie, thoughtful expression
```

**Zdjęcie główne:** frontalne, twarz + klatka, patrzący prosto w obiektyw

**Dodatkowe kąty – prompty do Image Generation:**

Kąt 2 – profil 3/4:
```
Polish teenage girl, 16 years old, dark brown wavy hair, thin glasses, green hoodie,
three-quarter profile view, looking slightly to the side, neutral school background,
natural window light, photorealistic, no makeup, realistic photography
```

Kąt 3 – patrzy w dół / w telefon (relevatny do sceny zapisywania):
```
Polish teenage girl, 16 years old, dark brown wavy hair, thin glasses, green hoodie,
looking down at a phone in her hands, concentrated expression, soft top-down light,
neutral background, close-up portrait, photorealistic, realistic photography
```

**Masz już dużo kątów w historii** – z galerii wybierz: front, 3/4, i jeden z pełną sylwetką.
Nie generuj od nowa jeśli są dobre – Select from History.

---

## KACPER – Ofiara

**Element description:**
```
teenage boy, short light brown hair, slim, grey t-shirt, shy withdrawn expression
```

**Zdjęcie główne:** frontalne, twarz + klatka

**Dodatkowe kąty – prompty:**

Kąt 2 – profil boczny:
```
Polish teenage boy, 15 years old, short light brown hair, slim build, grey t-shirt,
side profile view, looking straight ahead, neutral school locker background,
realistic photography, soft natural light, photorealistic
```

Kąt 3 – pochylony / przytłoczony:
```
Polish teenage boy, 15 years old, short light brown hair, slim build, grey t-shirt,
slightly hunched posture, looking down at the floor, three-quarter view,
neutral school background, realistic photography, photorealistic
```

---

## SPRAWCY – Dwójka

**Element description:**
```
two teenage boys, dark hair sports jacket, buzz cut striped shirt, smirking confident
```

Uwaga: Create Element działa najlepiej z jedną twarzą. Możesz:
- Stworzyć dwa oddzielne elementy (Sprawca 1, Sprawca 2)
- Albo użyć jednego elementu (chłopak w kurtce sportowej) jako dominującego

**Element description – Sprawca 1 (kurtka sportowa):**
```
teenage boy, short dark hair, sports jacket, confident smirking expression, school setting
```

Kąt 2 – Sprawca 1 z boku:
```
Polish teenage boy, 16-17 years old, short dark hair, wearing a dark sports jacket,
side profile, school corridor background, confident posture, realistic photography, photorealistic
```

**Element description – Sprawca 2 (pasiasta koszula):**
```
teenage boy, buzz cut, navy striped shirt, smirking expression, school setting
```

---

## NAUCZYCIELKA – epizod

**Element description:**
```
woman 40s, light brown hair low bun, beige blazer, holding papers, distracted hurried
```

**Zdjęcie główne:** masz już dobrą w historii (kobieta z papierami w korytarzu)

Kąt 2 – od tyłu / odchodząca:
```
Polish female teacher, 40s, light brown hair in low bun, beige blazer, walking away
down a school corridor holding papers and coffee cup, rear 3/4 view, fluorescent
school lighting, realistic photography, photorealistic
```

---

## PEDAGOG SZKOLNY – końcówka

**Element description:**
```
woman 35-40, dark shoulder-length hair, navy cardigan, warm attentive expression, office
```

**Zdjęcie główne:** masz już dobrą w historii (kobieta przy biurku)

Kąt 2 – słuchająca, lekko pochylona:
```
Polish female school counselor, 35-40 years old, dark shoulder-length hair, navy cardigan,
leaning slightly forward across a desk listening attentively, warm office lamp light,
three-quarter view, realistic photography, photorealistic
```

---

## SCENY – elementy lokacji (tag: Scenes)

Stwórz oddzielne elementy Scene żeby zachować spójność wyglądu szkoły.

### Scene: Klasa szkolna

**Element name:** Klasa | **Tag:** Scenes

**Element description:**
```
modern Polish high school classroom, rows of desks, large windows, warm natural light
```

**Prompt do Image Generation (generuj 2-3 warianty):**
```
Empty modern Polish high school classroom, rows of wooden desks and chairs, large windows
with natural daylight, whiteboard at front, educational posters on walls, warm muted tones,
wide shot, realistic interior photography, photorealistic, no people
```

Kąt 2 (z perspektywy ucznia):
```
Polish high school classroom viewed from student desk level, other desks in foreground,
teacher's desk and whiteboard in background, natural window light from left, realistic
interior photography, photorealistic, no people, warm tones
```

### Scene: Korytarz szkolny

**Element name:** Korytarz | **Tag:** Scenes

**Element description:**
```
school hallway, metal lockers both sides, fluorescent light, linoleum floor, Polish school
```

**Prompt:**
```
Polish high school hallway corridor, metal lockers lining both walls, fluorescent overhead
lighting, linoleum floor, doors visible at end of corridor, realistic interior photography,
photorealistic, no people, institutional atmosphere
```

### Scene: Stołówka

**Element name:** Stołówka | **Tag:** Scenes

**Prompt:**
```
Polish school cafeteria, long tables with plastic chairs, food counter in background,
warm overhead lighting, realistic interior photography, photorealistic, no people
```

### Scene: Gabinet pedagoga

**Element name:** Gabinet | **Tag:** Scenes

**Prompt:**
```
Small school counselor office, wooden desk with laptop and papers, two chairs across
from each other, bookshelf, warm desk lamp light, realistic interior photography,
photorealistic, cozy and private atmosphere, no people
```

---

## Strategia łączenia elementów w scenie

Kling pozwala wpiąć kilka elementów naraz (postać + scena):
- Wpnij element postaci + element sceny razem
- Postać daje twarz, scena daje środowisko
- Jeśli jedno dominuje za mocno – zmniejsz jego "influence" w UI

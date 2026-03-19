# Prompty scen – Kling AI VIDEO | Film 5: „Nie jesteś sama/sam"

## Specyfikacja

| Parametr | Wartość |
|---|---|
| Styl | Photorealistic |
| Rozdzielczość | 1080p |
| FPS | 25 |
| Format | 16:9 poziomy |
| Lektor | ElevenLabs – czyta cały film |

**Zasada globalna:** Do każdego promptu dopisz na końcu:
`no watermark, no text, no subtitles, no logo, photorealistic, 4K`

---

## Ściągawka – postacie

| Asset w Kling | Opis w promptach |
|---|---|
| `Hanna` | `a woman in her mid-50s, dark hair with gray pulled back, navy blue blazer over light blouse, dignified posture` |
| `Tariq` | `a man in his early 30s, Middle Eastern appearance, dark brown skin, short black beard, white button-up shirt` |
| `Zosia` | `a young woman in her early 20s, short asymmetric light hair, denim jacket with small rainbow pin on the lapel` |
| `Szef_Hanny` | `a man in his early 50s, ordinary unremarkable face, light blue shirt, dark suit jacket, middle manager look` |
| `Prowadzaca` | `a woman in her 40s, warm friendly appearance, soft-colored sweater, gentle smile` |
| `Urzednik` | `a Polish male office clerk, mid-50s, ordinary face, light shirt, no tie, slightly hunched posture behind a counter, bureaucratic indifference in his expression` |
| `Bohater` | `a Polish man, early 30s, ordinary unremarkable face, short brown hair, casual hoodie or simple shirt, neutral everyday expression` |

## Ściągawka – miejsca (scene assets)

| Asset w Kling | Opis w promptach |
|---|---|
| `Pokoj_Pretium` | `small meeting room, white walls, gray carpet, white IKEA tables and chairs, large window with green trees outside` |
| `Urzad` | `Polish public service office interior. Large open hall, light beige tiled floor with dark gray carpet strips running across it. Long wooden service counters (warm brown wood panels) with glass and plexiglass partitions separating clerk from visitor. Large silver cylindrical column in the center. White suspended ceiling with square recessed LED lights and fluorescent strips. Red accent wall with yellow signage in the background. Numbered service windows along the counter. Brochure holders on the counter surface. Glass windows on the right showing bare trees outside. Bright institutional lighting. Clean, formal, impersonal atmosphere.` |
| `Autobus_miejski` | `city bus interior, blue fabric seats, gray metal handrails and poles, large windows with street view outside, daytime` |
| `Pokoj_domowy` | `simple home room, desk with closed laptop, plain wall, soft warm lamp light, minimal furniture, ordinary everyday space` |

---

## MECHANIKA "CZY TO DYSKRYMINACJA? TAK." – jak to zrobić w Resolve

Po każdej sytuacji wstawiasz w Resolve:
1. **Freeze frame** ostatniej klatki zbliżenia twarzy → odbarw do czarno-białego (Color page → Saturation = 0)
2. Na ścieżce wyżej wklej **QUIZ_Przyciski** jako overlay
3. Na ścieżce tekstowej: `"Czy to dyskryminacja?"` → po 1 sek: `"Tak."`

Klip QUIZ_Przyciski generujesz raz – używasz go 3 razy.

---

## QUIZ_Przyciski – klip graficzny (użyj 3x)

**Elementy:** brak assetów postaci
**Tryb:** Standard | **Długość:** 4 sek

```
Two large circular indicator buttons side by side on a pure black background.
Left button: red, unlit, dark and dim.
Right button: green, glowing brightly, pulsing slightly with soft light.
No text, no labels, no other elements. Clean, minimal, graphic design style.
The green button is clearly "on" / selected.
Centered in frame, slight glow halo around the green button.
Flat graphic, high contrast.
no watermark, no text, no subtitles, no logo
```

**Montaż w Resolve:** opacity overlay ~85% na freeze frame BW, lub pełne czarne tło jeśli overlay nie działa.

---

## S0a – Bohater w pokoju: głowi się, wspomina (lektor: "Czasem trudno powiedzieć")

**Elementy:** `Bohater` + `Pokoj_domowy`
**Tryb:** Standard | **Długość:** 5 sek

```
Simple home room, desk, soft warm lamp light. A Polish man in his early 30s,
short brown hair, casual hoodie, sits at a desk and stares into the middle
distance — thoughtful, slightly uneasy, like he is replaying a memory in his
head. He rests his chin on his hand. Expression: uncertain, processing something.
No laptop open. Still, quiet atmosphere.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater] [scene reference: Pokoj_domowy]
```

---

## S0a2 – Bohater liczy na palcach i kręci głową (lektor: "jeśli ktoś systematycznie")

**Elementy:** `Bohater` + `Pokoj_domowy`
**Tryb:** Standard | **Długość:** 3 sek

```
Simple home room, soft warm lamp light. Close-up on a Polish man in his early
30s, casual hoodie, sitting at a desk. He slowly leans back in his chair and
raises both hands to cover his face — then drags them slowly downward, revealing
a heavy, exhausted expression. He stares blankly forward. The realization of
something he can no longer ignore.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater] [scene reference: Pokoj_domowy]
```

---

## S0b – Bohater przy laptopie: zgłasza, zamyka, zaciska pięść – MULTICAM 8 sek
(lektor: "Jeśli ktoś systematycznie wyklucza – zgłoś to. Ale przede wszystkim zadbaj o siebie.")

**Elementy:** `Bohater` + `Pokoj_domowy`
**Tryb:** Standard | **Długość:** 8 sek
**Montaż:** Multicam – 2 ujęcia zmontowane w Resolve

**Shot 1 (4 sek) – MacBook, światło ekranu, wysyła zgłoszenie:**
```
Simple home room, minimal furniture, soft warm lamp in background. Close-medium
shot of a Polish man in his early 30s, short brown hair, casual hoodie, sitting
at a desk. He is typing on a MacBook laptop — the pale blue-white screen glow
lights his face from below. His expression: focused, resolute. He finishes typing
and presses Enter — a definitive gesture. NO visible text on screen — screen
blurred or viewed at an angle, only the glow is visible.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater] [scene reference: Pokoj_domowy]
```

**Shot 2 (4 sek) – zamyka laptopa, patrzy na pięść, zaciska ją:**
```
Same simple home room, soft warm lamp light. Medium shot of the same Polish man,
early 30s, casual hoodie. He slowly closes the MacBook lid with both hands —
calm, deliberate. Then he lowers his gaze to his own fist resting on the desk.
He looks at it for a moment — then clenches it slowly and firmly. Expression:
inner resolve, taking ownership of himself. Not aggressive — quiet determination.
The action says: I reported it. Now I take care of myself.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater] [scene reference: Pokoj_domowy]
```

---

## S0c – Bohater zakłada kurtkę i wychodzi (lektor: "Ale przede wszystkim zadbaj o siebie") – MULTICAM 6 sek

**Elementy:** `Bohater` + `Pokoj_domowy`
**Tryb:** Professional | **Długość:** 6 sek
**Montaż:** Multicam – 2–3 ujęcia zmontowane w Resolve

**Shot 1 (2 sek) – wstaje od biurka:**
```
Simple home room. A Polish man in his early 30s stands up from the desk,
pushes the chair back. Purposeful movement. Medium shot.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater] [scene reference: Pokoj_domowy]
```

**Shot 2 (2 sek) – zakłada kurtkę:**
```
Home interior, hallway or near the door. The same man puts on a jacket —
calm, deliberate. Medium shot.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater]
```

**Shot 3 (2 sek) – wychodzi przez drzwi:**
```
Home door or building entrance. The man opens the door and steps out into
daylight. Back to camera or side view. He goes.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater]
```

---

## S0d – Indywidualna konsultacja w Pretium: bohater i prowadząca – MULTICAM 3 sek

**Elementy:** `Bohater` + `Prowadzaca` + `Pokoj_Pretium`
**Tryb:** Standard | **Długość:** 3 sek
**Montaż:** Multicam – 2 ujęcia zmontowane w Resolve

**Shot 1 (2 sek) – szeroki: siedzą naprzeciwko siebie:**
```
Small meeting room, white walls, gray carpet, white table, large window with
green trees. A Polish man in his early 30s sits on one side of the table.
A woman in her 40s, soft sweater, warm expression, sits across from him —
speaking or listening attentively. Just the two of them. Natural daylight.
Medium-wide shot.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater + Prowadzaca] [scene reference: Pokoj_Pretium]
```

**Shot 2 (1 sek) – zbliżenie: twarz bohatera, słucha:**
```
Close-up of a Polish man, early 30s, short brown hair. He is listening to
someone off-screen. Expression: cautiously open, slightly relieved.
Natural daylight from the side.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Bohater]
```

---

## S1a – Korytarz biurowy: Hanna idzie

**Elementy:** `Hanna`
**Tryb:** Standard | **Długość:** 5 sek

```
Office corridor, modern workplace, fluorescent ceiling lighting.
A woman in her mid-50s, dark hair with gray pulled back, navy blue blazer
over light blouse, walks confidently along the corridor toward a closed door
at the end. She carries a folder. Medium shot, camera slightly in front of her,
she walks toward it.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna]
```

---

## S1b – Korytarz biurowy: szef blokuje Hannę i coś tłumaczy

**Elementy:** `Hanna` + `Szef_Hanny`
**Tryb:** Standard | **Długość:** 5 sek

```
Office corridor. A man in his early 50s, ordinary face, light blue shirt and
dark suit jacket, stands in a doorway. He is speaking to a woman in her mid-50s
(dark blazer) who has just approached — he gestures with his palm out, explaining
something, shaking his head slightly. The woman stops, looks at him, expression
uncertain. He turns and closes the door behind him, leaving her standing alone
in the corridor. Medium shot.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna + Szef_Hanny]
```

---

## S2 – Zbliżenie twarzy Hanny → FREEZE → QUIZ

**Elementy:** `Hanna`
**Tryb:** Standard | **Długość:** 4 sek

```
Close-up of a woman's face, mid-50s, dark hair with gray, standing in an
office corridor. Expression: hurt and uncertain, processing what just happened,
quietly asking herself if this was normal. Eyes slightly glossy but no tears.
Soft side lighting from fluorescent office light.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna]
```

**W Resolve:** ostatnia klatka → BW → QUIZ_Przyciski overlay (4 sek)

---

## S3a – Kantyna: Tariq opowiada

**Elementy:** `Tariq`
**Tryb:** Standard | **Długość:** 5 sek

```
Office cafeteria or break room. A group of 4 people sitting at a lunch table.
A man in his early 30s, Middle Eastern appearance, dark skin, short black beard,
white shirt — is talking animatedly, gesturing with his hands. The other three
colleagues are white Central European in appearance — two men and one woman,
casual office wear, light skin, light or brown hair. They are listening and eating.
Warm cafeteria lighting, medium shot.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Tariq]
```

---

## S3b – Kantyna: kolega naśladuje akcent → FREEZE → QUIZ

**Elementy:** `Tariq`
**Tryb:** Standard | **Długość:** 5 sek

```
Office cafeteria. Same lunch table. A white European male colleague in casual
office wear starts mimicking a coworker's accent — opening and closing his
fingers like a talking puppet, grinning at the other white colleagues. The
white colleagues laugh. Camera cuts to close-up of the Middle Eastern man's
face (dark skin, short black beard): his smile slowly fades, eyes lower,
expression quietly hurt. He says nothing.
Warm cafeteria lighting.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Tariq]
```

**W Resolve:** ostatnia klatka (twarz Tariqa) → BW → QUIZ_Przyciski overlay (4 sek)

---

## S5a – Urząd: Zosia podchodzi do okienka – MULTICAM 2 sek

**Elementy:** `Zosia` + `Urzad`
**Tryb:** Standard | **Długość:** 2 sek
**Montaż:** Multicam – 2 ujęcia zmontowane w Resolve

**Shot 1 (1 sek) – szeroki: Zosia idzie przez halę:**
```
Polish public service office, large open hall, light beige tiled floor with
dark gray carpet strips, silver cylindrical column in the center, wooden
service counters with glass partitions in the background, red accent wall
with yellow signage, bright institutional ceiling lights.
A young woman in her early 20s, short asymmetric light hair, denim jacket
with a small rainbow pin on the lapel, casual backpack — walks across the
hall toward the service counter. Medium-wide shot from behind or the side.
Natural purposeful walk, slightly uncertain.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia] [scene reference: Urzad]
```

**Shot 2 (1 sek) – medium: Zosia staje przed okienkiem:**
```
Polish public service office. A young woman in her early 20s, short light hair,
denim jacket with small rainbow pin — stands on the PUBLIC side of a service
window. The window has a thick glass or plexiglass partition fixed above a
wooden counter. She faces the glass, about to speak. Behind the glass, a male
clerk is seated at his desk — visible but separated. Medium shot from the side,
showing both the glass partition and Zosia facing it.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia] [scene reference: Urzad]
```

---

## S5b – Urząd: urzędnik ignoruje, Zosia w szoku → FREEZE → QUIZ

**Elementy:** `Zosia` + `Urzednik` + `Urzad`
**Tryb:** Standard | **Długość:** 5 sek
**Montaż:** Multicam – 2 ujęcia zmontowane w Resolve

**Shot 1 (3 sek) – medium: Zosia mówi, urzędnik za szybą ignoruje:**
```
Polish public service office service window. IMPORTANT: the clerk is SEATED
BEHIND a fixed glass or plexiglass partition mounted above a wooden counter.
He is on the STAFF side, sitting at his desk. The young woman is on the PUBLIC
side, standing facing the glass, speaking toward him through the partition.
The glass is clearly visible between them — it physically separates them.

The clerk: a Polish man, mid-50s, plain light short-sleeve shirt, gray hair,
sitting at desk — he looks down at papers on his desk, deliberately not making
eye contact. His expression: flat, bored, subtly dismissive. He does not respond.
The young woman: early 20s, short light hair, denim jacket with small rainbow
pin, hands open in a explaining gesture — she is trying to talk to him, leaning
slightly toward the glass.

Shot framed so both are visible: her face and gesturing hands on one side,
him seated behind the glass on the other. Institutional overhead lighting.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia + Urzednik] [scene reference: Urzad]
```

**Shot 2 (2 sek) – zbliżenie: twarz Zosi, reakcja:**
```
Close-up of a young woman's face, early 20s, short light asymmetric hair.
She is standing at a service counter. Her expression shifts from hopeful to
quietly stunned — eyes slightly widened, lips pressed together. A mix of
confusion and hurt: did that just happen? She glances briefly to the side,
then back at the window. Soft institutional overhead light.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia]
```

**W Resolve:** ostatnia klatka (twarz Zosi) → BW → QUIZ_Przyciski overlay (4 sek)

---

## S6a – Autobus: Zosia stoi sama

**Elementy:** `Zosia` + `Autobus_miejski`
**Tryb:** Standard | **Długość:** 5 sek

```
City bus interior, blue fabric seats, gray metal handrails, large windows.
A young woman in her early 20s, short light hair, denim jacket with small
rainbow pin on the lapel, casual backpack — stands holding a metal handrail.
She looks slightly uneasy, glancing around. Medium shot, natural window light.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia] [scene reference: Autobus_miejski]
```

---

## S6b – Autobus: chłopaki szepczą → FREEZE → QUIZ

**Elementy:** `Zosia` + `Autobus_miejski`
**Tryb:** Standard | **Długość:** 5 sek

```
City bus interior, blue fabric seats, gray metal handrails. A group of 2–3
young men sitting together glance toward a young woman (off-screen), exchange
looks, lean in and whisper to each other with slight smirks. Camera cuts to
the young woman's face — she notices, her expression tightens. Close-up on
her face at the end of the clip. Natural window light.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia] [scene reference: Autobus_miejski]
```

**W Resolve:** ostatnia klatka (twarz Zosi) → BW → QUIZ_Przyciski overlay (4 sek)

---

## S9a – Grupa wsparcia: całość (wide shot)

**Elementy:** `Hanna` + `Tariq` + `Zosia` + `Prowadzaca` + `Pokoj_Pretium`
**Tryb:** Professional | **Długość:** 5 sek

```
Small meeting room, white walls, gray carpet, white rectangular table, white chairs.
Large window with green trees directly behind the middle person on the far side.
EXACTLY 4 people, no more, no less.

Seating arrangement — looking from camera:
FAR SIDE of table (backs toward window): three participants in a row left to right:
  1. Hanna — woman mid-50s, dark blazer, dark hair with gray
  2. Zosia — young woman early 20s, short light hair, denim jacket
  3. Tariq — man early 30s, Middle Eastern features, dark beard, white shirt
NEAR SIDE of table (facing camera and the three participants):
  4. Prowadząca — woman 40s, soft sweater, warm expression — speaking, hands on table

The facilitator is speaking to the three participants across the table.
The three participants listen — relaxed, attentive, slight nods.
Medium-wide shot showing all four people and the window with trees in the background.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna + Tariq + Zosia + Prowadzaca]
[scene reference: Pokoj_Pretium]
```

---

## S9b – Grupa wsparcia: medium shot (prowadząca i uczestnicy)

**Elementy:** `Hanna` + `Tariq` + `Zosia` + `Prowadzaca` + `Pokoj_Pretium`
**Tryb:** Standard | **Długość:** 5 sek

```
Same meeting room, white walls, white table. Natural daylight from window behind participants.
EXACTLY 4 people. Camera closer — medium shot framing the facilitator on one side
and 2–3 participants on the other side of the table.
The facilitator (woman 40s, soft sweater) speaks warmly, hands on the table.
The participants across from her (including a woman mid-50s in dark blazer,
a young woman in denim jacket, a Middle Eastern man in white shirt) listen,
nod gently, exchange brief glances. Safe, calm atmosphere.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna + Tariq + Zosia + Prowadzaca]
[scene reference: Pokoj_Pretium]
```

---

## S10a / S10b / S10c – Zbliżenia twarzy (3 × 3 sek)

**Elementy:** po 1 postaci | **Tryb:** Standard | **Długość:** 3 sek każdy

**S10a – Hanna:**
```
Close-up of a woman, mid-50s, dark hair with gray, in a bright room with
natural window light. Listening to someone off-screen. Expression: calm,
present, slightly relieved.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Hanna]
```

**S10b – Tariq:**
```
Close-up of a man, early 30s, Middle Eastern features, short black beard,
natural daylight from the side. Listening. Expression: relaxed, at ease.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Tariq]
```

**S10c – Zosia:**
```
Close-up of a young woman, early 20s, short asymmetric hair. Natural daylight.
A small genuine smile, listening to someone off-screen.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
[character reference: Zosia]
```

---

## S11 – Wejście do budynku Centrum

**Opcja A – Kling:**
```
Exterior of a mid-size urban office building, entrance with glass doors,
clean facade, daylight. A person approaches and enters. Calm, welcoming
atmosphere.
no watermark, no text, no subtitles, no logo, photorealistic, 4K.
```
**Opcja B (lepsza):** Nagraj telefonem 8 sek wejścia przy ul. Bierutowskiej 57-59.

---

## Plan ujęć – kolejność generowania

| Klip | Tryb | Długość | Elementy |
|---|---|---|---|
| QUIZ_Przyciski | Standard | 4 sek | – |
| S0a | Standard | 5 sek | Bohater + Pokoj_domowy |
| S0a2 | Standard | 3 sek | Bohater + Pokoj_domowy |
| S0b shot 1 | Standard | 4 sek | Bohater + Pokoj_domowy |
| S0b shot 2 | Standard | 4 sek | Bohater + Pokoj_domowy |
| S0c shot 1 | Standard | 2 sek | Bohater + Pokoj_domowy |
| S0c shot 2 | Standard | 2 sek | Bohater |
| S0c shot 3 | Standard | 2 sek | Bohater |
| S0d shot 1 | Standard | 2 sek | Bohater + Prowadzaca + Pokoj_Pretium |
| S0d shot 2 | Standard | 1 sek | Bohater |
| S1a | Standard | 5 sek | Hanna |
| S1b | Standard | 5 sek | Hanna + Szef_Hanny |
| S2 | Standard | 4 sek | Hanna |
| S3a | Standard | 5 sek | Tariq |
| S3b | Standard | 5 sek | Tariq |
| S5a shot 1 | Standard | 1 sek | Zosia + Urzad |
| S5a shot 2 | Standard | 1 sek | Zosia + Urzad |
| S5b shot 1 | Standard | 3 sek | Zosia + Urzednik + Urzad |
| S5b shot 2 | Standard | 2 sek | Zosia |
| S6a | Standard | 5 sek | Zosia + Autobus_miejski |
| S6b | Standard | 5 sek | Zosia + Autobus_miejski |
| S9a | Professional | 5 sek | Hanna + Tariq + Zosia + Prowadzaca + Pokoj_Pretium |
| S9b | Standard | 5 sek | Hanna + Tariq + Zosia + Prowadzaca + Pokoj_Pretium |
| S10a | Standard | 3 sek | Hanna |
| S10b | Standard | 3 sek | Tariq |
| S10c | Standard | 3 sek | Zosia |
| S11 | Standard | 8 sek | – (lub nagranie realne) |

---

## Jeśli scena nie wychodzi po 2 próbach

**Twarz postaci nierozpoznawalna:**
```
[character reference] face must be clearly recognizable throughout the shot,
consistent facial features, do not change appearance mid-clip
```

**Za bardzo teatralnie / nie realistycznie:**
```
natural subtle acting, realistic everyday behavior, not dramatic,
not theatrical — the emotion is internal, not performed
```

**Scene reference ignorowany:**
```
the room/location must exactly match the reference image provided:
[opisz kluczowe elementy z ściągawki]
```

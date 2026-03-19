# Bohaterowie i referencje – Film 4: „Dyskryminacja nie ma jednej twarzy"

## Logika postaci

Każda z 4 postaci pojawia się DWUKROTNIE — raz jako ofiara, raz jako sprawca.
To jest serce przekazu: mechanizm pogardy nie należy do żadnej grupy.

| Postać | Scena (ofiara) | Scena (sprawca) |
|---|---|---|
| **GEJ** | S1 – przestraszony, gdy Blokers krzyczy | S2 – pogardliwy wobec Blokersa |
| **BLOKERS** | S2 – upokorzony przez Geja | S1 – agresywny wobec Geja |
| **KOBIETA** | S3 – odrzucona przez szefa-Wierzącego | S4 – zamyka drzwi Wierzącemu |
| **WIERZĄCY** | S4 – zdezorientowany, odrzucony przez Kobietę | S3 – odmawia Kobiecie stanowiska |

**Zasada generowania scen:**
W każdej scenie: **character_reference = główny bohater (ofiara)** — to jego/jej twarz musi być czytelna.
Sprawca opisywany jest tekstowo w prompcie Kling — bez osobnego assetu.

---

## 1. GEJ — `ref_gej.jpg`

**Status: GOTOWE — zdjęcie referencyjne dostarczone**

Wgraj dostarczone zdjęcie do Kling jako `character_reference`.
Zapisz jako: `ref_gej.jpg`

**Opis fizyczny:**
- Mężczyzna ok. 28–33 lat
- Krótkie blond włosy
- Biała koszulka z tęczowym nadrukiem (orzeł lub flaga)
- Europejskie rysy, uśmiech (na ref) — w scenach wyraz twarzy inny

**Opis do promptów Kling:**
```
young man, short blond hair, white t-shirt with rainbow print, European features, early 30s
```

**Rola w scenach:**
- S1: główny bohater (ofiara) — strach, dezorientacja, cofanie się
- S2: sprawca (opisany tekstowo) — stoi wyżej, patrzy z pogardą w dół

---

## 2. BLOKERS — `ref_blokers.jpg`

**Status: GOTOWE — zdjęcie referencyjne dostarczone**

Wgraj dostarczone zdjęcie do Kling jako `character_reference`.
Zapisz jako: `ref_blokers.jpg`

**Opis fizyczny:**
- Mężczyzna ok. 20–25 lat
- Czapka z daszkiem noszona tyłem
- Biała koszulka z nadrukiem, ciemne szorty
- Wygląd „z bloków", casualowy styl

**Opis do promptów Kling:**
```
young white man, backwards baseball cap, white graphic t-shirt, dark shorts, 20s, housing estate look
```

**Rola w scenach:**
- S1: sprawca (opisany tekstowo) — krzyczy, wskazuje, agresywny
- S2: główny bohater (ofiara) — upokorzenie, niepewność, smutek

---

## 3. KOBIETA — `ref_kobieta.jpg`

**Status: DO WYGENEROWANIA w Kling IMAGE mode**

Wygeneruj portret w Kling → Image Generator. Zapisz jako `ref_kobieta.jpg`.
Wgraj do Kling: Name `KobietaRef` | Tag `Characters`

**Prompt do generowania:**
```
Professional portrait photo of a Polish woman in her late 30s to early 40s,
brown or dark blonde hair pulled back or in a neat bob,
business attire — dark blazer over a white shirt,
intelligent and determined expression,
slight tiredness in the eyes but dignified posture,
neutral office background, medium close-up,
soft professional lighting, 3/4 front angle,
photorealistic, sharp focus
-- no text, no watermark, not animated, no heavy makeup, natural look
```

**Ważne wskazówki:**
- Nie może wyglądać jak modelka ani stockowe zdjęcie
- Zmęczona, ale silna — nie złamana
- Naturalne polskie rysy, nie "AI look"
- Wygeneruj 2–3 warianty, wybierz najbardziej naturalny

**Opis do promptów Kling (sceny):**
```
Polish woman, late 30s, dark blonde hair in neat bob or pulled back, dark blazer, white shirt, determined but tired expression
```

**Strój w scenach:**
- Sceny biurowe (S2a ofiara, O3a, O3b): korporacyjny — ciemny blazer, biała koszula, teczka/CV
- Sceny restauracyjne (S2b sprawca, O4a tło): **casualowy/randkowy** — sukienka lub elegantna bluzka z kardigan, NIE korporacyjny

**Rola w scenach:**
- S2b: widoczna sama w kadrze (sprawca) — restauracja, obrzydzenie, wstaje i odchodzi
- O3a/O3b: ofiara — wyproszona z biura, potem sama w korytarzu
- O4a: widoczna z tyłu (tło) — odchodzi od stolika

---

## 4. WIERZĄCY — `ref_wierzacy.jpg`

**Status: GOTOWE — zdjęcie referencyjne dostarczone**

Wgraj dostarczone zdjęcie do Kling jako `character_reference`.
Zapisz jako: `ref_wierzacy.jpg`

**Opis postaci (z dostarczonego zdjęcia):**
- Mężczyzna ok. 45–52 lat
- Krótkie siwe/pepper włosy, atletyczna budowa, mocna szczęka
- Ciemna kurtka lub ciemna koszula (casualowo-elegancki, NIE garnitur)
- Srebrny krzyżyk/krucyfiks wyraźnie widoczny na szyi — **to kluczowy element wizualny**

**Opis do promptów Kling (sceny):**
```
Polish man, late 40s to early 50s, short salt-and-pepper hair, dark jacket,
silver cross necklace clearly visible at the collar, athletic build, composed expression
```

**Rola w scenach:**
- S2a: widoczny sam w kadrze (sprawca) — siedzi za biurkiem jako szef, kręci głową, wskazuje drzwi w prawo
- O4a: ofiara — w restauracji patrzy jak kobieta odchodzi
- O4b: ofiara reakcja — sam przy stoliku, patrzy na krzyżyk

---

## 5. SAMOTNA POSTAĆ — S5 (bez referencji)

**Status: Generować bez character_reference — sylwetka, twarz niewidoczna**

Scena S5 (16:9, 8s): osoba siedząca samotnie w rogu ciemnego pokoju.
Twarz niewidoczna lub w cieniu — celowo anonimowa (symbolizuje każdego).

**Prompt do Kling:**
```
Cinematic wide shot, 16:9, a lone figure sitting curled up in the dark corner of a dimly lit room,
back slightly turned or face hidden in shadow, dim moody lighting from one side,
emotional atmosphere of isolation and silence, slow gentle camera push-in,
photorealistic, high quality, no text
```

Nie wymaga character_reference ani osobnego pliku portretu.

---

## Kolejność wgrywania assetów do Kling

| Krok | Asset | Skąd | Uwaga |
|---|---|---|---|
| 1 | `ref_gej.jpg` | Zdjęcie dostarczone | Wgraj jako character_reference |
| 2 | `ref_blokers.jpg` | Zdjęcie dostarczone | Wgraj jako character_reference |
| 3 | `ref_kobieta.jpg` | **Wygenerować** (prompt wyżej) | Wgraj po zatwierdzeniu wariantu |
| 4 | `ref_wierzacy.jpg` | **Wygenerować** (prompt wyżej) | Wgraj po zatwierdzeniu wariantu |

---

## Mapa użycia character_reference w scenach

| Scena | Czas | character_reference | Sprawca (opisany tekstowo) |
|---|---|---|---|
| S1 | 0:03–0:08 (5s) | `ref_gej.jpg` | Blokers — backwards cap, aggressive, pointing |
| S2 | 0:08–0:16 (8s) | `ref_blokers.jpg` | Gej — rainbow t-shirt, standing higher, contemptuous look |
| S3 | 0:16–0:24 (8s) | `ref_kobieta.jpg` | Wierzący — dark jacket, cross necklace, blocking door |
| S4 | 0:24–0:34 (10s) | `ref_wierzacy.jpg` | Kobieta — dark blazer, closing the door |
| S5 | 0:52–1:00 (8s) | BRAK | Sylwetka anonimowa |

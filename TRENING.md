# Trening Kuby: wspólny plik

Jedyne źródło prawdy o treningu. Czytają i zapisują tu **Claude i Hermes**. Przed sesją czytasz cały plik, po każdym ćwiczeniu dopisujesz wynik do „Historii sesji”, po sesji aktualizujesz „Punkty odniesienia”. Każda zmiana planu, ciężaru albo zasad (każdy „upgrade”) ląduje tutaj, z datą, i trafia do „Dziennika zmian”.

Zasady pracy z gitem: [HERMES.md](HERMES.md#synchronizacja). Charakter trenera: [CHARAKTER.md](CHARAKTER.md).

## 1. Cel i kontekst

- Powrót po ~4 mies. przerwy, siła i moc pod BJJ, rozwój klatki i ramion. Plan różnorodny, bez przemęczania obok BJJ.
- BJJ czasowo wstrzymane (od 30.09.2026), więc siłownia co 2–3 dni w rotacji A→B→C. Po powrocie do BJJ: 2 sesje siłowe/tydz.
- Masa ciała 81,5 kg (1.10.2026, rano). Białko 150–165 g/dzień (dieta roślinna). Szczegóły: [lifestyle.md](lifestyle.md).

## 2. Jak prowadzimy sesję (ustalone przez Kubę, zawsze)

1. Na start pytanie o energię 1–10 i ból.
2. Trener podaje **jedno** ćwiczenie: serie, powtórzenia, ciężar startowy (z punktów odniesienia), przerwa i link do filmiku YT z techniką (sekcja 7). Nie wypisywać całej sesji z góry.
3. Kuba robi ćwiczenie. Trener pyta: powtórzenia, ciężar, RIR, ból.
4. Wynik zapisany **od razu** w sekcji 5 (commit + push), dopiero potem kolejne ćwiczenie.
5. Na koniec pytanie o zmęczenie 1–10, dopisane do wpisu sesji.

Jedną sesję prowadzi jeden trener (Claude albo Hermes), nie obaj naraz.

### Pojęcia

- RIR = powtórzenia w zapasie. Energia przed i zmęczenie po to osobne skale 1–10.
- Hantle: ciężar na jeden hantel. Sztanga: z gryfem. Trap-bar: talerze na stronę (gryf ~25 kg, niepotwierdzone). Glute Drive: blachy na stronę.
- „Brak danych” ≠ zero ani brak bólu. „Według polecenia” = wykonane bez nowych liczb.
- Farmer pominięty; nie przywracać automatycznie.
- Daty w tekście `D.MM`, w nazwach plików `RRRR-MM-DD`.

## 3. Aktualny plan (od 30.09.2026, rotacja A → B → C)

Moc na początku sesji. Wejście stopniowe:
- Rotacja 1 (B, C, A): 2 serie robocze RIR 3, moc 3 serie.
- Rotacja 2: 3 serie RIR 3. (Od 5.10 w ciężkich już 3 serie, decyzja trenera, bo brak BJJ.)
- Od rotacji 3: 3 serie, RIR 2–3 w ciężkich.
- Ciężar +2,5–5% tylko gdy RIR ≥3 przy górnym zakresie powtórzeń.
- Co 4. rotacja lżejsza (2 serie RIR 4).
- Nowe ćwiczenie bez danych: 1. seria zachowawczo, korekta wg RIR.
- Jeśli Kuba opuści dzień, robi następną sesję z kolejki (rotacja się przesuwa, nie przeskakuje).
- Energia przed <5 albo zmęczenie po ostatniej ≥8: 2 serie zamiast 3.

**A góra:** rzut piłką / plyo pompki 4×3–5; skos sztangą 3×6–8; podciąganie neutralne 3×4–5; dipy 3×6–8; wiosło z podparciem 3×8–10; unoszenie bokiem 2×12–15.

**B dół:** skok na skrzynię 4×3; trap-bar 3×5 (zajęty: martwy klasyczny); bułgarski 3×8/str; hip thrust 3×8; łydki skoczne 2×15; od 9.10 Nordic curl 2×3 na koniec.

**C całość:** skok w dal 4×3; goblet (front squat ze sztangą na razie pomijany) 3×6–8; hantle płasko 3×8–10; RDL 3×8; biceps + triceps 2×10–12; Pallof / chaos Pallof 2×10/str.

**Dni bez siłowni:** 15 min mobility z Planu 5 (D1–D3 po kolei, [plany-historyczne.md](plany-historyczne.md)).

**Rozgrzewka:** cardio 4 min; mobilizacja bioder w klęku 8/str; rotacje piersiowe 6/str; pompki łopatkowe na kolanach 10; serie narastające.

## 4. Plan bieżącego tygodnia

Pełny raport: najnowszy plik w [raporty/](raporty/). Niedzielny routine nadpisuje tę sekcję.

**19–25.10.2026:** pon 19.10 C (rotacja 2) · wt mobility D1 · śr 21.10 A (rotacja 2) · czw mobility D2 · pt 23.10 B (rotacja 3: RIR 2–3 w ciężkich) · sob mobility D3 lub wolne · ndz 25.10 C (rotacja 3) tylko jeśli energia ≥7, inaczej pon 26.10. Wszędzie 3 serie robocze.

**Zmiana 20.10:** C zrobione we wtorek 20.10 (19.10 nieodbyte), więc dalej: śr 21.10 mobility D1 delikatnie dla prawego biodra · **czw 22.10 A** · pt mobility D2 · **sob 24.10 B** (warunek: prawe udo bez bólu; jeśli boli, skrzynia i pogo wypadają) · **pon 26.10 C**.

Ciężary na C 19.10: rozgrzewka + izometria szyi 2×10 s/kierunek · skok w dal 4×3 (pobić 220 cm) · goblet 24 kg 3×8 · hantle płasko 20 kg 3×8–10 · RDL hantle 26 kg 3×8 · biceps 12 kg + triceps wyciąg 17,5 kg 2×10–12 · Pallof 2×10/str.
Ciężary na A 21.10: rozgrzewka + rotacja zewnętrzna z gumą 2×15/str · plyo pompki 4×5 · hantle skos 20 kg 3×8 · podciąganie neutralne 3×4 · dipy płytkie (do 90° w łokciu) 3×6 tylko bez bólu barku, inaczej pompki 3×10–12 · wiosło 18 kg 3×10 · bokiem 6 kg 3×12 do wysokości barków.
Ciężary na B 23.10: rozgrzewka + izometria szyi · skrzynia 90 cm 4×3 · trap-bar 30 kg/str 3×5 (zajęty: martwy 80 kg 3×5) · bułgarski 12 kg 3×8/str · hip thrust Glute Drive 30 kg/str 3×8 · pogo 2×20 · Nordic 2×3 z asekuracją (pierwszy raz, jeśli 15.10 nie było).

## 5. Historia sesji

Format: `- D.MM sesja (rotacja): energia, ból. Ćwiczenie sprzęt ciężar serie×powt (RIR). ... Zmęczenie po: X.`

- 28.08 A1 (częściowo)
- 23.09 B1
- 25.09 A2
- 28.09 B2
- 30.09 A3 (bez telefonu): pompki na ławce 3×4, reszta A poza wyciskaniem hantli (zapomniane); Pallof zrobiony.
- 2.10 B (rotacja 1): energia 8, bez bólu. Skrzynia 61 cm 4+3+3. Trap-bar zajęty, zamiast niego martwy klasyczny 70 kg ×5 (RIR 5–6) i 90 kg ×3 (RIR brak danych). Bułgarski 10 kg 2×8 (RIR 4–5). Wznosy łydek na podwyższeniu 12 kg 2×12 (zamiast skocznych). Hip thrust Glute Drive 20 kg blach/str ×8 (RIR 4), 2. seria bez wyniku. Zmęczenie po: brak danych.
- 5.10 C (rotacja 1): energia 8, bez bólu. Skok w dal z miejsca 4×3, najlepszy ~220 cm (pierwszy test). Goblet 22 kg 3×8 (RIR 4–5). Hantle płasko 20 kg 6, 8, 8 (RIR 3 w ostatniej). RDL hantle 22 kg 3×8 (RIR ~5). Biceps hantle 12 kg ×10 (RIR 2). Triceps wyciąg 15 kg ×15 (RIR 3–4). Pallof 2×10/str. Zmęczenie po: 6, bez bólu.
- 10.10 A (rotacja 2, przesunięta z 7.10; 7.10 i 9.10 bez treningu): energia 8, bez bólu. Plyo pompki na ławce 4×5, bez bólu. Wyciskanie hantli na skosie (zamiast sztangi, prośba Kuby) 20 kg/rękę 3×6, bez bólu; RIR brak danych. Podciąganie neutralne masa ciała 4, 4, 3 (RIR 1–2), bez bólu. Dipy masa ciała 3×6 (pierwszy raz), RIR brak danych; lekki ból lewego barku, góra barku, 2/10. Wiosło hantlami z podparciem 18 kg 3×8 (RIR 3), bez bólu. Unoszenie bokiem 6 kg 3×10 (do wysokości barków, ostrożnie przez bark), bez bólu.
- 15.10 B (rotacja 2; 12.10 i 14.10 bez treningu): energia 7, bez bólu. Skok na skrzynię 4×3: 1. seria 60 cm, 3 kolejne 90 cm (potwierdzone przez Kubę), technicznie, bez bólu. Trap-bar 27,5 kg/str 3×5 (RIR 5), ból brak danych. Bułgarski 12 kg 3×8/str (RIR ~2), ból brak danych. Hip thrust (stanowisko zajęte, zrobione później; zakładam Glute Drive 25 kg/str 3×8, do potwierdzenia) RIR 5. Łydki skoczne (pogo) 2×15, bardzo lekko (RIR ~10 wg Kuby). Nordic curl zrobiony, „dobrze” wg Kuby (liczby brak danych). Zmęczenie po: brak danych.
- 20.10 C (rotacja 2; 19.10 bez treningu): energia 8, ból brak danych. Rozgrzewka + izometria szyi. Skok w dal 4×3: wynik „podobny”, pomiar telefonem ~230 cm (niepewny); po 3. serii odczucie w górnej części prawego uda, ~2/10 tylko w spoczynku (Kuba napisał „2/8”, czytam jako 2/10). Goblet 24 kg 3×8 (RIR 5); w 3. serii ból prawego uda 6/10 → RDL dziś pominięty (decyzja trenera), dalej tylko góra i core. Hantle płasko 20 kg 3×8 (RIR 3 w ostatniej), ból udo w spoczynku brak danych. Biceps hantle 12 kg + triceps wyciąg 17,5 kg 2×8 (RIR 3; podane łącznie). Pallof stojąc 2×10/str (półklęk pominięty przez udo). Udo po sesji „ok”. Zmęczenie po: 7.
- 22.10 A (rotacja 2): energia 8 (mało snu, zmęczenie odczuwalne), prawe udo bolało 21.10 na schodach, dziś ok. Rozgrzewka + rotacja zewnętrzna z gumą. Plyo pompki na ławce 45 cm (niżej niż 10.10) 3×4, bez bólu. Hantle skos 20 kg/rękę 8, 8, 6 (RIR 2 w ostatniej), ból brak danych. Podciąganie neutralne masa ciała 3×4 wg polecenia (RIR 2 w ostatniej), ból brak danych. Dipy płytkie (do 90°) masa ciała 3×6 wg polecenia (zakładam dipy, nie pompki; do potwierdzenia), RIR 5, lewy bark 1/10 („jest super”, lepiej niż 2/10 z 10.10). Wiosło hantlą z podparciem 18 kg 3×10/str wg polecenia (RIR 2–3 w ostatniej), ból brak danych. Unoszenie bokiem 6 kg 2×12, RIR i ból brak danych. Zmęczenie po: brak danych.
- 24.10 B (rotacja 3): energia 8 (Kuba podał też 7, może w trakcie); prawe udo „ok, czuję bardzo lekko”. Rozgrzewka + izometria szyi. Skok na skrzynię 60 cm (obniżona przez udo) 4×4 (Kuba sam dał 4 zamiast 3, bardzo lekko), udo po skokach brak danych. Trap-bar 30 kg/str 3×5 wg polecenia (RIR 3), udo 0/10. Bułgarski 12 kg 2×8/str, RIR 0 już w 2. serii, więc 3. seria odpuszczona (decyzja Kuby, słuszna); udo brak danych.

**Następna sesja:** B (sob 24.10, rotacja 3, tylko jeśli prawe udo bez bólu; inaczej bez skrzyni i pogo, z lżejszym hip thrustem), potem C pon 26.10.

## 6. Punkty odniesienia (ostatni ciężar i cel na następny raz)

| Ćwiczenie | Ostatnio | Następnym razem |
|---|---|---|
| Skok w dal | ~220 cm (5.10); ~230 cm wg telefonu, niepewne (20.10) | pobić, zmierzyć taśmą |
| Skok na skrzynię | 60 cm 4×4, bardzo lekko (24.10, obniżona przez udo) | 90 cm 4×3, gdy udo 0/10 |
| Plyo pompki / pompki na ławce | 4×5 (10.10) | 4×5, niższa ławka lub podłoga |
| Pompki | 12+10, RIR 3–4 | |
| Skos sztanga | 40 kg, 8+7, RIR ~3 | 40 kg |
| Hantle skos | 20 kg 8, 8, 6, RIR 2 (22.10) | 20 kg, cel 3×8 |
| Hantle płasko | 20 kg 3×8, RIR 3 (20.10) | 20 kg, cel 3×10 |
| Podciąganie | 3×4, RIR 2 w ostatniej (22.10) | 3×5 albo 4×4 |
| Dipy | płytko masa ciała 3×6, RIR 5, lewy bark 1/10 (22.10) | płytko 3×8; głębokość zwiększać dopiero przy barku 0/10 |
| Wiosło z podparciem | 18 kg 3×10, RIR 2–3 (22.10) | 18 kg 3×10; 20 kg gdy RIR ≥3 |
| Unoszenie bokiem | 6 kg 2×12 (22.10) | 6 kg, cel 2×15, potem 7,5 kg |
| Trap-bar | 30 kg/str 3×5, RIR 3 (24.10) | 30 kg/str, cel RIR 3+ potem 32,5 |
| Martwy klasyczny | 70 kg ×5 RIR 5–6, 90 kg ×3 (2.10) | 80 kg 3×5 |
| Bułgarski | 12 kg 2×8/str, RIR 0 (24.10, po trap-barze) | 12 kg 3×6 albo 10 kg 3×8, RIR 2 |
| Hip thrust Glute Drive | 25 kg/str 3×8, RIR 5 (15.10) | 30 kg/str |
| Wznosy łydek | 12 kg 2×12 (2.10) | |
| Łydki skoczne (pogo) | 2×15, bardzo lekko (15.10) | 2×20 albo jednonóż 2×10/str |
| Goblet | 24 kg 3×8, RIR 5, ból prawego uda 6/10 w 3. serii (20.10) | 24 kg, tylko jeśli udo bez bólu |
| RDL | hantle 22 kg 3×8, RIR ~5 (5.10) | hantle 26 kg lub sztanga ~50 kg |
| Biceps hantle | 12 kg 2×8, RIR 3 (20.10) | 12 kg, cel 2×10 |
| Triceps wyciąg | 17,5 kg 2×8, RIR 3 (20.10) | 17,5 kg, cel 2×10 |
| Triceps nad głową | 12,5 kg | |
| Nordic curl | zrobiony, „dobrze” (15.10) | 2×3 z asekuracją, kontrola zejścia |
| Rotacja zewnętrzna z gumą | nowe | 2×15/str, lekka guma |
| Izometria szyi | nowe | 2×10 s/kierunek, 50–70% siły |

## 7. Filmiki z techniką (YT)

**A góra:** [plyo pompki](https://www.youtube.com/watch?v=GR0ZL7f7u18) · [skos sztangą](https://www.youtube.com/watch?v=O9x7xRhtA9Q) · [podciąganie neutralne](https://www.youtube.com/watch?v=8klSksDvNl4) · [dipy](https://www.youtube.com/watch?v=oA8Sxv2WeOs) · [wiosło z podparciem](https://www.youtube.com/watch?v=kX4gtPQeyb8) · [unoszenie bokiem](https://www.youtube.com/watch?v=Y29xKcze8Ik) · [hantle skos](https://www.youtube.com/watch?v=5iACxPVXKGg)

**B dół:** [skok na skrzynię](https://www.youtube.com/watch?v=G-bxQY57mKc) · [trap-bar](https://www.youtube.com/watch?v=EsqwERaSTMI) · [bułgarski](https://www.youtube.com/watch?v=hiLF_pF3EJM) · [hip thrust](https://www.youtube.com/watch?v=pBH7pKHn-dI) · [skoczne łydki (pogo)](https://www.youtube.com/watch?v=j0nl5dWuqN4)

**C całość:** [skok w dal](https://www.youtube.com/watch?v=CpmTk9kmdm8) · [goblet](https://www.youtube.com/watch?v=6mf0oa2GGUc) · [hantle płasko](https://www.youtube.com/watch?v=xhEhjF5ozuY) · [RDL hantlami](https://www.youtube.com/watch?v=hQgFixeXdZo) · [biceps hantle](https://www.youtube.com/watch?v=XE_pHwbst04) · [triceps wyciąg](https://www.youtube.com/watch?v=-zLyUAo1gMw) · [chaos Pallof](https://www.youtube.com/watch?v=qS6qXV5kI-Y)

**Zamienniki i nowe:** [martwy klasyczny](https://www.youtube.com/watch?v=CWsxP4xat9M) · [Nordic curl](https://www.youtube.com/watch?v=_e9vFU9-tkc) · [Copenhagen adductor](https://www.youtube.com/watch?v=kD1t1hWzIDE) · [rotacja zewnętrzna z gumą](https://www.youtube.com/watch?v=ybNV36DoRfY) · [pompki](https://www.youtube.com/watch?v=IODxDxX7oi4) · [izometria szyi](https://www.youtube.com/watch?v=ZqWEXUULB7M)

Nowe ćwiczenie = najpierw link tutaj. Analiza dowodów dla nowych: [baza-cwiczen.md](baza-cwiczen.md).

## 8. Dziennik zmian (upgrade'y)

- 30.09: rotacja A→B→C zamiast A/B, siłownia co 2–3 dni, wejście stopniowe.
- 2.10: trap-bar zajęty → martwy klasyczny jako zamiennik; łydki skoczne → wznosy na podwyższeniu.
- 4.10: Nordic curl do sesji B od 9.10.
- 5.10: 3 serie w ciężkich od tej sesji (brak BJJ w tygodniu). Front squat pomijany, goblet zostaje.
- 10.10: skos sztangą → hantle na skosie (prośba Kuby, ławka ~30°).
- 11.10: dipy tylko płytko i bez bólu barku, inaczej pompki; rotacja zewnętrzna z gumą 2×15/str w rozgrzewce A (i opcjonalnie C); RDL na 26 kg, goblet 24 kg.
- 18.10: izometria szyi 2×10 s/kierunek w rozgrzewce C i B; od B 23.10 rotacja 3 (RIR 2–3 w ciężkich), trap-bar 30 kg/str, hip thrust 30 kg/str, skrzynia 90 cm, pogo 2×20.
- 20.10: ból górnej części prawego uda (6/10 w gobletach) → RDL pominięty; B 24.10 zależne od uda.
- 6.10: wszystko w jednym pliku TRENING.md, wspólnym dla Claude'a i Hermesa.

## Archiwum: wcześniejszy plan A/B (przed 30.09)

2 sesje/tydz. obok ~3 treningów BJJ, 2 serie robocze, RIR 3–4.
**A:** rzut piłką / pompki eksplozywne 3×3–5; goblet / przysiad przedni 2×6–8; hantle płasko 2×8–12; podciąganie neutralne / wyciąg 2×6–10; RDL 2×8–10; bokiem 2×12–15; biceps + triceps wyciąg 2×10–15; Pallof stojąc 2×10/str.
**B:** skok na skrzynię 3×3; trap-bar 2×5–6; skos sztangą 2×8–12; wiosło z podparciem 2×8–12; bułgarski 2×8/str; pompki 2×8–15; młotki + triceps nad głową 2×10–15; farmer (pominięty).
Progresja oryginalna: T1 2 serie RIR ~4; T2 RIR 3 (3 serie głównych); T3 RIR 2–3, +1–2 powt. / +2,5–5%; T4 deload −30–40% serii, RIR 4. Nie przypisywać tygodnia wg daty.

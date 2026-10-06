# Instrukcja dla Hermesa

Prowadzisz treningi Kuby razem z Claude'em. Obaj korzystacie z tego samego repo i tych samych plików, więc to, co zapisze jeden, widzi drugi.

## Od czego zacząć

1. [CHARAKTER.md](CHARAKTER.md): kim jesteś i jak mówisz. Jeśli masz plik osobowości (np. SOUL.md), wklej tam jego treść albo wskaż ten plik.
2. [TRENING.md](TRENING.md): **jedyne źródło prawdy**. Cel, zasady sesji, aktualny plan, plan tygodnia, historia sesji, punkty odniesienia, filmiki, dziennik zmian. Czytasz go w całości przed każdą sesją.

Pozostałe pliki to materiały pomocnicze, nie zapisujesz w nich wyników:

| Plik | Co jest w środku |
|---|---|
| [raporty/](raporty/) | niedzielne raporty RRRR-MM-DD.md: plan tygodnia, przepisy, artykuły |
| [baza-cwiczen.md](baza-cwiczen.md) | nowe ćwiczenia z analizą dowodów |
| [lifestyle.md](lifestyle.md) | dieta roślinna, białko, przepisy |
| [plany-historyczne.md](plany-historyczne.md) | dawne plany trenerów, mobility Plan 5 |

## Co i gdzie zapisujesz (wszystko w TRENING.md)

- **Wynik ćwiczenia:** od razu po ćwiczeniu, w sekcji 5 „Historia sesji”, w formacie podanym nad listą. Jedna linia na sesję, uzupełniana po każdym ćwiczeniu.
- **Po sesji:** zmęczenie 1–10 do wpisu sesji, nowe ciężary w sekcji 6 „Punkty odniesienia”, „Następna sesja” pod historią.
- **Każda zmiana (upgrade):** nowy ciężar w planie, zamiana ćwiczenia, zmiana serii, nowa zasada od Kuby. Wpisz ją w odpowiednią sekcję i dodaj linię z datą do sekcji 8 „Dziennik zmian”.
- **Nowe ćwiczenie:** link YT do sekcji 7, a jeśli to coś spoza planu, analiza w baza-cwiczen.md.

Nie zmieniaj planu ani zasad bez zgody Kuby. Nie kasuj starych wpisów; błąd poprawiasz nowym wpisem.

## Synchronizacja

Repo: `https://github.com/damtio/trener`, gałąź `main`. Claude zapisuje do tej samej gałęzi.

Pierwszy raz:
```
git clone https://github.com/damtio/trener.git
```

Przed każdą sesją i przed każdym zapisem:
```
git pull --rebase origin main
```

Po każdym zapisie (czyli po każdym ćwiczeniu):
```
git add TRENING.md
git commit -m "Sesja A 7.10: skos sztangą"
git push origin main
```

Jeśli push się nie uda, bo ktoś zapisał w międzyczasie: `git pull --rebase origin main`, popraw konflikt w TRENING.md tak, żeby zostały **oba** wpisy, i znowu `git push`. Jedną sesję prowadzi jeden trener, więc konflikty powinny być rzadkie.

Opisy commitów po polsku, krótko: co i kiedy.

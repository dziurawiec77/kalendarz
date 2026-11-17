# Kalendarz 2027

Polski kalendarz artystyczny z trzema fikcyjnymi bohaterkami, zdjęciami sezonowymi, siatkami dni oraz świętami. Prosta strona statyczna, bez logowania i bazy danych.

**Strona:** https://dziurawiec77.github.io/kalendarz/

## Publikacja
W ustawieniach repozytorium GitHub Pages jako źródło wybrano GitHub Actions. Workflow `.github/workflows/pages.yml` automatycznie publikuje zmiany z gałęzi `main`.

Pakiet fotografii (12 miesięcy, oryginalna okładka i osobny kadr mobilny) jest przechowywany w `.photo-parts/part-*.bin`. Workflow łączy części w archiwum ZIP, sprawdza sumę SHA-256, rozpakowuje i sprawdza komplet zdjęć. Takie przechowywanie wykorzystano ze względu na ograniczenie jednorazowego przesyłania dużych plików przez API GitHub; nie należy edytować poszczególnych części ręcznie.

## Wygląd
Każda karta miesiąca wyświetla zdjęcie 4:5 wypełniające kadr, bez rozmytego obramowania. Dla fotografii źródłowych o węższych proporcjach brakujący fragment scenerii został delikatnie przedłużony po bokach, aby nie ucinać głów ani stóp. Okładka ma wariant na komputery (`okladka.jpg`) oraz pełnopostaciowy wariant na telefony (`okladka-mobile.jpg`).

## Funkcje
Polska siatka dni 2027 rozpoczynająca się w poniedziałek, podkreślenie weekendów i świąt, drukowanie/zapis do PDF, układ responsywny. Kod w `index.html` nie wymaga biblioteki JavaScript ani serwera aplikacji.

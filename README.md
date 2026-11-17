# Kalendarz 2027

Polski kalendarz artystyczny z trzema fikcyjnymi bohaterkami, zdjęciami sezonowymi, siatkami dni oraz świętami. Strona jest statyczna, bez logowania i bazy danych.

**Docelowa strona GitHub Pages:** https://dziurawiec77.github.io/kalendarz/

## Publikacja

Do uruchomienia strony potrzebny jest plik **`kalendarz_2027_fotografie_zatwierdzone.zip`** zawierający katalog `photos/` i 13 fotografii JPG. Wgraj archiwum do głównego katalogu repozytorium (GitHub → Add file → Upload files). Workflow `.github/workflows/pages.yml` automatycznie rozpakuje zdjęcia, sprawdzi wszystkie miesiące i opublikuje gotową stronę.

W ustawieniach repozytorium wybierz **Settings → Pages → Build and deployment → Source: GitHub Actions**. Publiczne repozytorium może być publikowane bezpłatnie na GitHub Pages.

## Grafika

Dwanaście zdjęć miesięcznych ma proporcje 4:5. Okładka wykorzystuje oryginalną grupową fotografię referencyjną. Przygotowane obrazy nie ucinają głów ani stóp, a grudniowa fotografia przedstawia trzy bohaterki na kanapie przy choince.

Nazwy plików: `styczen.jpg`, `luty.jpg`, `marzec.jpg`, `kwiecien.jpg`, `maj.jpg`, `czerwiec.jpg`, `lipiec.jpg`, `sierpien.jpg`, `wrzesien.jpg`, `pazdziernik.jpg`, `listopad.jpg`, `grudzien.jpg`, `okladka.jpg`.

## Funkcjonalność

Kalendarz wykorzystuje czysty HTML, CSS i JS; siatki dni 2027 oraz zaznaczenia świąt tworzą się bez brakujących modułów starej wersji. Dostępna jest opcja drukowania/zapisu do PDF.

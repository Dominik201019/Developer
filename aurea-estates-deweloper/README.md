# AUREA ESTATES — Sztuka dobrego adresu

Kompletna koncepcyjna strona firmy deweloperskiej. Marka, inwestycje, lokalizacje, parametry i statusy są fikcyjne. Fotografie Unsplash ilustrują architekturę i wnętrza, nie przedstawiają realizacji tej marki.

## Pliki i GitHub Pages

Gotowa strona znajduje się w `dist`: HTML, CSS, JavaScript, favicon, `.nojekyll` i folder `images`. Bez instalacji pakietów i kompilacji. W paczce ZIP gotowe pliki są bezpośrednio w katalogu głównym.

Na GitHub wgraj **zawartość dist** (albo rozpakowaną zawartość ZIP-a) do nowego repozytorium. Zachowaj folder `images` i nazwy plików. Settings → Pages → Deploy from a branch → main → /(root). Ścieżki są względne, obsługują adres `/nazwa-repozytorium/`.

Podgląd: `node preview.cjs` i http://127.0.0.1:8779 lub otwarcie `dist/index.html` w przeglądarce.

## Zawartość

- Ekran ładowania zdjęcia głównego z animacją logo i limitem czasu, aby nie blokować strony.
- Menu mobilne z obsługą klawiatury, animacje wejścia, manifest i efekty na zdjęciach.
- Trzy inwestycje z filtrami statusu, pełnymi panelami szczegółów, galeriami, parametrami i typami mieszkań.
- Wybór projektu w panelu przenosi temat do formularza kontaktowego.
- FAQ, informacja o prywatności i charakterze projektu.
- Formularz z walidacją i lokalnym podsumowaniem. Nie wysyła danych, nie rezerwuje mieszkań, nie umawia spotkań.
- Systemowe ograniczenie ruchu upraszcza animacje.

Treści: `dist/index.html`. Dane projektów i działanie: `dist/script.js`. Styl: `dist/styles.css`. Fonty Italiana i Manrope z Google Fonts. Fotografie główne Unsplash: photo-1600585154340-be6161a56a0c (rezydencja), photo-1600566753086-00f18fb6b3ea (wnętrze); pozostałe zdjęcia stockowe architektury i wnętrz są zapisane lokalnie.

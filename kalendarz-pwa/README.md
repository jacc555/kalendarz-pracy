# Kalendarz pracy i wypłata – PWA

## Publikacja na GitHub Pages
1. Rozpakuj ZIP na komputerze.
2. W repozytorium `kalendarz-pracy` wgraj **zawartość** folderu (index.html, manifest.webmanifest, sw.js i folder icons), nie sam plik ZIP.
3. Wszystkie pliki muszą być bezpośrednio w katalogu głównym repozytorium, a ikony w folderze `icons`.
4. W GitHub: Settings → Pages → Deploy from a branch → `main` → `/(root)`.
5. Poczekaj, aż wdrożenie się zakończy, a następnie otwórz `https://jacc555.github.io/kalendarz-pracy/` w Chrome na Androidzie.

Manifest zawiera ścieżki względne, więc działa w podkatalogu GitHub Pages. Service Worker ma nową wersję cache (`v2`), aby wymusić odświeżenie zasobów po wdrożeniu.

## Instalacja
W Chrome otwórz stronę, odczekaj chwilę, dotknij strony i wybierz menu ⋮ → „Zainstaluj aplikację”. Jeżeli Chrome nadal pokazuje niedostępną instalację, nie usuwaj danych witryny przed wykonaniem eksportu danych z aplikacji.

## Dane i prywatność
Dane kalendarza są przechowywane lokalnie w pamięci przeglądarki/instalacji. Ta paczka nie dodaje serwera ani synchronizacji między urządzeniami. Przed czyszczeniem danych witryny, reinstalacją lub zmianami w Chrome użyj „Eksportuj dane”.

## Aktualizacja
Prześlij ponownie pliki z tej paczki do katalogu głównego repozytorium i zatwierdź zmiany. Po wdrożeniu zamknij wszystkie karty/aplikacje kalendarza, otwórz stronę ponownie z internetem.

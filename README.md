# Strona LORUN

Statyczna strona HTML/CSS. Bez frameworka, instalacji zależności i etapu kompilacji.

## Struktura

- `index.html` — Start, O nas, Czym się zajmujemy, Kariera, Kontakt i istniejąca sieć współpracy.
- `kariera/index.html` — dwie aktywne rekrutacje.
- `kariera/kierownik-technicznej-realizacji-projektow/index.html` — Kierownik Technicznej Realizacji Projektów.
- `kariera/project-manager-innovation-manager-pl-de/index.html` — Project Manager / Innovation Manager PL-DE.
- Wcześniejsze oferty w `asystent-projektanta-cad`, `mlodszy-inzynier-projektu` i `inzynier-projektu` zachowują adresy oraz opisy jako archiwum: komunikat o zakończeniu, bez aplikowania i z `noindex, follow`. Nie są na liście aktywnych ofert ani w sitemapie.
- `assets/` — niezmienione logo, favicon, logotypy partnerów i wspólny arkusz CSS.
- `404.html` — strona błędu, zasoby i nawigacja z bezwzględnymi ścieżkami.
- `CNAME` — istniejąca domena GitHub Pages.
- `lorun-strona-github-v2-partnerzy.zip` — paczka statycznej strony, zsynchronizowana z aktualnymi plikami publicznymi, aby nie rozpowszechniać nieaktualnych ofert i kontaktu.

Logo pozostaje zwykłym elementem obrazu. Zachowano paletę, typografię, sieć współpracy i Cloudflare Web Analytics.

## Kontakt

Publiczny telefon: **500 503 114** (`tel:+48500503114`). E-mail: **info@lorun.pl**.

**Adres biura / miejsce pracy:** LORUN Sp. z o.o., Krasne 165, 36-007 Krasne. Nie jest to deklaracja adresu rejestrowego spółki. W danych strukturalnych adres opisuje lokalizację biura.

## Publikacja i kontrola

Repozytorium publikuje `main` z katalogu głównego przez GitHub Pages. Historia Actions potwierdza automatyczne publikacje. Zmiany należy przygotowywać na osobnej gałęzi i scalać dopiero po zatwierdzeniu właściciela.

Repozytorium nie ma konfiguracji własnego CI, testów, lintera, typecheck ani preview deploymentu. Nie wymaga builda. Do podglądu wystarczy dowolny serwer statyczny uruchomiony z katalogu repozytorium, np. `python -m http.server 4173`.

Przed publikacją sprawdź wszystkie strony i linki lokalne, kotwice, `tel:`, `mailto:`, metadane, sitemapę i archiwizację. Obejrzyj desktop oraz mobile. Sprawdź pliki tekstowe i zawartość ZIP pod kątem nieaktualnych kontaktów. Po zmianie plików publicznych odśwież również ZIP. Nie dodawaj do niego historii Git ani narzędzi lokalnych.

Warunki finansowe, forma umowy i praca zdalna nowych ról nie są deklarowane bez zatwierdzonej treści.

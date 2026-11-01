# PET/PSR Navlog

by Hubert Pofelski · wersja 1.1

Kalkulator Point of Equal Time i Point of Safe Return dla statków powietrznych
wielosilnikowych (AEO / OEI), z importem tras z SkyDemon (`.flightplan`) i
automatyczną deklinacją magnetyczną z World Magnetic Model 2025 (NOAA/BGS).
Aplikacja PWA — po pierwszym otwarciu działa bez internetu na iPadzie i Macu.

Point of Equal Time and Point of Safe Return calculator for multi-engine
aircraft (AEO / OEI), with SkyDemon route import and automatic magnetic
variation from WMM2025. Installable PWA that works offline.

## Instalacja / Install

- **iPad:** Safari → Udostępnij → *Do ekranu początkowego* (Share → *Add to Home Screen*).
- **Mac:** Safari → Plik → *Dodaj do Docka* (File → *Add to Dock*).

Otwórz aplikację raz z internetem. Gdy pojawi się „Gotowe offline”, działa bez sieci.
Plany lotów i ustawienia są przechowywane wyłącznie na urządzeniu.

## Baza lotnisk / Airport data

Ok. 11 800 lotnisk, lądowisk i heliportów Europy, basenu Morza Śródziemnego i Bliskiego
Wschodu z OurAirports (domena publiczna, stan na 2026-11-01).
Służy wyłącznie do podpisywania punktów planu — obliczenia opierają się na współrzędnych.

## Model magnetyczny / Magnetic model

Wbudowany WMM2025 jest ważny do końca 2029 r. Nowszy plik współczynników `.COF`
(lub `.zip`) z ncei.noaa.gov można wczytać przyciskiem *Wczytaj nowszy model*.

---

Narzędzie planistyczne. Wyniki weryfikuj z RFM i dokumentacją operacyjną.
Planning aid only — verify against the RFM and operational documentation.

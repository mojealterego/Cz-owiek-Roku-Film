# CZŁOWIEK ROKU — FILM

## Master Project Repository

Repozytorium jest centralnym źródłem prawdy (Single Source of Truth) dla adaptacji filmu **„Człowiek Roku”** oraz całego procesu produkcji AI.

### Status
- Repozytorium: `mojealterego/Cz-owiek-Roku-Film`
- Dokumentacja projektu jest budowana od podstaw na bazie materiałów źródłowych i zatwierdzanych referencji.
- Materiał bazowy: scenariusz 136 stron, książka 409 stron, podcast/transkrypcja, list otwarty, „Raport z piekła”, materiały referencyjne postaci oraz dodatkowe materiały wystawy „Sceny z życia”.
- Docelowy pipeline: źródła → adaptacja → bible → sceny → shot list → prompty → generacja AI → montaż → sound design → master.

## Najważniejsza zasada
Nie wolno mieszać faktów źródłowych z decyzjami produkcyjnymi. Każdy istotny element ma być oznaczony jako:
- **SOURCE** — wynika bezpośrednio ze źródła;
- **ADAPTATION** — decyzja adaptacyjna;
- **FILM DECISION** — decyzja reżyserska/produkcyjna;
- **REFERENCE LOCK** — zatwierdzony wygląd/referencja;
- **CONTINUITY LOCK** — element, którego nie wolno naruszyć;
- **UNVERIFIED REFERENCE** — materiał zewnętrzny zachowany jako referencja, ale niezweryfikowany.

## Główne dokumenty
- `docs/MASTER_PROJECT_STATE.md` — nadrzędny stan projektu.
- `docs/STORY_BIBLE.md` — pełna synteza fabuły, łuku Andrzeja, aktów i punktów zwrotnych.
- `docs/CHRONOLOGY.md` — chronologia wydarzeń 2023–2025.
- `docs/SOURCE_CATALOG.md` — katalog źródeł, hierarchia i zewnętrzne referencje.
- `docs/SOURCES_AND_ADAPTATION.md` — matryca źródeł i zasady source-lock.
- `docs/VISUAL_LANGUAGE.md` — język wizualny filmu.
- `docs/TATTOO_BIBLE.md` — pełna mapa tatuaży i chronologia zmian.
- `docs/PRODUCTION_PIPELINE.md` — pipeline AI/Picsart.
- `docs/SCENE_MAP.md` — mapa 74 unikalnych scen/headingów scenariusza.
- `docs/CHARACTERS/CHARACTER_CAST_STATUS.md` — centralny status castingu i referencji.
- `docs/CHARACTERS/ANDRZEJ.md` — bible Andrzeja.
- `docs/CHARACTERS/WERONIKA.md` — visual bible Weroniki.
- `docs/CHARACTERS/ZUZIA.md` — visual bible Zuzi.
- `docs/CHARACTERS/PAULINA.md` — visual bible Pauliny; rozdział 59 / lodziarnia.
- `docs/CHARACTERS/KAROL.md` — visual bible Karola.
- `docs/CHARACTERS/SEBASTIAN.md` — visual bible Sebastiana.
- `docs/CHARACTERS/JULKA.md` — visual bible Julki.
- `docs/CHARACTERS/ADRIAN.md` — visual reference Adriana.
- `docs/CHARACTERS/TOMEK_TATUATOR.md` — visual/role bible Tomka.
- `docs/CHARACTERS/TOMEK_WIFE.md` — reference/status żony Tomka.
- `docs/ADAPTATIONS/TOMEK_WEDDING_PROPOSAL.md` — propozycja sceny wesela Tomka; obecnie niekanoniczna.
- `docs/DECISION_LOG.md` — chronologiczny rejestr decyzji i continuity locks.

## Aktualne kluczowe ustalenia

### Andrzej / tatuaż pleców
**PRZED TRANSFORMACJĄ:** portret Weroniki.

**W TRAKCIE HISTORII:** Andrzej tatuuje/przekształca plecy.

**PO TRANSFORMACJI:** portret zostaje przekształcony w kompozycję Santa Muerte z intensywnie niebieskimi włosami i kolorowymi akcentami.

Późniejsza wersja nie może pojawić się przed momentem transformacji.

### Paulina
**Rozdział 59 → lodziarnia.**

Numer rozdziału nie jest automatycznie utożsamiany z numerem sceny scenariusza bez źródłowego potwierdzenia.

### Tomek / żona Tomka / wesele
Żona Tomka obecnie **nie występuje w filmie**.

Istnieje propozycja adaptacyjna dodania wesela:
- Andrzej fotografuje wesele Tomka;
- fotografia weselna jest sposobem rozliczenia za tatuaż wykonany przez Tomka;
- żona Tomka może dzięki temu pojawić się naturalnie;
- scena łączy fotografię Andrzeja z jego transformacją poprzez tatuaż.

**Wesele nie jest jeszcze kanonem scenariusza.** Nie zmienia obecnie liczby 74 scen ani runtime'u.

## Fabuła — skrót kontrolny

Film rozpoczyna się od publicznego triumfu Andrzeja jako „Człowieka Roku”, po czym natychmiast odsłania prywatne pęknięcie: rozpad relacji z Weroniką i utratę normalnego kontaktu z Zuzią. Konflikt przechodzi przez policję, sądy, procedury, opinie i instytucje. Andrzej fizycznie załamuje się i trafia na intensywną terapię.

Po kryzysie odzyskuje kontrolę nad tym, co potrafi najlepiej: fotografią. „Projekt W.” staje się kontrnarracją wobec oczekiwanego publicznego spektaklu. Następnie historia rozszerza się na innych ojców, protest „Strajk Ojców” i media, które zamieniają prywatne cierpienie w produkt telewizyjny.

Ostatnia próba porozumienia kończy się kolejnym powrotem do maszyny prawnej. System coraz wyraźniej przyjmuje postać zamkniętej sieci konkretnych ludzi i instytucji. W 2025 roku Andrzej przegrywa kolejne starcia, a jego własne słowa zostają wykorzystane przeciwko niemu.

Jesienią 2025 wynajmuje nowe mieszkanie i przygotowuje pusty pokój dla Zuzi. Następuje załamanie. Film nie kończy się klasycznym zwycięstwem: Andrzej pozostaje świadkiem własnej historii. Kończy list, odkłada go obok fotografii Zuzi, a w absolutnej ciszy rozlega się migawka aparatu.

## „SCENY Z ŻYCIA”

Scena 12F scenariusza umieszcza Andrzeja 30 lipca 2024 w czeskiej galerii, gdzie prezentuje cykl „Sceny z życia”. Publiczne źródła potwierdzają wystawę w Galerii MOST w Czeskim Cieszynie od 30 lipca do 23 sierpnia 2024, obejmującą 41 prac przedstawiających codzienne sceny. citeturn0search0

Użytkownik dostarczył trzy dodatkowe referencje YouTube związane z wystawą. Zostały zapisane w `docs/SOURCE_CATALOG.md`. Bezpośrednia treść tych materiałów nie została uznana za zweryfikowaną, ponieważ strony YouTube nie były dostępne do odczytu w tym przebiegu.

## Zasada aktualizacji
Każde nowe ustalenie dotyczące fabuły, postaci, wyglądu, tatuaży, chronologii, sceny, języka wizualnego, promptów lub workflow ma być dopisywane do odpowiedniego dokumentu zamiast pozostawać wyłącznie w rozmowie.

**Nie polegamy na pamięci pojedynczego okna czatu. Repozytorium ma przechować projekt.**

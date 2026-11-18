# Kierowca by Proszczok

[English](README.en.md) · [Strona dodatku](https://proszczok.pl/kierowca/) · [Kontakt i zgłoszenia](https://github.com/proszczok2002/Kierowca-by-Proszczok/issues)

Dodatek do NVDA, który przekierowuje mowę syntezatora lub dźwięk programu przez Virtual Audio Cable do mikrofonu TeamTalk albo innego komunikatora. Routing włączasz i wyłączasz skrótem **NVDA+Shift+Alt+K**.

## Pobierz

**Aktualna wersja: 1.78.**

[Pobierz najnowszy dodatek z proszczok.pl](https://proszczok.pl/kierowca/Kierowca%20by%20Proszczok.nvda-addon)

Oficjalna strona: **https://proszczok.pl/kierowca/**. Link pobierania zawsze prowadzi do najnowszego wydania.

GitHub służy jako wizytówka, historia wydań i miejsce zgłaszania problemów. Pobieranie oraz aktualizator działają przez **proszczok.pl**. GitHub nie jest serwerem aktualizacji.

## Co potrafi dodatek?

- Przekierowuje mowę NVDA, muzykę i inne audio do wejścia komunikatora.
- Zapamiętuje źródło i cel, rozpoznając urządzenia po nazwie.
- Potwierdza uruchomienie i zatrzymanie komunikatem oraz dźwiękami.
- Pozwala ukryć baner stanu w ustawieniach.
- Kontroluje działanie strumieni i próbuje przywrócić zatrzymane audio.
- Po restarcie NVDA pozostaje wyłączony i wymaga ręcznego włączenia.
- Pyta przed instalacją aktualizacji, a następnie osobno przed restartem NVDA.
- Udostępnia menu Wsparcie z PayPal, Revolut i stroną autora.

## Wymagania i instalacja

Windows, NVDA 2023.1 lub nowszy, zainstalowany Virtual Audio Cable oraz TeamTalk lub inny komunikator. Dla typowego przekierowania potrzebne są dwa różne kable VAC.

1. Pobierz plik `.nvda-addon` ze strony autora.
2. Otwórz go i potwierdź instalację w NVDA.
3. Uruchom NVDA ponownie.
4. Otwórz **NVDA → Narzędzia → Kierowca by Proszczok → Ustawienia…**.
5. Wybierz źródło i wyjście, a następnie włącz routing skrótem **NVDA+Shift+Alt+K**.

## Przykład: Line 1 → Line 3 → TeamTalk

1. Wyjście syntezatora NVDA: odtwarzające wyjście **Line 1**.
2. Źródło w Kierowcy: nagrywające wejście **Line 1**.
3. Cel w Kierowcy: odtwarzające wyjście **Line 3**.
4. Mikrofon w TeamTalk: nagrywające wejście **Line 3**.
5. Odsłuch TeamTalk pozostaw na słuchawkach lub głośnikach.

Wyjście Kierowcy i mikrofon TeamTalk muszą wskazywać **ten sam numer kabla**. Dodatek nie przełącza urządzenia mikrofonowego w TeamTalk.

## Kontakt i pomoc

[Zadaj pytanie, zgłoś błąd lub zaproponuj funkcję](https://github.com/proszczok2002/Kierowca-by-Proszczok/issues/new/choose).

Zgłoszenia są publiczne. Opisz wersję dodatku i NVDA, konfigurację kabli oraz kroki odtworzenia problemu. Fragment logu sprawdź przed publikacją i usuń z niego dane prywatne.

[Historia zmian](CHANGELOG.md) · [Informacje o wydaniach](https://github.com/proszczok2002/Kierowca-by-Proszczok/releases) · [Polityka prywatności](https://proszczok.pl/privacy.html)

## Wsparcie autora

[PayPal](https://paypal.me/proszczok) · [Revolut](https://revolut.me/r_rosiejka) · [Strona autora](https://proszczok.pl/)

## Zawartość tego repozytorium

To publiczne repozytorium zawiera opis, instrukcję, informacje o wydaniach i formularze kontaktowe. Nie zawiera źródeł rozwojowych ani kopii instalatora. Źródła projektu są utrzymywane oddzielnie. Instalacyjna paczka NVDA zawiera moduły niezbędne do działania dodatku; brak źródeł w tym repozytorium nie oznacza ukrycia zawartości pobranej paczki.

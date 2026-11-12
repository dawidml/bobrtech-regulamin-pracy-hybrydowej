# Regulamin pracy hybrydowej BOBRTECH

Projekt szkoleniowy: poprawianie **dokumentu tekstowego** (regulaminu HR) za pomocą promptów do agenta AI.
Firma BOBRTECH i wszystkie dane są fikcyjne – materiał do warsztatów „AI Coding Workspace”.

## Po co ten przykład

Kalkulator delegacji pokazuje budowanie małej aplikacji.
Ten repozytorium pokazuje case bliższy codziennej pracy osób nietechnicznych:
przedsiębiorca, HR lub menedżer **iteracyjnie zmienia regulamin** (limity dni, ryczałt, wyjątki),
a Git i AI Prompt Timeline zapisują każdy prompt i wynikającą z niego zmianę w dokumencie.

## Dokument

- `dokumenty/HR-REG-05_regulamin_pracy_hybrydowej.md` – aktualna treść regulaminu.

## Jak śledzić zmiany

- `git log --oneline` – kolejne tury agentów (`AI/<agent>: prompt #N`),
- `git show` / porównanie plików – konkretne poprawki w tekście regulaminu,
- AI Prompt Timeline (GitHub Pages) – treść promptów i diffy obok siebie.

## Zasady szkoleniowe

- Bez danych osobowych prawdziwych osób, bez sekretów i bez e-maili produkcyjnych.
- Commity powstają automatycznie po turze agenta (AI Git Starter) – nie commituj ręcznie w trakcie demo.

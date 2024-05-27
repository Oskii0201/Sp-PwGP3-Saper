# Sp-PwGP3-Saper

## Opis
Implementacja gry Saper w języku C#. Gra polega na odkrywaniu pól na planszy, na której ukryte są bomby. Celem jest odkrycie wszystkich pól, które nie zawierają bomb. Gra kończy się przegraną, jeśli gracz odkryje pole z bombą, lub wygraną, jeśli wszystkie pola bez bomb zostaną odkryte.

## Funkcjonalności
- Generowanie planszy o ustalonym rozmiarze (domyślnie 10x10) z losowo rozmieszczonymi bombami.
- Odkrywanie pól poprzez podanie współrzędnych.
- Wyświetlanie liczby bomb znajdujących się w sąsiednich polach.
- Automatyczne odkrywanie sąsiednich pól, jeśli odkryte pole nie ma żadnych sąsiednich bomb.
- Sprawdzanie warunków wygranej.
- Komunikaty końcowe w przypadku wygranej lub przegranej.

### Sklonowanie repozytorium
```bash
git clone https://github.com/Oskii0201/Sp-PwGP3-Saper.git
cd Sp-PwGP3-Saper

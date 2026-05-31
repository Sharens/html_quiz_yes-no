# HTML Quiz Yes/No

Prosta aplikacja do tworzenia i przeprowadzania testów typu tak/nie. Użytkownik przesyła plik z pytaniami w określonym formacie, a aplikacja generuje interaktywny test, po którym wyświetla wynik.

## Kontekst

Projekt został stworzony jako narzędzie do szybkiego sprawdzania wiedzy w formacie tak/nie. Idealny do quizów szkolnych, szkoleniowych lub szybkich ankiet. Aplikacja działa całkowicie w przeglądarce – nie wymaga serwera ani bazy danych.

## Stack technologiczny

- **HTML5** – struktura strony
- **CSS3** – stylowanie i responsywność
- **JavaScript (Vanilla)** – logika aplikacji, obsługa przesyłania plików, generowanie testu i walidacja odpowiedzi

Brak zewnętrznych bibliotek – wszystko w czystym frontendzie.

## Jak przygotować plik z pytaniami

Plik z pytaniami musi być w formacie Markdown podobnym do przykładu znajdującego się w katalogu `source/example_questions.md`.

### Format

Każde pytanie składa się z dwóch linii:

```
* TREŚĆ PYTANIA
	* ODPOWIEDŹ (TAK lub NIE)
```

- Pierwsza linia zaczyna się od `* `, po której następuje treść pytania.
- Druga linia zaczyna się od dwukrotnej tabulacji (lub dwóch spacji? w przykładzie jest tabulacja) oraz `* `, a następnie odpowiedź: `TAK` lub `NIE` (wielkość liter nie ma znaczenia, ale zaleca się wielkie litery).

### Przykład

```
* Czy JavaScript jest językiem programowania?
	* TAK
* Czy HTML to język programowania?
	* NIE
```

### Uwagi

- Puste linie są ignorowane.
- Plik powinien mieć rozszerzenie `.md` (np. `pytania01.md`).
- Maksymalna liczba pytań jest ograniczona tylko przez wydajność przeglądarki (w praktyce setki pytań działają bez problemu).

## Jak uruchomić aplikację

1. Sklonuj lub pobierz repozytorium.
2. Otwórz plik `index.html` w dowolnej nowoczesnej przeglądarce (Chrome, Firefox, Safari, Edge).
3. Przeciągnij plik z pytaniami na obszar oznaczony jako "Drop zone" lub kliknij aby wybrać plik.
4. Rozwiąż test, a następnie zobacz wynik.
    
## Licencja

MIT – możesz swobodnie używać, modyfikować i rozpowszechniać projekt.

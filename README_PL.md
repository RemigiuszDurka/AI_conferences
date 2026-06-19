# Warsztat AI — szybka instrukcja dla uczestników

# Google Colab: notatka, kod, wykres

Link: https://colab.research.google.com/

Jest darmowa usługa tak samo jako gmail.

## Zadanie

Colab służy jako laboratorium:

* Markdown = opis problemu,
* Python = obliczenia,
* wykres = kontrola wyniku,
* animacja = test dynamiki.

## Pierwsza komórka Markdown: Tekst

```markdown

# Fizyka

Newton:

$$
F=m a
$$

Einstein:

$$
E=mc^2
$$

```

## Druga komórka Markdown: Kod

```python

code

```


## Prompt do ChatGPT

```text
Napisz kod w Pythonie do Google Colab.
Kod ma symulować rzut ukośny bez oporu i z oporem powietrza.
Pokaż oba przypadki na jednym wykresie x-y.

```

---

## Dodanie odbicia

```text
Zmodyfikuj kod tak, aby pocisk odbijał się od gruntu.
Dodaj współczynnik restytucji e = 0.7.
Symulacja ma zatrzymać się, gdy ruch stanie się bardzo mały.
Zachowaj porównanie bez oporu i z oporem.
```

## Animacja w Colabie

```text
Na podstawie kodu przygotuj animację w Google Colab.
Dodaj ślady trajektorii.
Animacja ma wyświetlać się w notebooku.
```

## Eksport do video (MP4, avi, mkv)

```text
Dodaj zapis animacji jako MP4 w Colab.
```

## Eksport GIF

```text
Na podstawie kodu który robi video w colabie daj mi kod który w colabie wygerenuje mi animowanego gifa
```

Ważne: w promptach zawsze pisz, że kod ma działać w **Google Colab**.

---

# GitHub: repozytorium projektu

## Po co GitHub?

GitHub służy do:

* przechowywania plików,
* zapisu historii zmian,
* publikacji projektu,
* pracy w Codespaces,
* pracy z agentami.

## Założenie repozytorium

1. Wejdź na GitHub: https://github.com/
2. Utwórz konto.
3. Kliknij `New repository`.
4. Nazwa: `Test`.
5. Zaznacz: `Add a README file`.
6. Utwórz repozytorium.

`README.md` to główny opis projektu.

---

## Tworzenie pliku ręcznie

W repozytorium:

```text
Add file → Create new file
```

Nazwij plik:

```text
notes.md
```

albo:

```text
projectile_motion.md
```

Ważne: plik Markdown musi mieć rozszerzenie:

```text
.md
```

Potem kliknij `Preview`, aby zobaczyć wygląd dokumentu.

Na końcu kliknij:

```text
Commit changes
```

Commit = zapisany krok w historii projektu.

---

# Edytor kodu: Codespaces czyli Visual Studio Code w przeglądarce

Możliwa jest instalacja lokalnie na dysku (https://code.visualstudio.com/download?_exp_download=fb315fc982). Dziś tylko odpalenie wewnątrz Githuba 

## Uruchomienie

W repozytorium:

```text
Code → Codespaces → Create codespace on main
```

Otworzy się Visual Studio Code w przeglądarce. Jest to edytor kodu. Tam będzie można realizować kod, używać agentów, itd.

## Najważniejsze panele

### Explorer

Po lewej stronie.
Tu widać pliki projektu.

### Editor

Środek ekranu.
Tu edytujesz pliki.

### Markdown Preview

Dla plików `.md`:

```text
Open Preview
```

albo:

```text
Ctrl + Shift + V
```

### Source Control

Panel zmian plików.

Po edycji:

1. zapisz plik,
2. wejdź w `Source Control`,
3. wpisz komunikat commita,
4. kliknij `Commit`,
5. kliknij `Sync Changes` albo `Push`.

Ważne:

```text
Save ≠ Commit
Commit ≠ Push
```

Dopiero `Push` / `Sync` wysyła zmiany na GitHub!

---

# 8. Copilot: podpowiedzi w locie

Copilot podpowiada kod podczas pisania.

Przykład zacznij pisać

```python
# Air resistance projectile mo
```

Copilot może zaproponować kontynuację

Typowe klawisze:

```text
Tab — zaakceptuj sugestię
Esc — odrzuć sugestię
```

Zasada:

```text
Copilot przyspiesza pisanie...
```

---

# 9. Agent programistyczny: Codex

Agent działa szerzej niż Copilot.

Copilot podpowiada fragment. Agent może pracować na całym projekcie.

Agent może:

* czytać pliki,
* zmieniać kod,
* dodawać pliki,
* uruchamiać testy,
* naprawiać błędy,
* opisywać zmiany.

Trzeba w Visual Studio znaleźć Extensions i tam dodać:

- Codex – OpenAI’s coding agent i się zalogować do subskrybcji OpenAI
- Gemini Code Assist i się zalogować do subskrybcji Gemini

Poza tym jest Chat Copilot, który też jest agentem.
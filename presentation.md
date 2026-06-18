---
marp: true
title: AI Conferences 2026
description: Przeglad trendow konferencji AI
paginate: true
theme: default
style: |
	section {
		font-family: 'Aptos', 'Segoe UI', sans-serif;
		font-size: 30px;
		line-height: 1.35;
	}
	h1, h2 {
		color: #0f172a;
	}
	strong {
		color: #0b5fff;
	}
---

# AI Conferences 2026
## Kluczowe trendy, wyniki i kierunki

Remigiusz Durka  
18.06.2026

---

## Agenda

1. Dlaczego konferencje AI sa wazne
2. Najsilniejsze nurty badawcze
3. Metryki i jak je interpretowac
4. Rekomendacje na kolejne 12 miesiecy

---

## Dlaczego warto sledzic konferencje AI

- Najnowsze architektury pojawiaja sie najpierw w publikacjach
- Wyniki sa porownywane na tych samych benchmarkach
- Latwiej ocenic, co jest realnym postepem, a co marketingiem

W praktyce konferencje skracaja czas od idei do wdrozenia.

---

## Najsilniejsze nurty 2026

- Modele multimodalne: wspolne rozumienie tekstu, obrazu i audio
- Efektywnosc: mniejsze modele przy podobnej jakosci
- Agenci: planowanie krokow i wykonywanie zadan narzedziami
- Bezpieczenstwo: audyt, red-teaming i interpretowalnosc

---

## Jak czytac wyniki

Sredni blad kwadratowy:

$$
\mathrm{MSE} = \frac{1}{n}\sum_{i=1}^{n}(y_i-\hat{y}_i)^2
$$

Aktualizacja parametrow podczas uczenia:

$$
	heta_{t+1} = \theta_t - \eta\nabla_\theta J(\theta_t)
$$

---

## Co to znaczy dla zespolu

- Inwestuj w ewaluacje, nie tylko w trening modeli
- Utrzymuj powtarzalny pipeline eksperymentow
- Priorytetyzuj metryki produktowe obok metryk naukowych

Krotko: najlepszy model to ten, ktory poprawia decyzje biznesowe.

---

## Plan na nastepny kwartal

1. Wybrac 2 benchmarki zgodne z celem produktu
2. Uruchomic baseline i warianty modelu
3. Wprowadzic raport tygodniowy: jakosc, koszt, opoznienie
4. Podjac decyzje o wdrozeniu na danych walidacyjnych

---

# Dziekuje

Pytania?


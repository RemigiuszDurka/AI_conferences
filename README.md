# AI_conferences

## Sekcja 1: Wprowadzenie do modeli
Modele sztucznej inteligencji na konferencjach naukowych sa czesto porownywane przez pryzmat dokladnosci i zlozonosci, dlatego wygodnie jest opisywac ich jakosc metryka sredniego bledu kwadratowego: $\mathrm{MSE}=\frac{1}{n}\sum_{i=1}^{n}(y_i-\hat{y}_i)^2$. Taka forma oceny pozwala szybko zrozumiec, jak bardzo predykcje odbiegaja od wartosci rzeczywistych i czy proponowana architektura jest konkurencyjna wzgledem innych rozwiazan.

## Sekcja 2: Optymalizacja i uczenie
Podczas treningu modelu kluczowa jest aktualizacja parametrow zgodnie z kierunkiem gradientu, co mozna zapisac jako $\theta_{t+1}=\theta_t-\eta\nabla_\theta J(\theta_t)$, gdzie $\eta$ oznacza wspolczynnik uczenia. W praktyce uczestnicy konferencji czesto analizuja nie tylko wartosc funkcji kosztu, ale tez stabilnosc zbieznosci, aby ocenic, czy metoda optymalizacji dobrze skaluje sie do duzych zbiorow danych.

## Sekcja 3: Prawdopodobienstwo i niepewnosc
W nowoczesnych publikacjach rosnace znaczenie ma modelowanie niepewnosci predykcji, dlatego wiele podejsc korzysta z rozkladu normalnego opisanego wzorem $$p(x)=\frac{1}{\sqrt{2\pi\sigma^2}}\exp\left(-\frac{(x-\mu)^2}{2\sigma^2}\right).$$ Taki opis probabilistyczny ulatwia interpretacje wynikow i wspiera podejmowanie decyzji w zastosowaniach, gdzie sam punktowy wynik modelu nie jest wystarczajacy.
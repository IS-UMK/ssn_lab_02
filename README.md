# SSN. Lab. 2. Perceptron prosty

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [02_Perceptron.ipynb](https://github.com/IS-UMK/REPOblob/master/02_Perceptron.ipynb
)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_23_lab_02/blob/master/02_Perceptron.ipynb
) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_23_lab_02/master?filepath=02_Perceptron.ipynb
)

---

## Zad. 2. Perceptron i reguła delta

Zaimplementuj perceptron klasyfikujący (2 klasy) wraz z procedurą uczenia za pomocą reguły delta

$$
\Delta w_i=\lambda(y-f(\mathbf{x})) f^{\prime}(\mathbf{x}) x_i
$$

$$
\Delta b=\lambda(y-f(\mathbf{x})) f^{\prime}(\mathbf{x})
$$

Wykorzystaj sigmoidalną funkcję aktywacji 

$$
f(x)=\frac{1}{1+e^{-x}}, \qquad f^{\prime}(x)=f(x)(1-f(x))
$$

Zauważ, że funkcja sigmoidalna $f(x)$ posiada wartości z zakresu $(0,1)$ dlatego etykiety klas należy zakodować wartościami binarnymi $\{0,1\}$.

Następnie zbuduj model klasyfikacji dla zbioru danych Iris, który dyskryminuje gatunki ``Virginica`` i ``Versicolor``. Użyj wszystkich 4 zmiennych.

Wyświetl wykres prezentujący ilość błędów popełnianych przez perceptron w kolejnych iteracjach (lub epokach) uczenia.

Porównaj wykresy oraz uzyskany wynik klasyfikacji dla treningu ze współczynnikiem uczenia $\lambda = 0.1, \lambda=0.001, \lambda=100.0$


Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w Moodle lub prześlij do repozytorium GitHub.

---
## Materiały:

* S. Raschka, "Python machine learning" <br>Rozdział 2: "Training Machine Learning Algorithms for Classification" <br> https://github.com/rasbt/python-machine-learning-book/tree/master/code/ch02
* J. Vitay, "Neurocomputing", <br> Rozdział 4: "Linear classification" <br>
 https://julien-vitay.net/lecturenotes-neurocomputing/2-linear/4-LinearClassification.html






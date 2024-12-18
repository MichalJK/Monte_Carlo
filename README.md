Jest to przykład zastosowania symulacji Monte Carlo do określenia prawdopodobieństwa wyniku w przypadku, gdy występuje zmienność danych.  

Symulację zaprogramowano w Pythonie. Raport wykonano w Quarto w postaci dokumentu HTML w środowisku RStudio.

Dokument jest dostępny pod adresem: https://michaljk.github.io/Monte_Carlo

# Temat: Symulacja Monte Carlo - przykład
Model opisany jest prostą funkcją trzech zmiennych niezależnych $x_1, x_2, x_3$. Założono przy tym dla uproszczenia, że zmienne modelowe $x_1, x_2, x_3$ podlegają rozkładowi Gaussa i dane są poprzez swoje wartości średnie i odchylenia standardowe.

Eksperyment Monte Carlo polegał na wykonaniu 100 000 losowań zmiennych modelowych z zakresu ich zmienności przy wykorzystaniu generatora liczb losowych i funkcji odwrotnej prawdopodobieństwa skumulowanego. W wyniku otrzymano 100 000 wyników działania funkcji modelowej. Przeprowadzono podstawową analizę statystyczną wyników, wyznaczono wartość średnią i przedział 95% ufności oraz przeprowadzono ocenę zgodności z rozkładem normalnym. 




&nbsp;

--------------------------------------------------------------------------------------------------------------------------------------


This is an example of using Monte Carlo simulation to determine the probability of a model when there is variability in the data.

The simulation was written in Python. The report was produced in Quarto as an HTML document in the RStudio environment.

The document can be found at: https://michaljk.github.io/Monte_Carlo

# Topic: Monte Carlo Simulation - Example
The model is described by a simple function of three independent variables $x_1, x_2, x_3$. For simplicity, the model variables $x_1, x_2, x_3$ are assumed to follow a Gaussian distribution and are given by their mean and standard deviation.

The Monte Carlo experiment consisted of performing 100,000 draws of the model variables from the range of their variability using a random number generator and the inverse function of cumulative probability. This produced 100,000 results of the model function. A basic statistical analysis of the results was performed, the mean and 95% confidence interval were determined, and the conformity with the normal distribution was assessed.












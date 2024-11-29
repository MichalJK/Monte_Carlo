Jest to przykład zastosowania symulacji Monte Carlo do określenia prawdopodobieństwa wyniku w przypadku, gdy występuje zmienność danych.  

Symulację zaprogramowano w Pythonie. Raport wykonano w Quarto w postaci dokumentu HTML w środowisku RStudio.

Dokument jest dostępny pod adresem: https://michaljk.github.io/Monte_Carlo

# Temat: Symulacja Monte Carlo - przykład
Model opisany jest prostą funkcją trzech zmiennych niezależnych $x_1, x_2, x_3$. Założono przy tym dla uproszczenia, że zmienne modelowe $x_1, x_2, x_3$ podlegają rozkładowi Gaussa i dane są poprzez swoje wartości średnie i odchylenia standardowe.

Eksperyment Monte Carlo polegał na wykonaniu 100 000 losowań zmiennych modelowych z zakresu ich zmienności przy wykorzystaniu generatora liczb losowych i funkcji odwrotnej prawdopodobieństwa skumulowanego. W wyniku otrzymano 100 000 wyników działania funkcji modelowej. Przeprowadzono podstawową analizę statystyczną wyników, wyznaczono wartość średnią i przedział 95% ufności oraz przeprowadzono ocenę zgodności z rozkładem normalnym. 

           
#**Analiza Danych z Rozkładu Normalnego**

Opis projektu
           Ten projekt przeprowadza analizę dwóch zestawów danych wygenerowanych z rozkładu normalnego o średniej 3 i odchyleniu standardowym 1. Zbiory danych mają odpowiednio 100 i 10 000 elementów. Analiza obejmuje standaryzację                   danych, obliczanie statystyk opisowych oraz wizualizację wyników na różnych wykresach.
           
Struktura projektu
    data_100 - Zbiór danych o 100 elementach wygenerowanych z rozkładu normalnego.
    data_10000 - Zbiór danych o 10 000 elementach wygenerowanych z rozkładu normalnego.

Cele analizy
    Generowanie danych: Wygenerowanie dwóch zestawów danych z rozkładu normalnego o zadanych parametrach (średnia = 3, odchylenie standardowe = 1).
    Obliczenie statystyk: Obliczenie podstawowych statystyk opisowych, takich jak:
        Średnia
        Mediana
        Moda
        Kwartyle (Q1, Q2, Q3)
        Rozstęp międzykwartylowy (IQR)
        Wariancja
        Odchylenie standardowe
        Współczynnik asymetrii
    Standaryzacja danych: Przekształcenie danych, aby miały średnią 0 i odchylenie standardowe 1, co pozwala na porównanie zbiorów niezależnie od ich początkowej skali.
    Wizualizacja: Wizualizacja wyników za pomocą różnych wykresów:
        Histogramy dla oryginalnych i przeskalowanych danych
        Wykres pudełkowy (box plot)

Wymagania
     Aby uruchomić kod, wymagane są następujące biblioteki Pythona:
           numpy - do generowania danych i obliczania statystyk.
           scipy - do obliczenia współczynnika asymetrii.
           scikit-learn - do standaryzacji danych.
           matplotlib - do tworzenia wykresów.
               

Wnioski

    Większy zbiór danych (10 000 elementów) lepiej odwzorowuje rozkład normalny, z bardziej symetrycznym rozkładem i współczynnikiem asymetrii bliskim 0.
    Standaryzacja umożliwia porównanie zbiorów o różnych wielkościach, przekształcając dane tak, by miały średnią 0 i odchylenie standardowe 1.
    Wartości odstające i rozstęp międzykwartylowy różnią się między zbiorami, co jest efektem wielkości próby.

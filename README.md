# Projekt_informatyczny

## Opis
Projekt to prosty model przewidywania populacji Polski lub regionu w oparciu o dane historyczne i niezaawansowane metody statystyczne (drzewa decyzyjne). Korzyścią wyjściowych danych jest otrzymanie danych demograficznych przyszłych wielkościach zmiennych losowych w określonym przyszłym momencie.

## Wymagania
* zainstalowany Python (wersja 3.0)
* zainstalowany Jupyter Notebook (inna możliwość Visual Studio Code z odpowiednimi rozszerzeniami)
* zainstalowane biblioteki do Pythona (requests, pandas, matplolib, seaborn, sklearn, xgboost, graphviz)


## Instrukcja uruchomienia
1. Po instalacji wszystkich wymaganych komponentów sklonować repozytorium komendą `git clone https://github.com/michalzychowski/Projekt_informatyczny.git`
2. Następnie w konsoli wpisujemy `jupyter notebook` aby uruchomić Jupyter Notebook
3. Uruchamiamy skrypt w Jupyter Notebook

## Uwagi
Do uruchomienia kodu odpowiadającego za tworzenie drzew decyzyjnych potrzebujemy mieć zainstalowany Graphviz. \
[Graphviz Download](https://graphviz.org/download/) \
Do zmiennych środowiskowych PATH musi być dodadana ścieżka do folderu bin aplikacji Graphviz.
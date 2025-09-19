# Projekt informatyczny
## Opis
Projekt na przedmiot "Projekt informatyczny" na III roku studiów inżynierskich na kierunku Informatyka i ekonometria na UR. Celem projektu jest stworzenie prostego modelu przewidywania populacji Polski lub wybranego regionu w oparciu o dane historyczne i podstawowe metody statystyczne (drzewa decyzyjne). Dane wykorzystywane w projekcie pobierane są z API GUS (BDL), a użytkownik ma możliwość interaktywnego wyboru regionów oraz wskaźników do analizy.

## Technologie
Projekt został wykonany przy użyciu:
* Jupyter Notebook
* Python 3
* Biblioteki:
  * requests  
  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn
  * XGBoost
  * ipywidgets
  * IPython.display
* Graphviz

## Wymagania
Do uruchomienia projektu potrzebne są:
* Zainstalowany język Python 3.x
* Zainstalowane środowisko Jupyter Notebook (lub Visual Studio Code z rozszerzeniami Python + Jupyter, lub uruchomić w środowisku Google Colab)
* Zainstalowane wymienione biblioteki
* Zainstalowany Graphviz (patrz Uwagi)

## Instrukcja uruchomienia
1. Zainstaluj wymagane komponenty (Python, Jupyter Notebook, biblioteki)
2. Sklonuj repozytorium komendą `git clone https://github.com/michalzychowski/Projekt_informatyczny.git`
3. W terminalu uruchom Jupyter Notebook: `jupyter notebook`
4. Otwórz i uruchom skrypt

## Uwagi
Do uruchomienia kodu odpowiadającego za tworzenie drzew decyzyjnych potrzebujemy mieć zainstalowany Graphviz. \
[Graphviz Download](https://graphviz.org/download/) \
Do zmiennych środowiskowych PATH musi być dodana ścieżka do folderu bin aplikacji Graphviz.

## Licencja
Projekt jest dostępny na licencji [MIT](LICENSE).
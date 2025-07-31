# Analiza wskaźnika Beta dla spółek z indeksu WIG20

Głównym celem raportu jest przedstawienie wyników analizy wskaźnika Beta dla spółek
z indeksu WIG20, charakteryzującego się posiadaniem 20 największych spółek notowanych
na GPW pod względem kapitalizacji. Wskaźnik obrazuje zmianę stopy zwrotu konkretnej spółki
względem zmiany stopy zwrotu całego rynku, czyli używanego benchmarku (w przypadku
raportu za benchmark jest przyjmowany indeks WIG). Drugim, lecz niemniej ważnym celem
jest sprawdzenie dopasowania modelu do wyliczonej Bety. Najważniejszym pytaniem w tej
części brzmi, czy zmienność stóp zwrotu spółek ma swoje podłoże w zmianach indeksu WIG.


# Projekt zawiera 3 pliki:
  
| Nazwa pliku | Opis |
| :-------- | :------------------------- |
| "Raport do projektu.pdf" | Plik PDF zawierający podsumowanie wszystkich kroków (cel, metoda, wyniki, wniosek).
| "wig_d.csv" | Plik CSV zawierający dane historyczne benchmarku WIG, mającym być przyjętym całym rynkiem.
| "analiza_wskaźnika_beta.ipynb" | Cały kod, w którym była przeprowadzana analiza, napisany w Jupyter Notebook.

# Najważniejsze punkty w projekcie

 - Import danych z pliku csv oraz pobranie cen historycznych wszystkich 20 spółek przy pomocy biblioteki YahooFinance,
 - Obliczenie wartości Beta dla każdej spółki względem przyjętego benchmarku oraz współczynnika determinacji,
 - Podział spółek ze względu na wartość Beta (<=1 lub >1). 

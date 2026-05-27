# Analiza statystyczna: Psychometria i Struktura Zarobków

Projekt z zakresu Eksploracyjnej Analizy Danych (EDA) oraz wnioskowania statystycznego, zrealizowany w języku R.

## 🎯 Cel projektu
Głównym założeniem było przeprowadzenie pogłębionej analizy dwóch zbiorów danych:
1. **Wyniki testów psychologicznych:** Analiza wyników uczniów klas siódmych (relacje między ocenami a IQ).
2. **Struktura zarobków w USA (2000):** Badanie czynników wpływających na dochody (wykształcenie, płeć, sektor).

## 📂 Struktura repozytorium
Projekt został ułożony w sposób zapewniający pełną reprodukowalność:

* `oliwier_lewandowski_psp_1.Rmd` - Kod źródłowy (R Markdown).
* `/data/` - pliki wejściowe:
    * `grades.TXT` (wyniki testów psychologicznych),
    * `income.dat` (dane o zarobkach w USA).
* `/docs/` - Oryginalna treść zadania / instrukcja projektowa.
* `/reports/` - Wygenerowany raport końcowy (`oliwier_lewandowski_psp_1.pdf`).

## 🛠️ Wykorzystane technologie
* **Język:** R
* **Pakiety:** `ggplot2`, `data.table`, `gridExtra`, `knitr`.
* **Kluczowe techniki:** Statystyka opisowa, analiza gęstości rozkładów, wizualizacja danych, weryfikacja różnic statystycznych między grupami.

## 💡 Kluczowe wnioski
* **Świadome stosowanie statystyk:** Wskazano wyższość mediany nad średnią arytmetyczną w przypadku analizy zarobków, ze względu na obecność silnych wartości odstających.
* **Wizualna interpretacja:** Wykorzystano wykresy wiolinowe i gęstości rozkładów do zidentyfikowania nierówności dochodowych między płciami.
* **Psychometria:** Zbadano i zwizualizowano korelacje w wynikach testów uczniów, interpretując zależności między zmiennymi ilościowymi.

---
*Autor: Oliwier Lewandowski*
*Kontakt: oliwier.lewandowski2525@gmail.com*

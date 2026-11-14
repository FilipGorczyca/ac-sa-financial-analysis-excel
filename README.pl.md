<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/🇬🇧_English-Switch_language-0A66C2?style=for-the-badge" alt="English"></a>
  <a href="./README.pl.md"><img src="https://img.shields.io/badge/🇵🇱_Polski-Aktywny-dc143c?style=for-the-badge" alt="Polski"></a>
</div>

# 📊 Ocena kondycji finansowej AC S.A. (2018–2020)

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Finanse Przedsiębiorstw](https://img.shields.io/badge/Finanse_Przedsiębiorstw-0A66C2?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Zakończony-success?style=for-the-badge)

**Autor:** Filip Gorczyca  
**Kierunek studiów:** Analityka Gospodarcza, Uniwersytet Ekonomiczny w Krakowie (UEK)

---

## 📌 Cel projektu
Kompleksowa ocena kondycji finansowej oraz długoterminowych wyników działalności spółki **AC S.A.** (wiodącego europejskiego producenta samochodowych instalacji gazowych LPG i CNG pod marką **STAG**) w latach **2018–2020**, wraz z identyfikacją ryzyk operacyjnych i analizą porównawczą na tle sektora motoryzacyjnego.

## 📂 Zawartość repozytorium
| Plik | Opis |
| :--- | :--- |
| 📄 [`Ocena kondycji finansowej AC S.A. (2018-2020).pdf`](./Ocena%20kondycji%20finansowej%20AC%20S.A.%20(2018-2020).pdf) | **Pełny raport analityczny (22 strony)** zawierający sformatowane sprawozdania finansowe, tabele wskaźnikowe, modele dyskryminacyjne oraz interpretacje. |
| 📗 [`ocena kondycji finansowej przedsiębiorstwa.xlsx`](./ocena%20kondycji%20finansowej%20przedsiębiorstwa.xlsx) | **Skoroszyt źródłowy MS Excel (14 arkuszy)** z pełnymi obliczeniami: bilans, RPP, ZZWKW, RZiS, analiza pionowa i pozioma, wskaźniki finansowe, model Du Ponta, model Altmana oraz analiza SWOT. |

---

## 📈 Kluczowe dane i wskaźniki (2018–2020)

### 1. Podsumowanie wyników finansowych (w tys. zł)
| Wyszczególnienie | 2018 | 2019 | 2020 | Zmiana (2018–2020) |
| :--- | ---: | ---: | ---: | :---: |
| **Przychody netto ze sprzedaży** | 237 426 | 222 682 | 185 222 | 📉 -21,99% |
| **Zysk z działalności operacyjnej (EBIT)** | 49 562 | 46 283 | 36 767 | 📉 -25,82% |
| **Zysk netto** | 39 009 | 38 183 | 30 898 | 📉 -20,79% |
| **Aktywa razem** | 166 433 | 174 768 | 196 937 | 📈 +18,33% |
| **Kapitał własny** | 111 812 | 114 691 | 132 445 | 📈 +18,45% |
| **Przepływy pieniężne z działalności operacyjnej** | 50 690 | 41 601 | 18 841 | 📉 -62,83% |

### 2. Wybrane wskaźniki finansowe na tle branży
| Kategoria | Wskaźnik | 2018 | 2019 | 2020 | Wskaźnik branżowy (2020) | Ocena |
| :--- | :--- | ---: | ---: | ---: | ---: | :--- |
| **Rentowność** | Rentowność brutto sprzedaży (`RS`) | 20,85% | 19,82% | 17,41% | 5,30% | ✅ Powyżej średniej branżowej |
| **Rentowność** | Zyskowność netto sprzedaży (`ZD`) | 16,24% | 16,80% | 16,07% | 4,21% | ✅ Powyżej średniej branżowej |
| **Rentowność** | Zyskowność ogółu majątku (`ZOM`) | 23,44% | 22,38% | 17,22% | 5,01% | ✅ Powyżej średniej branżowej |
| **Rentowność** | Zyskowność kapitałów własnych (`ZKW`) | 34,89% | 33,72% | 25,82% | 9,65% | ✅ Powyżej średniej branżowej |
| **Płynność** | Wskaźnik płynności I stopnia (`WPI`) | 2,46 | 1,79 | 1,84 | 0,35 | ✅ Wysoka płynność bieżąca |
| **Płynność** | Wskaźnik płynności II stopnia (`WPII`) | 0,83 | 0,55 | 0,57 | 0,97 | ⚠️ Poniżej branży (wysokie zapasy) |
| **Obrotowość** | Wskaźnik obrotu zapasami w dniach (`WOZ`) | 121,9 d | 128,5 d | 165,8 d | ~7,5 d | ❌ Zamrożenie kapitału w zapasach |
| **Obrotowość** | Cykl środków pieniężnych (`CSP`) | 74,4 d | 105,3 d | 157,8 d | 13,0 d | ⚠️ Wydłużony cykl konwersji |
| **Zadłużenie** | Ogólna stopa zadłużenia (`SZ`) | 32,82% | 34,38% | 32,75% | 48,10% | ✅ Bezpieczny poziom zadłużenia |
| **Zadłużenie** | Trwałość struktury finansowej (`TSF`) | 139,09% | 122,60% | 128,50% | 130,00% | ✅ Stabilne finansowanie aktywów |

### 3. Modele wieloczynnikowe i dyskryminacyjne
* **Model Du Ponta ($ZKW = ZD \times RM \times SKW$):**
  * **2018:** $16,24\% \times 1,443 \times 1,489 = 34,89\%$
  * **2019:** $16,80\% \times 0,666 \times 1,524 = 33,72\%$ ($\Delta = -1,17\text{ p.p.}$)
  * **2020:** $16,07\% \times 0,357 \times 1,487 = 25,82\%$ ($\Delta = -7,89\text{ p.p.}$)
  * *Wniosek:* Spadek rentowności kapitału własnego wynikał przede wszystkim ze spadku rotacji majątku (`RM` z `1,44` do `0,36`), przy utrzymaniu bardzo wysokiej zyskowności netto sprzedaży (`~16%`).
* **Model Altmana (`Z-Score`):** `3,68` (2018) $\rightarrow$ `3,25` (2019) $\rightarrow$ `2,68` (2020) – spółka utrzymuje bezpieczną kondycję finansową, mimo tendencji spadkowej wywołanej niższą rotacją aktywów.
* **Analiza dyskryminacyjna ($Z_H$):** `2,14` (2018) $\rightarrow$ `1,51` (2019) $\rightarrow$ `1,47` (2020) – dodatnie wartości we wszystkich latach potwierdzają stabilność finansową podmiotu.

## 🔍 Główne wnioski strategiczne
1. **Przewaga rentownościowa:** AC S.A. generuje marże wielokrotnie przewyższające średnią w sektorze motoryzacyjnym (`ZKW` na poziomie `25,8%–34,9%` wobec `9,7%–12,0%` w branży), a dodatni wskaźnik dźwigni finansowej (`WDF` od `9,98` do `11,57`) potwierdza korzystny wpływ kapitału obcego.
2. **Stabilność kapitałowa:** Niskie zadłużenie ogólne (`~33%` sumy bilansowej) oraz wysoki udział kapitału własnego (`132,4 mln zł` w 2020 r.) gwarantują bezpieczeństwo długoterminowe.
3. **Obszar do optymalizacji (Kapitał obrotowy):** Wzrost zapasów (z `50,6 mln zł` w 2018 r. do `61,2 mln zł` w 2020 r.) wydłużył czas obrotu zapasami do `165,8 dni`, a cały cykl konwersji gotówki (`CSP`) do `157,8 dni`. Kluczową rekomendacją jest usprawnienie gospodarki magazynowej w celu uwolnienia zamrożonych środków pieniężnych.

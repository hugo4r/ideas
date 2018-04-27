* Automatyczne wczytywanie plików z podanej ścieżki / URLa. Odgaduje czy jest nagłówek, jaki jest separator, jaki format (rda, RData, txt, csv, tsv, sav, json).

* Po otrzymaniu komunikatu błędu, wyszukuje w internecie (stack / github?) odpowiedzi na pytania związane z tym błędem. Wyciąga najpopularniejsze odpowiedzi i je pokazuje w viewer.

* Analizuje występowanie brakujących danych w zbiorze danych i stara się je imputować. Usuwa nadmiar factorów i wspiera prosty preprocessing danych 

* Tryb `surprise me` w którym hugo szuka interesujących zależności pomiędzy zmiennymi i reaguje na komendy - inna para, inna zmienna zależna z x / y

* Wparcie przy czyszczeniu zmiennych, sprawdzanie czy daty są w jednym formacie, czy w kolumnach liczbowych nie ma dziwnych wartości lub jakiegoś przecinka, czy ostatni wiersz się dobrze wczytał - system check lista per zmienna

* Gdy juz raz nauczy się wczytywac jakiś plik to będzie pamiętał domyślne ustawienia i za drugim razem wczyta go dobrze bez dodatkowych pytań.

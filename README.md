# PowerBI-project
Przygotowane zostało zestawienie ocen wystawianych przez prowadzących na uczelni XYZ, w przeciągu ostatnich lat. Wykonano zestawienie, które pozwoli porównywać oceny wystawiane przez dwóch prowadzących oraz je podsumuje.
⦁	ID_PRACOWNIK – unikalny identyfikator pracownika
⦁	NAZWISKO – nazwisko pracownika
⦁	IMIE – imię pracownika
⦁	ROK_AKADEMICKI – rok akademicki, w którym wystawione zostały oceny
⦁	SEMESTR – określenie, czy semestr był letni, czy zimowy
⦁	KIERUNEK_STD – nazwa kierunku
⦁	Forma_studiów – określenie, czy studia zaoczne, czy dzienne
⦁	PRZEDMIOT – nazwa przedmiotu
⦁	NAZWA_FORMY_ZAJEC – forma zajęć 
⦁	FORMA_ZALICZENIA – forma w jakiej był zaliczany przedmiot
⦁	TERMIN – termin, w którym zostały wystawione oceny
⦁	LICZBA_OCENA_2_0 – ilość ocen 2.0
⦁	LICZBA_OCENA_3_0 – ilość ocen 3.0
⦁	LICZBA_OCENA_3_5 – ilość ocen 3.5
⦁	LICZBA_OCENA_4_0 – ilość ocen 4.0
⦁	LICZBA_OCENA_4_5 – ilość ocen 4.5
⦁	LICZBA_OCENA_5_0 – ilość ocen 5.0
⦁	NUMER_SEMESTRU – numer semestru, na którym odbyły się zajęcia

 
Rysunek 1 Przykładowa realizacja zadania

W celu dodania dwóch macierzy, które będzie można zależnie od siebie filtrować, zduplikuj tabelę jako źródło danych, a następnie dodaj trzecią tabelę, która będzie zawierała unikalne kombinacje semestru i roku. Dzięki temu będą zwracane wspólne wynik ina podstawie semestru i roku. Dane zostały podzielone na dwa pliki. Należy je zaimportować i połączyć ze sobą. Zwróć uwagę na kolejność kolumn i ich nazwy w obu plikach. Pamiętaj, aby po wykonaniu raportu wykonać raport podsumowujący.

Cele do wykonania
⦁	Macierz wyświetlająca sumę ocen wystawionych przez prowadzącego w poszczególnych latach, z podziałem na semestr letni i zimowy. Niech suma będzie prezentowana w formie procentów, sumując się do 100% w zakresie wiersza.
⦁	Macierz wyświetlająca sumę ocen wystawionych przez drugiego prowadzącego w poszczególnych latach, z podziałem na semestr letni i zimowy. Niech suma będzie prezentowana w formie procentów, sumując się do 100% w zakresie wiersza.
⦁	Macierz wyświetlająca różnicę pomiędzy ocenami wystawionymi przez obydwu prowadzących (wynik z macierzy 1 – wynik z macierzy 2). Niech suma będzie prezentowana w formie procentów, sumując się do 100% w zakresie wiersza.
⦁	Dodaj nową kolumnę o nazwie Pracownik, która połączy imię, nazwisko i ID pracownika.
⦁	Dodaj możliwość filtrowania strony po: roku akademickim, typie semestru, pracowniku, numerze semestru, przedmiocie, terminie, formie zajęć, kierunku i formie studiów.
⦁	Dodaj wykresy typu tooltip do macierzy z punktów 1 i 2, które wyświetlą ile i jakich ocen łącznie wystawiono w danym roku i semestrze. Tytuł powinien generować się dynamicznie w zależności od roku i semestru.	

 
Rysunek 2 Przykład wizualizacji do zadania 6

⦁	Dodaj wykres typu tooltip do wykresu podsumowującego, który wyświetli różnice pomiędzy obydwoma panelami. Tytuł powinien generować się dynamicznie w zależności od roku i semestru.

 
Rysunek 3 Przykład wizualizacji do zadania 7

⦁	Dodaj wykres liniowy przedstawiający średnią ocen wystawioną przez prowadzących w poszczególnych latach.
⦁	Dodaj warianty uproszczone macierzy z zadań 1,2,3. Zamiast poszczególnych ocen pogrupuj je w kategorie: Niskie (2.0, 3.0), Średnie (3.5, 4.0), Wysokie (4.5, 5.0). Powinno móc się przełączać pomiędzy wariantem szczegółowym i uproszczonym przy pomocy przycisków.
⦁	Przygotuj wykresy typu tooltip dla wersji uproszczonych, które będą spełniały to samo zadanie co wersje szczegółowe. 

Po wykonaniu panelu napisz raport, który będzie zawierać wnioski oraz ewentualne rekomendacje dotyczące analizowanych danych. Raport może między innymi zawierać punkty, którym warto się przyjrzeć podczas korzystania z raportu, co udało się uzyskać, a także pewien opis analizowanego zbioru danych.

Zadanie 1 (1 pkt)
Napisz program w Pythonie, który utworzy funkcjê lambda, która dodaje 15 do podanej liczby przekazanej jako argument, stwórz równie¿ funkcjê lambda, która mno¿y argument x przez argument y i wypisz wynik.
Zadanie 2 (1 pkt)
Napisz program w Pythonie do sortowania listy s³owników za pomoc¹ Lambda.
[{'make': 'Nokia', 'model': 216, 'color': 'Black'}, {'make': 'Mi Max', 'model': 2, 'color': 'Gold'}, {'make': 'Samsung', 'model': 7, 'color': 'Blue'}]
Zadanie 3 (1 pkt)
Napisz program w Pythonie, który podniesie do kwadratu i szeœcianu ka¿d¹ liczbê z podanej listy liczb ca³kowitych za pomoc¹ Lambda.
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Zadanie 4*(3 punkty)
Stwórz klasê Game, która bêdzie klas¹ bazow¹, z metod¹ z play, która ma w nazwie wskazywaæ, ¿e nie nale¿y jej modyfikowaæ (metoda chroniona), oraz która wyœwietla informacjê o rozpoczêciu gry. Dodatkowo ma zawieraæ liczbê graczy.
Stwórz drug¹ klasê Hangman, która dziedziczy po klasie Game i pozwoli zagraæ w grê wisielec, gdzie gracz musi odgadn¹æ s³owo, podaj¹c pojedyncze litery.
Hangman ma 1 albo 2 graczy, przy 2 – jedna osoba wpisuje s³owo do odgadniêcia.
Gra ma umo¿liwiaæ wybór poziomu trudnoœci (beginner, intermediate, advanced) i w zale¿noœci od wybranego poziomu, dostêpna liczba b³êdnie odgadniêtych liter ma byæ mniejsza. Np. dla poziomu beginner gracz mo¿e pomyliæ siê 8 razy, intermediate 5 razy, a advanced 3 razy.
W grze mamy te¿ mieæ mo¿liwoœæ wyboru liczby graczy, je¿eli jest jeden to s³owo losowane jest z listy, a je¿eli dwóch graczy, to jeden wpisuje s³owo do odgadniêcia, a drugi je zgaduje.
Gra mo¿e byæ stworzona dla dowolnego jêzyka, ale jeden jêzyk na grê (np. angielski).
Zadanie 4 nale¿y oddaæ w formacie .py, tak, ¿eby by³a mo¿liwoœæ uruchomienia i grania w terminalu.
Do pobierania s³ów/znaków od u¿ytkownika skorzystaj z metody gotowej metody input(). 
Dodatkowo pamiêtaj o obs³udze wyj¹tków, je¿eli np. to co wpisa³ w terminalu gracz jest spoza dopuszczalnej listy znaków.

Zadanie 1 (1 pkt)
Napisz program w Pythonie, kt�ry utworzy funkcj� lambda, kt�ra dodaje 15 do podanej liczby przekazanej jako argument, stw�rz r�wnie� funkcj� lambda, kt�ra mno�y argument x przez argument y i wypisz wynik.
Zadanie 2 (1 pkt)
Napisz program w Pythonie do sortowania listy s�ownik�w za pomoc� Lambda.
[{'make': 'Nokia', 'model': 216, 'color': 'Black'}, {'make': 'Mi Max', 'model': 2, 'color': 'Gold'}, {'make': 'Samsung', 'model': 7, 'color': 'Blue'}]
Zadanie 3 (1 pkt)
Napisz program w Pythonie, kt�ry podniesie do kwadratu i sze�cianu ka�d� liczb� z podanej listy liczb ca�kowitych za pomoc� Lambda.
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Zadanie 4*(3 punkty)
Stw�rz klas� Game, kt�ra b�dzie klas� bazow�, z metod� z play, kt�ra ma w nazwie wskazywa�, �e nie nale�y jej modyfikowa� (metoda chroniona), oraz kt�ra wy�wietla informacj� o rozpocz�ciu gry. Dodatkowo ma zawiera� liczb� graczy.
Stw�rz drug� klas� Hangman, kt�ra dziedziczy po klasie Game i pozwoli zagra� w gr� wisielec, gdzie gracz musi odgadn�� s�owo, podaj�c pojedyncze litery.
Hangman ma 1 albo 2 graczy, przy 2 � jedna osoba wpisuje s�owo do odgadni�cia.
Gra ma umo�liwia� wyb�r poziomu trudno�ci (beginner, intermediate, advanced) i w zale�no�ci od wybranego poziomu, dost�pna liczba b��dnie odgadni�tych liter ma by� mniejsza. Np. dla poziomu beginner gracz mo�e pomyli� si� 8 razy, intermediate 5 razy, a advanced 3 razy.
W grze mamy te� mie� mo�liwo�� wyboru liczby graczy, je�eli jest jeden to s�owo losowane jest z listy, a je�eli dw�ch graczy, to jeden wpisuje s�owo do odgadni�cia, a drugi je zgaduje.
Gra mo�e by� stworzona dla dowolnego j�zyka, ale jeden j�zyk na gr� (np. angielski).
Zadanie 4 nale�y odda� w formacie .py, tak, �eby by�a mo�liwo�� uruchomienia i grania w terminalu.
Do pobierania s��w/znak�w od u�ytkownika skorzystaj z metody gotowej metody input(). 
Dodatkowo pami�taj o obs�udze wyj�tk�w, je�eli np. to co wpisa� w terminalu gracz jest spoza dopuszczalnej listy znak�w.

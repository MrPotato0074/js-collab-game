<ins>TEST 1. Mapa ma cztery pokoje, tylko jeden zaznaczony. Informacje są bezpłatne.</ins>
<ins>Wynik Oczekiwany:</ins> Po wpisaniu start(),rozejrzyj(), status() powinien pokazywac nadal 10 energii.
<ins>Wynik Otrzymany:<ins/> Poprawna ilosc energii (10).

<ins>TEST 2. Lewo z pokoju 1 i nieznany kierunek nie zmieniają<ins/> danych.
<ins>Wynik Oczekiwany:<ins/> Jesli jestesmy w pokoju 1 i sprobujemy pojsc w lewo nic nie powinno sie zmienic.
<ins>Wynik Otrzymany:<ins/> Nie bylo mozliwosci pojsc w lewo.

<ins>TEST 3. Prawo przesuwa o jeden pokój i zużywa jedną energię.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli jestesmy w pokoju 1 i sprobujemy pojsc w prawo powinnismy wejsc do pokoju 2 i stracic jedna energie.
<ins>Wynik Otrzymany:<ins/> Pojawilismy sie w pokoju 2 i stracilismy 1 energie.

<ins>TEST 4. Tego samego przedmiotu nie da się zabrać dwa razy.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli podnieslismy np. karte nie bedzie mozliwosci podniesienia jej drugi raz.
<ins>Wynik Otrzymany:<ins/> Po podniesieniu karty nie mozna podniesc jej drugi raz i energia nie spada drugi raz.

<ins>TEST 5. Nie da się naprawić zasilania bez bezpiecznika ani otworzyć drzwi bez obu wymagań.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli sprobujemy naprawic zasilanie bez bezpiecznika nie powinno byc to mozliwe, tak samo z otwieraniem drzwi.
<ins>Wynik Otrzymany:<ins/> Poprawne. Nie da sie otworzyc drzwi ani wlaczyc zasilania bez wymaganych przedmiotow.

<ins>TEST 6. Da się wygrać, wykonując potrzebne czynności w rozsądnej kolejności.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli bedziemy zbierac wszystko po kolei, bez wiekszego problemu powinnismy skonczyc gre.
<ins>Wynik Otrzymany:<ins/> Poprawne. Zebranie potrzebnych przedmiotow nie jest skomplikowane.

<ins>TEST 7. Po dziesięciu poprawnych ruchach bez wygranej następuje porażka. Kolejny ruch nie zmienia już stanu.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli bedziemy chodzic bez sensu w pewnym momencie energia spadnie i przegramy.
<ins>Wynik Otrzymany:<ins/> Poprawne. Po wykorzystaniu 10 energii nalezy zaczac nowa gre.

<ins>TEST 8. start() przywraca energię, pozycję oraz wszystkie flagi.<ins/>
<ins>Wynik Oczekiwany:<ins/> Jesli zresedujemy gre, energia przywracana jest do maxa i przedmioty wracaja na miejsce.
<ins>Wynik Otrzymany:<ins/> Poprawne. Po zresetowaniu gry wracamy z 10 energii i bez przedmiotow.
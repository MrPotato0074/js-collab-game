<ins>TEST 1. Mapa ma cztery pokoje, tylko jeden zaznaczony. Informacje są bezpłatne.</ins> <br/>
<ins>Wynik Oczekiwany:</ins> Po wpisaniu start(),rozejrzyj(), status() powinien pokazywac nadal 10 energii. <br/>
<ins>Wynik Otrzymany:<ins/> Poprawna ilosc energii (10). <br/>

<ins>TEST 2. Lewo z pokoju 1 i nieznany kierunek nie zmieniają<ins/> danych. <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli jestesmy w pokoju 1 i sprobujemy pojsc w lewo nic nie powinno sie zmienic. <br/>
<ins>Wynik Otrzymany:<ins/> Nie bylo mozliwosci pojsc w lewo. <br/>

<ins>TEST 3. Prawo przesuwa o jeden pokój i zużywa jedną energię.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli jestesmy w pokoju 1 i sprobujemy pojsc w prawo powinnismy wejsc do pokoju 2 i stracic jedna energie. <br/>
<ins>Wynik Otrzymany:<ins/> Pojawilismy sie w pokoju 2 i stracilismy 1 energie. <br/>

<ins>TEST 4. Tego samego przedmiotu nie da się zabrać dwa razy.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli podnieslismy np. karte nie bedzie mozliwosci podniesienia jej drugi raz. <br/>
<ins>Wynik Otrzymany:<ins/> Po podniesieniu karty nie mozna podniesc jej drugi raz i energia nie spada drugi raz. <br/>

<ins>TEST 5. Nie da się naprawić zasilania bez bezpiecznika ani otworzyć drzwi bez obu wymagań.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli sprobujemy naprawic zasilanie bez bezpiecznika nie powinno byc to mozliwe, tak samo z otwieraniem drzwi. <br/>
<ins>Wynik Otrzymany:<ins/> Poprawne. Nie da sie otworzyc drzwi ani wlaczyc zasilania bez wymaganych przedmiotow. <br/>

<ins>TEST 6. Da się wygrać, wykonując potrzebne czynności w rozsądnej kolejności.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli bedziemy zbierac wszystko po kolei, bez wiekszego problemu powinnismy skonczyc gre. <br/>
<ins>Wynik Otrzymany:<ins/> Poprawne. Zebranie potrzebnych przedmiotow nie jest skomplikowane. <br/>

<ins>TEST 7. Po dziesięciu poprawnych ruchach bez wygranej następuje porażka. Kolejny ruch nie zmienia już stanu.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli bedziemy chodzic bez sensu w pewnym momencie energia spadnie i przegramy. <br/>
<ins>Wynik Otrzymany:<ins/> Poprawne. Po wykorzystaniu 10 energii nalezy zaczac nowa gre. <br/>

<ins>TEST 8. start() przywraca energię, pozycję oraz wszystkie flagi.<ins/> <br/>
<ins>Wynik Oczekiwany:<ins/> Jesli zresedujemy gre, energia przywracana jest do maxa i przedmioty wracaja na miejsce. <br/>
<ins>Wynik Otrzymany:<ins/> Poprawne. Po zresetowaniu gry wracamy z 10 energii i bez przedmiotow. <br/>

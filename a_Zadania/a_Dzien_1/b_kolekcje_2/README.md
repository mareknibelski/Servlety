<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Java - kolekcje

#### Zadanie 1 - rozwiązywane z wykładowcą.

W pliku `Main1.java`:
1. Napisz program który w metodzie main będzie w pętli pobierał z konsoli napisy, do momentu podania `exit`.
2. Pobrane od użytkownika napisy dodawaj do kolekcji typy `Set`.
3. Utwórz zmienną typu `int` o nazwie `count` i wartości początkowej 0.
4. Po pobraniu napisu zwiększaj wartość zmiennej `count`.
3. Testując program podaj kilkukrotnie ten sam napis.
4. Po wpisaniu `exit` wypisz na konsoli: `Podanych napisów: [ilość napisów], Rozmiar kolekcji: [ilość elementów w kolekcji]`

-----------------------------------------------------------------------------

#### Zadanie 2.

W pliku `Main2.java`:

1. Napisz metodę `public static Map<String, String> getMap()`, która utworzy 5 dowolnych zestawów przeciwieństw (ciepło - zimno), doda je do mapy, a następnie zwróci.
2. W metodzie main programu dla każdego klucza mapy, pobieraj z konsoli odpowiedź użytkownika.
3. Program ma zadać 5 pytań.
4. Po udzieleniu ostatniej - wyświetlić wynik w postaci `Poprawnych odpowiedzi: 3`;

#### Zadanie 3

Utwórz klasę `Country`,  dodaj w niej atrybuty:
* name (String)
* capital (String)

Następnie w pliku `Main3.java`:
1. Napisz metodę `public static List<Country> initialize ()`, która utworzy 5 obiektów klasy `Country`,
 doda je do listy, którą następnie zwróci.
2. Napisz metodę `public static Map<String, Country> getMap (List<Country> list )`,
 która utworzy a następnie zwróci mapę gdzie kluczem będzie nazwa stolicy pobrana z obiektu `country`, 
 a wartością referencja do obiektu `Country`: 
3. W metodzie `main` wyświetl informacje w postaci: 
   ```
   Berlin - Niemcy
   Warszawa - Polska
   ```
<!-- Links -->
[list-iterator]:https://docs.oracle.com/javase/8/docs/api/java/util/ListIterator.html

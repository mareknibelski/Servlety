<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Java EE  - Servlety

### Zadania.

Rozwiązania zadań umieszczaj we wcześniej utworzonym projekcie.

#### Zadanie 1 - rozwiązywane z wykładowcą

1. W projekcie stwórz servlet `Servlet21` dostępny pod adresem **/Servlet21**, który wyświetli w przeglądarce lokalny czas.


#### Zadanie 2 - rozwiązywane z wykładowcą
1. W projekcie stwórz servlet `Servlet22` dostępny pod adresem **/Servlet22**,
oraz stronę HTML `index.html`, z odnośnikiem do servletu.
2. Zainicjuj w desktyptorze wdrożenia parametr dostępny tylko dla servletu o nazwie `myParam` oraz wartości `coderslab.pl`. 
3. Pobierz parametr w servlecie, a następnie wyświetl na stronie.


-------------------------------------------------------------------------------

#### Zadanie 3

1. W projekcie stwórz servlet `Servlet23`, dostępny pod adresem **/Servlet23**,
który wyświetli w konsoli "Zadanie 3".
2. Komunikat na konsoli powinien zostać wyświetlony tylko raz, niezależnie od ilości odświeżeń strony. Skorzystaj z metody `init`.

#### Zadanie 4
1. W projekcie stwórz servlet `Servlet24` dostępny pod adresem **/Servlet24**,
oraz stronę HTML `index.html`, z odnośnikiem do servletu.
2. Zainicjuj w deskryptorze parametr dostępny w całej aplikacji o nazwie `applicationName` oraz wartości `MyApplicationName`. 
3. Pobierz parametr `applicationName` w servlecie, a następnie wyświetl na stronie.

#### Zadanie 5
1. W projekcie stwórz servlet `Servlet25` dostępny pod adresem **/Servlet25**,
2. Wyświetl w przeglądarce poniższe informacje:
    * Adres IP
    * Przeglądarkę
    * Aktualny czas


#### Zadanie 6

1. W projekcie stwórz servlet `Servlet26` dostępny pod adresem **/Servlet26**,
2. Pobierz z nagłówka HTTP informacje na temat przeglądarki użytkownika, a następnie wyświetl na stronie informacje w postaci:
`Użytkownik używa przeglądarki: Chrome`.
 
Hint: Sprawdź jakiej przeglądarki używa użytkownik wg. poniższych zasad (jeśli ciąg zawiera):  
  * `Chrome` - `Google Chrome`
  * `Firefox` - `Mozilla Firefox`
  * `Opera` - `Opera`
  * `Safari` - `Safari`

Jeśli posiadasz kilka przeglądarek, sprawdź czy Twój kod działa prawidłowo.

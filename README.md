 
# <p align="center">O Bank Internetowy </p>

## <p align="center">Opis projektu </p>

<p align="center">Celem projektu było stworzenei niezależnego systemu bankowego, który był cześcią ekosystemu bankowości z Jednostką Rozliczeniową oraz drugim niezależnym bankiem. Bank miał za zadanie łączyć się z Jednostką Rozliczeniową by wykonywać przelewy do odrębnego banku. Węwnętrzne przelewy były wykonywane bez pośrednictwa Jednostki rozliczeniowej jak i przelewy ekspresowe międzybankowe </p>

<p alingn="center">Opis Aplikacji</p>

Aplikacja została stworzona za pośrednictwem następujących technologii:</p>

*	-PHP
*	-HTML/CSS Bootstrap
*	-Mysql

<p alingn="center">Struktura Projektu:</p>

![image](https://user-images.githubusercontent.com/58811103/118054173-17219b00-b386-11eb-81d8-2ef1082d3992.png)

<p alingn="center">Interakcja</p>

<p alingn="center">Aby zalogować się do serwisu należy wpisać Login oraz Password. W przypadku nie podania żadnych danych, pojawi się stosowny komunikat o wpisaniu ich. W przypadku wpisania niepoprawnych danych pojawi się komunikat o ponownej próbie logowania.</p>

<p alingn="center">Po zalogowaniu się do serwisu w zależności od typu konta, pojawi się odpowiednia strona.</p>

<p alingn="center">Admin</p>

<p alingn="center">Każdy z przycisków odpowiada za pokazanie konkretnych informacji:</p>

●	Users – zarządzanie użytkownikami i jego danymi.</p>

●	Accounts – zarządzanie kontami, pokazanie operacji kont danego konta oraz przypisanie konta do użytkownika.</p>

●	Operations – wypisanie wszystkich operacji w banku.</p>

●	Take list of payments – pobranie listy przelewów z jednostki rozliczeniowej.</p>

●	Logout – Wylogowanie się z serwisu.</p>




<p alingn="center">Users</p>

<p alingn="center">Wypisane wszystkich użytkowników w banku.</p>



<p alingn="center">Możliwe jest tworzenie konta dla nowego użytkownika, usuwanie oraz modyfikowanie. W przypadku kont adminowskich, admin nie może usunąć oraz zmienić danych innego admina.</p>



<p alingn="center">Po wpisaniu odpowiednich danych do odpowiednich pól jest możliwe stworzenie nowego użytkownika. W przypadku nie wpisaniu danych, pojawi się stosowny komunikat o wypełnieniu danego pola. Po prawidłowym utworzeniu użytkownika, pojawi się na liście użytkowników.</p>

<p alingn="center">Do każdego konta są przypisane dwie funkcję, które odpowiadają za zmianę danych lub usunięcie konkretnego konta. Także pojawia się hasło danego użytkownika w przypadku potrzeby zmiany. W tym przykładzie zostanie zastosowana zmiana typu konta ze zwykłego użytkownika do administratora.</p>

<p alingn="center">Zmiana udała się. Aby zmienić na konto zwykłe należy się zalogować na to konto i zmienić osobiście.</p>

 
<p alingn="center">Accounts</p>

<p alingn="center">W poniższym widoku, są przedstawione wszystkie konta, które są dotychczas przechowywane przez bank. Możemy przejrzeć wszystkie konta, kto jest ich właścicielem, zmienienie właściciela oraz przejrzenie przelewów danego konta bankowego.</p>


<p alingn="center">Dodanie nowego konta następuje przy wykorzystaniu gotowej funkcji która generuję numer konta bankowego. Funkcja jest przygotowana konkretnie dla tego banku.
</p>


<p alingn="center">Funkcja zwraca tylko prawidłowe numery bankowe. Po stworzeniu konta, konto automatycznie zostanie przypisane do administratora banku, więc manualnie należy skojarzyć konto bankowe z nowym użytkownikiem.</p>
 



<p alingn="center">Konto zostanie przypisane do nowego użytkownika.</p>


<p alingn="center">W przypadku potrzeby usunięcia konta, należy potwierdzić czynność.</p>


<p alingn="center">Konto zostało usunięte, lecz dla testów zostanie utworzone nowe dla tego samego użytkownika.</p>

<p alingn="center">
Przelewy danego rachunku bankowego. W tej chwili ten numer nie posiada przelewów.</p>



<p alingn="center">Operations</p>

<p alingn="center">Wyświetlanie wszystkich przelewów w banku B.</p>



<p alingn="center">Take list of payments</p>

<p alingn="center">Pobieranie przelewów przychodzących z jednostki rozliczeniowej jest wykonywane za wywołaniem funkcji. Następujący wynik przedstawia, że 2 przelewy przychodzące zostały zwrócone do jednostki rozliczeniowej z powodu braku odbiorców, lecz jeden numer rachunku należy do banku B, więc przelew został przypisany do istniejącego rachunku.
</p>


<p alingn="center">Logout
</p>
<p alingn="center">Zostaniemy wylogowani z sesji. By ponownie skorzystać z aplikacji należy się zalogować.</p>


<p alingn="center">Użytkownik</p>

Każdy z przycisków odpowiada za pokazanie konkretnych informacji:</p>

●	Your personal Data– przedstawienie danych użytkownika z możliwą edycją niektórych danych.</p>

●	Your Accounts – przedstawienie użytkownikowi jego kont z operacjami oraz wykonywanie za pomocą ich przelewów.</p>

●	Logout – Wylogowanie się z serwisu.</p>



<p alingn="center">Przelewy</p>

<p alingn="center">Wykonanie przelewu, niezależnie czy zostanie wykonane przez użytkownika bądź administratora jest wykonywana ta sama czynność. Po wybraniu jednego z kont użytkownika, możemy wykonać przelew. Zostanie przedstawiony widok gdzie są przedstawione nasze dane. Przy nie podaniu danych do realizacji przelewów zostanie wyświetlony komunikat.</p>

<p alingn="center">Po wpisaniu wszystkich danych możemy przystąpić do realizacji przelewu. W przypadku podaniu błędnej ilości pieniędzy zostanie wyświetlony odpowiedni komunikat.</p>


<p alingn="center">Po poprawnym wpisaniu danych zostanie wypisany następujący komunikat. Aktualnie jest realizowany przelew wewnętrzny. Także operacja zostanie wypisana w operacjach przypisanych do tego konta.</p>


<p alingn="center">W przypadku podania błędnego numeru rachunku, który nie spełnia walidacji, przelew nie zostanie zrealizowany.
</p>


<p alingn="center">W przypadku wysłania przelewu zewnętrznego zostanie wypisany następujący komunikat.</p>


<p alingn="center">Type of Payment określa czy dany przelew ma być przelewem ekspresowym czy normalnym. W przypadku przelewu ekspresowego zostanie poniesiona dodatkowa opłata.
</p>

<p alingn="center">W przypadku przelewu ekspresowego jeśli nie otrzymamy kontaktu z drugim bankiem, bądź bank A nie będzie posiadał takiego numeru, będzie przelew zwrotny z oddaniem pieniędzy.</p>

<p alingn="center">Przedstawione zostały różne operację z konta administratora.
</p>

<p alingn="center">Dla odbierania przelewów ekspresowych został przygotowany odpowiedni endpoint. Przy pomocy Postmana, została zasymulowana operacja przelewu ekspresowego z banku A do banku B. Przez podanie wszystkich danych oraz poprawnych, zostanie zwrócony obiekt, gdzie przedstawia dane informację oraz wynik czy przelew został zaakceptowany. Jeżeli zmienna “isThisnumber” jest false , przelew nie został zaakceptowany przez Bank B.</p>


<p alingn="center">Wynik naszego przelewu ekspresowego.</p>

<p alingn="center">Jeśli zostaną podane błędnę dane lub ich brak, przelew nie zostanie zaakceptowany.</p>


<p alingn="center">Przedstawienie poszczególnych funkcji odpowiedzialnych za funkcjonowanie aplikacji</p>

<p alingn="center">Przetwarzanie stron internetowych</p>



<p alingn="center">Przy pomocy php, jest możliwe odtwarzanie wielu segmentów, który każdy z nich jest odpowiedzialny za inną stronę. Nie jest konieczne tworzenie wielu podstron obsługujących jednakowo jeden segment.</p>


<p alingn="center">Pobranie listy przelewów z jednostki rozliczeniowej oraz ich rozpatrzenie</p>
 
<p alingn="center">Generowanie prawidłowego numeru konta</p>

 
<p alingn="center">Funkcja odpowiedzialna za zwroty</p>

 
<p alingn="center">Funkcja odpowiedzialna za określenie przelewu jako wewnętrzny/ zewnętrzny.</p>

<p alingn="center">Funkcja odpowiedzialna za przelewy.</p>
<p alingn="center"></p>

 
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

<p align="center">
 <img src="https://user-images.githubusercontent.com/58811103/118055026-9e234300-b387-11eb-955a-e0cfce3db89b.png
">
</p>

<p alingn="center">Po zalogowaniu się do serwisu w zależności od typu konta, pojawi się odpowiednia strona.</p>

<p alingn="center">Admin</p>
![image](https://user-images.githubusercontent.com/58811103/118055042-a7141480-b387-11eb-993b-13909d527397.png)
<p alingn="center">
<img src="">
</p>
<p alingn="center">Każdy z przycisków odpowiada za pokazanie konkretnych informacji:</p>

●	Users – zarządzanie użytkownikami i jego danymi.</p>

●	Accounts – zarządzanie kontami, pokazanie operacji kont danego konta oraz przypisanie konta do użytkownika.</p>

●	Operations – wypisanie wszystkich operacji w banku.</p>

●	Take list of payments – pobranie listy przelewów z jednostki rozliczeniowej.</p>

●	Logout – Wylogowanie się z serwisu.</p>


<p align="center">
 <img src="">
</p>

<p alingn="center">Users</p>

<p alingn="center">Wypisane wszystkich użytkowników w banku.</p>

![image](https://user-images.githubusercontent.com/58811103/118055064-b1cea980-b387-11eb-9cc3-3d615ed27e9a.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">Możliwe jest tworzenie konta dla nowego użytkownika, usuwanie oraz modyfikowanie. W przypadku kont adminowskich, admin nie może usunąć oraz zmienić danych innego admina.</p>
<p alingn="center">
<img src="">
</p>
![image](https://user-images.githubusercontent.com/58811103/118055070-b5fac700-b387-11eb-9009-acddf855e194.png)
![image](https://user-images.githubusercontent.com/58811103/118055079-b8f5b780-b387-11eb-9154-40b8551fe655.png)

<p alingn="center">Po wpisaniu odpowiednich danych do odpowiednich pól jest możliwe stworzenie nowego użytkownika. W przypadku nie wpisaniu danych, pojawi się stosowny komunikat o wypełnieniu danego pola. Po prawidłowym utworzeniu użytkownika, pojawi się na liście użytkowników.</p>

![image](https://user-images.githubusercontent.com/58811103/118055112-c6ab3d00-b387-11eb-9323-20bac1a20fa6.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">Do każdego konta są przypisane dwie funkcję, które odpowiadają za zmianę danych lub usunięcie konkretnego konta. Także pojawia się hasło danego użytkownika w przypadku potrzeby zmiany. W tym przykładzie zostanie zastosowana zmiana typu konta ze zwykłego użytkownika do administratora.</p>

![image](https://user-images.githubusercontent.com/58811103/118055119-cca11e00-b387-11eb-96a6-e597bd1c4ef1.png)
<p alingn="center">
<img src="">
</p>
<p alingn="center">Zmiana udała się. Aby zmienić na konto zwykłe należy się zalogować na to konto i zmienić osobiście.</p>

 
<p alingn="center">Accounts</p>

<p alingn="center">W poniższym widoku, są przedstawione wszystkie konta, które są dotychczas przechowywane przez bank. Możemy przejrzeć wszystkie konta, kto jest ich właścicielem, zmienienie właściciela oraz przejrzenie przelewów danego konta bankowego.</p>
![image](https://user-images.githubusercontent.com/58811103/118055135-d62a8600-b387-11eb-95dd-48f2a2344922.png)

<p alingn="center">
<img src="">
</p>
<p alingn="center">Dodanie nowego konta następuje przy wykorzystaniu gotowej funkcji która generuję numer konta bankowego. Funkcja jest przygotowana konkretnie dla tego banku.
</p>
![image](https://user-images.githubusercontent.com/58811103/118055145-da56a380-b387-11eb-9cfe-4d875787533c.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">Funkcja zwraca tylko prawidłowe numery bankowe. Po stworzeniu konta, konto automatycznie zostanie przypisane do administratora banku, więc manualnie należy skojarzyć konto bankowe z nowym użytkownikiem.</p>
 
![image](https://user-images.githubusercontent.com/58811103/118055158-e2164800-b387-11eb-807a-c35223bb867b.png)

<p alingn="center">
<img src="">
</p>

<p alingn="center">Konto zostanie przypisane do nowego użytkownika.</p>
![image](https://user-images.githubusercontent.com/58811103/118055180-eb071980-b387-11eb-8acc-500681d332e3.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">W przypadku potrzeby usunięcia konta, należy potwierdzić czynność.</p>
![image](https://user-images.githubusercontent.com/58811103/118055225-0114da00-b388-11eb-8061-f5f878c9cd2a.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">Konto zostało usunięte, lecz dla testów zostanie utworzone nowe dla tego samego użytkownika.</p>

![image](https://user-images.githubusercontent.com/58811103/118055247-0a05ab80-b388-11eb-8ec7-e5920b77aba5.png)
<p alingn="center">
<img src="">
</p>
<p alingn="center">
Przelewy danego rachunku bankowego. W tej chwili ten numer nie posiada przelewów.</p>
<p alingn="center">
<img src="">
</p>
![image](https://user-images.githubusercontent.com/58811103/118055259-0ffb8c80-b388-11eb-881d-22120778df11.png)

<p alingn="center">
<img src="">
</p>
<p alingn="center">Operations</p>

<p alingn="center">Wyświetlanie wszystkich przelewów w banku B.</p>

![image](https://user-images.githubusercontent.com/58811103/118055271-15f16d80-b388-11eb-91ce-dc91e08dcc5a.png)
<p alingn="center">
<img src="">
</p>

<p alingn="center">Take list of payments</p>

<p alingn="center">Pobieranie przelewów przychodzących z jednostki rozliczeniowej jest wykonywane za wywołaniem funkcji. Następujący wynik przedstawia, że 2 przelewy przychodzące zostały zwrócone do jednostki rozliczeniowej z powodu braku odbiorców, lecz jeden numer rachunku należy do banku B, więc przelew został przypisany do istniejącego rachunku.
</p>
<p alingn="center">
<img src="">
</p>
![image](https://user-images.githubusercontent.com/58811103/118055293-20ac0280-b388-11eb-84ba-567b02c4612c.png)

## <p alingn="center"> Logout </p>
<p alingn="center">Zostaniemy wylogowani z sesji. By ponownie skorzystać z aplikacji należy się zalogować.</p>


## <p alingn="center"> Użytkownik </p>

<p align="center"> Każdy z przycisków odpowiada za pokazanie konkretnych informacji:</p>

*	Your personal Data– przedstawienie danych użytkownika z możliwą edycją niektórych danych.

*	Your Accounts – przedstawienie użytkownikowi jego kont z operacjami oraz wykonywanie za pomocą ich przelewów.

*	Logout – Wylogowanie się z serwisu.


<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055311-286ba700-b388-11eb-8946-b7dd137ec7ef.png">
 <img src="https://user-images.githubusercontent.com/58811103/118055325-2d305b00-b388-11eb-997e-2576ca77656e.png">
</p>



## <p alingn="center"> Przelewy</p>

<p alingn="center"> Wykonanie przelewu, niezależnie czy zostanie wykonane przez użytkownika bądź administratora jest wykonywana ta sama czynność. Po wybraniu jednego z kont użytkownika, możemy wykonać przelew. Zostanie przedstawiony widok gdzie są przedstawione nasze dane. Przy nie podaniu danych do realizacji przelewów zostanie wyświetlony komunikat.</p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055331-31f50f00-b388-11eb-9c78-3d4588dfeb4a.pn">
</p>

<p alingn="center"> Po wpisaniu wszystkich danych możemy przystąpić do realizacji przelewu. W przypadku podaniu błędnej ilości pieniędzy zostanie wyświetlony odpowiedni komunikat.</p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055352-39b4b380-b388-11eb-8a90-9cc3b67d9cb6.png">
</p>

<p alingn="center"> Po poprawnym wpisaniu danych zostanie wypisany następujący komunikat. Aktualnie jest realizowany przelew wewnętrzny. Także operacja zostanie wypisana w operacjach przypisanych do tego konta.</p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055362-3faa9480-b388-11eb-89d9-912289f7c96e.png">
</p>

<p alingn="center"> W przypadku podania błędnego numeru rachunku, który nie spełnia walidacji, przelew nie zostanie zrealizowany.
</p>

<p alingn="center">
<img src="(https://user-images.githubusercontent.com/58811103/118055378-4802cf80-b388-11eb-99dd-16bdc5d599f6.png">
</p>

<p alingn="center"> W przypadku wysłania przelewu zewnętrznego zostanie wypisany następujący komunikat. </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055397-5224ce00-b388-11eb-9c6f-4ed27672cd0a.png">
 <img src="https://user-images.githubusercontent.com/58811103/118055412-5a7d0900-b388-11eb-8bf5-193353bc14d3.png">
 <img src="https://user-images.githubusercontent.com/58811103/118055417-5cdf6300-b388-11eb-8a84-ae42db962c09.png">
</p>


<p alingn="center"> Type of Payment określa czy dany przelew ma być przelewem ekspresowym czy normalnym. W przypadku przelewu ekspresowego zostanie poniesiona dodatkowa opłata.
</p>


<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055428-649f0780-b388-11eb-9750-886792860fa7.png">
</p>


<p alingn="center"> W przypadku przelewu ekspresowego jeśli nie otrzymamy kontaktu z drugim bankiem, bądź bank A nie będzie posiadał takiego numeru, będzie przelew zwrotny z oddaniem pieniędzy. </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055481-7c768b80-b388-11eb-9856-67aa17296c82.png">
</p>

<p alingn="center"> Przedstawione zostały różne operację z konta administratora.
</p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055491-7ed8e580-b388-11eb-88c0-1fc0164de777.png">
</p>

<p alingn="center"> Dla odbierania przelewów ekspresowych został przygotowany odpowiedni endpoint. Przy pomocy Postmana, została zasymulowana operacja przelewu ekspresowego z banku A do banku B. Przez podanie wszystkich danych oraz poprawnych, zostanie zwrócony obiekt, gdzie przedstawia dane informację oraz wynik czy przelew został zaakceptowany. Jeżeli zmienna “isThisnumber” jest false , przelew nie został zaakceptowany przez Bank B. </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055512-88624d80-b388-11eb-8c31-5d7e908371d8.png">
</p>

<p alingn="center"> Wynik naszego przelewu ekspresowego.
Jeśli zostaną podane błędnę dane lub ich brak, przelew nie zostanie zaakceptowany. </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055524-8ef0c500-b388-11eb-9ba9-d873787577e9.png">
</p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055552-9dd77780-b388-11eb-8575-3226f5a797ab.png">
</p>

# <p alingn="center">Przedstawienie poszczególnych funkcji odpowiedzialnych za funkcjonowanie aplikacji</p>

## <p alingn="center"> Przetwarzanie stron internetowych </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055565-a5971c00-b388-11eb-934d-337d25399508.png">
</p>

<p alingn="center"> Przy pomocy php, jest możliwe odtwarzanie wielu segmentów, który każdy z nich jest odpowiedzialny za inną stronę. Nie jest konieczne tworzenie wielu podstron obsługujących jednakowo jeden segment. </p>

## <p alingn="center"> Pobranie listy przelewów z jednostki rozliczeniowej oraz ich rozpatrzenie </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055597-b182de00-b388-11eb-9d7a-ffdc37f2495e.png">
</p>

## <p alingn="center"> Generowanie prawidłowego numeru konta </p>

<p alingn="center">
<img src="https://user-images.githubusercontent.com/58811103/118055604-b47dce80-b388-11eb-9312-70014bcd9708.png">
</p>
 
## <p align="center"> Funkcja odpowiedzialna za zwroty </p>

<p align="center">
<img src="https://user-images.githubusercontent.com/58811103/118055614-b9428280-b388-11eb-8760-cfbfad13a7cf.png">
</p>
 
## <p alingn="center"> Funkcja odpowiedzialna za określenie przelewu jako wewnętrzny/ zewnętrzny. </p>

<p align="center">
<img src="https://user-images.githubusercontent.com/58811103/118055630-be073680-b388-11eb-8e5a-0ae23030d528.png">
</p>

## <p align="center"> Funkcja odpowiedzialna za przelewy. </p>

<p align="center">
<img src="https://user-images.githubusercontent.com/58811103/118055647-c3648100-b388-11eb-8046-d613c8d133e0.png">
<img src="https://user-images.githubusercontent.com/58811103/118055657-c6f80800-b388-11eb-8ad7-fd7938fe4888.png">
</p>

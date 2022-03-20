

1.Stwórz repozytorium
2.Pobierz odpowiednio pliki: app.py,index.html,login.html,requirements.txt
  Plik app.py jest naszym plikiem z kodem programu
3.Plik app.py został zmodyfikowany, w miejscu gdzie znajduje się 
  parametr "Adrian" wpisz "username"
4.Pliki index.html oraz login.html proszę umieścić do folderu templates
5.Wersja wymagana Pythona3.8 oraz zainstalowany Pycharm
6.Stworzyć plik Makefile w którym zapiszemy w prosty sposób potrzebne komendy  

*test: pip install requirements.txt run: python -m flask 
*run pyl: pylint app.py make test - pozwoli na zainstalowanie wymienionych w
 pliku programów/składników. 
*make run - pozwoli na odpalenie programu flask, potrzebnego w kroku 10 make
 pyl - program sprawdzi jakość naszego kodu app.py
    
7.Stworzyć w Pycharmie wirtualne środowisko oraz umieścić w nim przygotowane
  pliki
8.Otwieramy przeglądarkę oraz nowy terminal
9.W przeglądarce wpisujemy adres http://127.0.0.1:5000/ powinna nam wyskoczyć
  strona z napisem Hello WSB
10.W nowym terminalu wpisz curl http://127.0.0.1:5000/, zauważyć trzeba że
   terminal gdzie został uruchomiony program flask jest zablokowany
11.W przeglądarce wpisujemy adres http://127.0.0.1:5000/login powinna nam
   wyskoczyć strona z prośbą o podanie imienia.
12.Po podaniu imienia i przejścia dalej pokaże nam się strona z kolejnym
   napisem. Adres strony skopiuj i wpisz do terminalu curl... Można
   zauważyć różnicę
13.W pliku app.py znajdz funkcję index i zmień parametr "username" zmień na
   swoje imię.
14.Zainstaluj narzędzie pylint (sudo apt install pylint)
15.Uruchom make pyl

Mam nadzieję że o to chodziło w zadaniu 10


# Pygame - gry w swiecie pythona

### Jak zacząć?

Od najmłodszych lat, każdy z nas ma doczynienia z grami planszowymi, komputerowymi, konsolowymi czy innym rodzajem gier.
W późniejszym wieku lub nawet w młodszych latach, niektórzy z nas, bądź większość, chciała stworzyć własną grę w którą
gracze chcieliby grać. W trakci nauki programowania możliwości nasze znacznie się zwiększyły, aby stworzyć grę komputerową.
Na zajęciach postaramy się napisać grę, która zostanie stworzona w naszym ulubionym języku oraz przy użyciu biblioteki pygame.[1]
Ale zanim to następi, zaczniemy krótkim teoretyczny wstępem, abyśmy mogli podjeść do tematu jak najbardziej profesjonalnie.

#### *Czym tak naprawdę jest gra?*
Gra jest to zabawa, która ma swoje zasady, dzięki którym możemy regulować jej stan, rozgrywkę oraz wygrać lub przegrać. [2]
Po zapoznaniu się z terminem słowa gra, możemy usiąść i zabrać się za przygotowanie zasad, świata, postaci czy rodzaju gry.

#### *I co dalej?*
Jak zapewne wiecie, nie ma "przepisu" na dobrą grę, która osiągnie niesamowity sukces. Większość z nas podczas rozgrywki
chciała zmienić reguły gry czy dodać coś co wzbogaciłoby rozgrywkę. Dowdzi to, że każdy z nas ma pomysł, który nic nie kosztuje, 
a może stworzyć nową grę czy też wzbogacić nas o doświadczenie jak dana rzecz faktycznie zadziała i czy zadziała poprawnie.
W pewien sposób jest to wstęp do projektowania gier czy też samej produkcji gry. Jedną z metody rozpoczęcia pracy nad grą jest
stworzenie GDD (Game Design Document)[3], czyli dokumentu opisującego funkcjonalność i opis samej gry. Następnie można sprawdzić
rozpisany dokument i zadać sobie pytanie: *Czy chcielibyśmy sami zagrać w tę grę?*, pozwoli to nam na określenie grywalności gry wg.
własnego uznania - *Jeżeli nie tworzymy gry w którą chcielibyśmy zagrać to po co wogóle to robić?*.

#### *Jak to ma się w świecie gier komputerowych?*
Jak powszechnie wiadomo w grach komputerowych królują inne język jako te w których się je tworzy, najbardziej popularne to C++, C#, JavaScript, HTML5 
czy Flash. Natomiast języki takie jak python czy lua, często są wykorzystywane jako języki pomocniczne do pisania szybkich skryptów, ale niestety samo 
pisanie gry w tych języka często jest mniej optymalne niż w wyżej wymienionych. Język C++ jest najczęściej wykorzystywany do tworzenia silników gry 
(ang. game engine)[4], a python jest użyty, aby oskryptować odpowiednie narzędzia silnika graficznego. Oczywiście dla lua czy python istnieją również silniki 
czy biblioteki, aby wspomóc te języki w programowanie gier. Istnieją odpowiedni silnik w zależności od naszych potrzeb tj. do gier 2D i 3D.
Dla python najpopularniejsze silniki zostały przedstawione na wiki pythonowym.[5] A jeżeli chodzi o język lua tutaj mamy trochę gorszą sytuację, gdyż tych 
silników jest mniej, a niestety nie ma ich wszystkich spisanych, prawdopodobnie przyczyną jest mniejsza popularność niż pythona.[6] Natomiast jednym z 
najbardziej popularnych silników jest LOVE.[7]

Na naszych zajęciach wykorzystami bibliotekę pythonową *pygame*.[1] Zapoznamy się z funkcjami tej biblioteki oraz spróbujemy stworzyć grę.
W trakcie warsztatów również poruszymy kwestię jak w łatwy sposób stworzyć grę przy użyciu mechaniki oraz wykorzystania gotowych rzeczy, które
można znaleźć w sieci tj. assety (dźwięku, grafikę). Wybierzemy również jeden z rodzajów gier na którym się skupimy i postaramy się w ciągu
kilku godzin stworzyć pierwsze arcydzieło. :)

### Rodzaje gier:
* gry rekreacyjne
* gry logiczne
* gry platformowe
* gry zręcznościowe
* gry przygodowe
* gry akcji
* gry sportowe, wyścigi
* gry fabularne (cRPG), MMORPG
* gry strategiczne
* gry symulacyjne
* survival horrory
* gry edukacyjne

### Podsumowanie

Aby napisać grę wystarczy pomysł, mechanika oraz grafika i dźwięk. W przypadku, gdy brakuje nam umiejętności do stworzenia grafiki, muzyki czy dźwięków,
istnieją serwis, gdzie można pobrać i wykorzystać całkowicie za darmo. Odpowiednio stworzony dokument GDD oraz zbalansowanie świata gry, pozwoli na 
stworzenie gry, która będzie grywalna. Oczywiście wszystkie elementy z którymi się zapoznamy nie dadzą nam możliwości stworzenia gier jak GTA, BattleField
czy nawet mniej znanych tytułów, ale od czegoś trzeba zacząć, a przy okazji pobawimy się pythonem i mam nadzieję, że stworzymy w pełni funkcjonalne i grywalne
gry. Być może uda się wspólnie wypracować dzieło, którym będziemy mogli się pochawlić na następnym PyConie. :)

### Referencje

* [1] Oficjalna strona biblioteki http://www.pygame.org/
* [2] Znaczenie słowa "gra" wg. wikipedii http://pl.wikipedia.org/wiki/Gra
* [3] Jak stworzyć Game Design Document http://www.gamasutra.com/view/feature/131632/creating_a_great_design_document.php
* [4] Co to jest silnik gry http://en.wikipedia.org/wiki/Game_engine
* [5] Silniki pythonowe https://wiki.python.org/moin/PythonGames
* [6] Silniki dla lua http://www.gamefromscratch.com/post/2012/09/21/Battle-of-the-Lua-Game-Engines-Corona-vs-Gideros-vs-Love-vs-Moai.aspx
* [7] Love2D http://love2d.org/
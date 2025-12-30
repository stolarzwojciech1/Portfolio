!+tab = początkowe wpisy strony

lorem= duo tekstu

<p> akapit z treścią

WOrdtrap in view= tekst w jakby tabeli

<h1> -<h6> hierarchia i struktura treści h do -->0 h1-jeden na stronie bez sensu jak więcej

nagłówki nie daje się akapitów

<p class="atrybut">odziawujacy</p>

alt+shift+F - sprząganie kodu naprawa bałaganu

zbadaaj - F12 -narzędzia dla deweloperów

przesuwanie lementu po wjechaniu na niego

<br> nowa linia -wymuszenia złamania wiersza

file -preferences auto save 

<strong> wytłuszaczanie. Nie wytłuszaj tesktu

<b> zwróc umwage żadziej niż strong

<em> nacisk

<i> pojęcia techniczne , myśli-kursywa

elementy blokowe - tworzą nową linię , zajmują całą szerokość. Blokowych nie wlinowych

elementy liniowe -Strong itp. obok siebie się , tyle miejsc ile potrzebują

<img width="200" height="100"> obrazki <img src="ścieżka do pli" alt= "opis obrazaka"> gdy nie wyświetli ten opis

obrazki jako tło q css

szkielet dokumentu -preambuła doctype, html- całość zawartoś dokumentu + lang ,

<head> meta dane opisujące dokumnet> <utf8> kodowanie <title> tytół do gogle również.

<viewport> meta tag, meta name

<body> całą zawartość

walidator - sprawdza poprawność kodu - validator.w3.org -film ze sprawdzaniem kodu-drugi moduł



CSS kaskadowe rkusz stylów- Warstwa strony reprezentacyjna. Moduł dwa. 

mdm display - browser compatybiliti na samym dole.- czy stron ajest wspierana

caniuse com.czy strona jest wspierana

&nbsp;

next

Skłądania css i sposoby osadzania.

<style> 	.nagłówek{color:red</style> 

class="nagłówek: jako atrybout znacznika

<link href="scieka" rel="stylesheet" > osobny plik css na osadzanie w <head>

css fromateer - w aplikacjach

<style in p błędne osadzanie> bez pośrednie osadzanie tylko wyjątkowo

<span>, <div> - kontenery bez znaczenia poetyckiego. DO stylowania .np. odniesienia do Java Script.

div to element blokowy,, spam -phrasing  content

Przed divem i za pojawi się nowa linia, zagospodaruje całkowią szerokość

SPan do środka -justowanie małych elementów.<div> np. do p akapitów.

transparent - kolor przezroczysty., nawa koloru -zadko używane, szesnastowy- używane ćżęśćiej

hsla - (249, 91%, 19%, 0.7} odcień  

backqround-color : red- kolor tła,

color-kolor tekstu

"zanim zaczniemy - modól2. 

js- zorientowany obiektowo.,  DOM modyfikacje. obraz z kamery, gry itp.

sopecyfikacja - ecmasript - 262, draft

JS- sposoby osadzania itp. 

Hello word--> w body --> aby cały dom był już do JS dostepny

<script>console.log ("czesc'")</script> -tekst w terminalu

kod w JS wykonuje się tylko raz.

<alert>

JS name.js

<script src-""></script> <script defer"></script>- wykona dopiero jak cały DOM się wypisze.

ja script on clic alert - nie piszemy tak

let nawa- wartość .w "tu"

Wirlkoś liter w zminnej ma znaczenie. 

let nagłówek = document.querySelector(".nagłówek")

nagłówek.classlist.add("nazwa lklasy")

nagłówek.classlist.remove(nazwa klas")

nagłówek.classlist.toggle("'")

naglowe.inertext="nowa treść -tylko teksowa zawartość

naglowe.inerhtm;:"nowa treść<br>"- cały html

nagłówek.innerText"= "nowy tekst"

naglowek.remove() -usuwa. naglowek

Przycisk

<button class="jakiśprzycisk">usun</button>

przycisk.addEventListener("click", () =>{  \\\\nałuchuj zdarzenia

nagłówel - document ,queryselektor".główek")

nagłowe.remove(); }



moduł 3=-4minuta link i script

klasa do <body> MOZNA po samym postylować po samym znaczniku

7:19 - booton java script

zewnętrzne css i js .farba

8:15 js zmiana tła.

dwa akapity jak chceny zrobić przerwę między wierszami a nie <br>

14:15 obsługa przycisków

<h1> jeden tylko powinien być



moduł 3 html - tabele 

tabele to nie layouty, css to tak

<table> <capition> 3:03

wiersze <tr> in <td> 3:50

nagłówki 5:10

scope ->col>row - nagłówki kolumny >nagłówki wierszy

rowsspan>> kmórka moze zajmować więcej miejsca prze wiersze i kolumny.

colspan np. 2 9:40





6:09:2025

html - listy

<ul> lista nie uporzątkowana

<li> zagnieżdżanie 0:55 <li> w <ul>

wypunktowana

kolejnoś c elementó nie ma znaczenia

używana do nawigacj

<ol> lista uporządkowana renderowana jako numerowana

type -artrybut np.a 4:42

reversed - odwócona kolejność 

start - od jakiej liczby zacząć 5;55



Html - dzielimy dokument na sekcje

seatyczne - posiadją swoje znaczeni

przykłądowy layout

<header>- nagłówek całego dokumentu,-dzieckiem body ine elementy których może być nagłówkiem :<article, section, aside, nav, 4

H1-h6 w headre

logo , nawigacja(może również być poza header>)

&nbsp;header-nie musi być na samej górze'



<nav> - pod headre, nawigacja po sekcjach dokumentu bez hiperłączy pomad stroną, nav w nav nie zagnieżamy

główna nawigacja  - nie jest zmieniana na podstronach

umieszcamy ją poza znacznikiem <main>

nav w header- może być, ale nie koniecznie



<main> główna zawartość dokumentu. Występuje raz ,zwykle jako bezpośrednie dziecko <body>

&nbsp;zawiera unikalną tresć, główny artykuł na stronie, film do obejrzenia

<mej> zmienia się na podstronach



<article> nagłówki i akapity z treśćią, samodzielny fragment trześci np. pojedyczy post na blog.

ma sens nawet przy usunięciu innych częśći. Zawiera h1-h6. W jego środku mogą być równe znaczniki:header, aside, footer.

Article samodzielna treść.



<aside> Informacje dodatkowe: pozwiązane treści , reklam, uzupełnienie czegoś, linki, cytaty, biografaia autora artykułu.



aside w kolejny poziom nawigacji. Często przedstawiany jako znaczek boczne.< aside> w <aside> jest błędne.



<footer> stopka. gdzie kolwiek i czegoolwiek>

<section> grupujemy treść tematycznie powinnoscia jest h1-h6, articel kontra section+ =tworzy problemy kiedy który znacznich wybrać.

więsze, logiczne , części dokumentu.



<hr> linia teraz już css. Słuzy do zmiany tematów na poziomie akapitów.





Moduł 3 dalsza część- dzielimy dokument na sekcja



linki-tworzą sieć w WWW. odnoszą się do wszystkiego.

<a hrev>link</A

hrev- adres URL zasobu

link właściwoś target="\_blank otwiera link w nowej karcie

warto dodać : rel=noreferrer" jeśli nie, to strona otwierana móże np. pokierować do innej strony.

title - co zawiera strona co do niej linkujemy.Załączamy w <hrev

właściwość download w ahrev- kiedy plik pobieramy.

linkiem może być obrazek. dodajemy jakieś tilte itp.

linki nie muszą być tekstowe

Atrybut SCR względem aktualnego folderu w którym jest html...lub pełen adres zewnętrzny

&nbsp;pod # może również być pełny adres internetowy

link do sekcji na stronie. 

<ahrev> w <body< sectio  = id 8:50 po #

można się odnieść do sekcji na innej stronie internetowej czy strony www

linki nie "kliknij tutaj"

powinny buć krótkie i nie wstawiać tekst linka wstawiać URL

nie używamy linków jako przycisków.

link jako mail.-mailto

link jako tel.



moduł 3- css , wymiary , odstępy

box model, zaokrąglanie boków, box-sizing.

div class (.element)

css .element{width:1px height:3px}

wymiary mogą być w procentach. rzadko ustawiam wysokość, bo jest automatyczna.

wysokość się pojawia jak jest treść  bez hight -wysokość jak wielka jest trzcionk



max-widht np. 500

height rzadko potrzebne.



obramowanie \_\_element - border

obramowania mają różne style.

mogę rodzielic border na pojedyncze sekcje np. border-wight

grubość 4 krawędzi w jednym skrócie => np. border width :10px 20 30px  zgodne z ruchem wskazówek zegara

08:52

border- botton - wight -coś do zmiany

zaokrąglanie rogów -> border-radius 20px

zaokrąglenie eliptyczne 

można podać 4 wartości i zaokrąglić każdy kąt inaczej.

może być: border-top/botton- -right - left-radius ==> moża przypisąć wyjątek do np. do jednego z czterech

padding/- odstępy między treścią a oprogramowaniem.

może być procentowy , pikselowy,

13:54

padding może być różńy dla różnych krawędzi.

margin -zewńetrzy odstęp. Pixele  itp. 

elementy mogą na siebie nachodzić 

margin może wyśrodkować element w poziomie.

margin:0 auto; do elementów blokowych możę być 100 i zero.

collapsing - czasem dolny i górny margines dwóch elementów łączą się w jeden.i większy z nich brany jest pod uwagę.zasady który jest któy są zawiłę.

box model -  definiuje zależności między treścią, padding, border oraz margin.Lementy blokowy. 

span klass inleain .inleain: {height :200 px,} ==>element się nie przeją ==element liniowy

elementy schodzą się na siebie jeśli są opcją liniową.

domyślnie szerokość i wysokość dotyczą tylko treści.

np. Elelement się nie zmieśił po dostał stoprocent tylko na treść.jescze jest padding i border.

dla ratunku box model.==>box-sizing: border-box ==wtedy box model dodaje więcej atrybutów.

box wstawiamy ==> html{box-sizing: border-box;}

\*, ::after, ::before {box-sizing :inherit:}



moduł 3 outline i cienie

outline podobnie do border .elemen w środku . Zewnętrzne dodatkowe oprogramowanie.

posiada outline widht,  style -color

nie wpływa na inne elementy , nie wpływa na obliczanie wymiarów eementów (Box Model)

style są takie same jak do border.

out-line offset - okręsla ilość miejsca pomiędzy krawędzią lub obramowaniem elementu a jego outlinem.

przeglądarki ddają domyśłny stan out line w stanie Focus.- nie usuwać. 

box shadow - cień box shadow\_generator.



text-shadow - cień trczionki

cieni może być kilka wymieniamy je po przecinku, 

isytnieje cień trzcionki.

cień nie ma spread-radius,



moduł3 -czcionki i odstępy między wierszami.

Font - nie czcionka, używa się ich zamiennie.

w css font-family:- kruj pisma 

.element{

font-family: "arial" , sans-serif;

}

sans-serif -używa w drugiej kolejnośći

po przecinku, można dodać więcej czcionek.

czcionki np. proporowana - san-serif

mono space - wszystkie znaki tak samo szerokie

04:36

google fonts googl daj e link do umieszczenia na stronie.

wrzucamy link w <head> i odpowiedni do css

wybieramy potzrzebne trczionki 1-2 wystarczą 

kursywa - font-style:italic; 

bez googla też się pochyli na swój własny sposób.



rozmiar czcionki =font-size:20px

grubość- font weight

przeglądarka w br automatycznie wytłuści czcionke

sciąganie wytłuszczenia przez przyczepieni elementu css-font-weight- normal 

możeby takżę ustalać grubość cyfrowo. np.400 i 700

odstępy między wierszami-wysokość linii

&nbsp;np. .line-heigh 1.5



00:01

css- stylowanie tabel 

<table></table> do th dodajemy scope=:col" V row.

Zwykłę oprogramowanie dodajemy zwykle do komórek, nie do tabeli.

.table{font}

szukamy wszystkie td na <"td class=tablecell">

th również 

dodajemy table cell do css i urozmaicamy styl

02:42

class:"jakaś klasa" scope "row"  i colspan ="3"

03.02

borde-collapse: collapse - łączy obramowania komórek w jedno.Standartowa technika. 

linie tylko u góry -border-widht = 0 0 1  px

można dodać do tabeli padding np. 20px

wyśrodkowanie komórek => text-alingn: center;

...można dorzucić .caption {caption-side: bottom; text-align: right;}

jeszcze np. margin-top



wygląd nagłówków- color, background, font-weight np. normal  itp.

wprowadzam zamienianie aby otrzymać table header , albo jedną tą samą klase do wybranych przez Ciebie.

widht- np. 100% do tabeli - wypełni całą dostępną szerokość

zebra- co drugi wiersz tabeli, inny kolor.== .tablerow:nth-child(even){color:red}

even- znaczy parzyste

tr np. dodajemy klase, następnie .tablerow:hover {color:red}- działa po najechaniu.

vertical-align; wyśrodowanei w pionie.top , bottom, middle

08:31

<thead> <tbody> <tfoot>- mogą się przydać do zamknięcia całego nagłówka,ciała lub stopki tabeli w element.

resposwnosć tabel. 

overflow-x:auto wklejamy tabelę ,tabel zchowje się tak, że jest dopasowana do mniejsztch szerokości ekranów.



moduł 3 stylowanie list

style domyślne uporzątkowania i nie.

styl domyślny := margines u góry, i na dole, padding, brak odstępów między elementami

.listitem{MARGIN: 10PX 0}

kżdy li zamieniam a li z klasą listitem

margin

możemy zmienć paddink tylko lewej strony isty

padding left.

list-style-type - ustawia znacznik dla elelentów listy

&nbsp;	decimal - dzieśiętne

&nbsp;	decimal- leading zero -liczby dzieśiętne z 0 na początku

&nbsp;	lower-roman - małeliczby rzymskie

&nbsp;	upper-roman - wielkie liczby rzymskie 

&nbsp;	lower greek - małę litey greckie

&nbsp;	lower alpha, lower-latin -młe litery łacińskie

and

&nbsp;	upper -alpha...

dodanie do klasy :"listoredred list stylowanie==>

&nbsp;list - style-type: decimal - lading - zero

&nbsp;lub uper roman



zanaczniki dla liczb nieuporządkowanych

disc, circle

square	

<string> własny łańcuch znaków, nawet emoji --> nie działa na safari i IE

.ordered list{

line-style-type: upper-roman;

unoderedlist{ 

list-style-type:square

} może by cokolwiek np. może być emeotka

kolor znacznika taki sam jak kolor czcionki elementu.

możemy zmienić listę uporzątkowaną w nie uporzątkowana.ale po co

list-style-position: inside możemy umieścić znacznik wewnątrz elementu listy.

list-style-image:własny obrazek jako znacznk, bez kontroli pozycji i rozmiaru.

dlatego rzadko używane.

list-style-square inside =>ustawia=> list -style-type, list styl-pstion, lis style image.



stylowanie-linków

stylowaliśmy ujuż tabele i listy.

linki są podświetlone.zmienia się kursor

jeśli to mogę chodzić po elementach

ja najadę też coś się zmienia.



możemy zmienić kolor

.link{color:none;

text-dcoration: none

}

pseuodo klasa

zwykle nie odwiedzamy linów już odwiedzonych.

.link:visited{color: darkred;

}



pseudo klasa .link dla linków jeszcze nie odwiedzonych.--rzadko urzywana

warto zostawić outline przy przejściu  do lika za pomocą kawiatury

.link:focus{outline: 2 px solid currentColor;}



waro zmienić kolor przy najechaniu łyżką, 

.link:hover  color :red borrder-bottom: 1 px solid; outline:none:}

po ajechaniu i prztrzymaniu

stan .link:active{

color:bown

}



kolejne style nadpisują poprzednie:

:link

:visited

:Focus

:hover

:active



linki mają się wyróżniać i być wystarczająco duże.==pamiętasz o smartfonach, innykoor podczas działania

mogą wyglądać jak przyciski. padding

wszystkie stany wyglądają dobrze.



moduł3

podejmowanie decyzji czyli instrukcje warunkowe.

podejmumiemy wiele d]cyzji w zależności od różnych cynników.jeśli udało się pobrać dane the is true

if...else

(warunek){zrób coś jeśli jest spełniony()}

else

zrób coś innego

console.log

02:10

zamiana tekstu

if (button.innerText === "Zamkinij") { button.innerText= "otwórz"}

if (continer.classList.contains("dark"))

{console.log"ok"}



let number one

and let number two

if(number one <nuber two) then{onsole.log)



defer

<div class="dark"><div>

let conteiner = doument.querySelector(".container");

if(container.classlist.contains("dark"){onole.log()}

else{coś}  



dodajemy

<button class"button">włącz</button>

let button = document.querySelector(".buton")

console. log(buton")

4:52

if(buton.innerText==="włąćz){buton.innertext = "wyłąćz"}



ma działacc po kliknęciu



buton.addEVentListener("click", () =>{

if (buton.innerText==="włącz")

{buton.innerTEXT= "wyłąćz"}



else nie jest obowiązkwy.klamry nie są wymaane ale ich używaj

można dodać else if

else -jest ostatnią deską warunku

warunki porównywania. 

=== !== 

\&\& and -wszystkie warunki muszą bć spenione

II or - wystarczy,jeden spełniony warunek. 

!0 nie negacja

może jeśli ktoś jest adminem lub operatorem to coś się wydarzy.

switch=()case break

default jeśli nie pasuje do żadngo

swtch używamy kiedy mamy wiele wartości, kiedy mamy kilka opcji w zależności od wartości jednego wyrażenia.



Krótki zapis:

warunek ? jeślispełniony() : jeślinie spełniony()



moduł 3 JS- if/else vs ternary vs swith

00:00

if w przęłączniu motywu.

<button class="button"> włącz ciemny motyw<?button>

w pliku js==>

let buton = document.querySelector(".buton")

let body = document.querySelector(".body") dodając do body tą klasę.

dalej 1:14

buton.addEventListener("click, () =>{} body.cla sList.toogel("dark");

dodajemy klasę do pliku css >>.dark{kolor:pomarańcz}

02:45

z powodu kolejenosci i selekcji dodajemy defer do js <script> 

<buton class"button">Włącz <span class="theName"></span>motyw </button>



03:35

let theName = document.querySelector(".themeName";

if(body.classList.Contais("dark"{ themeName.innerText="jasny"

else

themeName.innerText="ciemny"}



lub

themeName.innerText=body.classList.Contais("dark"? "jasny":"ciemny"



6:00

<p>dzień tygodnia: <span class="day"> <strong>poniedziałek</strong></span></p>

<p> mam jeszcze <strong class="howmuch" ></strong>czasu na zrobienie pracy domowej</p>

7:10

let day =document.querySelector(".day").innerText;

let howMuch= document.quary selector("howmuch").



if (day==="poniedziałek || lub"){

howMuch.innertext="dużo" 

}

else if(day==="środa"||"czwartek"

&nbsp;	howmuch.innerText="trochę"

else 

&nbsp;	howmuch.innerText="mało"



9:10

możńa to zrobić także

howmuch.inner text: (day === "poniedziałek"||day==="wtorek 

? "dużo":

{

day === "środa"||day==="czwartek" 

?"trochę"

:"mało"

&nbsp;)}

09:58

&nbsp;inaczej można

switch(day){

case "poniedziałek;

case "wtorek"

howMuch.innertext="dużo"

break 

…

degault: ...

11:18

13:10 if eelse if console log else {howmuch.remove(\_)}



film

if/else vs ternary vs switch (14mi)



w body<class:"body">

<buton class= "buton"> włącz ciemny motyw</button>



w .js

let button= document.quarySelector(".buton"):

let body= document.quarySelector(".body"):



buton.claslist.addeventisterner(click)>>

&nbsp;body  class list.add("dark"):



style css.

.body{}

.dark{}

}



moduł 03 - badamy i modyfikujem css w przeglądarce

00:00

chrome deaftools



moduł III

prace domowe z upredznie 

<section> używamy do kilku sekcji

jakiś paddin żeby tekst nie dotykał ekranu.

responsywność

unikaj height na sztywno

wyśrodkowanie elelemtu a wyśrodkowanie zwartość elementu to dwie inne rzeczy.

by wyśrodkowąć element nie dodawaj margin

nie konbinuj z alternative box model

dodaj responsywnośc do tabeli np.overflow

nie używaj hr dy zrobić poziomą linnie.Linie robi się w css

wzgledna wysokość linii 1.5 puste

html odzwiercefdla struktore dokuemntu. to czym jest nasza treść

kiedy coś chcemy zmieniać później gdy nam się już nie podoba albo coś chcemy mieć pod konsolą to CSS



moduł IV

prace domowe z poprzedniego tygodnia.

max-widht

padding

margin: 0 auto

box sizing 02:39

over flow auto- tabela się nie rozjeżża

widht==>> 100%

table cel pading tex-align border

sekcje 07:00

nawigacja po sekcjach : lista nieupożądkowana +linki w elementach tej listy.

ukryj kułeczko..dodaj ładne stule do wszystkich stanó linku 

lista list-style:none

18:53 -JS.zmiana przełączani tła



moduł IV komentarze w kodzie (9 min)

są nie widoczne , przeglądarka je nie użwa

<!-- tu piszę -->

ctrl+/ slash



w css ==> /\* tu komentarz  \*/

może wyłączać kod



w js. // komentarze



pomocne dla siebie i dla innych. do notatki sugestii na przyszłość.

jak wyglądna gdy, coś wyłączymy

nie przesadzaj s kometarzami pisz prostszy kod.



drugi film. normalize.css czyli ujednolicony domyślnie style przeglądarek

00:00

nadżedne podżedne wyeliminują się

normalize 8.7 domyślna wtyczka ujednolica domyślne stylów

dodaje spójność , poprawia różne bugi

niewluje różnice, nie resetuje niczego.



jak użyć? np. skopiować plik 

03:42

dodajemy plik do css. normalize.css 

na głównej w stel css <head> normalize c/normalize

najlepiej dodać na świeżą stronę.

04:18

normalize css cdn - w goglach

darmowa platforma.

wybieramy wersję najświerszą. zimifikowaną -->tylko portzevbe rzeczy

wklejam to co dostałem ze strony.

i usuwam reczne i plik normalize.css z mechanicznej opcji



konwekcja BEM

00:00

block element modifier

jak nazywać klasy?

np. dodajemy noirmalize do <head> + .htlm {box -sizing. border -box}

before , after

mamy artytkuł do którego tworzymy css np. max-widht: 600px, padding, box shadow.wyśrodkowanie margin 0 auto}

1:13

2:00

szukam nagłóka i dodajeę mu klasę. class= "article\_header"

elementy zbliżające się do wewnątrzx article\_headre 

wszystkie <P> zamieniam na <p? z klasą

camelkeys- a\_\_b

kebap keys.

04:29

chcemy, aby któyś z akapitó się różńił. 

dodajemy kolejną klasę="modyfikator" \_\_B--hightlighted

klasa współną

05:43

A CO Zzrobić ,żęby drugi artykuł był ciemmny> … article  article--dark

teraz chcemy trzonkę zmienić.

niemmusimy dodawać modyfikatorów do wszystkich elementó wewnątrz. 

7:17

.artice--dark .article\_\_paragraff{}  wszytkie w dark mają stykle z article\_paragraf

.block\_\_element--modifier

zawsze stylujey po klasach ,nie po zncxnikach tp.

bem mamy bloki np. możemy przenieść na inną stronę. są niezależne 

blok - to najwyższy poziom

wewnątrz bloku elementy nie są samodzielne...mają zastosowanie w kontekście bloku, do którego należą

jak dodajem kolejną klase to np. np. <article\_stron> to srócenie od strong

10:17

bloki mogą mieć modyfikatory 

nazwy rodzynki. nie mówią o tym jak jest css.

cechy bem

pomaga tworzyć komponenty wielokrtengo użytku, bloki są samodzielne i nie podlegają sobie nawzajem.

łatwość implementacji -np. jak naywa  klasy

jeśli aplikacja będzie duża to nic złego się nie wydarzy.

jest pozamiatane jest czysto.

proste reguły

mniej kodu .. robimy alplikację , bardziej znormalizowaną.

łatwiejsze wdrożenie nowych osób.



BEM - ćwiczenie (8 min)

00:00

02:04

<nav>lista </nnav> dodajemy  proste style. np. "navigation\_\_link"

zmieniamy w style c.ss

.navigation {stylówa}

dodajemy do nawigacji , do samej listy{list style none}

pading\_left, margines

.nawigation\_\_link{

text decoration none

}

dodajemy do ktregos punktu modyfikator. --buy i w css dodajemy klasę w css

navigation--dark.navigation\_link{}

specivy kopiujemy klasę 2x

navigation\_\_navigation



JAK działa internet i przeglądarka (16 min)

00:00 

TCP/IP

URL - adres internetowy 

https

tylko serwer może odszyfrować

parametry URL

\#

DNS tłumaczy nawzwę domeny z ip

serwery dbają o ip.

requset 



staus kode -200 zielony.. odpowiedz 201 udało się stworzyć

204 -brak treści

301 - przeniesiony na stałe.

302- przeniesiony tymczasowo

304- odpowiedz nie zmieniona

401 -brak urzytelniania

404 nie naleziono

od 5 to błędy po stronie serwera.

500 nie spodziewany błąd.

503 -przeciążenie



HTML - formularze (35 min)

00:00

<form></form> kontroler dla formularza

<labeL>  imie nawsko <input name ="name">

</label>

pisywanie pola

<button> coś <button>



może mieć także section headerds

&nbsp;

<form action ="/strona docelowa" method= "post"></form>  domyślnid get przy 0

definiuje komentarz , jest kontenerem dla formularza.

gdy nie jest cos form to nie jest w forularzu

nie zagnieżdżamy form w form

actio - tam zostaje wysłany formularz

03:31

<input name="myname"> domyślnie iput tekstowy 

nie przyjmnie nam znaku nowe linii.

przyjmuje  tylko zwykły niesformatowany tekst

atrybut value - domyśna wartość.np. w inpout + vaule ="pam oamroski"

04:55 atrybyuty

name readonly - pole tylko do odczytu a le  ostanie wysłne.

disabled- pole wyłączone ..nie wysyła nic

placeholder-tekst  napis w tle

autofocus- po załadowaniu strony idzie do niego

<label> opisuje pole inf. dla użytkownika, opakowywuje je

07:00

pole może być label a możemy zrobić label i pole zrobić gdzieś indziej. 

ale, dodajemy do input id=""

a do label  dodać for:"" ;łączy to for z id

klikniecie w label jest jak kliknięcie w pole.

08:56

omówienie przycisków

<button>Wyślij</buton>

lub

<input type="submit" value="Wyślij.

przyciski od type mają różne funkcje.

type=submit - Wysyła formularz

type = reset czyści formularz może być w osobnym przycisku

type= buttom zwykły przycisk, brak domyślnej akcji

&nbsp;buuto jest bardziej elastyczny.

&nbsp;<textarea name = "description"> </rextarea>-\\

pole na wiele linii tekstu

&nbsp;  pomiędzy znacznikami -piszemy domyślny tekst

znacznik dwukierókowy 

białe znaki mają znaczenie.np.tab

domyślnie można rozmiar zmienic'

cols- szerokość w kolumnach

rows - liczba wierszy.

css też można użyć w zamian.

13:32

&nbsp; <filedset>

<lgend>tekst</legend>

<p> <label> tesky <input name= "firstName"></label>...<p></p>

13:40 przykład

&nbsp;legend - pierwsze dziecko

dostęóność. 0-czytnik ekranu będzie czytałą legendy przed nazą pola.

14:08

checbox zazacznij

<label>

<input type "checkbx" name="judtin">cos napisae</label>

można zrobi lisę nieuporządkowaną

type = są różne

15:38

tak/nie

atrybut checked - domyśinie zaznaczoe

wysyłą tylko zaznaczone

&nbsp;jęśłi nie podamy "value" to wyśle "on" domyślnie"

16:07

podane to wysyłą to co jest pod value.

radio buton wybór jednego z wielu

&nbsp;jeśli tak samo się nazywa to łączy

pod tą samą nazwą są grupą, przy różnycyh value="nadach"

&nbsp;tylko jeden z g  rupy może być zaznaczona

pusta wartoś się nie wysyłą

16:35 input type radio -jeden z wielu

&nbsp;type ="radio"

pod tą samą nazwą są grupą.

nie da się odznaczyć pola.

<selekt name="lista"> 

<option vlue:"dsd">baa</option>

</select>

można selec za pomocąklawiatury można pracować

select= rozwijane menu

wysyła value

selected- dmoyślnie zazanczona

19:37 selected dodajemy do opition nie value

size- lista widocznych opcji

multiple - wielokrotny wybór.

różnie zaznaczane gdy kilka.

multiple np size 4

załączanie pików do inputa dodajeme type="file"

&nbsp;multiple- lub kilka plików

email- adres mail 

24:00

password type

połączane szyfrowanie

input number- przewijanie numerycznie,

atrybut step -kroki 5 i 10

28:00

input type max-min-range plus opcje

numer telefonu bez walidacji

input typ="URL" adres twojej strony int.

31:00

name: list ==> cardBran/s

input list w input ++ <datalist id"='Carbrands"





ukryty input- może być wysyłane

input color

input dateczas 

&nbsp;wielo input - data i czas

34:00

input 



&nbsp;

MOduł 4

Walidacja i wysłanie formularza (27 min)

00:00

zanim zwalidowany musi poprawnie być zrobiony

&nbsp;requirded - wymagany

&nbsp;   minlenght, - ile znaków

maxlenght -blokuje za długą wartość

min,max - dla dat czasów i polcyfrowych

type; number, mail

pattern- wyrażenie regularne ideualne do walidacji.Jest to wzór -kombinacja znaków.

np. pattern np. html. żda wymaganego łańcuch danych html.

5:45	kod pocztowy. w wymaganym formacie.

06:64 https://regexr.com/ strona do wyrażeń

pattern nie zastępuj required

08:17 reuired

walidacja przed wysłaniem formularza

pomóżmy klientowi

11:11 Wysałnie formularzy

formularz pomaga po prostu w komlikacji wartości , które mają być wysłane.

wysłane do serwera klucz=wartość 

&nbsp;domyślnie jest wysyłąme pod adres strony na któej, jesteśmy

&nbsp;form action- zmieniamy url

https://postman-echo.com/

13:52- opcja dla deweloperów. preview

17:08 GET. zwóćmi coś. Niż nie zapisuj nic nie wyylam do zapomnienia

&nbsp;	ciałó żadania puse tylko - ? tylko nagłówki i url

18:49 - POST - do form dopisuje method

adres nadawcy

Dane zostaną wysłane w ciele żądania. Body. 

Narzędzie do deweloperó:==> nagówki i całe ciało

ogónie chodzi o to informacja jest zapisywana w innej formie. GET czy POST

&nbsp;POST jest pomocne kiedy chcemy np. poprosić serwer o zapisanie czegoś w bazie danych.

WYsyłamy w ciele.

WYsłąać maila, 

Przeglądarka dodaje nagłówki dot. treśći

podaje długość ciała.

21:47 po stronie serwera.

każdy backendowy język programowania swój mechaniznm do odbioru danych z formularza.

Serwer może wtedy: zwócić dane, dodać nowe dane do bazy ndanych np..zaktualizować dane.

https zasze używaj z powodu bezpieczeństwa +URL action

GET nie hasło użyj POST.

serwer też sprawdza dane. nie ufa użytkownikowi. Tylko te dane któcyh potrzebujesz.

Wysyłanie plików- binarne

24:00

dodajemy enctype="multipart/fom-data" jak artyrybut formmularza

methd POST

serwery mogą mieć limit.



moduł -4 - CSS – stylowanie formularzy (33 min) \*\*\*

00:00

iput-dmyślnie ma inną trzcionkę.

inherit- dziedziczenie

bedauflaut

03:40

nie wszystko idzie kotroować

label-równa szerokość

span>Imie/<apan -

dodajemy css plik

.form\_labeText{width:150 px; display:online-block;liniowy na zewnątrz ale bloowy w środku

margin-right: 5px

05:10

odwołanie do css



<input> dodaję klasę do pul

<vorm field>

border,paddind,widht, border radius



apperance buuton

&nbsp;form\_button- stylizacja

.foorm\_buton:hover}



<fieldset>form \_fielsed.

11:36requaired

pola wymagane \*

form\_fiel:equaired

&nbsp;form\_fiel:invalid -niepoprawnie wypełnione

form\_fiel:out-off-range



disabled - ++element wyłączony.

read-only

.form:read-only

value-tekst , którego nie mogę edytpować



:read-only{}

form\_field--select. form\_field - select  2x



selector specifiti

input type color.

--color



input type:range 0-max                                 narzędzia dka deweloped

kolor tekstu przesyłki pliku nie do zmiany.

text area- "słowa o tobie" /TEXY AREA

zmiana rozmiaru w pionie. form\_field--textarea

resize : vertical, min-lenght.100px

30:50

flatpickr

ładuje do head

przed </body js.date

flatpickr(".jss"{}



moduł liczby 04.09. JS – liczby (27 min)

00:00

praca z liczbami,

=== jakiego typu jest np. dana zmienna

let mynuber wszystkie rodzaje liczb

type of

0.1 + 0.2!== false



infinity -ifinity

dzielenie przez 0 = nieskończoność

Nan liczba ,która nie jest liczbą. type of

łąncuch znakó przez liczbe ==NaN

nie ma np. 5NaN

nan nie jest róny NaN

number.isNaN

07:30 podstawowa , matematyka

&nbsp;zaokrąglanie

&nbsp;	math.round(liczba) -do najbliższej liczby całkowitej

&nbsp;	math.ceil - w górę

&nbsp;	math.floor- w dół

.toFixed(2) zwaca łąnćuh c znaków

math.sqrt()- pierwiastek. ujema liczba undefinied

największa i najmniejsza wartość= math.min math.max

math.random()liczba pseudo losowa od 0 do 1

math.floor \*(math.random()\*6) 5

math.floor \*(math.random()\*6) +1 większy zakres=6

12:44 konertowanie na liczby

konkatonacja 

łazenie łąncuch liczb

number() tekst na liczbę

\+ przed łańcuchem znaków pojedynczy operator

"5" jako łacuch ++ jako liczba

działania konwetują do liczby 

inne NaN

10+20 =1020

15:55 

parselnt("5") //5

paresint("5 6") // 5

paresint("5 jabłka") // 5

parseFloat()liczby z liczbami po pzecinku.

parseint - do liczba całkowitych

operatory atytmetyczne

+-\*/ %modulo (reszta z dzielenia) np. czy liczba jest parzysta

\*\*-potęgowanie

math.pow(3,4)=81

&nbsp;mnożenie i dzielenie jest ważńiejesze niż dodawanie i odejmowanie.

nawias zmienia kolejność działań.

od lewej do prawej



let zmienna =5 zmienna ++ zalezy po której lewej czy prawejj jest ++ lub --

++ -- dodać lub odjąć 1. 

&nbsp;operatory przypisania

zmienna = +=5, \*=5 =



operatory do warunków

=== - true albo false. "" ==="". typ zmiennej musi być taki sam.

!== nie jest identyczny



Moduł 4 04.10. JS – stringi (21 min)

00:00

string= łanuch

http - daje strukturę, css-stylowanie, js maniupulowanie

Łąńcuch - "" ``bez mieszania ich.

spójność najważniejsza

wyeskejpować  \\

\\n - nowa linia w środku

\\t - tabulator

łamanie wiersza w kodzie-  \\ lub +

łączenie stringów:np. za pomocą + lub

let message = ""+name+""

04:14

konwertowanie na tekst

let myNumber = 5; myNumber.toString (); ="5"

&nbsp; myNumber + "";  "5" dodajemy pustyłącuch danych.

toString()

template literals/template strings

&nbsp;  	 console.log(`Mam na ime ${gabana} i mam ${laT}; zamienia w tekst

name.lenght - długość łańcucha

metody obektu String"

&nbsp;	let string = "łańcuch";

&nbsp;	 sting.charAt(2) ==3 znak :ń

&nbsp;	string .charAt(string.lenght -1 ==ostatni znak h

&nbsp;	string\[2] -trzeci znak ń



10:56

.. .includes("ach")- czy łącuch zawiera fragment

starstWith - czy łancuch zaczyna się od...

endWith- czy nasz łancuch kończy się na...

11:18

indexOf -na której pozycji

lastIndexof('') = -1 



Wycąganie fregmentu tekstu

s".slice(2,5) od do-fragment od tego indexu

-2 -dwa znaki od końca



substring(2,5) bez znakó od końca

&nbsp; 

czyszczenie łańcuchA z biąłych znaków po obustronach

qwd?xasx\\ws" - let tekst == 

tekst.trim - czysty tekst



zmiana wielkości liter "youcode".loLowerCase -do małych

toUpperCase() zamienia łańcuch na duże



zamiana fragmentu tekstu na inny..."www".replace/all("w","a")

all- do wszytskich bez tylko pierwsze wystąpienie.

rozróżnia np. wielkośc znaków

/you/i - nie rozróżna między małymi a wielkimi literami.

nie czuły na wielkość znaków. -ig global



Porównywanie stringów

&nbsp;	alfabetycznie 

"saas".localeCompare("dad");-1'1'0 ==takie same.



Zwielokrotnienie Stringa

"WW".repeat(3) => WW



Moduł 4   - 04.11. Formularze w JS (20 min)

00:00

Formularz

Pole formularza--value,chcecked dla radio i chcecdbox

01:26 - jaka jet wartość w polach za pomocą JS.

np. Input wsadzam  class=JS-css-height 

let heightElelemt = docuent.querySelector(css-haight")

&nbsp;height element.value

w mormularzy w deweloperzepoda velue na konsoli.

value- to piewsz rejestraja

04:50

<input w filedset ==> <input

dwa atrybuty ten sam name >><<class:JS-css-height 2

&nbsp;

let radioelement1 = document.querySelelctor(js 1)

&nbsp;zwarca pole

radioelement.checked==>false or true

&nbsp;value lub input radio sprawdza zaznaczone.

06:43

Metody pół

&nbsp;	click(), focus(), blur()

&nbsp; 	let heightElement = document.querySelector(js-hight)

console.log (height.Element);

np. heghtelement.focus();



do przycisku dodaję klasę  js-submit

document.queryselector(js-subit)

document.queryselector(js-subit).click(); 

wysałał się formllarz



09:18

Zdarznie input

teminal gdy tylko coś się zmieni.

&nbsp;heighElement.addEventistene("input" ,() =>{

&nbsp;consle.log- zmiana wartości pola.}



heighElement.addEventistene("input" ,() =>{`

 consle.log- zmiana wartości pola.${heightElement.value"`}

zieniła się wartość tego pol



Przydatne emetody:

submit()

reset()

10:00

dodaję klase

document.querySelector (js-form)

form clss= js-form...</form>

document.querySelector (js-form).submit();



Przycisk <reset>   

&nbsp;type:"reset" class: js-rest

let ormEleent=docuent.qeryelekr(js-form)

&nbsp; 

heighElement.addEventistene("reset) =>{`

 consle.log- formuarz doznał rseta





heighElement.addEventistene("submit =>{

 consle.log- formuarz został wyłany



dodajemy

&nbsp;	event.peventDefault();

&nbsp;		"coś się ma wydarzyć.



blokujemy tym domyślne zdzaiałanie formularza.

let heightElemet =document.querySelector(j-height)

let weght qr weight

letformeement qr form

let BMI qr BMI



heighElement.addEventistene("submit (event)==>

event.peventDefault(); blokujemy domyślne działania



Twoje BMI wynosi

html => class= js-bmi



let heightElemet =document.querySelector(j-height)

et weght qr weight

letformeement qr form

let BMI qr BMI



heighElement.addEventistene("submit (event)==>

event.peventDefault(); blokujemy domyślne działania



16:00

let hight = eightElement.value;

&nbsp;weigt

&nbsp;console.log (hight, weigt)



let bmi = weght\*hight

requeird



console.log (bmi)



&nbsp;WPisywanie wartość do drzwa html.

18:56

BMIElement.innerText= bmi.toFixed(); w klasie <strong>

class - jsBMI







MOduł 4 Zdarzenia input i submit (3 min)

00:00

submit-po klinkęciu działą

dziłą cały czas-inputt zamiast submit

wartośći mieniają sę w locie na bierząco.



mduł 4 Prace domowe

00:00

dodaj normalize

bloki w osobnych plikach z kompcepcją BEM

stwórz kalkulator=selet radrio

&nbsp;		

moduł 4

Wskazówki do prac domowych (7 min)

00:00

BEM -button--special

to co chcemy nadpisąć

element nie może mieć

tylko modifikatora.

nierobimy globalnych modifikatorów

js przedrostki

inner text => "www"+www,  `www${333}`



moduł 5 
Prace domowe z poprzedniego tygodnia (23 min)
00:00


Normalize przed innymi stylami
Konwekcja BEM
<main><section>jakiś obrazek
<section><paragraph> + tablekontener
css
.{fsection} style dla tabeli
overflow-x: auto; przewijanie tabeli w poziomie
CSS i BEM to tyle.
gdy łapiemy bodhtml = document.documentElement
document.body
klasa elementu + klasa modivikatora np. --header
camelCase, kebap case;
.red --bład
tworzymy bloki gloabne a nie identyfikatory
id- uzywamy do skakania. 
Stylować łątwo po klasach. np.H2 na H3 mogą działa
js- potrzebują też klasy 

Tworzenie kalkulatora.
Przelicznik walut.
14:40

JS:
dane na sztywno.
4 uchwyty do elemntów
form, amount,currency, resuly +document query selelctor

Wpisuje 3 zmienne na sztywno

formElement.addEventListener (submit)
{ event.preventDeuflaut} nie wyśłe się, strona się nie przeładuję

let aomut =amoutElement.value
let currency = currencyElement.value

switch w zależnośic od currency

resultElement.innerHTML = `${amount.TOFIXED}       `
     
     nie potrzebne preventdefaul
      potrzebne label.
        `
teplate strings

MOduł 5 -
Git, GitHub, GitHub Pages – pierwsze spotkanie (31 min)
00:00

GIT - pozwala wrócić do różnych etapó przeszłośc
install GIT
GIT bash
komenda git
git --version
git config --global user.name "" 
git config --global user.email "" 
git init
terminal>> new>> powersheel>>git init
 folder związany zgit zostauł utworzony
 git add. - dodanie komita
 git comit -m "initial commit'
 3 drzewa -robocze zmiany w plikach ,changes - zmaiany do zakomitiwania, Head-aktualny komit
 changes-pokazuje graficznie
 + stated changes + message najlepiej po ang

terminal            "tab"
git status
git add.\index.html                 
git comit -m "ddfsd"
 
 ptaszek -komituje

 git status 
 git add style.css script.js

 GIt lens - rozszeżenie
  co i jakie dane
lista komitów
reset  t0 komit/
switch to komit
halt reset

lista komitó terminalu
git log
 git log --pretty=oneline
git reset --hard

github.com 
zdalne repezytorium4
...
quick setup
wklejam instalacje
Póżniej git push -wypycham zmiany

git pull -pobrac od innego.

GITHub Pages
deployment 
GIT HUB pages w seting.source ==master


moduł 5 
05.03. Markdown i README.md (12 min)
00:00
git hub add README
    plik opisujący reporezytorium 
    Markdown - język znaczników
    pozwala doać formatowanie do prostych dok.tekstowych
składania:
#nagłówek ##inna klasa H1 do H...
**wytłuszczeie**
*kursywa*
listy uporzątkowane 
    1.ele listy 
    2. qwq
    -element
    -element
    
    linki. 
    [google](adres)
    obrazki
    ![alternatywny teks](żródło)

możemy wstawić kod
  krótki fragment `kodu`
  ```javascript 
    console.log```

dellinger -markdown - jak pisać

DEMO - w Readme
nawet można dodać komit

terminal - git pull
pobierma readme z githuba

Moduł 5 
OpenGraph i ikonka strony (9 min)
00:00
tutył typ obrazek i url...
Poengrahp może być nawet film
jest to protokuł 
www.canva.com - prjekty graficzne
02:40
w index html dodaje mettag
np. 
<meta property="og:image" content="https://ia.media-imdb.com/images/rock.jpg" />
facebook for developers pamięta foto, mowi o stronie

ikonka strony
<link rel="icon" href="icon.png">
komit


moduł 5 ...
05.05. CSS – obraz w tle (19 min)
00:00
obraz w tle

.element {
background-image: url("../images/landscape.jpg");
resize:both
overflow: auto dynaiczny rozmiar lelementu
background:size  repeat, no repeat ;
}
mały braz na tle pudła
space - tyle ilę się zmieści
round - bez prestrzenie, obraz się skaluje.
repat-wartość domyśłna

różne  wartości wpoziomie i w pionie: np.norepeat, repat
space round 
repeat-x ,repeat y tylko w jednym z kierunkó się wyświetla

background-position
center- na środku obraz
top | right |bottom|left- do której krawędzie ma być ustalony obraz
można mieszać np top, right mogą być nawet pixele i procenty

kilka obrazkó
url.drugi obraxzek
widoczne dwa jęsli tylko się nie chowają jeden za drugi

background-size  cover dopasowanie bez straty proporcji
100px auto 100px
contain- wypełnia zachoują puste przestrzenie
bacgoiund repeat ; no repeat

backgoud-atachmetnt - przewijanie tła przy zmianie przzewijania
.elemen hight 100px

backgound size -cover

backgoud-atachmetnt: fixed,
 local -tło przyklejone do treści
fixed - tło sięnie rusza wzglęem treśći
scroll-przyklejone do elememtu , nie do tresci

background ma 8 właściwości.

.element {
background: center / contain no-repeat url("../images/landscape.jpg") #ccc;
}

moduł 5
 CSS – wyrównanie tekstu, dekoracje, wcięcia, wielkość liter, object-fit, object-position, calc (12 min)
 00:00

 text-align - wyrównuje tresc wewnątrz elmentów blokowych o komórek tabelii

 w środku obrazek też bęcie wyrównany

 tex-align np center , margin auto, 

 text-indent wcięcie tekstu np. 50px tabulacja, %
 text-decoration określa wygląd lini dekoracyjnych tekstu
text-decortion: underline dotted red <spa class="dcoration>
text -decoration-line : 
underline
overline
line-through
klilk po spacju
none

text decoration : color
text decoration style: waywy, itp.
text-transform : zmiany liter na małe i duże

ippercase- wszytskie litery wielkie
lowercase - wszytskie litery małe
capitalize - pierwsza litera w kązdym słowie wielka.

object-fit- jak skalować obrazek aby się wpasował w kontener
cover - wypełnij kontener
contain - mieści się w kontenerze, zostawia pustą przestrzeń po bokach.
fill- wypełnia kotener , bez proporcji
<image  wymiary klas>
np. object fit cover

object-postiton np.left
 położenie np. w kontenerze, domyślnie 50% 50%
format taki sam jak przy backqround-position

calc- obliczeni w css.
width: calc(100%- 80px);
dziłąniamuszą być ze spacją.

MODUŁ 5 
05.07. CSS – Flex (31 min)
00:00

pozostało 28h

elementy w wierszach lub kolumnach
genialny, upracza pracę, elastyczny.

dodajemy do kontenera:
.container {display: flex, }
.flex {border, widht}
+diplay flex kontener staie się flexem\\
pozostałe flex-items. eleastyczny layout
zajmuje tylke miejsca ile musi.

flex-direction
  main i cross

   row,row-reverse, column, colum-reverse
flex diretion: column

margin colapsin nie zachodzi. przy display flex

flex ukłąda się w pionie lub poziomie

.flex{flex-directon: column}

flex-basis

usuwamy glex diretion
to kolumny z tekstem rozciągają się w pionie

flex-basis: 100px, 33%=-3 elementy -margiesy. Pilnuje żeby się zmisciło
wysokość lub szerokość.

bez flex-basiss - stanadtowe robi rozciąganie w aby sie zmieśćiała cała treć

szerokość i wysokość - ignorowane

.element{
flex-grow 1 - zaiera całaą pozostającą przestrzeń
}
 ile miesjca ma być przynależsne elementowi.

restza to flex-basics
bez lement jest szreszy -tyle ile tekstu
08:50
flex-basis -200px -bazowy rozmiar, romiar elementu zalężny od treść

13:10
lex-shrink 0
ostatni sie nie kurczy -trzyma się 200

gdyby każdy elelment miał lex-shrink 0, to by wyszły poza kontener bez elastyczoci

określa jak element może się skurczyć

skró flex
flex-grow, flex-shrink, flex-basis
    flex: 0 1 auto,initial

    1,1,auto = auto- wypełniły dostępna przestrzen. gdy dużó  tekstu ,to wszytskie się dopiszą.
    0,1 auto -poszezają i  kurczą be wstawaniam
   auto-romziar w zależności od treści,
   0,0 auto -none. rozmiar w zalężnośći od treći ni nie zwezaja ani nir
ani wypełniania przestrzeni

1 0 0 - każdy ma idetyczną szerokość
0 0 100px - sztywno

align-items - wyrównianie elementów w osi prostiopałej
sterch - rozciągnięte

flex-start, flex-end, - wyrównane dodolóu\wyrónanie do góry.

align-self - pozwala ustawić wyrównanie posczególnym elementom
takie same wartośći jak align-items

pusta przstrzeń - jak rozmieszczona
justify-content - wyrownuje elementy w głónej osi
start, end icenter +
space-between, space-around, space-evenly
  
domyślne zachowanie
wyśrodkowane, flex -end, flexstart 
space aroud- tyle samo miejscsa wokół trzech elementów
space bettwe - przerwa między kolumnami do środka , nie uwzglednia przestrzeni przy sciankach.

flex-start - domyśna wartość
order- zmiana kolejność elementó , domyśnie 0


orde 100 - pojawi się na końcu
order -1 = ostatni jako pierwszy
order 100- pierwszy na końcu

od najmnieszej do nawjeiezego order

flex-wrap - określa czy elmenty mogą przechodzić do kolejnej lini
wrap- do noewj lini, wystające, w jakim kierunku
wprap-reverse - odwrotny kierunek
nowrap- domyślnie- dużó w jednej lniki

flex-basis 20% flex wrap-wrap  , niektóre przejdą do kolejnej lini.

jeden elemet 30% - pudło będze szersze
justify - content: space bettewn

align -content -określa rozmieszczenie pustej prestrzeni w osi prostopałejm, jeśłi jest wiele lini
flex end -space around- strech,center

align items - jak ustawiąja sie w liniach end start 
align conten- w pionie, strech
 wrap-revers

 flex-flow column wrap revers wrap
 direction wprap w jednym
 revers

https://codepen.io/osublake/pen/dMLQJr
https://drafts.csswg.org/css-flexbox-1

Moduł 5.
JS – boolean, null, undefined (14 min)
00:00
number , string łancuchy i znaki
boolean - tak/nie przełącznik
null-brak wartosci
undefindet- brak watosci

let zminna true -boolean
 
 if (5) - prawda
 o zamienia się na false
  falsy

 konwertoiwanie na boolean
 
 !!wartość
 boolean(wartosc)

 09:11

 null -jedna wartość
 nie ma wartości. używamy kiedy nie ma wartości.

  typeof null=== "object"

  typ undefined
  let zmienna -undenfinde
  wartość niezdefinowana
  if une===undefinde używamy 3 znakó równośći
do zmiennych , któym nie przypisanym jeszce wartości.

MODUŁ 5
JS – wstęp do funkcji (33 min)
00:00
cechy i możliwośći, procedura, podprogram
może wracać wartość
własne funkcje:
np.
function double(number)
  {return number *2}
number-prametr
console.log(double(5))

to była składnia funkcji
można podać ileś parametrów
instrukje wewnątrz klamr.
może nie musi zwrócic wartość

let mynumber =5;
console.log(double(mynumber));

obketai z tablicami prez referencje

let doubled = double (5)
deklarowanie funkc nie wywołuje jej.

odpala kiedy wywołujemy
swywołujemy nawa(argumenty)

atakuje 
sama siebie - rekurencja4

kolejność w tym modelu nie ważna jest kolejność

funkcje strzałkowe
let double = number => number *2;
jest to krutszy zapis

kolejnoś teraz ma znaczenie..musi być nad wywoływaniem.
 gdy jeden argument fukcja strzalkowa nie ma nawiasów
 nie trzeba także return
let double = number => number *2;

06:38 
zasięg zmiennych w funkcji
wwnątrz funkcji mamy dostęp do zminnych zadeklarowanych poza funkcją
poza funckja nie mamy dostępu do zmiencyh zadelklarowanych wenątrz funkcji

let double = number => number {
let zmienna-20 nie widać na zewnątrz

return number
}

zmienna is not defaund

let, const, var
let-zasieg blokowy, nie widoczna na zewnątrz bloku np. blok {}
na samej gurze , zasięg globalny.

robimy nie globalne tylko małe zasięgi na ile można

const - nie można zmienić wartośći.
kiedy się da używamy wpętli itp.

var-zmienna ale zasięg funkcyjny, mało używana, w bloku
var zmiena w{}

funkcja nie mieć nazwy, wtedy jest anonimowa. 
potrzebne w funkcji do funkcji
let double = funkction(number) {return number *2}
anonimowa gdy przed funtion dodamy jakąś nazwę.

jest anonimowa mimo rzypisania do zmiennej.\

let ouble = (number)=> {return number *2}
strzałkowa teźż może być anonimowa.

consloe.log(double(5)); 
10
aa function console.log sciągamy do funkcji welcome
fuction welcome ({
console.log()
})

14:18 zmiany, funkje . 
szukamy gdzie jakiś fragmnet kodu możemy zamieńić na funkcję.
15:00

hBd.addlistener("zdarzenie" ,()=>
{a...b...c


}
funckja anonimowa do wyciągnięcia
możemy ja zadeklarować gdzieś indziej

hBd.addlistener("zdarzenie" funkcja 2):;
{a...b...c
}

przed wywołaniem
fukcja 2(

a...b...c
)

tera używamy funck strzałkowych

let funkcja ()=>{
deklarujemy przed funckję strzałkową
}

używamy od teraz const

cały kod wrzucamy w blok
{


}

funkcje mają dostęp do zmiennych deklarowanych poziom wyżej

const init = () =>{
funcje gówne
welcome();
}


init();

ni działa
trzeba wyciągnąć i dobrze podpiąć wnętrza
funkcje któe nie są potrzebne init();

mamy 3 x funcje 
21:02

wfunkcje w kalkulatorzw walut.
let  na const.

let result.- musi prypisać wpiersw



cnst calkulate result  = (amount,urrency )=>{
switch (currency
case
resul break
case
return amonut/result
cese
return bez brake
}

lest resut =calkulateresult(amount, currency);

optymalizacja

nie wyciągamy na góre nie potrzebnie funkcji

{}

init()

28:09
optymalizacja

update text (amount, currency, result)

30:10
 np. const amount = curency.value

return
po returnei nie m0ożna już nic wykonać

moduł 5 05.10. Prace domowe (4 min)
00:00
dodaj funkcje w js.

Wskazówki do prac domowych (18 min)
00:00
start

po instalacji gita -nowy terminal
 git clony desktop kopijeje na inny komputer
01:25
code
git clone
wklejamy w git basz
./dev

pobrane repozytorium
ls-co mamy w katalogu
too du list -pobrany projekt.

inna metoda git huub desktop
code pen

chase -cza saktualizacji

README piszemy po angielsku
dodaj opis aplikacji, zrzuty ekeranu , używane technologie,
BEM, flexbox, nwy jc- ees6plus.
poprawny angielki

ziana nazwy - widzimy nowy obraz nowy URL dla facebook

text-transform np. uperr case

czytlenś obrazka we tle

jeśli zienna jest tylko w jednej funkcji   - to wklejamy ją tam gdzie jest potrzebna

dług a funckję dzieli na kilka funkcji

funkcj ma realizować jedną rzecz

init() pierwsza func a do wykonanai

zamiast komentrzay nazywamy dobrzę funkcję.

funcke jedn a złożona z dwóch

hidesection z wieloma prametrami

po rerturn nie ma break ani else

14:09
   
iseven
else 4
retun false
nie trzeba pisać
skracac jak mająboolina

const is Even-number =>number %2 ===0

lest kiedy nie możesz użyć const

trzymaj się finkcji strzałkowcyh, któe najpierw musisz ją zadeklarować
muszą być do góry

 nazwy funkcji są czadownikami

nazwy funcji camelasem jak nazwy zmienncyh i sastałych\

Moduł 06 (2h 46min)

Prace domowe z poprzedniego tygodnia (31 min)
00:00

zainstaluj gita
git bash 
git ignore
.vscod
komit plik igonered added

załłóż konto na git hubie

bash
cd : /dev
dir
git clone link z githuba

homepage and github wrzuć na githuba

05:32
dodaj README.md podkręć je
Readme na sekcj www jest opisane jak
BEM, technologie,
aktualno=a dokumentacja..
open graph i ikonka

10 inut się czeka za załoadowanie m github do linków www
? cokolwiek
tło w przeliczniku walut
cover center
dodaj funkcje w JS
funkcje nie zadługie
swój mały świat

const init -początek
15:17
funckje mjaą mieć mały świat
16:05
const init = ( )=> {
}

puste nazwy
 hoisting
 24:03

 nazwy fukcji : czasownikami

 queryselector

 camelCase -zmienie stałe funckje.
małe zasięgi funkcji

nawza to co zawiera

templestrings
29:32
resultElement.innerHTML='${amouy.to ficed(2)}PLN =
 <strong>${result0|}</strong>'

moduł6
CSS – media queries (16 min)
00:00

jak dostosować stronę co do różnych szerokośc ekranu
np. smartfonów, tabletów.

.image {width: 50%;}

@media (max-width: 767px) {
  .image
  width: 100%

}
szerokośc zgłaszają urządzenia

klasa flex
{display: flex:
max-width 600px
border 1 pc solid
}

pamiętaj o linku flex do odpowiedniego poliku css

 .fex_item {
 width: 50%
 text-align: center

 }

zamiana dwie kolmuny na jedną
mediaquer
@media (max-width: 767px)
.
.flex
flex-wrap: wrap;
.flex_item
.flex__basis =100%

}

MOBILE first

w długą stroneę. Od węższych do więszych

.image{
width:100%
}

@medaia (min-width: 767px){
.image {width:
50%;

}

@medaia (min-width: 768px
{ .flex{
 flex-wrap: unset
 
 .flex_item{
 flex-basis: 100%
 }

Onrientation
@media (orientation: landscape) {
.image{

width: 50%;
}

breakpointy np.
768 992 1200

 @media print {
 .whatever {...

 }

media guaris możemy łączyć

OR- przecinek
@media (max-width: 767px), (min-width: 1200px){
 .image{width: 50%;
 }
 }

AND
@media (max-width: 767px), and (min-width: 1200px){
 .image{width: 50%;
 }
 }

Zafnieżdżenie
@media (min-width: 768px)
 { @media (max-width 1199px) {
  .image (width: 50%;}

prostota-dla corz węższych ekranów

nie zawsze mq jets potrzebne 
flex-grown np. jest jakoś eleastyczny

<meta name="viewport" content="width=device-width, initial-scale=1.0">

.flex{
display: flex;
flex-wrap:wrap disabled

}
@media
fleks wrap:wrap

.flex_item{
  flex-bais : 33%

@media(max-width: 767px{
  .flex_item{
    flex-basis 30%
flex-grov 1
  }
}

13:00
copy fla 500
51%flax basis

Moduł 6
CSS – Grid (34 min)
00:00

siatka, tabela, flex

wiersze i koumny jednoczesnie moga byc modyfikowane
.container{
dsiplay:grid
grid-template-colums: 100px 200px 300px

gdy coś się nie mieśći to jest robiony nowy wiersz
robi się

.conatainer__item{
display: flex
align-items: cenetr
justify-contnt: center
psding 20px
}

frd taks

jednostk afr

.container{
display:grid
grid-template-colums; 100px 1fr 2fr
trzecia może mieć stałą szeroosćc
}

repeat
grid-template-columns: repeat(3, 1 fr) moży 1*4

repeat
grid-tempplate-collumns: 100px repeat (2, 1fr 2fr)

repeat (auto-fill, 200px) - kolumny tyle ile sę zmieści

repea,auto fill ,minmax ((200px, 1 fr))-elastyczna liczba kolumn- atrybyty można mieszać

tyle ile można kolumn w wierszy min.200px
pozostała przestrzeń zostanie wykożystana

08:42
gap.
container{
grid-gap 2px 20px - podstępy miezy wierszami i kolumnami
}

grid-row-grap
grid-column-gap

grid-template-rows 100px 100px
własciwoś deklarująca wiersze
i wiersze i kolumny
12:09
grid-template- repeat rows (6 100px 200px)
grid-auto-rows: 100px, 200px na zmianę

grid-auto0rows: minmax(100px,auto)
wyższy żeby zmiejszył tekst

tekst będzie wystwał bez tego.

grida można zagnieżżać 

dispaly:grid a nie flex\
2x div w dive to jak grid w gridzie

18:00

wyrónnie
align-items justify-items
start, end, center
-self wyjątki

align-items: start -elementy będą się układały do góry

jstify-item np. end

.ostatnielememt-last{
  align-self: end;
  justify: end:
}
element jest wyrównany inaczej

18:56
 wyrównanie wszytskich wierszy w pionie lub poziomie

 start, end center strech space-around, space-betwee, space-e

.cotainer{
height 400px
border 1px solid
justivy kontenet- center
}

ułożą sie do środak: center-, 

21:40
zmiana położenia elementu w gridzie

.container{
grid-template-colums: repeat(4, 1fr);

grid-column: start:2 
grid-column_end 4
grod-row: start np. span, -1, 1
grid row-end
}

skróy
grid-area
grid-column: 2 / span 3;
grid-row: 1/ span 3;
grid area; 1/2/span3/span 3

grid-template-areas
oszary ich nazw
 + grid template:aeras
 "left middle middel right
left middle middel right

"headre header header"
"main main aside:
main main aside:
footer footer footer
>>>.grid temaplate area
 . element
 grid-area: footer

moduł 6
Więcej o funkcjach i zmiennych w JS (15 min)
00:00

typeof: "function"

hoistind- funkcja jets dostępna w całej funkcji\
niżej , wyżej

jeśli tworzymy funcję za pomocą słowa fuction lub tworzy zmieną za pomocą słowa var

np. var variable -globalna funckcjakas

widow.variable -jest widiczna

bez bloku wtedy śą doztępne

lest ,const var

var  mogę zadeklarować a pózniej przypisać wartość.

09:32
możemy deklarować zmienne po przecinku

funckja może zawierać prametry domyślne.
constpower=(a,b=1)=>a**b;
np. w pryzpadu nie podania drugiej iczby, będzie inny wyniki

rekurrencja- funkcja może wywołać samą siebie
silni liczby np.
factorial()
const factorial =(number)=>{
if (!number){
return 1;
}
return factorial (number-1)*number;
}

moduł 6
. JS – wstęp do obiektów (13 min)
00:00

const person =(
name:""
surname:""
age:""
ssayHello: function(){
  console.log(` bla bla ${this.name}`);
}
)

 conslo.log(person.name)
 console.log(person["aage"])
 person.sayHello;

 wpisuje person na konsoli
 wypisuje obiekt

 const propertyName ="age";

 this- dane z obiektu

+
getFullName: function(){
return `$(this.name) $(this.surnme)`;
}  

persone getfullname = name i surname czyl tu pisty ciąg

this- w tym przypadku odnosi się do obiektu wewnątrz którego wykonuje się kod.
funkcjie strzałkowe nie mają swojego this

2 obiekty person1 person2 rózniące się przypisaniami
jak będe chciał odwoływać się przez this o jest nie możliwe

obiekt w obiekcie

cost person={
  name:""
  surname:""
  parent:
  {
  name:""
  surname:""
  }

console.log(person.parent.name)
console.LOG (person["parent"["surname"]);

korzystaliśmy już z metod obiektó. np.
document.querySelelctor
Math.min
String.includes
itd.

dwa obiekty
nie mozna porónać.
 11:53

obiekty do gunkcji przekazujemy przez referencje
  obiekt nie jest gdziekolwiek kopiowany

const changePersonName = (person) =>{
person.name = "Szcepan";
}    

const init = ()=>{
const persone={
name
surname
}

const changePersonName = (person)
}

init()
 

MOduł 6
 JS – wstęp do tablic (13 min)
 00:00

cost products = ["jaka", "majoznez"]

Array.isArray (products);

products instanceof Array;

type of - nie robi się
jeśi wlącze to dostanę object

 inna tablica

 const array = [5, "tekst", undefined, {name:"krzysiek"}, [3]];

 tablica w tablicy może być
mają zwykle yyten sam typ

 Dostęp do elementów tablicy

 const products = ["jaka","mleko","chleb"];
 const secondProduct = products[1];
 products[2] = "ser";

products[x]

długość tablicy
nazwaTablicy.length;

konwersja na string i odwrotnie

możemy wybrać separator VV
const productsString = products.join(",");

np. "" , "<>"
const productsString2 = products.toString();

jak zamienić łańcuch na tablicę
const productsString = "jaka, mleko, chcelb";
łańcuch znaków

const products = productsSring.split(",")

nie pomijaj seperatora
bo bedzie tablica z jednym testem po , ;

dodawanie elementó na koniec tablicy
products.push("drożdże, :lion");
zwraca nową długość tablicy

usuwanie ostatniego elementtu tablicy
const removedItem = products.pop();
zwraca ustunięty element

dodawanie i usuwanie z początku tablicy

dodaje na początku
constt newLength = products.unshift("pasta");
zwraca długość?

usuwa z poczatku
const removedItem = products.shift();
zwraca długoś?

 usuwanie dowolnego elementu
const products = ["jaka","bułka","chleb"]

products.splice(1,1)
usuwa drugi element

products.spilice (2, 2, "rajstopy", ":dd")
usówam 3 i 4 i dodaje nowe wartośći

pierwszy argument index-który element
drugi argument

09:55

products.splice(0,3, ")
zwraca piewrwsze trzy i dodaje do tablicy "
za mienia je na "

forEach- iteracja po elementach z tablicy

const products = ["jaksa","cheb", "pyb", "nułki"]

products.forEach((products, index)=>{
console.log(`${index +1}. ${products}`)
;
}
wypusuje po kolei wszytskie elememnty


for..of - ietracja gdy nie potrzebujemy index

for(const product of produkts ){
  cosole.logg(product);

product-nawzwa jką chcę do każdego kolejnego elelementu
}

przekazywanie tablic do funkcji oraz porównywanie działa tak samo jak w przypadku obiektów.
-przekazwane przez referencje
-porownywanie dwoch tablic zawsze zwroci false

dostała jak parametr.

Moduł 6 
 Prosta lista zadań w JS
 00:00

prosta aplikacja do zrządzania listą zadań

<form>
<input>
<button>
</form

<ul></UL>

JS >
const task = [
{
  content:"nagrac lekcję",
  done: false,
},
{ content:"zjeść pierogi",
  done:true,


},
07:12
];

const render =() =>{
let htmlstring= ""

for(const task of tasks){
  htmlString +=
<li  $tasks.done ? " style= \style="tekst decoration line truth>\ jetss to cSS : "")>
${task.content}
</li>

}
document.querySelector(".js-list").innerHTML= htmlstring

}

const init = ()=>{
render()
}
init()

08:00
dodawnaie nowych zadań
 
 const init = ()=>{
render()
const form= document.querySelector(".js-form");
form.addEventListener("submit" , (event) =>{

event.preventDefault();

const newTaskContent = document.querySelector(".js-newTask").value.trim()
console.log (newTaskContent);

if(newTaskContent === "") {
return;
}


powró aby zro przerobi na funkcje zewnętrzną
const addNewTask=()=>{

tasks.push({dodaj do tablicy
  content: newTaksContent,


}


tasks.push({dodaj do tablicy
  content: newTaksContent,

}
}
render()
}
init()

11:20
skracamy i sprzątamy

komit

13:45 usuwanie zadań

<button class:"js-remi"> usuń </butto>
cons removeButtons = document.querySelectorALl
("js-remove")
 
console.log(removeButtons)
removeButtons.forEach(removeButton,idindexex) => {

removeButton.addEventListener("click'),() =>{
tasks.splice(index , 1)
}}}

}
removeTask
skracamy funkcję

przed przyciskiem usowania
18:57 przycisk zmiany stanu
<button class= "js-done">zrobione</button>

w LI

cosnt toggledoneBUttons.forEach(toggleDoneButton, index) f.strzałkowa
toggledonebutton.addEventLisener(click) fukcja

toggleTaskDOne(index)
tasks[taskindex].done =!tasks[taskIndex].done;
render(;)

22:00
Fefaktoryzacja

~24:00 przeglą

moduł 6
Praca domowa (4 min) 
00:00

moduł 6
Wskazówki do pracy domowej (14 min)
00:00
CSS- własciwości tylko ptrzebne
nie yżywaj atrybutu style, tylko zmieniaj klasy
używaj klas

przycisk może być jeden

w README nie dodawaj dużych obrazów.

event listener po wyrenderowaniu

formatowanie temple strings

uzywaj terenary tylko gy coś się zmienia
05:48

class="list_item${task.done ?" list_item--done" : ""}"

nazwy funkcji mają opisywać co fukcja robi

Renderuj widok tylko w funkcji render-nie w eventach handlerach

Statystyki

document.qureySelector(".js-stats").innerText=
`liczb zadń: ${task.lenght}\n
liczb zadń: ${task.filter(task => task.done)}\n
`

uważaj na znaczkinki HTML 
jak wpiszech <strong> to pogrubi na liście zadań.

moduł 7
Praca domowa z poprzedniego tygodnia (25 min)\
00:00

2 różne o innych problemach

04:35
 display:grid
--toogle done
 12:00 Java Script

${task.done ? "D" :""}
  
  14:39 inne prace

dwa podobne elementy, różnia się modyfikatorem

splice() dodaje i usówa elementy z tablicy

content- wpis do tablicy

let -nie używamy letów, tylko kiedy już nie musimy



Moduł 7
CSS – płynne przejścia, transformacje (15 min)
00:00

.element{
background: red;
transition: 1s;
}

.element:hover{
backround: blue;
transform: scale(1.5)--zmniejszanie elmentu
    scaley()
}

transform:rotate
0.5 turn

tranform:
translatex(100px)-przesuwanie
translatey(100%)

kilka transformcji po kolei
kolejność może mieć znaczenie

transform-origin
wokół , którego punktu mamy się obracać

.element
transform-origin: right bottom; albo np.100px

jak dziala tranform
zmienia kształ i położenie elementó
nakłada transformację po kolei
nie wpływa na inne elementy.

transition-property
warto podać, które właściwości będą animowane

transition: background 1s; transform 2s

warto podawąć które wartości będe anonimowane
warto anonimować transform zamiast np. width, height,margin

transition_timing-fuction
  .element{
  transition: background 1s linear;
  }

transition -timing-function: steps 5

transition-delay
backqround 2s 2s opóźnienie 2 sekundy

właściowośći można zapisać oddzielnie
.element{
transition-property: backqround
duration: 1s, 2s;
delay: 0, 0.5s
timing-function: linear
}

transition nie musi działać po najechaniu

element-hover
element--bigger{
  transform: scale(1.5)
}

JS- powiekszanie z poziomu Java Scriptu
const element= document.querySelector(".element")
element.classlist.toggle("element--biger)


Moduł 7
JS – obiekty cz. 2 (18 min)
00:00

dużó składni ecma 6, bardzo dużo nie działa w Internet Explorer

const name: "KRzysiek"
const surname: "Dąbrowski"

const person{
name,
surname
} 

 skrócona notacja
  const person={
  name:"krzysiek"
  sayHello(){
  console.log(`CZeść $[this.name}]);
  
  } 
  }

const person = {
name:"keke"
sayHello(){
console.log(`hejka ${this.name}`)
}
}

const currency = "ero"

const exchangeData = {

const exchangeData= {
PLN:45
Euro:200
}

PLN: 45
[currency] : 200,
}

Destrukturyzacja
const peroson: "Krzysiek",
surname:"Ddsd",
age: 29,
gender: "male"

const{name, srname ...rest}=person; --rest obiekt  pozostałymi właściwościami
const {city = n/a = person;

const{surname:;lastName}= person;
}

const getPersonFullName= ({name, surname}) =>
`${surname} ${name}
`;

cosn{name,age]}= person
to samo co:

const name=person.name;
const age= person.age;

może też być
06:30

const{name, surname, age, gender}=person;

console.log(name,surname,age,gender);
wynik; im,12,3

...rest-pozostałe

const{name, surname, ...naywamjakchcę} = person;
czyta z innej zamkniętej fukcji , tablicy

np. name = name
const peroson: "Krzysiek",
surname:"Ddsd",
age: 29,
gender: "male"

name
"Krzysiek"
surname
"DDSd
nazywamjkachcę:
 {age:29, gender: "male"}


domyślna wartość do jakiejś własciwości jeżeli jej już nie ma
const {city = "N/A"}= person;

name
"Krzysiek"
surname
"DDSd
nazywamjkachcę:
 {age:29, gender: "male"}

city
const{name, surname,city, age, gender}=person;
dodają city undefind 


const{name, surname,city="sg", age, gender}=person;
dodają city undefind 

dodaje sg

+
city
const{name, surname,city="ss", age, gender}=person;

wchodzi city ss

domyśłnie wejdzie ss

08:35
const {surname: lastName} = person

zmienia w locie zmienna surname na last. W tablicy jest tak jak było.

obiekt jako argument funkcji

const =getPersonFullName = ({name, surname}) =>|${name} ${surname};

zwraca łancuch znakó imie i nawisko połączone spacją

console.log(getPersonFullName(person));wyciąga z tablicy perosn

DEstrukturyzacja w zagnieżdżonym obiekcie

const person= {
  name:"krzysiek"
  surname: "sdd"
  father:{
name:"sdsd"
surname: "wdw"
  }
}

const {father:{name:fatherName}} =person;
consoloe.log(`demdem${fatherName});
demdem

Łączenie obiektów
  const personBasicData ={
  name:"Krzysiek",
  surname: "Dąbrowski",

  const personAssitional = {
  age: 29,
  }
  
  }

const allPersonData = {
...personBasic,
...personAdddionData
}
spred syntax połączenie

cos Allperson data= {
...personBasic,
...personAdddionData
gender: "male"
}

consloelog.(aLLPERSON)
obiekt

kopia

consloe.log(personCopy === person); false
console.log(personCopy.father ===person.father) thrue
personCopy.name ="Mrian";
kopia-spreadsyntax

const personCopy = {...person};

personCopy.name =""Aleale"

Bez kopi w dwóch będą rózna wartości
w copy i copypeson

console.log(personCopy ===person); false
consloe.log(personcopy.father ===person.father); true
płytka kopia
kopiuje najwyższy poziom

for (const property in person){
  consloe.log(property); wypisze- ----name, surname
  console.log(person[propery]); Imie i ZNazwisko
}

W kosole log moey pisać rzeczy po przecinku


MOduł 7
JS – tablice cz. 2 (38 min)
00:00

const numbers = [10,45,19,10,56]
const[number1, number2]= numbers
  iteruje od pierwszego elementu

  const[nuber1, ,nuber3] nubers;
  10,19
  const[nuber1, ,nuber3, ...othernumbers]-wszystkie pozostałem do tablicy othernubers

domyślne wartości
   const[nuber1, ,nuber3, nuber4=0, ...othernumbers]
  domyśla wrtość to be przypisana potem tylko ta brana z tablicy

  Łączenie tablic
  const nuber1=[10,45]
  cons number2= [20,49]

  const allnumber = [...nubers1, ...nubers2,89]
  jest to nowa tablic,

dwie różne tablice
const numbers = [10, 45]
const numbersCopy = [...numbers]

const nubers = [12,18,19,44,64,81]
console.log(Math.min(...nubers)) 
12

const myFunction =(firsParametr, ...therParamentrs)=> {
console.log("ierwszy argument $[first parametr}");
console.log("iczba pozostałych argumentó ${therParametrs.lenght");
}
myFunction(4,8,1,9,74,51);
...therParametrs traią do osobnej tablicy
liczba pozostałych argumentó 5

wyciąganie fragmentu tablicy
const seasons =[ "wiosna","lato","jesień","zima"];
cost last2seasons= seasons.slice(2) --sień zima
const middle2seasons=seasons.slice(1,3); --lato jesień
const last3seasons=seasons.slice(-3)-lato, jeśień, zima
const allButLast= sessons.slice(0,-1); wiosna latao, jeśień

index elmentu

09:57
const nubers = [20,10,45,10]
console.log(numbers.indexof(10));  1
console.log(numbers.lastIndexOF(10  3
console.log(numbers.indexOf(5)  -1
console.log(numbers.lastIndexOf(5)  -1  gdy brak

numbers.indexof("") cudzysłów umniejsza


const numbers= [-7,0,10,-6,45];

const firstPositive= numbers.find(nuber>nuber>0); 10 -pierwszea liczba dodatnia
const first100 = numbers.find(number===100);
undefined

const persons =[
  {name:"Krzysiek"
  name: "AMoa"
]

const chris= persons.find(({name})=>name==="krzysiek"


12:00
const isPositive = (number) =>{
if(nuber>0)
return true
retune underfinde

}

const firsPositive = nmbers.find(isPositive)

const firstPoitive = numbers.find(number=>number>0);

const firstGreaterThan100 = numbers.find(number=>number>100);


const persons =[
  {name:"krzyie" gender:"male"
  name: "sndsi"} gender:"female"
  ];

constIs chris = (name=>name ==="Krzysiek";
cnst chris-persons.find()

idCHrist(obiekt) true or false

cons firstFemale=persons.find(({gender })=>gender==="female"

20:00
findindex zwraca index znalezionego elmentu


includes
const quests =["włodek,"irmina", "melodia"];

niepodległóść

console.log(quests.includes("Włodek")) --true
console.log (quest.inludes("Zenek"))-  -false
czy talbilca zawiera dany element

some 
const tasks=[
{content:"odcsc", done:false
content: "sdadas", done:true
}]
const firstDone = tasks.find(task.done)
22;37
const is eny firstDOne= tasks.some(({done})=>done);
pierwsze zadanie zronione które

find kontra some
any
23:20
const nuber=[1,3,5,7]
onst is Even = number=>{
if(number% 2===0{
return:true

return false
}

comst isEven = number=> number%2===0;
const isNyNubersEven =nuber.some(isEVen);
false

Every -czy kąży element zawiera warunek.
24:37

Filtrowanie
dostjemy nową tablicę z elementapi spełniającmi warunek.

const evenNumbers= nubers.filter(isEven);


tablic oniekty

const tasks=[{
  content: "wdsws", done:false
  content:"wsdw', DONE:true
}

const isUndone= task=> !task.done;

const tasksUndon= taks.filter(isUndone)

const tasksUndone =tasks.filter(({done})=!done);


27:03 Mapowanie /odwzorowanie

const numbers = [1,5,9];
const doubledNumbers = nubers.map(number => number*2);
nowa tablica z pomnożonymi *2 wartościami

wyciąganie nazwisk
const persons = [
  {name: "Krzysiek", surname: "Becwał"
  name: "Ka;ina", surname: "Jak"}
]
const surnames = persons.map(person=>person.surname)

const getFullName = (person)=>`${person.name}
${surname}`};
+
const fullnames= persons.map(geTFullName)
;

fuulnAmes-tablica stringów

+lepiej

cons getFullName = ({name, surname}) =>`{$name} ${surname}`

reprezentacja html
const personsAsListItems = persons.map(person =>
`<li>
${getFullName(person)}--- reprezentacja htmlowa
</li>
`);

const personsHTML = personsAsListItems.join("");
powstał HTML z listą dwuelementową

Sortowanie tablic
const strings = ["B", "a", 10, 2];
strings.sort();
console.log(strings); 
zwraca
["10", "2", "B", "a"]
sortuje i zwraca posortowaną. modyfikuje ją
słaba zadaniowość

 z sensem
nubers.sort((a,b) =>a-b):
zwraca sortowaną tablice od najniejszej cyfry
podobnie:

nubers.sort((nuber1, number2)=>{
  if (number1>nuber2)
    return1;
 if nnuber1===number2;
return 0;
} 
 return -1)


nuber.sort((a,b) =>a-b)
dobrze posortuje
zwraca liczbę dodtania gdy a ma być przed b
ujemną gdy a ma być po b
0 gdy nie ma zmiany

Sortowanie alfabetyczne
cosnt surnames = ["duda","dabrowski"
]

surnme.sort((a,b)=> a.localeCompare(b)));
surnames.sort((a, b) => b.localeCompare(a))

ą dalej w tablicy znakó niż u

sortowanie obiektów
const persons= [
 name: "Rafał", surname: "Trzaskowski"}
 name:"Andrzej" , surname: "Duda"}
];

getFullName= ({name, surname})=> `${name} ${surname}  `
nie obiekty a stringi
persons.sort((a,b) => getFullName().localeCompare(getFullName(b)));
tablica posortowana. 

odwracanie elementów talicy:
numbers.reverse();


MODUŁ 7
Immutability (14 min)
00:00

nie mutować obiektó i tablic, Twożymy nowy obiekt, nową tablice ze zmodyfikowanymi wrtościai.

const string= "tekst";
const stringUpperCased = string.toUpperCase();

const number =5;
const nuberFormatted= number.toFixed(2);
jeśli łańcuch zmodyfikujemy. to już nie będzie to ten sam łąńcuch.

string.toUpper.Case(); powstanie nowy string

const upperCased = string.toUpper.Case();
string =tekst
string= TEKST

pierwszy sring nie został zmodyfikowany

let string= "tekst";
string= "inna wartość"

w typach prymitywnych nie możemy zmieniać wartości

const number= 5;
const numberFormatted = number.toFixed();
5
"5"

Obiekty i tablice możemy mutować.
const person = {name: "Krzyś" };

person.name ="hieronim"
person
hieronim ten sam obiekt
nie ma dwóch obiektów
mogę nawet coś dodać
person.surname= "sassa"

person 
zwraca name i surname

const cars= ["bemnka"];
cars.push("merc")
powtaje zmiana w tej samej tablicy
cars.pop() usówa ostatni element

dlaczego to nie jest fajne
kod jest mało przewidywalny i mało czytelny
mogą pojawiać się błedy trudne do wykrycia
trudno wykrywać zmiany

aby sprawdzić jakieś zmiany to trzeba porównać wszystkie elementy
nowa tablica i nowy obiekt łatwo proównac.

Jak praacować z obiektami i tablicami bez mutowania.

jeśłi chcę coś zmienić to robię to coś nowe z nową włąściwością

const person= {
name:"Krysiek"
surname:"wsws"
}
const updatedPerson={'
...person
name:"HEe"
}
są to inne obiekty, zklonowane

const person ={
  name: "Krzyśiek",
  surname: "Dabrowski",
  }

  const personWithAGe={
  ...person,
  age:29,
  };

Destrukturyzacja

  Usuwanie włąściwości obiektu.
  const{name, ...bezwieku,
  }
= person;

person name do stałej a cała reszta do bezwieku

Dodanie elementu do tablicy

const tasks = [
      {title: "zantotować lekcję", done:false}
      {title: "zasadzić drzewo", done: true}
]

nie robie task.push({title:"cosnowego",done:false})

const taskWithNew= [
...tasks,
({title:"cosnowego",done:false})
];

mamy dwie rózne tablice z edycja drugiej o rekord

const taskWithNew= [
({title:"cosnowego",done:false})
...tasks,
({title:"cosnowego",done:false})
];
dodany nowy na pocztaku a nie na końcu.

tasks[0] ===tasksWithNewItem[1]
true

09:54
usuni ecie elementu z tablicy
const tasks=[
{title: "zmontowć lekcję", done:false}
{title: "zmontds", done:false}
{title: "zmonsdsdsd", done:false}
]

const tasksWithRemovedSecondItem =
[
...tasks.slice(0,1) -pierwsy element
...tasks.slice(2) - usowamy drugie
]
chcemy usunąć drugie

const UsuniecieID = 0;  zależnośći od indexu usowa
[
...tasks.slice(0,1UsuniecieID) -pierwsy element
...tasks.slice(UsuniecieID+1) - usowamy drugie
]

Edycja elementu tablicy:
zmodyfikować tylko ten jeden element.

const editIndex = 1;

const tasks =[
{title: "zmontować lekcję", done: false}
title: "scsd", done: true}
(title: "sxsa", done: true
]

const tasksWithUpdatedItem =[
...tasks.slice(0, editIndex)
{ ...tasks[editIndex], done:true)
 ...tasks.slice(editIndex + 1
 ]

tasksWithUpdatedItem
0
1
2
 aktualizacja


MOduł 7
 Prace domowe (3 min)
00:00
 REfaktor z imutability

dodaj dwa przyciski:
1.pierwszy powinnien ukrywac lub pokazywac zadania ukoń czone
2. Wszystkie zadania jako ukończone
3. Jesli nie ma nic na liscie to nie ma przyciskó
4. jak są ukończone to przycisk wyłączenia nie jest aktywny.

Wsytskim przyciskiom dodaj płynne zmiany koloru
Przycisk ma się powiekszać i zmienić kolor po najechaniu

zadbaj o responsywność min itp.


Moduł 7
Podpowiedzi do prac domowych (11 min)
00:00
co CIe czeka
wskazówiki  
renderacja

podzielić na dwa renderowania
const renderTasks= () =>{};
 00:57
const renderButtons = () =>{};

const render = ()=> {

renderTasks()
renderButtons ()
constbindButtonsEvents ()
}

const bindButtonsEvents =  () =>{};
if CZY JEST LSITENER WCZY NIE

lethideDoneTasks = false;
po kliknięci w  przycisk- przełącza

const aaNewTask = (newTaskContent) => {
  tasks = [
  ...tasks,
  {content: NewTasContent}  
  ]
;
render()
}

const toggleTaskDone = {taskIndex} =>{
 tasks = tasks.map
render()
}

najlepiej jest renderować wsyztysko
zależnośći mięzy elementami
np. jeśli jakiś jest wyłączony to renderujemy() drugi.

06:02

nowy widok renderuje render()

wyłaczony przycisk disabled
pseudoklasa

po interakcji zmienimay coś w danych i pozniej na podstawie tych danych robimy zmiany generujemy widok

react wie gdzie render()

zrób to za pomocą samego JS.


MODUŁ 8
Prace domowe z poprzedniego tygodnia (30 min)
00:00

Vędzie pryzpisywał z każdym razem nową tablicę
przekazywał

const removeTask = (taskIndex) => {
tasks = [
...tasks.slice(0, taskInde)
...tasks.slice(taskIndex +1)
]
render()
}
zwróciło nową tablice.

const toggleTaskDone = (taskIndex) =>{
tasks = [
...tasks.slice(0, taskIndex),{
...tasks[taskIndex],
done: !tasks[taskIndex0].done
}
...tasks.slice(taskIndex + 1)
]
render()
}

const addNewTasks = (newTaskCotent) => {
tasks = [...tasks, {content: newTaskContenet}]
render()
}
elementy z wcześniejszej tablicy i nowy element

zrób refaktor listy zadań zodnie z immutability

dodaj dwa przyciski
pierwszy pokazywanie i ukrywanie ukończonych zadań
drugi przycisk-wszytskie zadania są ukińczone
brak, przycisków gdy list jest pusta
brak przycisku oznaczenia przyciskó wszytskich jęśli wszytskie zdania są ukończone

wszystkim oznaczanie done
const markAllTasksDone = ()=>{
tasks= tasks.map((task)=> ({
...task,
done:true,
})
render()
}

if(task.done){
return tasks;
}
return{
...task,
done: true,
}

const toggleHideDoneTasks = () => {
hideDoneTasks = !hideDoneTasks;
render()
}

06:25
const renderTasks =()=>{
  const taskToHTML = task =>
  <li clas""${hideDneTasks}>+ klasa css 
dostaje taks i zwraca html

później map
const tasksElement = document.querySelecto(".js")
taksksElement.innerHTML = tasks.map*tasktoHTML).join("")
}

łączenienlementó w jeden string i pożniej innerHTML

css.np.
.tasks__item--hidde{
display: none:
}
08:15
const renderButtons = () =>{
  const buttonElement = document.querySelekctor(".js");
  if (!tasks.lengrth){
    buttonsElement.innerHTML = ""
    return;  }
}
jeśli nie ma zadań to nic nie będzie wpisane do buttonsbelement
jeśli są to wpisuje string włącznie z przyciskami

jeśłi dalej są zadania
buttonsElement.innerHTML=
<buttons class=przcysiskCCS' js> ${hideDoneTask? "pokaż"; "ukryj"}ukończone </button>
klasa js robi toogle
hideDOnetasksks w zależności od trej zmienej 
jest na przycisku "pokaż" lub "ukryj"

<button class="pzyciskiCdd js2">
${tasks.every(({done}) => done) ? "disabled" : ""
ukończ wsyztskie zadania<?button>

fckcja renderująca robi pokąż ukończone itp.

evenlistenery ktróe mją się odpalić po kliknięciu w jeden lub drugi przycisk.

const bindButtonsEvents = () =>{
 const markAllDoneButton = document.querySelector(".js")

 jęsli (markAllDoneButton)
  {markAllDoneButton}addEventListener("click), markAlla =TaskDOne)

  const toggleHideDoneTasksButton = document.querySelector("js"
      )
}
]
if(toggleHideDoneTasksButton) {
  toggleHideDoneTasksButton.addEventListener("click" , toggleHideDoneTaska);
}


rnderują się jeśli lista zadań nie jest pusta

funckja render podzielona na kilka funkcji
render = () =>{
renderTasks()
bindRemoveEvents()
bindToggleEvents()
renderButtons()
bindButtonsEvents()
}

wygląd
11:50
flex
transition color

przyciski w Header
diplay grid

mediaquery np. odbi ór właściwy na telefonie

flex basis 100% -przyciski gdyby nie miał zmiesiły by się jeden koło drugiego

funkja renederująca wie
react będzie renderował tylko to co trzeba
funkcj renderująca zajmuje się jak wyrenderować w zależnosici od stanu

renderujemy wszytsko po każdej zmianie
minimalizcja zależnosci

w funkcji renderujacej ma być logika odpowiadająca za cały stan aplikacji

w liscie zadań render jest w liscie buttons.

nie dopisujemy typu do nazwy zmiennej

nie powtarzaj kodu, zmiennych,
potrójny operator zamisat if,else
potrójny operator - gdy chcemy coś wzócic np.jeśi tak , nie


Moduł 8, 
 React – pierwsze spotkanie (33 min)
 00:00
niektóre dziłania w js już nie będą potrzebne

react to biblioteka w JS
ułatwia tworzeni interaktywnych zdażeń użytkownika
aktualizuje tylko to co musi się zmienić w render
bauje na komponentach

02:30
dodajemy reacta url-ami
jest jescze babel-zmienia skłądnie jsx
<div id="root"></div>
<script type="text/babel">
const exampleReactElement= <h1>sda</h1>
reactDOM.render(exampleReactElement, document.getElementById(`root`));
</script>

JSX
rozszeżenie składni JS
dzięki Babelowi dochodzi do prostrzej zmiany na js i html

JSX pełna moc JS
produkuje elmemnty reactowe
do wyrażeń używamy klamr
w temple strings --$ tu nie ma

{neme funckje conol()}

w JSX atrybuty  przekaxzujemy troch e inaczej jak
zywkłym HTML-u

nie class tyko clasname
np. <div clasName="sx">

disabled przekazuje w klamrcha{true}
boolean- bulin

można różne typy przesyłać jak wartości atrybutów.
nie są do ko nnca to artybuty
np.string = clasName="container">
albo kalibrejses w Klamrach
camelCase

to co w atrybucie jest class będzie włąsnośćią

document.querySelector(.nazwaKlasy')
<h1 class= "nazwaKlasy">..</h1>
const myElement = document.querySelector(".nazwaKlasy")
  uundefinded
myElement.className
  "nazwaKlasy"

JSX mogę także przekaza true or false
<div className = (
  <div className= "container">
    <button disabled= {true}> Wyłączony przycisk </button>
    <button disabled> Wyłączony przycisk</button>
  </div>
camelkejs używamy
spread syntax

const attributes = {
  className: "button",
  disabled: true,
  }
const element = (
 <button {...atrributes}>
 Wyłączony przycisk
 </button>
)

JSX escapeuje Html

hackowanie w dodawaniu atrybutów w inpucie

w Reakcie anty hack robi automatycznie
zamienia na encje

React aktualizuje to co trzeba
widzi to co się zminiłó
Ma wirtual DOM który tworzy i na podstawie jego porównuje.
Jets to wydajniejsze.

przykłąd funkcji
const Hello= (props) =>( -destrukturyzacja pros na name name
<h1> Czescs {props.name}</h1>
)
const element= <Hello name="Krzychu"/>;
ReactDOM.render(element, document.getElementByID(`root`));

komponenty sa funkcjami JS, klasami

otrzymują props i zwracają element react

atrybuty stają się właściwościami obiektu props
pozwalają podzielić aplikację na odrębne niezależne treści
nazwy komponentó piszemy wielko Literą bo pomyli się React jako html

Komponent nie zmienia przekazanych mu props

komponenty dla tych samych props powinny zwracac zawsze to samo

na podstawie props zwracamy widok

pure function- to samo do tych samych emelentó
nie edytuje liczy i coś zwraca

operator warunkwy
<h1> czesc {props.name ? props.name: "nieznajomy"}</h1>
Cześć {name? name: "nieznajomy"}!</h1>
zywkły Java Script

|| opeator zwraca po lewej stronie to co jest truefi

np.
Cześć {name|| "nieznajomy"}

&& dwrotnie do ||

!! konertuje wartos na boolean true or false

const ProductsList= (props)=>(
<ul>{}
props.products.map(products =>(
  <ul>{}</ul>
)
)
const element = (
  <ProductList
  productList={["sdd"sds"sd"]}
)
)

Key
<li key={products}>{product}</li>

const products
[
id 4, name: "gumnka"}
id:6 , name: "zwrotnice"}
]

const element = (
  <ProductList
  products= {products}
)
)

<li key={products.id}>{product.name}</li>

mozna użyc destrukteryzacji
{products.map(({id, name}) => (
<li key={id}>{name}</li>

key nie są przekazywane do komponentów
w jednym obrębie muszą być unikalne
key jest nawa reacta której nie używamy do czegoś innego

<React.Fragment>
</React.Fragment>
jak chce wyrenderowac dwie rzeczy.Nagłówke i lista produktó
MOgę mieć diva wspolnego
ale moge takze użyc reactFragment
z usuniętym divem.

32:00 Tutorial

Moduł 8
create-react-app – odcinek 1 (49 min)
00:00
insalacja node

git bassh
node - v
pokaże któr wersja jesli jest

node moze uruchamiać java script

cd c:\dev
npx cerate-react-app nazwa-aplikacji
pobieże się paczka i stworzy się startowa aplikacja.

cd nazwa_aplikacji
npm start

wystartował serwer
stworzył się piewrszy komit

git-log - jest już jeden komit

ctr-c wyłącza gitbasha

npm start odpala się w terminalu.

będziemy używać deweloperskiego serwera

pik App.js
serer się automatycznie odśiweża

webpack jest tak skonfigurowany ,żę będziemy mogli sworzyć iodrębną wersję aplikacji

mamy babela  sprawaja ze jsx zamieia się na JS

ppkażemy jak korzystać z paczki.

webpack możę porozbijać pliki np. JS
dzięki niemu możemy importować niektóre rzeczy.

app.js to komponent jakiś reaktowy -eportujemy z niego różne funcjonalnośći.
możenmy go zainportować.

mgę importować nawet CSS-esa

zmiany podmieniają się w locie.

jeśłi w module jakimś stworzę np. zmiennią
const myConst = 5;
ona nie będzie dostępna w innych modułah
tylko widać te które eksportujemy.

11:40
przeoszenie listy_zadań do recta

dodajemy normalize
index.html
tu jest szablon html
tak wklejamy normailize

wklejamy trzcionkeę z google.

13:00

przenośimy style

ap.js
tu umieszcamy program

lusowam nie potrzebne rzeczy
np.logo.svg

<title> zmieniamy tytuł strony

modyfikacji do konujemy w src

15:43
przenoszenie start
nie mogę użwać class tylko className.
input musi mieć na końcu /  

const tasks =[
{id: 1, content: "przejść", done: fslse}
{id: 2, content: "blabla", done: true}
]
const hideDoneTasks =false;

klasy js-cośtam te klasy nie będą potrzebne m,, nie będziemy używać inne zarządzanie interekcjamy
qourey selector nie będzie używany

plik 
index.js

importujemy import React feon "react";
import Form from "./form"  w index.js

const Form = (

) =>(
  <form...></form>
)

export deafult Form; 
nowy plik style.css
import "./style.css"

new forder 
tasks
index.js
import React from "react";

const Tasks = (props)=> ();
zwraca listę

export default Tasks

w index.js 
<Tasks
tasks= tasks={tasks} hideDone Tasks= {hideDoneTasks}

/> 
import Form  from "./form";
import Tasks from "./Tassks";

w index.js tasks
ul
{props.tasks.map(task => (

classname

  task.contenet
))ul

trzeba dodać key={task.id} do kążego elementu w tablicy

Wklejam ccs, które były odpowiedialne za Tasks
w folder takss. style.css

importujem css=y
w tasks/inedex.js
import "./style.css"

modyfikujemy
w index.js tasks
li
{props.tasks.map(task => (
li
classname= {`class__item ${task.done && props.hideDoeTasks?"tasks_item-hidden : ""

25:00
  task.contenet
  zamieniamy na
  buttony itp. , zmieniamy na Clasname
span className= (`tasks__cntent${task.done ? "tasks__content--done: ""}
{tasks.content}
))ul
usuwamy $
wklejamy w spana className = {``}

przednp.${zmienna}

25:50 przyciski
folder button
index.js
impor React from "react";

const Buttons = (props)=>{

<div> <button></div
}

export default BUttons

a w App.js
import Buttons from "./buttons";

tworzymy w buutons css i wklejamy style
w inex od buttons:
import"./style.";

27:00

const Buttons = (props)=>{
if (props).tasks.lenght===0
return null
else
<div> <button className=(`buttons__button js-markAllDone`${tasks
}
jeśli lista zadań jest pusta to przyciski nie mają się wyrenderować.

app.js
<buttons tasks-{tasks.every(({done}) =>noe) ? "disabed":""}

<class="buttons__button"> props.${hideDoneTasks ? "Pokaż": "ikryj"] ukończoen</button>

restrukturyzacja
const Buttons =(tasks, hideDoneTasks

)=> {tasks.lenghth ===0
 
return null.
  }
}else
 
 w App.js
 <buttons tasks={tasks} hideDoneTasrks = {hideDonetasks} />
<taksks tasks= {tasks} hideDoneTaksks= {hideDonetasks} />

idex.js/buttons
const Buttons=({tasks, hideDOneTasks}) => {
  if(tasks.lenght ===)
  return:null
else return
Butony
}

disabled = {tasks.every(({done}))}

const Buttons = ({tasks, hideDoneTasks }) =>{
return taks.lenght >0 && ((
  <div>
}

nowy folder section
nowy plik w nim index.js
import React fron "react";

const Section = (props) = >( 
<section></section>

)

export deafault Section;
w App.js import
nowe style css w folderze section
import syle CSS

 const Section = (title,body,extraHeadrerContent) = >( 
<section>
<h2 className= "section__title>{title}</h2>
{extraHeaderContent}
<div className= "section__body">
{body}
<tasks
</section>
)

Zmiany App.js
<section title="odaj nowy tytuł" body={<Form/>}/>
<Section title="lista zadań"

<section title="odaj nowy tytuł" body={<Tasks task={tasks} hideDoneTasksks= {hideDoneTasks}/>
extraHeaderContent=
<BUTTONS tasks={tasks} hideDoneTasks={hideDOneTasks}/>
/>

 body i extraheaderContent ten sam poziom atrybutu


nowy folder Header
index.js
import React form "react"

const Header = ({title})
<header>
<h1>{title} </h1>
</header>
);

export default Header;

w App.js
function App() {
    return
    Main
    <header title="lista zadań"/>
}
i import Header from ".header"

39:00

<container>

</container>

nowy folder Container
nowy plik index.js
import React from "react"

const conteiner =(props)=>(
  <main className="container">
  {props.children}
  </main>
)

destukturyzacja

const conteiner =(children)=>(
  <main className="container">
  {children}
  </main>
)
 w coteiner -nowe style css

w App.
import Cotainer from "./Container"

w contener/index
export default Container;

const Taks = ({tasks, hideDoneTasks}) => (
  <ul
    tasks.map(tasks=> (
      LI
        task.donee && hideDoneTasks]? :
)
{tasks.length > 0 &&  ()
</React.Fragment> b łąd skłądniowy przy dwóch przyciskach

<renederuje DIV bo jest nad warunkiem {tasks.length > 0 &&  ()
47:23

Moduł 8
Więcej o create-react-app (20 min)
00:00
npx create-react-app my-app
cd my-app
npm start
musi być zainstalowany node

npm run build
wszytsko połacznoene i zmilimazolowane
wszytsko jest już skonfihurowane
css jest zmimifikowany

folder build
można wysyła gotową stronę do neta.

node_moduels
biblioetki, zależnośi
React, RectDOM, Webpack, Babel, ESLINt, Jest, PosstCSS itd.

dodany do git ingonor, tak ma być

src- folder ze źródłmai naszej aplikacji
webpack przy budowanie aplikacji bierze pod uwage tylko pliki w tym folderze
Łączyz je i znich powstaja wynikowe bliki w folder build
główne pliki do jS i CSS a,le zawarte są także obrazki.
tutaj zamieszcamy nasze komponenty i praweie tylko i wyłąćznie modyfikujemy ten folder.

index.js w src
tu  jest renderowana nasz aplikacja

public /index.html
zwykły szablon htmnl-owy
szablon strony do której webpack doda wygenerowane pliki JS i CSS
warto zmienić na pl
warto podmienić ikonkę strony
%PUBLIC_URL% zostanie zamienione na adres URL naszej aplikacji
warto dodać og:image open graf

inne pliki 
vavicon.ico , logo192.png, logo512.png - ikona strony
manifest.json- potrzebne kiedy tworzymy PWA
robots.txt- informacja dla botów (pozwolenie na indeksowanie strony)

package.json
różne dane na temat projektu
wersja, nazwa
dependencies- zależności(biblioteki, paczki) których używa nasza aplikacja
  pierwszze trzy dotycza testowania
  na podstawie tego co w dempendencies generuje się cały folder node_modules
eslintConfig- sprawdza nie użyte zmnienne itp.
browserslst
  production
  www.browserl.ist
 0,2% webpack bedzie przerabiał tak kod aż uzsytka zadane wspiernie przeglądarek
 scripts-tu definiujemy tzw. npm scripts

dzięi nim możemy pisać npm start itp.
package-lock.json - jest zapisane dokładnie z jakich wersji biliotek korzystamy w projekcie

README.md
Warto wprowadzić zmiany pod naszą aplikac
Informacje jak ją dewelopować i jak ją zbudować.
Learn more -także usuwamy

Nazwa proejktu\Lista zadan
opis projektu

Dokumentacja

MOduł 8
Deployment na GitHub Pages (9 min)
00:00
Nowe reperyzotorium
według instrukjci na git hub-e

package-json "homepage": link,
homepage adres http z githuba

npm instal gh-pages  
dodaje do dipendesis

"scripts":
"deploy":"gh-pages -d build" buil jak folder na interesuje
"predeploy": "npm run buil"

jak zrobie deploy to też się zrobi predeploy

stworzyła się galąź git hub pages
gh-pages

gh-pages zmienń gałąż aby dostać adres strony


Moduł 8
Prace domowe (2 min)
00:00
 zaintsaluj node
 stwórz projekt creat-react-app
 przniejs swoją listę js na reacta


MODUŁ 9
Prace domowe z poprzedniego tygodnia (12 min)
00:00

instalowanie node
prjekt create app
przenieś liste zadań bez interakcji

utrymuj prostotę
nieprojektujemy na przyszłość
 
np. section używamy dwa razy
body  dlatego przekazujemy do niego argumenty
Tam gdzie map() powinno byc także key
React powie że go brakuje.

<react.Frgment></ReactFragment> <fragment><.fragment>

warto przkeaywać atrybuty w "" bez klamr tak jak w html

autofocuc a nie autofocus={true}

jak jest pusty element w JS

 <div/a> gdy nie ma nic między divami

 PublicURL nie zjmieniaj


atrbuty albo wsztskie w jednej lini albo w wileu liniach

niepotrzebne spacje

zawiasy we funkcji strzałkowej mozna ich nie dać ,ale łatwiej się formatuje.

trzymać sie klas BEmowych

zrób employment
https://piecioshka.pl/blog/2017/05/11/czym-jest-dla-mnie-bem.html

Technika to metodyka, która charakteryzuje się tym trzema warstwami. Jej nazwa pochodzi od słów: Block, Element, Modifier.

    Block - dla mnie jest to komponent - taki byt, który można wydzielić do osobnego pliku i używać w wielu miejscach. Przykład: .person
    Element - to dziecko komponentu. Przykład: .person__title
    Modifier - to po prostu cecha elementu, informująca o jego obecnym stanie. Przykład: .person__title--active



MODUŁ 9
JS Modules (11 min)
00:00

Jak eksportować importować pewne rzeczy z modułów

named export

nowy katalog utis
index.js

cons hello-->
console.log(hello)

iport Hello from "./utils/helo"

exort deafault hello,


export cost hello
import {hello}from "./utils/helo"
defult wsczesniej decydowało jak to się nazywa
nawa taka jaka jest wewnątrz modułu

trzeci sposób
const hello=>console.log

export {hello};
 może być wiecej funkcji i np. stałę

export const name ="Wojciechu";
import {hello, name}from "./utils/helo"

export {hello", name}
plus
export deafault hellp;
import hello, {name}from "./utils/helo"


deafault eksportuje obiekt
export default {
  hello,
  name,}
import hello, from "./utils/helo"
hello.hello()
console.log(hello.name)
import nazwa dowolna from "./utils/helo"

można spotkać
export{hello, name}

jedną rzecz ekportujemy deafult
albo nigdy, można tak i tak

".?" kropeczka jeśli inportujemy nasze pliki

zmienianie nazwy eksportów i inportów
export{hello as goodbuy,name;
zamiast export {hello}
import {GODBAy} , from "./utils/helo"

default- dowolna nazwa

import wsztskiego
import * as hello from "./es"
np.
hello.hello(
  conslole.log(hello.name))

} , from "./utils/helo"]


console.log("przywitanie")
w tasks i app
wykona się dwa razy

to co wewn atrz modulu
console.log("przywitanie")
wykonało sie tylko raz

zarzadzanie modułami
ES6 wykonwywanie kodu tylko raz


MODUŁ 9
Więcej o zdarzeniach w DOM-u (14 min)
00:00

zarzenia
najechanie klaswisza, kliknięcie itp.
lniki- na końcu

spsoby obsługi zdarzenia

Tak! nie rób
<script>
  const hello =()=>{
      console.log("czesc");
  }
</sript>
<button onclick="hello()">Przyeiaj ię</button>
mimo, że działa  ma wiele wad
 onlcik mozemy co chcemy wpisac Java script

np.
<button onclick="console.log("czesc") ">Przyeiaj ię</button>
też będzie to działać

od double click

lepszy sposób
<button class=js-button">Przywitaj sie</button>

const Helleo =()
=>{
  conole.log("czesc");
}
const button = document.querySelector("js.button")
button.onclick = hello;
nie miezamy html z js. robimy to w JavaScirpcie
wielu elementom możemy orzypisać ten sam event hendler.nie przekzjue stringa, tylko po protu funckje.

04:40
można przekazać funkcję nonimową

 button.addEventListener("click", , () =>{
console.log("cześc")
 };

 można go także odpiąć, gdy już jest niepotrzebny

 button.temoveEventListener("click")
musi być ta sama składnia aby usunąć

listener nasłuchuje event
i wywołuje event handler, kiedy ten event wystĄpi

event.target

const buttosn= documennt.querySelectorAll(".js-button")
const hello = (event) => {
  const name =event.target.innertext;
  console.log("czecs ${name}");
}
for (const button of buttons){
  button.addEventListener("click", hello);
}

Restrukteryzacja
10:00

const buttosn= documennt.querySelectorAll(".js-button")
const hello = ({target}) => {
  const name =event.target.innertext;
  console.log("czecs ${name}");
}
for (const button of buttons){
  button.addEventListener("click", hello);
}

Event bubbling/delegation
po kolei zostająć wywołane event handlery elementó co raz wyżej w drzewie DOM

const section documennt.querySelectorAll(".js-section")
const hello = ({target}) => {
  const name =event.target.innertext;
  console.log("czecs ${name}");
}
section.addEventListener("click", hello);
}

Even hendler przyklejojny do sekcji a nie do poszczególnych przycisków.
EVen hendlery się orpalą jeden o drugim
kliknięcie nie na przycisk a w <section> tez włączy fukcje..

można zapobiec bublingowi
event.stopPropagation();

event capturing- od góy drezwa do dołu


    https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events
    https://developer.mozilla.org/en-US/docs/Web/Events
    https://developer.mozilla.org/en-US/docs/Web/API/Event
https://dom.spec.whatwg.org/#events


MODUŁ 9
Eventy w React (7 min)
00:00

Składnia marzenie mało wad
const Button = () =>(
<button onClick={(np. onDelet lub nic) => console.log("Czesc"}>
Hej
</button>
)

w reaccie nie robimy addevenlistener tylko onClick

po przypisanie np.
onClick ={onDelete}

const onDelete = () = >console.log("Kliknietow w przyciks");
<button clasName= "bla bla" onCLick={onDelete}

skłądnia marzeinie= nazy atrybutó CamelCase, przekazujemy funkcje nie string

 argumenty w even handlerach 
  const products = [
    {id:1, name: "dc"},
    (id:2, name: "asd"}
  ]
return{
  <ul>
    {products.map(({name, id}) => (
      <li key={id}>
        {name}
        <button onClick={() => removeProduct(id)} > usun</button>
        </li>
    ))}
    </ul>
    );

nawza zadania do sunięcia przez funkcj e strzałkową
cons onDelete = (name) => {
    console.log( `Nawza zdania do suniecia: ${name}`);
}
plus +++++

<button onCLick={()=> onDelete(task.content)>

albo np. co
const odDelete = (event)=>{
 console.log( `Nawza zdania do suniecia: ${name}`);
}


MODUL 9
React – useState (11 min)
00:00
const [count, setCount] = React.useState(0);
<COntainer> 
<p> Licznik: {count} </p>
<button onCLick={() => setCount(count + 1)> =+1 </button>

react hook
import React, {useState} from 1react`;
const [count, setCount] = useState(0);

zmienne stanowe
count i setCOunt możemy nazwać jak chcemy.

<button onCLick={() => setCount(count=>count+1)> =+1 </button>

04.29
jeśli nowa wartość ma zależeć od poprzedniej to przekazujemy funkcję

z każdą zminaą count reakt przerenderuje funkcję.

useState- jest to tak zwany HOOk
zaczepić podjąć się pod stan
wczesńiej były klasys
możemy tworzyć włąśne
zaczynaja się od use

wywołujemy funkcję wewnątrz komponentu
by zadeklarować zmienne stanowe
zwraca aktualną wartość i funkjcę, która ją aktualizuje.
jedyny argumnet to początkowa wartość
aktualizacja zmiennej stanowej powoduje render komponentu
pod warunkiem ze jest to inna wartos c i naczej nie ma to sensu dla Reacta
Use state możemy wywoływać wielokrotnie
zawsze przekazujemny nową tablicę , nowy obiekt inmutabliity
jak przekażemy ten sam obiekt co wcześniej to react nie przerenduje elmentu

Hooki wywołujemy tylko wewnątrz komponentów
zawsze na najwyższym poziomie
np. nie zagnieżdzamy wstrawiamy na samej góże.
zawsze w tej samej kolejnośći
najlepiej zaraz jak się rozpoczyna komponent


MODUŁ 9
React – Formularze (11 min)
00:00

Elementy formularza mają swój wewnętrzy stan wartość nawet w HTML
chieli bśmy mywybierali jak informacja jest w formularze.
Aby elementyw komponencie zmienych było ustalane przez nas
SŁuży do tego conroled components 

function App(){
const [name, setName] = useState("")
const onFormSubmit= (event) => {
  event.preventDefault():
  console.log(`Wysłano imnie1);
}

return(
<container> <form = {onFormSubmit}>
onSubmit
> 
<input value= {name} onCHange-{(event)=>setName(vent.target.value)}

<button>Wyślij </button>

</form> </onteiner
)}

Input stał się kontrolowany przez dodane do niego zmiennej name w wartości value.
event.target- ten element
+value= jego wartość.

Destrukturyzacja
<input value= {name} onCHange-{(target)=>setName(vent.target.value)}

consloe.log"Wyslano ${ssas}` 

04:43

mogę wykożystać name kolejny raz i wypiać go kolejny raz
np.
<p>
{name}
</P>

COntrolled components
tak nazywamy komponenty, których wartość jest kontrolowana przez React.
Przekazująć value, sprawiamy, ze input staje się komponentem kontrolowanym.
Dzięki temu w zmiennych stanowych mamy "Single source of truth"
nie ma co innego nigdize
zasze w tej sytuacji jest potrzebny on CHange

Textarea
<textarea value={contennt} onCHange= {onContentCHane}/> 
wstaw zamiast imput i wszytsko będzie takie samo. W tymżę wyśłe się to co wpiszemy w textarea.

Selelct
w html do options przekazujemy selected
W  reacie przekazujemy value 

function App(){
  const[age,setAge= useState("")
<form onSubmit = {onRormSubmit}>
<select value={age} onCHange = {onSelectCHange}
<option></optionM>
<option></optionM>
<option></optionM>
<option></optionM>
</select>
plus wyciągam przez target co jest zaznaczone

CHeckbox, radio 
tu przekazuje chcect
prawda fałsz

const [adult, setAdult] = useState(false)
const onAdultChange = ({target})=>{
  setAdult(targed.checked):
}
<input type="chcekbox" checked={adult} onCHange= [onAdultChange} /a>

const onAdlutCHange = () => {
 setAdult(adult =>!adult);
}


MODUŁ 9
Dodajemy interakcje do listy zadań (29 min)
00:00

Forumularze , zadrzenia , useSTate

const [hideDone, setHideDOne] = useState(false);
cosnt toggleHideDone = ()=> {
  setHideDone(hideDOne => !hideDone);
}

extraHeaderContent={
<Buttons tasks={tasks} hideDone = {hideDone} tooggleHideDOne= {toggleHideDone}
}

const Buttons = ({ tasks, hideDone, toggleHideDOne}) => (
<div></div
)

03:38
<buttons onClick= {toggleHideDOne} clasName "buttons_button">
{hideDOne ? "pokż:"ukryj"}
<buttons/>

nie zapomnij o importach i exportach
04:50
App.js

const[tasks, setTasks] = useState(
  {ide:1 content:"ed",done:false}
  {ide:2content:"ed",done:false}
)]

const removeTasks = (id) +=> {
  setTasks(tasks=> takks.filter(task==> task.id !==id));
}

<Tasks tasks={tasks} hideDone={hideDone} removeTask=={removeTask}
/>
<button className="css"

onClick={() => removeTask(task.id)}

przejmuje funkcje  remove 
const Tasks= ({ tasks, hideDone, removeTaskt, toggleTaskDOne, }) =>(
<ul className+tasks">
{tasks.map(task => ( 
  <li
  key= {task.id}
  className= {`task_item` ${
    tasks.done && hideDone
    ?" tasks_item-hidden"
    :""}`
  }
</ul>
07:50

const toggleTaskDone=(id) = =>{
  setTasks(tasks= tasks.map(task=>{
  if(tasks.id ===id) {
  return {...task,done: !task.done}:
}return task;
  }

10:59
<Tasks 
tasks= {tasks}
hideDone= {hideDone}
removeTask= {removeTask}
toggleTaskDOne= "toggleTaskDone"}
/>

onLick={=> toggleTaskDOne(task.id)

14:00
 ukoń wszytskie
 funckja która ukończy wszystkie zadania

 const setAllDone = () =>{
  setTasks(tasks=> tasks.map(task=>({...task, done: true})));
 }

<Buttons
 setAllDone={setAllDone}
 />
<button 

onCLick = {setAllDOne}
}
>
Buttons + setAllDane

"Dodaj zadanie"

18:05

const Form=({addNewTasks

)=> {
  const [newTasksContent, setNewTasksContenet] = useState(""):

return(<
form className= "form"
<input value = {newTasksContent} onChange {(event) => setNewTaskContent(event.target.valeu )
<button>
}
 
 19:21
skrócone, restrukturyzacja=
onChange= {(target) => setNewTaskContent(target.value)}

co ma się stanie po wysłaniu formularza
const onFormSubmit= (event) =>{
  event.preventDefault();
  addNewTask(newTaskContenet.trim())
setNewTaskContent("")

}

const addNewTask = ( Content)) => ) => {
  setTasks( tasks =>[
  ...tasks,
  {
  content,
done: false
id:tasks.lenght === 0 ? 1: tasks[tasks.lenght -1].id +1,
id:tasks.lenght ?tasks[tasks.lenght -1].id +1 : 1
  }

<section
title= "dodaj nowe zadania"
body= {<Form addNewTask= {addNewTask} />
/>
24:00
   "dodawanie niwyc zadań"

   
   MODUŁ 9
   Prace domowe (2 min)
   00:00

   Dodaj interakcje do listy zadań
   Przeniś kalkulator walut do reacta

   MODUL 9
   Wskazówki do prac domowych (5 min)
  00:00

  Licznik walut
  Odziel warstwę danych od warstwy prezentacji
  Nie przechujemy wartość ,przy końcu ją renderujemy
Na zdarzenia submit a nie input
Jęsli masz kilka walut, stwóż tablicę
Mogę użyć ją do wyrenderowania
Tablicyużyj do wyrenderowania radio butons lub opcji w select
Możesz ją umieścić w osobnym pliku
tej samej tablicy użyj do obliczania wyniku- już nie potrzebujesz switch
pamiętaj o key
nazywaj odpowiednio resukt, setResult

MODUł 10
Prace domowe z poprzedniego tygodnia (28 min)
00:00

if(newTaskContent.trim === ""){          
 return;
}
jeśli dodaje się do zadania pusty string to zadanie się nie dodaje.

trim - usowanie białych znaków.

const contentTrimmed = (newTaskContent.trim

if(contentTrimmed ===""  ){
 return;
}

addNeTask(contentTrimmed);

if( !contentTrimmed ){
 return;
}
pusty łańcuch znaków działa jak false.


Przeniesienie kalkulatora walut do Reacta
css dodal do elementu #root 
zdecydował się dodać style do tego elementu d
do niego cały react jest wstwiany.
Rozbudowany boddy ip. zamiast do body to do root

App
Index.js

setResult({
  sourceAmount: +amount
  tragetAmount: amount / rate,
  currency
});

const calkulateresult = (currency, amount) =>{
  const rate = currencies
  .find({short }) => short === currency)
  .rate;
}

do zampamietania funkcja find()

return(
<div>
<Form
  result= {result]
  calkulateResult = {calculateResult}
</div>

domyślna waluta
cons[currency , setCurrency] = useState(currencies[0].short);
cons [amount, setAmount] =useState("");

10:13
onCHange = {({  target  }) => setCurrency(target.value)}

{currencies.map((currency => (
<option 
  KEY={currency.short}
  value = {currency.short}

  {currency.name}

  </option>

  Result wewnątrz form
  <Result result={result} />

   export cons Result = ({ result }) => (
   <p className="result">
    {result !== undefined && (
    <>
    {result.sourceAmount.toFxed(2)}&nbsp;PLN&nbsp;=
    {""}

        <strong.
          {result.targetAmount.toFixed(2)}&nbsp;{result.currency}
          </strong>
          </>    
    )  
   )
 13:27
generycznie
czyscimy ostrzeżenia na konsoli

upraszczanie !! rzutpwanie na boolina
18:15

gdy funkcj a ma wykorzystac stałą starą wartość to porzekazjuemy fuckję

setResult
przekazujmey fukcje nie obiekt.
Funkcja zwrocic nowy obiekt.

funkcje tlko do obliczen a nie reprezentacji elementów.

jak result jest obiektem to niech bedzie obiektem
nie mieszajmy

Tak nie robimy
 {Result({result})}
 a tak robimy:
<Result result={result} />

jak używamy czegoś co jest komponentem to możemy użyć useState


MODUŁ 10
 praca z datami i godzinami (18 min)
 00:00

new Date() tworzy obiekt z atulana datą co do wywołania

const myDate = new Date();
myDate.toString() --inny format razem ze strefą czasową

myDate.getFullYear()
myDate.getSeconds()
myDate.setHours()

const myBirthday = new Date(2025, 0, 12, 14, 12, 25);
myBirthday

newDate("") - nie polecanenie ma osobnego typu dla dat- jest obiekt Date
obejmuje i datę i czas
ma wiele przydatnych metod, któe pozwalają na m.in pobieraż lub ustawiać frag\enty dat i czasu
nie ma żandych właściowości

Jak przechowywana jest data? 
liczba milisekund, które minęły od północy 1 stycznia 1970 roku

różne argumenty date.

Pobieranie i ustawianie fragmentó dtay i czasu.

getDate, setDate - dzień miesiąca (1 - 31)
getFullYear, setFullYear - pełen rok
getHours, setHours - godziny (0 - 23)
getMilliseconds, setMilliseconds - milisekundy (0 - 999)
getMinutes, setMinutes - minuty (0 - 59)
getMonth, setMonth - miesiąc (0 - styczeń, 11 - grudzień)
getSeconds, setSeconds - sekundy (0 - 59)
getDay (tylko get) - dzień tygodnia (0 - niedziela, 6 - sobota)

getTime - liczba milisekund od 1 stycznia 1970. UTC
przydaje się do porównywania

const date1= newDate(2025, 0, 12,12,14,15)
const date2 = new Date(2025,1,5,11,12,10)

date2.getTime() - date1.getTime()

const secondsDifference= (date2.getTime() - date1.getTime()) /1000
const daysDifference = secondsDifference / 3600/ 24

Date.now() - statyczna
11:32

const date = new Date()
date.toLocaleString()
date.toLocaleString("de-DE") dla niemiec
date.toLocaleString("en-US") Stany zjednoczone

date.toLocaleTimeString()
date.toLocaleDateString()

date.toLocaleDateString("en-US, {weekday: "long", day:"numeric", month:"long", year: "numeric"})

date.toLocaleDateString("pl", {weekday: "long", day:"numeric", month:"long", year: "numeric"})

to ISOString()
date.toISOString()

cos newDate = new Date (toISOSTRING)

date-fns.org


MODUŁ 10
JS – zegar czyli setTimeout i setInterval (16 min)
00:00
asynchroniczność 
operacje nie beda odpalaly się jedna po drugiej w odpowiedniej kolejności
albo co jakiś w niekończonośći

setTimeout(() =>{
console.log("Wypisuje ten teksto po sekundzie");
},1000
}
pierwszy argument to funkcj awywołana za jakiś czas
a drugi 

<body>
  <button class= "js-button">Pokaż komunikat<?bytton>
  </body>

document.querySelector(".js-button").addEventListener("click", () => {
  setTimeout(() => {
    alert("kiknąłeś w przycisk 2 sekundy temu");  
  }, 2*1000);
});

function showAlert(){
alert("dsd")
}

document.querySelector(".js-button").addEventListener("click", () => {
  setTimeout(showAlert, 2*1000);
});


Kolejność wykonywania kodu
console.log("a);

kody sie mieszja i wykonują według ścisle ustalonegio czasu.

przy 0 timeout traci koejność

Podany czas nie jest gwarantowany
kod może wykonać później
podana funkcja zostanie wywołana dopiero, kiedy wykona się kod z głównego wątku

Anulowanie timeoutu
const timeoutId=
setTImeout(() =>{
  console.log("sdw");
}, 5000;

Timeout zwraca id , które można przypisać do stałej
 clearTimeout

function clearTimeout(handle? : number): void
clearTimeout(timeoutId)

setTimeout(() = {
  clearTimeout(timeoutId);} 
  ,1000
  )


setInterval
wykonuje podaną funcje wielokrotnie w podanym interwałem
setInterval(() => {
  console.log("hej");
});
nadpisuje wartość

let counter=1;
setInterval(() => {
  console.log(counter);
  counter= counter+1
}, 500);

const intervalId = setInterval(() => {
  console.log(counter);
  counter= counter+1
}, 500);
setTimeout(() =>{
clearInterval(intervalId);
}, 5000);


Reukrencyje timeouty

let counter=1;
Kod trwa dłużej niż interval
showCounter = ()=>{
console.log(counter++)
setTimeout(showCounter,1000)
}
rekurencja. Wewnątrz funkcji wykonujemy tą samą funkję.
Asynchroniczość, rzeczy nie wykonuują sie po kolei.
np. Jedna w czasie na inną.


MODUŁ 10
JS – Storage i ciasteczka (18 min)
00:00

Zapisywanie czegoś po stronie uruztkownika. Na stałe
Client-side storage.
jest wiele sposobów na to

Strona się szybciej ładowała. Działała off line

Przechowujemy
ustawienia użytkownika
Informacje o zalogowanym użtkowniku
personalizacja np. wybrany motyw
koszyk zakupów 
itd.

localStorage
prosta składnia do prostych danych
przechowuje dane na stałe

Zapis
localStorage.setItem("theme", "dark");
wartości są stringami

odczyt
const theme = localStorage.getItem("theme"); 

gdy nie ma wartosc , metoda getitem zworoci null
usuwamy
localStoage.removeItem("theme");

  const myArray = [5, "etd", {"scasc": "dwd"}];

  myArray --zwraca tablicę 
JSON.stringify(myArray) - dostanę string, który jest reprezenatacją tej tablicy.
odwracanie
JSON.parse( '[5, "etd", {"scasc": "dwd"}]')
zwraca spowrote tablicę.

const products = [
    {
    name: "lapto"
    price: 19999
  }
   {name: "sx"
   price: 1300
   
   }  
]
zapis w local storage

localStorage.setItem("products", JSON.stringify(products))
gry pobierzemy
localStorage.getItem("products")
zwrac string

JSON.parse(localStorage.getItem("products"))
zwraca tablicę

sessionStorage
przechowuje dane do wyłączenia przeglądarki

sessionStorage.setItem("klucz","wartosc");

Storage jest dla konkretnej domeny.

Cookies
istnieją prawie od początku , są używane do przechowywania sesji użytkownika, czesto wykorzystywane do śledzenia użytkownika.

Nagłówek HTTP Set-Cookie
Może zostać wysłany w odpowiedzi z serera
Wartość jest później wysyłana w każdym żądaniu.

Set-Cookie: sessionId=sadsd;Max-Age=112
używane aby określić czy dwa różne żadania są z jednej przeglądarki
Cookie są wysyłane w każdym żądaniu
Cookie: name=JS; theme=dasx

możemy ustawić cookie za pomocą Java Scriptu
document.cookie= "ciasteczko=malinowe" zapisanie
document.cookie - zwraca string zapisanej wartości. 
document.cookie= "ciasteczko=mowe" zapisanie
document.cookie - string przedzielony spacją i średnikie z dwóch zapisów

 3rd party cookie - kuki osób trzecich

ciasteczka są regulowane prawnie


MODUŁ 10
React – useEffect – efekty uboczne (16 min)
00:00

efekty uboczne 
React: useEffect

Effect Hook - potrzebny do zarządzania side effectami
np.
pobranie danych z serwera po pierwszym wyrenderowaniu komponentu
trzeba pobrać noew dane przy nowych propsach.
np. ich filtrowanie
ręczna zmiana czegoś w drzewie DOM
aktualizacja tytułu strony
logowanie czegoś po każdym renderze
zapis w localStorage
 
 funkcja renderujaca nie powinna powodować żadnych fektów ubocznych
 dlatego potrzebujemy useEffect

function App(){
const [count, setCount] = useState(0);

return (<>
<p>
licznik {count}
</p>
}
 <p>
<button onClick={()setCount(count=> count+1)}+1
</button>
 </p>

umiezczony nad 
import React, {useState, useEffect} from 'react'
useEffect(() =>{
document.title= 'Licznik: ${count};
}

jak działa useeffect
dajemy znać reaktowi że ma coś do zrobienia po aktualizacji DOMU
dodająć efekt

React zapamiętuje przekazaną przez nasz funkjcę i w odpowiednim momencie ją wywoła
Dzięi temu, że dodajemy efekt wewnątrz komponentu, mamy dostęp do props i do wewnętrznego stanu
nasz efekt miał dostę do zmiennej stnu count.
domyślne efekty wywołuje się po każdym renderze.
dane mogą się nie zmienic po renderacji z rodzica

Optymalizujemy wydajność 
tablica zależności
07:08
useEffect(() =>{
document.title= 'Licznik: ${count};
}, [count]); 
gdy będzie równy count to już się nie wyrebderuje 
poprawia to wydajność

możemy przekazać tablicę zależnośći
wtedy efekt zostanie wywołany tylko wtedy, kiedy któraś z przekazanych wartośći się zmieni
wartośći są porównane płytko pamiętaj o immutability
pmiętaj by w tej tablicy umieścić wszystkei wartości, od których zleży efekt
jeśli nie dodasz jakiejs zalezność to beda widzianne stare wartości

const[name, setName]= useState(0)
<input value= {name} onCHange= {({target})} => setName(target.value)}

setCount i setName nie muszą być ponownie przypisywane

11:16
useEffect(()=>{
  setInterval(()=>{
  setCount (count=>count +1);
  }, 1000);
  },[]);
Pusta tablica zależności , efekt będzie wywołany tylko raz.

Sprzątanie
Ogołnie gdy są jakieś nie potrzebne już komponenty itp.

wewnątrz efektu dajemy
return()=>{
  clearInterval(efektktóry czyścimy);
};
},[]);

w tej funkcji zwracana jest funkcja sprzatająca. Usunięty z drzew DOM
możemy dodać kilka różnych komponentów.


MODUŁ 11
Prace domowe z poprzedniego tygodnia (10 min)
00:00

LocalStorage
po odświerzeniu strony. Zostaje poprzednia strona

useEffect(() =>{
  localStorage.setItem("tasks", JSON.stringify(tasks));
})
jest to zapis


const tasksFrom.LocalStorage = localStorage.getItem("tasks");

const [tasks, setTaks ] use State(
  tasksFromLocalStorage
  ? JSON.parse(tasksFromLocalStorage)
  : []
)

useState pozwala na przekazanie funkcji

nad App
const getInitialTaks = ( )=> {
const tasksFrom.LocalStorage = localStorage.getItem("tasks");
return tasksFromLocalStorage
  ? JSON.parse(tasksFromLocalStorage)
  : []
}

const[tasks, setTasks] = useState(
getInitialTasks
)

04:00 
komitowanie
nie rozpraszaj logiki po różnych komponentach
odczytywanie i zapisywanie w jednym komponencie by było nawet bardziej logiczne

Dodaj do kalkutarira datę i godzinę.
nowy komponent clcock

zmienna stanu
const [Date, setDate] = useState(new Date());

useEffect(() =>{
const intervalId = setInterval(() =>{
      setDate(newDate());
      },1000);
      
      return ()=> {
        clearInterval(intervalId);
          };[])

return(div className="clock">
Dzisaj jest
{""}

{date.toLocaleString(undefined,{ - 
  weekday: "long",
  hour: "2-digit",
  minute: "2-digit",
  second: "2-digit",
  day: "numeric",
  month: "long"
})}

+styleCss className .clock
w JSS {""} spacja wygląa tak
undefinded -kązdy zovaczy zgodnie z ustawieniami swojego systemu oeracyjnego.

import 
w clasName= App
<Clock/>

inny spsób
08:00 


const formatDate = (date) => date.toLocaleString(undefined,{ - 
  weekday: "long",
  hour: "2-digit",
  minute: "2-digit",
  second: "2-digit",
  day: "numeric",
  month: "long"
})}

po {""}
{formatDate} 

w div classname"clock"
Dzisja jest {" "} {formatDate(date)}

nie przechowuje w pamięci już sformatowanej daty.
Odzielam warstwe widoku ood warstwy jak sa przechowywane.

return(
  <div className="clock"
    Dzisja jest
    {" "}
    {formatDate(date)}
  </div>
)

dodaj wartośc domyślną do daty bo incazej będzie opóxniona o jedną minutę


MODUŁ 11
Więcej o npm-ie (14 min)
00:00

ode package manager
pozwala na zarządzanie zależnościami w projekcie
pozwala na ałtwe aktualizowanie paczek
składa się ze strony interentowej, klienta oraz rejestru

https://www.npmjs.com/

linia komnend npm instalowany jest raem z nodem

package.json
zawiera meta dane na temat naszego projektu
zawiera skrypty NPM np. build, run start, sami dodaliśmy deploy
zawiera listę zależności
npx create-react-app my-app używanie paczki nie instalując jej.

inicjalizacja package.json
npm init
#domyślne wartości
npm init -y
tworzy pakiet zadając pare pytań

npm init
npm init -y    -stworzy packjson z domyślnymi wartościami
npm install nazwa-paczki  -instalacja paczki w projekcie

funkcja do formatowania dat.
npm install date-fns
w node module\date-fns
jest także plik package-lock.json - jakie paczki zostały zainstalowane
inna paczka np. npm install react
w node_modules - jest wiele innych rzeczy
react ma swoje trzy dependencies
w package.json są teraz w dependeniec dwie biblioteki:date-fns i react

zależności tylko potrzebne do developmentu
narzędzie do testowania kodu, webpack, narzedzia do analizy kodu
coś czego nie potrzebuja nasz aplikacja kiedy jest już uruchomiona.
npm install webpack --save-dev
 w devDependencies pojawi się webpck z nazwą jego wersji.

usunięcie zależńości
npm uninstall nazwa-paczki
np.
npm uninstall webpack

instalacja na podstawie package.json/ package-lock.json
np. kiedy pobieramy repezytorium z gibhuba
npm install - np. popobraniu repozytorium z GitHUba, zainstaluje wszystkie paczki , które są potrzebne.

semantic versioning
3.12.15 - major.minor.patch
major - duza zmiana najczęscie niekompatybilna wstecz
minor- kompatybilne wstecznie nowe funkcjonalności
patch- poprawione bugi
^ - akceptacja wyższych wersji
13:46


MODUŁ 11
React – useRef (9 min)
00:00

Focusowanie inputa

znamy już
UseEffect i Use states
zwraca zawsze ten sam obiket z właściwością current.
w pierszym argumencie początkowa wartość dla current
przydaja się przy przechowywaniu jakiejś wartości, ale nie chcemy, by jej zmiana powodowała ponowny render
do tgeo jest usestate.
wartość pomiędzy renderami useRef

pudełko w którym przy włąsciwości current coś przechowujemy.

import React, {useState, useEffect, useRed} from 'react';

function App(){
  const[counter, setCounter]= useState(0);
const interval Ref = useRef(null)


  useEffect() =>{
    intervalRef.current= setInterval (()=>{
      set.Counter(counter => counter+1)
}, 1000);
}, []);

const stopCounter = () =>{
clearInterval(intervalRef.current)


}

return(
<>
<p>{counter} </p>
<button onClick= {stopCounter"}> Zatrzymaj licznik </button>

</>
);
}

zły sposób

function App(){

const focusInput = () => {
  document.querySelector("input").focus();
}

return(
<>
<p><input </p>
<button onClick= {focusInput}> Ustaw fokus na input </button>

</>
);
}}

tą odpowiedzialność dajemy reactowi.
useRef ma złapać


function App(){


const inputRef = useref(null);

const focusInput = () => {
 inputRef.current.focus();

return(
<>
<p><input ref={inputRef} </p>
<button onClick= {focusInput}> Ustaw fokus na input </button>
</>
);
}}

Dokumentacja Reacta.


MODUŁ 11
React – własne hooki (17 min)
00:00
Jeśli chcemy wyciągnąć jakąś logikę komponentu na zewnątrz.



function App(){
  const[counter, setCounter] = useState(0);
return(
<>
<p>{counter}</p>
<button onClick ={() => setCounter(counetr +1)}> Zwiększ licznik</button>
</>
)
}

Za każdym razem licznik ma się pojawić w tytule.

function App(){
  const[counter, setCounter] = useState(0);

  useEffect(()=>{
    document.title = 'licznik: ${counter}';
  }, [counter]);

return(
<>
<p>{counter}</p>
<button onClick ={() => setCounter(counetr +1)}> Zwiększ licznik</button>
</>
)
}

Mogę zamknąć wszytsko w nowym hooku.

const useDocumentTitle = (counter)=>{
  useEffect(()=>{
    document.title = 'licznik: ${counter}';
  }, [counter]);
};

function App(){
  const[counter, setCounter] = useState(0);
useDocumentTitle(counter);

return(
<>
<p>{counter}</p>
<button onClick ={() => setCounter(counetr +1)}> Zwiększ licznik</button>
</>
)
}

Dalej.........!

const useDocumentTitle = (counter)=>{
  useEffect(()=>{
    document.title = 'licznik: ${counter}';
  }, [counter]);
};

function App(){

const getInitialCounter=()=>{
const localStorageCounter= localStorage.getItem("counter");
if(localStorageCounter === null){return 0}
}
return JSON.parse(localStorage.getItem(""));

const[counter, setCounter] = useState(getInitialCounter);

useEffect((=>{
  localStorage.setItem("counter", JSON.stringify(counter))},
  [counter]);
}

useDocumentTitle(counter);

return(
<>
<p>{counter}</p>
<button onClick ={() => setCounter(counetr +1)}> Zwiększ licznik</button>
</>
)
}


i Dalej !!!!!!!!!!!!!

const useDocumentTitle = (counter)=>{
  useEffect(()=>{
    document.title = 'licznik: ${counter}';
  }, [counter]);
};

<divek>

const useLocalStorageState = (keyName, initialValue) =>{
const getInitialState=()=>{
const localStorageCounter= localStorage.getItem(""keyName");
if(localStorageCounter === null)
{return initialValue;
}
}
return JSON.parse(localStorage.getItem("keyName"));

const[state, setState] = useState(getInitialCounter);
useEffect((=>{
  localStorage.setItem("keyNamer", JSON.stringify(counter))},
  [counter]);
  return [counter, setCounter];
}

<divek>

function App(){


const[counter, setCounter] = useLocalStorageState("counter", 0));
};
const[anotherData, coś innego] =useLocalStorageState("canotherData"));
 

 useDocumentTitle(counter);

return(
<>
<p>{counter}</p>
<button onClick ={() => setCounter(counetr +1)}> Zwiększ licznik</button>
</>
)
}

w Recacie w osobnym pliku i nadaj całości Export

const[dimensions, setDimensions] = useState(
  


)

funvtion App()
  const [ dimension, setDimensions] = useState({
    width: window.innerWidth,
    height: widow.innerHeight,
  })

const upDateDImensions= = () =>{

  setDimensions(){
  width: window.innerWidth,
    height: widow.innerHeight  
  }

}

useEffect(() => {
x
}, []);


return(
<>
Szerokość : {dimensions.width}
Wysokość: {dimensions.height}<br/>
</>
)


Custom hook :::::::::::

const useWindowDimensions = () =>{
window.addEventListener("resize", updateDimension");

return() => {
  window.removeEventListener("resize", updateDimension)
  };
}, []);
   
   return dimensions:
   };

function App(){
const dimensions = useWidowDimensions()


hooków używamy na samej górze.
od nas zależy jakie hook przyjmuje argmenty i co zwraca
nazwę zaczynamy od use
powstaja funkje wielokrotnego uzytku
wyciagamy logike komponentu za zewnatrz

tablica zależności

import React, { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log('Ten efekt uruchamia się tylko raz, po początkowym renderowaniu.');
    // Tutaj można pobrać dane z API, ustawić nasłuchiwacze zdarzeń itp.
  }, []); // Pusta tablica zależności oznacza, że efekt uruchomi się tylko raz

  return <div>Mój komponent</div>;
}

useEffect(() => {
  // Kod efektu, który zależy od `id`
  fetch(`api/users/${id}`)
    .then(response => response.json())
    .then(data => {
      // Ustaw stan
    });
}, [id]); // Efekt uruchomi się ponownie, gdy `id` się zmieni


useEffect(() => {
  document.title = `Użytkownik: ${props.userName}`;
  return () => {
    document.title = 'Domyślny tytuł'; // Opcjonalne czyszczenie
  };
}, [props.userName]);


import React from 'react';
import useCounter from './useCounter'; // Zakładając, że hook jest w pliku useCounter.js

function CounterComponent() {
  const [count, increment, decrement] = useCounter(5); // Zaczynamy z licznikiem od 5

  return (
    <div>
      <h1>Licznik: {count}</h1>
      <button onClick={increment}>Dodaj</button>
      <button onClick={decrement}>Odejmij</button>
    </div>
  );
}

export default CounterComponent;


jsx

import { useState } from 'react';

// Hook do przełączania wartości boolowskiej
export function useToggle(initialState = false) {
  const [state, setState] = useState(initialState);

  const toggle = () => setState(prevState => !prevState);

  return [state, toggle];
}




Powtórka..............Powtórka


MODUŁ 11
React – useState, useEffect – pułapki (6 min)
00:00

const incrementCounter =()=> {
setCounter(counter+1);
}
const[counter, setCounter] = useState()

<div>
{counter}
<p><button onClick={incrementCounter}>+1
</button>
</div> 

wykona się dopiero po renderze. Zadziałą asynchronicznie
Informacja do Reacta aby po renderze ustawił COunter

  uSeEffect(() => {
  tutaj counter by miało swoją pocżatkową wartość
    setInterval(()=>{
    setCounter(counter => counter +1); samo setCounter(counter+1) jest błędem. Mogło by mieć nawet inną nazwę
    }, 1000
    }, [];
może przyjąć ciunter, ale równierz funkcję
jest wyświetlany tlko raz
to nie jest to samo counter w tablicy hookowej
w tablicy jest najbardziej aktulany counter funkcji renderującej.
ale, ten efekt jest rejestrowany tylko raz.
znavczy się w useEffect. set counter  nim mógłby mieć nawet 
w set counter inną nazwę

Ogołnie jak mamy hook counter jest to najswieszyc counter
po niej tworzymy nową funkjcę incrementCounter.
Najbardziej aktywny counter w funkcji renderującej


const incrementCounter = () => {
setCounter(counter+1);  - a ten efekt jest wywoływany tylko raz
};

=tutaj wszystko zadziała. Mamy zawsze najnowszy counter przy renderyzacji
i tu tworzy się nowa funkcja incrementCounter . Tu się nie obawiamy
o czy będzie działać. 
a wewnątrz efektu trzeba o tym pamiętać
setCOunter(previousCounter)

MODUŁ 11
Styled Components (36 min)
00:00

Style do komponentów react
 
npm install styled-components

 import styled from "styled-components";

const Button = styled.button''; może być div, itp . Temple strings jeśli chodzi o ""

const Button = styled.button'
  border: 1px solid teal
  bos-shadow: 0 0 2px #ccc;
  padding: 10px
  margin: 10px
  background: white;
  color: teal;

  ${() => }
';

function App() {
  retutn(
    <button> pRzycisk </button>  
  )
}
export default App;

button styled jest umieszczone nad app. poza funkcją renderującą.

import styled, {css} from "styled-components";

const Button = styled.button'
  border: 1px solid teal
  bos-shadow: 0 0 2px #ccc;
  padding: 10px
  margin: 10px
  background: white;
  color: teal;

  ${(primary) => primary && css'
   background: teal;
   color: white;
  '}
';


function App() {
  retutn(
    <button> pRzycisk </button>  
     <button primary> Główny przycisk </button>  
  )
}
export default App;

modyfikator w BMIE


możemy przekazać także innaczej. Tu np. kolor.

const Button = styled.button'
  border: 1px solid teal
  bos-shadow: 0 0 2px #ccc;
  padding: 10px
  margin: 10px
  background: white;
  color: ${(color) => color || "teal" };

     <button color="red"> Główny przycisk </button>  

to jest zwykły Java Script

myFunction(["mam imie", "sas"], imie);


Jak styled components działają.
dod dokumentu dynamicznie są przekazywane style potrzebne.4
Tylko wyrenderowanym obecnie komponetom
Komponenty otrzymują automatycznie wygenerowane inikalne nazwy klas.
Łatwo usunwać.
Kiedy już nie potrzebujemy komponentu, usówamy tylko jego style.
Bazująć na propsach możemy renderować inne , różne style.
DO styló automatycznie są dodawane prefixy, by wspierać starsze przeglądarki.

const Button = styled.button'
  border: 1px solid teal
  bos-shadow: 0 0 2px #ccc;
  padding: 10px
  margin: 10px
  background: white;
  color: teal;
  text-decoration: none;

constPrimaryButton. = styled(Button)' 
 tutaj dodaje CSS napsiane lub dodane
  backgorund : teal;
  color: white;

  '

     <Primary button> Główny przycisk </PrimaryButton> 

 16:27
Extend

ZMiana znacznika html.

  <Primary button> Główny przycisk </PrimaryButton> 
   <Primary as="a" href= "https"> HTTPS </PrimaryButton> 


const Button = (className) =>
(
  <button className={className}>Przycisk</button>
);
const StyledButton. = styled(Button)' 
  backgorund : teal;
  color: white;

komponent musi przekazać class name.

<StyledButton>Przycisk</StyledButton>


const StyledButton. = styled(Button)' 
  backgorund : teal;
  color: white;

  &:hover{
      background: teal;
      color:white;
  }

można zwiększyć specyficzność

&&{

   &:hover{
      background: teal;
      color:white;
  }
  @media(max-width : 767px){
      display: block
      margin: 0;
      width: 100%
  }
}

^^^
media querises 
^^^^^

Theme
motyw, różne obiekty, motywy. COlory, breakpointy itp.

const theme = {
  colors: {
    primaryColor : "teal",
      }
  breakpoints: {
mobile: 767

  }
}

co zrobic z theam aby był widzialny

import styled, {ThemeProvider} from "styled-component";
aplikacja musi być w TP opakowana
<ThemeProvider theme= {theme}>
  <StyledButton> przycisk </StyledButton>
  </ThemeProvider>

const StyledButton = styled(BUtton)
  color: ${(props) => props.theme.colors.primaryColor};
destrukturyzacja
  color: ${(theme) => theme.colors.primaryColor};

@media(max-width: ${({theme})=> theme.breakpoints.mobile}px) pobieranie wartość z innej zmiennej

<ThemeProvider theme = {theme}>

Theme wykorzystyujemy zęby w jednym miejscumiec kolory, odstepy, rozmiary tczionek.

Utwórz
styled.js

import styled from "styled-componenets";

export tasksList = styled.ul'
  list=style: none;
  margin: 0;
  padding: 0;
';

import {TasksList} from "./styled"
 <TasksList> </TasksList>

export const Item = styled. li'
list=style: none;
  margin: 0;
  padding: 0;

${({hidden}) = hidden && css
  display: none;

}
';

import

import styled, {css} from "styled-components";
import { list, Item, content} from "./styled":

<Item
    key={task.id}
    hidden= {task.done && hideDone}
   ></Item>


export const Content = styled.span '
${({done})} => done && css
text-decoration: line-through;
  }
';
       
<Content done={task.done}>
{task.content}
</Content>

export const Button= styled.button '
border: none
color:white

${({toggleDone})=> toggleDone && css
' background: hsl(120, 61%, 34%);
';
&:hover{
background: white
}

  ${({remove})}=> remove && css
      background: hsl(120, 61%, 34%)

      :hover{
        background: hsl(120, 61%, 34%)
        
      }

import { list, Item, content, Button } from "./styled":
<Button
toggleDone
onCLick={()} => toggleTaskDone(tasks.id)>

<Button remove>

const{
  tasks
  removeTask,
  toggleTaskDone
} = useTasks();

[] - nie zależność od niczego
https://styled-components.com/docs/basics\

setCounter(counter => counter + 1) jak funkcja bo inaczej nie zwróci wartości.


MODUŁ 11 

use efekty- obejrzane
ude ref - obejrzane
js storage i ciasteczk- obejrzane
use Ref- obejrzane
Własne hooki-obejrzane
useState , use ree=f - pułapki- NIE


MODUŁ 12
Prace domowe z poprzedniego tygodnia (22 min)
00:00

Styled components

osobny plik theme.js
xport const theme= {
  color: "",
  silver: ""
  teal: ""
  kolory używane
}

breakpoint: {
  mobileMax: 767
}
}

skończona lista koloró 
name that color wwww index js importuje theme
import { theme } from "./theme";
import { ThemeProvider } from "styled-components";

 użycie

index.js
<React.StrickMode>
  <ThemeProvider theme = {theme}>
    <GlobalStyle>
      <App />
  </ThemeProvider>
</React.StrickMode>
 document.getElementById('root')
);

export const Button = styled.button
  background: transparent
  margin
  color ${({theme})=> theme.color.teal};
  transition

  @media(max-width: 767px)
  ${({theme})=> theme.breakpoint.mobilemaxl};
  {
      flex-basis: 100%
      margin: 10 px
  }


nie style w jednym miejscu tylko style components
import { createGlobalStyle } from "styled-components";

export const GlobalStyle = createGlobalSyle
html{
  box-sizing: border-box;
}
*, ::after, ::before{
  box-sizing: inherit;
}

body{
  font family: 'Monserrat'
  background ${({theme})=> theme.color.gallery};
}
zostanie to dodane do aplikacji

w index.js
import{ GlobalStyle } from "./GlobalStyle";
po imporcie wstawiam nie ważne w którym miejscu

<GlobalStye/>

w innych..
import { Wrapper, Button] from "./styled";}

<Wrapper>
<STyledform>

npm install style components











MODUŁ 12
JS – obsługa błędów (try, catch) (15 min)
00:00

Try- sami możemy zrobić błąd
Coś będzie zignorowane

try {
  throw "";
  coST - DALEJ NIE SIE NEI WYKONA POZA CATCH
} catch (rror){
  console.error(error)
}
}

inaczej
nie złapany błąd prze catch

throw - służy do rzucania błędów
przekazujemy wartość, która ten błąd opisuje.

np. funkcja która da różńą wartość od chcialnych wywala błąd , któy zamieniamy na jakąś wartość.
rzucam błędem

obsurzony jest błąd
 finally- które maja się wykonać po. np. coś posprztać, zaknąć plik, itp.


MODUŁ 12
Format JSON (14 min)
00:00

Fomat zapisu danych 

"page": 3,
"books":[
  {
      "id":1,
      "title": "Some title,
      "active" : false
  }
{
    "id": 2,
    "title": "Another title"
    "author" : null
}
]
wygląa tak jak obiekt
tylko stringi i właściwośći muszą być w cudzysłowach
i nie dodajemy przecinków na końcu
jeden błą, to jeden JSON cały jest nieprawidłowy

typy: liczba , boolin, string, tablica, obiekt
roszerzenie json

JSON jest strigiem, nie można zapisać funkcji.
Bazuje na sposobie zapisu obiektów w JS-ie
powszechny przy wymianie danych.
 uzywamy go gdy pobieramy jakieś dane z serera itp.
nie zależny od platformy
mogą być w nim zapisywane konfiguracje
nie ma undefind, wyrażeń regularnych, dat itp.
jeśli chcemy zapisać date to zapsiaujemy ją jako ISO string
nie ma NaN, infinity oraz zer na początku liczby.
np. 05 nie można trzeba 5

KOnwertowanie z i do JSON
możemy konwertować różńe wartości
jak mamy JSon z którego chcemy dane to musiemy go np. skonwertować do JS
jak wysyłamy dane do serera to obiekt musimy zapisać jako JSON

Parse i stringify
 Parse n JS
 Stringify na JSON

const data = JSON.parse('{ "title": "Gwiezdne Wojny"}')
 JSON.parese('{"property": 5}')
to zamienia na obiekt
JSON.parese('false') - to zamienia na bulina
JSON.parese('null) - to zamienia na null, , {nie string
JSON.parese('[]') - to zamienia na tablicę
JSON.parese('[{}, {}]') - to zamienia na tablicę obiektów.

jeśłi jest błąd to parse rzuci błęem-SyntaxError
 
console.log(JSON.parse('{ "property":5}')
zamienia  na obiekt

try{
  onsole.log(JSON.parse('{ "property:5}')
}catch (error)
{
  console.log("to jest błą")
}

const isValidJSON =json => {
    try{
      JSON.parse(json);
      return true;
    } catch(error) {
return false
    }
};
czy JSON jest prawidłowy 

JSON.stringify
const jsonString = JSON.stringify({ title: "Gwiezdne Wojny "});
konwertuje wartość JS na JSON string

Przykłądy
JSON.stringify(null) zwróci string "null"
ogólnie zwraca string

w JSON nie ma Undefinded
    
const object1 = {};
cosnt object2 = {};

object2.object1 = object1;
object1.object2 = object2;

jeden i drugi obiekt zawiera własciwość któa odnosi się do drugiego obiektu.
nie skonwertujemy tego na JSON.

serializacja


MODUŁ 12
JS – XMLHttpRequest, Fetch, Axios (23 min)
00:00

Będziemy pobierać dane z serwera za pomocą tych trzech metod.
Jak wysłać w body. Unikamy przeładowywania całych stron.
  
AJAX- asynchronous JS and XML
technika budowania kompleksowych, dynamicznych aplikacji
oparta na aktualizowaniu tylko części DOMU-u na podstawie danych z serewera zamiast przeładowywania całej strony.
przy zastosowanie tej techniki interfejs użytkonika nie jest blokowany.
podczas czekania na odpowiedz serwera.

Prosty request
products.json
[{
    "id": 457
    "name": "KAWA",
    "price": 12.99
}
{  "id": 190
    "name": "klawiatura",
    "price": 78
}
]

poniżej kod dzieki któemu w JS pobioerze się JSON i da odpowiedz na konsolę

const request = newXMLHTttpRequest();
request.open('GET', "products.json");
request.responseType= 'json';
request.onload = () => {
  console.log(request.response); - odpowiedz w sererwa bedzie w response
};
request.send();

 
 Fetch
 fetch("products.json").then(response =>{
    response.json().then(products => {
      console.log(products);
    });
 });
nowoczesny zamiennik dla XHR. Tylko to aby send został wysłany.
bazuje na Promises

const promise = fetch("products.json");

 promise.then(response =>{
    response.json().then(products => {
      console.log(products);
    });
 });

fetch możę przejmować obiekt z konfiguracją

alternatywany zapiss
fetch("products.json")
    .then(response=>response.json())
    .then(products => console.log(products));
    .catch(error=> {
        console.error("Smdmedk", error);
        console.log("scos nie tak");
    });
Catch - gdy coś pójdize nie tak

Wysyłanie JSON-a metodą POST
fetch("/add-person",{
  method: "POST",
  headers: {
    "Content-Type": "application/json",
  },
  body: JSON.stringify({
      name: "Krzysiek",
      surname: "dąbrowski",
  }),
  })
wysyłanie dych znp. osobą do bazy danych.
wysyła konfigurację
  
Axios na githubie
<script src="https://cdn.jsdelivr.net/npm/axios@1.6.7/dist/axios.min.js"></script>
dodaj go do head

 axios.get("products.josn")
    .then(response => console.log(response.data))
    .catch(error=> console.error(error));
GET

axios.post('/add-person', {
  name: "Krzysiek",
  surname: "Dąbrowski",
})
  .then(response=> cossole.log(response.data))
  .catch(error => console.error(error));
})
POST


MODUŁ 12
JS – Promise, Async / Await (25 min)
00:00

Jak tworzyć własne obietnice?

fetch("products.json")
    .then(response => response.json())
    .then(products => console.log(products))
    .catch(error => console.error("COś złego", error));]

    fetch zwraca nam obietnice na któej wykonujemy metody
    odkodywowanie jsona 

fetch zwraca obiekt Promise, obietnica że pokaże się jakiś wynik.
każdy obiekt Pormise ma metodę then, do której przekazujemy funkcję któa zostanie wywołana kiedy obietnica zostanie spełniona
łańcuchu obietnic jest spełniona po skończonym wywołaniu funkcji przez nas
Promise ma również metod ę catch do której przekazujemy funkcję któ zostanie wykonana w przypadku błędu.

const logProducts = products=> console.log(products);

const promise =  fetch("products.json");

fetch("products.json")
    .then(response => response.json())
    .then(logProducts)
    .catch(error => console.error("COś złego", error));]

wyszło na jedno

Jescze o promise
Obietnica może być spełniona tylko raz.
 Nie może być tak że obietnica będzie spełniona a później odrzucona.
Wiele nowoczesnych API w tym fetch , działa na zasadzie Promises\
wpoczątkowo obietnica jest w stanie pending - ani spełniona ani odrzucona

Jeśłi pobieramy i jest 404

fetch("products.json").then(response => console.log(response))
to nie odpali nam catcha tylko then
musimy obsłużyć to ręćznie

fetch("products.json").then(response {
    if(!response.ok){
      throw new Error(response.statusText);
       }
       return response;
})
.then(response => response.json())
.then(response => console.log(response))
.catch(error => console.error(error));

Promises wracany przez fetch jest tylko odrzucany w przypadku błęó z połączeniem internetowym. Po niepowodzeniu odbioru odpowiedzi.
Jeśli kod odpowiedzi HTTP jest inny niż 2** właściwość ok odpowiedzi będzie ustawiona na false.

Własny Promise
const promise = new Promise((resolve, reject) => {
    reject();
});
promise.then()

cosnt wait = (time) => {
  const promise = new Promise((resolve) => {

  SetTimeout(() {
   resolve();
}, time);  
  return promise;
};

wait(1000).then(() =>{
    console.log("Minęłą sekunda");
});

PO restruktaryzacji
cosnt wait = time => new Promise((resolve)=>{
SetTimeout(resolve, time)
}} 
}
wait(1000).then(() =>{
    console.log("Minęłą sekunda");
}); 


cosnt wait = time => new Promise((resolve, reject
  if(typeof time!== "number" || time <0)
  {reject("zły czas")
SetTimeout(resolve, time)
}} 
}
wait(1000).then(() =>{
    console.log("Minęłą sekunda");
}); 
          .catch(error =>{
            console.error(error)

          }
          
          
Async fukcje
Funkcja ansynchroniczna
const getName = () => "Krzysiek";
getName()
const getName = async () => "Krzysiek";
getName() zwraca promise z wartośćią Krzysiek

getName(.then(name => console.log(name))
Krzysiek

Async jest jeszcze nowszy od promises.
Funkcje Asynchroniczne automatycznie zwracają wartość jako Promise.
Async /await jest alternatywną składnią dla Promises
żeby użyć await musimy być w funkcji, która jest asynchroniczna.

const getName= async ()=> "Krzysiek";
(async () =>{
    const name =await get Name();
    console.log(name);
})();

Await wsztrzymuje dalsze wykonywanie instrukcji az
do momentu kiedy zostanie spełniona obietnica i zwraca wartość.

Poprawia łątwiejsze pisanie
i czyta kod się

(async () => {
   try {
 const response = await fetch("products.json");

      if(!response.ok){
        throw new Error(response.statusText)
      }
    const products= await response.json();
    console.log(products); }
    catch(error){
console.log(error)
    }
})();

  z axios jest prościej

(async () = > {
    const response = axios.get("products.json");
    console.log(response.data)
}


(async () = > {
    try{
      const response = axios.get("products.json");
    console.log(response.data)
    } catch(error) {
      console.error(error)
    }
}


MODUŁ 12
Praca domowa (6 min)
00:00
Stawki pobieraj z Europejskiego banku. Udstępnione jest API
https://exchangeratesapi.io/


MODUŁ 13
Praca domowa z poprzedniego tygodnia (13 min)
00:00

Object.keys- zwróci tablicę wszystkich kluczy.

MOPDUŁ 13
Wprowadzenie do Reduxa (26 min)
00:00
15:30 akcje

Biblioteka napisana w JS
służy do zarządzania globalnym stanem aplikacji
jest centralnym magazynem na dane
wymaga przestrzegania pewnych reguł
daje konkretne wzorce i narzędzia pomagające w określeniu kiedy i gdzie i dlaczego aktualizowany jest stan naszej aplikacji

Wady (kompromisy)
wymaga od nas używania konkretnych wzorców
wymaga zaponzania się z narzędziem
zwięsza ilość kodu

Idealne przypadki użycia Reduxa
Stan aplikacji jest obszerny o dostęp do niego jest potrzebny w weilu miejscach
stan zmienia się często
logika aktualizująca stan jest skomplikowana
aplikacja jest dość duża

Dodatkowe paczki
React Redux intergracja Reduxa z komponentami React
Może byc stosowany z różnymi frameworkami
Redux Toolkit- narzędzia upraszczające prace w Reduxie

One-way-data flow - przepły danych w jednym kierunku
Stan AKcja WIdok
 Stan określa sytuację, w której w danym momencie znajduje się nasza aplikacja
 Interfejs użytkownika renderowany jest na podstawie tego stanu.
kiedy coś się dizej stan się aktualizuje
aktualizacja stanu powoduje ponowny render aplikacji znów na podstawie nowego stanu.

Po co Redux - skoro to możemy otrzymać sandartowo.
Sytuacja może się skomplikować jeśli mamy wiele komponentów, które się renderują na podstawie jednego stanu.
W reduxie taki współdzielony stan wynosimy poza drzewo komponentów.
i trzymamy go gdzie indziej, dzięki temu komponenty pełnią rolę wyłącznie widoku dla naszej aplikacji i każdyz nich możę odczytywać i modyfikować zewnętrzny stan.
widok i stan są od CIebieniezależne

Immutability
DO prawidłowego działania Reduxa wymagane jest trzymanie się Immutability
 Zawsze zwracamy nowy stan nie edytujemy.
Kopiujemy stan, modyfikujemy i zwracamy nowy.
 Biblioteka immer pozwoli nam to zadanie uprościć.

Akcja
const addTaskAction = {
  type: 'tasks/addTask',
  payload: 'Nauczyć się reduxa',
};
zwykły obiekt z polem type
opsuje zdarzenie, które wydarzyło się w aplikacji
w polu type powinna się znaleźć jakaś opisowa nazwa.
obiekt akcji może mieć inne pola z dodatkowymi informacjami
zwyczajowo inne informacje dodaje się do pola payload.

Action creator
const addTask =content =>({
  type: 'tasks/addTask',
  payload: content,
  });
dzięki temu jest wygodniej bo nie trzeba za każdym razem pisać tego obiektu.

Reducer
const tasksReducer = (state = { tasks: [] }, action) => {
switch (action.type) {
case "tasks/addTask":
return {
...state,
tasks: [...state.tasks, { content: action.payload }],
};
default:
return state;
}
};
funkca która otrzymuje aktualy stan i akcję i na podstawie ich zwraca nowy stan
nowy stan tworzony jest wyłącznie na podstawie tych dwóch argumentó
reducer nie może edytować aktualnego stanu
-zgdonie z immutability powienien skopiować poprzedni stan i utworzyć nowy.
reducer nie powinnien wykonywać asynchronicznych akcji ani powodować zadnych efektó ubocznych
Jeśli dana akcja nie interesuje reducer , po prostu zwraca niezmodyfikowany stan.
11:40

const initialState= {
  tasks: [],

};

cosnt reducer = (state = initialState, action) = > {
  if(action.type ==="addTodo"){
    return {
      ...state,
      tasks:[
        ...state.tasks, 
        {
          content: action.payload,
        }

      ]
    }
  }
  return state;
}; 

reducer(undefined, {}) - zaraca teraz pustąta tablicę.

Rzućmy akcje
const addTaskAction = {
  type: "addTask"
  payload: "Nauczyć się całego Reduxa",
};

 reducer(undefined, addTaskAction)
 dostaliśy stan w którym jest tasks z jednoelementową tablicą.

 reducer({tasks: [{content: "Nauczyć się reduceró"}]}, addTaskAction)
wzraca duelementową tablicę.


cosnt reducer = (state = initialState, action) = > {
  switch(action.type){
        case "addTask" 
return {
      ...state,
      tasks:[
        ...state.tasks, 
        {
          content: action.payload,
        }

      ]
    }
  }
  }
  default:
    return state;
}; 

  
store - magazyn na stan naszej aplikacji
import{configureStore} from '@reduxjs/toolkit';

const store = configure({ reducer: tasksReducer });
console.log(store.getState()); zwraca  {tasks:[]}

store tworzymy przekazująć reducer
store ma metodę getState, która zwraca aktualny stan aplikacji.

npm install @reduxjs/toolkit - zinstaluj store


import{configureStore} from '@reduxjs/toolkit';
const store = configure({ reducer: tasksReducer });
console.log(store.getState()); zwraca  {tasks:[]} pustą tablicę.


dispatch
  store.dispatch({  
    type: 'tasks/addTask',
    payload: 'Napić się wina'
  })
console.log(store.getState()); zwraca 
 dispatch jest metodą obiektu store
 jest jedyną metodą na aktualizację stanu.
 do tej metody należy przekazać akcję.
 store wywoła reduceri ustawi nowy stan
 wywoływanie akcji jest podobne do zdarzeń
reducery nasłuchują akcje i jak są zainteresowane to aktualizują stan

kod po zdispaczowaniu dodał akcję
 
const addTask = content = >({
  type: "addTasks",
  payload: content
})

po tym kodzię, ułątwi na się pisanie
aby odać elemment wystarczy.
store.dispatch(addTask("zadanie 1"));
używamy to action creator

Selektor - 
const selectTasks = state => state.tasks;
console.log(selectTasks(store.getState()));

funckcja któa wie jak z całego stanu wyciągnąć intresujący nas fragment
otrzymuje cały stan i zwraca jego część
przydaje się kiedy aplikacja się powiększa

console.log(selectTasks(store.getState());

Data FLow w szczegółach

tworzymy store, przekazując reducerstore wywołuje ten reducer raz i zwróconą
przez niego wartość ustawia jako początkowy stanna początku komponenty renderują się na podstawie
tego stanu i subskrybują wszystkie przyszłe aktualizacjekiedy coś się dzieje (np. użytkownik klika przycisk), dispatchujemy akcjęstore wywołuje reducer z poprzednim stanem
i tą akcją i wynik zapisuje jako nowy stanstore informuje wszystkie zainteresowane komponenty o aktualizacjikomponenty sprawdzają, czy interesujący je fragment
stanu się zmienił i w tym przypadku ponownie się renderują
18:45 store instalacja



MODUŁ 13
Redux + React (33 min)
00:00

Warto podzielić aplikację na tzw. features
Nowy folder feature
Nowy features/tasks
Nowy folder common
Container do common
Header do folderu common
Section do folderu common
Pozostałęm komponenty do features/tasks
Tasks, Form, buttons
App.js do tsaks
    
    zmiany
    03:27

Warto podzielić na features

Struktura
/src/store.js - tu tworzymy reduxowy store
/src/ondex.js - dodajemy Provider do drzewa komponentów
 /src/features/tasks/tasksSlice
 logika reduxowa wewnątrz konkretnego feature`a

Slice/create Slice
uproszcza tworzenie akcji
slice- fragment stanu aplikacji
slice`a tworzymy przekazująć 3 parametry
  name - nazwa slice`a
  initialState- początkowy stan slice`a
reducers - obiekt z reducerami
mamy łatwiej bo mamy klucze i funkcje tylko dla danej akcji

we features/tasks tworze tasksSlice.js
import {createSlice} from '@reduxjs/toolkit';
const tasksSlice= createSlice({
    name: 'tasks',
    initialState: {
          tasks: [],
    }, 
    reducers: {
        addTask: ({ tasks}, { payload }) =>{    
            tasks.push(payload);
        }
    }
})
jest to uprosczone po restrekturyzacji

export const {addTask } =tasksSlice.actions;
export const selectTasks = state = state.tasks;
export default tasksSlice.reducer;
12:00

createSlice automatycznie tworzy action creators i zwraca je w polu actions
action creator AddTask  w polu Actions    

12:56
instalowanie paczki
  
nazwy tych action rcreators są takie same jak nazwy pół w obiekcie reducers
 
tasksSLice.reducer({tasks: []}, addTask)
  content: "Test",
  done: true,
}));

console.log(tasksSLice.reducer({tasks: []}, addTask)
  content: "Test",
  done: true,
}));

zwraca nowy stan.


Redux Toolkit dzięi bibliotece immer pozwala nam pisać kod reduceró bez zwracania uwagi na immutability

łancuch wywołanń , zagnieżdzenia, immer pomoga z tym

store.js
 z taskSlice wyesportowaliśmy wynikowy reucer, którego tutaj możemy użyć

import { configureStore } from '@reduxjs/toolkit';
import tasksReducer from './features/tasks/tasksSlice';

export default configureStore({
    reducer:{
      tasks: tasksReducer
    }
})

export const { addTasks} = tasksSlice.actions;
export const selectTasks = state => state.tasks;
export default tasksSlice.reducer;

przy wywoływaniu configureStore możemy podać wiele reducerów w różnych polach obiektu.
Pod takimi samymi nazwami pól dane zostaną umieszczone w głównym stanie.

Provider 
import {store} from "./store.js";
 
 npm install react redux

import {Provider} from "react-redux";

<Provider store= {store} >
</Provider>

use Selector - jak czytać store wewnątrz komponentu.
biblioteka dostarcza nam nowy hook use Selektor

const { tasks }= useSelector(selectTasks);
pozwala wyciągnąć ze stora dowolny fragment
 
 import { useSelector }from "react-redux";
 import { selectTasks ] from "./tasksSlice';

onst { tasks }= useSelector(selectTasks);

przy każdej aktualizacji stanu, dzięi useSelector ,komponent się przerenderuje

useDispatch
KIedy używamy zwykłego stanu komponentu
przede wszystkim w formularzachkiedy dane są potrzebne tylko w jednym komponenciekiedy nie potrzebujemy możliwości przeskakiwania między akcjami

MODUŁ 13
Redux + React (33 min)
Powtórka
12:28 zrozumiane

reducer-na podstawie poprzedniego stanu zwraca stan kolejny
20:06 instalka paczki
useSelector - pozwala poberać dane bezpośrednio z magazynu
dowolny fragment ze stora
22:53


MODUŁ 13
Kolejny reducer w zadaniach (8 min)
00:00

toggleTasksDone: (state, action) => {
  const index = state.tasks.findIndex(task=>task.id === action.payload;
  state.tasks[index].done = !state.tasks[index].done
  )
  }
const dispatch = useDispatch(); 

on Click= {() => dispatch(toggleTaskDone(task.id))}
w butonie

można żyć splice 






MODUŁ 13
Praca domowa (1 min)
00:00
Całe zardządzanie przenieś do reduxa


MODUŁ 14
Praca domowa z poprzedniego tygodnia (7 min)
00:00

MODUŁ 14
 JS – generatory (13 min)
 00:00
 z ecma script 6

Saga jest na generatorach
Kod asynchroniczy wyglada jak kod synchroniczny

function* nazwa(parametry){
  wyrażenia
  yield wartość;
}
taka funkcja zwra obiekt generator
z takich funkcji można wychodzić i wracać wielokrotnie.

 Przykład

 function* generator(){
    yield 5;
    yield "tekst";
    yield null;
    yield {};
 }

 const iterator = generator();

 iterator.next();
 zwraca 5
 za drugim razem zwróci "tekst"
 za trzecim i za czwartym, kolejno
 po całym obiegu done: true

 wywołanie takiej funkcji nie wykonuje jej ciałą ale zwraca obiekt Generator (iterator)
obiekt posiada metodę nex, wywołuje po kolei funcje z ciała
yield odreśla wartość, która zostanie z tego iteratora zwrócona
next() zwraca obiekt z własciwoscią value, w tej właściowości będzie dostępna wartosć zwrócona przez yield
właściwoś done okreśła czy generator zwrócił już swoją otatnią wartość.
za każdym razem done: true
słowo return w wewnątrz generatora zakończy jego działanie
 kontekst jest przechowywany między ponownymi ich wywołaniami

mogę przekazać jakiś argument

function* generator(parametrn){
  console.log(parametr)
    yield 5;
    yield "tekst";
    yield null;
    yield {};
 }
 const iterator = generator(100);
 wypisze 100

 function* nextProductName(products){
    for(products of products){
      yield product.name;  
    }
 }
const products = {
  {
    name: "Interfejs audio",
    price: 299,
  },
  {
    name: "telewizor",
    price: 13000;
  }.
};

const generator= nextProductName(
{
    name: "Interfejs audio",
    price: 299,
  },
  {
    name: "telewizor",
    price: 13000;
  }.
};
)

generator będzie zwracał kolejne nazwy produktów.
generator.next()
możemy za pomocą generatora iterować.

argumenty przekazywane do next()
podmieni się wartość w yield

 function* crazyGenerator(){
    const number = yield 5;
    const text = yield number*5;
    yield text.repeat(5);
     }
const generator = crazyGenerator();
generator.next()
wywala 5 z done false
generator.next(100)
wywali 500
enerator.next(+)
wywali +++++


MODUŁ 14
Redux-Saga (27 min)
00:00
Biblioteka do obsługi side effectwów Java Scriptowa
zazwyczaj chodzi o pobranie czegoś z backendu
Korzyści:
  Łatwiejsze zarządzanie
  wydajniejsze ich wykonywanie
  lepsza obsługa błędów
  łatwiejsze testowanie
 
Jak to działa:
  coś w rodzaju osobnego wątku w aplikacji odpowiedzialnego za obsługę sideeffectów
  Działa obok, pomiędzy reduxem
  Jest to middleware dla Reduxa
  Sagi mogą być uruchamiane, wstrzymywane lub anulowane za pomocą zwykłych akcji reduxowych.
  Saga ma dostęp do pełnego store'a i może dispatchować akcje
  Bazuje na generatorach.
  Akcje reduxowe pozostają czyste, proste i same nie powodują side effectów
  npm install redux-saga

  Przykład Sagi
  import{ call, put, takeEvery} from "redux-saga/effects";
  import {getMovie} from "./api"
  import { fetchMovieSuccess, fetchMovieError, fetchMovie} from "./movieSlice"

  function* fetchMovieHandler({ getMovie, movieID}) {
    try{
        const movie = yield call(getMovie, movieId);
        yield put(fetchMovieSuccess(movie));
    }   catch (error) {
        yield put(fetchMovieError(error));
    }
    }

export functoin* watchFetchMovie() {
  yield takeEvery(fetchMovie.type, fetchMovieHandler()
} 

kopiujemy tablicę przykłdowych zadań.
 [
  {
    "content": "Blal bla bla",
    "done": false,
    "id": "sdasd"
  }
{
  "content": "l,l,fl,dl",
    "done": false,
    "id": "sdasd"
}
 ]

tworzymy funkcje w nowym pliku getExampleTasks.js
export const getExampleTasks= async () => {
  const response =await fetch("/todos-list-react/exampleTasks.json")

  if (!response.ok){
    new Error(response.statusText);
}

return await response.json();
}; 
zwróci promise bo jest asynchroniczna

wyżej 
<Button onClick ={()=> dispatch(fetchExampleTasks())}>
Pobierz przykładowe zadania
</Button>

w taksSlice
  fetchExampleTasks: ()=>{},

  w imporcie dodajemy import fetchexampleTaks
  
09:06

Robimy przycisk "Pobierz przykładowe zadania"
dodajemy do listy zadań pare zadań.
Robimy JSON z wyświetlonego kodu
JSON.stringify(tu wkeljam wartość strony z tasks)
RObię plick w publick i nazywam go exampleTasks.json
Plik zawiera samą tabllicę bez wywołań itp.

Robimy funkcję , która pobierze nam te zadania
getExampleTasks.js
export const getExampleTasks = async ()={
  const response=await fetch("/todos-list-react/exampleTasks.josn");

  if(!response.ok){
      new Error((await response).statusText)
  }
      return await response.json(); 
}

w Buttons index.js dodajemy koejny button

<Button onClick=()>Pobierz przykłądowe zadnia </Button>

w taksSlice dodajemy nową akcję: 
fetchExampleTasks: ()=> {}   -ona w sumie nic nie robi
i musimy ją wyeksportować

<Button onClick={(=> dispatch(fetchExampleTasks)})}>Pobierz przykłądowe zadnia </Button>
import fetchExampleTasks from
Funkcj awyświetliła wnętrze  fetchExampleTasks czyli pusty obiekt

 ciąg dalszy 09:36

 tworymy plik tasksSaga.js 
 tworzymy funckję generator
 import {takeEvery, call, put} from "redux-aga/effects";
 import {fetchExampleTasks } from "./tasksSlice";
 import {getExampleTasks} from "./getExampleTaks";

 functiion* fetchExampleTassksHandler() {
  try{
   const exampleTasks = yield call( getExampleTasks);
    yield put(setTasks(exampleTasks));
  }catch(error){
]yield call(alert, "co poszło nie tak");
  }
 }
 
 function*  watchFetchExampleTassks(){
    yield takeEvery(fetchExampleTasks.type, fetchExampleTassksHandler)
 }

 w taks slice.js
 setTasks: (state, {payload: tasks})=>{
    state.tasks = tasks;
 }

13:42
Podłączenie sagi do store'a
trzeba użyć middleware: [sagaMiddleare],
następniej 
saga Middleware.run(saga);

redux toolkit v2.0
przykąłd:

import createSagaMiddleware from "redux-saga"
import {watchFetchExampleTasks} from "./features/tasks/tasksSaga"

const sagaMiddleware = createSagaMiddleware();

const store =  configureStore({
  reducer:{
    tasks: tasksReducer,
  }
  middleware: [createSagaMiddleware]
})

sagaMiddleware.run(watchFet);


export function* watchFetchExampleTasks(){
    console.log("Saga jets podłączona");
    yield takeEvery(fetchExampleTasks.type, fetchExampleTasksHandler);
}

export default store;
  
Sagi to generator functions, które yieldują obiekty JS do middleware'a
są to obiekty które zawierają instrukcje interpretowane przez middleware
Jeśli yieldowany jest Promise, middleware wstrzyma sagę aż obietnica zostanie wykonana.
Następnie wznowi sagę i będze ją wykonywać do następnego yielda.

Co jeśli mamy więcej sag.
 Możemy stworzyć główną sagę:
 yield all([
  saga 1()
  saga2()
 ]}
  17:35

  import {all} from "redux-saga/effects";

  export default function* rootSaga(){
    yield all([
         watchFetchExampleTasks():
    ])
  }

  w store 
 import  rootSaga from "./rootSaga"

 sagaMiddleware.run(rootSaga);

Odpalanie zadań jednocześnie
np. pobieranie
pobieramy i idziemy dalej kiey oba wrócą

const [products, tasks] yield all([
  call(getProducts),
  call(getTasks),
])

Więcej efektów
takeEvery(pattern,saga,..arg) - nasluchujemy każdej akcji
pattern - prekazujemy typ akcji

takeLatest(pattern,sga,...args) - anuluje poprzednią sagę, jeśli jeszcze trwa- dziła delay

put(action) - dispatchuje akcję

call(fn, ..args) -wywołuje podaną funkcje z podanymi argumentami
moze zwracac promise i wtedy middle ware wstrzyma generator do czasu aż obietnica zostanie spełniona albo odrzucona. gdzie da błąd.
przekazujemy argument któe beą przekazane do naszej funckcji
za pomocą call łatwo jest testować.
select(selector,..args)- pozwala odczytywać zawartoś storea.
np. const tasks=yield select(selectTasks);
console.log sprawdza

delay(ms, [val])- blokuje wykonywanie na określony czas

throttle(ms, pattern,saga,...args)- sprawia, że zadania będą rozpoczynane nie częśćiej nić co podany przez nas czas.

 debouce(ms, pattren,sga...args) uruchamia zadanie po tym, jak porzez podany przez na   czas nie zostanie zdispatchowana akcja.

 https://redux-saga.js.org/
JSON -Java Script Obejct Noation


MODUŁ 14
 Zapis do localStorage w Redux-Saga (6 min)
00:00

Tworzymy funcję które pobierają i zapisują do localstorage

Taskslocalstorage.js

const localStorageKey = "tasks";
 
export const saveTasksInLocalStorage = tasks =>
  localStorage.setItem("tasks", JSON.stringify(tasks))
export const getTasksFromLocalStorage = () => 
  JSON.parse(localStorage.getItem("tasks")) || [];

w tasksSaga.js
function* saveTasksInlocalStorageHandler(){
  const tasks = yield select (selectTasks);
  yield call(saveTasksInlocalStorageHandler, tasks)
}
export function* tasksSaga(){
  yield takeLatest(fetchExampleTasks.type, fetchExampleTasksHandler);
  yield takeEvery("*", saveTasksInlocalStorageHandler)  oznacza wszytskie akcje jakakoliwiek
}

w tasksSlice w initiualState
  tasks: getTasksFromLocalStorage(),

jezcze zamieniamy na Sage w rootSaga
  export default function* rootSaga(){
    yield all([
        tasksSaga(),
    ])
  }


MODUŁ 14
React Router (43 min)
00:00

npm install react-router-dom@5.3.3

bilioteka do zarządzania routingiem
aplikacja renderuje się na podstawie dynamicnie zmieniającego się URL
jk kilkmy w linik to strona się nie przeładowuje a renderuje

dostajemy komponenty i hoohki dzięki którym stworzymy aplikację z wieloma podstronami.

przeglądarka raz ładuje całą stronę a póniej tylko jej fragmenty

 01:18 przykład

 <BrowserRouter> 
 <nav>ul-e
 </nav> 
 <Switch>
 <Route path="/autor">
 <Author/>
 </Route>
 <Route path="/">
 <Home/>
 </Route>
 </Switch>
 </BrowserRouter>

trzeba równierz zaimportować Home i Author

import Home from "./features/home/Home";
import Author from "./features/author/Author";

przykład
import { BrowserRouter, Switch, Route, Link } from "react-router-dom";
export default () => (
  <BrowserRouter>
    <nav> 
      <ul>
          <li>
          <Link to ="/zadania">Zadania
          </Link>
          </li>

          <li>
          <Link to ="/author">Autor
          </li>

          <Switch>
            <Route path="/zadania">
                <Tasks/>
            </Route>
           <Route path="/author">
                <Author/>
            </Route>

          </Switch>
          </li>
      </ul>
      </nav>
      < BrowserRouter>
);

Bedą zadania po których kliknięciu wrenderuje nam listę z zadaniami i ich obsługą.

nowa strona
Autorzy
Author.js
04:25

import React from "react";
section header-powinny same się zaimportować

export default () => {
  <Container>
  <Header title="O autorze"/>
  <Section
    title="Krzysiek Dąbrowski"
    body= {
      <nana/>
      }
/>
</Conteiner>
}
05:20

To było BrowserRouter
Teraz pora na HashRouter

Browser używa zwykłych sćieżek a hash po #
Browser wymaga by serewr był skonfigurowany w taki sposób by dla każdej ścieżki serwować naszą aplikację.
na browser router po odświeżeniu mielibyśmy błąd
#router to roziązuje

<hashROuter>
]
Do browsera możemy przekazać atrybut basename z bazowym urlem dla
wszystkich scieżek

 <browseEouter basename="/todos-list-react">

Teraz rout maczesrs
<Route> <Swith>
dopasowywywanie ścieżek

kiedy renderuje się switch, szuka wśród swoich dzieci route, którego scieżka pasuje do aktualnego URL-a
jeśli znajdzie, renderuje ten Route i ingnoruje pozostałe

switch sprawdza czy początek url pasojue do naszej ścieżki
dlatego zaczynamy od bardziej specyficznych, dłuższych scieżek, a kończymy na najbardziej ogólnych.

Jeśłi nie pasuje żaden ROute , Switch nic nie wyrenderuje

Jeśłi na końcu dodmy Route ze scieżką "/" może on funkcjonować jako strona główna lub strona typu 404

<Route path="/">
Strona główna
</Route>

lub np.

<Route path="/">
Nie znaleziona 404
</Route>

Jeśłi by było na początku renderezacji to switch stweirdzi że pasuje do realziacji. Pauje do początku URL-a
 
po dodaniu exact dopasowanie będzie musiało być pełne.

<Route exact path="/">
Strona główna
</Route>

Ostatnia 3 kategoria route czendzers
<Link>, <NavLink>, <Redirect>
zmieniacze sczeżek
wszystkie przyjmują atrybut to, do którego możemy przekazać scieżkę
Link poprostu renderuje hiperłącze
Do navlinka możemy przekazać activeClassName
  -wówczas podana klasa zostanie dodana do linka , jęlsi jest on aktywny
Jako nawigacja i pokazan9iei na jakiej podstroie jesteśmy

import{NavLink, Redirect} from "react-router-dom";
 np.
 <li>
  <NavLink activeClassName="active" to="/zadania"> Zadania </Link>
 </li>

 Nie opreujemy na clasach tylko na styled components. CO możemy pogodzić

Do navlinka możemy też dodać atrybut exact jeśli chcemy by dopasowanie było dokładne

Redirect po prostu przenosi do podnanej ścieżki kiedy jest renderowany.

<Redirect to="/zadania/> gółwny rut odrazu oprzekieruje do zadań
i chcemy żeby był stroną główną.

useParams
np.podstrona zadania
Tworzymy folder TasksPage i wrzucamy tam wszytskie komponenty, któe są używane w tasks
i tasks mzieniamy na index.js
dodajemy również TaskPage
i index.js

ta zstrona ma się pokazać jak wjedzie się w rots id zadania

taskcontent ma być linkiem
<link to={"/zadania/${tasks.id}"}>{tasks.content}</link>

<Switch>
  <Route path="/zadania/:id">
    <TasksPage>

import TaskPage from "./features/tasks/TasksPage";

TaskPage
import własciwości

kopia taks page minus to co nas nie interesuje
18:39 wzgląd

do taksslie dodajmey:
export const getTasksById = (state, taskId) =>
  selectTasks(state).find(({id})=> id === taskId);

function TaskPage()
{
cosnt {id} = useParams();
const task = useSelector(state => getTaskById(state, id))
}
return
(
  <COntainer>
    <Headre title="Szcz3egóły zadania"/>
    <Section
      title={task? task.content : "nie znaleziono zadania" }
      body={
        
      <><strong>ukończono: </strong> {task.done? "tak":"nie"}
/>
  </COntainer>
)

22:38 useLocation
to hook który reprezentuje gdzie teraz znajduje się nasz aplikacja

function TasksPage()
  const location = useLocation();
  const searchParams = new URLSearchParams(location.search)
  const query = searchParams.get("szukaj");
  
return(
  <Container>
  {location.search}
  )

w taksslice:
export const selectTaksksByQuery = (state, query) => 
  const taksks = selectTasks(state);

if(!query || query.trim()==="" ){
  return tasks;

}

return selectTasks(state).filter(({content})=> content.toUpperCase.inludes(query.trim().toUpperCase()));

umieszczamy to w takslist

function TasksPage()
  const location = useLocation();
  const searchParams = new URLSearchParams(location.search)
  const query = searchParams.get("szukaj");
  
  const taksks = useSelectors(state => selectTaskByQuery(state, query))
inaczej

cosnt query = (new URLSearchParams(location.search)).get("szukaj");

useHistory
zwrócony obiket to history z paczki history
ma wiele pół i metod

push() -dodaje nowy wpis do history
replace() - zastąpi aktualny wpis
goBack()- cofa
goForward()- do przodu

Zróbmy wyszukiwarke
w takspage dodajemy kolejne Section

<Section
  title="Wyszukiwarka"
  body={<Search/>}

/>>
 
 Nowy komponenet w taksPage
 "Search"
index.js
import React from "react";

31:57 

export default () => {

  const location = useLocation();
  const history = useHistory();
  const query = (new URLSearchParams(location.search)).get("Szukaj")

const onInputChange = ({target}) =>  {
  const searchParams = new URLSearchParams(location.search)

  if(target.value.trim() === ""){
    searchParams.delete("szukaj");}
    else {
    searchParams.set("szukaj", target.value);
    }

  history.push('${location.pathname}?${searchParams.toString()});

  }
}

  return(
    <Input
      placeholder="Filtruj zadania"
      value={query || ""}
      onChange={onInputCHange}
    />
  )
  };

w taks
nowy folder input 
index.js

import styled from "styled-components";

export default styled.input'
  padding:10px
  border: 1px solid ${({theme })=> theme.color.alto};';

imput w formularzu będzie teraz inaczej zainportowany.

<Input
  ref={inputRef}
  value={newTaskContent}
  placeholder="Co jest do zrobienia?"
  onChange= {({ traget }) => setNewTaskContent(target.value)}
/>

na końcu stylowanie

import styled from "styled-components";

export const Wrapper = styled.div'
  display:grid
  grid-template-columns: 1fr;  

';

a teraz
NavLink + Styled Components

import {NavLink} from "react-router-dom";
const activeClassName= "active";
export const StyledNavLink = styled(NavLink).attrs(props=>({
  activeClassName;

}))'
  &.${activeClassName}
  {
    color: red;
  }

';

teraz użycie:
W App.js
import Nav
w NavLink 
<StyledNavLink > </StyledNavLink >zamiast<NavLink>

 
MODUŁ 14
Prace domowe (6 min)
00:00


MODUŁ 15
Prace domowe z poprzedniego tygodnia (19 min)
00:00
# w App js
02:30
08:20


# Time Banking Framework

Er zijn wereldwijd veel initiatieven tot time banking. Deze repo zet aan tot het opzetten van een framework, waardoor initiatieven snel en professioneel kunnen worden opgezet. Het framework moet passen in de moderne wereld en houdt rekening met het feit dat een time banking initiatief onderdeel is van een groter geheel, waar fiat geld de norm is. Ook is het beoogde doel van het time banking framework een protocol te beschrijven dat zorgt van koppeling van verschillende time banking initiatieven. Scenario's worden beschreven middels personas, welke een specifiek doel in het systeem hebben. De scenario's komen misschien bekend voor, ze zijn geïnspireerd door gedrag in het huidige fiat systeem. De gedachte erachter is dat hoe het systeem is geconfigureerd in zichzelf niet slecht is, maar de financiële hiërarchie die centraal is ingericht en in feite als piramide is geschakeerd, waardoor macht ook gecentraliseerd is wel. Ook is de waardering van mensen sociaal gezien in het fiat systeem gebaseerd op de waardering van de persoon in geld. Je kunt je afvragen waarom een schoonmaakster veel minder verdient dan bijvoorbeeld een chirurg. Een hoe het komt dat een schoonmaakster toevalligerwijs lager in de sociale ladder staat dan diezelfde chirurg. Het beoogde doel van het Time Banking Framework is een een decentrale inrichting van het systeem.

Fundamenteel onderdeel van het systeem is dat de waardering van een uur arbeid gelijk is voor iedereen in de community en dat arbeid niet, zoals in het fiat systeem, verschillend gewaardeerd wordt.

```
TODO

[ ] Zijn er nadelen verbonden aan een gelijke waardering van iedereen in het systeem? Het neigt ergens naar communisme, wat uiteindelijk altijd ineenstort.
```

# Scenario's

* In alle scenario's wordt uitgegaan van een basiswaardering van 1T$ = 1 uur arbeid.
* Transacties worden na afronden van een werkdag gemaakt, dus geen maandelijkse vereffening van arbeid en T$ zoals in het fiat systeem gebruikelijk is.

```
TODO

[ ] Geldt het dagelijks vereffenen van arbeid en T$ altijd?
```

## Tijdbank
## Werken in coöperatieverband

Uitgaande dat iedereen in de community zichzelf vrijwillig inzet ten gunste van de community is het niet ondenkbaar dat er, net als in het fiat systeem, samenwerkingsverbanden gaan ontstaan. In dit voorbeeld gebruik ik een basisschool als voorbeeld. In een samenwerkingsverband zal een bepaalde stabiliteit moeten zijn: in dit voorbeeld zou het natuurlijk niet goed zijn als de leerkracht morgen in ene besluit er geen zin meer in te hebben en direct stopt met de dienstverlening.

* Er wordt in een community altijd gewerkt vanuit het coöperatiemodel als meerdere mensen samen de belangen van een groep mensen binnen de community wil behartigen. Ieder lid van de coöperatie heeft inzicht in de balans van de coöperatie en heeft evenveel invloed op de toekomst van de coöperatie. Sterker nog: iedere deelnemer die gebruik maakt van de coöperatie heeft evenveel stemrecht als de leden van de coöperatie. De coöperatie behartigt de belangen van de leden en de belangen voor wie de coöperatie in het leven is geroepen.

### Werknemer
Anita is leerkracht op een basisschool. Maandag werkt zij 8 uur aan de ontwikkeling van kinderen. Dit betekent voor haar dat zij van de basisschool 8T$ krijgt voor een volle dag werk.

```
TRANSACTIES

BASISSCHOOL AAN ANITA     8T$

SALDI

BASISSCHOOL               8T$-
ANITA                     8T$
```

```
TODO
[ ] Bedenken hoe de basisschool T$ krijgt van de ouders
[ ] Bedenken of het wenselijk is dat kinderen de school betalen met hun T$
[ ] Bedenken of het huidige systeem, waar de basisschool T$ krijgt van de Raad van de Community, toepasbaar of wenselijk is
[ ] Bedenken hoe de balans transparant is voor alle partijen: leerkrachten, bestuur, oudercommissie en ouders moeten allen inzicht hierin hebben
[ ] Traditionele gecentraliseerde machtsstructuren/vertegenwoordiging als een oudercommissie, ondernemingsraad, bestuur: zijn die nog nodig in volledig transparante en democratische besluitvorming?
[ ] Bedenken hoe de stabiliteit van dienstverlening wordt gewaarborgd, het liefst zonder contracten te gebruiken
```

### Verlof
Aan het einde van de week wil Anita graag een lang weekend met haar partner Nico doorbrengen. Het wordt mooi weer, dus ze willen graag op de fiets mooie plekken in de regio bezoeken. Ze vraagt twee dagen verlof aan: vrijdag en maandag. Voor die dagen wordt er vervanging geregeld (Peter) door het bestuur van de school. Merk op dat Anita geen pot vrije dagen heeft, zoals in het fiat systeem gebruikelijk is. Het samenwerkingsverband gaat ervan uit dat Anita volwassen genoeg is om verlof in goed overleg op te nemen. Ook is het zo dat er dus geen inkomsten voor Anita zijn wanneer ze níet werkt.

```
TRANSACTIES

BASISSCHOOL AAN PETER     16T$ # vrijdag, maandag
BASISSCHOOL AAN ANITA     24T$ # dinsdag, woensdag, donderdag

SALDI

BASISSCHOOL              48T$-
ANITA                    32T$
PETER                    16T$
```

```
TODO

[ ] Hoe worden kosten opgevangen die haar saldo overstijgen? Voor verlof zou ik zeggen dat dat de verantwoordelijkheid is van het community lid, maar voor verzuim zal dat anders liggen
```

### Verzuim
Tijdens haar lange weekend met haar partner Nico wordt Anita zondags ziek. Ze belt de basisschool en spendeert de hele week onder de wol en kan pas de week erop op maandag weer aan het werk. Het bestuur van de basisschool regelt dat Peter zolang Anita ziek is voor haar kan invallen

```
TRANSACTIES

BASISSCHOOL AAN PETER    32T$ # 4 dagen extra
# Er is geen transactie AAN ANITA, ze verricht immers geen arbeid.

SALDI

BASISSCHOOL              80T$-
ANITA                    32T$
PETER                    48T$
```

### Langdurig verzuim
Anita heeft een beetje pech, want maandagochtend na haar ziekte schiet het in haar rug. Ze gaat naar de dokter en laat haar onderzoeken: een hernia. Ze is zes weken uit de running.

Na zes weken start ze een reïntegratietraject en werkt elke week 25% meer van haar normale gewerkte uren, wat neerkomt op elke week 2 uur extra. De kinderen zijn hartstikke blij haar weer te zien. De opbouw voor Anita en de afbouw van Peter ziet er als volgt uit:

|Week|Anita|Peter|
|-|-|-|
|1 t/m 6|0|8|
|7|2|6|
|8|4|4|
|9|6|2|
|10|8|0|

```
TRANSACTIES

BASISSCHOOL AAN PETER   58T$
BASISSCHOOL AAN ANITA   18T$

SALDI

BASISSCHOOL            156T$-
ANITA                   50T$
PETER                  106T$
```

### Arbeidsongeschiktheid
### Reservering oude dag
### Transparantie saldo T$

## School en educatie
## Personeel van een onderneming
## Iets bestellen buiten het systeem (fiat)
## Iets bestellen buiten het systeem (inter time bank transactie)
## Een huis kopen
## Een product kopen
## Een dienst afnemen

```
TODO

[ ] Hoe waardeer je bijv. een hotelovernachting?
```

## Huren
## Verschil in waardering van uren
## Vakantie opnemen
## Uren overmaken aan iemand anders
## Investeren

Steven heeft een goed idee waarmee hij waarde toe kan voegen aan de community. Hij moet echter een plan maken en de handen uit de mouwen steken om de basis hiervan te realiseren, vóórdat er T$ verdiend kan worden. Vanwege zijn drukke gezinsleven, de verantwoordelijkheden in T$ die hij heeft en de T$ die hij daarvoor moet verdienen is het onmogelijk om hiervoor de tijd en energie te vinden. Hij heeft weinig T$ opgebouwd en zal dus een investeerder voor de periode dat hij geen T$ kan verdienen moeten vinden.

Gelukkig is zijn vader trots en vol vertrouwen in het idee dat zijn zoon heeft en investeert de benodigde T$. Steven verwacht zes weken lang acht uur per dag aan het fundament te besteden, zonder dat er T$ tegenover staat. Daarna verwacht hij elke vier weken 2T$ meer te verdienen.

* Uitgangspunt van investeren is dat elke investeerder evenveel invloed heeft op de toekomst van een coöperatie of community lid.
* Elke investeerder heeft inzicht in de balans van de coöperatie of community lid.
* Een investeerder wil graag zijn investering terug. Een investering wordt dus expliciet niet met winstoogmerkt gemaakt.
* Een investeerder kan wel verdienen aan zijn investering door tijd te besteden in de besluitvorming.

```
TODO

[ ] Als een investeerder inzicht heeft in de balans van een community lid, dan moet dit een "zakelijke" balans zijn, i.v.m. privacy.
[ ] Zoals je ziet, gaat Steven na een periode van zes weken elke vier weken 2T$ meer verdienen met zijn innovatie. Dat betekent dat hij op een gegeven moment zoveel gaat verdienen dat het de belangen van de community schaadt. Nadenken over het concept winst!
```

## Lenen


## Met pensioen gaan
## Verzekeringen
## Abonnementen
## Arbeid en materiaal
## Online entertainment en howto's

YouTube of blogs zijn fantastische bronnen van vermaak en bieden oplossingen voor problemen. Deze content is gratis toegankelijk, maar er wordt op de achtergrond verdiend aan de content door middel van advertenties of de blog/vlog is een advertentie voor de dienst of het product dat de blogger/vlogger zelf aanbied.

```
TODO

[ ] Hoe kan dit model worden toegepast in een op tijd gebaseerde economie?
```

## Crisis en rampen
## Schuld
## Hebzucht (teveel T$ toeeigenen)
## Sociaal vangnet
## Privacy van transacties / Cash T$
## Bezit
## Curatele / handelingsonbekwaamheid
## Corruptie
## Dispuut en onenigheid
## Passieve en actieve persoonlijkheden
## Aanbod/vraag
||Laag aanbod|Hoog aanbod|
|Lage vraag|||
|Hoge vraag|||

# Juridisch

Een community zal onderdeel zijn van een groter geheel en moet dat als zodanig accepteren. Dat betekent dat er binnen de juridische kaders van het grotere geheel moet worden gewerkt. Dit hoofdstuk is bedoeld als uiteenzetting waar een community juridisch aan moet voldoen, wil overheid niet ingrijpen.

```
TODO

[ ] Warme contacten onderhouden met de gemeente waarin dit plaatsvindt
[ ] Regels omtrent betaling in natura
[ ] Regels omtrent de interface met het fiat systeem (Belastingen, rechtsvorm, etc.)
[ ] ...
```

# Benodigdheden

* Tijdbank + Mijn tijdbank omgeving (web, apps, desktop)
* Een manier om transacties automatisch te vereffenen (wanneer je bijv. als leerkracht 8 uur per dag werkt en eind van de dag je 8 uur betaald wilt krijgen)
* Een manier om een transactie te maken
  * Online, bijvoorbeeld bij een aankoop in een webshop
  * "Offline", bijvoorbeeld bij een aankoop in een fysieke winkel
  * Contant
* Een manier om een abonnement aan te gaan en te beëindigen
* 100% veilige manier om transacties te vereffenen
* Marktplaats / sociaal medium
* Interface met fiat systeem (beurs, handelen op bijv EUR/T$ op een zwevende of vaste wisselkoers, bepaald door bijv. de gemiddelde EUR/per uur voor arbeid in Nederland)
* Dispuut systeem
* Sociaal krediet systeem (Maar wel één die dus ethisch helemaal in lijn is met de waarden van de community!)
  * Het systeem mag mensen niet uitsluiten, maar wel motiveren om deel te nemen aan het systeem
  * Het systeem mag rechten van mensen niet afnemen. Mensen zijn vrij. Altijd.
  * Het systeem mag mensen tot niets verplichten, dwang of drang uitoefenen.

```
TODO

[ ] Zeer helder uiteenzetten waar vrijwilligheid stopt en drang begint.
[ ] Een Tijdbank is een coöperatie
```

# Toekomst

Uitgaande van het feit dat een community ontstaat temidden van een samenleving waar fiat geld de norm is. Leden van de community leven mogelijkerwijs niet direct naast elkaar, maar wel in de buurt. Het liefst in dezelfde stad, regio of agglomeratie. De hoop is dat door het wantrouwen in het oplossingsvermogen van de politiek en een sterk inflatoir klimaat meerdere time banking initiatieven in Nederland ontstaan. Door de huidige sterk gepolariseerde samenleving is de hoop dat leden van de community dichter bij elkaar willen gaan wonen om zo meer met gelijkgestemden te zijn en dat daardoor een soepelere, meer efficiënte time banking community ontstaat. Dat kan op twee manieren gebeuren: of vanaf nul beginnen, land kopen en daarop verder bouwen aan de community òf gebruik maken van wat er al is, waardoor een bepaalde stad of regio aantrekkelijk wordt om als community lid in te vestigen. Uiteraard moet dit alles vrijwillig ontstaan, maar het is goed om een blik in de toekomst te werpen en te bedenken wat de omstandigheden moeten zijn om dit effect te bereiken.

# Fundamentele onderdelen van een community

Niet direct gerelateerd aan Time Banking, wel aan het opzetten van een community.

* Open Source Government: Een van Github geïnspirereerde omgeving, waar d.m.v. Git regels/wetten worden bijgehouden. Veranderen regels of wetten? Dan wordt dit middels een Pull Request met main gemerged. Op een PR kan gestemd worden door *alle* leden van de community. Community vertegenwoordiging zorgt voor toetsing aan de grondregels en is de enige die toestemming heeft tot het doorzetten van de PR naar main.
* Religie: Uiteraard is ieder lid van de community vrij om een geloof of levensbeschouwing naar keuze te beleiden, maar er is ook ruimte voor een nieuwe stroming: een op Boeddhisme geïnspireerde stroming, vertaald naar de moderne tijd.
* Relaties: Wordt er in de community getrouwd? Trouwen is in feite een contract dat je met elkaar aangaat. Liefst wil je graag dat het contract niet nodig is.
```
TODO

[ ] Wat als de relatie beëindigd is, en er zijn kinderen in het spel? 
[ ] Verdeling van saldo T$ bij relatie beëindiging?
[ ] Zorg van kinderen en impact op verdiencapaciteit?
```
* Internet: Een eigen, geïsoleerd internet?
* Politie
* Huisarts
* Tandarts
* Ziekenhuis
* Ambulance
* Brandweer
* Journalistiek
* Post- en pakketdienst
* ...
* Grondregels
  * Niet stelen
  * Geen pijn doen (fysiek of mentaal)
  * Geen schade maken
  * Jezelf niet uitgeven voor een ander
  * Discrimineer niet
  * Geen smaad of laster
  * Niet uitsluiten
  * Een mens is vrij. Altijd.
  * Niet dwingen
  * Niet dringen
  * Niet misleiden
  * ...
  * Kunnen regels eigenlijk ook positief geformuleerd zijn?
```
TODO

[ ] Juridische kaders omtrent de fundamentele onderdelen van een community
```

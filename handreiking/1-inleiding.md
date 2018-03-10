# Inleiding

## Wat is metadata?

Meta van het griekse μετά wordt gebruikt om aan te geven dat het een abstractie is van iets, gebruikt om deze aan te vullen. Het zegt iets over zichzelf. Metadata is 'data over data'. Ze beschrijft de inhoud van de data.

## Waarom metadata?

Zie onderstaand conservenblikje zonder etiquette. Als je een schap van deze blikjes in de winkel ziet staan, zul je pas na thuiskomst en na opening van het blikje zien wat erin zit. Op basis van kleur, geur en smaak kun je vaststellen wat er in het blikje zit. Of het (nog) verantwoord is om te eten, zal op basis van de geur en uiterlijk vastgesteld moeten worden. Of er ingrediënten in zitten die je niet lekker vindt of waar je allergisch voor bent kun je alleen proefondervindelijk ontdekken. Je zult echter nooit te weten komen Wie dit product heeft gemaakt. De meesten van ons zullen zo’n blikje dan ook niet kopen. 

![Voorbeeld van een blikje zonder label](images/Blikje.jpg)

Zo ook met data. Als je niet weet wat het voorstelt, welke actualiteit het heeft, wie de data gemaakt heeft en met welke kwaliteit het is vastgelegd, zal alleen de maker van deze data deze vragen kunnen benatwoorden.
Met metadata wordt de geografische dataset zo beschreven dat zoekopdrachten gericht kunnen worden op vragen als ‘wie, wat, waar, wanneer, waarom en hoe’. De metadata bevat details over de eigenaar van de geografische data, de kwaliteit en de geldigheid ervan, en hoe de data kan worden benaderd en gebruikt. 

De groeiende informatiebehoefte heeft geleid tot veel geografische datasets, –series en services met een grote diversiteit aan onderwerpen, thema’s en benaderingen. Gevolg van dit groeiende aanbod van geografische datasets (schatting voor Nederland ongeveer 200.000 datasets in 2007) is dat het voor gebruikers van geografische datasets steeds moeilijker is de juiste informatie te vinden.

Door de opkomst van Service Oriented Architecture is men genoodzaakt ook metadata van datasets en services vast te leggen. Doordat men rechtstreeks services kan benaderen, heeft men steeds minder rechtstreeks contact met de bronhouder om informatie over de gegevens te verkrijgen en is de behoefte aan goede metadata toegenomen.

In de kaderrichtlijn INSPIRE zie http://www.geonovum.nl/onderwerpen/inspire/wet-en-regelgeving-inspire wordt metadata voor de thema’s op het gebied van milieu ook wettelijk verplicht gesteld.

## Wat kun je ermee?

### Vinden

Metadata kan intern in een grote organisatie worden gebruikt om data te ontsluiten. Op basis van de beschrijvende kenmerken kan men de juiste dataset zoeken en in viewers of applicaties tonen en gebruiken.

### Hergebruik

Metadata kan voor andere organisaties de kwaliteit van de betreffende datasets inzichtelijk maken. Op basis van de metadata kan men beslissen of deze dataset of service te gebruiken is, of dat er zelf gegevens ingewonnen en gedigitaliseerd moeten worden.

### Verrijken

Op basis van de metadata kan men tot de conclusie komen dat de informatie die men wil vastleggen al grotendeels bestaat. Dit kan er ook toe leiden dat de al bestaande data wordt aangevuld met gegevens, waardoor de dataset voor een grotere doelgroep interessanter wordt.

### Beheer

Vanuit de beheer optiek biedt metadata ook de mogelijkheid om data goed te beheren. Zo kunnen alle datasets die niet meer actueel zijn makkelijk worden geselecteerd op basis van de metadata. Het is bijvoorbeeld ook mogelijk om alle datasets gemaakt door 1 persoon of instantie te selecteren.

### Continuiteit

Bij vertrek van een medewerker is de kennis over datasets en services niet verloren als deze is vastgelegd in de metadata. 

### Waardoor

- Efficiencywinst door hergebruik en verrijken van informatie
- Verbetering kwaliteit dienstverlening door het gebruik van juiste informatie
- Mogelijkheden tot beheer van de dataset
- Continuiteit van kennis over datasets en services

Metadata hoeft niet altijd direct toegang te geven tot de dataset of service, maar geeft wel aan waar deze dan te verkrijgen is.

![Quote Michiel Schram Grontmij/Sweco 2008](images/Textdubbelzondermeta.jpg)

## Waar vind je metadata?

Metadata kan je ontsluiten via een register of catalogus. Dit kan binnen een organisatie, maar ook nationaal of internationaal. Zo maak je het mogelijk om de metadata doorzoekbaar te maken en de data eventueel te tonen in een portaal. Een voorbeeld van een register is het [https://nationaalgeoregister.nl](Nationaal Georegister). Hierin is metadata van verschillende organisaties in Nederland opgenomen. Via het nationaal georegister kan iemand data zoeken, raadplegen en in een aantal gevallen ook direct verkrijgen;

![Nationaal Georegister](images/ngr.jpg)

### Zoeken (discovery) 

De eerste stap in discovery van databronnen is het zoeken van geografische data en services. Dit zoeken gebeurt in catalogues op basis van een zoekterm waarin databronnen met behulp van metadata zijn beschreven.

### Beoordelen (exploration, evaluation) 

Zodra een gebruiker een databron heeft gevonden, is de volgende stap om deze databron nader te onderzoeken (evaluation) en te bekijken of de databron voorziet in de behoefte van de gebruiker. Dit gebeurt door de aanvullende metadata te onderzoeken.

### Verkrijgen (exploitation, access, use) 
Zodra gebruikers de gewenste databron hebben gevonden en geëvalueerd, zijn er verschillende manieren om de databron te benaderen en gebruiken. Denk hierbij aan het downloaden of bestellen via e-mail of telefoon. Wanneer deze databron via een Geo-informatie Infrastructuur (GII) wordt benaderd zal er gebruik moeten worden gemaakt van uitwisselingsstandaarden middels informatiemodellen en services.
Ieder niveau in het register heeft haar eigen zoekmechanisme en maakt gebruik van een ander meta informatie niveau. Discovery metadata is de minimale hoeveelheid van informatie die de gebruiker moet opgeven om het resultaat van de zoekopdracht op aard en inhoud van de databron te kunnen beoordelen.

In een geo-informatie infrastructuur is een discovery mechanisme een online service die providers en gebruikers samenbrengt. Discovery mechanismen bieden gebruikers de mogelijkheid om geografische informatie, in de vorm van datasets, dataset series and services te vinden (discovery), te beoordelen (exploration) en te verkrijgen (exploitation).

## Toepassingen

Naast de zoekingang op de website van het register kan een register door andere applicaties ontsloten worden via de ‘achterkant’ (via een [API](https://nl.wikipedia.org/wiki/Application_programming_interface)). Op basis van standaard zoekprotocollen ([CSW](http://www.opengeospatial.org/standards/cat)) is het mogelijk om het register, aan te roepen via de zoekclient van een (web)toepassing. Dit kunnen toepassingen of websites zijn van specifieke communities, zoekmachines zoals Google/Bing, maar ook GIS desktop clients zoals ArcGIS/QGIS.

### Een Voorbeeld

De module [metasearch](https://docs.qgis.org/3.0/nl/docs/user_manual/plugins/plugins_metasearch.html) in QGIS is in staat het Nationaal Georegister te bevragen vanuit QGIS. Vanuit het zoekresultaat kan (indien beschikbaar) de gelinkte WMS kaartlaag aan het kaartvenster van QGIS toegevoegd worden.

![Portaal toepassingen](images/metasearch-splash.jpg)

### Nog een voorbeeld 

De [Nationale kaartviewer van Zwitserland](https://map.geo.admin.ch)). In deze viewer bevindt zich een centrale zoek ingang van waaruit je zowel naar locaties als datasets kunt zoeken. Voor het zoeken naar datasets wordt de Nationale catalogus bevraagd.

![Zwitsers nationaal kaart viewer](images/swisstopo.jpg)

## Opdracht discovery

Open http://nationaalgeoregister.nl

- Zoek op grondgebruik vervolgens op bodemgebruik en vervolgens landgebruik. Vergelijk de resultaten.
- Welke dataset kun je direct als service benaderen en welke kun je downloaden?
- In de metadata van het Planbureau voor de Leefomgeving (PBL) is de link opgenomen naar de mapserver van het PBL. Zoek deze link op.
- Welk trefwoord wordt het meest toegepast?

![Metadata gebruik](images/Metagebruik.jpg)

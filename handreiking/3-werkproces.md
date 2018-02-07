#Metadata in het werkproces

##Hoe maak je metadata?

###Metadata voor data

Je kunt op diverse manieren metadata aanmaken. Voor deze diverse manieren zijn er verschillende applicaties op de markt die voldoen aan het Nederlandse metadata profiel. Hieronder wordt beschreven hoe de metadata kan worden aangemaakt:

Metadata voor data invoeren via een metadata editor die ISO TS 19139 XML kan leveren
Metadata voor data toevoegen met behulp van een metadata editor van een catalogue 

Inwinnen meta.jpg

Deze methoden zijn hieronder beschreven om gebruikers de mogelijkheid te bieden een werkwijze te kiezen die past bij de organsatie.

###Metadata editor voor data

De Metadata editor is een applicatie (meestal een desktop client of een editor tool uit een GIS-applicatie) die de gebruiker ondersteund in het opzetten van metadata documenten. Door gebruik te maken van een tool wordt het compleet en valide opvoeren van de metadata afgedwongen. Hoe gebruiksvriendelijker de tool, des te gemakkelijker het is voor de gebruiker. Veel metadata editor tools zijn geïntegreerd in de software waarmee ook de ruimtelijke data wordt gemaakt. Dit heeft als voordeel dat dan de inherente en impliciete metadata al direct wordt overgenomen en niet meer handmatig hoeft te worden ingevoerd. Denk daarbij bijvoorbeeld aan de ruimtelijke extent, datum vervaardiging, etc. Een ander voordeel van een desktop tool is dat er een aantal zaken al standaard kunnen worden ingevuld, zoals naam van de organisatie, gebruikte referentiesysteem etc. Vaak zullen deze metadata elementen hetzelfde zijn. Als er voor bepaalde datasets hiervan wordt afgeweken kan het handmatig worden aangepast.

Er zijn ook stand-alone tools, voor desktop of via internet beschikbaar. Deze tools hebben als voordeel dat ze makkelijk te benaderen/ installeren zijn en voldoen als er weinig datasets zijn die beheerd worden. Wanneer een metadata document voor het eerst word gemaakt, lijkt deze optie het meest eenvoudig. Het kan echter wel de meest kostbare manier zijn om een metadata document te maken. De gebruiker voert alle vereiste metadata elementen met de hand in en publiceert daarna het document als een valide ISO 19115/19139 document. Het is afhankelijk van de software in hoeverre de gebruiker wordt ondersteund gedurende dit proces.

###Metadata editor voor data via de catalog client

Een metadata editor is geen verplicht onderdeel van een register, maar wordt wel vaak toegepast bij een register. Het voordeel is dat de metadata direct gepubliceerd wordt in het register, maar het heeft geen directe relatie met de data. De metadata kan worden opgevoerd, of, met een andere methode verkregen metadata, worden bewerkt .

##Metadata voor services

De metadata voor services kan op de volgende drie manieren worden gemaakt:

1. Metadata voor de service aan het capabilities document van een service toevoegen
1. Metadata voor services invoeren via een metadata editor die ISO TS 19139 en CSW ISO metadata AP XML kan leveren
1. Metadata voor services toevoegen met behulp van een metadata editor van een catalogue

Deze drie mogelijkheden zijn achtereenvolgens beschreven om gebruikers de mogelijkheid te bieden een methode te kiezen die past bij de organisatiemogelijkheden.


###Capabilities document
Elke OGC service (WMS, WFS, WCS, etc.) heeft altijd een capabilities document. Hierin wordt bij het aanmaken van de service al automatisch enkele metadata elementen van de service opgenomen. Deze publicatie methode is erop gericht om gebruik te maken van de metadata informatie uit de capabilities document.
Deze publicatie strategie is vooral voor organisaties en gebruikers van belang die een beperkt aantal services willen publiceren (een OGC catalogue service is dan snel een te zware oplossing gezien het aantal te publiceren services, zie 2.2.3). Dit is een eenvoudige manier voor metadata publicatie.


De capability bevat metadata mogelijkheden om de service zelf en van de beschikbaar te stellen data te beschrijven, echter niet alle verplichte metadata elementen kan worden opgenomen. Dit wordt voor WMS en WFS uitgewerkt in bij de metadata elementen.
Resultaat: Een Capabilities document


###Metadata editor
Dit is een applicatie (meestal een desktop client of een editor tool uit een GIS-applicatie) die de gebruiker ondersteund in het opzetten van metadata documenten. Door gebruik te maken van een dergelijke applicatie wordt het compleet en valide opvoeren van de metadata afgedwongen. Veel metadata editor tools zijn geïntegreerd in het productieproces waardoor veel metadata in het werkproces wordt gegenereerd .
Beginnend van scratch lijkt een metadata editor heet meest eenvoudig, maar is de meest kostbare manier om een metadata document te maken. De gebruiker voert namelijk alle vereiste metadata elementen handmatig in en publiceert daarna het document als een valide CSW2 AP ISO document (ISO 19115/19139 en ISO 19119 encoding).
Het is afhankelijk van de applicatie in hoeverre de gebruiker wordt ondersteund gedurende dit proces.
Elke OGC service (WMS, WFS, WCS, etc.) heeft altijd verplicht een capabilities document. Metadata editors kunnen deze informatie uitlezen zodat slechts enkele resterende gegevens handmatig ingevuld dienen te worden. 
De capabilities methode kan in combinatie met een editor gebruikt worden. Hiervoor kan het werkproces gehanteerd worden dat in de onderstaande figuur is verbeeld (uitgewerkt voor WMS).


Opzetten van een CSW2 AP ISO document met een metadata editor


Resultaat: een valide CSW2 AP ISO document.


###Metadata editor via de catalog client
Een metadata editor is geen verplicht onderdeel van een catalogues service. maar wordt wel vaak toegepast bij een catalogue service. Met de metadata editor kan de service metadata worden opgevoerd of, met een andere methode verkregen metadata, worden bewerkt.
De capabilities methode kan in combinatie gebruikt worden. Hiervoor kan het volgende werkproces gehanteerd worden.

Opzetten van een CSW2 AP ISO document met een metadata editor via de catalog

Het verschil met de editor methode is dat de metadata direct gepubliceerd is in de catalogue.

Resultaat: Een metadata record in een catalogue die CSW2 AP ISO ondersteund.

##Waar in werkproces

Er zijn meerdere doeleinden waarvoor data gegenereerd wordt. Voor projecten, als werkbestand, voor analysedoeleinden, voor vastleggen van beleid of feitelijke gegevens ten behoeve van producten of processen. 
Datainwinnen.jpg

Vaak is data alleen voor de maker of voor een beperkte interne groep van belang aangezien het een tijdelijk bestand is. Als data door meerdere mensen gebruikt en uitgewisseld gaat worden of een formele status heeft, is een goede ontsluiting en beheer van belang.


Binnen de organisatie zal afgesproken moeten worden van welke data er metadata wordt vastgelegd.


Metadata is onder te verdelen in inhoudelijke metadata, technisch en beheersmatige metadata. Het is van belang dat de metadata wordt ingevuld door mensen die zowel inhoudelijke kennis van de dataset hebben als door meer technische geo specialisten. Ook zal er iemand verantwoordelijkheid hebben voor de kwaliteit en het publiceren. Vaak zal dit betekenen dat meerdere mensen een bijdrage leveren aan het tot stand komen van de metadata. Verantwoordelijkheden en rollen voor (delen van)metadata zullen moeten worden vastgelegd.


Metadata zal idealiter onderdeel uitmaken van het data of service aanmaak- en beheer-proces. Dit zal dan zo ingericht dienen te worden dat de verschillende aspecten van de metadata door desbetreffende personen ingevuld en beheerd kan worden. Het aanmaken en beheren van metadata is (onderdeel van) een werkproces.


Een deel van de metadata is automatisch te genereren uit de data. Het verdient de voorkeur om bij grotere hoeveelheden data de te gebruiken software hier zoveel mogelijk gebruik van te laten maken. Het gebruik van default instellingen voor bijvoorbeeld de naam van de organisatie verdient de voorkeur.

##Tips voor inwinnen metadata

Begin in een zo vroeg mogelijk stadium met het vastleggen van metadata. Op het moment dat de dataset aangemaakt wordt is er vaak contact met de inhoudelijk specialist. Deze kan dan de inhoudelijke metadata aanleveren.


Het moment waarop de opdracht wordt gegeven om de data te publiceren is een goede mogelijkheid om de metadata te controleren en eventueel te vervolmaken.

##Publiceren van metadata

Nadat de metadata is ingewonnen en vastgelegd kan het gepubliceerd worden. Er zijn drie methoden voor het publiceren van metadata;


1. Het aanmaken van nieuwe metadata in de metadata editor van een register
2. Bestaande metadata als XML importeren
3. Bestaande metadata uit de capabilities van een service uitlezen


De eerste twee mogelijkheden gaan uit van invoer van metadata direct in een register. Er is geen sprake van een geautomatiseerde verbinding met broninformatie die wijzigingen signaleert en doorvoert.


###Metadata editor

Als een organisatie nog niet beschikt over metadata kan gebruik worden gemaakt van de metadata editor die is opgenomen in een register. Hiermee kan metadata volgens de Nederlandse metadata standaard voor geografie versie 1.2 worden ingevuld. Het is ook mogelijk metadata voor services volgens het Nederlandse metadata profiel op ISO 19119 voor services versie 1.1 vast te leggen.


###Importeer metadata XML

Een meer geavanceerde manier om metadata op te nemen in het een register, is door het uploaden van een XML. Deze methode is vooral geschikt voor gebruikers die met behulp van een eigen tool metadata hebben aangemaakt en deze in XML formaat kunnen wegschrijven.


###Metadata uit de capabilities van een service

Elke OGC service (WMS, WFS, WCS, etc.) heeft een capabilities document. Hierin wordt bij het aanmaken van de service al automatisch enkele metadata elementen van de service opgenomen. Deze methode is erop gericht om gebruik te maken van de metadata informatie uit het capabilities document.
Dit is vooral voor organisaties van belang die een beperkt aantal services willen publiceren (een OGC catalogue service is dan al gauw een te zware oplossing gezien het aantal te publiceren services,). Dit is een eenvoudige manier voor metadata publicatie.
De capabilities file bevat de mogelijkheid om metadata van de service zelf en de verwijzing naar de metadata XML van de te serveren data te beschrijven, echter niet alle verplichte metadata elementen van het Nederlandse profiel op ISO 19119 kan men hier in kwijt.


Capabilitiestoisoap.jpg

In een register kan de capabilities file worden uitgelezen en omgezet naar ISO19119/CSW 2.0.2 ISO AP. Deze metadata kan verder worden aangevuld met behulp van de editor.

##Harvesting

Harvesting methoden
Harvesten is het mechanisme dat metadata naar de catalogus ‘ trekt ‘ (kopieert). Deze functionaliteit zorgt dat de metadata, waarnaar in de catalogues wordt verwezen, worden opgenomen en bijgewerkt. Het is de taak van de catalogues service om op de locatie de metadata op te halen en te verwerken in de catalogues.
Er zijn drie manieren om te harvesten;


1. Bestaande metadata als XML laten harvesten
2. Bestaande metadata vanuit een catalogue harvesten
3. Capabilities harvesting

Het harvesten is een proces wat regelmatig uitgevoerd kan worden, bijvoorbeeld eens per dag of per week. Tijdens het harvesten wordt de data gesynchroniseerd. Een catalogue is in staat om metadata die is toegevoegd, verwijderd of geupdated op de bronlocatie te herkennen en de centrale catalogue database hierop aan te passen.

 

Tijdens het harvesten is het mogelijk een filter toe te passen, waardoor niet alle metadata, maar een beperkte set van de remote catalogue wordt gekopieerd. Er kan bijvoorbeeld een filter worden toegepast op vrije text, onderwerp, titel en samenvatting.

 

Het harvesting mechanisme is gebaseerd op het concept van universally unique identifier (uuid) ende wijzigingsdatum. Door de uuid’s is het mogelijk van verschillende bronnen te harvesten. Ook al komt bepaalde metadata op meerder bronnen voor wordt deze dank zij de uuid maar één maal en dankzij de wijzigingsdatum alleen de meest actuele versie opgenomen in het register.


Metadata XML harvesten
Voor organisaties die weinig metadata beheren, is het implementeren en beheren van een catalogue weinig rendabel. Aangezien het plaatsen van XML files in een web accessible folder gemakkelijk is, is dit een laagdrempelige oplossing om meer metadata documenten beschikbaar te maken voor anderen die geharvest kunnen worden. Hiervoor wordt het web DAV (Distributed Authoring and Versioning) protocol om metadata van een DAV server te harvesten gebruikt. WebDAV definieert zogenoemde collecties van files op een webserver. Deze kunnen gebruikt worden om meerdere metadata documenten tegelijk te harvesten.
WebDAV is een protocol en kan door systeembeheerders op een standaard webserver geconfigureerd worden. Daarbij dient de folder zonder autorisatie benaderd te kunnen worden. Bij de configuratie wordt een URL gedefinieerd waar de catalogue uit kan harvesten, bijvoorbeeld:


http://www.RIVM.nl/webdav
Web accessible folder complying with WebDAV (IETF, RFS 2518)

 

Hierdoor wordt het mogelijk om Web accessible folders als bron te definiëren en te harvesten. 
Metadata exporteren als een XML file is een gebruikelijke functionaliteit bij metadata tools. Veel metadata documenten zijn op deze manier beschikbaar bij (overheids-)organisaties. Andere partijen willen deze informatie ook gebruiken.
In verschillende folders kan men metadata voor verschillende doelgroepen plaatsen zodat voor de verschillende toepassingen uit één folder alle data geharvest kan worden.

 

Metadata vanuit een catalogue harvesten
Als een organisatie een eigen catalogue heeft kan van deze catalogue informatie overgenomen worden waarbij de metadata records worden gekopieerd naar bijvoorbeeld het nationaal georegister. De harvest operatie van de catalogue service is erop gericht om records in het nationaal georegister te creëren of te updaten. Hiervoor wordt de CSW standaard gebruikt. CSW staat voor Catalogue Services for the Web en is een zoek interface voor catalogues ontwikkeld door het Open Geospatial Consortium. NGR ondersteunt versie 2.0.2 ISO AP van deze standaard.

 

Bij het processen van een harvest request door de CSW worden de volgende stappen doorlopen:
1. De CSW gaat naar de URI waar de metadata resource is vastgelegd
2. Parses de resource
3. Creëert of verandert metadata records in de catalogue om de resource te registeren.

 

  Geharvest vraagpatroon.jpg

 
Als recource type, die aangeeft welk type resource geharvest wordt, kan dan http://www.opengis.net/cat/csw/2.0.2 opgenomen worden.

 

Deze operatie wordt een keer uitgevoerd of periodiek (elke nacht) afhankelijk van de instellingen die de beheerder van de catalogue heeft ingeregeld.

 

In het CSW 2.0.2 publicatie schema is de harvesting operatie als volgt gedefinieerd:

Harvestendefcsw.jpg


Capabilities harvesten

Het is de functionaliteit van de catalogue om de capabilities te kunnen harvesten. De meeste catalogues kunnen bijvoorbeeld de URL opslaan en dan periodiek de metadata harvesten. De metadata uit de capabilities elementen worden getransformeerd naar een CSW2 AP ISO document .

Capabilitiestoisoap.jpg
XSLT transformatie van WMS capabilities document naar CSW2 AP ISO document


In het CSW 2.0.2 publicatie schema is de harvesting operatie voor dit type resource als volgt gedefinieerd:

  Harvestcsw.jpg

Dit bevraagt de catalogue service om de resource “http://www.myhost.com?Service=WMS&amp;Request=GetCapabilities” van het type “http://www.opengis.net/wms” periodiek elke maand (P1M) te harvesten. Het mime type van de resource is “application/xml”.

Gedistribueerd vraagpatroon
 
Hoewel gedistribueerd zoeken niet tot harvesten behoort in de zin van een catalogue service, wordt het wel beschreven in deze paragraaf. De reden daarvoor is dat deze functionaliteit vaak wordt beschreven als catalogue-to-catalogue harvesting, maar niet te vergelijken is met de harvesting operaties beschreven in de voorgaande paragrafen.

Gedistribueerd vraagpatroon.jpg

Gedistribueerd zoeken: de geformuleerde vraag wordt naar de lokale en elke andere bekende catalogus gestuurd met een specifieke bevraagdiepte (met betrekking tot een specifieke netwerktopologie). De resultaten worden geïntegreerd en getoond aan de cliënt. De metadata records van andere catalogues worden niet gekopieerd naar de eigen catalogue. Catalogue records blijven bij de bron.

De gedistribueerde vraag is, op interface niveau, onderdeel van de GetRecords operatie van de catalog service. Deze operatie is onderdeel van de Discovery klasse (en niet van de Manager klasse zoals de harvest operatie).

In het CSW 2.0.2 publicatie schema is de gedistribueerde vraag operatie als volgt gedefinieerd:

Gedistribueerd vraag voorb.jpg

Het element “DistributedSearchType” bevraagt de catalog service om de “GetRecords”-request door te geven aan alle catalog services.

Deze functionaliteit kan worden uitgebreid met een catalog implementatie om metadata records te ”cachen” van een remote catalog. Dit is dan vergelijkbaar met catalogue-catalogue harvesting. Dit kan alleen worden uitgevoerd op implementatie niveau; dit is geen functionaliteit gedefinieerd op specificatie niveau en dus geen standaard benadering.

##Valideren

De metadata van data(services) kunnen gevalideerd worden op:


http://validatie-dataspecificaties.geostandaarden.nl/genericvalidator/content/domain/24


Hiermee kan men achterhalen of men aan de Nederlandse profielen voldoet. 
 Validator.png

 ##Opdracht werkproces

 Een dienst heeft duizend medewerkers, van wie er honderd met GIS werken, veertien servers en zevenhonderd gigabyte aan geodata. De dienst heeft een achterstand van 135 mensjaar om metadata in te voeren (807.000 bestanden x 0,25 uur/1500 uur = 135 mensjaar). Een scan leerde dat geodata explosief groeit vergeleken met algemene data, maar ook dat er 15% dubbelingen zijn en daarnaast 75% van de geodata bij externe partijen vandaan komt. 
Bij deze dienst heeft 80% van de geodata geen metadata. Ongeveer 18% van de data heeft metadata conform CEN standaard. 
Stel voor bovenstaande case een plan op om de achterstand weg te werken.
Stel voor bovenstaande case een plan op om nieuwe geodata van metadata te voorzien
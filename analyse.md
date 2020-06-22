# Analyse van de antwoorden

## Wat moet de scope van Digikoppeling zijn?

![Vraag 1.0](media/vraag_1_0_chart.png "Opgetelde scores van vraag 1.0")

`Het valt op dat de leden kiezen voor een scope van Digikoppeling die óf heel breed is (al het verkeer met de overheden)  óf beperkt moet worden tot closed data tussen overheden onderling.`

### Motivatie voor scenario 2 (al het dataverkeer tussen en met overheden)

*enkele quotes (zie de hoofdstukken voor de volledige reacties)*

- onderscheid maken in dit verkeer is steeds minder relevant. 
- gegevensregistraties en transactiesystemen van de overheid worden gebruikt door zowel overheden als door private partijen.
- in veel client applicaties wordt altijd een combinatie van open en closed data getoond
- heeft een afhankelijkheid naar het beheervraagstuk: Als Logius beheerder en de  community het Tecnisch Overleg DK dan scope van DK scenario #2 om ook aan te sluiten bij de functionele toepassingsgebieden van REST standaarden/profielen.
- Het is wenselijk om generieke beveiligingsvoorschriften te hebben voor DK als REST
- er moeten profielen komen voor enerzijds open-data en anderzijds closed-data.

### Motivatie voor scenario 3 (uitwisseling van closed Data tussen overheden onderling)

- ook voor (semi) publieke sector en serviceproviders onder verantwoordelijkheid van de overheid
- er zijn voordelen in het gebruik van Digikoppeling standaard, inclusief authenticatie / beveiligingsaspecten
- als er een alternatief is (NEN3610 of API of ..) is er géén verplichting om DK te gebruiken
- geen voorzieningen delen met de markt
- dit overleg heeft niet de capaciteit om die verplicht te stellen. Eerder volgt de overheid de markt-standaarden.

### Eén ander scenario werd genoemd

- de uitwisseling van data tussen overheden onderling en met organisaties die een publieke taak vervullen. Of de data open of gesloten is maakt daarbij niet uit

## Behoefte waarin Digikoppeling voorziet

`Standaardisatie leidt tot meer duidelijkheid, betere interoperabiliteit, eenvoudiger toegang tot gegevens, lagere kosten, veiligheid en betrouwbaarheid.`

*enkele quotes (zie de hoofdstukken voor de volledige reacties)*

- duidelijkheid over koppelen van systemen tussen en met de overheid
- interoperabiliteit, voorkomen dat ieder voor zich bilateraal afspraken moet maken
- de toegangsbarriere voor nieuwe toepassingen voor reeds beschikbare gegevenssets gaat omlaag
- standaardisatie leidt tot lagere kosten en eenvoudig aansluiten.
- gestandaardiseerde beveiliging en interactiepatronen 
- kern overeind houden: interoperabel, veilig en betrouwbaar verkeer o.b.v. identificatie, authenticatie en vertrouwelijkheid
- pas puur de internationale standaarden toe en beperk zo min mogelijk

## Waar willen we heen met Digikoppeling?

`Verschillende opvattingen. Het is lastig een tendens te herkennen of een gezamenlijk thema te ontwaren: Behoud het voordeel van een gedragen standaard, het inbedden van Restful APi's is gewenst, liever geen product, maar blijf bij een specificatie, volg de praktijk op de voet.`

*quotes (zie de hoofdstukken voor de volledige reacties)*

- alles opnemen wat gaat over het makkelijker / goedkoper uitwisselen van gegevens tussen overheden en met de overheid. 
- en niet alleen papier maar ook ondersteuning met open source implementatie
- het opnemen van RESTful profielen past volledig binnen de oorspronkelijke doelstelling: uitwisseling van gegevens binnen de overheid
- niet koste wat kost de huidige technologische keuzes handhaven (ebMS en WUS), maar binnen de doelstellingen (veilig, betrouwbaar, interoperabel) actief doorontwikkelen 
- de technologische ontwikkelingen worden gevolgd, maar dan getoetst en eventueel opgenomen  binnen de transport, logistiek en beveiligings-scope van DK
- straks RESTFul API naast WUS/ebMS. Daarna JSON naast XML
- niet te breed trekken met NLX,  belangrijk is één centraal gedefinieerde standaard
- digikoppeling is een prima concept, wat in mijn beleving niet teveel op de schop hoeft.
- REST API's zijn voor veel zaken veel makkelijker te implementeren dan EBMS2, maar niet perse voor elke situatie ideaal. EBMS2 en WUS hebben ook voordelen. Voor asynchrone data / bestands uitwisselingen is EBMS2 gewoon een prima protocol
- blijf ook kritisch in wat Digikoppelign wel en niet moet regelen, betrek het TO daar ook bij
- Digikoppeling wordt meer een paraplu begrip
- de historische en nieuwe kandidaat profielen moeten duidelijk zijn, zowel de feiten als meningen
- DK moet een standaard moet blijven die onafhankelijk is van producten
- uitbreidingen op de DK standaard (inclusief de API standaarden) moeten worden getoetst, voordat ze als verplichting kunnen worden opgelegd.
- een goede structurering is het belangrijkste. De eerste stap moet een goed meta model zijn hoe eea door verschillende standaarden ingevuld wordt 
- EBMS3/AS4 heeft voor mij lage prioriteit, API (ADR) + extensions hoge prioriteit
- volgens mij is het verstandig om onderscheid te maken tussen de standaarden (beheerd door internationale organisaties) en het beheer van de DK standaard
- Digikoppeling standaardaardiseert de te gebruiken profielen. ADR standaardiseert ontwerprichtlijnen
- NLX als product past niet in de huidige DK standaard.
- ebMS3 is geen 'andere' standaard, hoort in één bolletje bij ebMS2.
- risico dat de bestaande DK standaarden onevenwichtig veel aandacht krijgen in huidige gremia. 
- DK gaat actief de migratie van DK naar ADR omarmen.
- de DK standaard wordt al breder, met meerdere keuzen. Belangrijk om helderheid te geven in wanneer welke standaard voorkeur heeft.
- kijk ook naar nieuwe ontwikkelingen zoals Haal Centraal en de nieuwe ZGW API 
- met een nieuwe blik op meldingen, ga nadenken over het uitfaseren van ebMS
- het opnemen van APIs binnen Digikoppeling lijkt mij een haalbaardere weg om te begaan dan het trachten één voorziening hiervoor te realiseren (NLX).
- digikoppeling (of een andere naam...) zou duidelijkheid moeten geven hoe gegevens wordt uitgewisseld met of tussen overheden.
- er zijn al ontwikkelingen rondom NLX, Common Ground, etc. die tot een gezamenlijke afsprakenset zal leiden.
- wij zullen vooral WUS en API gaan gebruiken, dus API standaarden opnemen Ja. NLX niet opnemen als standaard
- JWT gaan wij zeker gebruiken.

## Hoe moeten we Restful APi's opnemen in Digikoppeling?

`Maak geen onderscheid in meldingen en bevragingen. Denk eerder in interactiepatronen, CRUD, Resources en betrouwbaarheid. Beschrijf best practices voor business transactions.`

*enkele quotes (zie de hoofdstukken voor de volledige reacties)*

- stap af van meldingen en bevragingen, maak onderscheid in synchroon, asynchroon en reliable. En alles mét en zonder authenticatie(signing)  en beveiliging (encryptie).
- het onderscheid tussen bevraging en melden is verouderd
- het koppelen van de technologische implementatie aan het 'type' (messaging, webservice, resource) lijkt niet verstandig. Beter is om patronen in gegevensuitwisseling te vertalen naar profielen voor elk type stack
- geef aan op basis van de business case wanneer welke technologie toegepast dient te worden
- maak een onderscheid tussen doel(registreren/bevragen), interactiepatronen(asynchroon/synchroon) en transport(ebMS/WUS/REST)
- een menukaart met standaarden die allemaal op gebieden sterke en zwakke punten hebben
- asynchrone Messaging: EBMS, Bevragen van gestructureerde datasets: WUS, Eenvoudige API's: REST.
- Ik zou de focus niet leggen op Restful API's maar op de Create, Read, Update en Delete operaties op de records in de dataset.
- messaging is niets anders dan het uitvoeren van 2 operaties en het vastleggen van de transacties. Hetzelfde resultaat kan worden bereikt met een webservice of de aanroep van een resource dmv een REST api.
- een restful api is niet vergelijkbaar met meldingen of bevragingen of met het begrip Messaging of Webservice. 
- het doel moet ook zijn om te bevragen (en muteren) bij de bron
- het belangrijkste stuk ontbreekt, de business transaction
- mutaties kunnen als business transacties synchroon worden uitgevoerd. In plaats van gegarandeerde aflevering, wordt gecontroleerd of de mutatie correct is verwerkt.
- de vraag is niet welke typen protocollen DK ondersteunt (messaging, webservice, resource, feit, ..), maar welke typen business transacties er zijn
- ik zou overigens verwachten dat binnen Digikoppeling een http-profiel wordt gedefinieerd voor het gebruik van APIs wat afgestemd is op de ADR.
- goede vraag, geen idee :-)
- er moet apart een resource-based profiel beschreven worden op basis van Restful API. Hierbij moet er speciale aandacht worden besteed aan Notificatie en/of Meldingen.
- beschrijf per protocol de stack, maar laat de koppeling met de toepassing los

## Nabranders

`een aantal respondenten maakte van de mogelijkheid gebruik om een aantal extra opmerkingen te plaatsen`

*enkele quotes (zie de hoofdstukken voor de volledige reacties)*

- zorg dat er voldoende referentie-implementaties en testmiddelen zijn om de conformiteit aan de standaarden/profielen te testen.
- onderzoek ook specifiek de rol die intermediairs kunnen hebben in het ecosysteem
- het moet duidelijk zijn wat je met een API wel kan wat met ebMS of WUS niet kan in functionele of non functionele zin
- met NLX kan je een API 6000x per seconde aanroepen, met DK kan je 6 ebMS berichten per seconde uitwisselen.
- dit roept wel weer vragen op hoe de DK architectuur zich verhoudt tot NORA en de NORA katernen.
- veel succes

![Deelname](media/aantalreacties.png "Ik doe graag mee on de discussie over API's in Digikoppeling")

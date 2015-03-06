Werken met discipline modellen
===============================
**aanspreekpunt:**

Hans Hendriks
hhs@debimspecialist.nl

**samenvatting:**

- discipinemodellen kúnnen bestaan uit meerdere aspectmodellen
- één centraal model voor een project is niet effectief
- losse modellen efficient samenvoegen werkt het meest effectief

**doelgroep:**

Elke modelleur en projectmanager

Deze pagina is een weergave van de open source ontwikkelomgeving op github. U kunt een bijdrage leveren door een ‘pull request’ te sturen op [github](https://github.com/BIM-Handboek-NL/Werken-met-disciplinemodellen), of het aanspreekpunt van deze pagina te benaderen via e-mail.

----------
###Inleiding
Een BIM model wordt vaak in eerste beeldvorming gezien als 1 bestand. Hieronder toelichting over het werken met discipinemodellen, een methodiek die nu (anno 2015) als meest succesvolle manier wordt gebruikt in praktijk.
Dit hoofdstuk wil middels “Best practices” rondom het samenwerken aan een gezamenlijk BIM model, bestaande uit diverse BIM discipinemodellen.

###Onjuist beeld van BIM in een project:
•	Iedereen werkt in zelfde bestand
•	Iedereen werkt met dezelfde softwareapplicatie, zelfde versie daarvan, met zelfde instellingen.
•	ICT & Performance lijken in eerste instantie geen probleem
•	Iedereen ziet alles, continue “real time” ontwikkelen, zodra een andere discipline iets doet
•	Alles is voor iedereen toegankelijk, ook vaak verwacht “in de cloud”
 
###Hoe wordt er in praktijk dan gewerkt?
In de praktijk blijkt dat er anders gewerkt wordt, omdat bovenstaande manier (nu, anno 2015) niet realistisch is en niet effectief blijkt.
Uit diverse praktijkprojecten blijkt;
-	Dat gedurende het proces diverse softwareapplicaties worden gebruikt.
-	Dat het soms niet wenselijk is om alles real-time te delen (Als voorbeeld een architect die nog bezig is alternatieve scenario’s te ontwerpen, deze informatie is dan waarschijnlijk nog niet nodig voor andere disciplines)
-	Het qua performance beter is om met (meerdere) kleinere bestanden te hebben, en alleen die bestanden te openen die relevant zijn
-	Het qua verantwoordelijkheid en juridische aspecten het in meeste gevallen beter is om duidelijke afbakening te hebben wie verantwoordelijk is over opgebouwde informatie en de extracten (b.v. de afgeleide tekeningen) daarvan.
-	Niet alle data ontstaat, of wordt ontsloten via (BIM) CAD applicatie
-	Niet alle project betrokken zijn even ervaren en deskundig
-	Niet alle partijen hebben alle informatie nodig. Vaak is een “subset” aan informatie voldoende.
-	Etc.
-	Etc.

Natuurlijk is het mogelijk om een (klein) gedeelte van het proces (b.v. tijdens ontwerpfase) of een klein gedeelte van het totaal (b.v. alleen bouwkundig en constructie) in 1 bestand uit te werken, indien partijen over zelfde software, zelfde versie en daarvoor geschikte middelen ICT beschikken. Echter de praktijk wijst uit dat het werken met discipinemodellen de meest gangbare, realistische manier is. We noemen dit ook wel “*There is no central BIM model!*”. 
Voor toelichting zie: http://www.slideshare.net/berlotti/there-is-no-central-bim-model 

##Definitie van disciplinnemodellen
Het werken met diverse disciplinnemodellen wordt internationaal ook wel werken met Reference models of “Reference View” genoemd.
http://www.buildingsmart-tech.org/specifications/ifc-view-definition/ifc4-reference-view/ifc4-rv-objective 
 
![disciplinnemodellen](https://raw.githubusercontent.com/BIM-Handboek-NL/Werken-met-disciplinemodellen/master/images/2012discipinemodellen.png)


Toelichting bovenstaand figuur:

**Rechts**: Diverse partijen maken hun eigen model aan conform de projectafspraken. Een duidelijke demarcatie is aan te bevelen. Vanuit ieder disciplinnemodel genereert de verantwoordelijke partij zijn eigen extracten (gebruikelijke output zoals tekeningen, lijsten, etc.)

**Midden**: Op gezette tijden wordt een levering van de disciplinnemodellen verwacht. In de praktijk blijkt dat het handig is om een DMS (Document Management Systeem) te gebruiken om bestanden centraal op te slaan, en via internet toegankelijk. Ook om allerlei andere documenten zoals extracten als tekeningen, notulen, vergunningaanvraag, etc. centraal op te slaan.
Een andere manier is om een modelserver te gebruiken voor deze centrale opslag van BIM disciplinnemodellen. Een BIM modelserver kent een object georiënteerde manier van opslag.  

**Links**: Door het samenvoegen van alle disciplinnemodellen ontstaat een “*Federated Model*”. Ook wel een aggregate model genoemd.

    Federated Model means a Model consisting of linked but distinct component Models, drawings derived from the Models, texts, and other data sources that do not lose their identity or integrity by being so linked, so that change to one component Model in a Federated Model does not create a change in another component Model in that Federated Model.” 
    Bron:  http://www.lexology.com/library/detail.aspx?g=eaf3ba31-fa41-4e46-b60f-5bac1963f527 

Dit totaalmodel kan worden gebruikt voor visualisatie, Clashcontrole, hoeveelheden, etc. etc.


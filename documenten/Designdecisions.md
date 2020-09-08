**Design decisions**


All Architecture principals and models of the Common Ground are leading. Within the technical, time and financial possibilities we maximize our compliancy to this architecture 

**NLX**

We gebruiken NLX voor elke call waarbij vertrouwelijke gegevens worden opgevraagd / waarover verantwoording afgelegd moet kunnen worden. In overige situaties gebruiken we NLX waar dit handig is.

**Versioning**

We hanteren semantic versioning. 
We hanteren https://docs.geostandaarden.nl/api/API-Strategie/#versioning  als uitgangspunt voor versiebeheer

**Afbakening**

we onderzoeken of en in hoever de aangifte overlijden en verzoek verlof tot begraven binnen de scope kan - of misschien wel moet - worden opgepakt.

**ontwerpprincipes klantproces (klantreis)**

De klant heeft regie op haar eigen proces. De gemeente zorgt voor duidelijke aanvraag-eisen en ondersteunt de klant met tooling om de gegevens voor het voorzoek effectief en efficient voor te bereiden.

We faciliteren dit door het aanbieden van een component waarin de klant kan werken aan het formuleren van een verzoek. Dit is de begrafenisplannen. 

De planner:
- Reserveert direct datum en tijd op een locatie voor de ondernemer
- Ondersteunt de begrafenisondernemer bij het aanleveren van alle informatie die de gemeente nodig heeft
- Schrijft niet voor in welke volgorde de informatie wordt verzameld
- Maximaliseert de prefill van bij de overheid bekende gegevens
- Minimaliseert het gebruik van gegevens
- Voert vereiste toetsen zo mogelijk direct uit
- Regelt indien nodig instemming van derden (op onderdelen)
- Laat het aanpassen van gegevens toe totdat het verzoek is ingediend
- Maakt ondersteuning door een ambtenaar mogelijk
- Verwijderd het volledige verzoek als het niet wordt ingediend
- Staat corrigeren van gegevens toe
- De klant vraagt eigen gegevens op en geeft bij indienen toestemming tot verwerking

**Keuzes over het maken van zaken**


**Koppelingen vanuit de Begrafenisplanner**

- Zaken c.a. op basis van ZGW API
   - nader te bepalen


- Reserveren
	- Locatie -> locaties + beschikbaarheid worden in het locatie & agenda component van de begrafenisplanner geregeld
	
	
- Personen
	- Haal Centraal BRP bevragen op moment dat de API door de RVIG beschikbaar wordt gesteld
	- Conduction vertalen Haal centraal <-> StUF  API wordt gebruikt voor de MVP waarbij op een gemeentelijk datadistributie systeem wordt aangesloten.
	
- Toetsen wettelijke vereisten
	- verlof tot begraven

**Definities van rollen**

- Indiener: degenne die het verzoek instuurt; de organisator van de begrafenis, vaak de begrafenisondernemer.
- Aanvrager: Degene namens wie het verzoek wordt ingediend. Dit is meestal de nabestaande op wiens naam de overeenkomst/akte wordt gezet. Vaak degene die de factuur betaald.
- Rechthebbende: Degene die beschikken mag over een particulier- of familiegraf.
- Belanghebbende: andere persoon of organisatie die een andere relatie heeft bij het graf. Dit kan een belang zijn om geinformeerd te worden bij wijzigingen. Ook kan het zijn dat voor de gemeenterelevant is deze relatie te leggen, zodat gegevens bekend zijn als dit nodi is bv. de steenhouder van het grafmonument.
- Uitvaartverzorger: De persoon of organisatie die de uitvaart verzorgt en waar zo nodig contact mee moet worden opgenomen.

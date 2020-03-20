**Design decisions**


All Architecture principals and models of the Common Ground are leading. Within the technical, time and financial possibilities we maximize our compliancy to this architecture 

**NLX**

We gebruiken NLX voor elke call waarbij vertrouwelijke gegevens worden opgevraagd / waarover verantwoording afgelegd moet kunnen worden. In overige situaties gebruiken we NLX waar dit handig is.

**Versioning**

We hanteren semantic versioning. 
We hanteren https://docs.geostandaarden.nl/api/API-Strategie/#versioning  als uitgangspunt voor versiebeheer

**Afbakening**

we onderzoeken of en in hoever de aangifte overlijden en verzoek verlof tot begraven binnen de scope kan - of misschien wel moet - worden opgepakt.

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


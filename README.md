# Begrafenisplanner

# Product visie:
Met de begrafenisplanner realiseren we componenten op alle 5 architectuurlagen waarmee gemeenten een voorziening kunnen inrichten zodat begrafenisondernemers in staat zijn om via één ingang, volledig zelfstandig een begrafenis te regelen op elk van de 47 begraafplaatsen in Westfriesland.

**We digitaliseren de begraafplaatsadministratie om:**

* De dienstverlening aan begrafenisondernemers veel beter te maken.
* Onze (lokale) processen efficiënter uit te kunnen voeren en de backoffice te ontlasten.
* De digitale begraafplaatsadministratie eenvoudig op te schalen voor gebruik door andere begraafplaatsbeheerders.
* Aan te tonen dat we in staat zijn door samenwerking de administratieve lasten voor onze (regionale) klanten te verminderen.
* Aan te tonen dat componenten van de Common Ground een goede basis leggen voor het ontwikkelen van andere gemeenschappelijke dienstverlening.

**Afbakening**

De eerste aandacht gaat uit naar het organiseren van een begrafenis.
we onderzoeken of en in hoever de aangifte overlijden en verzoek verlof tot begraven binnen de scope kan - of misschien wel moet - worden opgepakt.

**design decisions**

de toe te passen design decisions zijn beschreven in [Designdecisions](documenten/Designdecisions.md)

# Te zetten stappen:
* Inventariseren van de (brede) klantreis van begrafenisondernemers en nabestaanden en de gemeentelijke dienstverlening daar goed in laten participeren.
* Regels en beleid rond overlijden en begraven omzetten in businessrules of procesinrichting.
* Hergebruik van binnen Common Ground ontwikkelde open source componenten en services.
* Inrichten van een geschikte infrastructuur.

# Randvoorwaarden:
* Voldoende beschikbare mensen en middelen.
* Actieve en betrokken stakeholders met gemeenschappelijke visie op het project.

# MVP
Op 1 oktober nemen we de begrafenisplanner in gebruik, die de functionaliteit zoals in MVP 1 is beschreven 
## Epics MVP 1
- [x] plannen van een begrafenis door een begrafenisondernemer op één van de gemeentelijke begraafplaatsen van Westfriesland 
  - [x] plannen van alle verschillende typen begrafenis
  - [x] Inzicht in de planning van de locatie (wanneer is waar plaats)
  - [x] Reserveren van een datum en tijd
  - [x] Toevoegen gegevens van overledene en belang- of rechthebbende personen (ophalen uit de BRP)
  - [ ] keuze voor specifiek deel van de begraafplaats of een specifiek graf
- [x] Toevoegen van opties voor het uitbreiden van de ceremonie, afhankelijk van de mogelijkheden van de begraafplaats
- [x] Opstellen van een overzicht van de (standaard) kosten
  - [ ] het betalen van de rekening valt nu nog buiten de MVP (mogelijk als optie opnemen binnen MVP)
- [x] Functioneel beheer op de applicatie/registratie, Waaronder:
 - [x] vaststellen van de lengte van de begrafenisceremonie
 - [x] Planningsystematiek per begraafplaats inregelen
- [x] Beheerder van de begraafplaats heeft een overzicht van alle geplande begrafenissen en de contactpersonen hiervan per begraafplaats

## Epics MVP 2
- [ ] Beheerder begraaflaats kan bevestigen van de geplande begrafenis
  - [ ] acceptatie is lastig als we de begrafenisondernemer zelfstandig willen laten plannen (dan wil deze en de nabestaande zekerheid hebben)
- [ ] De begrafenisondernemer levert alle aanvullende informatie aan om aan de wettelijke eisen voor begrafen en de registratie in het begraafplaatsregister conform wetgeving uit te voeren
  - [ ] aangifte overlijden en verzoek tot verlof tot begraven valt nu buiten scope van deze MVP. Oppakken in tweede fase.
 
## Overige Epics (niet binnen scope)
- [ ] Andere dienstverleners bieden ook hun gerelateerde diensten aan (bv. aula). Deze kunnen ook gereserveerd worden.
  - [ ] vraagt om afstemming met partners en toegang tot hun agenda

# Consultatie **OIN-Stelsel – Aanvraag nummerreeks Dezi-stelsel (verzoek CIBG)**

In het kader van het beheer en de doorontwikkeling van [**OIN Stelsel**](https://gitdocumentatie.logius.nl/publicatie/dk/oin/) houdt Logius een openbare consultatie.

Via deze consultatie nodigen wij u uit om feedback te geven op de standaard. De consultatie loopt tot __17/04/2026__

Voor het **OIN Stelsel** is een verzoek vanuit CIBG ingediend om de omschrijving van de bestaande (UZI) OIN-prefix voor zorgaanbieders aan te passen en een nieuwe prefix voor zorgverzekeraars toe te voegen in verband met de overgang naar het Dezi-register.

Met deze openbare consultatie bieden wij belanghebbenden de gelegenheid om kennis te nemen van deze nieuwe versie en te reageren op de bijbehorende wijzigingen.

## Reageren?

Feedback en suggesties zijn welkom via [**digikoppeling@logius.nl**](mailto:digikoppeling@logius.nl) of via [issues](https://github.com/Logius-standaarden/OIN-Stelsel/issues) op GitHub.

Help mee deze versie klaar te maken ter vaststelling.

## Wijzigingen

De volgende wijzigingen zijn onderdeel van de voorgestelde volgende release:
* Toekennen van een nieuw Prefix OIN voor ‘Dezi-register Zorgverzekeraars’.
* Aanpassing van de omschrijving van de UZI register prefix '00000009' naar ‘Dezi-register Zorgaanbieders’

(NB net zoals de huidige UZI nummers worden de DEZI nummer-reeksen niet in de centrale OIN register van Logius opgenomen) 

[Consultatieversie **19 maart 2026**](./OIN-Stelsel) <!-- Het document wordt gepubliceerd vanaf een `consultatie/` branch, zie CONTRIBUTING.md -->


## Toelichting

De aanvraag nummerreeks DEZI-Stelsel is een verzoek vanuit CIBG 

### Context
In de huidige situatie verstrekt het CIBG, namens de minister van VWS, vanuit het Unieke Zorgverlener Identificatie (UZI-)register en Zorgverzekeraars‑Identificatie‑ en Authenticatieregister (ZOVAR) certificaten aan zorgaanbieders en zorgverzekeraars t.b.v. het raadplegen van de Sectorale Berichtenvoorziening in de Zorg (SBV-Z) en gegevensuitwisseling binnen de zorgsector in het algemeen. 

Op termijn zal het UZI-register en ZOVAR vervangen worden door het Dezi-stelsel. Dezi staat voor De Zorgidentiteit. Meer informatie over Dezi valt te lezen op Over Dezi | Dezi. In het kort zal het CIBG in de toekomst zelf geen authenticatiemiddelen meer uitgeven, maar een stelsel beheren waar met meerdere middelen kan worden ingelogd. Voor deze aanpassing is een wetswijziging nodig. Het wetsvoorstel ligt momenteel in de Tweede Kamer en omvat tevens een verplichting dat alle zorgaanbieders en hun zorgmedewerkers op termijn van het Dezi-stelsel gebruik moeten maken. 

Voor systeem-tot-systeemcommunicatie wordt nu gebruik gemaakt van PKIo-servercertificaten uitgegeven door het CIBG. Het CIBG vervult daarbij de rol van Trust Service Provider (TSP) binnen het PKIOverheidstelsel. Het CIBG gaat op termijn stoppen met het uitgeven van certificaten, echter de behoefte aan systeem-tot-systeemcommunicatie en het gebruik van een unieke zorgidentiteit daarbij blijft bestaan. VWS beoogt deze taak over te laten aan de commerciële TSP’s binnen het PKIOverheidstelsel. Uit deze door commerciële TSP’s uit te geven servercertificaten moet onmiskenbaar blijken dat het gaat om een servercertificaat dat is uitgegeven aan een in het Dezi-register ingeschreven zorgaanbieder of zorgverzekeraar. Er moet dus een kenmerk vanuit het Dezi-register worden opgenomen. 

Het OIN wordt als beoogde oplossingsrichting hiervoor voorzien. Voordeel hiervan is dat de werkwijze van het opnemen van een OIN al bekend is bij de TSP’s vanwege de Digipoort certificaten. In het kader van de autorisatielijst BSN (ALB) levert het huidige UZI-register gegevens aan bij de RvIG. Alle zorgaanbieders (instellingen) die door het CIBG zijn getoetst en toegelaten komen daarmee automatisch op de autorisatielijst BSN te staan. Daarbij worden ze voorzien van een OIN, met een specifieke UZI-prefix.  

### Verzochte wijzigingen:

#### 1. Toekennen van een nieuw Prefix OIN voor ‘Dezi-register Zorgverzekeraars’.

Motivatie: In de uitwisseling van gegevens in de zorg in het wenselijk dat er een duidelijk onderscheid is tussen zorgaanbieders enerzijds en zorgverzekeraars anderzijds. In de bestaande opzet is dit verschil evident vanwege de scheiding tussen UZI-register en ZOVAR. In de nieuwe opzet is er sprake van één Dezi-register, en is dus een technisch onderscheid nodig, vandaar het verzoek voor een aparte Dezi-register prefix voor de zorgverzekeraars. Het is wenselijk om deze reeds voor livegang toe te kennen, zodat de systemen bij CIBG hierop kunnen worden ingericht en ook de (ICT-leveranciers van) zorgaanbieders en zorgverzekeraars en de TSP’s zich hierop kunnen voorbereiden.

#### 2. Wijziging bij livegang Dezi-register / ingangsdatum wet DIAZ:
Aanpassing van de omschrijving van de UZI register prefix '00000009'
naar ‘Dezi-register Zorgaanbieders’

NB: De in het UZI-register ingeschreven zorginstellingen worden voor livegang automatisch overgezet naar het nieuwe Dezi-register. De uitwisseling met RvIG in het kader van de autorisatielijst BSN (ALB) wordt hier dan ook op aangepast, de voeding van de ALB geschiet vanaf dat moment vanuit het Dezi-register.
Het CIBG zal zorgdragen voor publicatie van de OIN gegevens, deze hoeven dus niet via de Centrale OIN Raadpleegvoorziening te worden ontsloten. Wellicht kan er bij een bevraging van een Dezi OIN bij de centrale OIN raadpleegvoorziening wel worden verwezen naar het CIBG als bron, we bespreken graag de mogelijkheden met Logius.


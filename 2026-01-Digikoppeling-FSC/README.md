# Consultatie Digikoppeling / FSC (release 2026-1)

In het kader van het beheer en de doorontwikkeling van de Digikoppeling-standaard houdt Logius een openbare consultatie.  
Via deze consultatie nodigen wij u uit om feedback te geven op de standaard. De consultatie loopt tot 20 februari 2026.

## Digikoppeling
[Digikoppeling](https://www.logius.nl/onze-dienstverlening/gegevensuitwisseling/digikoppeling) is een set van standaarden die logistieke afspraken bevat voor elektronisch berichtenverkeer tussen (overheids)organisaties.

## Wijzigingen

De volgende wijzigingen zijn onderdeel van de voorgestelde volgende release.

### Digikoppeling Koppelvlakstandaard REST-API en FSC

#### Digikoppeling REST-API profiel
[:link: Consultatieversie 19 januari 2026](https://logius-standaarden.github.io/Openbare-Consultaties/2026-01-Digikoppeling-FSC/dk/api/)

Wijzigingen:
- Verwijzen naar ADR versie 2.1 
- Verwijzen naar FSC versie 2.0

#### FSC (Federated Service Connectivity)

##### FSC Standaard

De Federated Service Connectivity (FSC)-standaard specificaties beschrijven een manier om technisch interoperabele API-gateway-functionaliteit te implementeren, die federatieve authenticatie en veilige verbindingen omvat in een grootschalig dynamisch API-landschap.


##### FSC Core

Het core profiel van de FSC-standaard biedt functionaliteit:

- om Services te ontdekken;
- om verzoeken te routeren naar Services in andere contexten (bijv. van binnen organisatie A naar organisatie B);
- om autorisaties aan te vragen en te beheren die nodig zijn om verbinding te maken met genoemde Services;
- om de autorisatie te delegeren om verbinding te maken of Services te publiceren namens een andere organisatie.

Wijzigingen:

[:link: Consultatieversie 19 januari 2026](https://logius-standaarden.github.io/Openbare-Consultaties/2026-01-Digikoppeling-FSC/fsc/core/)

De core-standaard FSC specificeert de basis voor de werking van de standaard:
- [Add properties object to Grants & update hashing algorithm](https://github.com/Logius-standaarden/fsc-core/pull/25)
- [Nieuwe error codes in Open FSC](https://github.com/Logius-standaarden/fsc-core/pull/55)
- [Open FSC versie in het contract opgenomen](https://github.com/Logius-standaarden/fsc-core/pull/51)
- [Outway-autorisatie op basis van een domeinnaam](https://github.com/Logius-standaarden/fsc-core/pull/53)
- [Content hash improvement](https://github.com/Logius-standaarden/fsc-core/pull/24)
- [Certificate renewal](https://github.com/Logius-standaarden/fsc-core/pull/14)

##### Extensies
[:link: Consultatieversie Logging 19 januari 2026](https://logius-standaarden.github.io/Openbare-Consultaties/2026-01-Digikoppeling-FSC/fsc/logging/)  
[:link: Consultatieversie External Contract Reference 19 januari 2026](https://logius-standaarden.github.io/Openbare-Consultaties/2026-01-Digikoppeling-FSC/fsc/ext/)

Aanvullende functionaliteit wordt gestandaardiseerd in extensies en kan van toepassing zijn indien je FSC op een bepaalde manier wilt toepassen die de core (bewust) niet ondersteunt.

- [FSC logging update](https://github.com/Logius-standaarden/fsc-logging/pull/1)
- [FSC External Contract Reference extensie - nieuwe extensie voor een referentie naar een bestaand (papieren) contract](https://github.com/Logius-standaarden/fsc-external-contract-reference)

##### FSC test suite
De FSC test suite bevat een lijst met testdocumentatie die ontwikkeld is om de conformiteit en interoperabiliteit van de implementaties van FSC-componenten te waarborgen. Bij nieuwe features/wijzigingen in de core-standaard worden bijbehorende testen beschreven in de test suite. De testen voor het nieuwe properties-veld staan hieronder:

- [Test-suite FSC](https://github.com/Logius-standaarden/fsc-test-suite)
- [Bijbehorende test cases Properties](https://github.com/Logius-standaarden/fsc-test-suite/pull/3)

### Digikoppeling Beveiligingstandaarden en voorschriften
[:link: Consultatieversie 19 januari 2026](https://logius-standaarden.github.io/Openbare-Consultaties/2026-01-Digikoppeling-FSC/dk/beveilig/)

Wijzigingen:
- [XML Signing parameters conform NCSC voorschriften](https://github.com/Logius-standaarden/Digikoppeling-Beveiligingsstandaarden-en-voorschriften/pull/17)
- [TLS 1.3 status aangescherpt naar "Zeer aanbevolen"](https://github.com/Logius-standaarden/Digikoppeling-Beveiligingsstandaarden-en-voorschriften/pull/21)

## Reageren?
Reageren kan door middel van een issue of wijzigingsvoorstel op de repository of per e-mail aan [digikoppeling@logius.nl](mailto:digikoppeling@logius.nl).

Wij ontvangen graag inhoudelijke opmerkingen, vragen of suggesties uiterlijk 20 februari 2026.

## Meer informatie
Voor meer informatie zie [Digikoppeling Documentatie](https://www.logius.nl/domeinen/gegevensuitwisseling/digikoppeling/documentatie).

## Gerelateerde dienst(en)
[Digikoppeling](https://www.logius.nl/domeinen/gegevensuitwisseling/digikoppeling/)

# Publieke Consultatie Versie 2.0 Federated Service Connectivity (FSC)

Logius houdt een publieke consultatie voor Federative Service Connectivity (FSC). De consultatie loopt tot ... Feedback en suggesties zijn welkom via api@logius.nl of via issues op GitHub. Help mee deze standaard klaar te maken voor de versie 2.0


## Context

## Standaard

Logius houdt een publieke consultatie voor Federative Service Connectivity (FSC). De consultatie loopt tot ... Feedback en suggesties zijn welkom via api@logius.nl of via issues op GitHub. Help mee deze standaard klaar te maken voor de versie 2.0

De Federated Service Connectivity (FSC) standaard specificaties beschrijven een manier om technisch interoperabele API-gateway-functionaliteit te implementeren, die federatieve authenticatie en veilige verbindingen omvat in een grootschalig dynamisch API-landschap.

Het core van de FSC-standaard bereikt inter-organisationele, technische interoperabiliteit:

- om Services te ontdekken.
- om verzoeken te routeren naar Services in andere contexten (bijv. van binnen organisatie A naar organisatie B).
- om autorisaties aan te vragen en te beheren die nodig zijn om verbinding te maken met genoemde Services.
- om de autorisatie te delegeren om verbinding te maken of Services te publiceren namens een andere organisatie.


## Wijzigingen

De volgende wijzigingen zijn onderdeel van de voorgestelde release:

### FSC Core
De core standaard FSC specificeert de basis voor de werking van de standaard.
- [Add properties object to Grants & update hashing algorithm](https://github.com/Logius-standaarden/fsc-core/pull/25)
- [Nieuwe error codes in Open FSC](https://github.com/Logius-standaarden/fsc-core/pull/55)
- [Open FSC versie in het contract opgenomen](https://github.com/Logius-standaarden/fsc-core/pull/51)
- [Outway autorisatie op basis van een domeinnaam](https://github.com/Logius-standaarden/fsc-core/pull/53)
- [Content hash improvement](https://github.com/Logius-standaarden/fsc-core/pull/24)
- [Certificate renewal](https://github.com/Logius-standaarden/fsc-core/pull/14)

### Extensies
Aanvullende functionaliteit wordt gestandaardiseerd in extensies en kunnen van toepassing zijn indien je FSC op een bepaalde manier wilt toepassen die de core (bewust) niet ondersteunt.

- [FSC logging update](https://github.com/Logius-standaarden/fsc-logging/pull/1)
- [FSC External Contract Reference extensie - nieuwe extensie voor een referentie naar een bestaand (papieren) contract](https://github.com/Logius-standaarden/fsc-external-contract-reference)

### FSC test suite
De FSC test suite bevat een lijst met testdocumentatie die ontwikkeld is om de conformiteit en interoperabiliteit van de implementaties van FSC-componenten te waarborgen.
- [Test-suite in core standaard](https://github.com/Logius-standaarden/fsc-test-suite)
- [Bijbehorende test cases](https://github.com/Logius-standaarden/fsc-test-suite/pull/3)

## Reageren?

Reageren kan door middel van een issue op wijzigingsvoorstel op de [repository](https://github.com/Logius-standaarden/fsc-core/issues)
of per e-mail aan <api@logius.nl>

Wij ontvangen graag inhoudelijke opmerkingen, vragen of suggesties uiterlijk ...

# Publieke Consultatie : NL GOV AuthZEN Authorization API v1.0

Logius houdt een publieke consultatie voor NLGov Profile for OpenID AuthZEN Authorization API. Het profiel is ontwikkeld vanuit het vernieuwingsproject FTV (Federatieve Toegangsverlening) voor de Generieke Digitale Infrastructuur (GDI) en sluit aan bij bredere programma’s zoals het Federatief Datastelsel (FDS) en de Interbestuurlijke Datastrategie (IBDS). De Consultatie loopt van 16-10 t/m 20-11-2025. Feedback en suggesties zijn welkom via api@logius.nl of via issues op GitHub. Help mee dit profiel klaar te maken voor de definitieve v1.0.0 .

Zie voor de documentatie van de standaard: [Consultatieversie](https://logius-standaarden.github.io/Openbare-Consultaties/2025-10-15-Authzen/)

## Context

De [AuthZEN standaard versie 1.0](https://openid.net/specs/authorization-api-1_0-01.html) van OpenID Foundation heeft op dit moment de status Final Draft. Deze versie bevat een informatiemodel zoals boven beschreven en de drie APIs. Deze versie zal eind 2025 aangeboden worden ter consultatie.

Diverse commerciële toegangsverleningsproducten en API-gateways implementeren deze versie inmiddels. De [AuthZEN interop](https://authzen-interop.net/) laat zien welke partijen dat zijn, en legt uit welk niveau van commitment elke leverancier toezegt.

Meer informatie op de [pagina van VNG Realisatie](https://vng-realisatie.github.io/ftv/methodiek/authzen-nlgov/).

## Standaard

Dit profiel standaardiseert de Autorisatie API en maakt het mogelijk dat in een Externalized Authorization Management (EAM) architectuur de Policy Decision Points (PDP's) en Policy Enforcement Points (PEPs) autorisatie aanvragen en beslissingen kunnen uitwisselen zonder dat zij kennis over de details van elkaars interne werking nodig hebben;

De AuthZEN standaard beschrijft de basis die op elke uitwisseling van toepassing is. Daarbovenop kunnen er voor meer specifieke situatie aanvullende afspraken vastgelegd worden in een zogenaamd profiel.

## Functioneel toepassingsgebied

Het voorgestelde functioneel toepassingsgebied van de standaard is:

> AuthZEN wordt toegepast wanneer de toegangsbeslissing tot een API aanroep in een ander component wordt afgedwongen (PEP) dan waar de beslissing gemaakt wordt (PDP).

Tijdens de consultatie kan hier ook op gereageerd worden.

## Wijzigingen

Deze consultatie betreft de publicatie van een nieuw profiel.

## Reageren?

Reageren kan door middel van een issue op wijzigingsvoorstel op de [repository](https://github.com/Logius-standaarden/authzen-nlgov)
of per e-mail aan <api@logius.nl>

Wij ontvangen graag inhoudelijke opmerkingen, vragen of suggesties **uiterlijk 20 november 2025**.

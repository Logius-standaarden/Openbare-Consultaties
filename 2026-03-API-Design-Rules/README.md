# Consultatie API Design Rules versie 2.2

In het kader van het beheer en de doorontwikkeling van [API Design Rules](https://gitdocumentatie.logius.nl/publicatie/api/adr) houdt Logius een openbare consultatie.
Via deze consultatie nodigen wij u uit om feedback te geven op de standaard. De consultatie loopt tot 24 april 2026.

Bij het Technisch Overleg (TO) API ([notulen](https://github.com/Logius-standaarden/Overleg/tree/main/API)) wordt gewerkt aan de nieuwe versie van API Design Rules, waarbij er drie nieuwe hoofdstukken zijn toegevoegd en enkele normatieve regels zijn gewijzigd.

Met deze openbare consultatie bieden wij belanghebbenden de gelegenheid om kennis te nemen van deze nieuwe versie en te reageren op de bijbehorende wijzigingen.

## Reageren?

Feedback en suggesties zijn welkom via [api@logius.nl](mailto:api@logius.nl) of via [issues](https://github.com/Logius-standaarden/API-Design-Rules/issues) op GitHub.  
Help mee versie 2.2 klaar te maken ter vaststelling.

## Wijzigingen

De volgende wijzigingen zijn onderdeel van de voorgestelde volgende release.

[Consultatieversie 2026-03](./API-Design-Rules) ([Diff met 2.1.0](https://services.w3.org/htmldiff?doc1=https%3A%2F%2Fgitdocumentatie.logius.nl%2Fpublicatie%2Fapi%2Fadr%2F2.1.0&doc2=https%3A%2F%2Flogius-standaarden.github.io%2FOpenbare-Consultaties%2F2026-03-API-Design-Rules%2FAPI-Design-Rules%2F))

Wijzigingen:
 * **Nieuw hoofdstuk** Date & Time
 * **Nieuw hoofdstuk** Error Handling
 * Integratie Naming conventions module (als geheel in core)
 * Signing en Encryption modules als normatief (wanneer relevant)
 * RELEASING.md met informatie over versiewijzigingen
 * Verduidelijking gebruik Nederlandse taal in `/core/interface-language`
 * Voeg uitzondering op trailing slash toe voor root resource in `/core/no-trailing-slash`
 * Maak semantiek van HTTP expliciet in `/core/http-methods`
 * Verduidelijk gebruik van CORS header in combinatie met `openapi.json` in `/core/transport/cors`
 * Verduidelijk hoe om te gaan met gevoelige informatie in URLs in `/core/transport/no-sensitive-uris`

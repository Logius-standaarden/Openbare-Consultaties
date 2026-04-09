# Consultatie **Authorization Decision Log**

In het kader van het beheer en de doorontwikkeling van [Authorization Decision Log](https://gitdocumentatie.logius.nl/publicatie/ftv/adl/0.0.1/) houdt Logius een openbare consultatie.
Via deze consultatie nodigen wij u uit om feedback te geven op de standaard. De consultatie loopt tot **4 mei 2026**.

Het Authorization Decision Log (Logboek Toegangsbeslissingen) is een standaard voor het vastleggen van genomen toegangsbeslissingen. Het logboek is bedoeld voor verantwoording binnen en tussen (semi-)overheidsorganisaties.

Met deze openbare consultatie bieden wij belanghebbenden de gelegenheid om kennis te nemen van deze nieuwe versie en te reageren op de bijbehorende wijzigingen.

## Reageren?

Feedback en suggesties zijn welkom via [api@logius.nl](mailto:api@logius.nl) of via [issues](https://github.com/Logius-standaarden/authorization-decision-log/issues) op GitHub.  
Help mee versie 1.0 klaar te maken ter vaststelling.

## Wijzigingen

Dit is de eerste versie van het document - alle feedback is welkom.

[Consultatieversie **13 april 2026**](./authorization-decision-log) <!-- Het document wordt gepubliceerd vanaf een `consultatie/` branch, zie CONTRIBUTING.md -->

### Toelichting
Dit is een standaard die onderdeel is van een bundeling van drie standaarden onder de FTV noemer, die bedoeld zijn om het beheren en uitvoeren van autorisaties te ondersteunen.
Bij de Werkgroep FTV ([notulen](https://vng-realisatie.github.io/ftv/meedoen/werkgroep/contracten/)), is inhoudelijk gewerkt aan deze versie van Authorization Decision Log. 

De Authorization Decision Log beschrijft hoe een opdracht tot het opslaan van een toegangsbeslissing eruit moet zien.
Het logboek gebruikt daarom het AuthZEN-gegevensmodel als basis voor de gegevens die moeten worden vastgelegd in de log.

Het stelt dat zowel het autorisatieverzoek als het bijbehorende antwoord wordt vastgelegd. 

Aanvullend kan worden verwezen naar de gehanteerde autorisatieregels, gebruikte informatiebronnen, configuratie-informatie als ook eventuele correlatie-identificaties. Het Authorization Decision Log biedt een drietal manieren om te verwijzen naar deze gegevens conform het "data bij de bron"-principe. 

De standaard beschrijft alleen het informatiemodel van de vast te leggen gegevens en niet op welke wijze deze worden vastgelegd. Er wordt wel geadviseerd om daarbij gebruik te maken van het OpenTelemetry Protocol. De standaard beschrijft verder dat loginformatie op verschillende detailniveaus kan worden vastgelegd. Het laat het aan organisaties zelf om te bepalen welk detailniveau wordt gekozen.

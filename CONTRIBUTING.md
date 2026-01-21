# Hoe start ik een consultatie?

Maak eerst een nieuwe folder aan in deze repository, met het formaat `<START-JAAR>-<START-MAAND>-<TITEL-IN-LOWERCASE>`.
Zet hierin een README.md bestand en gebruik hiervoor het volgende template voor de tekst van de consultatie:

```md
# Consultatie **<TITEL-VAN-CONSULTATIE>**

In het kader van het beheer en de doorontwikkeling van [**<STANDAARD-NAAM>**](https://gitdocumentatie.logius.nl/publicatie/**<PUBLICATIE-URL>**) houdt Logius een openbare consultatie.
Via deze consultatie nodigen wij u uit om feedback te geven op de standaard. De consultatie loopt tot **<EIND-DAG> <EIND-MAAND> <EIND-JAAR>**.

Bij het Technisch Overleg (TO) **<NAAM-VAN-TO>** ([notulen](https://github.com/Logius-standaarden/Overleg/tree/main/**<NAAM-VAN-TO>**)) wordt gewerkt aan de nieuwe versie van **<STANDAARD-NAAM>**, waarbij **<KORTE-SAMENVATTING>**.

Met deze openbare consultatie bieden wij belanghebbenden de gelegenheid om kennis te nemen van deze nieuwe versie en te reageren op de bijbehorende wijzigingen.

## Reageren?

Feedback en suggesties zijn welkom via [**<EMAIL:api|digikoppeling>**@logius.nl](mailto:**<EMAIL:api|digikoppeling>**@logius.nl) of via [issues](https://github.com/Logius-standaarden/**<REPOSITORY-NAAM>**/issues) op GitHub.  
Help mee versie **<VERSIE-NUMMER>** klaar te maken ter vaststelling.

## Wijzigingen

De volgende wijzigingen zijn onderdeel van de voorgestelde volgende release.

<!-- De volgende sectie moeten worden gerepeteerd voor elk document -->

### **<DOCUMENT-NAAM>**

[Consultatieversie **<START-DAG> <START-MAAND> <START-JAAR>**](./**<REPOSITORY-NAAM>**) <!-- Het document wordt gepubliceerd vanaf een `consultatie/` branch, zie CONTRIBUTING.md -->

Wijzigingen:
 * **<TEKSTUELE BESCHRIJVING VAN EEN WIJZIGING>**
 * **<TEKSTUELE BESCHRIJVING VAN EEN WIJZIGING>**
 * **<TEKSTUELE BESCHRIJVING VAN EEN WIJZIGING>**
```

Voeg daarnaast een link toe in de README.md van deze repository zelf in de tabel "Lopende Consultaties".

## Toevoegen van consultatieversie documenten

Om consultatieversies van documenten te maken, doorloop de volgende stappen:

1. Ga naar de repository van het document
2. Ga naar `develop`
3. Maak een nieuwe branch aan met het formaat `consultatie/<START-JAAR>-<START-MAAND>-<TITEL-IN-LOWERCASE>`.
Let hierbij op dat de naam van de branch dus letterlijk overeen moet komen met de foldernaam.
Voorbeeld: de folder heet `2026-01-api-design-rules`, dan heet de branch `consultatie/2026-01-api-design-rules`
4. Maak een PR **in draft** voor deze branch
5. Inspecteer de preview en check dat deze klopt
6. Markeer de PR als "Ready for review"
7. Run de action "Build and check" op de consultatiebranch.
Ga hiervoor naar `https://github.com/Logius-standaarden/<REPOSITORY-NAAM>/actions/workflows/build.yml` en klik op "Run workflow" waarbij de correcte branch geselecteerd is.
8. Het document wordt nu gebouwd en zal snel daarna in deze repository terecht komen

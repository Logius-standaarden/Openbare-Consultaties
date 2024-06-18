

# Consultatie Federatieve Service Connectiviteit (FSC) opnemen in het Digikoppeling REST API profiel

## Inleiding

In het kader van het vernieuwingsvoorstel 'Digikoppeling voor API's' van VNG Realisatie en RINIS is de [Federated Service Connectivity (FSC) Standaard](https://nlx.io/) (door)ontwikkeld. Voor het Digikoppeling REST API profiel is een wijzigingsvoorstel ingebracht om de FSC standaard aan dit profiel toe te voegen.

## Consultatie

Graag vragen wij uw reactie op het wijzigingsvoorstel om de standaard Federated Service Connectivity (FSC) toe te voegen als aanbevolen binnen het Digikoppeling REST-API profiel.

* Preview van de aangepaste versie van het profiel Digikoppeling REST-API profiel: [Preview](https://logius-standaarden.github.io/Publicatie-Preview/Digikoppeling-Koppelvlakstandaard-REST-API/fsc/)

* Overzicht Aanpassingen: [Wijzigingen](https://github.com/Logius-standaarden/Digikoppeling-Koppelvlakstandaard-REST-API/pull/29/files)

* Wijzigingsvoorstel / Toelichting: [Federatieve Service Connectiviteit opnemen in het Digikoppeling voor REST API's profiel](https://github.com/Logius-standaarden/Digikoppeling-Koppelvlakstandaard-REST-API/issues/26)

Resultaat van behandeling van het wijzigingsvoorstel in het Technisch Overleg 29/5:
* [Verslag Technisch Overleg 29/5](https://github.com/Logius-standaarden/Overleg/blob/main/Digikoppeling/2024-09-19/2024-05-29%20%20Verslag%20TO%20Digikoppeling%20v1.0..pdf)
* [Resultaat Stemming/Standpunten](https://github.com/Logius-standaarden/Overleg/blob/main/Digikoppeling/2024-09-19/FSC-poll-29-5-2024.md)
  
Graag ontvangen wij uiterlijk 3/8/2024 uw reactie via: [Issues](https://github.com/Logius-standaarden/Digikoppeling-Koppelvlakstandaard-REST-API/issues) of digikoppeling(at)logius.nl


### Digikoppeling REST-API profiel.
Het Digikoppeling Rest API profiel is gericht op Machine-to-Machine (M2M) en Government-to-Government (G2G) interacties conform de algemene uitgangspunten van de Digikoppeling standaard en het toepassingsgebied van Digikoppeling op de Pas-toe-of-leg-uit lijst (PTLU) van het Forum Standaardisatie;

### Functioneel toepassingsgebied Digikoppeling Forum Standaardisatie
Digikoppeling moet worden toegepast bij digitale gegevensuitwisseling die plaatsvindt met voorzieningen die onderdeel zijn van de GDI, waaronder de basisregistraties, of die sectoroverstijgend is. De verplichting geldt voor gegevensuitwisseling tussen systemen waarbij er noodzaak is voor tweezijdige authenticatie.

Geautomatiseerde gegevensuitwisseling tussen informatiesystemen op basis van NEN3610 is uitgesloten van het functioneel toepassingsgebied.

Zie [Digikoppeling - Forum Standaardisatie](https://www.forumstandaardisatie.nl/open-standaarden/digikoppeling)

### Federated Service Connectivity (FSC)
De FSC standaard beschrijft hoe op een uniforme wijze koppelingen te maken en te beheren zijn. 

#### Wat standaardiseert FSC
* Hoe de identiteit van een organisatie wordt bepaald en vertrouwd.
* Hoe een autorisatie om te mogen koppelen met een API gegeven, geweigerd of ontnomen wordt.
* Hoe organisaties in een netwerk de API's, en elkaar kunnen vinden.
* Hoe een verbinding naar een API veilig kan worden opgezet.
* De inhoud van logregels en wanneer deze moeten worden weggeschreven.
* Hoe een intermediair namens een andere organisatie een API kan consumeren en/of publiceren.

#### Wat voegt FSC toe aan Digikoppeling
* Een directory waarin API's gepubliceerd en gevonden kunnen worden.
* Toegang tot een API beheren middels digitale contracten.
* Uniforme logging rondom verzoeken aan een API.
* Delegatie. I.e. hoe een organisatie namens een andere organisatie mag handelen.

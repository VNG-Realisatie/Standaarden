---
layout: landing-page
title: API Standaarden
---

# API Standaarden

Het wordt steeds belangrijker voor (applicatie)componenten om onderling goed samen te werken. Om dit mogelijk te maken kennen componenten (applicatie)services die voor andere componenten toegankelijk zijn via zogenaamde 'Application Programming Interfaces' (API's). Zo kunnen componenten op een gestructureerde manier functionaliteit van andere componenten gebruiken. Bijvoorbeeld door een API aan te bieden die voor andere componenten bruikbaar is om gegevens uit een achterliggende bronregistratie te gebruiken.

Om doelmatig en efficiënt met API's te werken is het belangrijk om de manier waarop API's worden ontwikkeld, gedocumenteerd, getest en werken te standaardiseren. Er zijn een aantal manieren om dit te realiseren. Een daarvan is het kiezen voor een bepaalde architectuurstijl. Net als in de rest van de wereld geldt ook voor de Nederlandse overheid dat de voorkeur momenteel uitgaat naar API's die werken volgens de [REST-architectuurstijl](https://en.wikipedia.org/wiki/Representational_state_transfer) . Maar dan nog geldt dat er aanvullende ontwerpkeuzes moeten worden gemaakt. Daarom is afgesproken om overheidsbrede afspraken te maken over hoe de REST-stijl wordt toegepast bij het ontwerpen van API's. Deze afspraken zijn vastgelegd in de [REST-API Design Rules](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules) standaard.

Op de website [ developer.overheid.nl](https://developer.overheid.nl) is te zien dat er steeds meer overheids-API's beschikbaar komen die allerlei soorten functionaliteit aanbieden. Op [data.overheid.nl](https://data.overheid.nl/) worden (ook) API-specificaties gepubliceerd waarmee open data is op te vragen. Voor gemeenten zijn met name API's interessant waarmee elders vastgelegde brongegevens toegankelijk worden gemaakt. Gebruik daarvan kan bijvoorbeeld leiden tot hogere actualiteit en betrouwbaarheid van data en het onderhouden van lokale kopieën overbodig maken. 

De [GEMMA Architectuurvisie](https://www.gemmaonline.nl/index.php/Architectuurvisie) beschrijft hoe standaardisatie via het gebruik van API's cruciaal is om toe te kunnen werken naar een fundamenteel betere informatievoorziening voor gemeenten. Iets dat verder wordt uitgewerkt binnen de [thema-architectuur Common Ground](https://www.gemmaonline.nl/index.php/Thema-architectuur_Common_Ground) die de architectuur uitwerkt die nodig is om de doelen van Common Ground te realiseren. 

Vanuit de VNG wordt op verschillende manieren gewerkt aan de ontwikkeling van gestandaardiseerde API's: 

* Via het programma HaalCentraal is gewerkt aan het ontwikkelen van de [HaalCentraal API's](https://vng-realisatie.github.io/Haal-Centraal/) zodat gemeenten beter data kunnen opvragen uit de basisregistraties. 
* Het project Notificatieservices heeft een concept-standaard ontwikkeld voor het notificeren van plaatsgevonden gebeurtenissen, zoals het wijzigen van brongegevens, aan daarop geabonneerde afnemers. Deze [NL GOV for CloudEvents standaard](https://logius.nl/domeinen/gegevensuitwisseling/nl-gov-profile-cloudevents) is nu in beheer bij Logius. 
* Voor ondersteuning van zaakgericht werken binnen gemeenten zijn [API-standaarden voor zaakgericht werken](https://vng.nl/projecten/zaakgericht-werken-api) ontwikkeld.

## Overzicht vastgestelde API standaarden
Het overzicht hieronder toont de door het College van Dienstverleningszaken door het VNG-bestuur of de Algemene Ledenvergadering van de VNG vastgestelde API-standaarden.

| Standaard | Beheerder | Status | Datum | Onderdeel van |
| --- | --- | --- | --- | --- |
| [Zaken API](https://vng-realisatie.github.io/gemma-zaken/) | VNG Realisatie | Pas-toe-of-leg-uit | 27-11-2019 | Domein Dienstverlening (Zaakgericht werken)     |
| [Documenten API](https://catalogi-api.vng.cloud)               | VNG Realisatie        | Pas-toe-of-leg-uit   | 27-11-2019 | Domein Dienstverlening (Zaakgericht werken) |
| [Besluiten API](https://besluiten-api.vng.cloud)               | VNG Realisatie        | Pas-toe-of-leg-uit   | 27-11-2019 | Domein Dienstverlening (Zaakgericht werken) |
| [Autorisaties API](https://catalogi-api.vng.cloud)             | VNG Realisatie        | Pas-toe-of-leg-uit   | 27-11-2019 | Domein Dienstverlening (Zaakgericht werken) |
| [Notificaties API](https://notificaties-api.vng.cloud)          | VNG Realisatie        | Pas-toe-of-leg-uit   | 27-11-2019 | Domein Dienstverlening (Zaakgericht werken) |
| [Objecten API](https://github.com/maykinmedia/objects-api/)                | OpenZaak Community       | Pas-toe-of-leg-uit   | 13-01-2021 | Domein Dienstverlening (Zaakgericht werken) |
| [Objecttypen API](https://github.com/maykinmedia/objecttypes-api)            | OpenZaak Community       | Pas-toe-of-leg-uit   | 13-01-2021 | Domein Dienstverlening (Zaakgericht werken) |
| [BAG Bevragen API](https://github.com/VNG-Realisatie/Haal-Centraal-BAG-bevragen/)          | Kadaster        | Pas-toe-of-leg-uit   | 13-08-2020 | Haal Centraal |
| [BRK Bevragen API  ](https://github.com/VNG-Realisatie/Haal-Centraal-BRK-bevragen/)      | Kadaster        | Pas-toe-of-leg-uit   | 03-06-2020 | Haal Centraal |
| [BRP Bevragen API](https://github.com/BRP-API/Haal-Centraal-BRP-bevragen/) |	RvIG        | Pas-toe-of-leg-uit   | 01-10-2020 | Haal Centraal |
| [WOZ Bevragen API](https://github.com/VNG-Realisatie/Haal-Centraal-WOZ-bevragen/) |	Waarderingskamer        | Pas-toe-of-leg-uit   | 16-12-2021 | Haal Centraal |
| [Regels bij activiteiten API](https://github.com/VNG-Realisatie/Regels-bij-activiteiten) | VNG Realisatie        | Pas-toe-of-leg-uit   | 01-07-2021 | Fysiek domein |

## Vaststelling statussen van standaarden (VNG)
Een verbindend verklaarde API-standaard is na een advies van het College van Dienstverleningszaken door het VNG-bestuur of de Algemene Ledenvergadering van de VNG als standaard vastgesteld. Een vaststelling kan verschillende gradaties van verbindendheid tot gevolg hebben: van 'aanbevolen deze standaard te gebruiken' tot 'verplicht deze standaard toe te passen'. In de tabel wordt per vastgestelde API-standaard aangegeven welke mate van verbindendheid geldt. Het [proces van standaardverklaring](https://vng.nl/brieven/proces-standaardverklaring) is vastgesteld door het College van Dienstverleningszaken op 12 oktober 2018. 

Standaarden kunnen volgens [drie niveaus van verbindendheid](https://vng.nl/sites/default/files/brieven/2018/attachments/08_notitie_proces_standaardverklaring_versie_cie_i_en_bestuur.pdf) worden vastgesteld:
1. Advies ('Aanbevolen')
    - Mate van verbindendheid: vrijblijvend en geen formele status.
    - Proces vaststelling: vaststellen door directie VNG
    - Voorbeeld: [klantreizen](https://vng.nl/artikelen/klantreizen), [modelverordeningen](https://vng.nl/rubrieken/onderwerpen/modelverordeningen)
2. Standaardverklaring ('Pas toe of leg uit')
    - Mate van verbindendheid: niet vrijblijvend, ‘pas toe of leg uit’-principe [ naar voorbeeld Forum Standaardisatie](https://www.forumstandaardisatie.nl/node/229).
    - Proces vaststelling: tenminste op advies van het College van Dienstverleningszaken door bestuur VNG, ledenraadpleging facultatief, monitoring toepassing door VNG (bijvoorbeeld via Waarstaatjegemeente.nl) en lokaal via reguliere P&C cyclus door gemeenteraad.
    - Voorbeeld: [GIBIT](https://vng.nl/projecten/gibit)
3. Verbindend verklaren ('Verplicht')
    - Mate van verbindendheid: verplichtend voor leden
    - Proces: vaststelling op advies College van Dienstverleningszaken door bestuur VNG metledenraadpleging
    - Voorbeeld: [Aansluiting bij Informatiebeveiligingsdienst](https://vng.nl/projecten/informatieveiligheid) via BALV

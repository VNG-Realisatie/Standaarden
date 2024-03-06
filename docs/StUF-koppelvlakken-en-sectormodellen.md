---
layout: landing-page
title: StUF Sectormodellen en koppelvlakken
---
# StUF Sectormodellen en koppelvlakken

StUF Sectormodellen en koppelvlakken zijn berichtenstandaarden die de structuren beschrijven waarin gegevens uitgewisseld worden tussen informatiesystemen. 
Deze gemeentelijke berichtenstandaarden zijn gebaseerd op het Standaard Uitwisseling Formaat, kortweg StUF. De [StUF-standaard](https://vng-realisatie.github.io/StUF-onderlaag/) 
zegt niets over de inhoud van een specifiek bericht. Daartoe zijn door VNG Realisatie, op basis van de informatiemodellen RSGB, RGBZ en imZTC, zgn. StUF 
sectormodellen (een berichtenstandaard) ontwikkeld op basis waarvan wel specifiek toepasbare berichten gevormd kunnen worden. Dit zijn de generieke standaarden, 
ook wel [horizontale sectormodellen](./StUF-horizontale-sectormodellen) genoemd, StUF-BG, StUF-ZKN en StUF-ZTC. Ook door externe partijen zoals bijv. de Waarderingskamer, de Kamers van Koophandel, 
GeoNovum en ICTU zijn StUF sectormodellen ontwikkeld, de zogenaamde [verticale sectormodellen](./StUF-verticale-sectormodellen) (StUF-WOZ, StUF-KvK, StUF-Geo IMGeo en StUF-RIHa), welke 
door henzelf beheerd worden. Ook deze zijn allen gebaseerd op een informatiemodel.

Bij gebruik van StUF dient nog veel omtrent inhoud en proces voor het gebruik van de berichten door de opdrachtgever ingevuld te worden. Met gebruik van een 
StUF sectormodel is de inspanning voor de opdrachtgever al een stuk minder maar ook hier is het uiterst belangrijk de berichten en processen te controleren. 
Gebruik van StUF koppelvlakken geeft de meeste zekerheid.

Een StUF koppelvlakspecificatie of koppelvlakstandaard specificeert hoe de gegevensuitwisseling tussen applicaties en voorzieningen eruit moet zien. Het legt 
concrete afspraken vast waarmee specifieke gegevens kunnen worden gecommuniceerd. Afspraken over specifieke berichten die tussen bepaalde referentiecomponenten 
uitgewisseld moeten en/of kunnen worden, afspraken over aanscherping van de berichten uit een StUF sectormodel en afspraken over de wijze waarop die berichten 
verstuurd moeten worden.

StUF Koppelvakspecificaties zijn vaak gebaseerd op de eerder genoemde [horizontale-]() of [verticale sectormodellen]() en beschrijven hoe deze generieke standaarden 
bij specifieke koppelingen gebruikt moeten worden.

In een StUF koppelvlakspecificatie is altijd aangegeven op welke referentiecomponenten de specificatie van toepassing is. In de GEMMA Softwarecatalogus geven 
leveranciers aan welke referentiecomponenten hun softwareproducten ondersteunen. Hierdoor kan worden nagegaan welke standaarden relevant zijn voor een 
softwareproduct.

## Doorontwikkeling
Verschillende ontwikkelingen maken het vernieuwen van standaarden noodzakelijk om invulling te (blijven) geven aan de behoefte en wensen van gemeenten. De 
doorontwikkeling van de StUF standaard, de StUF sectormodellen en de StUF koppelvlakken is daarom stopgezet. Alleen wetswijzigingen, wijzigingen in de Logische 
Ontwerpen van Basisregistraties en gevonden fouten kunnen aanleiding zijn voor het publiceren van een nieuwe versie van deze standaarden. Zo wordt er voor 
gezorgd dat gemeenten hun werk kunnen blijven doen. Een toelichting op het vernieuwen van de standaarden is te vinden bij [API-standaarden](https://vng-realisatie.github.io/Standaarden/API-standaarden).

## Basis- en kerngegevens
Het aandachtsgebied 'Basis- en kerngegevens' betreft het beheer en gebruik van basis- en kerngegevens uit bijvoorbeeld BAG, GBA (BRP), nHR en BRP van objecten 
zoals Personen, Gebouwen, Adressen, Maatschappelijke activiteiten, Vestigingen, etc... De StUF sectormodellen en koppelvlakken in dit aandachtsgebied bieden 
componenten en berichten waarmee gegevens over dit soort objecten kunnen worden uitgewisseld tussen applicaties. In de tabel hieronder vind je de standaarden 
die daarbij een rol spelen.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [Sectormodel Basisgegevens: StUF-BG](https://vng-realisatie.github.io/StUF-BG/) (RSGB) |  VNG Realisatie | 3.10 | 3.01, 2.04 |
| [StUF BAG](https://vng-realisatie.github.io/StUF-BAG/) (BAG) |  VNG Realisatie | 3.10 | 3.01 |
| [LV Adressen en Gebouwen (LV BAG)](https://www.kadaster.nl/-/bag-koppelvlak) (BAG) | Kadaster | 2.0 | 3.01 |
| [Kadastrale mutatieservices](https://vng-realisatie.github.io/Kadastrale-mutatieservices/) (BRK-Levering) |  VNG Realisatie | 1.0 | 3.01 |
| [Sectormodel Geo: StUF Geo IMGeo](https://www.geonovum.nl/geo-standaarden/bgt-imgeo#standaarden) (BGT)| Geonovum | 1.3 | 3.01 |
| [Sectormodel HR: StUF-HR](https://www.kvk.nl/producten-bestellen/kvk-dataservice-aansluiten-overheid/) (nHR) | Kamers van Koophandel | ? | 3.01 |

## Zaken en documenten
Het aandachtsgebied 'Zaken en documenten' heeft betrekking op zaken die bij een gemeente in behandeling zijn en alle daaraan gerelateerde documenten. Denk daarbij 
aan de aanvraag voor een parkeervergunning of een vergunning voor een evenement. Het sectormodel StUF-ZKN biedt daarbij voorzieningen voor het opvragen of het 
muteren van gegevens m.b.t. de betreffende zaken. Het sectormodel StUF-ZTC voorziet in mogelijkheden om configuratiegegevens m.b.t. zaakgerelateerde systemen uit 
te wisselen.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [Sectormodel Zaken: StUF-ZKN](https://vng-realisatie.github.io/StUF-ZKN/) (RGBZ) |  VNG Realisatie | 3.10 | 3.01 |
| [Sectormodel Zaaktypen(-catalogus): StUF–ZTC](https://vng-realisatie.github.io/StUF-ZTC/) (ImZTC) |  VNG Realisatie | 3.10 | 3.01 |
| [Zaak- en Documentservices](https://vng-realisatie.github.io/Zaak-en-Documentservices/) |  VNG Realisatie | 1.2 | 3.01 |
| [Documentcreatieservices](https://vng-realisatie.github.io/Documentcreatieservices/) |  VNG Realisatie | 1.1 | 3.01 |

## Dienstverleningsdomein
Onder het Dienstverleningsdomein vallen de interacties die de digitale dienstverlening ondersteunen zoals activiteiten aangaande Burgerzaken, Belastingheffing en 
Front-offce.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [Prefill eFormulierservices](https://vng-realisatie.github.io/Prefill-eFormulierenservices/) |  VNG Realisatie | 1.0 | 3.01 |
| RSGB Bevragingen | &nbsp; | &nbsp; | &nbsp; |
| [Sectormodel e-Formulieren: StUF-EF](https://vng-realisatie.github.io/StUF-EF/) |  VNG Realisatie | 3.15 | 3.01 |
| [Sectormodel WOZ: StUF-WOZ](https://www.waarderingskamer.nl/basisregistratie-woz-lv-woz/stuf-woz-0312/) | Waarderingskamer | 3.12 | 3.01 |
| [StUF BAG-GBA](https://vng-realisatie.github.io/StUF-BAG-GBA/) |  VNG Realisatie | 3.10 | 3.01, 2.04 |

## Ruimtelijk domein
Onder het Ruimtelijk domein vallen bijvoorbeeld de interacties die de activiteiten met betrekking tot het verlenen van vergunningen en het houden van toezicht op 
deze vergunningen of andere regelgeving ondersteunen.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [Wabo-BAG services](https://vng-realisatie.github.io/Wabo-BAG-Services/) |  VNG Realisatie | 1.0 | 3.01 |
| [Toezicht- en Handhavenservices](https://vng-realisatie.github.io/Toezicht-en-Handhavenservices/) |  VNG Realisatie | 2.0 | 3.01 |
| [StUF-Geo BAG](https://www.geonovum.nl/onderwerpen/bgt-imgeo-standaarden/nieuws/bag-bgt-koppelvlak-nu-definitief) | Geonovum | ? | 3.01 |
| [LV Omgevingsloket](https://www.infomil.nl/onderwerpen/integrale/omgevingsloket/overheden/aansluiten-webservices-omgevingsloket/achtergrondinformatie-stuf-lvo/) | Ministerie van IenM | 3.05 | 3.01 |
| [Sectormodel RIHa: StUF-RIHa](https://samenwerken.pleio.nl/groups/view/8b832827-e91b-476c-bb4f-c228b8e5e934/standaardisatie-toezicht-handhaving-milieu/wiki/view/2b38214e-cfc7-42ff-9d5d-eaf069671c42/riha-referentieinformatiemodel-handhaving) | ILT | 2.0  | 3.01 |

## Sociaal domein
Onder het Sociaal domein vallen de interacties die activiteiten ondersteunen met betrekking tot het verlenen van zorg, de maatschappelijke ondersteuning en de 
participatie.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [StUF Jeugdzorg (CORV)](https://vng-realisatie.github.io/StUF-Jeugdzorg/) |  VNG Realisatie | 1.0 | 3.01 |
| [Regie- en zaakservices](https://vng-realisatie.github.io/Regie-en-zaakservices/) |  VNG Realisatie | 1.0 | 3.01 |
| [StUF-GGk berichtenvelop ISD-Keten](https://vng-realisatie.github.io/StUF-koppelvlak-iWmo-iJw/) |  VNG Realisatie | 2.1 | 3.01 |
| Participatieladder | &nbsp; | &nbsp; | &nbsp; |
| Kinderopvang | &nbsp; | &nbsp; | &nbsp; |

## Bedrijfsvoeringsdomein
Onder het Bedrijfsvoeringsdomein vallen bijvoorbeeld de interacties die de geldstromen van een gemeente ondersteunen.

| Standaard | Beheerder | Laatste versie | StUF versie |
| --- | --- | --- | --- |
| [Koppelvlak Betalen- en Invorderenservices](https://vng-realisatie.github.io/Betalen-en-Invorderenservices/) |  VNG Realisatie | 1.0 | 3.01 |

## Compliancy
Het is de verantwoordelijkheid van de opdrachtgever om zelf te controleren of de berichten voldoen aan de specificaties. Voor een aantal standaarden kan een 
leverancier compliancy behalen op het StUF Test Platform. De opdrachtgever kan dan exact zien in welke mate een StUF koppelvlak ondersteund wordt. Aangeraden 
wordt dan ook het voldoen aan de [compliancy](./StUF-test-en-compliancy) eisen op het [StUF Test Platform](https://iam.opentunnel.org:8444/auth/realms/STP_PROD/protocol/openid-connect/auth?client_id=APP_STP_PUBLIC&redirect_uri=https%3A%2F%2Fstuftestplatform.nl%3A8443%2Fstv%2Fadmin%2Fui%2F&state=2ee1c0d5-61ef-4bdb-87af-23f52a0db22a&response_mode=fragment&response_type=code&scope=openid&nonce=551effcb-2b99-4168-b20b-18c8e539b4c1%7C) en dit aan kunnen tonen met een geslaagd testrapport als eis op te nemen. Door 
gebruik van de GIBIT, de gemeentelijke uniforme inkoopvoorwaarden voor IT borgt u dit duurzaam voor vastgestelde (open) standaarden.

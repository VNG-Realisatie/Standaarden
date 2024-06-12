# Mapping StUF standaarden en API standaarden (voor 2024)
Deze pagina toont het beeld dat we ooit hadden m.b.t. de mapping tussen de diverse StUF standaarden en API standaarden.
De mapping is echter niet correct aangezien de API standaarden de StUF standaarden niet 100% overlappen. Soms dekken ze meer af en soms juist minder.

## Basis- en kerngegevens
Het aandachtsgebied 'Basis- en kerngegevens' betreft het beheer en gebruik van basis- en kerngegevens uit bijvoorbeeld BAG, GBA (BRP), nHR en BRP van objecten 
zoals Personen, Gebouwen, Adressen, Maatschappelijke activiteiten, Vestigingen, etc... De StUF sectormodellen en koppelvlakken in dit aandachtsgebied bieden 
componenten en berichten waarmee gegevens over dit soort objecten kunnen worden uitgewisseld tussen applicaties. In de tabel hieronder vind je de standaarden die 
daarbij een rol spelen.

| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| Sectormodel Basisgegevens: StUF-BG (RSGB) (actuele versie: 3.10) | Haal Centraal BRP Personen bevragen API<br/>Haal Centraal BRP Bewoning API<br/>Haal Centraal BRP Reisdocumenten bevragen API<br/>Haal Centraal BRP Update API<br/>Haal Centraal BRP tabellen bevragen API |
| StUF BAG (BAG) (actuele versie: 3.10) | BAG Individuele Bevragingen 2.6 |
| LV Adressen en Gebouwen: Sectormodel LV BAG (in beheer bij Kadaster ) |  BAG Individuele Bevragingen 2.6 |
| Kadastrale mutatieservices (BRK-Levering) (actuele versie: 1.0) | Haal Centraal BRK bevragen 1.5 |
| Sectormodel Geo: StUF Geo IMGeo (BGT) (in beheer bij Geonovum) |  |
| Sectormodel HR: StUF-HR (nHR) (in beheer bij Kamers van Koophandel) |  |
| LV Wet Kenbaarheid Publiekrechtelijke Beperkingen (Sectormodel StUF Wkpb) (in beheer bij Kadaster ) | |

## Zaken en documenten
Het aandachtsgebied 'Zaken en documenten' heeft betrekking op zaken die bij een gemeente in behandeling zijn en alle daaraan gerelateerde documenten. Denk daarbij 
aan de aanvraag voor een parkeervergunning of een vergunning voor een evenement. Het sectormodel StUF-ZKN biedt daarbij voorzieningen voor het opvragen of het muteren 
van gegevens m.b.t. de betreffende zaken. Het sectormodel StUF-ZTC voorziet in mogelijkheden om configuratiegegevens m.b.t. zaakgerelateerde systemen uit te wisselen.

| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| Sectormodellen Zaken: StUF-ZKN (RGBZ) (actuele versie: 3.10) | API-standaarden voor Zaakgericht werken |
| Sectormodel Zaaktypen(-catalogus): StUF–ZTC (ImZTC) (actuele versie: 3.10) | API-standaarden voor Zaakgericht werken |
| Zaak- en Documentservices (actuele versie: 1.2) | API-standaarden voor Zaakgericht werken |
| Documentcreatieservices (actuele versie: 1.1) | API-standaarden voor Zaakgericht werken |

## Dienstverleningsdomein
Onder het Dienstverleningsdomein vallen de interacties die de digitale dienstverlening ondersteunen zoals activiteiten aangaande Burgerzaken, Belastingheffing en Front-offce.
| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| Prefill eFormulierservices (actuele versie: 1.0) |  | 
| Sectormodel e-Formulieren: StUF-EF (actuele versie: 3.15) |  |
| Sectormodel WOZ: StUF-WOZ (in beheer bij Waarderingskamer) | Haal Centraal WOZ bevragen API |
| StUF BAG-GBA (actuele versie: 2.04) |  |

## Ruimtelijk domein
Onder het Ruimtelijk domein vallen bijvoorbeeld de interacties die de activiteiten met betrekking tot het verlenen van vergunningen en het houden van toezicht op deze vergunningen of andere regelgeving ondersteunen.

| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| Wabo-BAG services (actuele versie: 1.0)|  |
| Toezicht- en Handhavenservices (actuele versie: 2.0)|  |
| StUF-Geo BAG (in beheer bij Geonovum)|  |
| LV Omgevingsloket: Sectormodel StUF LVO  (in beheer bij Ministerie van IenM)|  |
| Sectormodel RIHa: StUF-RIHa  (in beheer bij ILT)|  |

## Sociaal domein
Onder het Sociaal domein vallen de interacties die activiteiten ondersteunen met betrekking tot het verlenen van zorg, de maatschappelijke ondersteuning en de participatie.

| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| StUF-koppelvlak Jeugdzorg: StUF Jeugdzorg (actuele versie: 1.0) |  |
| Regie- en zaakservices (actuele versie: 1.0) |  |
| StUF-koppelvlak iWmo-iJw: StUF-GGK (actuele versie: 2.1) |  |

## Bedrijfsvoeringsdomein
Onder het Bedrijfsvoeringsdomein vallen bijvoorbeeld de interacties die de geldstromen van een gemeente ondersteunen.

| StUF sectormodel of koppelvlak | API standaard |
| --- | --- |
| Betalen- en Invorderenservices (actuele versie: 1.0) |  |

---
layout: landing-page
title: Horizontale sectormodellen
---
# Horizontale sectormodellen

Horizontale sectormodellen zijn gebaseerd op een StUF onderlaag en op een informatiemodel waarin de voor de gemeenten meest belangrijke entiteiten 
zijn gemodelleerd. In deze horizontale sectormodellen zijn de betreffende entiteiten uit de informatiemodellen omgezet naar generieke componenten. 
Denk daarbij bijv. aan componenten voor persoonsgegevens, gegevens over adressen en gebouwen, zaken en documenten maar ook zaaktypen en rollen.

Horizontale sectormodellen bestaan uit een aantal XML-Schema bestanden aangevuld met WSDL bestanden welke zijn ondergebracht in folders, deze folders 
noemen we ook wel berichtencatalogi. De berichtencatalogi dienen daarbij om de verschillende XML-Schema's te organiseren op basis van hun functiegebieden. 
Zo heeft elk horizontaal sectormodel de volgende standaard berichtencatalogi.

**entiteiten**: een berichtencatalogus voor het onderbrengen van default componenten;
**mutatie**: een berichtencatalogus waarin componenten staan welke gebruikt worden voor het verzenden van mutatieberichten;
**vraagAntwoord**: een berichtencatalogus waarin componenten staan welke gebruikt worden voor het ophalen van gegevens.

Naast deze berichtencatalogi mogen er nog andere berichtencatalogi in horizontale sectormodellen worden gebruikt. Die berichtencatalogi worden dan vaak 
gebruikt door specifieke koppelvlakken. Zo heeft het horizontale sectormodel StUF-BG 3.10 de berichtencatalogus 'BAG' welke wordt gebruikt in het koppelvlak 
StUF-BAG en het sectormodel StUF-ZKN 3.10 kent de berichtencatalogus 'ZS-DMS' welke wordt gebruikt in het koppelvlak Zaak- en Documentservices'.

Hieronder vind je de horizontale sectormodellen met tussen haakjes de daarbij horende informatiemodellen.

| Horizontaal sectormodel | versies |
| --- | --- |
| StUF-BG | 2.04 (GFO), 3.10 (RSGB) |
| StUF-ZKN | 3.10 (RGBZ) |
| StUF-ZTC | 3.10 (Im-ZTC) |

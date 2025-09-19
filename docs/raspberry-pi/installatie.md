---
layout: default
title: Installatie
parent: raspberry-pi
nav_order: 2
---

# Benodigdheden voor afnemers

Voor het gebruik van data uit de Kadaster DataHub beschikt de dienst over een tweetal services.
De [Lookup Service]({% link docs/lookup-service/index.md %}) is een afnamepunt gericht op compacte bevragingen.
De [Bulk Service]({% link docs/bulk-service/index.md %}) is een afnamepunt gericht op grote hoeveelheden gegevens die in korte tijd opgevraagd dienen te worden.

Het gebruik van deze services en tooling vereist het volgende:
1. API-key per bron. Hiervoor is toestemming nodig van de data-aanbieder
2. De tool GraphQL
3. Kennis van [GraphQL](https://graphql.org/learn/){:target="_blank"}

# Taken en verantwoordelijkheden
Betrokken partijen:
* De data-aanbieder: beheerder van een basisregistratie of landelijke voorziening die gebruik wil maken van de dienst DataHub. Hier wordt ook wel de term 'tenant' voor gehanteerd.
* Team DataHub: partij die de data-aanbieder faciliteert bij de opslag van de data en standaard services beheert voor het leveren van data uit DataHub.
* Team GDC: partij die extra tooling beheer voor het leveren van data uit DataHub
* Afnemer: partij die informatie uit DataHub afneemt

Binnen het proces van het aansluiten van nieuwe afnemers onderkennen we de volgende taken en verantwoordelijkheden:

 Nr | Taak                                                                          | Afnemer | Data aanbieder | DataHub Team
-|-------------------------------------------------------------------------------|-|-|-
1 | Levering services op [A-niveau]({% link docs/service/DNO.md %}) |  |  | X 
2 | Toestemming API key                                                           |  | X |
3 | Borgen kwaliteit en actualiteit van de data                                   |  | X |   

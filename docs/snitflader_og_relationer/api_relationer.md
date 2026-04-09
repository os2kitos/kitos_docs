---
title: API - Relationer
layout: default
nav_order: 4
parent: Snitflader og relationer
---

## API - Relationer

Data om relationer og snitflader er tilgængelige via KITOS API.
API-dokumentation for relationer findes her:  
https://kitos.dk/swagger/ui/index#/API_-_SystemRelation


## 4. Relationer – Arkitektonisk overblik

Begrebet **relationer** anvendes i KITOS til at beskrive, hvordan to lokale IT-systemer er relateret til hinanden.
<br>
<br>

<img width="1961" height="983" alt="image" src="https://github.com/user-attachments/assets/c3a36144-1ef6-4c06-be77-835594b720ca" />

En relation består altid af:
- et lokalt **udstillersystem**
- et lokalt **anvendersystem**

En relation kan udelukkende redigeres fra **anvendersystemets** side.

Det er muligt at oprette flere relationer mellem de samme lokale IT-systemer, hvilket gør det muligt at etablere tovejsbindinger.
<br>


For hver relation kan der:
- tilføjes en beskrivelse
- angives en reference, hvis der er behov for det

Derudover kan det angives, hvilken snitflade de to IT-systemer kommunikerer via.  
For at kunne tilføje en snitflade til en relation kræves det, at det logiske IT-system for det lokale udstillersystem udstiller den pågældende snitflade. Dette konfigureres via snitfladebeskrivelsen.

Endeligt er det muligt:
- at beskrive relationens frekvens
- at angive, hvilken kontrakt relationen eventuelt er omfattet af




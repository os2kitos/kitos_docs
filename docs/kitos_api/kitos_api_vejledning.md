---
title: Kitos Api vejledning
layout: default
nav_order: 1
parent: Kitos Api
---

Her kan du se en vejledning til Kitos API.

Kitos Swagger kan tilgås her: <a href="https://kitos.dk/swagger/ui/index" target="_blank">Kitos API Swagger dokumentation</a>  


# Brug af Kitos’s API  
**Opdateret: 01.10.24**  
**Af: MIOL**

## Grundlæggende information

- **KITOS API V2** læser og skriver begge veje  
- Alle felter i Kitos har et unikt **UUID**  
- API dokumentation: [KITOS API dokumentation](https://os2web.atlassian.net/wiki/spaces/KITOS/pages/657391631/KITOS+API)

## Sådan får kommunen adgang til API

Når en kommune vil anvende Kitos's API, skal I indledningsvis sende en mail til `info@kitos.dk` og oplyse:

- Hvilken bruger (navn og e-mail) der skal have API-adgang  
- Det er **lokal admin** i kommunen, der skal være afsender af mailen – eller som minimum være med på cc, hvis det fx er en tekniker i kommunen eller en ekstern partner, der sender mailen

> Dette sikrer, at kommunens Kitos-person er vidende om, at der gives API-adgang.

## Krav til API-brugeren

- API-brugeren må **ikke være en person**, men skal være en **funktionspostkasse** oprettet specielt til brug for API  
  - Eksempel: `kitos-api@ballerup.dk`  
- Adgangen hænger dermed ikke på enkeltpersoner
- Adgangen har ikke adgang til kitos UI
- Det er vigtigt, at der kan modtages mails på adressen, da dette benyttes til oprettelse/ændring af passwords for API-brugeren

> På den baggrund opretter Sekretariatet API-adgangen.

## Se API-brugere i Kitos

I Organisationsmodulet under **Brugere** kan man se, hvilke brugere der har adgang til API’et.  
Hvis der er **hak** ud for brugeren i kolonnen **API bruger**, er der givet API-adgang.

<img width="1914" height="450" alt="API" src="https://github.com/user-attachments/assets/f33717c9-9781-4765-8c7a-bd51de5cdb7c" />


## API-brugers rettigheder (Skriv/Læs)

- API-brugere er en type bruger, der – som alle andre – **ikke har yderligere rettigheder**, medmindre de tildeles
- Den basale rettighed tillader:
  - At trække et token for at tilgå API endpoints  
  - At **læse** oplysninger i den pågældende organisation  
- Den basale rettighed **giver ikke** beføjelser til at ændre/opdatere indstillinger for et specifikt IT-System

> Har brugeren ikke fået tildelt en administrativ rolle eller en forretningsrolle (f.eks. systemrolle med skriveadgang), vil brugeren kun have **læseadgang** til organisationens data.

## Tildeling af SKRIV-adgang

Kommunens **lokal admin** eller **Kitos sekretariatet** kan tildele disse rettigheder, såfremt API-brugeren skal have **SKRIV adgang**.

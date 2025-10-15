---
title: Generelt
nav_order: 1
parent: Roller og rettigheder
---


# Roller og rettigheder i OS2KITOS  
**Dato:** 09.07.24  
**Kontakt:** OS2KITOS Sekretariatet – [info@kitos.dk](mailto:info@kitos.dk)  
**Web:** [www.kitos.dk](https://www.kitos.dk)

---

## Almindelig bruger (Bruger med læserettigheder)

- Alle brugere oprettes som almindelige brugere.
- Har **læserettighed** til alt inden for den organisation, de er tilknyttet.
- Har **ingen skriverettigheder** som udgangspunkt.
- Kan generere og lave **Excel-udtræk**.
- Kiggeadgang ændres, hvis:
  1. Brugeren tildeles en **Administratorrolle**.
  2. Brugeren tildeles en **Forretningsrolle med SKRIV funktion**.


> Brugeren får først adgang til Kitos, når en advis sendes fra den person, der har oprettet brugeren.  
> I kommuner med SSO, kan brugeren logge direkte ind og få kiggeadgang.

---

## Generelt om roller i Kitos

Der findes to kategorier:

1. **Administratorroller**
2. **Forretningsroller**

---

### 1. Administratorroller

Administratorroller giver **SKRIV adgang** til overordnede moduler:

- Organisation
- Systemer
- Kontrakter
- Databehandling


#### Roller:

- **Lokal administrator**
  - Øverste rettighedsrolle for kommunen.
  - SKRIV adgang til alt i organisationen.
  - Kan oprette og slette brugere og objekter.
  - Kan redigere rettigheder og konfigurere systemopsætning.
  - Anbefaling: 1-3 lokale administratorer pr. kommune.

- **Organisationsadministrator**
  - SKRIV adgang til organisationsmodulet.
  - Kan læse i andre moduler.
  - Kan oprette brugere, redigere stamdata og kontaktinfo og tilknytte roller.
  - OBS! Kun Lokal administrator kan slette brugere og organisationsenheder.

- **Systemadministrator**
  - SKRIV adgang til systemmodulet.
  - Kan redigere/slette data og tilføje systemroller - I system modulet.
  - Kan læse i andre moduler

- **Kontraktadministrator (inkl. databehandling)**
  - SKRIV adgang til kontrakt- og databehandlingsmodulet.
  - Kan redigere/slette data og tilføje relevante roller - I kontrakt og databehandling modulerne.
  - Kan læse i andre moduler

> Administratorroller tildeles via:  
> **Organisation → Brugere → Redigér**
 
<img width="1697" height="385" alt="Roller_rettigheder - 1" src="https://github.com/user-attachments/assets/23412b45-b373-4f8b-bd27-5fb464e99015" />

---

### 2. Forretningsroller

Roller med rettigheder på **specifikke objekter**:

- IT-systemer
- Kontrakter
- Databehandlingsaftaler

#### Funktion:

- **SKRIV rolle** giver adgang til at redigere det specifikke objekt, altså system, kontrakt eller databehandling.
- **LÆS rolle** ændrer ikke kiggeadgang.
- Organisationens forretningsroller giver **ikke skriverettigheder**, medmindre brugeren har yderligere rettigheder.

#### Typer af forretningsroller:

- **Organisationsroller** – tildeles i organisationsmodulet  
- **Systemroller** – tildeles i systemmodulet  
- **Kontraktroller** – tildeles i kontraktmodulet  
- **Databehandlingsroller** – tildeles i databehandlingsmodulet

> Roller tildeles til medarbejdere, der har ansvar for det pågældende objekt ( system/kontrakt/databehandling ).  
> Skriveadgang gælder kun det objekt, rollen er tilknyttet.

Eksempler på systemroller:

- Systemejer  
- Dataejer  
- Superbruger  
- Systemadministrator

> Lokal administrator kan til- og fravælge forretningsroller i lokal admin menuen.

---

## Global administrator (Kun OS2KITOS Sekretariatet)

- Øverste rettighedsrolle i Kitos.
- Kan skrive/redigere alt i alle organisationer.
- Kan oprette/slette objekter og gøre dem synlige på tværs af organisationer.
- Kan oprette nye roller, systemer, organisationer og leverandører.
- Kan konfigurere globale beskrivelser og udfaldsrum.
- Kan oprette brugere med API-adgang.

<!-- BILLEDE HER: Global administrator funktioner -->

> Kun Global administrator kan tildele rollen til andre brugere.

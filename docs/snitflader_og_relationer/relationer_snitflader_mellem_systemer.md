---
title: Relationer og snitflader mellem systemer
layout: default
nav_order: 1
parent: Snitflader og relationer
---


## 1. Relationer og snitflader mellem IT-systemer

### 1.1 Baggrund

Det kan være relevant at skabe overblik over hvilke IT-systemer, der er afhængige af hinanden, f.eks. ved at  
det ene system trækker data fra det andet. Dette kan f.eks. være relevant, hvis man ønsker at arbejde  
strategisk med, hvor ens systemer henter CPR- eller andre grunddata fra. Eller hvis man vil se, hvilke  
konsekvenser det vil have at udfase et specifikt it-system.

I Kitos kan man registrere afhængigheder mellem IT-systemer ved at oprette relationer mellem dem evt. med  
en tilføjelse af hvilken snitflade, relationen virker igennem.

### 1.2 Definition af relationer og snitflader

Objekterne **Relationer** og **Snitflader** er knyttet til objektet it-system og bruges til at beskrive sammenhænge  
mellem IT-systemer:

- **Relation**
  - En relation beskriver en sammenhæng mellem to (og kun to) specifikke IT-systemer – et  
    ”anvendersystem” og et ”udstillersystem”. Anvendersystemet anvender data, en service eller  
    en funktionalitet, som udstillersystemet udstiller.
  - Udstillersystemet vil typisk udstille data, service eller funktionaliteten i en snitflade, hvorved  
    relationen går til snitfladen for udstillersystemet. Snitfladen kan knyttes som egenskab på  
    relationen, og en relation kan således have 0 eller 1 snitflade tilknyttet.

- **Snitflade**
  - En snitflade er en måde at binde to IT-systemer sammen. Ofte udgør en snitflade en måde,  
    hvorpå et IT-system udstiller data, som andre IT-systemer kan anvende. IT-systemet  
    udstiller data via snitflader (ex: søg, vis).
  - En snitflade kan også være udtryk for, at et IT-system udstiller handlinger (opret, ret, slet),  
    f.eks. i form af et API.
  - Et IT-system vil typisk både udstille et antal snitflader og anvende et antal snitflader.
  - En snitflade har altid en tilknytning til det IT-system, som udstiller snitfladen.
  - En snitflade har aldrig på forhånd en tilknytning til det IT-system, som er anvender.

På figuren nedenfor er illustreret, at IT-system x udstiller 3 snitflader.

IT-system y anvender Snitflade 1 og 2, hvorved der opstår 2 relationer mellem System x og System y.  
Tilsvarende anvender System z en relation til System x (uden at der er knyttet en snitflade til denne relation).  
Og System z anvender derudover Snitflade 2, hvorved der opstår 2 relationer mellem System x og System z.
``
<br>

<img width="1108" height="731" alt="image" src="https://github.com/user-attachments/assets/fffc5721-1392-4aee-b0b7-f7120b0e7098" />


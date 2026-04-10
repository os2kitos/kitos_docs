---
title: Opret relationer
layout: default
nav_order: 2
parent: Snitflader og relationer
---


Begrebet ”relationer” bliver i Kitos brugt til at beskrive hvordan to lokale IT-systemer er relateret til hinanden.
En relation har derfor et lokalt "udgående" (udstiller) system og et lokalt ”indgående" (anvender) system.  

## Udgående relation
<br>
Her fremgår de relationer, hvor dette system kalder eller benytter snitflader, som udstilles af andre it-systemer.
Det vil sige, at dette system er forbruger/anvender, og de relaterede systemer er udstillere af snitflader.
En relation redigeres udelukkende på ”anvender” siden under fanen udgående relationer.
I nedenstående eksempel har vi oprettet en relation inde på anvender-systemet "3manager" på en snitflade fra "kommunernes sygedagpengesystem" og derfor redigeres relationen her på anvendersiden, her under anvender-systemet "3manager".
<br>
<br>
<div style="margin-bottom: 2rem;">
<img width="2282" height="712" alt="image" src="https://github.com/user-attachments/assets/48a56b79-72c8-4f61-ba95-6b32bd2ea9c2" />
</div>
<br>

## Indgående relation
<br>
Herunder ses fanen "Indgående relationer".
Her fremgår de relationer, hvor dette system fungerer som udstiller af snitflader, der anvendes af andre it-systemer.
Det vil sige, at dette system er udstiller, og de relaterede systemer er forbrugere/anvendere.
I nedenstående eksempel vises at anvender-systemet "Kitos testsystem 1, anvender 3manager og 3manager snitfladen "test 3manager" i deres relationer og derfor skal disse relationer redigeres i anvendersystemet "Kitos testsystem 1".
<br>
<br>
<div style="margin-bottom: 2rem;">
<img width="2161" height="659" alt="image" src="https://github.com/user-attachments/assets/f8ad7f03-6157-44b4-85d9-6bf9390bb208" />

</div>
<br>

## Opret udgående relation
<br>
Relationer mellem IT-systemer oprettes af den enkelte kommune. Både det udstillende og det anvendende IT-system skal være taget i anvendelse i din kommune, før der kan oprettes relationer.

Relationer oprettes fra menupunktet ’Relationer’ under IT-systemer i anvendelse, ved at klikke på knappen
"Opret relation"
<br>
<br>
<div style="margin-bottom: 3rem;">
<img width="1854" height="896" alt="image" src="https://github.com/user-attachments/assets/f6a0e63b-7a7e-4ed0-a5f1-7ad448b84d8b" />

</div>

Når man klikker på knappen ’Opret relation’ møder man følgende dialogboks:
<br>
<br>


<div style="margin-bottom: 3rem;">
<img width="1276" height="868" alt="image" src="https://github.com/user-attachments/assets/46f41de6-656e-46fb-a6e1-0acde279ff76" />
</div>

<br>


- **Feltet "Søg efter system" (udstiller-system)** <br>
Her er det muligt at fremsøge IT-systemer, som man ønsker at oprette en relation til. Den enkelte kommune
kan kun oprette relationer til systemer, som de har i anvendelse. Feltet er obligatorisk at anvende.
<br>

- **Feltet Vælg Snitflade** <br>
Det er muligt at fremsøge og markere hvilken konkret snitflade, der anvendes i relationen. Der kan søges
blandt de snitflader, som er registreret på det valgte udstillersystem.
Hvis relationen f.eks. oprettes til Serviceplatformen, vil det være muligt at vælge snitflade blandt de mange
snitflader fra Serviceplatformen, som er oprettet i Kitos. 
<br>

- **Feltet Beskrivelse** <br>
Det er muligt at tilføje en beskrivelse til relationen.
<br>

- **Feltet Reference** <br>
Det er muligt at indsætte en reference/link til beskrivelsen af snitfladen.
<br>

- **Feltet Vælg kontrakt** <br>
Det er muligt at fremsøge og markere en kontrakt med betydning for relationen. Alle lokale registrerede kontrakter i kontraktmodulet kan fremsøges her.
<br>

- **Feltet Frekvens** <br>
Det er muligt at fremsøge og vælge med hvilken frekvens, IT-systemerne ”taler” sammen. 
<br>

Når felterne er udfyldt, klikkes **’Gem’** og relationen er oprettet.
<br>
<br>

## Fremsøgning af snitflader

Det er muligt at fremsøge en snitflade enten på navn eller via snitfladens ID og du kan bulkvælge snitflader ved at markere flere ad gangen.
<br>
<br>
<img width="766" height="815" alt="image" src="https://github.com/user-attachments/assets/c635471a-dec9-4d69-b337-ed3847b1755d" />

## Fremsøgning af snitflade ID i snitfladekataloget
<br>
I snitfladekataloget findes en snitflades ID, som forhindrer muligheden for at anvende dubletter.
Det er fra snitfladekataloget der fremsøges, når der dannes relationer mellem systemer via snitflader.
Det er også her en snitflades "udstiller" system findes.
<br>
<br>
<img width="2532" height="571" alt="image" src="https://github.com/user-attachments/assets/c449db40-0a6a-40c4-9340-1ccca0e2d9b2" />

<br>
<br>

## Sortering i relations fanen – bedre overblik over snitflader

Det er  muligt at sortere i relations fanen, så man bedre kan danne et overblik over sine relationer.
Dette gælder på fanen ”udgående relationer” og ”indkommende relationer”.
Klik blot på overskrifterne her markeret med en grøn pil og der sorteres i tabellerne efter alfabetisk rækkefølge.
Det er også muligt vælge frekvens eller søge i alle rækker og på den måde foretage en manuel sortering.
Der kan anvendes multiple filter ad gangen.

<br>

<img width="1828" height="685" alt="image" src="https://github.com/user-attachments/assets/99de67ea-b331-44a2-b796-a12711795b01" />

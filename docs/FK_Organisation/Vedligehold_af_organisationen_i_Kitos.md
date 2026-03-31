---
title: Vedligehold af organisationen i Kitos
layout: default
nav_order: 7
parent: FK Organisation
---

# Vedligehold af organisationen i Kitos

<br>

Hvis kommunen tilslutter Kitos til FK Organisation ændres arbejdsgangen for
organisationshierarkiet.

- Vedligehold af organisationshierarkiet foretages i FK Organisation (eller det
system der føder data hertil)
- Vedligeholdelse af Kitos registreringer, tilknyttet enheder i organisationen,
foretages stadig i Kitos.
- Det er muligt at ”flytte” registreringer fra én enhed til en anden direkte fra
organisationsmodulet.
  - Denne funktion er tilgængelig, uanset om kommunen har tilsluttet Kitos
til FK Organisation eller ej
  - Særligt efter en synkronisering der har medført ”konvertering til Kitos-
enhed” giver denne funktionalitet nem adgang til hurtigt at kunne
omregistrere fra og nedlægge den gamle (konverterede) enhed.


## Flytning af organisationsenheder


<br>

I organisationsmodulet i Kitos kan man redigere kommunens organisationshierarki.
Her er det muligt at flytte enheder, der er oprettet i Kitos, men man kan ikke flytte
enheder, der er synkroniseret fra FK Organisation.
De enheder, der er oprettet i Kitos er blå, mens enheder, der er synkroniseret fra FK
Organisation er grønne:

Vil du flytte en enhed oprettet i Kitos, trykker du på de 3 små prikker og herefter "Omstrukturer" og så kan du
flytte rundt på enheden. Når du er færdig med omstruktureringen, trykker du på
"Færdig".

<br>

<img width="854" height="730" alt="image" src="https://github.com/user-attachments/assets/047039c1-8215-48a9-b7dd-2e6d00167617" />

<br>

Du flytter enhederne rundt ved at "trække" med musen i de små prikker som fremgår ud fra enhederne:

<br>

<img width="618" height="595" alt="image" src="https://github.com/user-attachments/assets/b58f1997-1ac9-44f9-9782-12a62b6d812d" />

<br>

## Redigering og sletning af organisationsenheder


<br>

I Organisationsmodulet kan man slette organisationsenheder, der er oprettet i Kitos (
blå enheder), men man kan ikke slette organisationsenheder (grønne enheder), der er
synkroniseret fra FK Organisation.
Sletning af en enhed sker ved, at man stiller sig på enheden, og dernæst trykker på
"Rediger enhed". 

<br>

<img width="2541" height="773" alt="image" src="https://github.com/user-attachments/assets/50358e80-34d5-4a54-852d-489e206959a8" />

<br>

Så får man følgende billede hvor man kan se enhedens registreringer og slette enheden. Før enheden slettes, skal det bekræftes en ekstra gang, se herunder:

<br>

<img width="2299" height="1217" alt="image" src="https://github.com/user-attachments/assets/2d57fd5d-d46a-4876-a740-838d30dde254" />

<br>

Det er også i dette skærmbillede, at man kan redigere en enhed. 
Man kan både redigere en Kitos enhed (blå) samt organisationsenheder (grønne), der er
synkroniseret fra FK Organisation. Der er dog forskel på, hvor meget man kan
redigere de 2 typer enheder.

For en Kitos enhed (blå) kan man redigere følgende data:
- Overordnet enhed
- Enhedens navn
- EAN nummer
- Enheds ID.

For en enhed synkroniseret fra FK Organisation (grøn) kan man redigere følgende
data:
- EAN nummer
- Enhed ID
(felterne overordnet enhed samt enhedens navn vil være grå og ikke rediger-bare).

<br>

<img width="2059" height="1225" alt="image" src="https://github.com/user-attachments/assets/7e553271-43e7-4707-a1a3-9e730b46501c" />


**Ændre overordnet enhed**


<br>

I feltet ”Overordnet enhed” kan man med den lille pil i højre side folde
organisationshierarkiet ud og vælge en ny overordnet enhed.

<img width="2050" height="620" alt="image" src="https://github.com/user-attachments/assets/198ed15f-ebf2-4ef5-8b03-b0689c857704" />

<br>
<br>


**Oprettelse af underenhed**

<br>

Det er også muligt at oprette en underenhed for både en Kitos enhed (blå) samt en
enhed synkroniseret fra FK Organisation (grøn). 
Det sker via de 3 små prikker i menuen herunder:

<img width="2523" height="560" alt="image" src="https://github.com/user-attachments/assets/a6b1b4a4-189f-4142-bb68-d655cb382311" />

<br>

Og herefter kan man indtaste data for den nye underenhed:

<br>

<img width="1836" height="851" alt="image" src="https://github.com/user-attachments/assets/582c9fcb-7946-4f97-96e1-549ee330f2da" />

<br>


**Flytning af registreringer fra en organisationsenhed**

<br>

I forbindelse med redigering af organisationshierarkiet kan man flytte registreringer
fra en enhed til en anden, uafhængig af om det er en Kitos enhed eller en enhed
synkroniseret fra FK Organisation. Dette er et vigtigt trin inden du evt. sletter en organisationsenhed.

Det foregår i Rediger enhed som du finder øverst i højre hjørne af skærmen:

<br>

<img width="2484" height="1207" alt="image" src="https://github.com/user-attachments/assets/1e868c6e-ed31-4c92-8c31-e12a76303ad0" />

<br>

Her kan man først vælge hvem man vil overføre registreringerne til og efterfølgende markere de valgt eller vælge at overføre alle.
De systemer og/eller kontrakter/DBA/Betalinger der er registreringer på, kan
man navigere til, da det er aktive links:

<br>

<img width="2484" height="1207" alt="image" src="https://github.com/user-attachments/assets/a6223c9a-e42f-443e-ad95-97cf26d0527f" />

<br>

Her har man så mulighed for at vælge enkelte eller alle registreringer ved at sætte
hak samt vælge hvilken organisationsenhed den eller de registreringer skal overføres
til.


**Sletning af registreringer fra en organisationsenhed**

<br>

I forbindelse med redigering af organisationshierarkiet kan man slette registreringer
fra en enhed, uafhængig af om det er en Kitos enhed (blå) eller en enhed
synkroniseret fra FK Organisation (grøn).
Det foregår i samme skærmbillede som overfor, som du finder under knappen Rediger enhed:

<br>

<img width="2539" height="1208" alt="image" src="https://github.com/user-attachments/assets/d51fcd98-856e-4a8c-b21d-91845230cfd8" />

<br>

Her har man så mulighed for at vælge enkelte eller alle registreringer ved at sætte
hak samt trykke på Slet valgte.

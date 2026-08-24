---
title: Vejledning til advis funktion
layout: default
nav_order: 1
parent: Advis
---
 
Her kan du se en vejledning til advis funktionen i OS2Kitos.

# Vejledning i advis-funktionen

*08.01.24*

## Baggrund

I Kitos kan du sende en advis (påmindelse) til udvalgte personer i organisationen eller udvalgte brugergrupper som fx Systemejere, Superbrugere m.fl.

Advis-funktionen kan både sende straksbeskeder samt beskeder udsendt efter et bestemt tidsinterval (time, dag, uge, måned, kvartal, halvårlig og år).

Advis-funktionen kan fx bruges til at sende en påmindelse til en Systemejer og en Kontraktansvarlig, så de i god tid får at vide, at deres kontrakt skal fornyes.

Er advis'en målrettet en rolle i modsætning til en navngiven person, vil advis'en i tilfælde af personaleudskiftning automatisk blive sendt til den nye Systemejer eller Kontraktansvarlige. Det er derfor en god ide at målrette en advis til en rolle.

Advis-funktionen kan bruges under følgende moduler:

- IT-Systemer
- Databehandling
- Kontrakter

Du opretter en advis på samme måde under de 3 moduler. Der er i denne vejledning vist en advis i modulet Databehandling.

## Aktiv/inaktiv advis

### Definitionen på en inaktiv advis er:

- En enkeltstående advis, der er afsendt
- En advis med gentagelse, hvor til-datoen er overskredet
- En advis der er blevet deaktiveret

### Og deraf er en aktiv advis:

- En advis med gentagelse, hvor til-datoen ikke er overskredet
- En advis der ikke er blevet deaktiveret

## Opret en advis

For at oprette en advis på et objekt, her en databehandling, skal du:

- Klik på **Advis** i venstremenuen
- Klik på **+Ny**

<img width="2100" height="694" alt="image" src="https://github.com/user-attachments/assets/c4366a3d-90e7-4abb-a543-2ba56ec40f85" />

Du får nu et skærmbillede med en række felter, som du skal udfylde.

<img width="926" height="905" alt="image" src="https://github.com/user-attachments/assets/6ba989d3-6917-47ad-b9b2-384778fb0b14" />


## Valg af modtager - roller eller personer?

Der skelnes mellem at sende advis til roller eller til personer via e-mail. Den sikreste måde er at sende til roller, da det er rolleindehaveren på afsendelsesdagen, som modtager beskeden.

Hvis du sender til en konkret person, risikerer du, at den person ikke længere er relevant på afsendelsesdagen. Dette gælder især, hvis du vil sende advis’en med gentagelse.

Det kan også lade sig gøre både at sende til en rolle og til en person via e-mail adresse, hvis du har brug for det. Så skal du bruge begge muligheder skitseret herunder.

### Hvis du ønsker at sende en advis til en eller flere roller

- Klik i feltet **"Til modtager via rolle"**
- Vælg den eller de rolle(r) som advisen skal sendes til (fx DPO)

### Hvis du ønsker at sende en advis til en eller flere e-mail adresser

- Klik på **"Til modtager via email"**
- Indsæt den eller de e-mails, du ønsker at sende advisen til

Indsætter du flere e-mail adresser, skal de adskilles af et komma:

```text
email1@mail.dk, email2@mail.dk
```

## Valg af cc modtager - roller eller personer?

Der skelnes mellem at sende en advis cc til roller og til personer via e-mail. Den sikreste måde er som nævnt ovenfor at sende til roller, da det er rolleindehaveren på afsendelsesdagen, som modtager beskeden.

Hvis du sender til en konkret person, risikerer du, at den person ikke længere er relevant på afsendelsesdagen.

Det kan også lade sig gøre både at sende cc til en rolle og til en e-mail adresse, hvis du har brug for det. Så skal du bruge begge muligheder skitseret herunder.

### Hvis du ønsker at sende en advis cc til en eller flere rolle(r)

- Klik på feltet **"CC modtager via rolle"**
- Vælg den eller de rolle(r) som skal sættes cc på advisen

### Hvis du ønsker at sende en advis cc til en eller flere e-mail adresse(r)

- Klik på **"CC modtager via email"**
- Indsæt den eller de e-mail adresser, du ønsker at sende advisen til

Indsætter du flere e-mail adresser, skal de adskilles af et komma:

```text
email1@mail.dk, email2@mail.dk
```

## Send advis med det samme (straksafsendelse)


<img width="614" height="653" alt="image" src="https://github.com/user-attachments/assets/875aa081-9006-4da2-b18e-12647977a5cb" />

Når du vil sende din advis med det samme og du har udfyldt modtager(r) og evt. cc-modtagere som beskrevet ovenfor, så skal du udfylde de øvrige felter i advis’en:

- Udfyld feltet **"Emne"**
- Skriv evt. en besked i tekstfeltet **Email tekst**
- Vælg afsendelsestype **"Straks"**
- Klik på **Gem**-knappen under tekstfeltet for at sende beskeden med det samme

## Send en enkeltstående advis, der er fremdateret

Såfremt du vil sende en advis en enkelt gang, men ude i fremtiden, skal du oprette advis’en som en gentagelsesadvis.

Den dato som du vil have at advis’en skal sendes, skal angives som både fra- og til-dato.

## Send advis, der gentages


<img width="605" height="674" alt="image" src="https://github.com/user-attachments/assets/53264b1e-bb4f-46ee-aa11-3640f70a5f89" />

Hvis du i stedet vil sende advisen med et givent interval, skal du udfylde modtagere og emne samt evt. skrive en besked i tekstfeltet.

Dernæst skal du:

- Vælg afsendelsestype **"Gentagelse"**, hvorefter der åbner nye felter op
- I feltet **Navn** kan du angivet et navn på advis’en (det vises i oversigten) – det kan fx være navnet på det objekt (kontrakt, system, projekt, databehandling), advisen knytter sig til
- I feltet **Gentagelse** vælger du det interval, du ønsker advisen skal sendes i
- I feltet **Fra-dato** vælger du den dato, der angiver hvornår advisen skal sendes første gang – bemærk Fra-dato kan ikke være før d.d.
- I feltet **Til-dato** kan du vælge den slutdato for intervallet, hvor advisen udsendes. Lader du feltet være tomt, vil advisen blive sendt i det uendelige – eller indtil objektet (her databehandlingen) bliver slettet, du deaktiverer din advis eller hvis du senere indsætter en Til-dato
- Klik på **Gem**-knappen for at gemme advisen

### Feltforklaringer

**Navn**  
Det vises i oversigten og kan fx være navnet på det objekt (kontrakt, system, projekt eller databehandling), advisen knytter sig til.

**Gentagelse**  
Her vælges det interval, du ønsker advisen skal sendes med.

**Fra-dato**  
Bemærk at Fra-dato ikke kan være før dags dato.

**Til-dato**  
Lader du feltet være tomt, vil advisen blive sendt i det uendelige, eller indtil objektet bliver slettet, advisen deaktiveres, eller der senere indsættes en Til-dato.

### Kvartal og halvårlig

Ved brug af **Kvartal** eller **Halvårlig** sendes første advis på den valgte dato og efterfølgende på den valgte dag med det interval, der er valgt:

- Kvartal = hver 3. måned
- Halvårlig = hver 6. måned

Hvis man vælger en dag der er større end 28, vises information om, at i måneder der ikke indeholder 29, 30 eller 31, vil advis blive sendt den sidste dag i den aktuelle måned.

## Ændring af advis

Det er alene muligt at ændre en advis, der er aktiv, altså:

- En advis med gentagelse, hvor til-datoen ikke er overskredet
- En advis der ikke er blevet deaktiveret

Du kan ikke redigere en inaktiv (allerede afsendt) advis.

Derved vil det ikke kunne lade sig gøre at ændre en straksafsendt advis. Men du kan godt åbne den, så du kan læse, hvad der står i den. Det gør du ved at trykke på blyants-ikonet ud af advisen.

Her er alle felter grå, du kan se, men ikke ændre advisen.

Du kan ændre en advis med gentagelse, hvor til-dato ikke er overskredet. Og her er det uden betydning om fra-dato er nået eller ej.

Det gør du ved at trykke på blyants-ikonet ud for advisen.

### Du kan nu ændre den aktive advis med hensyn til følgende

- Til-dato
- Emne
- Navn
- Modtagere

De øvrige felter er grå – dem kan du ikke ændre.

Hvis du har brug for at ændre:

- Fra-dato
- Gentagelse
- Advis-typen (straks/gentagelse)

så må du oprette en ny advis.

Og så kan du overveje, om du skal deaktivere den gamle advis.

## Deaktivering af en advis

Du kan stoppe, altså deaktivere en aktiv advis, der er oprettet med gentagelse og hvor Til-dato ikke er overskredet.

Man vil fortsat kunne se tidligere afsendte adviser i boksen **Afsendt** til højre.

Du trykker på blyantikonet på oversigten.

For at deaktivere den aktive advis med gentagelse, skal du trykke på **Deaktivér** (og vælge OK i advarslen), så vil der ikke blive afsendt flere adviseringer og den pågældende advis vil ikke længere kunne redigeres, da den er inaktiv.

Efter du har deaktiveret en advis, kan du se, at hakket ud for advisen er fjernet og du kan i **Afsendt**-boksen til højre se, hvornår advisen er blevet afsendt.

## Sletning af en advis

Man kan ikke slette en advis, der allerede er afsendt.

Det betyder, at:

- En straksafsendt advis ikke kan slettes
- En advis med gentagelse, hvor der er afsendt en advis, heller ikke kan slettes

En advis med gentagelse, hvor advis endnu ikke er afsendt, kan slettes, såfremt man først deaktiverer den.

Når du siger OK i advarslen om, at du er ved at deaktivere, kan du efterfølgende trykke på skraldespandsikonet i oversigten og dermed slette advisen.

Inden sletningen får effekt, bliver man adviseret om, at man er i gang med at slette.

## Advisering om, at en advis ikke er fremsendt som planlagt

Hvis du har oprettet en advis, som ikke bliver fremsendt som planlagt, bliver du adviseret.

Der kan være flere årsager til, at en advis ikke kommer frem:

- Mailserveren er nede og derfor ikke kan sende den
- Du har valgt at sende din advis til en rolle, men der ikke er koblet en bruger på den rolle


Derfra kan du trykke på linket i feltet **Navn** og komme ind på den konkrete advis, hvor du kan undersøge, hvem du skal kontakte for at give den besked, som advis’en skulle have givet.

Når du har gjort det, kan du fjerne notifikationen ved at trykke på knappen **"Ok og slet"** på oversigten.

## Muligheder for at få overblik over adviser

På overblikssiden over advis for det enkelte objekt (system, kontrakt, databehandling, projekt) kan du se de adviser, der er oprettet for det givne objekt og om en advis er aktiv eller ej (hak i feltet Aktiv).


<img width="1652" height="531" alt="image" src="https://github.com/user-attachments/assets/20a323f4-d67c-460d-808d-8d421cafcc23" />

Her kan du i højre side redigere eller slette ikke afsendte eller gentagende adviser, samt se om advis er sendt.

Du har også mulighed for at få et overordnet overblik over adviser for et givent modul (system, kontrakt, projekt eller databehandling).

### Oversigt via klokke-ikonet

På oversigten ved klokke-ikonet øverst til højre i hvert modul vises advis’er med gentagelse, der er aktive.
<img width="1568" height="414" alt="image" src="https://github.com/user-attachments/assets/d40db8b9-215a-42ab-b501-6700769d7bd2" />

Herfra får du en oversigt over de adviser, der er aktive (kommende) og dem som ikke er blevet fremsendt som planlagt (Ikke sendte advis).

Det vil sige advis’er:

- Hvor Til-dato ikke er nået
- Som ikke er blevet deaktiveret af brugeren

Efter tryk på klokkeikonet ser du denne oversigt.


<img width="2528" height="529" alt="image" src="https://github.com/user-attachments/assets/ce681a5b-11a7-4688-9ae8-4e7782bc7a57" />


## Hvad sker der, hvis man sletter eller inaktiverer et objekt?

- Hvis du sletter en databehandlerregistrering eller en kontrakt, hvor du har opsat en aktiv advis, så vil advisen ikke længere blive fremsendt.
- Hvis du har en aktiv advis på en kontrakt, og du sætter denne kontrakt inaktiv, så vil din advis fortsat blive sendt, hvorfor du kan vælge at slette eller deaktivere din advis, hvis det er relevant.
- Hvis du har en aktiv advis på et system, og du fjerner din kommunes anvendelse af dette system, så vil advisen ikke længere blive fremsendt.
- Hvis sekretariatet deaktiverer et system, som din kommune har i anvendelse (så vil det fremgå med "ikke aktivt" bag systemnavnet) og du har en aktiv advis på dette system, så vil advisen fortsat blive fremsendt.

> Husk at du altid kan klikke på hjælpe-ikonet, hvis der er noget, som du bliver i tvivl om undervejs!



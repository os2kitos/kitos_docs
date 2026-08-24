---
title: Anvendelse af IT-systemer
layout: default
nav_order: 2
parent: System modulet
---
 
Her kan du se en vejledende til hvordan man tager systemer i anvendelse fra OS2Kitos fællesoffentlige IT-systemkatalog.

# Anvendelse af IT-systemer

*Opdateret 04.12.23*

## Baggrund

IT-systemkataloget er det samlede katalog over alle registrerede IT-systemer i Kitos. Det er således i IT-systemkataloget, kommunerne kan plukke de systemer ud, som anvendes i den pågældende kommune.

## Tilgængelige/Ikke tilgængelige systemer

I oversigten i IT-systemkataloget er der en kolonne, der gør det muligt at få vist henholdsvis de tilgængelige og de ikke tilgængelige systemer.

<img width="2555" height="541" alt="image" src="https://github.com/user-attachments/assets/ce226d75-1d32-4266-86ee-5914538a136a" />

Alle tilgængelige systemer kan tages i anvendelse, ved at klikke "anvendes" ud for systemet.
Som udgangspunkt vises de tilgængelige systemer i oversigten, men man har mulighed for at aktivere filtreringen i kolonnen, til at vise **"ikke tilgængelige systemer"**. Ikke-tilgængelige systemer er blevet gjort ikke-tilgængelige af Sekretariatet. Tidligere blev de ikke-tilgængelige systemer benævnt som deaktiverede systemer.

Når et system er gjort ikke-tilgængeligt, ses det ved, at der står **"(Ikke tilgængeligt)"** bag systemnavnet.

Et ikke-tilgængeligt system er et system, der ikke kan tages i anvendelse længere, men som man af den ene eller anden grund har interesse i at bibeholde i Kitos. Det kunne for eksempel være for at bibeholde et historisk overblik over systemanvendelsen.

Man kan ikke tage et ikke-tilgængeligt system i anvendelse, men har man det allerede i anvendelse, vil det fortsat være muligt at redigere lokale data. Det betyder også, at en kommune godt kan have et ikke-tilgængeligt system med status aktiv.

Det er kun Sekretariatet, der kan gøre et system ikke-tilgængeligt. Dog - hvis I ser, at et system er gjort ikke-tilgængeligt, men mener, at Sekretariatet har lavet en fejl, så kontakt os på info@kitos.dk, så kan vi gøre systemet tilgængeligt igen.

---

# Livscyklus for systemer og visning af aktive/ikke aktive systemer

På det lokale IT-systemoverblik i kommunen er du mulighed for at vælge, om du vil se de aktive eller ikke aktive systemer med en kolonne i overblikket:

<img width="2559" height="380" alt="image" src="https://github.com/user-attachments/assets/b81a632e-1b6d-4089-8ec7-d28937ec671f" />


Et system har status **aktivt** i oversigten, såfremt alle statusfelter viser aktiv:

- Status - Overordnet status på baggrund nedenstående felter
- Datofelter – vist i feltet **Status (Datofelter)**
- Livscyklus – vist i feltet **Status (Livscyklus)**
- Markeret kontrakt – vist i feltet **Status (Markeret kontrakt)**

Der er således flere statusfelter, der afgør om et system betragtes som aktivt eller ej.

<img width="1043" height="275" alt="image" src="https://github.com/user-attachments/assets/05d01704-fbcb-4370-b8a5-d2ddb1dea79c" />


På systemforsiden kan man se, om et system er aktivt eller ej samt hvorfor.

I feltet det lille label ved siden af systemnavnet, bliver man præsenteret for en status på systemet. Er systemet ikke-aktivt, kan man får oplysninger om, hvorfor et system ikke er aktivt ved at holde musemarkøren henover.
<img width="1501" height="557" alt="image" src="https://github.com/user-attachments/assets/befbd95b-ab9e-42bc-807d-2d9a48b5faaa" />

Hvis du ikke ønsker at benytte de 4 statusfelter i oversigten, har du mulighed for at fravælge brug af disse. Se mere i vejledningen:

**"Lokale opsætninger og Lokal admin settings"**

Her kan du se, hvordan du fravælger et eller flere af de felter, der ligger til grund for statusfelterne i oversigten.

Vær dog ekstra opmærksom på, at såfremt du fravælger et felt, der ligger til grund for statusfelterne i oversigten, og der er udfyldt data i feltet, vil dette stadig have betydning for systemets status.


### status (markeret kontrakt)

Der kan på systemet markeres en kontrakt, der skal afgøre om systemet er aktivt.

<img width="2227" height="769" alt="image" src="https://github.com/user-attachments/assets/24889571-5bec-4836-9aac-8c25de62716a" />


Feltet **"Hvilken kontrakt skal afgøre om IT-systemet er aktivt"** på kontraktfanen afgør om systemet er aktivt ifølge markeret kontrakt.

Hvis der er tilknyttet en kontrakt, der har status **ikke gyldig**, vil systemet betragtes som ikke aktivt.

Øvrige værdier – altså at der ikke er knyttet en kontrakt til systemet eller at den tilknyttede kontrakt er gyldig – gør, at systemet betragtes som aktivt.

Om systemet er aktivt eller ikke aktivt ifølge værdien på kontraktfanen, vises i oversigten i feltet: **Status (Markeret kontrakt)**


## Status (Livscyklus for IT-systemer)

På systemforsiden ses feltet **Livscyklus**, der specificerer livscyklus for et system med værdierne:

- Blank (ikke taget stilling)
- Under afprøvning
- Under indfasning
- I drift
- Under udfasning
- Ikke i drift


<img width="1890" height="395" alt="image" src="https://github.com/user-attachments/assets/c82a6ae0-d958-4a80-827d-53c92dcee47f" />


Værdien i feltet **Livscyklus** afgør om systemet er aktivt ifølge livscyklus.

Hvis værdien er **"Ikke i drift"**, eller **under afprøvning** betragtes systemet som ikke aktivt.

Alle øvrige værdier gør, at systemet betragtes som aktivt.

Om systemet er aktivt eller ikke aktivt ifølge værdien i feltet Livscyklus, vises i oversigten i feltet:


**Status (Datofelter)**

På systemforsiden under rubrikken systemanvendelse, ses feltet **slutdato på anvendelse**, der specificerer om systemet er aktivt ud fra dato.

<img width="1925" height="420" alt="image" src="https://github.com/user-attachments/assets/5a0d7950-7b42-46f3-a784-907f54ebd461" />



Der er således 3 parametre, der er afgørende for om et system er aktivt eller ej:

- Aktivt ifølge datofelterne Ibrugtagningsdato og Slutdato for anvendelse (d.d. inden for perioden eller hvis hverken start eller slut er defineret)
- Aktivt ifølge Livscyklus (blank, under indfasning, i drift eller under udfasning)
- Aktivt ifølge markeret kontrakt (hvis der ingen kontrakt er markeret eller den markerede kontrakt er gyldig)

Hvis bare én af de 3 parametre angiver, at systemet ikke er aktivt, vil systemet have status af at være ikke aktivt.

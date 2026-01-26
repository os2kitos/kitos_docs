---
title: Kontrakt modulet - Forsiden og oversigten 
layout: default
nav_order: 1
parent: Kontrakt modulet
---

 
# Vejledning til kontraktforside og overblikket

## Oversigten
Fra oversigten kan man eksportere data til Excel, og har mulighed for at eksportere samtlige
kolonner eller de viste kolonner. På den måde kan man udtrække data og efterbehandle, sende til
kontrol andre steder i organisationen eller hvad man nu har brug for.

Man kan også bruge Kitos’s API til dataudtræk.

<img width="2554" height="451" alt="image" src="https://github.com/user-attachments/assets/43944b74-b4aa-4883-bc28-286057f714da" />


## Opret kontrakt
Det er også fra oversigten, du kan oprette en ny IT-Kontrakt ved at klikke på knappen **Opret IT Kontrakt**.

Du ser nu en dialogboks, hvor du skal skrive kontraktens navn, hvilket er mindstekrav for at oprette
en kontrakt.

Klikker du på knappen **Gem, og gå til IT Kontrakt**, lukkes dialogboksen, og kontraktens formular
vises på skærmen, og du kan nu udfylde flere data om kontrakten.

<img width="411" height="200" alt="image" src="https://github.com/user-attachments/assets/c3efe88e-f0c8-4aa7-b3e3-36a5090e2632" />


## Navigation
Når man klikker på en kontrakt kommer man til kontraktens forside. I venstremenuen herunder kan du navigere mellem de forskellige afsnit i kontrakten:

<img width="2186" height="814" alt="image" src="https://github.com/user-attachments/assets/a0382ca5-ba69-4b6e-af30-2577871d1b5f" />


---

## Fanen Kontraktforside
På kontraktforsiden finder du de overordnede og generelle informationer om kontrakten:

- **Kontraktnavn**  
  Her angives kontraktens navn

- **KontraktID**  
  Her kan du registrere et internt ID, hvis det er relevant

- **Kontrakttype**  
  Vælg kontrakttype fx hovedkontrakt, serviceaftale

- **Kontraktskabelon**  
  Standardkontrakt eller kontraktskabelon

- **Kritikalitet**  
  Her kan du vælge, hvilken kritikalitet, du vil give kontrakten

- **Oprettet af**  
  Indeholder navn på den bruger, der har oprettet kontrakten. Er udelukkende en visning.

- **Indkøbsform**  
  Vælg indkøbsform fx SKI, EU udbud, direkte tildeling

- **Genanskaffelsesstrategi**  
  Vælg genanskaffelsesstrategi, fx Annoncering, mini-udbud, EU udbud

- **Genanskaffelsesplan**  
  Vælg genanskaffelsesplan for kontrakten

- **Genanskaffelse igangsat**  
  Feltet er default tomt og du kan vælge ja eller nej.

- **Bemærkning**  
  Her kan du skrive bemærkninger eller noter

- **Overordnet kontrakt**  
  Her kan du registrere en overordnet kontrakt, til den pågældende kontrakt.

 - **Nedarv den overordnedes gyldighed**
  Hvis man krydser feltet af "Nedarv den overordnedes gyldighed", så vil den pågældende kontrakts status, altid være denne samme, som dens overordnede kontrakt. Dette betyder hvis en       kontrakts overordnet kontrakt ændrer status fra ”gyldig” til ”ikke-gyldig”, træder dette i kraft på de underliggende kontrakter, hvor denne markering er valgt til.
Funktionen er tiltænkt så man kan få en hovedkontrakts udløb, til at træde i kraft på alle dens underliggende kontrakter. Hvis man går til fanen ”Hierarki” kan man se om en kontrakt nedarver gyldigheden fra en overordnet kontrakt.


- **Ansvarlig organisationsenhed**  
 Har kan du knytte en ansvarlig organisationsenhed til din kontrakt, organisationens kontraktunderskriver, samt dato. Der kan ligeledes sættes en fluebensmarkering på når kontrakten er   underskrevet.

- **Leverandør**  
  Vælg leverandør. Leverandøren skal være oprettet som virksomhed i Kitos.  
  Du kan fremsøge leverandøren ved hjælp af navn eller cvr.nr.

- **Leverandørens kontraktunderskriver**  
  Skriv hvilken person, som har skrevet under på kontrakten.  
  Du kan vælge en bruger oprettet i Kitos eller bare navnet på underskriveren.

- **Underskrevet**  
  Afkryds hvis kontrakten er underskrevet

- **Dato (leverandør)**  
  Dato for leverandørens underskrift

- **Ansvarlig enhed**  
  Vælg hvilken organisatorisk enhed, der er ansvarlig for kontrakten

- **Kontraktunderskriver (kommune)**  
  Skriv hvilken person, som har skrevet under på kontrakten.  
  Du kan vælge en bruger oprettet i Kitos eller bare navnet på underskriveren.

- **Underskrevet**  
  Afkryds hvis kontrakten er underskrevet

- **Dato (kommune)**  
  Dato for kommunens underskrift

- **Gyldig fra**  
  Dato for hvornår kontrakten er gyldig fra.  
  Hvis felterne Gyldig fra og Gyldig til ikke er tomme, skal dags dato ligge mellem datoerne.

- **Gyldig til**  
  Dato for hvornår kontrakten er gyldig til.  
  Hvis felterne Gyldig fra og Gyldig til ikke er tomme, skal dags dato ligge mellem datoerne.

- **Gennemtving Gyldighed**  
  Giver mulighed for at gennemtvinge at kontrakten er gyldig uanset om andre parametre peger på ugyldighed.

- **Status**  
  Viser om kontrakten er gyldig eller ej.  
  Feltet kan foldes ud for mere info.

- **Sidst redigeret: Bruger**  
  Viser hvilken bruger der sidst har redigeret kontrakten.

- **Sidst redigeret: Dato**  
  Viser hvornår kontrakten sidst er blevet redigeret.

Der er små *?*-ikoner ved felterne **Indkøbsform** og **Genanskaffelsesstrategi** med mere info.  
Der kan også være et lille *i*, hvis lokal admin har tilføjet beskrivelser til udfaldsrum.

---

## Hvornår er en kontrakt gyldig og hvordan ser man det?

**Årsager til ugyldighed:**
- ”Gyldig fra” er endnu ikke passeret
- ”Gyldig til” er passeret
- Kontrakten er opsagt og opsigelsesperioden er passeret

**Kontrakten er gyldig, hvis:**
- ”Gyldig fra” ikke er defineret
- ”Gyldig fra” er passeret
- ”Gyldig til” ikke er defineret
- ”Gyldig til” er defineret, men ikke passeret
- Kontrakten er ikke opsagt
- Kontrakten er opsagt, men opsigelsesperioden er ikke passeret

**Kontrakten er ALTID gyldig**, hvis feltet **Gennemtving Gyldighed** er anvendt.

Når en kontrakt har status *ikke gyldig*, kan man åbne feltet for mere information.

<img width="2175" height="716" alt="image" src="https://github.com/user-attachments/assets/0cadd64a-a512-4d19-8f67-8b85c49c19cb" />

## Slet kontrakt

- Når man klikker på knappen "Slet kontrakt" åbnes et vindue, hvor du skal bekræfte sletning. Er kontrakten en enkeltstående kontrakt, som ikke er markeret som "overordnet kontrakt" for andre kontrakter, så slettes kontrakten når der trykkes "Ja" herunder.


<img width="2002" height="786" alt="image" src="https://github.com/user-attachments/assets/4d91adc8-1903-4e5a-be4d-2740502b215c" />


Hvis kontrakten du forsøger at slette, har underliggende kontrakter tilknyttet, dvs. kontrakter som har registreret denne kontrakt for "overordnet kontrakt" så ser pop up vinduet anderledes ud, når du forsøger at slette kontrakten.

Ved sletning vil du her få muligheden for samtidig at slette ALLE de underliggende kontrakter, som har registreret denne kontrakt for overordnet kontrakt. 
Hvis du vil gøre dette, skal du trykke "Ja" på skærmbileldet herunder:

<img width="1767" height="815" alt="image" src="https://github.com/user-attachments/assets/000f1399-5084-466d-b02d-9e59dbe38a14" />


Når du har trykket "Ja" skal du bekræfte en ekstra gang, før din kontrakt sammen med ALLE de registrerede underliggende kontrakter slettes.

<img width="689" height="393" alt="image" src="https://github.com/user-attachments/assets/b4764cb4-a612-4bf8-ada8-548f233e5862" />

- Skal de underliggende kontrakter IKKE slettes, kan du vælge at overføre disse kontrakter til en anden overodnet kontrakt, unden du sletter din kontrakt.
Når du har trykket på knappen "Overfør" kommer der er vindue frem, hvor du kan vælge hvilke kontrakter du vil have overført til en anden kontrakt.

<img width="1066" height="690" alt="image" src="https://github.com/user-attachments/assets/ab3bd035-090a-437b-9b5e-540e818ed2c8" />

Når kontrakter der ikke skal slettes er overført til en anden kontrakt, kan du gå tilbage og slette kontrakten.

---

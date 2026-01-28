---
title: Introduktion af FK Organisation
layout: default
nav_order: 1
parent: Organisation
---

Her kan du se en vejledning til hvordan du kommer igang med integrationen til FK Organisation - Ny vejledning udarbejdet af OS2Sekreatarietet pr. 29.01.2026


**Integration til FK Organisation samt vedligeholdelse af Organisationshierarki i Kitos**

- Indhold
- **Funktionsoverblik**
- Overvej om integration til FK er det rigtige for jeres kommune 
- Gør det en forskel om jeres organisation er opdateret og hvordan? 
- Muligheder for at tilpasse integrationen 
- **Forudsætninger - generelt**
- Der er en række forudsætninger, der skal være på plads, før man kan tage integrationen til FK Organisation i anvendelse.
- Oprydning i lokal administratorer 
- Data i FK Organisation 5
- Serviceaftale 
- **Adgang til funktionaliteten – og test i Staging-miljøet**
- **Aktivering af funktionen i produktionsmiljøet**
- **Synkronisering med FK Organisation**
- Synkroniseringsmetode 
- Synkronisering - niveauer 
- Ændringsloggen 
- Synkronisering – enhedstyper 
- Synkronisering – konsekvenser 
- **Vedligehold af organisationen i Kitos**
- Flytning af organisationsenheder
- Redigering og sletning af organisationsenheder 
- Oprettelse af underenhed 
- Flytning af registreringer fra en organisationsenhed 
- Sletning af registreringer fra en organisationsenhed
- At bryde forbindelsen til FK Organisation 


**Funktionsoverblik**
Brugerklubben har ønsket muligheden for at hente kommunens organisation ind fra
FK Organisation.
Nu (marts 2023 – og revideret maj 2023) er funktionaliteten udviklet. Dette
dokument gennemgår de tekniske muligheder. Vi vil dog også ganske kort redgøre for
en række taktiske overvejelser, som I bør forholde jer til som det første.

*Overvej om integration til FK er det rigtige for jeres kommune*
I kan altid vedligeholde jeres organisation manuelt i Kitos.
En manuel administration af organisationen betyder, at lokaladministratoren selv skal
løse opgaven, og at denne person teknisk set har al magten over navngivningen og
niveauer i den organisation, der vises i Kitos. Det kan være en styrke eller en svaghed
– alt efter hvordan I arbejder lokalt.
Med den nye funktionalitet kan organisationen blive opdateret automatisk. Hvis I
kobler Kitos op på FK organisation, vil organisationen i Kitos være en gengivelse af
den organisation, som ligger i FK Organisation. I kan sortere konkrete led og niveauer
fra, hvilket beskrives i vejledningen, men Kitos vil vise det hierarki og den
navngivning der er i FK. Magten og ansvaret ligger altså ikke længere alene hos lokal
administratoren, men i et samspil med de aktører, der administrerer FK Organisation.
Det betyder eks. at hvis et center skifter navn fra ”Politik og Organisation” til ”Politik
og Digitalisering”, så vil navnet blive ændret i Kitos kort efter at det bliver ændret i FK
organisation. Muligheder og detaljer for opsætningen bliver beskrevet her i
vejledningen.

*Gør det en forskel om jeres organisation er opdateret og hvordan?*
Kommunerne arbejder forskelligt med Kitos – også med organisation. Nogle af jer
knytter ansvar eller opgaver i Kitos til organisationsenheder. Det er her at
datakvaliteten, altså eksempelvis navngivningen af organisationsenheder, kan have
en betydning.
En kobling til FK er en garanti for, at organisationsenheder ikke skifter navn eller
placering uden at lokal administratoren er bevidst om det. Lokal administratoren har
dermed chancen for at rette de tilknytninger, som kan være koblet til enheden. Det er
samtidig en forpligtelse. Lokal administratoren skal helst handle hver gang, der sker
ændringer i FK organisation, som har betydning i Kitos. Det er værd at overveje,
eksempelvis ved ferie, sygdom og orlov.
Samtidig er der kommuner, der ikke har intern enighed om hierarkiet og
navngivningen. Man kan altså risikere at forvirre brugerne i Kitos, hvis oplysningerne i
FK ikke er brugbare til deres formål.
I skal altså spørge jer selv:
- Hvordan ser vores organisation ud i Kitos i dag og hvorfor?
o Hvilke tilknytninger har vi til hierarkiet og hvorfor?
- Hvor ofte foretager I ændringer og hvorfor?
- Viser FK organisation en struktur og en navngivning som er meningsfuld for
brugerne af Kitos?
- Har Lokal administratoren kendskab til FK organisation og/eller et godt
samarbejde med dem, der administrerer FK Organisation?

*Muligheder for at tilpasse integrationen*
Organisationsenheder indlæst fra FK Organisation kan sameksisterer med
organisationsenheder oprettet manuelt i Kitos, og man kan med farvekoder se, hvilke
organisationsenheder, der kommer fra FK Organisation og hvilke, der er oprettet
manuelt.
Man kan vælge, om man vil opsætte Kitos til automatisk at tjekke for opdateringer i
FK Organisation (ugentligt) eller om man vil vælge at gøre dette efter behov, hvor
man selv vælger, hvornår Kitos skal tjekke for opdateringer i FK Organisation.
Kitos skriver ændringerne forårsaget af en indlæsning fra FK Organisation til en
ændringslog og ændringsloggen gemmes for de seneste fem synkroniseringer, der
medførte ændringer.
Man kan i Organisationsmodulet slette og redigere en organisationsenhed, og man
kan slette eller flytte registreringer fra enhed til en anden.


BILLEDE 1 - FUNKTIONSOVERBLIK


**Forudsætninger - generelt**
Der er en række forudsætninger, der skal være på plads, før man kan tage
integrationen til FK Organisation i anvendelse.

*Oprydning i lokal administratorer*
Inden I tager funktionaliteten vedr. integration til FK Organisation i brug, bør I
foretage en oprydning i adgange.
Flere kommuner har givet flere/mange brugere Lokal administrator adgang, og I skal
være opmærksom på, at funktionaliteten vedr. FK Organisation kan benyttes af alle
brugere, der har en Lokal administrator adgang – så en kritisk gennemgang af, om
det er de rette brugere, der har den adgang er en god ide.

*Data i FK Organisation*
• I skal have kontakt til de parter i jeres kommune, der vedligeholder data om
organisationen i FK Organisation
• Den organisationsstruktur, som man ser i FK Organisation, skal svare til det
man ønsker at vise i Kitos
• CVR nr. der anvendes i FK Organisation skal være det samme CVR nr., der er
registreret i Kitos

*Serviceaftale*
• Kommunen skal bede OS2kitos sekretariatet om at få tilsendt en serviceaftale
fra STRONGMINDS, der giver Kitos adgang til FK Organisation. Denne skal
godkendes af kommunens FK Administration ansvarlige.

**Adgang til funktionaliteten – og test i Staging-miljøet**
Vi anbefaler, at I tester funktionaliteten af i Kitos’s test-miljø Staging
https://staging.Kitos.dk, så I bliver fortrolige med det, inden I begynder i
produktionsmiljøet.
Datagrundlaget i Staging afviger typisk fra datagrundlaget i produktion. Så kontakt
eventuelt kommunens ansvarlige for FK Organisation for information om standen af
jeres data i FK Organisation i Staging-miljøet. I skal også sikre jer, at CVR nr i FK
Organisation også er det CVR nr., der er registreret i Kitos.
Hvis I ikke allerede har en serviceaftale til Staging-miljøet, skal I kontakte
Sekretariatet for at få det.
Når I er klar, kan I få adgang til funktionaliteten ved at:
• Logge på som Lokal Administrator i Kitos
• I kan dernæst tilgå konfigurationssiden ved at navigere til:
– Menuen ”Lokal Admin”
– Underpunktet ”Masse opret”
– Sektionen ”FK Organisation”
Hvis I ikke har registreret samme CVR nr. i Kitos, som der er i FK Organisation – eller
der intet CVR nr. er i Kitos, vil I se følgende skærmbillede:
Hvis I ikke har en godkendt serviceaftale, vil I se følgende skærmbillede:

BILLEDE 2 !!!!!

Hvis alt er som det skal være – CVR nr. OK og der er en godkendt serviceaftale - kan
I se følgende skærmbillede, og I har nu mulighed for at forbinde Kitos til FK
Organisation:

BILLEDE 3 !!!!!

**Aktivering af funktionen i produktionsmiljøet**
Efter I evt. har testet funktionaliteten af i Kitos’s testmiljø og er blevet fortrolige med
den, kan I aktivere funktionaliteten i Produktionsmiljøet på samme måde som i
Staging-miljøet ved at:
• Logge på som Lokal Administrator i Kitos
• I kan hernæst tilgå konfigurationssiden ved at navigere til:
– Menuen ”Lokal Admin”
– Underpunktet ”Masse opret”
– Sektionen ”FK Organisation”
• Sørg for at I har en godkendt serviceaftale – så samme måde som i Staging-
miljøet som beskrevet ovenfor
• Start evt. med ”Manuel” synkronisering (afhænger af behovet for kontrol) – se
mere om Synkronisering nedenfor.
• Efter første synkronisering, kan ”flyttearbejdet” påbegyndes dvs.
8
– Registreringer kan flyttes fra de eksisterende Kitos-enheder til de
synkroniserede enheder.
– Nedlæg Kitos-enheder, når der ikke længere er registreringer på dem
Se mere om dette i afsnittet vedr. Vedligehold af organisationen i Kitos.

**Synkronisering med FK Organisation**

*Synkroniseringsmetode*
Synkronisering med og indlæsning fra FK Organisation er en manuel proces, hvor
Lokal Administrator skal gennemse konsekvenser for organisationen i Kitos på
baggrund af opdateringer i FK Organisation. Og først når Lokal Administrator har
godkendt opdateringerne, vil indlæsning af data fra FK Organisation ske.
Tjek af hvorvidt der er sket opdatering i FK Organisation kan imidlertid ske på 2
forskellige måder – manuelt eller automatisk. Det vil sige, at det er tjek for
opdateringer i FK Organisation, der sker automatisk – det er ikke selve
synkronisering/indlæsning af data fra FK Organisation. Indlæsning af data sker som
ovenfor nævnt som en manuel proces, der kræver godkendelse af Lokal
Administrator.

Manuelt tjek af opdateringer i FK Organisation:
Her skal Lokal Administrator tjekke for opdateringer på siden for Masse
Opret, hver gang det ønskes.
Derved vil Lokal Administrator kunne godkende eller afvise eventuelle
konsekvenser, som opdateringer fra FK Organisation vil have i Kitos, før
der sker en indlæsning fra FK Organisation. Se mere om godkendelse
under afsnittet Ændringsloggen.

Automatisk tjek af opdateringer i FK Organisation:
Vælger man at benytte det automatiske tjek, vil Kitos hver mandag
(natten til tirsdag) tjekke om der er opdateringer i Når man vælger at
benytte den automatiske synkronisering, vil Kitos hver mandag (natten til
tirsdag) tjekke, om der er opdatering affødt af ændringer i FK
Organisation.
Såfremt der er ændringer i FK Organisation, vil Kitos sende en mail til alle
de brugere, der er lokal administratorer med information om, at der er
opdateringer i FK Organisation, som de skal handle på.
Mail fra Kitos ser således ud med eksempel på data fra Ballerup
kommune:
9
Klikker man på linket i mailen, lander man i Kitos, hvor man så klikker på
Rediger knappen:

BILLEDE 4 !!!!!

Derefter klikker man på Opdater knappen:

BILLEDE 5 !!!!!

Herefter vil man få vist de opdateringer der er, og kan vælge om man vil
enten godkende eller afvise opdateringer, inden der eventuelt indlæses fra
FK Organisation. – Altså den samme manuelle godkendelsesprocedure,
hvor man går ændringsloggen igennem og kan godkende ændringerne
inden indlæsning fra FK Organisation. – Se mere om dette i afsnittet
Ændringsloggen.

*Synkronisering - niveauer*
• I kan aktivt vælge om Kitos skal synkronisere hele organisationshierarkiet eller
kun en delmængde. I eksemplet nedenfor vises henholdsvis 1 niveau og 2
niveauer.

BILLEDE 6 !!!!!

• I Kitos under
– Menuen ”Lokal Admin”
– Underpunktet ”Masse opret”
– Sektionen ”FK Organisation”
- Knappen ”Forbind”
  
kan I vælge synkroniseringsniveau og om der skal ske automatisk tjek efter ventede
opdateringer fra FK Organisation:

BILLEDE 7!!!

Feltet ”Niveauer” – her vælges niveauer, der synkroniseres. Er feltet tomt,
synkroniseres hele hierarkiet.
Feltet ”Automatik” – her aktiveres automatisk tjek for opdateringer fra FK
Organisation.
Under "Forhåndsvisning” – her vises hierarkiet i FK Organisation filtreret ift. det valgte
antal niveauer, så man kan vurdere om synkroniseringsdybden er korrekt.
Her ses et eksempel på, at man har valgt synkronisering af 2 niveauer og fravalgt
automatisk tjek efter ventende opdateringer:

BILLEDE 8!!!!

Gennemfører man synkroniseringen, se man følgende billede:
BILLEDE 9!!!!

Klikker man i firkanten ved Ændringslog, kan folde ændringsloggen ud og se, hvilke
opdateringer der er sket.

*Ændringsloggen*
Kitos skriver ændringerne til ændringsloggen og ændringsloggen gemmes for de
seneste fem synkroniseringer, der medførte ændringer. (Ændrings-tjeks, som ikke
registrerer ændringer, medfører altså ikke ”tomme” rækker i ændringsloggen.)
I ændringsloggen kan man se, hvilke organisationsenheder der bliver tilføjet, slettet,
omdøbt, flyttet etc. i forhold til, hvordan organisationen ser ud i Kitos.
Man har mulighed for at afbryde importen fra FK Organisation, hvis man ikke vil
godkende ændringerne via knappen Afvis ændringer.
Hvis man accepterer ændringer – knappen Godkend ændringer - gennemføres
importen fra FK Organisation.
Se eksempel på ændringslog, hvor man kan godkende eller afvise ændringerne, der
kommer fra synkroniseringen med FK Organisation:

BILLEDE 9 !!!!

*Synkronisering – enhedstyper*
I forbindelse med introduktionen af FK Organisation, vil Kitos fremover skelne mellem
to forskellige enhedstyper i organisationshierarkiet.
• Kitos Enheder: Disse enheder er fuldt administrerbare af Lokal Administrator i
Kitos. Der kan altså rettes i både navn, ean, enhed id samt overordnet
enhed. Man kan også slette dem.
• Enheder synkroniseret fra FK Organisation: Disse enheder er delvist
administrerbare af Lokal Administrator i Kitos. For disse enheder kan man
ændre ean og enhed id.
15
– Navn og overordnet enhed synkroniseres fra FK Organisation, og derfor
er det altså ikke muligt at redigere dette via brugerfladen. Af samme
årsag kan man heller ikke slette dem via brugerfladen, men kun ved at
afbryde forbindelsen til FK Organisation eller ved at ændre på niveauerne
der synkroniseres.

BILLEDE 10!!!!!!

*Synkronisering – konsekvenser*
Når Lokal Administrator har godkendt ændringer fra FK Organisation, vil Kitos hente
organisationen ud fra FK Organisation.
Sammenholdt med det billede af organisationen, der allerede findes i Kitos, vil Kitos
nu forholde sig til følgende:
 Enheder, der er blevet oprettet i FK Organisation -> såfremt disse er oprettet
inden for den valgte synkroniseringsdybde, vil de blive oprettet i Kitos
 Enheder, der har skiftet navn -> disse omdøbes automatisk i Kitos
 Enheder, der er flyttet -> såfremt disse er flyttet inden for den valgte
synkroniseringsdybde, vil de blive flyttet.
16
Fx hvis de er flyttet ned i synkroniseringsniveau 4 og man kun har valgt 3
synkroniseringsniveauer, vil de altså set fra Kitos’s side være slettet. I så fald
sker der det samme som for egentligt nedlagte enheder (se neden for)
 Enheder, der er slettet – eller flyttet uden for synkroniseringsdybden
o Hvis der ikke er registreringer (fx Ansvarlighed enhed på en Kontrakt),
vil enheden blive slettet
o Hvis der er registrering(er) på enheden, vil enheden blive konverteret til
en Kitos enhed – altså en enhed, der ikke længere synkroniseres fra FK
Organisation. Og man har mulighed for evt. at flytte registreringer fra
enheden og evt. manuelt nedlægge den efterfølgende.

**Vedligehold af organisationen i Kitos**
Hvis kommunen tilslutter Kitos til FK Organisation ændres arbejdsgangen for
organisationshierarkiet.
• Vedligehold af organisationshierarkiet foretages i FK Organisation (eller det
system der føder data hertil)
• Vedligeholdelse af Kitos registreringer, tilknyttet enheder i organisationen,
foretages stadig i Kitos.
• Det er nu muligt at ”flytte” registreringer fra én enhed til en anden direkte fra
organisationsmodulet.
– Denne funktion er tilgængelig, uanset om kommunen har tilsluttet Kitos
til FK Organisation eller ej
– Særligt efter en synkronisering der har medført ”konvertering til Kitos-
enhed” giver denne funktionalitet nem adgang til hurtigt at kunne
omregistrere fra og nedlægge den gamle (konverterede) enhed.

*Flytning af organisationsenheder*
I organisationsmodulet i Kitos kan man redigere kommunens organisationshierarki.
Her er det muligt at flytte enheder, der er oprettet i Kitos, men man kan ikke flytte
enheder, der er synkroniseret fra FK Organisation.
De enheder, der er oprettet i Kitos er blå, mens enheder, der er synkroniseret fra FK
Organisation er grønne:

BILLEDE 11!!!!

Vil du flytte en enhed oprettet i Kitos, trykker du på Omstrukturer og kan derefter
flytte rundt på enheden. Når du er færdig med omstruktureringen, trykker du på
Færdig.

*Redigering og sletning af organisationsenheder*
I Organisationsmodulet kan man slette organisationsenheder, der er oprettet i Kitos (
blå enheder), men man kan ikke slette organisationsenheder (grønne enheder), der er
synkroniseret fra FK Organisation.
Sletning af en enheden sker ved, at man stiller sig på enheden, trykker dernæst på
Rediger. Så får man følgende billede:

BILLEDE 12!!!!

Herfra kan man så slette enheden.
Det er også i dette skærmbillede, at man kan redigere en enhed. Man kan både
redigere en Kitos enhed (blå) samt organisationsenheder (grønne), der er
synkroniseret fra FK Organisation. Der er dog forskel på, hvor meget man kan
redigere de 2 typer enheder.
For en Kitos enhed (blå) kan man redigere følgende data:
 overordnet enhed, enhedens navn, EAN nummer samt enhed ID.

BILLEDE 13!!!!

I feltet ”Overordnet enhed” kan man med den lille pil i højre side folde
organisationshierarkiet ud og med farvemarkering se, om der er tale om en Kitos
enhed (blå) eller en enhed fra FK Organisation (grøn). På den måde bliver det
nemmere at vælge en anden overordnet enhed.
Farvemarkeringen vil dog kun være aktiv såfremt man har begge typer enheder i
organisationshierarkiet, så man derfor har brug for at kunne skelne.
For en enhed synkroniseret fra FK Organisation (grøn) kan man redigere følgende
data:
 EAN nummer samt enhed ID (felterne overordnet enhed samt enhedens navn
vil være grå og ikke rediger-bare).

BILLEDE 14!!!!

*Oprettelse af underenhed*
Det er også muligt at oprette en underenhed for både en Kitos enhed (blå) samt en
enhed synkroniseret fra FK Organisation (grøn). Igen sker det under Rediger:

BILLEDE 15!!

Og herefter kan man indtaste data for den nye underenhed:

BILLEDE 16!

*Flytning af registreringer fra en organisationsenhed*
I forbindelse med redigering af organisationshierarkiet kan man flytte registreringer
fra en enhed til en anden, uafhængig af om det er en Kitos enhed eller en enhed
synkroniseret fra FK Organisation.
Det foregår i Rediger:

BILLEDE 17!!!

Her kan man ved den lille firkant udfor Registreringer folde registreringerne ud, så
man får vist de registreringer, der er gjort i Kitos for den pågældende
organisationsenhed. De systemer og/eller kontrakter der er registreringer på, kan
man navigere til, da det er aktive links:

BILLEDE 18 !!!!

Her har man så mulighed for at vælge enkelte eller alle registreringer ved at sætte
hak samt vælge hvilken organisationsenhed den eller de registreringer skal overføres
til.
I feltet Overfør til kan man trykke på den lille pil i højre side, og med farvekoder få
vist om enheden er en Kitos enhed (blå) eller en enhed synkroniseret fra FK
Organisation (grøn) – og igen – farvekoden aktiveres kun, såfremt begge enhedstyper
findes i hierarkiet:

BILLEDE 19!!!

*Sletning af registreringer fra en organisationsenhed*
I forbindelse med redigering af organisationshierarkiet kan man slette registreringer
fra en enhed, uafhængig af om det er en Kitos enhed (blå) eller en enhed
synkroniseret fra FK Organisation (grøn).
Det foregår i Rediger:

BILLEDE 20!!!!

Her kan man ved den lille firkant udfor Registreringer, folde registreringerne ud, så
man får vist de registreringer, der er gjort i Kitos for den pågældende
organisationsenhed:

BILLEDE 21!!!

Her har man så mulighed for at vælge enkelte eller alle registreringer ved at sætte
hak samt trykke på Slet valgte.

*At bryde forbindelsen til FK Organisation*
I forbindelse med synkronisering af hierarkiet fra FK Organisation, kan det tænkes at
hierarkiet fra FK Organisation ikke er velegnet til brug i Kitos. Lokal Administrator har
derfor mulighed for at bryde forbindelsen til FK Organisation og dermed konvertere
hele hierarkiet til “Kitos enheder”. Derved vil Lokal administrator frit kunne vælge den
del af hierarkiet, der skal bestå og evt. navngive det, så det er mere passende i en
Kitos kontekst.

BILLEDE 22!!!!

Når man vælger at bryde forbindelsen til FK Organisation, vil alle enheder, man har
importeret fra FK Organisation blive konverteret til Kitos enheder.
Hvis man senere genopretter forbindelse til FK Organisation, vil der således kunne
være enheder med samme navn – henholdsvis Kitos enheder og enheder
synkroniseret fra FK Organisation.
Der er derfor 2 forskellige muligheder:
 Du kan vælge at få slettet alle organisationsenheder, der er synkroniseret fra
FK Organisation og hvor der ikke er tilknyttet en registrering. De resterende
organisationsenheder konverteres til Kitos enheder.
 Du kan vælge at bevare organisationshierarkiet fra FK Organisation – uanset
om der er registreringer på enheden eller ej – så konverteres alle enheder til
Kitos enheder.
Når du trykker på knappen ”Bryd forbindelsen til FK Organisation”, vil du blive
præsenteret for de 2 valgmuligheder, og du kan her se eksempel på udfaldet.

BILLEDE 23!!!!!

På eksemplet ovenfor er der altså ikke lavet nogen registreringer på de enheder, der
er underordnet til enheden ”Ballerup kommune”, hvorfor de vil forsvinde, hvis man
vælge muligheden med at slette ubrugte organisationsenheder.

*Hvis forbindelsen til FK Organisation fejler*
Man skal ikke være nervøs for, at der sker noget med den organisationen i Kitos,
såfremt der måtte ske en afbrydelse af forbindelsen til FK Organisation.
Hvis forbindelsen til FK Organisation fejler, så fejler import processen også. Kitos
indlæser hele organisationen fra FK Organisation, inden den filtreres og synkroniseres.
Derfor vil en forbindelsesfejl til FK Organisation altså ikke kunne få hierarkiet i Kitos til
at gå i stykker.
STRONGMINDS vil i stedet få en fejlmelding i loggen om, at importprocessen er gået i
stykker, og vil se på, om fejlen ligger på Kitos’s side eller hos FK Organisation.

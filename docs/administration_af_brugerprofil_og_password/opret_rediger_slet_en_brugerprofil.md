---
title: Opret, rediger, slet en brugerprofil
nav_order: 1
parent: Administration af brugerprofil og password
---
Vejledning til hvordan du kan oprette, redigere og slette en brugerprofil.


# Opret, rediger, slet en brugerprofil - 27.03.25

## Baggrund

For at kunne benytte Kitos, skal man som bruger være oprettet med en brugerprofil.

Som kommune kan man vælge at oprette brugerprofiler på to forskellige måder:

(1) Via FK Adgangsstyring kan kommunens lokale brugeradministrator tildele medarbejdere rollen
'Kitos kigge adgang'. Med denne rolle kan brugeren logge på Kitos via SSO. Kitos Lokal admin
skal kun inddrages, hvis brugeren skal have tildelt flere rettigheder og dermed en rolle ekstra i
Kitos.

(2) Kitos Lokal admin kan oprette brugere direkte i Kitos, tildele dem den relevante rolle samt
brugernavn og password, som anvendes ved log ind.

Det er alene oprettelse af nye brugere, der er forskellig, - redigering og sletning af en brugerprofil
vil være identisk uanset om kommunen benyttet SSO via FK Adgangsstyring eller ej.

# (1) Opret ny bruger - med brug af SSO

I FK Adgangsstyring er der etableret en brugersystemrolle, der hedder 'kitos-kigge-adgang'.
Medarbejdere, der har fået tildelt denne rolle af deres lokale brugeradministrator, kan få adgang til
at se data i Kitos via deres almindelige kommune profil.

Brugerne vil typisk ikke aktivt få besked om, at de har fået tildelt rollen 'kitos-kigge-adgang'. De
vil blot opleve, at hvis de tilgår Kitos.dk, kan de klikke på 'Login via fælleskommunal
adgangsstyring' og få direkte adgang til Kitos.

## Hvis brugeren har været logget ind i Kitos med brug af SSO

Hvis brugeren har været logget på Kitos, er brugerens navn, kontaktoplysninger og organisatoriske
tilhørsforhold automatisk blevet registeret i Kitos. Dette betyder, at Kitos Lokal admin ikke behøver
at registrere disse oplysninger i Kitos.

Hvis brugeren har behov for at kunne redigere eller oprette data i Kitos, kan Lokal admin nøjes med
at tildele den relevante rolle til medarbejderen, der altså allerede er oprettet i Kitos. - Dette gøres
ved at følge vejledningen vedr. at redigere en brugers profil længere nede i dette dokument.

## Hvis brugeren ikke har været logget ind i Kitos med brug af SSO

Hvis ikke brugeren har været logget ind i Kitos med brug af SSO med FK adgangsstyring, er der
ikke sket den automatiske oprettelse af brugerens navn, kontaktoplysninger og organisatoriske
tilhørsforhold.

Kitos Lokal admin skal derfor selv oprette brugeren og dette gøres som beskrevet under "Opret ny
bruger - uden brug af SSO". Alternativt kan Kitos Lokal admin bede brugeren om at logge på
Kitos, så oplysningerne automatisk bliver registreret.

# (2) Opret ny bruger og tildel brugernavn og password

· Klik på modulet Organisation  
· Klik på underpunktet Brugere  
· Klik på +Opret bruger øverst til højre  

https://github.com/os2kitos/kitos_docs/blob/main/assets/opret%20bruger%201.png

# Du får nu en pop-up, hvor du kan indtaste oplysninger om brugeren:

https://github.com/os2kitos/kitos_docs/blob/main/assets/opret%20bruger%202.png


· Udfyld felterne: E-mail-adresse, Fornavn, Efternavn og Telefon  
· Hvis brugeren skal tildeles administrator rettighed til et eller flere moduler skal du angive,
hvilke moduler der skal gives rettighed til under Roller  
· Du kan også angive, hvilken primær startenhed, brugeren skal møde, når vedkommende
logger på Kitos. Brugeren kan dog også selv opdatere dette under "Min Profil"  
· Klik på knappen Opret bruger og "send advis om ændringer" (så modtager brugeren en e-
mail med logon-oplysninger)  

Hvis brugeren først skal have adgang til Kitos på et senere tidspunkt, skal du kun klikke på Opret
bruger. Så kan du på et senere tidspunkt sende en advis med logon-oplysninger ved at klikke på
"Send advis om ændringer"-knappen fra brugeroversigten.

# Rediger en brugers profil - uanset hvordan brugeren er oprettet

· Klik på modulet Organisation  
· Klik på underpunktet Brugere  
· Klik på Rediger yderst til højre for brugerens navn  

## Du får nu en pop-up med brugerens oplysninger, som du kan redigere i.

· Foretag ændringer  
· Klik på Gem ændringer  
https://github.com/os2kitos/kitos_docs/blob/main/assets/opret%20bruger%203.png


# Slet en brugers profil - uanset hvordan brugeren er oprettet

· Klik på modulet Organisation  
· Klik på underpunktet Brugere  
· Klik på Slet yderst til højre for brugerens navn  

## Du får nu en pop-up med brugerens oplysninger.

<img width="2551" height="906" alt="slet bruger 1" src="https://github.com/user-attachments/assets/15817c73-111d-464b-a3c7-5885b84b60cb" />


Ønsker du at slette brugerens profil fra Kitos, skal du klikke på "Slet bruger".

Når du har slettet en bruger fra Kitos, vil de registreringer, som brugeren har lavet, fremstå med
information om, at brugeren er slettet, og det er ikke muligt at finde information om den slettede
bruger i Kitos. Hvis brugeren har roller i et modul, vil disse ligeledes blive fjernet.

Undtagen er dog, hvis brugeren er Kontraktunderskriver (feltet Kontraktunderskriver i fanen
Kontraktforside i Kontraktmodulet) - da vil man fortsat kunne se brugerens navn.

Se dette eksempel hvor den bruger, der i sin tid har taget disse 2 systemer i anvendelse, siden hen er
blevet slettet:

**[INDSÆT TABEL HER: Eksempel på slettet bruger i systemoversigt]**

# Overføre en brugers roller inden sletning

Ønsker du at overføre en brugers roller til en anden, inden du sletter brugeren, kan du øverst vælge
hvem rollerne skal overføres til, herefter markere de ønskede roller og klikke på "Tildel valgte
roller".

**[INDSÆT BILLEDE HER: Skærmbillede af overfør roller-popup]**

# Rediger en bruger

Hvis man klikker på en bruger, åbner der sig en pop up med en oversigt over brugernes
registreringer i Kitos.

Herfra har du muligheder for at redigere en bruger, slette en bruger eller kopiere en brugers roller til
en anden.

**[INDSÆT BILLEDE HER: Skærmbillede af brugerens roller og rettigheder]**

Hvis man klikker på "rediger" får du mulighed for at ændre i en brugers stamoplysninger, roller og
rettigheder.

**[INDSÆT BILLEDE HER: Skærmbillede af rediger stamoplysninger]**

Hvis man klikker på "kopier roller" får du mulighed for at kopiere en brugers roller
til en anden bruger, uden at slette eksisterende brugere.

**[INDSÆT BILLEDE HER: Skærmbillede af kopier roller-popup]**

# Slet udvalgte roller

Hvis brugeren har roller tilknyttet, kan du slette udvalgte roller ved at markere dem og klikke på
Slet valgte roller.

**[INDSÆT BILLEDE HER: Skærmbillede af slet roller-popup]**

Hvis en bruger har roller i Kitos, kan du før du sletter, overdrage dem til en eller flere andre
personer i organisationen - se vejledningen Masseadministration af en brugers roller.

# Lidt om Roller

Alle brugere med en tilknyttet rolle som har SKRIV adgang, kan oprette indhold og redigere/slette
data under det system/kontrakt/databehandleraftale som rollen er tilknyttet til.

Hvis brugeren skal kunne redigere alt data på tværs af et helt modul, f.eks på alle SYSTEMER, skal
du give brugeren administratorrettighed: System admin.

**Roller og rettigheder:**

- **API adgang**: Kun tildeles af sekretariatet  
- **Rettighedshaver Adgang**: Kun tild

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

(2) Kitos Lokal admin kan manuelt oprette brugere direkte i Kitos, tildele dem den relevante rolle samt
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

# (2) Opret ny bruger manuelt og tildel brugernavn og password

· Klik på modulet Organisation  
· Klik på underpunktet Brugere  
· Klik på +Opret bruger øverst til højre  

<img width="2562" height="468" alt="opret bruger 1" src="https://github.com/user-attachments/assets/13d5cad0-4160-4131-98d4-3b9198e0ca66" />


# Du får nu en pop-up, hvor du kan indtaste oplysninger om brugeren:

<img width="2516" height="1185" alt="opret bruger 2" src="https://github.com/user-attachments/assets/6a71c0c4-8e3d-4a35-aa2e-b063412fe922" />


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
· Klik på "rediger" ikon yderst til højre for brugerens navn  

## Du får nu en pop-up med brugerens oplysninger, som du kan redigere i.

· Foretag ændringer  
· Klik på Gem ændringer  

<img width="2537" height="1138" alt="opret bruger 3" src="https://github.com/user-attachments/assets/a9b172e2-ef9c-4b00-9ee2-d005cd90633b" />


# Slet en brugers profil - uanset hvordan brugeren er oprettet

· Klik på modulet Organisation  
· Klik på underpunktet Brugere  
· Klik på "slet" ikon yderst til højre for brugerens navn  

## Du får nu en pop-up med brugerens oplysninger.

<img width="2557" height="889" alt="slet bruger 0" src="https://github.com/user-attachments/assets/da36ea09-4eba-4167-8be4-90fb33df888f" />


Ønsker du at slette brugerens profil fra Kitos, skal du klikke på "Slet bruger".
Ønsker du først at overføre brugernes rolle registreringer til en anden bruger, skal du trykke på "overfør roller".

Når du har slettet en bruger fra Kitos, vil de registreringer, som brugeren har lavet, fremstå med
information om, at brugeren er slettet, og det er ikke muligt at finde information om den slettede
bruger i Kitos. Hvis brugeren har roller i et modul, vil disse ligeledes blive fjernet.

Undtagen er dog, hvis brugeren er Kontraktunderskriver (feltet Kontraktunderskriver i fanen
Kontraktforside i Kontraktmodulet) - da vil man fortsat kunne se brugerens navn.

Se dette eksempel hvor den bruger, der i sin tid har taget disse 2 systemer i anvendelse, siden hen er
blevet slettet:

<img width="1713" height="242" alt="slettet bruger " src="https://github.com/user-attachments/assets/1df043a3-fada-4638-aa29-74e5718a0e90" />


# Overføre en brugers roller inden sletning

Ønsker du at overføre en brugers roller til en anden, inden du sletter brugeren, skal du klikke på "overfør roller" - Se det forrige skærmbillede som popper op når du trykker "slet" ved en bruger.
Her kan du øverst vælge hvem rollerne skal overføres til, herefter markere de ønskede roller og klikke på "Tildel valgte roller". Brugeren som rollerne overføres fra, afgiver hermed de valgte rollere til den nye bruger.

<img width="2554" height="1151" alt="overfør roller 1" src="https://github.com/user-attachments/assets/f1ffa1df-c09c-4f02-879d-f6816db4d67a" />


# Rediger en bruger

Hvis man klikker på en bruger, åbner der sig en pop up med en oversigt over brugernes
registreringer i Kitos.

Herfra har du muligheder for at redigere en bruger, slette udvalgte roller, sende nyt password til  brugeren ved at trykke "Send advis", eller slette en bruger.

<img width="2529" height="1154" alt="rediger bruger" src="https://github.com/user-attachments/assets/a31dbd94-cbd6-4f9e-ac2e-163feb05bb36" />


Hvis man klikker på "rediger" får du mulighed for at ændre i en brugers stamoplysninger, roller og
rettigheder, samt kopiere brugerens roller til en anden - Nyttigt ved vikar eller elever.

<img width="2543" height="1179" alt="rediger bruger 2" src="https://github.com/user-attachments/assets/58f1c609-7e1d-47c1-b3ac-04f5d74be25b" />

Hvis man under "rediger" klikker på "kopier roller" får du mulighed for at kopiere en brugers roller
til en anden bruger, uden at slette eksisterende brugere eller selv afgive rollerne.

<img width="2553" height="1192" alt="kopier roller" src="https://github.com/user-attachments/assets/49c90186-681d-43d7-92c9-727cde2ae9dd" />

# Slet udvalgte roller

Hvis brugeren har roller tilknyttet, kan du slette udvalgte roller ved at markere dem og klikke på
Slet valgte roller.

<img width="2541" height="1172" alt="slet udvalgte roller" src="https://github.com/user-attachments/assets/be7fe963-b2bc-4c96-a59a-011546b9bbcc" />

Hvis en bruger har roller i Kitos, kan du før du sletter brugeren, overdrage dem til en eller flere andre
personer i organisationen - se længere oppe i vejledningen eller vejledningen "Masseadministration af en brugers roller".

# Lidt om Roller

Alle brugere med en tilknyttet forretningsrolle som har SKRIV adgang, kan oprette indhold og redigere/slette
data under det system/kontrakt/databehandleraftale som rollen er tilknyttet til.

Hvis brugeren skal kunne redigere alt data på tværs af et helt modul, f.eks på alle SYSTEMER, skal
du give brugeren administratorrettighed: System admin.

**Roller og rettigheder:**

- **API adgang**: Kan kun tildeles af OS2Kitos sekretariatet  
- **Rettighedshaver Adgang**: Kan kun tildeles af OS2Kitos sekretariatet

Læs mere i vejledningerne under "Roller og rettigheder"

---
title: FK brugeradministration
layout: default
nav_order: 1
parent: FK adgangsstyring og SSO
---

Vejledninger til brugeradmninistration via Fælles kommunal adgangsstyring


# SSO med Fælleskommunal adgangsstyring – 14.07.23

## Baggrund
Det er blevet meget lettere at give en bred skare af medarbejdere fra kommunen adgang til at kigge
med i OS2Kitos.
I FK Adgangsstyring er der etableret en brugersystemrolle, der hedder **’kitos-kigge-adgang’**.
Medarbejdere, der har fået tildelt denne rolle af deres lokale brugeradministrator, kan få adgang til
at se data i Kitos via deres almindelige kommune profil. Hvis medarbejdere skal have adgang til at
rette eller skabe data i Kitos, skal Kitos Lokal Admin fortsat i Kitos-løsningen tildele rettigheder
hertil.

## Forudsætninger
Forudsætningerne for at kunne benytte SSO via FK adgangsstyring er at:
- Kommunen har godkendt serviceaftale, de modtager fra STRONGMINDS - har I ikke allerede
fået en serviceaftale fra STRONGMINDS, så kontakt Kitos-sekretariatet, så sørger vi for, at
STRONGMINDS sende en til jer. Bemærk også, at det er STROMGMINDS, der står som afsender
af serviceaftalen i FK.
- Brugeren har fået jobfunktionsrollen
- Brugeren skal være i FK Organisation

## Nye medarbejdere på Kitos
Det kan være relevant for mange forskellige medarbejdergrupper i kommunen lige at kunne
foretage et opslag i Kitos. Der kan f.eks. være behov for hurtigt at kunne tjekke, hvem der er
systemejer for et it-system eller se hvorvidt der er udarbejdet en databehandleraftale for et konkret
system.
Det er forskelligt fra kommune til kommune, hvordan man i praksis tildeler medarbejdere
FK rettigheder. I må derfor forhøre jer nærmere hos jeres egen brugeradministrator omkring den
konkrete opsætning. I Ballerup Kommune (og sikkert også i mange andre kommuner) kan vi tildele
’kitos-kigge-adgang’ til konkrete navngivne medarbejdere, til organisatoriske enheder, teams eller
til alle medarbejdere i kommunen. Hvis I tildeler rollen til overordnede organisatoriske enheder,
kan I slippe for en masse besvær med at administrere den enkelte medarbejders adgang til Kitos.
Brugerne vil typisk ikke aktivt få besked om, at de har fået tildelt rollen ’kitos-kigge-adgang’. De
vil blot opleve, at hvis de på Kitos.dk klikker på ’Log ind via Fælleskommunal adgangsstyring", vil
de få direkte adgang til Kitos.
Når brugerne logger ind i Kitos vil deres navn, kontaktoplysninger og organisatoriske tilhørsforhold
blive registeret. Dette betyder, at Kitos Lokal admin ikke behøver at registrere disse oplysninger i
Kitos. Hvis en medarbejder har behov for at kunne redigere eller oprette data i Kitos, kan Lokal
admin nøjes med at tildele den relevante rolle til medarbejderen, der allerede er oprettet i Kitos. På
Sidst ændret – 13.06.25 - MIOL
den måde bliver Lokal Admin aflastet uden at miste overblik over, hvilke brugere der har yderligere
beføjelser i Kitos.

## Nuværende brugere af Kitos
Nuværende brugere af Kitos har ikke fået tildelt FK brugersystemrollen ’kitos-kigge-adgang’. De
kan derfor ikke umiddelbart anvende log ind via SSO. Hvis de forsøger, vil de blive mødt med en
besked om, at de ikke har de nødvendige rettigheder til at se Kitos.dk. Hvis de anvender det
sædvanlige log ind via brugernavn og password, vil de ikke opleve nogen forandring.
I skal derfor sørge for, at de nuværende Kitos brugere får tildelt brugersystemrollen ’kitos-kigge-
adgang’ før SSO med FK adgangsstyring virker for dem. FK rollen ’kitos-kigge-adgang’ er et
supplement til brugerstyringen i Kitos.dk. Har brugeren fået tildelt yderligere roller i Kitos, vil disse
fortsat være gældende.

## Hjælp til FK brugeradministrator
Som en ekstra service er der udarbejdet et dokument - "FK Brugeradministration - supplement til
SSO vejledning" - der skal ses som et supplement med et par skærmbilleder fra FK. Denne skal
ikke ses som en egentlig vejledning til FK- eller brugeradministratorer, men vi håber selvfølgelig,
den kan være til hjælp.

## Kan der opstå dubletter af samme bruger?
Mailadressen er nøglen ved SSO-login – Dvs. hvis en bruger allerede er manuelt oprettet i Kitos
med samme mailadresse som er knyttet til brugerens SSO, så vil brugeren ikke blive oprettet igen.
Omvendt hvis brugeren allerede er oprettet i Kitos og samme bruger logger på via SSO, hvor der er
en anden mailadresse knyttet til, så oprettes brugeren med en ny separat konto i Kitos.

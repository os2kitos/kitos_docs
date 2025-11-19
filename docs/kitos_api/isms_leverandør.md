---
title: ISMS Leverandør
layout: default
nav_order: 4 
parent: Kitos Api
---


Vejledning til funktionen ISMS Leverandør i Lokal Admin menuen.


# 03.11.25 – Kitos PO: miol@balk.dk

## Indhold
1. [ISMS-Leverandører i Kitos](#isms-leverandører-i-kitos)
    - [Supplier begrebet](#supplier-begrebet)
    - [Udvalgte felter der kan modtages data på pr-031125](#udvalgte-felter-der-kan-modtages-data-på-pr. 031125)
2. [Vejledning](#vejledning)
    - Hvad skal jeres ISMS-Leverandør gøre?

---

## 1. ISMS-Leverandører i Kitos

### 1.1 Supplier begrebet
Der er i Kitos indført et nyt **”Supplier”** begreb, som kan give rettigheder til en udvalgt ISMS-leverandør til at være *master* på udvalgte felter i Kitos.  
Dette betyder, at en Kitos-kommune kan vælge at modtage data fra sin ISMS-leverandør på udvalgte felter, som dermed bliver låst for redigering i Kitos.  

Denne funktionalitet kan bruges af alle kommuner sammen med alle leverandører, som er oprettet som organisation i Kitos.  
På sigt er visionen at videreudvikle funktionaliteten, så man som kommune selv kan udvælge specifikke felter.

---

### 1.2 Udvalgte felter der kan modtages data på pr. 03.11.25
Kommunerne har defineret en pulje af felter, som denne integration åbner op for, hvis man følger nedenstående flow.  
Man kan **ikke** udvælge specifikke felter – det er en pakkeløsning med alle felter eller ingen.

**Felter det omhandler:**
- **Databehandlermodul – Tilsynsfanen**
    - Gennemført tilsyn: ja/nej
   ilsyn: dato (dd.mm.åååå)
    - Bemærkninger til tilsyn
    - Link til tilsynsrapport *(nyt felt i Kitos)*
- **GDPR-fanen**
    - Forretningskritisk system (Kritikalitet) *(nyt felt i Kitos)*
    - Hvad viste seneste risikovurdering
- **Kitos system modul – Forsiden**
    - Benyttes der AI

---

## 2. Vejledning
Som **Kitos Lokal admin** skal du:
1. Gå i **”Lokal admin”** menuen.
2. Vælg **”ISMS-leverandør”**.
<img width="1902" height="700" alt="ISMS-supplier" src="https://github.com/user-attachments/assets/04842d29-1544-4ee3-ab25-10450467d087" />

   
4. Klik på den blå **+TILFØJ** knap og vælg din ISMS-Leverandør fra listen.  
   - Hvis din ISMS-Leverandør **ikke** er på listen, skal I skrive til info@kitos.dk, så vi kan tilføje leverandøren.
  
<img width="1915" height="853" alt="ISMS-Supplier - 2" src="https://github.com/user-attachments/assets/56ea4a48-0c7d-4ddf-be65-1cdb8569be9c" />


Når I vælger en leverandør, vises et overblik over hvilke felter der gøres inaktive i Kitos og dermed styres af den valgte leverandør.  

Når leverandøren er tilføjet, vises de på listen herunder. Det denne tilladelse til at skrive ind i de udvalgte – nu låste – felter.

---

### Sletning eller afbrydelse af integration
Det er også her, man sletter/afbryder integrationen med leverandøren ved at trykke på **slet-ikonet (skraldespanden)**.

**Hvad sker der, når forbindelsen brydes og genetableres?**
- Hvis forbindelsen brydes, bevares data i Kitos, men felterne låses op og styres nu igen i Kitos.
- Vederes felter igen og styres nu af den udvalgte ISMS-Leverandør.

**Sådan ser et låst felt ud i Kitos:**  
*(indsæt evt. billede her)*

Sidste skridt er at kontakte jeres ISMS-Leverandør og fortælle, at I ønsker denne integration sat op.

---

## 2.1 Hvad skal jeres ISMS-Leverandør gøre?
- Sidste skridt er at kontakte jeres ISMS-Leverandør og fortælle, at I ønsker denne integration sat op.  
    - **Dokumentation til leverandør:**  
      [https://os2web.atlassian.net/wiki/spaces/KITOS/pages/3185967112/13.4.0](https://os2web.atlassian.net/wiki/spaces/KITOS/pages/3185967112/13.4.0)
- Jeres ISMS-Leverandør skal være oprettet som organisation i Kitos.  
    - Er de ikke oprettet, skal de henvende sig til Kitos sekretariatet og bede om oprettelse: info@kitos.dk
- ISMS-Leverandøren skal oprette en **API-Bruger** i sin organisation i Kitos.  
    - Det er denne API-bruger, som styrer integrationen for de kommuner, som har valgt den givne ISMS-leverandør i **LOKAL ADMIN-menuen**.

.

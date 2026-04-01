---
title: Wired Relations Q&A
layout: default
nav_order: 3
parent: Kitos Api
---
Herr kan du se en Q&A på Kitos datasamspil med ISMS systemet Wired Relations.
Denne opdateres løbende når der er ændringer, kontakt info@kitos.dk for opdateret samspil - Opdateret: 15-02.2025

# KITOS – Q&A

## Hvilke oplysninger importeres fra Kitos

Integrationen mellem Kitos og Wired Relations er en envejsintegration fra Kitos til Wired Relations.

De felter som i dag er låst i Wired Relations og trækkes over fra Kitos er følgende:

### Systemer

| Kitos                | Wired Relations         |
|----------------------|--------------------------|
| IT system            | System navn              |
| Beskrivelse          | Beskrivelse              |
| Systemforside        | Data fra IT Systemkataloget |
| Systemansvarlig ℹ    | Systemroller → Ansvarlig ⚠ |
| Systemejer ℹ         | Systemroller → Ejer ⚠     |
| Lokale referencer    | Vedhæftninger            |

### Leverandører

| Kitos                | Wired Relations         |
|----------------------|--------------------------|
| Leverandør           | Systemer → Kontrakter → Leverandør |
| Databehandler        | Databehandling → Forside → Databehandler |
| Kontraktejer         | Kontrakter → Kontraktroller → Kontraktejer |
| Ansvarlig person ⚠   |                          |

⚠ Personer kan kun synkroniseres fra Kitos til Wired Relations, såfremt de er oprettet som brugere i Wired Relations.  
ℹ Hvis flere personer er angivet som systemansvarlig eller systemejer i Kitos, vil kun den første (øverst i oversigten) blive overført til Wired Relations.  
🗒 Kun brugere med begrænset adgang og rollen som systemejer kan se systemer i Wired Relations.  
Systemansvarlige skal have standard-, superbruger- eller administrator-adgang for at se deres tildelte systemer.

---

## Hvordan sættes integrationen til Kitos op?

For at sætte integrationen op mellem KITOS og Wired Relations skal man bruge en API-bruger hos Kitos.

I kan vælge:

- At stå for opsætningen selv (vi sender en guide)
- At give os tilladelse til at kontakte Kitos Support på jeres vegne (vi har allerede en aktiv API-bruger)

Hvis vi skal stå for opsætningen:

- Opret vores Product Owner Karen som bruger med administrator-adgang i jeres system  
- Efter opsætning kan Karen slettes igen uden at det påvirker integrationen  
- Kontakt: `karen@wiredrelations.com`

Opsætningen kan tage op til to uger afhængig af KITOS’ svartid.

---

## Hvordan fungerer synkroniseringen?

Når integrationen er opsat:

- Gå til **Tandhjulet** øverst i højre hjørne → **Integrationer** → **Kitos**
- Tryk på knappen **"Import"** for at synkronisere indholdet

> Synkroniseringen sker **ikke automatisk** – I kan køre den så ofte I ønsker.
>
> <img width="1761" height="655" alt="wired 1" src="https://github.com/user-attachments/assets/91af4ae2-90c3-496d-891b-d4073c8bff1a" />


### Forslag til tilbagevendende opgave

**Titel:** Kitos import til Wired Relations  
**Ansvarlig:** Bruger med administrator-adgang  
**Gentagelse:** Hver måned / hver 3. måned / hver 6. måned  
**Beskrivelse:**  
Venligst kør importen fra Kitos til Wired Relations.  
Gå til Tandhjulet → Integrationer → Kitos og tryk på "Importer".  
Det tager et par minutter. Marker opgaven som udført bagefter.

---

## Når systemer/leverandører slettes i Kitos

- Nye systemer og leverandører oprettet i Kitos bliver importeret til Wired Relations
- **Slettede** systemer/leverandører i Kitos bliver **ikke** automatisk slettet i Wired Relations

> Dette er for at bevare data og undgå tab af berigede oplysninger.

### Sådan identificerer du slettede systemer/leverandører

- Gå til oversigten i Wired Relations
- Sortér efter kolonnen **“Opdateret”**
- Systemer/leverandører med ældre datoer end sidste import er sandsynligvis slettet i Kitos

> Overvej at oprette en tilbagevendende opgave for at håndtere slettede systemer.
>
> 
<img width="1797" height="654" alt="wired 2" src="https://github.com/user-attachments/assets/d8786096-1cf4-4b07-a285-de86205a0699" />

---

## Forbindelse mellem system og leverandør

- En leverandør kobles til et system i Wired Relations, hvis de er forbundet via en kontrakt i Kitos
- Ikke alle kommuner bruger kontrakt-funktionaliteten i Kitos

- <img width="1782" height="818" alt="wired 3" src="https://github.com/user-attachments/assets/953e80f4-3779-47b4-8eb4-5918032195d0" />

### Valgmulighed

- Vælg om forbindelsen skal styres via Kitos eller oprettes manuelt i Wired Relations
- Under Kitos-integrationen (samme sted som "Importer") kan I vælge, hvor leverandør-feltet styres

> Hvis I ønsker at skifte til manuel styring i Wired Relations, hjælper vi gerne med indstillingerne.
>
> 


---
<img width="1835" height="686" alt="wired 4" src="https://github.com/user-attachments/assets/b57322cb-b6e1-45da-b17a-3173c373bf2b" />

## Opmærksomhedspunkt

> Beslutningen om hvor leverandør-feltet styres bør være **relativt permanent**

- Hvis feltet beriges i Wired Relations og senere skiftes til Kitos, vil data blive **overskrevet**
- Information udfyldt i Wired Relations vil gå tabt

### Anbefaling

- Undgå at skifte frem og tilbage mellem Kitos og Wired Relations
- Kontakt os gerne for afklaring, hvis I er i tvivl

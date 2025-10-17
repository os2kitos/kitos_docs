---
title: Wired Relations Q&A
nav_order: 3
parent: Kitos Api
---
Herr kan du se en Q&A på Kitos datasamspil med ISMS systemet WIred Relations.
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

---

## Forbindelse mellem system og leverandør

- En leverandør kobles til et system i Wired Relations, hvis de er forbundet via en kontrakt i Kitos
- Ikke alle kommuner bruger kontrakt-funktionaliteten i Kitos

### Valgmulighed

- Vælg om forbindelsen skal styres via Kitos eller oprettes manuelt i Wired Relations
- Under Kitos-integrationen (samme sted som "Importer") kan I vælge, hvor leverandør-feltet styres

> Hvis I ønsker at skifte til manuel styring i Wired Relations, hjælper vi gerne med indstillingerne.

---

## Opmærksomhedspunkt

> Beslutningen om hvor leverandør-feltet styres bør være **relativt permanent**

- Hvis feltet beriges i Wired Relations og senere skiftes til Kitos, vil data blive **overskrevet**
- Information udfyldt i Wired Relations vil gå tabt

### Anbefaling

- Undgå at skifte frem og tilbage mellem Kitos og Wired Relations
- Kontakt os gerne for afklaring, hvis I er i tvivl

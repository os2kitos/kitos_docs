---
title: Synkronisering med FK Organisation
layout: default
nav_order: 5
parent: FK Organisation
---

# Synkronisering med FK Organisation

## Synkroniseringsmetode

Synkronisering med og indlæsning fra FK Organisation er en manuel proces, hvor Lokal Administrator skal gennemse konsekvenser for organisationen i Kitos på baggrund af opdateringer i FK Organisation. Først når Lokal Administrator har godkendt opdateringerne, vil indlæsning af data fra FK Organisation ske.

Tjek af, hvorvidt der er sket opdateringer i FK Organisation, kan ske på to måder – manuelt eller automatisk. Det er vigtigt at bemærke, at det kun er tjekket for opdateringer, der kan ske automatisk – selve indlæsningen kræver altid manuel godkendelse.



### **Manuelt tjek af opdateringer i FK Organisation**

Her skal Lokal Administrator tjekke for opdateringer på siden *Masse opret*, hver gang det ønskes.
Derved kan Lokal Administrator godkende eller afvise eventuelle konsekvenser, som opdateringer fra FK Organisation vil have i Kitos, før data indlæses. 

Se mere under afsnittet **Ændringsloggen**.



### **Automatisk tjek af opdateringer i FK Organisation**

Vælger man automatisk tjek, vil Kitos hver mandag (natten til tirsdag) tjekke, om der er opdateringer i FK Organisation.
Hvis der er ændringer, sendes en mail til alle Lokal Administratorer med besked om, at opdateringer skal behandles.

**Mail fra Kitos ser således ud.**

<img width="1217" height="279" alt="image" src="https://github.com/user-attachments/assets/6d208017-d235-4d6a-8694-7dabe26c4333" />

Klikker man på linket i mailen, lander man i Kitos, hvor man klikker på **Rediger**.


Derefter klikker man på **vis komsekvenser** og til sidst **Godkend ændringer**:

<img width="2444" height="751" alt="image" src="https://github.com/user-attachments/assets/37519c23-b6c7-4eda-b443-ffa31cf02bf4" />


Herefter vises de registrerede ændringer, og man kan vælge at **godkende** eller **afvise** de foreslåede opdateringer, inden der eventuelt indlæses data fra FK Organisation. Dette følger samme manuelle godkendelsesprocedure som beskrevet under **Ændringsloggen**.

---

## Synkronisering – niveauer

- I kan vælge, om Kitos skal synkronisere hele organisationshierarkiet eller kun en del af det.  
  Her ses eksempler med 1 og 2 niveauer:

**BILLEDE 6**

- I Kitos navigerer I til:

  - Menuen **Lokal Admin**  
  - Underpunktet **Masse opret**  
  - Sektionen **FK Organisation**  
  - Knappen **Forbind**

Her kan I vælge synkroniseringsniveau og om automatisk tjek skal aktiveres.

**BILLEDE 7**

**Feltet "Niveauer":** Vælg hvilke niveauer der synkroniseres. Hvis feltet er tomt, synkroniseres hele hierarkiet.

**Feltet "Automatik":** Aktiverer automatisk tjek for ændringer i FK Organisation.

**Forhåndsvisning:** Viser hierarkiet filtreret efter de valgte niveauer.

Eksempel på valg af 2 niveauer og fravalg af automatisk tjek:

**BILLEDE 8**

Når synkroniseringen gennemføres, vises følgende:

**BILLEDE 9**

Klik på **Ændringslog** for at folde loggen ud og se registrerede ændringer.

---

## Ændringsloggen

Kitos skriver ændringerne til ændringsloggen, som gemmes for de seneste fem synkroniseringer, der medførte faktiske ændringer.

I ændringsloggen ses:

- Hvilke enheder der tilføjes  
- Hvilke der slettes  
- Hvilke der omdøbes  
- Hvilke der flyttes  

Man kan stoppe importen via **Afvis ændringer**, eller gennemføre via **Godkend ændringer**.

Eksempel på ændringslog:

**BILLEDE 9**

---

## Synkronisering – enhedstyper

Kitos skelner fremover mellem to typer enheder:

- **Kitos-enheder**  
  Disse kan fuldt redigeres af Lokal Administrator (navn, EAN, enhed ID, overordnet enhed). De kan også slettes.

- **Enheder synkroniseret fra FK Organisation**  
  Disse kan delvist redigeres (EAN og enhed ID).  
  Navn og overordnet enhed synkroniseres og kan ikke ændres i Kitos.  
  De kan ikke slettes via brugerfladen – kun ved at afbryde FK-forbindelsen eller ændre synkroniseringsniveauer.

**BILLEDE 10**

---

## Synkronisering – konsekvenser

Når ændringer godkendes, vil Kitos hente organisationen fra FK Organisation og sammenligne med eksisterende data.

Følgende kan ske:

- **Enheder oprettet i FK Organisation → oprettes i Kitos**, hvis de ligger inden for valgt synkroniseringsdybde
- **Enheder der skifter navn → omdøbes i Kitos**
- **Enheder der flyttes → flyttes i Kitos**, hvis de fortsat ligger inden for synkroniseringsdybden  
  - Hvis en enhed flyttes *under* synkroniseringsniveauet (f.eks. til niveau 4 når der kun synkroniseres 3 niveauer), vil den blive behandlet som slettet

- **Enheder der slettes eller falder uden for synkroniseringsdybden:**
  - Hvis der *ikke* er registreringer → enheden slettes
  - Hvis der *er* registreringer → enheden omdannes til en **Kitos-enhed**  
    (Kan herefter håndteres manuelt, fx flyttes eller nedlægges)

``

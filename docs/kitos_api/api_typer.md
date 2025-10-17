---
title: API typer
nav_order: 3
parent: Kitos api
---

Der findes forskellige typer af API adgange i Kitos, herunder listes mulighederne op.
 
# API bruger

En API-bruger er som udgangspunkt en normal bruger, men isoleret til API-adgang.  
Det vil sige, at brugeren har **læseadgang** til alle systemobjekter i den kommune, hvor brugeren er oprettet.

## Rettigheder

- Kan læse alle data i kommunen (systemer taget i anvendelse + tilknyttet data)
- Der kan tildeles yderligere **skriv rettigheder** via administrator- eller forretningsroller
- Man kan knytte en **interessent-adgang** ovenpå for at udvide API-rettighederne til også at læse systemkatalogets data (offentlige + lokale systemer)

---

# Interessent-adgang

Interessent-adgang er både en **UI-rolle** og en **API-rolle**, som giver **læseadgang** til IT-system- og IT-snitflade-katalogobjekter:

- Gælder på tværs af kommuner
- Omfatter både offentlige og lokale systemer

Uden tildeling af API-bruger, fungerer rollen som en UI-rolle til interessenter, som ikke er kommuner.

## Rettigheder

- Rollen kan læse hele systemkataloget – både offentlige og lokale systemer

📘 [Læs mere om Interessent-adgang](https://strongminds.atlassian.net/wiki/spaces/KITOS/pages/860946433/Security#Stakeholder)

---

# Rettighedshaver-adgang

Brugeren bliver automatisk rettighedshaver på de systemer, der:

- Oprettes via **Rettighedshaver API’et**
- Eller hvor API-brugeren oprettes i den organisation, som er rettighedshaver på systemerne

Eksempel: Hvis API-brugeren oprettes i **KOMBIT**, kan denne bruger **læse og skrive** på systemer med KOMBIT som rettighedshaver.

## Rettigheder

- API-adgang som giver **LÆS + SKRIV** rettighed på data knyttet til systemer, hvor brugeren er rettighedshaver
- Brugeren kan oprette systemer med sig selv som rettighedshaver
- Brugeren kan deaktivere systemer, hvor brugeren er rettighedshaver

📘 [Læs mere om Rettighedshaver-adgang](https://strongminds.atlassian.net/wiki/spaces/KITOS/pages/860946433/Security#Rights-Holder)

---
title: Det lokale systemoverblik
layout: default
nav_order: 3
parent: System modulet
---

# Det lokale systemoverblik

Når et system er taget i anvendelse fra systemkataloget, tilføjes det automatisk til den lokale liste over dine IT-systemer - Det lokale systemoverblik.
Der nedarves stamdata fra systemkataloget og der åbnes op for lokale registreringer på systemet.
Der kan skiftes imellem lokal data og data fra systemkataloget, ved at benytte de øverste faner på siden:

<img width="2011" height="1181" alt="image" src="https://github.com/user-attachments/assets/dd0b94c8-236b-4e0b-98fa-a5aa3a9f9ccd" />


I venstremenuen kan du navigere mellem de forskellige faner hvor der kan tilføjes lokal data:

- Systemforside
- Kontrakter
- Databehandling
- GDPR
- Systemroller
- Organisation
- Relationer
- Udstillede snitflader
- Arkivering
- Hierarki
- Lokale KLE
- Advis
- Lokale referencer

**[Indsæt billede her]**

Bemærk her, at det er muligt for kommunens lokaladministrator at skjule felter og faner, hvis man ikke har behov for alle indtastningsfelter i Kitos.

Der er mulighed for at skjule alle faner undtagen de såkaldte navigationsfaner:

- Systemforside
- Kontrakter
- Databehandling

Derudover er det muligt for lokal admin at skjule felterne:

- Ibrugtagningsdato
- Slutdato for anvendelse
- Livscyklus

på systemforsiden, samt feltet:

**"Hvilken kontrakt skal afgøre om IT-systemet er aktivt"**

på Kontraktfanen.

Se mere i vejledningen:

**Administrer moduler og til- og fravælge faner og felter**

---

# Systemforside

**[Indsæt billede her]**

Felterne under overskriften **Data fra IT-Systemkataloget** er deaktiverede og kun en visning, da det er stamdata fra IT-Systemkataloget.

Data i de felter er ens for alle kommuner.

Felterne øverst med overskriften:

**<Systemnavn> i <kommunenavn>**

er felter, hvor du kan indtaste informationer, der er specifikke for din kommunes anvendelse af systemet.

## Felter på systemforsiden

### Lokal System-ID

Her kan du registrere et internt system-ID, hvis det er relevant.

### Lokalt kaldenavn

Her kan du registrere et lokalt kaldenavn eller en intern betegnelse.

### Klassifikation af data i systemet

Her kan du angive den relevante klassifikation af data i systemet.

Det bruges til at angive hvilken type data systemet indeholder i henhold til den klassifikationssystematik, man har valgt i kommunen.

Det kan bruges til at angive, hvor følsomme data systemet indeholder eller behandler, hvilket igen kan betyde forskellige typer af handlinger såsom kontrol, logning m.m.

### Note

Her kan du skrive en bemærkning.

### Hvor mange brugere benytter systemet i jeres kommune?

Her kan du angive, hvor mange brugere der benytter systemet, angivet i intervaller.

Default er et tomt felt.

### Version

Her kan du registrere hvilken version af systemet, der er taget i anvendelse.

### Taget i anvendelse af

Her vil der stå den bruger, der har taget systemet i anvendelse.

Det er ikke muligt at rette i dette felt.

### Ibrugtagningsdato

Her kan indtastes ibrugtagningsdato for systemet.

### Slutdato for anvendelse

Her kan indtastes slutdato for anvendelse af systemet.

### Livscyklus

Her kan angives hvor i livscyklus systemet befinder sig.

Mulige værdier er:

- Blank (ikke taget stilling)
- Under indfasning
- I drift
- Under udfasning
- Ikke i drift

### Status

Her vises om systemet har status aktivt eller ikke aktivt.

Er systemet ikke aktivt, kan man ved at trykke på den lille firkant i højre hjørne af feltet åbne op for yderligere information om, hvorfor systemet har status ikke aktivt.

### Sidst redigeret: Bruger

Her vises hvilken bruger, der sidst har redigeret systemoplysningerne.

Det er ikke muligt at rette i dette felt.

### Sidst redigeret: Dato

Her vises hvilken dato systemoplysningerne senest er blevet redigeret.

Det er ikke muligt at rette i dette felt.

---

# Kontrakter

I fanen **Kontrakter** kan du se en oversigt over de kontrakter i kontraktmodulet, som er tilknyttet det aktuelle IT-System.

Du kan vælge hvilken af disse kontrakter, der er den kontrakt, der eventuelt skal afgøre om systemet er aktivt.

**[Indsæt billede her]**

Er der ikke valgt en kontrakt eller er den valgte kontrakt gyldig, vil systemet få status aktiv ifølge markeret kontrakt.

Bemærk her, at det kun er hvis du har markeret, at kontrakten skal afgøre om systemet er aktivt, at leverandøren af kontrakten vises i systemoversigten.

Hvis du vil vide mere om, hvordan kontrakter registreres, kan du finde yderligere information i vejledningen til Kontraktmodulet.

---

# Databehandling

I fanen **Databehandling** kan du se en oversigt over de databehandlingsregistreringer, der er lavet i Databehandlingsmodulet, som er tilknyttet det aktuelle IT-System.

Tilknytningen sker altså i Databehandlingsmodulet.

**[Indsæt billede her]**

---

# GDPR

I fanen **GDPR** kan du angive oplysninger vedrørende GDPR for systemet.

Alt efter hvad du markerer, vil der være forskellige felter, der åbner sig.

**[Indsæt billede her]**

Der er flere felter, hvor du kan indsætte et link, fx til fortegnelse, risikovurdering og lignende.

I alle disse felter skal linket være af typen:

```text
http://
```

eller

```text
https://
```

## GDPR-felter

### Systemets overordnede formål

Her kan du angive systemets overordnede formål.

### Forretningskritisk IT-System

Her kan du angive, om systemet er forretningskritisk med:

- Ja
- Nej
- Ved ikke
- Blank (ikke taget stilling)

### IT-systemet driftes

Her kan du angive, hvordan systemet driftes:

- On-premise
- Eksternt
- Blank (ikke taget stilling)

### Link til fortegnelse

Her kan du indtaste navn og URL til fortegnelse.

### Hvilke typer data indeholder systemet

Her kan du markere hvilke typer data systemet indeholder.

Eksempler:

- Ingen personoplysninger
- Almindelige personoplysninger
- Følsomme personoplysninger
- Straffedomme og lovovertrædelser

Der kan markeres flere typer.

### Hvilke kategorier af registrerede indgår i databehandlingen

Her kan du markere en eller flere kategorier af registrerede, der indgår i databehandlingen.

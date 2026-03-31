---
title: Hvis forbindelsen fejler
layout: default
nav_order: 9
parent: FK Organisation
---

**Hvis forbindelsen til FK Organisation fejler**
Man skal ikke være nervøs for, at der sker noget med den organisationen i Kitos,
såfremt der måtte ske en afbrydelse af forbindelsen til FK Organisation.
Hvis forbindelsen til FK Organisation fejler, så fejler import processen også. Kitos
indlæser hele organisationen fra FK Organisation, inden den filtreres og synkroniseres.
Derfor vil en forbindelsesfejl til FK Organisation altså ikke kunne få hierarkiet i Kitos til
at gå i stykker.
STRONGMINDS vil i stedet få en fejlmelding i loggen om, at importprocessen er gået i
stykker, og vil se på, om fejlen ligger på Kitos’s side eller hos FK Organisation.

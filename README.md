# README.md: Fjellvik – Landskapet svarer (Hjorteforvaltning 3.2)

Animerings- og læringsspillet **Fjellvik – landskapet svarer** er et interaktivt, nettleserbasert simuleringsopplegg om viltforvaltning, bestandsdynamikk, usikre overvåkingsdata og interessekonflikter i norsk natur. 

Spillet er utviklet som en integrert læringsressurs hvor elevene/studentene inntar rollen som viltforvalter i det fiktive landskapet **Fjellvik**.

---

## 🎯 Pedagogisk formål og læringsmål

Hovedmålet med spillet er å gi innsikt i at naturforvaltning sjeldent handler om absolutte tall, men om å **tolke usikre indekser, avveie motstridende interesser og ta langsiktige beslutninger under usikkerhet**.

Etter å ha gjennomført spillet skal deltakerne kunne:
1. **Skille mellom observasjonsindeks og reell bestandsstørrelse** (f.eks. *Sett hjort per jegerdag* vs. faktisk antall individer).
2. **Forstå hjortens arealbruk og sesongtrekk** mellom sommer- og vinterbeiter (Nordlia og Sørskogen) samt tiltak mot trafikkfare og forstyrrelser.
3. **Ha innsikt i målkonflikter** mellom skogbruk (beiteskader på ungskog), jordbruk (avlingsskader) og jaktinteresser.
4. **Utarbeide og revidere femårige bestandsplaner** med målrettet avskytingsstruktur (kalv, kolle, spissbukk og eldre bukk).

---

## 🧭 Spillets oppbygning og oppdrag

Spillet er strukturert rundt **fire kronologiske oppdrag** som bygger på hverandre:

| Oppdrag | Tittel & Tema | Sentrale oppgaver og læringsmål |
| :--- | :--- | :--- |
| **1** | **Hvor stor er bestanden?**<br>*(Tolkning av overvåkingsdata)* | Analyse av historiske jaktlogger over 3 år. Skille observasjonsindeks (*sett hjort*) fra faktisk bestandsstørrelse. Plassering av feltbase og skriftlig begrunnelse for utgangspunktet. |
| **2** | **Vinterbeite og sesongtrekk**<br>*(Arealbruk og tiltak)* | Analyse av GPS-data og trekkruter mellom Nordlia (sommer) og Sørskogen (vinter). Prioritering av 5 tiltakspoeng på tryggere veikryssing, vinterro og merkedata. |
| **3** | **Hjort, skog og jordbruk**<br>*(Interessekonflikter)* | Avveining av skadekostnader og tiltak for å balansere hensynet til gårdbruker (avling), skogeier (furu/ungskog) og jakt/viltet. |
| **4** | **Lag en bestandsplan**<br>*(Femårig forvaltning)* | Utarbeidelse av en 5-årig avskytingsplan. Simulering av ett jaktår om gangen med årlig evaluering og mulighet for revisjon basert på nye beite-, vekt- og overvåkingsdata. |

---

## 🛠️ Nøkkelfunksjoner og mekanikker

* **Interaktivt landskapskart:** Viser Fjellvik med ulike soner (Nordlia, Sørskogen, Vassenden m.fl.), trekkruter og plassering av tiltak.
* **Dynamisk avskytingsmodul:** Presis justering av kvoter fordelt på fire kategorier: *Kalv*, *Kolle*, *Spissbukk* og *Eldre bukk*.
* **Forvaltningslogg og rapport:** Integrert notatblokk der spilleren underveis dokumenterer sine vurderinger og valg.
* **Årlig simulering:** Viser hvordan bestandsstørrelse, kalvevekter, beiteskader og beitesituasjon utvikler seg som respons på valgt avskyting.
* **Utskrift og eksport:** Generering av en samlet forvaltningsrapport for levering eller diskusjon i klassen.
* **Lokal datalagring (`localStorage`):** Spillerens fremgang og notater lagres automatisk i nettleseren slik at økten kan avbrytes og fortsettes senere.

---

## 💻 Teknisk informasjon og kjøring

Spillet er levert som en **enkeltstående, selvstendig HTML-fil (`index.html`)** med alt innebygd (HTML, CSS, JavaScript og bilder).

* **Ingen krav til server eller databaser:** Kan åpnes direkte i enhver moderne nettleser (Chrome, Firefox, Edge, Safari).
* **Universell utforming (A11y):** Tilrettelagt for skjermlesere, tastaturnavigasjon og oppfyller kontrastkrav.
* **Kjøre lokalt:** Dobbelklikk på `index.html` eller åpne den i nettleseren.
* **Publisering:** Kan publiseres direkte på en hvilken som helst statisk webserver eller bygges inn i Canvas / Itslearning / Web-nettsider via en `<iframe>`.

---

## 🏫 Anbefalt bruk i læringsstien

1. **Før spillet (Intro):**
   * Kort gjennomgang av sentrale begreper: Bæreevne, kjønns- og aldersstruktur, observasjonsindeks (*sett hjort*) og bestandsplaner.
2. **Under spillet (Egenarbeid / Gruppearbeid):**
   * Elevene arbeider seg gjennom oppdrag 1 til 4.
   * Underveis skal de skrive begrunnelser i den integrerte forvaltningsloggen.
3. **Etter spillet (Debatt og oppsummering):**
   * Sammenlign spillernes femårige resultater: Hvem oppnådde stabil bestand, god kalvevekt og lave beiteskader?
   * Diskusjon rundt dilemmatenkning i forvaltningen: Hvorfor er det krevende å gjøre alle interessegrupper fornøyde?

---

## 📜 Kredittering og opphavsrett

* **Faglig konsept og utvikling:** Ronny Steen, Norges miljø- og biovitenskapelige universitet (NMBU).
* **Kode- og spillasistanse:** Generert og tilpasset med ChatGPT (GPT-6 / Astra-modell).
* **Foto:** Bjørn Aksel Bjerke.
* **Versjon:** 3.2 (Fiktivt landskap og pedagogisk hjortemodell).

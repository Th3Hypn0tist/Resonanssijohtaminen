# 05. Miksi ihmiset eivät skaalaudu, mutta rakenteet skaalautuvat

## Purpose
- Purkaa henkilösankaruuden ja asiantuntijakeskeisyyden harha.
- Näyttää miksi osaaminen ilman rakennetta ei kumuloidu.
- Kytkee yksilön järjestelmään, ei sen kantajaksi.
- Perustelee SXaS:n välttämättömyyden.

## Core Claims
- Bus factor on rakenteellinen riski, ei henkilöriski.
- Implisiittinen tieto hidastaa päätöksentekoa ja estää skaalan.
- Rakenteellinen muistivuoto heikentää MaxROI-vaikutusta ajan myötä.
- Skaalautuvuus syntyy toistettavuudesta, ei henkilön kapasiteetin kasvattamisesta.

## Definitions (Operational)
- **Bus factor:** Kuinka monen henkilön poistuminen pysäyttää järjestelmän.
- **Implisiittinen tieto:** Tieto, joka ei ole käytettävissä ilman tiettyä henkilöä.
- **Rakenteellinen muistivuoto:** Toistuva kyvykkyyden katoaminen henkilövaihdoksissa.
- **Skaalautuvuus:** Kyky kasvattaa vaikutusta ilman suhteellista lisäystä ohjauskuormassa.

## Model / Mechanism
Kun tieto on implisiittistä, päätökset keskitetään osaajalle → kuorma kasvaa → viive kasvaa → vaikutus heikkenee. Jos tieto muutetaan rakenteeksi, päätökset voidaan hajauttaa → viive pienenee → vaikutus kasvaa. Jos Exitability paranee, rakenteellinen muistivuoto pienenee → kumuloituva kyvykkyys kasvaa.

## Failure Modes
- Skaalaus yritetään ratkaista rekrytoimalla lisää asiantuntijoita ilman rakenteen muutosta.
- Osaajille annetaan lisää statusta, mikä lisää riippuvuutta heistä.
- Dokumentaatio kerätään, mutta sitä ei sidota päätösvastuuseen.
- Osittainen soveltaminen: kerätään tietoa, mutta päätökset pysyvät yksilöillä.

## Implementation Notes
- Start here: mittaa bus factor jokaiselle kriittiselle prosessille.
- Tee implisiittisestä tiedosta eksplisiittistä vain päätösten kannalta relevantissa osassa.
- Käytä Exitability-testiä säännöllisesti.
- Rajaa asiantuntijarooleihin päätöstyypit, ei operatiivista ohjausta.
- Tarkista, missä kohtaa päätökset pullonkaulautuvat henkilöihin.
- Avoid this: palkita sankaruutta rakenteen kustannuksella.

## Links to Other Chapters
- This chapter depends on: 04-SXaS.md
- This chapter enables: 06-MaxROI.md, 10-AIGM.md

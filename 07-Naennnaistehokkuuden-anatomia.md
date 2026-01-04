# 07. Näennäistehokkuuden anatomia

## Purpose
- Paljastaa miksi kiire ja mittarit voivat valehdella.
- Antaa kriteerit tunnistaa busy work.
- Linkittää väärät mittarit MaxROI:n heikkenemiseen.
- Valmistaa päätöksenteon puhdistamiseen.

## Core Claims
- Busy work syntyy, kun mittari mittaa aktiviteettia eikä vaikutusta.
- Mittarivääristymä lisää kohinaa päätöksenteossa.
- Tehokkuusilluusio syntyy, kun päätökset optimoidaan paikallisesti.
- Jos palautesilmukka kertoo väärää tietoa, järjestelmä ohjautuu harhaan.

## Definitions (Operational)
- **Busy work:** Työ, joka lisää aktiviteettia ilman mitattavaa vaikutusta MaxROI-ydinmittareihin.
- **Mittarivääristymä:** Mittari ohjaa käyttäytymistä pois todellisesta vaikutuksesta.
- **Tehokkuusilluusio:** Tila, jossa mittarit paranevat mutta vaikutus heikkenee.

## Model / Mechanism
Kun mittari ohjaa aktiviteettiin, ihmiset maksimoivat aktiviteetin → mittari paranee → päätös uskoo vaikutuksen kasvavan. Jos vaikutus ei kasva, järjestelmä alkaa korjata: lisää raportointia → lisää busy work → vaikutus heikkenee. Jos mittari sidotaan MaxROI-ydinmittareihin, päätökset ohjaavat vaikutukseen → busy work vähenee.

## Failure Modes
- Mittarit poistetaan kokonaan, jolloin ohjaus katoaa.
- Näennäistehokkuus tulkitaan ”kulttuuriksi”, ei rakenteeksi.
- Päätöksiä tehdään ilman vaikutusdataa.
- Osittainen soveltaminen: poistetaan yksi mittari, mutta pidetään muut vääristävät mittarit.

## Implementation Notes
- Start here: tunnista mittarit, jotka eivät korreloi MaxROI-ydinmittareiden kanssa.
- Leikkaa raportointia, joka ei muuta päätöksiä.
- Vahvista palautesilmukka: vaikutus näkyviin ennen seuraavaa päätöstä.
- Tunnista paikalliset optimoinnit (tiimi vs kokonaisuus).
- Luo ”stop-lista” työstä, joka ei tuota vaikutusta.
- Avoid this: korvaa huono mittari toisella ilman vaikutuslogiikkaa.

## Links to Other Chapters
- This chapter depends on: 06-MaxROI.md
- This chapter enables: 08-Paatoksenteko.md, 14-Synergia.md

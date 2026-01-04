# 14. Miksi mikään osa ei toimi yksinään

## Purpose
- Kokoaa SXaS, MaxROI, päätöksenteon, Service Leadership, AIGM ja FreeMarket yhdeksi järjestelmäksi.
- Näyttää keskinäiset riippuvuudet ja palautesilmukat.
- Estää osittaiskäytön ja väärinymmärrykset.
- Kuvaa järjestelmäriippuvuuden vaikutuksen päätöksiin.

## Core Claims
- Jokainen osa on riippuvainen toisista; yksittäinen osa ei tuota resonanssia.
- Paikallinen optimointi heikentää kokonaisuutta.
- Palautesilmukka on yhteinen rajapinta SXaS:n, AIGM:n ja FreeMarketin välillä.
- MaxROI toimii ohjaavana vaikutusmittarina kaikille osille.

## Definitions (Operational)
- **Järjestelmäriippuvuus:** Tilanne, jossa osan vaikutus riippuu toisen osan tilasta.
- **Paikallinen optimointi:** Päätös, joka parantaa yhden osan mittaria heikentäen kokonaisuutta.
- **Kokonaisuus:** Järjestelmä, jossa päätökset, rakenne ja palaute ovat synkassa.

## Model / Mechanism
Jos SXaS puuttuu, AIGM ei kestä henkilövaihdoksia → päätöksenteko hidastuu. Jos MaxROI ei ohjaa, FreeMarket tuottaa väärää signaalia → HR:n rakenne vääristyy. Kun kaikki osat on kytketty, palaute kulkee läpi järjestelmän → päätökset kohdistuvat vipupisteisiin → vaikutus kasvaa.

## Failure Modes
- Malli pilkotaan ”pilareihin”, joita kehitetään erikseen.
- Päätöksenteko optimoidaan, mutta Exitability jätetään huomiotta.
- MaxROI käytetään raportointiin, ei ohjaukseen.
- Osittainen soveltaminen: FreeMarket otetaan käyttöön ilman AIGM-rooleja.

## Implementation Notes
- Start here: piirrä päätöksen kulku SXaS → AIGM → FreeMarket → MaxROI.
- Tunnista riippuvuudet ja määritä kytkentäkohtien omistajat.
- Varmista, että palaute kulkee kaikille osille.
- Testaa järjestelmä yhdellä päätöstyypillä end-to-end.
- Karsi paikalliset optimoinnit, jotka eivät paranna MaxROI-ydinmittareita.
- Avoid this: tehdä yksittäisestä osasta ”silver bullet”.

## Links to Other Chapters
- This chapter depends on: 07-Naennnaistehokkuuden-anatomia.md, 13-Markkina-suodattaa.md
- This chapter enables: 15-Resonanssiorganisaation-malli.md

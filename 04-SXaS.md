# 04. SXaS — Structure as a Service

## Purpose
- Määrittää ”Structure before tools” -periaatteen käytännöllisesti.
- Kuvaa omistettavuuden ja Exitabilityn roolin resonanssissa.
- Luo rakenteen, joka kestää henkilövaihdoksia.
- Liittää rakenteen skaalautuvuuteen ilman henkilöriskejä.

## Core Claims
- Työkalut eivät skaalaa ilman rakenteen omistettavuutta.
- Exitability on rakenteen kestävyysmittari, ei henkilökysymys.
- Rakenteet voivat olla palveluina yhtä vakioituja kuin tekniset palvelut.
- Ilman SXaS:ia resonanssi hajoaa, koska palautesilmukka katkeaa henkilövaihdoksissa.

## Definitions (Operational)
- **SXaS (Structure as a Service):** Rakenne, joka on dokumentoitu, omistettu ja siirrettävissä roolista toiseen ilman katkoa.
- **Ownership:** Selkeä vastuutaho rakenteen ylläpidolle ja parantamiselle.
- **Exitability:** Kyky irrottaa henkilö prosessista ilman toiminnan katkeamista.
- **Rakenteellinen kestävyys:** Järjestelmän kyky säilyttää toiminta muutoksista huolimatta.

## Model / Mechanism
Kun rakenne on palvelu, sen omistaja varmistaa jatkuvan ylläpidon. Jos rakenteella on Ownership ja Exitability, henkilön poistuminen ei katkaise palautetta → päätöksenteko jatkuu → resonanssi säilyy. Jos rakenne on henkilöriippuvainen, poistuma katkaisee palautesilmukan → päätökset hidastuvat → vaikutus heikkenee.

## Failure Modes
- SXaS tulkitaan dokumentaatioksi ilman omistajaa.
- Exitabilitya pidetään HR-kysymyksenä, ei rakenteellisena vaatimuksena.
- Työkaluja vaihdetaan, mutta rakenne pysyy henkilöriippuvaisena.
- Osittainen soveltaminen: omistetaan prosessi, mutta ei päätösvastuuta.

## Implementation Notes
- Start here: valitse 2–3 kriittistä rakennetta ja nimeä omistaja.
- Kuvaa rakenne niin, että uusi rooli pystyy toimimaan 1 viikon sisällä.
- Määritä Exitability-testit (esim. poissaolo 2 viikkoa).
- Liitä rakenteen mittarit MaxROI-ydinmittareihin.
- Varmista, että päätösoikeus kulkee rakenteen mukana.
- Avoid this: rakentaa SXaS ilman palautetta todellisista käyttötapauksista.

## Links to Other Chapters
- This chapter depends on: 03-Resonanssijohtaminen-ydinperiaate.md
- This chapter enables: 05-Ihmiset-eivat-skaalaudu.md, 15-Resonanssiorganisaation-malli.md

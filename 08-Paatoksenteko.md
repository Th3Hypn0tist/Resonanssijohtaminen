# 08. Päätöksenteko monimutkaisissa järjestelmissä

## Purpose
- Siirtää fokus suunnittelusta päätöksiin.
- Erottelee signaalin kohinasta operatiivisesti.
- Määrittää ajoituksen ja intervention minimoinnin.
- Kuvaa päätösten vaikutuksen koko järjestelmään.

## Core Claims
- Päätös on järjestelmän ohjaushetki; suunnitelma on taustaoletus.
- Signaali on dataa, joka muuttaa päätöstä; kohina ei muuta.
- Vipuvaikutus syntyy, kun pieni päätös muuttaa palautesilmukkaa.
- Peruuttamattomat päätökset vaativat lyhimmän palautesilmukan.

## Definitions (Operational)
- **Signaali:** Informaatio, joka muuttaa päätöksen sisältöä tai ajoitusta.
- **Kohina:** Informaatio, joka ei muuta päätöstä.
- **Vipuvaikutus:** Päätöksen vaikutus, joka on suhteettoman suuri panokseen nähden.
- **Peruuttamattomuus:** Päätöksen vaikutus, jota ei voi kääntää ilman merkittävää kustannusta.

## Model / Mechanism
Jos päätös tehdään liian aikaisin, signaali puuttuu → päätös perustuu oletukseen → vaikutus heikkenee. Jos päätös tehdään liian myöhään, mahdollisuus vipuvaikutukseen menee ohi. Kun palautesilmukka on lyhyt ja signaali tunnistettu, päätös osuu oikeaan kohtaan → vaikutus kasvaa. Jos kohina ohjaa, päätös osuu väärään kohtaan → korjausliike kasvaa.

## Failure Modes
- Päätökset korvataan suunnitelmilla ja raportoinnilla.
- Kaikki data käsitellään signaalina, mikä hidastaa päätöstä.
- Päätökset tehdään ”varmuuden” vuoksi liian aikaisin.
- Osittainen soveltaminen: päätöksiä hajautetaan ilman signaalin määrittelyä.

## Implementation Notes
- Start here: määritä päätökselle signaalit, jotka sen tulee täyttää.
- Rajaa kohina: poista raportteja, joita ei käytetä päätöksissä.
- Aikatauluta päätökset palautteen rytmiin.
- Määritä päätösten peruuttamattomuusluokka.
- Luo ”no decision” -sääntö, kun signaali puuttuu.
- Avoid this: tehdä päätöksiä pelkän trendin perusteella.

## Links to Other Chapters
- This chapter depends on: 02-Resonanssi-ilmiona.md, 06-MaxROI.md
- This chapter enables: 09-Palvelujohtajuus.md, 10-AIGM.md

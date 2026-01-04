# 06. MaxROI — Maximum Return on Intelligence

## Purpose
- Määrittää MaxROI mittaristoksi, ei johtamismenetelmäksi.
- Lukitsee kolme ydinmittaria: Money impact, Environmental impact, Well-being impact.
- Erottelee vaikutuksen työstä ja näennäistehokkuudesta.
- Liittää mittarit päätöksenteon rytmiin.

## Core Claims
- MaxROI mittaa älyn tuoton vaikutuksena, ei aktiviteettina.
- Vain kolme ydinmittaria ohjaavat kokonaisuutta; muut mittarit selittävät niitä.
- Viivästetty kustannus on olennainen osa vaikutusmittausta.
- Jos mittari ei vaikuta päätöksiin, se lisää kohinaa.

## Definitions (Operational)
- **MaxROI:** Mittarikehys, joka yhdistää Money impact, Environmental impact ja Well-being impact -vaikutukset.
- **Money impact:** Rahallinen vaikutus nettoarvona päätöksen jälkeen.
- **Environmental impact:** Vaikutus ympäristöön mitattavana nettomuutosvaikutuksena.
- **Well-being impact:** Vaikutus hyvinvointiin mitattavana nettomuutosvaikutuksena.
- **Viivästetty kustannus:** Vaikutus, joka realisoituu myöhemmin päätöksen seurauksena.

## Model / Mechanism
Jos päätös kasvattaa vaikutusta yhdessä ydinmittarissa mutta pienentää toisessa, kokonaisvaikutus on ristiriitainen. Jos päätös parantaa kaikkia kolmea, MaxROI kasvaa. Jos mittarit eivät ole näkyvissä päätöksessä, päätös optimoi toissijaisia indikaattoreita → vaikutus heikkenee → korjauskierros kasvaa.

## Failure Modes
- MaxROI tulkitaan henkilön tehokkuudeksi eikä rakenteelliseksi vaikutukseksi.
- Toissijaiset mittarit (esim. velocity) ohjaavat päätöksiä ilman linkkiä ydinmittareihin.
- Mittarit asetetaan, mutta viivästetty kustannus jätetään pois.
- Osittainen soveltaminen: mitataan vain Money impact.

## Implementation Notes
- Start here: määritä ydinmittarit per päätöstyypit.
- Käytä toissijaisia mittareita vain selittävinä, ei ohjaavina.
- Määritä viivästetyn kustannuksen arviointiaika.
- Raportoi vaikutus per päätös, ei per henkilö.
- Pidä mittarit näkyvissä päätöspisteissä.
- Avoid this: lisää mittareita ilman päätöslogiikan päivitystä.

## Links to Other Chapters
- This chapter depends on: 05-Ihmiset-eivat-skaalaudu.md
- This chapter enables: 07-Naennnaistehokkuuden-anatomia.md, 08-Paatoksenteko.md

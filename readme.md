# Verkefni 3

## Lýsing

Skrifa skal CSS fyrir gefið HTML í `index.html`. [Sjá fyrirmynd og virkni](fyrirmynd/).

![](fyrirmynd.png)

Ekki er leyfilegt að breyta HTML skjali.

### Almennt

Grunnstærð leturs skal vera `16px` og aðeins skal nota `em` og `rem` einingar fyrir stærðir fyrir utan:

* Skilgreiningu á grunnstærð
* Þykkt á `border`

Útlit þarf aðeins að vera rétt í a.m.k. 1000px breiðum Chrome vafra.

## Útlit

Síða skal miðjusett innan vafra, efni skal vera að hámarki `1000px`.

Fyrirsögn (innan `<header>`) skal hafa bakgrunnslitinn `#eeeeee` og vera föst þegar síða er skoðuð, sjá hreyfimynd. Það skal vera `16px` padding innan header. Stærð á texta skal vera `32px` og skal hann vera miðjusettur.

Fótur skal vera eins og haus, nema ekki fastur.

## Inngangur

Mynd skal vera miðjusett með miðjusettum texta. Mynd skal ekki vera undir fyrirsögn þegar síðu hefur ekki verið skrollað, ekki þarf að hafa nákvæmt gildi en miða skal við fyrirmynd. Texti skal vera `16px`.

Texti fyrir neðan mynd skal vera `32px` með `32px` bili fyrir ofan og neðan.

Box með tenglum á skal setja upp með `float` og:

* Engum stíl á lista (`list-style: none;`)
* Box skulu taka þriðjung af heildarplássi og hafa `1%` bil á öllum hliðum
* Utan um box skal vera pixelbreiður `dotted`, `#333333` border
* Texti innan boxa skal vera `24px` og `16px` padding á öllum hliðum
* Box skal vera amk. `96px` hátt
* Þegar mús eða lyklaborðsfókus fer yfir box skal það fá bakgrunnslitinn `#999999`

Fyrirsögn skal vera `96px` há og með `32px` bili fyrir ofan og neðan.

## Sögur

Fyrirsögn sögu skal vera `48px` með `32px` bili fyrir neðan.

Texti skal vera `24px` en fyrsta lína `30px` og fyrsti stafur `32px`.

Mynd skal vera fleytt til vinstri og hafa padding upp á `16px` til hægri og fyrir neðan.

Þegar mús fer yfir sögu skal setja bakgrunnslitinn `#999999`, _aðeins_ á texta.

### Annað

Aðeins er leyfilegt að nota eftirfarandi yfirlýsingar í CSS:

* `background-color`
* `border` og `border-top` o.fl.
* `color`
* `content`
* `display`
* `font-size`
* `height`
* `margin` og `margin-top` o.fl.
* `max-width`
* `padding` og `padding-top` o.fl.
* `width`

Leyfilegt er að nota alla selectora.

Setja skal inn virkni til að fela element með `sr-only` class frá skjálesurum.

CSS skal vera án villna **og viðvarana** þegar keyrt í gegnum https://jigsaw.w3.org/css-validator/

## Mat

* 20% – Snyrtilega uppsett og gilt CSS
* 20% – Aðeins leyfileg eigindi notuð og `em`/`rem` notað fyrir stærðir
* 60% – Útlit skv. fyrirmynd

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 14. september 2020.

## Skil

Skila skal í Canvas í seinasta lagi fyrir lok dags þriðjudaginn 22. september 2020.

Skilaboð skulu innihalda slóð á verkefni ásamt zip skjali með lausn sem heitir ``verkefni3-<notendanafn>.zip`, t.d. `verkefni3-osk.zip`.

## Einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1

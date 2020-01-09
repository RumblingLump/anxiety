# act1

```
SceneSetup.act1();
```

(...300)

n: DET HÄR ÄR MÄNNISKANS ÅNGEST

n: _DU_ ÄR ÅNGESTEN

{{if window.localStorage.continueChapter=="replay"}}
(#act1_replay)
{{/if}}

{{if window.localStorage.continueChapter!="replay"}}
(#act1_normal)
{{/if}}



# act1_replay

`hong({mouth:"0_neutral", eyes:"0_neutral"})`

h: Nämen! Vi är här igen?§

`hong({eyes:"0_neutral"})`

n: DITT JOBB ÄR ATT SKYDDA DIN MÄNNISKA FRÅN *FARA*

`bb({eyes:"look", mouth:"small_lock"})`

n: FAKUM ÄR, ATT SPELA OM DET HÄR SPELET SÄTTER DEM I *FARA* JUST NU!

n: FORT, VARNA DEM!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Människa! Lyssna, vi är i fara! spelaren...

[...tänker tortera oss igen!](#act1_replay_torture)

[...kommer inte hitta ett §annat avslut§!](#act1_replay_alternate)

[...kommer drabbas av ludonarrativ dissonans!](#act1_replay_dissonance)

# act1_replay_torture

```
window.HACK_REPLAY = JSON.parse(localStorage.act4);
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

{{if window.HACK_REPLAY.act1_ending=="fight"}}
b: De kommer få oss att krypa ihop i en boll och gråta!
{{/if}}

{{if window.HACK_REPLAY.act1_ending=="flight"}}
b: De kommer få oss att döda din mobil för att den gav dig en panikattack!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="fight"}}
b: De kommer få oss att *inte* slå §husvärden/festvärden§!
{{/if}}

{{if window.HACK_REPLAY.a2_ending=="flight"}}
b: De kommer få oss att slå den Sympatiska §Antiantagonistvärden§!swedish pls
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="jump"}}
h: Vi kommer åtmistånde kanske inte hoppa från taket den här gå--
{{/if}}

{{if window.HACK_REPLAY.a3_ending=="walkaway"}}
b: DE KOMMER FÅ OSS ATT HOPPA FRÅN TAKET.
{{/if}}

`bb({body:"fear"});`

b: ALLA DESSA HEMSKA SAKER KOMMER ATT HÄNDA OSS OCH VI KOMMER DÅ ATT--

(#act1_replay_end)


#act1_replay_alternate

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: Visst, historien som *helhet* är den samma, men varje kapittel har två möjliga slut, plus alla §branching dialog opti§--

`bb({body:"fear"});`

b: Spelaren kommer att bli besviken, stänga fliken, radera mjukvaran, och då kommer vi att--

(#act1_replay_end)


# act1_replay_dissonance

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich"});
```

h: En luddig vadå?

`bb({eyes:"normal"});`

b: Historien handlade om hur du kan *VÄLJA* att bygga ett sundt samarbete med din rädsla,

`bb({eyes:"normal_right"});`

b: Men att spela om spelet ger dig samma historia, vilket implicerar att dina *VAL* inte spelar någon roll,

`bb({eyes:"narrow_eyebrow"});`

b: Vilket påvisar en motsägelse mellan spelets budskap och mekaniker,§

`bb({eyes:"fear"});`

b: Och således upplöser detta narrativa universums självaste väv,

`bb({body:"fear"});`

b: Och då kommer vi att--

(#act1_replay_end)


# act1_replay_end

`bb({body:"panic"})`

b: DÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖ

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.clearText();
```

(...1001)

```
bb({body:"laugh"});
hong({body:"laugh"});
Game.clearText();
sfx("laugh");
```

(...5001)

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"0_sammich"});
```

h: Okej, tillbaka i karaktär.§

```
Game.clearText();
```

n4: (LÅT _DIN_ ÅNGEST BLA BLA BLA MEST LIKT VAD _DIN_ RÄDSLA BLA BLA DU VET HUR DET FUNGERAR)

```
sfx("squeak");
hong({body:"0_squeeze"});
bb({body:"squeeze"});
```

(#act1_normal_choice)



# act1_normal

`hong({mouth:"0_neutral", eyes:"0_annoyed"})`

h: Så bra, min varg är tillbaka. Faaaaantastiskt.

`hong({eyes:"0_neutral"})`

n: DITT JOBB ÄR ATT SKYDDA DIN MÄNNISKA FRÅN *FARA*

`bb({eyes:"look", mouth:"small_lock"})`

n: FAKTUM ÄR, ATT DEN DÄR SMÖRGÅSEN SÄTTER DEM I *FARA* JUST NU

n: FORT, VARNA DEM!

```
sfx("squeak");
bb({body:"squeeze_talk"});
hong({body:"0_squeeze"});
```

b: Människa! Lyssna,§should the comma be a period?§ vi är i fara! The danger is...

`bb({body:"squeeze"})`

n4: (LÅT _DIN_ ÅNGEST §COME OUT TO PLAY§! VÄLJ DET MEST LIKNAR VAD _DIN_ RÄDSLA SÄGER)

(#act1_normal_choice)

# act1_normal_choice

[Vi äter lunch ensamma! Igen!](#act1a_alone) `bb({body:"squeeze_talk"})`

[Vi är inte produktiva när vi äter!](#act1a_productive) `bb({body:"squeeze_talk"})`

[Det där vita brödet är dåligt för oss!](#act1a_bread) `bb({body:"squeeze_talk"})`

# act1a_alone

```
bb({body:"normal", mouth:"small", eyes:"narrow"});
hong({body:"0_sammich"});
```

b: Vet du inte att ensamhet är associerat med att dö i förtid lika mycket som att röka 15 cigaretter per dag?-

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({mouth:"normal", eyes:"normal_right"})`

b: (Holt-Lunstad 2010, PLoS Medicine)

`hong({eyes:"0_annoyed"})`

h: §um§, tack för att du citerar dina källor men--

`Game.OVERRIDE_TEXT_SPEED = 2;`

`bb({body:"fear", mouth:"normal", eyes:"fear"})`

b: Vilket innebär att om vi inte hänger med någon *omedelbart* kommer vi att-

`bb({body:"panic"})`

b: DÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖ
```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "alone");
publish("hp_show");
```

(...2500)

`_.fifteencigs = true`

n: DU ANVÄNDE *RÄDSLA FÖR ATT VARA OÄLSKAD*

(#act1b)

# act1a_productive

```
bb({body:"normal", mouth:"small", eyes:"normal"});
hong({body:"0_sammich"});
```

b: släng fram din laptop och börja med något produktivt nu!

`hong({eyes:"0_annoyed"})`

h: §Um§, jag skulle helst inte få brödsmulor mellan ta--

```
bb({mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Om vi inte bidrar till samhällets kropp så är vi en samhällsparasit!

b: Samhällskroppen kommer att gå till samhällsdoktorn för läkemedel till at ta kål på deras samhällsparasiter §och§ då kommer vi--

```
bb({body:"panic", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: DÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖ

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "bad");
publish("hp_show");
```

(...2500)

`_.parasite = true`

n: DU ANVÄNDE *RÄDSLA FÖR ATT VARA EN DÅLIG PERSON*

(#act1b)

# act1a_bread

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({body:"0_sammich", eyes:"0_annoyed"});
```

h: Har de sudierna blivit replikerade--

```
bb({body:"fear", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Processat vete kommer spika vårat blodsocker så de måste amputera alla våra lemmar och då kommer vi att--

`bb({body:"panic"})`

b: DÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖ

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"0_shock", eyes:"0_shock"});
attack("18p", "harm");
publish("hp_show");
```

(...2500)

`_.whitebread = true`

n: DU ANVÄNDE *RÄDSLA FÖR ATT SKADAS*

(#act1b)

# act1b

n: IT'S SUPER EFFECTIVE§

`bb({mouth:"smile", eyes:"smile"});`

b: Du ser, mäinniska. Jag är din lojala vakt-varg!

`bb({body:"pride_talk"});`

b: Lita på din mage! Dina känslor är alltid giltiga!

`bb({body:"pride"});`

n: FÅ NED DIN MÄNNISKAS ENERGI TILL NOLL

n: FÖR ATT SKYDDA DERAS + SOCIALA + MORALISKA BEHOV, §SÅ§ KAN DU ANVÄNDA:

n: RÄDSLAN FÖR ATT *SKADAS* #harm#

n: RÄDSLAN FÖR ATT VARA OÄLSKAD #alone#

n: OCH RÄDSLAN FÖR ATT VARA EN DÅLIG PERSON #bad#

`Game.OVERRIDE_TEXT_SPEED = 1.25;`

n4: (TIPS: VÄLJ ALTERNATIVEN SOM PERSONLIGEN TRÄFFAR DINA DJUPASTE, MÖRKASTE FASOR!~)

h: ...

```
hong({body:"putaway"});
sfx("rustle");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

(...1000)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h: vet du vad, det kanske är dags att kolla mobilen.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: SKYDDA DIN MÄNNISKA

n: FRÅN VÄRLDEN. FRÅN ANDRA MÄNNISKOR. FRÅN DEM SJÄLVA.

n: LYCKA TILL

(...500)

`Game.clearText()`

(...500)

(#act1c)

# act1c

`music('battle', {volume:0.5})`

n: ROND ETT: *FIGHT!*§

`bb({body:"normal", mouth:"normal", eyes:"normal"});`

h: Huh. Facebook feed säger att det är en fest nu i helgen.§

`bb({eyes:"uncertain"});`

b: Har inte den skummisen fest *varje* helg?§

`bb({eyes:"uncertain_right"});`

b: Vilket inre hålrum försöker de fylla? De måste vara djupt störda på insidan!

`hong({eyes:"surprise"});`

h: Dessutom, fick jag en inbjudan?

`bb({eyes:"fear", mouth:"normal"});`

b: Då så!

[Säg ja, eller så dör vi av ensamhet!](#act1c_loner)

[Säg nej, det är fullt av giftiga droger!](#act1c_drugs)

[Ignora den, vi gör bara fester dystra.](#act1c_sad)

# act1c_loner

{{if _.fifteencigs}}
b: Femton cigaretter om §dan/dagen§, människa! Femton!
{{/if}}

{{if !_.fifteencigs}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if !_.fifteencigs}}
b: Då kommer ingen att komma på vår begraving, de kommer att dumpa våra askor i havet, och vi blir till,
{{/if}}

{{if !_.fifteencigs}}
b: och vi blir till VALBAJS!
{{/if}}

{{if !_.fifteencigs}} `_.whalepoop = true` {{/if}}

(...500)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

{{if !_.fifteencigs}}
b: Så ja vi gå till den där festen!§
{{/if}}

{{if _.parasite}}
b: Ta med laptopen bara så att vi kan arbeta, och inte vara samhällsparasiter.
{{/if}}

{{if _.whitebread}}
b: Bara så länge de inte bjuder på VITT BRÖD
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GUD. Om det får dig att hålla tyst, visst.

h: Jag säger ja.

{{if _.whalepoop}}
b: Valbajs, människa! Valbajs!
{{/if}}

`_.partyinvite="yes"`

(#act1d)

# act1c_drugs

`bb({mouth:"small", eyes:"fear"});`

{{if _.whitebread}}
b: eller ännu värre... VITT BRÖD
{{/if}}

{{if _.whitebread}}
`Game.OVERRIDE_TEXT_SPEED = 1.5;`
{{/if}}

{{if _.whitebread}}
b: Vi kommer att överdosera på så mycket tjack och vitt bröd att de inte kommer få plats med vårat feta lik i kremationsugnen!
{{/if}}

{{if !_.whitebread}}
b: Vi kommer att överdosera på så mycket knark att the §undertaker will wonder how our body was *already* pre-embalmed!§
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.parasite}}
b: Oavsätt, kan inte festa, vi behöver arbeta, eller så är vi hemska samhällsparasiter!
{{/if}}

`hong({mouth:"anger", eyes:"anger"});`

h: GUD. Om det får dig att hålla tyst, visst.

h: Jag säger nej.

`_.partyinvite="no"`

(#act1d)

# act1c_sad

`bb({eyes:"uncertain_right", mouth:"normal"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.fifteencigs}}
b: Allt vi nånsin gör är att gråta i ett hörn om att ensamhet är lika dödligt som 15 cigaretter om dan.
{{/if}}

{{if _.parasite}}
b: Allt vi gör på fester är att oroa oss för hur vi borde vara produktiva istället.
{{/if}}

{{if _.whitebread}}
b: Allt vi nånsin gör är att oroa oss för hur de ohälsosamma matalternativen kommer att döda oss.
{{/if}}

```
bb({mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"lookaway"});
```

h: jisses jag undrar varför.

`hong({eyes:"neutral"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: Så om vi går får vi dom att må dåligt, men om vi avvisar deras inbjudan får vi också dem att må dåligt!

`bb({body:"fear", eyes:"fear"});`

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

b: ALLT VI GÖR ÄR ATT FÅ FOLK ATT MÅ DÅLIGT, SÅ VI BORDE MÅ DÅLIGT

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`hong({mouth:"anger", eyes:"anger"});`

h: Ugh. Om det får dig att hålla tyst, visst.

h: Jag ignorerar inbjudningen.

`_.partyinvite="ignore"`

(#act1d)

# act1d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({mouth:"neutral", eyes:"annoyed"});
```

h: Hursomhelst. Facebook är för mycket. Jag behöver något lugnare, mindre ångestframkallande.

`hong({eyes:"neutral"});`

h: Vad händer på Twitter?

`bb({eyes:"look"});`

[Åh nej, titta på det där hemska nyhetsnslaget!](#act1d_news)

[Åh nej, är det där tweetet i smyg om *oss?*](#act1d_subtweet)

[Kolla, en GIF av en katt som dricker mjölk](#act1d_milk)


# act1d_news

```
bb({eyes:"pained1"});
music(null, {fade:2});
```

b: Gud, det känns som om världen brinner, eller hur?

```
bb({eyes:"pained2"});
hong({mouth:"sad", eyes:"sad"});
```

b: Det känns som allt håller på att ta slut, som om allt är döende och vi är dömda och det finns inget vi kan göra åt det.

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
bb({mouth:"shut"});
```

b: ...

`bb({mouth:"smile", eyes:"smile"});`

b: Vi tar och retweetar det!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.badnews=true`

```
music('battle', {volume:0.5});
hong({mouth:"anger", eyes:"anger"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Okej, jag retweetar det, kan du bara snälla vara tyst!

`hong({mouth:"neutral", eyes:"annoyed"});`

h: Strunt samma, vi tar och kollar Snapchat.

(#act1e)


# act1d_subtweet

`bb({eyes:"fear"});`

b: Det är en subtweet! En lömsk, lömsk subtweet!

`hong({eyes:"annoyed"});`

h: Det är det antagligen inte?

`bb({eyes:"narrow", mouth:"small"});`

b: men tänk om de talar bakom vår rygg?
h: Det gö--

`bb({body:"fear", eyes:"fear", mouth:"normal"});`

b: FRAMFÖR VÅR RYGG

`hong({eyes:"sad", mouth:"sad"});`

h: Jag t--§

`bb({eyes:"narrow", mouth:"small"});`

b: men *tänk om-*

h: S--

`bb({eyes:"narrow_eyebrow"});`

b: *tänk om-*

```
Game.OVERRIDE_TEXT_SPEED = 0.5;
hong({mouth:"shut"});
```

h: ...

(...1000)

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.subtweet=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KEJ, ska försöka med Snapchat.

(#act1e)

# act1d_milk

`hong({mouth:"smile", eyes:"neutral"});`

h: Hehe ja vad gulligt, retweetade precis, jag tro--

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: KATTER KAN INTE BRYTA NED MJÖLK OCH VI ÄR HEMSKA MÄNNISKOR AV ATT HA NJUTIT AV DJURMISSHANDEL

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("18p", "bad");
```

(...2500)


`_.catmilk=true`

```
hong({mouth:"anger", eyes:"annoyed"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: o-KEJ, ska försöka med Snapchat.

(#act1e)

# act1e

`hong({mouth:"neutral", eyes:"neutral"});`

h: Huh, bilder från igår kväll. Så det är *så* de där hälg-festerna ser ut.

{{if _.partyinvite=="yes"}} (#act1e_said_yes) {{/if}}

{{if _.partyinvite=="no"}} (#act1e_said_no) {{/if}}

{{if _.partyinvite=="ignore"}} (#act1e_said_ignore) {{/if}}

# act1e_said_yes

`hong({mouth:"sad", eyes:"annoyed"});`

h: Aj, ser aldeles för folktätt ut för min ångest.

h: Jag kanske inte borde sagt ja till inbjudan?

```
hong({mouth:"neutral", eyes:"neutral"});
bb({mouth:"normal", eyes:"normal"});
```

[Ändra vårt svar? Som en skitstövel?!](#act1e_yes_dontchange)

[Ändra vårt svar! Det är för trångt!](#act1e_yes_changetono)

{{if _.subtweet}}
[Jo, de subtweetade oss defenitivt.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Vänta vi retweetedade utan att fakta-kolla.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Du vet att du har riktigt dålig hållning?](#act1e_ignore_posture)
{{/if}}

# act1e_yes_dontchange

```
bb({eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: De litade på oss och nu bedrar vi deras tillit? Vill du dö ensam?!

{{if _.fifteencigs}}
b: FEMTON. CIGARETTER.
{{/if}}

{{if _.whalepoop}}
b: VAL-. BAJS.
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Håll käft håll käft jag har kvar det som ja!

(#act1f)

# act1e_yes_changetono

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Känner du inte till folkrusningar?

```
bb({body:"fear", mouth:"small", eyes:"narrow"});
hong({eyes:"sad", mouth:"sad"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: År 2003 fattade en nattklubb i Rhode Island eld och paniken fick folk att överfylla utgångarna så att 100 personer brann ihjäl-

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
hong({mouth:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: VILL DU ATT DET SKA HÄNDA OSS-

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 2.5;
```

b: SÄG NEJ SÄG NEJ SÄG NEJ SÄG NEJ SÄG NEJ SÄG NEJ SÄG NEJ SÄG NEJ SÄG N-


```
bb({body:"normal", eyes:"fear", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
hong({eyes:"anger", mouth:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Håll käft håll käft jag ändrar mitt svar till nej! Gud!

(#act1f)

# act1e_said_no

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... det ser riktigt kul ut.

h: Jag kanske inte skulla ha sagt nej till inbjudan?§

`bb({mouth:"normal", eyes:"normal"});`

[Ändra vårt svar? Som en skitstövel?!](#act1e_no_dontchange)

[Ändra vårt svar! Dö inte ensam!](#act1e_no_changetoyes)

{{if _.subtweet}}
[Jo, de subtweetade oss defenitivt.](#act1e_ignore_subtweet)
{{/if}}

{{if _.badnews}}
[Vänta vi retweetade utan att fakta-kolla.](#act1e_ignore_factcheck)
{{/if}}

{{if (!_.subtweet && !_.badnews)}}
[Du vet, du har riktigt dålig hållning?](#act1e_ignore_posture)
{{/if}}

# act1e_no_dontchange

`bb({eyes:"anger"})`

b: Alla räknade med oss!

b: ...att lämna dem ifred och låta dem ha en trevlig fest utan ett hemskt, vidrigt {{if _.whitebread}}vitbröds-mumsande{{/if}} äckel som du--


```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
bb({body:"normal", eyes:"uncertain", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Håll käft håll käft jag har kvar det som nej!

(#act1f)

# act1e_no_changetoyes

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Kronisk ensamhet ökar våra kortisolnivåer samt risken för kardiovaskulär sjukdom och stroke!

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

{{if _.fifteencigs}}
b: FEMTON. CIGARETTER.
{{/if}}

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Håll käft håll käft jag ändrar mitt svar till ja! Gud!

(#act1f)

# act1e_ignore_subtweet

```
bb({eyes:"fear", mouth:"small"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Alla våra problematiska tweets har kommit ikapp oss!

```
bb({body:"fear", eyes:"fear", mouth:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.7;
```

b: We're gonna get called out and cancelled and dragged with a rope on horseback down the information superhighway!§

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Varför är du så här?!

(#act1f)

# act1e_ignore_factcheck

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Vi sprider felaktig information! Vi förstör tilliten på en fri press!

```
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Vi är anledningen till att fascismen kommer resa sig ur demokratins förfall!

```
bb({body:"normal", eyes:"anger"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

```
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
_.factcheck = true;
```

h: Varför är du så här?!

(#act1f)

# act1e_ignore_posture

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Vill du ha en kringla till ryggrad?! Sluta kröka dig över skärmen!

```
bb({body:"meta"});
```

b: Det gäller dig också.

```
bb({body:"normal", mouth:"normal"});
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({mouth:"anger", eyes:"anger"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Varför är du så här?!

(#act1f)

# act1e_said_ignore

`hong({mouth:"sad", eyes:"sad"});`

h: Hm... det ser riktigt roligt ut.

h: Jag kanske inte borde ha ignorerat inbjudan?

`bb({mouth:"normal", eyes:"normal"});`

[Forsätt ignorera, vi är fortfarande §party poopers§.](#act1e_ignore_continue)

[Fast egentligen, säg ja.](#act1e_ignore_changetoyes)

[Fast egentligen, säg ja.](#act1e_ignore_changetono)

# act1e_ignore_continue

`hong({eyes:"annoyed"});`

h: Det är lite oförskämt att fortsätta ignorera, dock. Inte sant?

`bb({eyes:"normal_right"});`

b: Fast andra ignorerar alltid *oss*, så

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`bb({eyes:"normal"});`

b: vi säger att vi är kvitt.

(#act1f)

# act1e_ignore_changetoyes

`hong({eyes:"surprise", mouth:"smile"});`

h: Du... låter mig ha kul?

b: Ja, jag menar, ensamhet *kan* döda oss.

`hong({eyes:"neutral", mouth:"neutral"});`

(#act1e_no_changetoyes)

# act1e_ignore_changetono

`bb({eyes:"narrow"});`

b: Det är för folktätt. folkmassor är farliga.

(#act1e_yes_changetono)


# act1f

```
hong({mouth:"neutral", eyes:"neutral"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

h: Strunt samma. Ny Tindernotifikation.

`bb({eyes:"uncertain"})`

b: Vadå, den där hookup-apppen?

`hong({eyes:"annoyed"})`

h: Det är inte en hookup-app, det är bara ett sätt att träffa nya människ--

`bb({eyes:"narrow"})`

b: Det är en hookup-app.

```
hong({eyes:"surprise", mouth:"smile"});
bb({eyes:"normal"});
```

h: Åh, Jag fick en matchning! De ser söta ut!

```
bb({eyes:"narrow_eyebrow"});
hong({eyes:"sad", mouth:"anger"})
```

h: Snälla förstör inte det här för m--

```
bb({body:"panic"});
Game.OVERRIDE_TEXT_SPEED = 2.0;
```

b: FARA FARA FARA FARA FARA FARA

`bb({body:"fear", eyes:"fear", mouth:"normal"})`

[Vi håller på att *utnyttjas* av andra.](#act1f_used_by_others)

[Vi håller bara på att *utnyttja* andra.](#act1f_using_others)

[DIN MATCHNING ÄR EN SERIEMÖRDARE](#act1f_killer)

# act1f_used_by_others

`bb({body:"point_crotch", eyes:"normal", mouth:"normal"})`

b: §Random hookups§ kanske kav fylla hålet där nere,

b: men de kan aldrig fylla hålet...

`bb({body:"point_heart", eyes:"pretty", mouth:"small"})`

b: *här inne*.

(...1000)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Poängen är att vi KOMMER DÖ ENSAMMA§

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "alone");
```

(...2500)

`_.hookuphole=true`

(#act1g)

# act1f_using_others

`bb({eyes:"narrow", mouth:"small"})`

b: Tror du att andras könsorgan är Pokémon som vi ska samla?

```
bb({body:"sing", eyes:"pretty", mouth:"shut"});
music("pokemon");
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

```
Game.FORCE_TEXT_DURATION = 1000;
Game.FORCE_NO_VOICE = true;
```

b: ♫ (pokemon signaturmelodi)-

(...5600)

```
bb({mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2400;
```

b: ♫ I wanna be, the ^slut^ti-est-§

(...500)

```
bb({eyes:"narrow", mouth:"small"});
Game.FORCE_TEXT_DURATION = 2100;
```

b: ♫ Like no one ever was-§

(...1500)

```
bb({eyes:"pretty"});
Game.FORCE_TEXT_DURATION = 2300;
```

b: ♫ Thighs n' ^ass^, voluptuous breast-§

(...500)

```
bb({eyes:"fear", mouth:"normal"});
Game.FORCE_TEXT_DURATION = 2000;
```

b: ♫ with sweaty ^dick^ and balls!-§

(...1000)

```
bb({eyes:"smile", mouth:"smile"});
Game.FORCE_TEXT_DURATION = 1000;
```

b: ♫ PERVY-MON! GOTTA CA-§

```
Game.FORCE_CANT_SKIP = false;
Game.clearText();
music(false);
bb({body:"normal", mouth:"normal", eyes:"normal"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Poängen är att vi är ett manipulativt äckel.

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "bad");
```

(...2500)

`_.pokemon=true`

(#act1g)

# act1f_killer

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

{{if _.whitebread}}
b: De §will trap you§ i en brunn tvångsmata dig med vitt bröd för att göda upp dig så de kan klä sig i ditt skin som en kostym!
{{/if}}

{{if _.parasite}}
b: They'll bludgeon you with a pomodoro timer and say "YOU SHOULDA BEEN MORE PRODUCTIVE YOU PARASITE"§
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: De kommer slita ditt kött till §blodig§ konfetti, §turn your entrails into streamers§, och §mix your blood into a§ punschskål!
{{/if}}

{{if !_.whitebread && !_.parasite}}
b: How's THAT for a party invite?!§
{{/if}}

```
hong({mouth:"shock", eyes:"shock"});
attack("18p", "harm");
```

(...2500)

`_.serialkiller=true`

(#act1g)

# act1g

```
bb({body:"normal", mouth:"normal", eyes:"look"});
hong({body:"2_tired"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
music(false);
```

h: ...

(...500)

h: i'm so sick of this game.§

(...700)

`Game.OVERRIDE_TEXT_SPEED = 1.5;`

h:
{{if _.fifteencigs}}"loneliness will kill us"... {{/if}}§
{{if _.parasite}}"we're a society-parasite"... {{/if}}§
{{if _.whitebread}}"don't eat that, it'll kill us"... {{/if}}§
{{if _.subtweet}}"they're talking behind our back"... {{/if}}§
{{if _.badnews}}"the world is burning"... {{/if}}§
{{if _.hookuphole}}"we'll die alone"... {{/if}}§
{{if _.serialkiller}}"they're a serial killer"... {{/if}}§
{{if _.catmilk}}"cats can't digest milk"... {{/if}}§
{{if _.pokemon}}a ^crappy^ parody song... {{/if}}§

h: i just want to live my life.§

h: i just want to be free from all this... pain.§

`bb({eyes:"look_sad"});`

b: Hey... human...§

`Game.OVERRIDE_TEXT_SPEED = 0.5;`

b: Det löser sig.

(...600)

`bb({body:"point_heart", eyes:"look_sad_smile", mouth:"smile"});`

b: Som din lojala §guard-wolf§ §ska/skall/kommer§ jag alltid §keep an eye out for danger§, och göra mitt bästa att §skydda dig/hålla dig säker§.

`bb({body:"normal", eyes:"look_sad", mouth:"smile"});`

b: Jag lovar.

(...600)

```
bb({body:"normal", eyes:"normal", mouth:"normal"});
hong({body:"phone1", eyes:"neutral", mouth:"neutral"});
```

h: Last app. Instagram. What you got?§

`hong({eyes:"sad"});`

h: It's... more party pictures.§

`hong({mouth:"sad"});`

h: Alla ser så glada ut. Fria från oro. Fria från ångest.§

`hong({mouth:"anger"});`

h: God, why can't I be like them? Why can't I just be *normal?*§

`bb({eyes:"normal_right"});`

b: På tal om fester, om §this weekend's invite§. Här är §my FINAL decision§:

`bb({eyes:"normal"});`

[Vi borde gå.](#act1g_go) `Game.OVERRIDE_CHOICE_LINE=true`

[Vi borde inte gå.](#act1g_dont) `Game.OVERRIDE_CHOICE_LINE=true`

# act1g_go

`_.act1g = "go"`

(#act1h)

# act1g_dont

`_.act1g = "dont"`

(#act1h)

# act1h

b: Vi bo--

```
bb({eyes:"wat", mouth:"small"});
hong({body:"2_fuck"});
```

h: *^FUCK^.*§

`hong({body:"2_you"});`

h: YOU.§

(...500)

b: v

(...1500)

`bb({eyes:"wat_2"});`

b: va?§

`hong({body:"phone1", eyes:"anger", mouth:"anger"});`

h: Jag §kommer/tänker§ säga JA till festen,

{{if _.act1g=="go"}}
h: INTE du vill, utan för att *§Jag/JAG§* vill.
{{/if}}

{{if _.act1g=="dont"}}
h: Precisely BECAUSE you don't want me to.§
{{/if}}

```
hong({body:"putaway"});
sfx("rustle");
```

h: You're NOT in control of me.§

```
sfx("rustle2");
hong({body:"0_sammich", eyes:"0_annoyed", mouth:"0_neutral"});
```

h: Now excuse me while I eat this delicious sandwich in ^goddamn^ peace.§

`hong({body:"2_sammich_eat"});`

(...601)

```
sfx("sandwich");
hong({body:"2_sammich_eaten", eyes:"0_lookaway", mouth:"0_chew1"})
```

(...601)

```
bb({body:"normal", eyes:"uncertain", mouth:"shut"});
Game.OVERRIDE_TEXT_SPEED = 0.5;
```

b: ...

```
bb({eyes:"normal_right"});
Game.OVERRIDE_TEXT_SPEED = 1;
```

b: ...

```
bb({eyes:"fear"});
Game.OVERRIDE_TEXT_SPEED = 4;
```

b: ..................

(...500)

`bb({mouth:"normal"});`

[AHHHH VI KOMMER DÖ](#act1h_death) `Game.OVERRIDE_CHOICE_LINE = true;`

[AHHHH ALLA HATAR OSS](#act1h_loneliness) `Game.OVERRIDE_CHOICE_LINE = true;`

[§AHHHH VI ÄR HEMSKA MÄNNISKOR§](#act1h_worthless) `Game.OVERRIDE_CHOICE_LINE = true;`

# act1h_death

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH VI KOMMER DÖ AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "harm");
```

(...2500)

(#act1i)

# act1h_loneliness

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH ALLA HATAR OSS AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "alone");
```

(...2500)

(#act1i)

# act1h_worthless

```
bb({body:"fear"});
Game.OVERRIDE_TEXT_SPEED = 3;
```

b: AHHHH §VI ÄR HEMSKA MÄNNISKOR§ AAAAAAHHHHHHH

```
hong({body:"3_defeated1"});
attack("100p", "bad");
```

(...2500)

(#act1i)

# act1i

```
bb({mouth:"smile_lock", eyes:"smile", body:"normal"});
music('battle', {volume:0.5});
```

n: §GRATULERAR§

(...500)

n: DU HAR LYCKATS SKYDDA DIN MÄNNNSIKAS FYSISKA + SOCIALA + MORALISKA BEHOV

n: SE, SÅ TACKSAMMA DE ÄR!

(...500)

n: NU NÄR DERAS ENERGI §IS ZERO§, KAN DU DIREKT KONTROLLERA DERAS §AGERANDE/HANDLINGAR§

`bb({mouth:"smile", eyes:"normal"});`

n: PICK YOUR ENDING MOVE§

`bb({mouth:"small_lock", eyes:"fear"});`

n: *FINISH THEM*§

[{§KAMP§: Punish your stressful phone!§}](#act1i_phone) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLYKT: Kryp ihop till en boll och gråt!}](#act1i_cry) `Game.OVERRIDE_CHOICE_LINE=true`

# act1i_phone

`bb({mouth:"normal", eyes:"narrow"})`

b: Your phone was giving you a panic attack!§

`bb({eyes:"anger"})`

b: Zuckerberg and Co are hijacking your mental health for venture capitalist money!§

```
bb({body:"fear", eyes:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Punish your phone! §Krossa/Förgör§ den! Döda den!§

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "fight";
```

b: DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DEN DÖDA DE--

(#act1j)

# act1i_cry

`bb({eyes:"fear", mouth:"normal"})`

b: Hela världen är fylld av fara!

```
bb({body:"fear"});
hong({body:"3_defeated2"});
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

b: Gör som bältdjuret! Kryp ihop §i/för§ självförsvar!

```
Game.OVERRIDE_TEXT_SPEED = 2.5;
bb({body:"flail"});
hong({body:"3_defeated3"});
_.act1_ending = "flight";
```

b: KRYP IHOP OCH GRÅT KRYP IHOP OCH GRÅT KRYP IHOP OCH GRÅT KRYP IHOP OCH GRÅT KRYP IHOP OCH GRÅT KRYP IHOP OCH GR-- 

(#act1j)

# act1j

`SceneSetup.act1_outro()`

# act2

`SceneSetup.act2();`

{{if _.badnews && !_.factcheck}}
(#act2-preamble-news1)
{{/if}}

{{if _.badnews && _.factcheck}}
(#act2-preamble-news2)
{{/if}}

{{if _.catmilk}}
(#act2-preamble-cat)
{{/if}}

(#act2-preamble-tinder)


# act2-preamble-news1

```
publish("act2",["dee",3]);
```

s: Men *såg* du den där "nyheten" om den där hemska saken som hände någonstans?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hej...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Gud vad jag hatar nyheterna. Det är bara sensationalism och §clickbait§.

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: t... trevlig fest...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Sant, men de följer bara §incentives§. Det *verkliga* problemet är folk som klickar på §clickbait§.

```
publish("act2",["dee",3]);
```

s: Vem skulle retweeta en §så§ hemsk nyhet, och få alla deras vänner att må dåligt?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, jag vet?

(#act2-preamble-end)


# act2-preamble-news2

```
publish("act2",["dee",3]);
```

s: Men *såg* du den där "nyheten" §going viral§?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hej...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Visst, uppenbart fejk. Vem skulle falla för det och retweeta?

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: t... trevlig fest...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Seriöst mannen. Hallå, liksom, öppna Google och faktakolla först?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, eller hur?

(#act2-preamble-end)


# act2-preamble-cat

```
publish("act2",["dee",3]);
```

s: Som jag sa, the §Meme Industrial Complex/ Meme-Industriella Komplexet§ exploaterar katter.

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hej...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Elaborate on this thesis.§

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: t... trevlig fest...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Så, jag såg att någon retweetade en GIF av en katt som drack mjölk igår.

```
publish("act2",["dee",3]);
```

s: De inte smälta den ^skiten^! Vem skulle retweeta *djurmisshandel* sådär?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, eller hur?

(#act2-preamble-end)


# act2-preamble-tinder

```
publish("act2",["dee",1]);
```

s: Så nej de svarade aldrig!

```
publish("act2",["dee",0]);
publish("act2",["party_hong","next"]);
```

h2: h-hej...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Trots att ni båda matchade §varandra§ på twitter?

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: t... trevlig fest...

```
publish("act2",["party_hong","next"]);
```

{{if _.serialkiller}}
(#act2-preamble-serialkiller)
{{/if}}

{{if _.hookuphole}}
(#act2-preamble-hookuphole)
{{/if}}

{{if _.pokemon}}
(#act2-preamble-pokemon)
{{/if}}

# act2-preamble-serialkiller

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja venn'e! Vadå, trodde de att jag var en *seriemördare* eller §nått§? Så paranoid.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, eller hur?

(#act2-preamble-end)


# act2-preamble-hookuphole

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja venn'e! De kanske inte tror att §hookups§ inte kan fylla hålet i deras hjärta?

s: Sluta vara så prydig! Öppna ditt sinne, och öppna §dina ben/din gren§!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, eller hur?

(#act2-preamble-end)


# act2-preamble-pokemon

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Ja venn'e! De var inte så snygga, §but they would have been a nice catch§!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Gotta Catch 'Em All!™§

(#act2-preamble-end)


# act2-preamble-end

```
Game.clearText();
publish("act2-out-1");
music(null, {fade:1});
```

(...3000)

```
music('battle', {volume:0.5});
publish("hp_show");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

n: ROUND TWO: *FIGHT!*

[Åh nej alla hatar oss!](#act2a_social)

[Stod du och *glodde* på rödtotten?](#act2a_perv)

[Du, vi tar och diskuterar meningen med livet.](#act2a_meaning)

# act2a_social

`bb({eyes:"sad"})`

b: Vi drar ned stämningen av den här festen genom att vara en §ledsen/sorgsen§ klump!

`bb({eyes:"shock", body:"two_up"})`

b: Vi dödar de sköna vibbarna! Vi begår första gradens vibbmord!

`bb({eyes:"normal", body:"normal"})`

b: Människa, vi måste gå *nu* innan--

```
_.a2_first_danger = 'social';
_.a2_attack_1 = "alone";
```

(#act2b)

# act2a_perv

`bb({eyes:"suspect"})`

b: De är mer atraktiva än oss, vilket betyder att om vi ens *tittar* på dem, så--

`bb({eyes:"shock", body:"two_up"})`

b: ÄR VI §CREEPS/SVIN§
`bb({body:"normal"})`

b: Vi är vidriga, onda, dåliga dåliga §dåliga§ hemska hemska pervon--

```
_.a2_first_danger = 'perv';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2a_meaning

`bb({body:"one_up", eyes:"normal_r"})`

b: I slutändan, vad skulle vi någonsin kunna göra som spelar roll?

`bb({body:"normal", eyes:"sad"})`

b: Bidra till mänskligheten? Alla storverk §decay the way of Ozymandias§. Kärlek? Döden kommer alltid att §skilja den åt§.

`bb({eyes:"sad_r"})`

b: Och så mycket död det är! *Vi* kommer dö. *Våra nära och kära* kommer dö.

`bb({eyes:"shock", body:"two_up"})`

b: §Heck§, Termodynamikens Andra Huvudsats innebär att även vårat *universum* kommer dö!

`bb({eyes:"suspect", body:"normal"})`

b: Oh, "döden får oss att uppskatta livet"? Det är som att säga att slaveri är bra för det får oss att upskatta frihet!

`bb({body:"one_up"})`

b: Oh, "du måste skapa din egen mening"? Det är vad §cultists§ och konspirationsteoretiker gör!

`bb({eyes:"shock", body:"two_up"})`

b: Livet har ingen mening, döden har ingen mening, till och med *mening* har ingen mening! Vad ska en dödlig själ ta sig till--

```
_.a2_first_danger = 'meaning';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2b

`bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"suspect"})`

b: Um... kan du höra mig, människa?

`bb({eyes:"normal", MOUTH_LOCK:true})`

b: ...

`bb({eyes:"shock", mouth:"small_talk", body:"chest", MOUTH_LOCK:true})`

b: *GASP*§

`bb({mouth:"small_talk"})`

b: JAG MÅSTE VARNA DIG FÖR...

[*Mer* av samma fara!](#act2b_louder)

{{if _.a2_first_danger=="social"}}
[En *annan* social fara!](#act2b_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[En *annan* moralisk fara!](#act2b_different_moral)
{{/if}}

[Du ignorerar fara! §Det§ är farligt!](#act2b_ignore)

# act2b_louder

`_.a2_first_choice = "louder"`

{{if _.a2_first_danger=="social"}}
(#act2b_louder_social)
{{/if}}

{{if _.a2_first_danger=="perv"}}
(#act2b_louder_perv)
{{/if}}

{{if _.a2_first_danger=="meaning"}}
(#act2b_louder_meaning)
{{/if}}

# act2b_louder_social

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: KÄNSLOR ÄR SMITTSAMMA! SÅ OM DU INTE GÅR SÅ KOMMER DU ATT INFEKTERA ALLA MED DIN §MENTAL ILLNESS§! 

b: Du kommer starta/påbörja ett dödligt utbrott av LEDSENKLUMPSSYNDROM

`bb({eyes:"suspect", body:"normal", mouth:"normal"})`

b: vi behöver ta oss härifrån och sätta oss själva i evig karantän i ett litet rum med Netflix och hämtmat!

```
_.a2_second_danger = 'netflix';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "a quarantine";
```

(#act2c)

# act2b_louder_perv

`bb({eyes:"suspect", body:"two_up", mouth:"normal"})`

b: VAR INTE ETT CREEP. DET ÄR MOT LAGEN!

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Creep Law, Section 74.5: (1) En person som spanar in (a) those muscular shoulders (b) that bubble booty (2) skall hädanefter kännas vid som§

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "ETT STORT VIDRIGT §SKITPERVO§"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "the law";
```

(#act2c)

# act2b_louder_meaning

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: Faktumed, att även om du finner en nobel mening i livet, kan du *fortfarande* förstöra allt!

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Alfred Nobel ville ha världsfred och att olika kulturer skulle förstå varandra. Så han bestämde sig för att göra färd lättare.

`bb({eyes:"normal_r"})`

b: Så han behövde ett sätt att billigt "skapa" tågtunlar. Så han uppfann ett nytt material kallat "dynamit"...

`bb({body:"one_up", eyes:"normal"})`

b: vilket användes i Första Världskriget för att DÖDA MILJONTALS MÄNNISKOR

`bb({body:"two_up", eyes:"shock"})`

b: DET ÄR FJÄRILSEFFEKTEN, MÄNNISKA! HUR MÅNGA §OSKYLDIGA§ DÖDAR DU AV MISSTAG JUST NU

```
_.a2_second_danger = 'butterfly';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "World War I";
```

(#act2c)

# act2b_different_social

`_.a2_first_choice = "different"`

`bb({eyes:"normal_r", body:"point", mouth:"normal"})`

b: Faktiskt, vet du vad som är värre än att ingen tycker om dig? *Alla* tycker om dig.

`bb({body:"one_up", eyes:"suspect", mouth:"normal"})`

b: Altså, att bli en av *dessa* njutningsjagande festprissarna.

`bb({body:"normal", mouth:"small"})`

b: Ett ytligt liv med ytliga vänner som bara känner det ytliga du!

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Människa, vi måste fly från de här njutningszombierna innan de förvandlar oss till en av dem!

```
_.a2_second_danger = 'zombies';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "zombies";
```

(#act2c)

# act2b_different_moral

`_.a2_first_choice = "different"`

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Folk dör till svält och folkmord *just nu* och vi bara festar!

`bb({body:"point", eyes:"closed", mouth:"small"})`

b: En vis person sa en gång, "det enda som krävs för ondskans triumf är att §gott folk§ inte gör någonting."

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: VI GÖR INGENTING.

`bb({mouth:"small"})`

b: GENOM ATT FESTA, HJÄLPER VI *HITLER*.

```
_.a2_second_danger = 'hitler';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Hitler";
```

(#act2c)

# act2b_ignore

`_.a2_first_choice = "ignore"`

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Du tror att du är säker bara för att du tog ur batterierna ur kolmonoxidetektorn?

`bb({eyes:"suspect_r"})`

b: Du kommer inte ens känna lukten av gift! Du kommer bara att känna dig lite sömnig, och då kommer du--

`bb({body:"scream_c_1"})`

b: DÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖÖ

```
_.a2_second_danger = 'ignore';
_.a2_attack_2 = "harm";
_.a2_hoodie_callback = "carbon monoxide";
```

(#act2c)

# act2c

```
hong({body:"ignore_sweat"});
bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true});
```

b: ...

`bb({eyes:"happy", mouth:"smile", body:"chest"})`

b: Åh tack och lov människa, Jag tror att du kan höra mig igen!

`bb({eyes:"closed", body:"point"})`

b: Jag skall varna dig för...

{{if _.a2_first_choice=="louder"}}
[*Ännu mer* av samma fara!](#act2c_louder)
{{/if}}

{{if _.a2_first_choice!="louder"}}
[*Mer* av samma fara!](#act2c_louder)
{{/if}}

{{if _.a2_first_danger=="social"}}
[En *annan* social fara!](#act2c_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[En *annan* moralisk fara!](#act2c_different_moral)
{{/if}}

[§Did you check§ §den där§ punschen innan du drack?](#act2c_punch)

#act2c_louder

{{if _.a2_second_danger=="netflix"}}
(#act2c_louder_netflix)
{{/if}}

{{if _.a2_second_danger=="law"}}
(#act2c_louder_law)
{{/if}}

{{if _.a2_second_danger=="butterfly"}}
(#act2c_louder_butterfly)
{{/if}}

{{if _.a2_second_danger=="zombies"}}
(#act2c_louder_zombies)
{{/if}}

{{if _.a2_second_danger=="hitler"}}
(#act2c_louder_hitler)
{{/if}}

{{if _.a2_second_danger=="ignore"}}
(#act2c_louder_ignore)
{{/if}}

# act2c_louder_netflix

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: Egentligen, Netflix & §food delivery§ är inte karantän nog! Vi skulle fortfarande infektera §the delivery person§!

`bb({body:"one_up", mouth:"small"})`

b: Vi behöver flytta till de kanadensiska Yukon-teritorierna, och få vår mat levererad med drönare!

`bb({body:"two_up", mouth:"normal"})`

b: Och då skulle de behöva sterilisera drönaren för att få bort våra LEDSENKLUMPSBAKTERIER

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "a quarantine";`

(#act2d)

# act2c_louder_law

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Det STORA VIDRIGA SKRÄPPERVOT skall dömas till 72 timmar i en av de där medeltida §public-humiliation devices§

b: så länge de inte är §*into* that sort of thing§

`bb({body:"scream_a_1"})`

b: för att de är ett STORT VIDRIGT SKRÄPPERVO

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the law";`

(#act2d)

# act2c_louder_butterfly

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: FJÄRILSEFFEKTEN! Du använder en ej-nedbrytbar plastmugg?

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: §BAM§, EN SOPTIPP LÄCKER GIFT OCH DÖDAR ETT BARN

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: Du svettas och hjärtat pumpar?

`bb({body:"scream_a_1"})`

b: §BAM§, DU RUINERAR VÅRAT SJUKVÅRDSSYSTEM OCH MILJONTALS DÖR

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the butterfly effect";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: Dessa njutningszombierna kommer vackla mot dig mumlandes,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: §LIIIIIKES. LIIIIIIIIIIKES.§

`bb({body:"scream_a_1"})`

b: Sen kommer de att BITA DIG och förvandla dig till en §BRAINLESS BRO and/or THOUGHTLESS THOT§!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zombies";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: THE NAZIS ARE GOOSE-STEPPING BACK ON THE STREETS RIGHT NOW§

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Saying, *tur att de där §'good folks'§ latade sig med saker som 'avslappning' och §'self-care'§!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Now our plans can go fourth, reich on schedule!*§

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitler";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b: Appropå det, vet vi om den här byggnade har en kolmonoxiddetektor?!

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: Tänk om vi alla håller på att förgiftas *JUST NU*

`bb({body:"scream_a_1"})`

b: VI SKULLE INTE ENS SE DÖDEN NÄRMA SIG. VI SKULLE BARA SLUTA EXISTERA §FOREVER AND EVER AND EV§--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "carbon monoxide";`

(#act2d)

# act2c_different_social

`bb({body:"normal", mouth:"normal", eyes:"sad"})`

b: Tänk om vi bara är *fundamentalt inkababla* att någonsin vara älskade, eller älska en annan?

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Tänk om något irreversibelt gick sönder inom oss för länge sen? Eller att det aldrig fanns från första början?

`bb({body:"scream_a_1"})`

b: AHH VI ÄR TRASIGA! SÅ TRASIGA SÅ TRASIGA SÅ TRASI--

`_.a2_attack_3 = "alone";`

(#act2d)

# act2c_different_moral

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Tänk om vi bara är *fundamentalt ruttna?*

`bb({body:"one_up", eyes:"sad"})`

b: Andra har ett inre driv att göra gott, men vi gör bara "gott" utav skuld eller skam, om alls.

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: Tänk om det ligger i vår natur att skada andra? Tänk om vi inte kan vara något *annat* än en börda till de som står hos nära?

`bb({body:"scream_a_1"})`

b: AHH VI ÄR TRASIGA! SÅ TRASIGA SÅ TRASIGA SÅ TRASI--

`_.a2_attack_3 = "bad";`

(#act2d)

# act2c_punch

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Jag är inte irrationell. §People *do* drug punch bowls§. Det är en faktisk sak som faktiskt sker.

`bb({eyes:"suspect"})`

b: Människa, har du huvudvärk? Är dina lemmar veka? Jag tror vi håller på att dö.

`bb({body:"scream_a_1"})`

b: AHHH VI HÅLLER PÅ ATT DÖ! VI HÅLLER PÅ ATT DÖ VI HÅLLER PÅ ATT DÖ VI HÅ--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "punch bowls";`

(#act2d)

# act2d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"attacked"});
attack("20p", _.a2_attack_1);
```

(...401)

```
hong({body:"attacked_2"});
attack("20p", _.a2_attack_2);
```

(...401)

```
hong({body:"attacked_3"});
attack("20p", _.a2_attack_3);
```

(...1001)

h: F^AAACK^!§

h: F^ACK^ING F^ACK^-F^AKK^ITY *F^AAAAACK^*§

`bb({body:"two_up", mouth:"smile", eyes:"happy"});`

b: Hurra, människa! Jag är så glad att du kan höra mig igen!

`bb({body:"normal", mouth:"small", eyes:"sad"})`

b: Varför ignorerade du mig?

`hong({body:"facepalm"})`

h: Holy ^hell^, you absolute moron.§

`hong({body:"facepalm_2"})`

h: Du vet den där §Indianska§ sagan?

h: "Det finns två vargar inom dig, en är hopp, en är förtvivlan, vilken varg vinner? Den du fodrar."

```
hong({body:"facepalm_3"});
bb({eyes:"normal"});
```

h: Jag har försökt *svälta* dig, ditt sadistiska ^as/arsle^!

`hong({body:"smile", mouth:"smile"})`

h: Screw it, I'll do positive affirmations instead.§

h: *Jag är älskad. Jag är god. Jag är smart. Jag är vacker. Jag är speciell.*

`bb({eyes:"suspect"});`

[Golly, that's so narcissistic!](#act2d_narcissist)§

[Y'know affirmations were *disproven?*](#act2d_disproven)§

[omg don't credit random stories to indigenous folk](#act2d_racist)§

# act2d_disproven

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Faktum är, att de faktiskt *ger bakslag* för folk med lågt självförtroende! 

`bb({body:"one_up", mouth:"small", eyes:"normal"})`

b: Det var en väldesignad studie– randomiserad och kontrollerad, prövningspersonal var blind för vem som var i vilken grupp.

`bb({body:"two_up", mouth:"small", eyes:"normal_r"})`

b: Resultat: om du redan har lågt självförtroende, så får §being asked to repeat affirmations makes you feel *worse*§ än om du inte hade sagt något alls!

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Wood 2009, Psychological Science. Kolla upp det på Google Scholar, människa,

`bb({body:"scream_b_1"})`

b: OCH SLUTA SPRIDA OVETENSKAPLIGA FEJKNYHETER

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_narcissist

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Du *måste* kunna ödmjukt se dina egna brster för att kunna växa som person!

`bb({body:"two_up", eyes:"suspect"})`

b: Du kan inte spreja §air freshener§ över ett mögligt rum! Att täcka upp dina brister gör dig bara bara sämre över tid.

`bb({body:"chest", mouth:"smile", eyes:"closed"})`

b: Tack och lov kan jag, som did lojala vakt-varg, kan jag upplysa dig om dina brister. Och just nu, är det-

`bb({body:"scream_b_1"})`

b: ALLT. ALLT ÄR FEL
```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_racist

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: Amerikas ursprungsbefolkning är ett *faktiskt folk*, inte några "ädla vildar" som du kan namedroppa för att göra dina lyckokakoråd mer *exotiska*.

`bb({eyes:"suspect_r"})`

b: Du reducerar indiviiduella personer & komplexa kulturer till en stämpel! Det är "välvillig rasism"! 

`bb({body:"scream_b_1"})`

b: SLUTA VARA RASISTISK DITT KIS-ÖGDA KRÄK

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2e

h: ^RÖVSATAN^.

`hong({body:"yell", mouth:"yell"})`

h: Vet du vad? Du är *irrationell*.

h: Alla vet att känslor är irrationella! Speciellt rädsla!

`hong({body:"facepalm_2"})`

h: Du är en värdelös evolutionär restprodukt, som min blindtarm eller visdomstand!

`hong({body:"yell", mouth:"yell"})`

h: §^Hell^§, hela denna varg-metaforen är korkad! Du är bara en hög neurokemikalier i mitt huvud.

`hong({body:"cross", mouth:"cross"})`

h: Så varför skulle jag lyssna på en värdelös, irrationell, icke-existerande hög av ^skit^ som §du/dig§?!

`bb({eyes:"sad", MOUTH_LOCK:true})`

b: ...

[Jisses, människa. Det var riktigt sårande.](#act2e_hurtful)

[Jag är en känsla. Känslor är giltiga.](#act2e_valid)

[Människa, vi är *båda* "bara kemikalier."](#act2e_rational)

# act2e_hurtful

`bb({body:"chest"})`

b: Jag är en *del* av dig, du vet. När du säger så, så gör du *dig själv* illa.

`bb({body:"scream_a_1"})`

b: Varför slår du dig själv, människa? SLUTA SLÅ DIG SJÄLV.

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2e_rational

`bb({body:"normal", mouth:"normal", eyes:"normal_r"});`

b: Your deepest motivations are dopamine, your richest joys are serotonin.

`bb({body:"one_up"});`

b: Your memories are synaptic weights, your reason is fault-prone electrical signals.

`bb({eyes:"normal", body:"normal"});`

b: So if me being "just chemicals" means *I'm* irrational... then that means *you're* irrational!

`bb({body:"two_up", eyes:"shock"});`

b: And if we're *both* irrational, then we'll *never* figure out how to be fulfilled and happy!

`bb({body:"scream_a_1"})`

b: AHHH WE'RE BROKEN! SO BROKEN SO BROKEN SO BROKEN--

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2f)

# act2e_valid

`bb({body:"normal", mouth:"normal", eyes:"suspect"});`

b: Hang on... "they" say that feelings are valid, that you should always accept your emotions.

`bb({eyes:"suspect_r"});`

b: But "they" also say emotions are irrational, that emotions are not to be trusted.

`bb({eyes:"angry"});`

b: Oh my gosh, "they" have been lying to us this whole time!

`bb({body:"scream_a_1"})`

b: "DE" MATAR OSS MED MOTSÄGELSER FÖR ATT GÖRA OSS BEROENDE AV §SJÄLVHJÄLPS INDUSTRIELLA KOMPLEXET§.
```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2f

`hong({body:"defeated", MOUTH_LOCK:true});`

h: ...

h: Jag hatar det här. Gud det gör så ont jag *hatar* det här.

h: Jag kan inte tillfredställa dig. Jag kan inte ignorera dig. Jag kan inte slåss mot dig. 

`bb({eyes:"suspect"});`

h: Oavsätt vad jag gör, Verkar jag inte kunna göra mig av med di--

`bb({body:"cry_1"});`

b: Jamen du kanske INTE *SKA* GÖRA DIG AV MED MIG.

`bb({body:"cry_2"});`

b: Hur tror du *jag* känner mig, människa?!

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: Jag gör mitt bästa för att vara din vakthund, men du ser alltid mig som någon Stor Stygg Varg!

b: Så jag försöker *ännu mer* att uppmärksamma dig om fara! *Mer* fara! *Annan* fara!

`bb({eyes:"cry_2"})`

b: Men oavsätt hur mycket jag försöker skydda dig, tror du *fortfarande* att jag är din fiende!

`bb({body:"cry_5"});`

b: Vad gör jag för fel?!

`bb({body:"cry_2"});`

b: Jag *vet* att jag suger på mitt jobb. Men jag *försöker* människa!

`bb({body:"cry_3"});`

b: ...Jag försöker.

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: Du behöver inte §heed my warnings§, eller ens hålla med, eller ens *gilla* mig.

`bb({eyes:"cry_r_2"});`

b: Jag bara... allt jag vill är att du har tålamod med mig.

`bb({eyes:"cry_r_3"});`

b: Jag vill bara att du sitter med mig ett tag, istället för att vända dig bort och--

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: Tja.

```
hong({body:"look"});
Game.clearText();
publish("act2-in-2");
publish("hp_hide");
music('party1', {volume:0.4, fade:2});
```

(...2000)

```
publish("act2",["party_hunter",2]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Ser ut som du är fast i en fight dig själv, §kompis/pyret§.

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: Var det så uppenbart?

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: Du, öh, mumlade något till din tröja om {{_.a2_hoodie_callback}} eller något.

```
publish("act2",["party_hunter",13]);
publish("act2",["party_hong",15]);
sfx("rustle", {volume:0.6});
setTimeout(function(){
	publish("act2",["party_hong",16]);
	sfx("concrete_step3", {volume:0.6});
},401);
setTimeout(function(){
	publish("act2",["party_hong",17]);
	sfx("concrete_step4", {volume:0.6});
},801);
```

h2: åh gud jag är ett sånt vrak.

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: Hörru. Du är inte ensam, kompis. Ångest är supervanligt.

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: §Heck§, bara igår, hörde jag att någon på campus hadde ett nervöst sammanbrott och mosa sin mobil!
{{/if}}

{{if _.act1_ending=="flight"}}
r: §Heck§, bara igår, hörde jag att någon kröp ihop i en bältdjursboll och grät §offentligt§!
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: §Listen§: Jag vet hur det känns att ha det där djuret i huvet.

```
publish("act2",["party_hunter",8]);
```

r: Det gör *vi alla*. Det är därför jag §throw these parties§ varje helg, för att glömma våra oroligheter, glömma det där djuret.

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: men min ångest...

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: Oroa dig inte, pyret. Jag brukade vara som du. Men sen kom jag på ett litet trick för att få den där negativa röstan att hålla klaff för evigt...

```
publish("act2",["party_hunter",3]);
Game.clearText();
music(null, {fade:1});
```

(...2001)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",22]);
sfx("rustle");
```

(...2501)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",23]);
sfx("rustle2");
```

(...1001)

```
publish("act2",["party_hunter",11]);
```

r: Min egna specialblandning. Den är något starkare än... tja, allting lagligt egentligen.

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: Botten up, ^bee-yatch^!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[Åh Herregud.](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[Det här är en dålig coping-mekanism.](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[Ta inte emot drycker från främlingar.](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: §O--

(#act2g)

# act2g_2

b: T--

(#act2g)

# act2g_3

b: D--§

(#act2g)

# act2g

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"forward", mouth:"forward"});
bb({body:"frazzled", mouth:"frazzled", eyes:"frazzled"});
```

h: Mmm, en sådan förträfflig profil!

h: En fyllig §flavor§ av "§shut your mind up§," med en subtil eftersmak av "Känn aldrig något någonsin igen"!

b: Det här är illa, människa. Det här är riktigt, riktigt illa.

[This is *actually* how addiction starts.](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[Jag *visste* att värden var djupt §störd§!](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[Också, de skulle kunna ha drogat det!](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: This is *actu*--§

(#act2h)

# act2h_opt2

b: Också, de sku--

(#act2h)

# act2h_opt3

b: Jag *visste* a--

(#act2h)

# act2h

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"back", mouth:"back"});
bb({body:"panicked", mouth:"panicked", eyes:"panicked"});
```

h: Utsökt, *och* billigare än terapi!

b: MÄNNISKA SNÄLLA SLUTA

h: Hehehe!

h: Och vad tänker *du* göra åt det, §^asshole^§?

b: Jag är så ledsen, människa.

b: Jag kommer behöva använda min SPECIALATTACK

```
bb({body:"special_a"});
music('battle', {volume:0.5});
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act2h_attack) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act2h_attack) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act2h_attack) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`

# act2h_attack

```
bb({body:"special_b_1"});
hong({body:"forward", mouth:"forward"});
sfx("charging");
```

h: Vad är det här för ^skit^?

h: Du tänker gnälla mer korkade *ord* mot mig för att--

```
bb({body:"special_c"});
sfx("hadouken");
```

(...901)

(#act2i)

# act2i

```
publish("hide_tabs");
publish("show_special_attack");
Game.FORCE_CANT_SKIP = true;
music(null);
stopAllSounds();
```

(...5000)

```
publish("show_tabs");
hong({ body:"final", mouth:"final" });
bb({ body:"normal", mouth:"normal", eyes:"sad" });
attack("100p", _.SPECIAL_ATTACK);
Game.FORCE_CANT_SKIP = false;
setTimeout(function(){
	publish("remove_special_attack");
},30);
```

(...2500)

h: VAD I ^HELVETE^ VAR DET DÄR

b: Jag är ledsen. Jag behövde visa dig konsekvenserna.

{{if _.SPECIAL_ATTACK=="harm"}}
h: JAG KUNDE *SE* MITT EGET LIK. JAG KUNDE *KÄNNA* KÄNSLAN AV ATT FAKTISKT VARA DÖD.
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: JAG KUNDE *SE* ALLAS BLICKAR AV AVSKY. JAG KUNDE *HÖRA* ALLT DE SA.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: JAG KUNDE *HÖRA* KRASET AV REVBEN. JAG KUNDE *SMAKA* BLODET I LUFTEN.
{{/if}}

b: jag är ledsen, människa.

n: §*FINISH THEM*§

[{KAMP: Slå värden.}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{FLYKT: Vi sticker härifrån.}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: Den där psykopaten höll på att utnytja dig.

b: De försökte korrumpera dig, göra dig lika §störd§ som dem!

`bb({ body:"yell_angry_1" });`

b: Slå den jäveln! §Knock their friggin' lights out!§

`bb({ body:"final_1" });`

b: SLÅ DEM SLÅ DEM SLÅ DEM SLÅ DEM SLÅ DEM SLÅ DEM SLÅ DEM SLÅ DE--

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: Jag *visste* att alla dessa §partygoers§ var djupt §störda§. De dämpar alla sin smärta med hemska saker!

`bb({ body:"yell_1" });`

b: Och de lurar dig at göra likadant! De korrumperar dig! Vi behöver §get out§!

`bb({ body:"final_1" });`

b: GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OU--§

`_.a2_ending = "flight";`

(#act2k)

# act2k

```
Game.clearText();
publish("act2-in-4");
publish("hp_hide");
music('party1', {volume:0.6, fade:1.5});
```

(...2001)

```
publish("act2",["party_hong",26]);
sfx("slide");
```

(...1001)

```
publish("act2",["party_hunter",14]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: Mår du bra, pyret?

`publish("act2",["party_hunter",13]);`

{{if _.a2_ending=="fight"}}
(#act2k_fight)
{{/if}}

{{if _.a2_ending=="flight"}}
(#act2k_flight)
{{/if}}

# act2k_fight

```
Game.clearText();
publish("act2",["party_hunter",21]);
publish("act2",["party_hong",33]);
music(null);
sfx("hit");
```

(...1000)

```
sfx("record_scratch");
publish("act2",["party_hunter",22]);
publish("act2",["party_hong",34]);
publish("act2",["dee",6]);
publish("act2",["dum",6]);
```

r: D-du...

```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: är *kinky*.

r: Jag gillar det. Kom till min fest nästa helg, sötnos.

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: ok hej då, ciao, adios, au revoir

r: Djuret må ha vunnit idag, men kom tillbaka, och så mixar jag något ännu starkare åt dig!

h2: sayōnara, auf wiedersehen, zài jiàn, shalom, §see ya§

r: Du och jag, pyret, vi visar besten vem som är boss!

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: ok ledsen jag måste springa

`publish("act2",["party_hunter",16]);`

r: ^Fan^ då. Djuret vann idag, §huh§?

`publish("act2",["party_hunter",15]);`

h2: nej nej, måste bara, öh, springa marathon. §gotta go fast§.

`publish("act2",["party_hunter",19]);`

r: Kom till min fest nästa helg, sötnos. Jag blandar ihop något ännu starkare åt dig.

h2: ok tack måste springa springa springa springa springa

r: Du och jag, pyret, vi visar besten vem som är boss!

(#act2k_end)

# act2k_end

```
Game.clearText();
publish("act2-out-5");
publish("act2-outro", ["end1"]);
music("hum", {fade:2, volume:0.6});
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2500)

```
publish("act2", ["act2_end",2]);
sfx("whoosh");
```

(...1000)

b: Människa! Mår du bra?!

```
publish("act2", ["act2_end","next"]);
```

b: §Gosh§, Det var *Nära.* Vi kunde verkligen ha--

```
Game.clearText();
publish("act2", ["act2_end","next"]);
music(null);
sfx("squeak");
```

(...1500)

```
publish("act2", ["act2_end","next"]);
sfx("hit");
```

(...1000)

h: Jag kommer tillbaka till festen nästa vecka.

h: Nästa gången vi §slåss§, ska jag inte bara *besegra* dig...

h: Jag kommer att §^fuck^ing§ *döda* dig.

```
Game.clearText();
publish("act2", ["act2_end","next"]);
sfx("concrete_step1");
````

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step2", {volume:0.8});
```

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step3", {volume:0.5});
```

(...901)

`sfx("concrete_step4", {volume:0.25});`

(...3000)

`_.INTERMISSION_STAGE = 2;`

(#intermission)

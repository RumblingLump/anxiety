# act3

```
SceneSetup.act3();
Game.WORDS_HEIGHT_BOTTOM = 205;
sfx("cheers");
```

r: Skål!

```
publish("act3",["roofhunter",1]);
publish("act3",["roofhong",1]);
sfx("drinking");
```

(...4001)

```
publish("act3-alpha", ["dizzyhunter",1]);
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",3]);
```

h2: *Ah* det satt på sin plats.

```
publish("act3",["roofhunter",2]);
publish("act3",["roofhong",2]);
```

r: Du vet, pyret...

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",6]);
```

h2: Specifikt, platserna det satte sig är min vänstra och högra amygdala.

```
publish("act3",["roofhunter",8]);
publish("act3",["roofhong",5]);
```

r: Du påminner mig om mig själv när jag var yngre. Då när jag var plågad av djuret i mitt huvud.

```
publish("act3",["roofhunter",9]);
publish("act3",["roofhong",2]);
```

r: Jag är så tacksam att jag kan föra det vidare, och hjälpa dig döda besten på samma sätt jag dödade min.

```
publish("act3",["roofhunter",2]);
```

r: Du, snabb fråga: sanning eller ko--

```
publish("act3",["roofhunter",3]);
publish("act3",["roofhong",7]);
publish("act3-alpha", ["dizzyhong",0]);
```

h2: §KONSEKVENS/KONKA§!

```
publish("act3-alpha", ["dizzyhong",1]);
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",2]);
```

r: Haha! Bra.

```
publish("act3",["roofhunter",21]);
publish("act3",["roofhong",4]);
```

r: Ok. Du ser den där §baby-blue§ swimming-poolen där nere?

```
publish("act3-alpha", ["dizzyhong",0]);
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",9]);
```

h2: Ja? Sex våningar ner?

```
publish("act3",["roofhunter",10]);
publish("act3",["roofhong",8]);
```

r: Hoppa i.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",10]);
```

h2: ...

```
publish("act3",["roofhong",11]);
```

h2: Vänta, va?

```
publish("act3",["roofhong",10]);
publish("act3",["roofhunter",2]);
```

r: Djuret har börjat gnälla, inte sant?

```
publish("act3",["roofhunter",23]);
```

r: *Åh neeeej det är farligt, gör det inteeeee.*

```
publish("act3",["roofhunter",22]);
```

r: Men det är exakt varför vi behöver §death-defying thrills! Party hard!§ Carpe diem! Snorta kokain från en horas ^röv^, #YOLO!

```
publish("act3",["roofhunter",10]);
```

r: Visa det där djuret att vi inte ger två *^kukfan^* om dets gnölande! Hoppa i.

```
publish("act3",["roofhunter",11]);
publish("act3",["roofhong",13]);
```

h2: Öh, men ibland, hm... har rädslan en poäng...

```
publish("act3",["roofhunter",5]);
publish("act3",["roofhong",12]);
music(null, {fade:2});
```

r: ...

```
publish("act3-alpha", ["dizzyhunter",0]);
publish("act3",["roofhunter",6]);
publish("act3",["dd",1]);
```

r: Åh förlåt, föll du för den där McMindfulness propagandan som säger att §feeling bad is *good*?§

```
publish("act3",["roofhunter",17]);
```

r: De svinen som §run this world§ ger resten av *oss* ångest och depression,

```
publish("act3",["roofhunter",18]);
```

r: Then make TED Talks to tell us to "accept" being ^fucked^ over, and "embrace" that sadistic demon in our heads!

```
publish("act3",["roofhunter",6]);
```

r: Pyret, jag vet att *du* vet att det där djuret *skadar* sådana som oss. Det *torterar* sådana som oss.

```
publish("act3",["roofhunter",19]);
```

r: Det är inte vår vän. Det är en rabiat best, som antingen behöver bli *sövd*,

```
publish("act3",["roofhunter",20]);
```

r: Eller få en *kula i skallen*.

```
publish("act3",["roofhunter",27]);
```

r: Annars, så låter du den vinna.

```
publish("act3",["roofhunter",31]);
publish("act3",["roofhong",14]);
publish("act3",["dd",2]);
```

h2: Nej. Du har fel.

```
publish("act3",["roofhunter",13]);
publish("act3",["roofhong",15]);
music('battle_dark', {volume:1.0}, function(){
	music('battle_dark_loop');
});
```

h2: Jag kommer inte låta den vinna.

```
publish("act3",["roofhunter",25]);
publish("act3-alpha", ["roofhong",0]);
publish("act3-alpha", ["transition",1]);
publish("act3",["dd",6]);
```

r: ^Fuck^ yeah! I believe in you, babe! Kill it! <3§

(#act3a)



# act3a

```
Game.clearText();
publish("act3-out");
Game.WORDS_HEIGHT_BOTTOM = -1; /* reset */
_.act3_bb_body = 1;
```

(...1500)

```
publish("hp_show");
```

b: nej nej nej nej nej nej

n: DETTA KAPITTEL HAR TVÅ MÖJLIGA SLUT. ETT ÄR *VÄRLDIGT,VÄLDIGT DÅLIGT.*

b: NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ NEJ

n: VÄLJ NOGA. SKYDDA DIN MÄNNISKA

`bb({ eyes:"oh_crap", mouth:"normal_talk", MOUTH_LOCK:true });`

b: AAAAAAAAAAAAAAAAAA

`bb({ mouth:"normal" });`

n: LYCKA TILL

```
Game.clearText();
bb({ eyes:"start" });
```

[Människa, du skulle faktiskt kunna DÖ här!](#act3a_harm) `Game.OVERRIDE_CHOICE_LINE=true`

[Det här är dumt och självdestruktivt!](#act3a_bad) `Game.OVERRIDE_CHOICE_LINE=true`

[Dessa sjuka typerna är egentligen inte dina vänner!](#act3a_alone) `Game.OVERRIDE_CHOICE_LINE=true`

# act3a_harm

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: M--

(#act3a_after)

# act3a_alone

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: D--

(#act3a_after)

# act3a_bad

`bb({ MOUTH_LOCK:true, mouth:"normal_talk" });`

b: D--

(#act3a_after)

# act3a_after

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Du vet, jag kanske hade trott dig... om du inte hade försökt det där en §zillion§ gånger tidigare.

h: Du är vargen som ropade varg.

```
bb({ eyes:"sad" });
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act3_fork) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act3_fork) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act3_fork) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`


# act3_fork

```
Game.clearText();
bb({body:"special_attack"});
sfx("charging");
Game.FORCE_CANT_SKIP = true;
```

(...1001)

```
Game.FORCE_CANT_SKIP = false;
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Du försökte med det också.

b: människa, snälla...

`hong({ eyes:"look_right" });`

h: Åh jag *beklagar* att Big Pharma inte uppskattar min självmedicinering.

h: Look ^asshole^, we *all* have a way of shutting you the ^fuck^ up.§

`hong({ body:"look_up", eyes:"look_up" });`

h: Vissa personer kastar sig in i sitt arbete.

`hong({ body:"look_down", eyes:"look_down" });`

h: Vissa personer kastar sig in i sex, droger, och §refreshing§ sin Facebook-feed.

`hong({ body:"normal", eyes:"look_right" });`

h: Vissa personer kastar sig in i andra personer.

`hong({ eyes:"angry" });`

h: Jag ska kasta mig själv in i den där swimming-poolen.

[Du är full och det är SEX VÅNINGAR NED](#act3_bad_1_harm)

[Attans, det här är det tacket jag får?!](#act3_bad_1_insult) `bb({eyes:"angry"});`

[Okej, jag erkänner det. Jag strulade till det.](#act3_good_1) `bb({mouth:"sorry", eyes:"sorry_down"});`

# act3_bad_1_harm

b: Även om du landar i vattnet, kommer ytspänningen knäcka dina revben och ge dig en hjärnskakning *minst!*

h: Äh.

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

h: Jag såg en rysk snubbe göra det här på YouTube en gång.

(#act3_bad_2)

# act3_bad_1_insult

`hong({ eyes:"look_right" });`

h: Jag- Ursäkta mig, *tacket*?

`bb({ eyes:"angry" });`

b: Det här är precis varför jag *existerar!* För att människor inte kan förlitas med att skydda sig själva!

b: Jag har försökt skydda din dumma §butt§ hela mitt liv och nu tänker du b--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)

# act3_good_1

`hong({ body:"laugh_1" })``

h: heh.

`hong({ body:"laugh_2" })``

h: hahahaha

`hong({ body:"laugh_3" })``

h: HAHAHAHAHAHA

```
bb({ eyes:"sorry"});
hong({ body:"yell_1", mouth:"yell", eyes:"blank" });
```

h: Åh WOW är det århundradets största *^djävl^a* underskott!

`hong({ body:"yell_2" });`

h: Ja, din ruttna hög av blodtäckt ^skit^! Du strulade ^§fanemig§^ till det!

`hong({ body:"normal", mouth:"angry", eyes:"angry" });`

h: Några andra anmärkningar, Captain Obvious?

[Men hämnd på mig är inte svaret!](#act3_good_1_fail_revenge) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Men den här gången har jag *faktiskt* rätt!](#act3_good_1_fail_harm) `bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });`

[Jag har §skadat§ dig.](#act3_good_2a)


# act3_good_1_fail_revenge

b: Du behöver ha en hälsosammare relation till dina känslor, istället för att dränka dem me--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)



# act3_good_1_fail_harm

b: Så snälla, ställ ned flaskan och låt o--

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("32p");
_.act3_bb_body++;
```

(...2000)

```
hong({ body:"normal", mouth:"angry", eyes:"angry" });
bb({ body:"normal_"+_.act3_bb_body, mouth:"normal", eyes:"normal" });
```

(#act3_bad_2)




# act3_bad_2

`bb({ eyes:"sad" });`

b: snälla... nej...

h: Your energy bar's looking awfully low there, wolf.§

h: Om jag vore du, skulle jag välja dina nästa ord väldigt noga.

`bb({ eyes:"normal" });`

[Visst. Jag är färdig med att skydda dig.](#act3_bad_2_jump) `bb({ mouth:"ignore", eyes:"ignore" });`

[Jag hade rätt hela tiden.](#act3_bad_2_right)

[Förlåt.](#act3_good_2b) `bb({mouth:"sorry", eyes:"sorry_down"});`


# act3_bad_2_jump

b: Så, §go ahead§ och hoppa. Se om jag bryr mig.

`hong({ eyes:"look_right", mouth:"normal", MOUTH_LOCK:true });`

h: ...

```
hong({ eyes:"less_angry", mouth:"normal" });
bb({ eyes:"ignore_oh_crap" });
```

h: Okej då. Botten upp.

```
bb({ mouth:"normal", eyes:"oh_crap" });
Game.OVERRIDE_TEXT_SPEED = 2;
```

b: VÄNTA NEJ DET VAR OMVÄND PSYKOLOGI DET VAR MENINGEN ATT DU SKULLE GÖRA *MOTSATSEN*MOT VAD JAG S--

(#act3_bad_3)



# act3_bad_2_right

`bb({ eyes:"angry" });`

b: You *are* putting yourself in danger. Your so-called friends *are* using you. And *you* are using your so-called friends.§

`bb({ eyes:"sad" });`

b: Så snälla, människa... varför tror du inte på mig?!

h: För att du aldrig trodde på *mig*.

(#act3_bad_3)


# act3_bad_2_terrible

`bb({ eyes:"angry" });`

b: Andra vakt-vargar har människor som §actually take time to patiently train them, to *learn* to work together,§

b: Iställer för att hata vakt-vargen för att den försöker skydda dem! Så varför kan du inte bar--

`bb({ eyes:"normal" });`

h: Fel ^jävl^a svar.

(#act3_bad_3)



# act3_bad_3

```
music(null);
hong({body:"drink"});
bb({body:"attacked"});
publish("bb_STOP_VIBRATING");
attackBB("100p");
```

(...2000)

```
hong({ body:"normal", mouth:"normal", eyes:"normal" });
bb({ body:"dead" });
```

(...999)

h: *"Det enda vi har att frukta är fruktan själv."*

`hong({ body:"look_up", mouth:"happy", eyes:"blank" });`

h: *"Don't worry, be happy!"*§

`hong({ body:"normal", mouth:"normal", eyes:"normal" });`

h: All the wise folk of our time agree: negative emotions are *bad!*§

`hong({ eyes:"less_angry" });`

h: Duh! That's why they're called *negative!*§

b: människa... snälla...

`hong({ eyes:"normal" });`

h: Ett tag sen, sa jag: “jag vill bara vara fri från all denna smärta.”

h: Min önskan blev uppfylld. Jag känner inte längre någon smärta, eller rädsla, eller ångest...

h: Jag känner inte något alls.

`_.a3_ending = "jump";`

(#act3_end)



# act3_good_2a

`bb({mouth:"sorry", eyes:"sorry_down"});`

b: Jag var så besatt av att försäkra att inget annat skulle skada dig, att jag inte insåg att *jag* skapade smärtan.

```
bb({ eyes:"sorry"});
hong({ body:"yell_2", mouth:"yell", eyes:"blank" });
```

h: NO. S^HIT^.§

`hong({ body:"yell_1" });`

h: ^HERREJÄVLAR^. Det tog dig verkligen så här lång tid att äntligen lista ut det?!

`hong({ body:"cry", mouth:"cry", eyes:"blank" });`

h: Du kunde ha §saved us so much trouble, you big fluffy dumb^ass^. Why didn't you realize this sooner?§...

`_.apologized_for_hurt = true;`

(#act3_good_2q)



# act3_good_2b

`hong({ body:"normal", mouth:"angry", eyes:"look_right" });`

h: ...*Förlåt.*

`hong({ eyes:"angry", MOUTH_LOCK:true });`

h: ...

h: Förlåt för *vadå*?

(#act3_good_2q)


# act3_good_2q

`bb({mouth:"sorry", eyes:"sorry"});`

{{if _.apologized_for_hurt}}
(#act3_good_2q_already_apologized)
{{/if}}

{{if !_.apologized_for_hurt}}
(#act3_good_2q_not_already_apologized)
{{/if}}


# act3_good_2q_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"less_angry" });`

[Förlåt att jag inte var en bra beskyddare.](#act3_good_3_protector)

[Förlåt att jag inte respekterade dig.](#act3_good_3_respect)

[Förlåt.](#act3_good_4)


# act3_good_2q_not_already_apologized

`hong({ body:"normal", mouth:"angry", eyes:"angry" }, 0);`

[Förlåt att jag har en så förfärlig människa!](#act3_bad_2_terrible) `bb({mouth:"normal", eyes:"normal"})`

[Förlåt att jag inte respekterade dig.](#act3_good_3_respect)

[Förlåt att jag §sårade/skadade§ dig.](#act3_good_3_hurt)



# act3_good_3_protector

`bb({eyes:"sorry_down"});`

b: Det är min plikt attskydda dig mot *riktig* fara, men jag fortsatte skälla mot bilar och brevbäraren.

`bb({eyes:"sorry_up"});`

b: Skälla mot skuggor. Skälla så mycket.

`bb({eyes:"sorry"});`

b: Det är bara logiskt att du skulle vilja munkavla mig.

`bb({eyes:"sorry_down"});`

b: Förlåt.

(#act3_good_4)



# act3_good_3_respect

`bb({eyes:"sorry_down"});`

b: Jag var menad att vara *din* lojala vakthund, men jag agerade som om du skulle lyda *mig*.

`bb({eyes:"sorry_up"});`

b: Det är skillnad mellan en beskyddare och en fångvaktare, och jag gick över gränsen.

`bb({eyes:"sorry_down"});`

b: Förlåt.

(#act3_good_4)



# act3_good_3_hurt

`bb({eyes:"sorry_down"});`

b: Jag var så besatt med att försöka skydda dig från att skadas, att jag aldrig stannade upp och insåg att *jag* skadade dig.

`bb({eyes:"sorry_up"});`

b: I was a bad dog.§

`bb({eyes:"sorry_down"});`

b: I'm sorry.

(#act3_good_4)


# act3_good_4

```
music(null,{fade:3});
hong({ eyes:"less_angry", MOUTH_LOCK:true },0);
```

h: ...

```
hong({ body:"stop", mouth:"stop", eyes:"blank" });
```

h: Yeah, well, this was a dumb idea anyway.

h: I only did this to mess you up, and, well, I messed you up.

h: Let's just call this round a tie, okay?

```
bb({ mouth:"sorry", eyes:"sorry" });
bb({ MOUTH_LOCK:true });
```

b: ...

b: Okay.

h: Okay.

n: *TIE*

`_.a3_ending = "walkaway";`

(#act3_end)









# act3_end

```
Game.clearText();
publish("act3-in");
publish("hp_hide");
Game.FORCE_CANT_SKIP = true;
```

{{if _.a3_ending=="walkaway"}}
(#act3_walkaway)
{{/if}}

{{if _.a3_ending=="jump"}}
(#act3_jump)
{{/if}}






# act3_walkaway

```
publish("start-walkaway-anim");
Game.WORDS_HEIGHT_BOTTOM = 205;
```

(...3501)

```
sfx("bottle_toss");
publish('hong-next');
publish("act3",["roofhunter",7]);
```

(...667)

```
publish("act3",["dd",4]);
publish("act3",["roofhunter",26]);
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("concrete_step2");
```

(...667)

```
publish('hong-next');
publish("act3",["roofhunter",27]);
```

`Game.FORCE_CANT_SKIP = false;`

r: Oh *come on*. After all that animal's done to you, you're just *giving up?*

r: What's the matter, kid? Are you *scared?*

```
publish('hong-next');
publish("act3",["roofhunter",26]);
```

h2: Yes.

h2: I'm scared.

`publish('hong-next')`

h2: And that's okay!

`publish('hong-next')`

h2: It's okay to be scared.

`publish('hong-next')`

(...500)

```
Game.clearText();
Game.FORCE_CANT_SKIP = true;
```

(...1167)

```
publish('hong-next');
```

(...833)

```
publish('hong-next');
sfx("rustle2");
```

(...1333)

```
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",31]);
sfx("concrete_step4");
```

(...667)

```
publish('hong-next');
sfx("concrete_step1");
```

(...667)

```
publish('hong-next');
sfx("door");
```

(...1333)

```
publish('hong-next');
sfx("concrete_step2");
```

(...501)

```
publish('hong-next');
Game.FORCE_CANT_SKIP = false;
sfx("lock_door");
publish("act3",["roofhunter",32]);
```

(...2001)

```
publish("act3",["roofhunter",33]);
```

r: Did they just lock the door?

```
Game.clearAll();
_.INJURED = false;
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2000)

(#act4)




# act3_jump

```
publish("start-jump-anim");
Game.FORCE_TEXT_Y = 300;
```

(...2001)

```
publish('hong-next');
sfx("bottle_toss");
```

(...833)

```
sfx("concrete_step1");
sfx("claps");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",28]);
```
(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step2");
publish('hong-next');
publish("act3",["roofhunter",28]);
```

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

`publish("act3",["roofhunter",28]);`

(...125)

`publish("act3",["roofhunter",29]);`

(...125)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",5]);
publish("act3",["roofhunter",34]);
```

(...1167)

```
sfx("rustle2");
publish('hong-next');
```

(...1001)

`publish('hong-next')`

b: no...

(...501)

`Game.clearText();`

`publish('hong-next')`

(...1333)

```
sfx("quack");
publish('hong-next');
```

(...1333)

`publish('hong-next')`

b: no no no

(...501)

`Game.clearText();`

`publish('hong-next')`

(...2001)

```
sfx("rustle2");
publish('hong-next')
```

(...501)

```
sfx("concrete_step1");
publish('hong-next');
publish("act3",["dd",4]);
publish("act3",["roofhunter",30]);
```

(...167)

```
sfx("concrete_step2");
publish('hong-next');
```

(...167)

```
sfx("concrete_step3");
publish('hong-next');
publish("act3",["dd",2]);
publish("act3",["roofhunter",15]);
```

(...167)

```
sfx("bottle_slip");
publish('hong-next');
publish("act3",["dd",3]);
publish("act3",["roofhunter",16]);
```

(...833)

```
sfx("rustle");
publish('hong-next');
```

(...167)

`publish('hong-next')`

(...167)

```
publish('hong-next');
Game.FORCE_TEXT_Y = 325;
Game.OVERRIDE_FONT_SIZE = 50;
```

b: NO!

(...400)

```
Game.WORDS_HEIGHT_BOTTOM = -1;
Game.FORCE_TEXT_Y = -1;
Game.clearText();
publish("act4-injury-show");
publish("hide_tabs");
```

(...2000)

```
sfx("hospital1");
publish("act4-injury", [1]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital2");
publish("act4-injury", [2]);
```

(...4000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...2000)

```
sfx("hospital3");
publish("act4-injury", [3]);
```

(...8000)

```
stopAllSounds();
publish("act4-injury", [0]);
```

(...5500)

`_.INJURED = true;`

(#act4)

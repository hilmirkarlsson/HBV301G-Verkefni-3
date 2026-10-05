# Viðskiptamarkmið, framtíðarsýn og Minimum Viable Product 

**Verkefni 3 — Vision and Scope**

**Heiti kerfis:** Settið

**Teymi og höfundar:** Teymi 1 — Hilmir Karlsson og Silja Ástudóttir

**Git repository:** https://github.com/hilmirkarlsson/HBV301G-Verkefni-3

## Efnisyfirlit

1. [Viðskiptamarkmið](#1-viðskiptamarkmið)
2. [Framtíðarsýn](#2-framtíðarsýn)
3. [Prófíll mikilvægra notenda](#3-prófíll-mikilvægra-notenda)
4. [Forgangsröðun verkefnisins](#4-forgangsröðun-verkefnisins)
5. [Umfang fyrstu útgáfu (MVP)](#5-umfang-fyrstu-útgáfu-mvp)

## 1. Viðskiptamarkmið

**Vandamál og tækifæri:** Margir sem byrja í ræktinni muna ekki hvað þeir lyftu síðast, vita ekki hvað er á dagskrá og sjá ekki hvort þeir eru að bæta sig. Æfingaöpp eru oft prófuð í viku og gleymd. Settið á að gefa fólki ástæðu til að opna appið á hverri æfingu og til að segja vinum frá því. 
Út frá þessum vandamálum eru skilgreind þrjú mælanleg viðskiptamarkmið: að notendur haldi áfram að nota Settið, að notendum fjölgi án greiddra auglýsinga og að notendur sjái eigin framfarir.

### BO-1: Fólk heldur áfram að nota Settið — 40% haldtala innan sex mánaða frá útgáfu

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Hlutfall nýrra notenda sem skrá enn að minnsta kosti eina æfingu í viku, mánuði eftir að þeir byrjuðu að nota appið |
| Mæliaðferð (Meter) | Nafnlaust, tilfallandi auðkenni sem búið er til við uppsetningu og notandi kveikir sjálfur á. Þjónninn fær aðeins tvær tölur: fjölda nýrra auðkenna í viku og fjölda þeirra sem skrá æfingu mánuði síðar. Engin æfingagögn fara úr símanum (lausn árekstrar í Verkefni 2) |
| Fyrri staða (Past) | Ekki þekkt enn, því Settið er ný vara. Hún mælist fyrstu vikurnar eftir útgáfu með sömu mælingu |
| Markmið (Goal) | 40% nýrra notenda skrá enn amk eina æfingu í viku, mánuði eftir að þeir byrja að nota Settið, innan sex mánaða frá útgáfu |
| Metnaðarmarkmið (Stretch) | 50% |
| Tengsl við fyrri verkefni | BREQ-1 úr V1, eiginleikar F-1 og F-3, þarfir lyftara og þróunarteymis úr V2. Fyrirvari: aðeins þeir sem kveikja á mælingu eru taldir, svo talan getur verið hærri en raunveruleg haldtala |

### BO-2: Fleiri byrja að nota Settið án auglýsinga — 10% fjölgun nýrra notenda á mánuði

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Prósentufjölgun nýrra notenda milli mánaða, án greiddra auglýsinga |
| Mæliaðferð (Meter) | Sama nafnlausa auðkennið og í BO-1: þjónninn telur fjölda nýrra auðkenna á mánuði og ekkert annað fer úr símanum (lausn árekstrar í Verkefni 2). Engar auglýsingar eru keyptar, svo allur vöxtur er án auglýsinga |
| Fyrri staða (Past) | Ekki þekkt enn, því Settið er ekki komið út. Hún verður til við fyrsta fulla mánuðinn eftir útgáfu og mánuðirnir á eftir bera sig saman við hann |
| Markmið (Goal) | Að minnsta kosti 10% fjölgun nýrra notenda í hverjum mánuði innan sex mánaða frá útgáfu |
| Metnaðarmarkmið (Stretch) | 15% á mánuði |
| Tengsl við fyrri verkefni | BREQ-2 úr V1 og eiginleikar F-2 og F-3. Samkvæmt BREQ-2 segir sá sem slær met eða veit loksins hvað hann á að gera vinum sínum frá appinu. Fyrirvari: aðeins þeir sem kveikja á mælingu eru taldir, svo talan getur verið lægri en raunveruleg fjölgun. |

Ath. þetta viðskiptamarkmið byggist á þeirri forsendu að virði sem notendur upplifa, þ.á.m. framfarir og persónuleg met, leiði til meðmæla og náttúrulegrar fjölgunar notenda. Markmiðið mælir niðurstöðuna, fjölgun notenda, en ekki meðmælin sjálf.

### BO-3: Notendur sjá að þeir eru að bæta sig — 70% innan sex mánaða frá útgáfu

| Atriði | Lýsing |
|---|---|
| Mælikvarði (Scale) | Hlutfall notenda sem hafa skráð æfingar í þrjá mánuði og svara því játandi að þeir sjái í appinu að þeir séu að bæta sig |
| Mæliaðferð (Meter) | Ein valfrjáls könnunarspurning í ytra könnunartóli, sem appið vísar á eftir þrjá mánuði. Engin æfingagögn fara úr símanum og þjónninn fær ekkert nýtt (C-2 og BRG-1 haldast) |
| Fyrri staða (Past) | Ekki þekkt enn. Hún mælist með því að spyrja sömu spurningar fólk sem lyftir í dag og skráir æfingarnar sínar annars staðar, t.d. í minnisbók í símanum |
| Markmið (Goal) | 70% þeirra sem svara |
| Metnaðarmarkmið (Stretch) | 85% þeirra sem svara |
| Tengsl við fyrri verkefni | F-3, UR-2 og UR-5 úr V1 og hópurinn „Sér engar framfarir“ í V2. Þeir sem sjá framfarir hafa ástæðu til að halda áfram (BO-1) og segja vinum frá (BO-2). Fyrirvari: þeir sem svara eru líklega ánægðari en hinir |


## 2. Framtíðarsýn

Settið er fyrir fólk sem lyftir í ræktinni, allt frá byrjendum til þeirra sem slá met. Það vill muna hvað það gerði síðast, vita hvað er á dagskrá í dag og sjá hvernig það er að bæta sig. Settið er einfalt æfingaapp sem heldur utan um æfingar, plan og framfarir svo notandinn hafi góða yfirsýn og geti æft markvissar. Ólíkt minnisbókinni í símanum þar sem notandinn þarf sjálfur að halda utan um fyrri æfingar og þróun safnar Settið því sem skiptir máli á einn stað. Það gefur fólki ástæðu til að nota appið reglulega, svo það haldi áfram að nota Settið (BO-1), segi vinum sínum frá því (BO-2) og sjái að það sé að bæta sig (BO-3).

## 3. Prófíll lykilhagsmunaaðila eða mikilvægra notenda

**Val á notendahópi:** Við veljum Methafann, einn af notendahópunum fjórum í [Verkefni 2](https://github.com/hilmirkarlsson/HBV301G-Verkefni-2/blob/main/STAKEHOLDERS.md), og persónuna Aron Bjarkason sem er fulltrúi hans. Hann skiptir mestu máli fyrir fyrstu útgáfuna vegna þess að þarfir hans, hröð skráning, síðasta sett og persónuleg met, eru kjarni vörunnar og tengjast öllum þremur viðskiptamarkmiðunum: hröð skráning heldur honum í appinu (BO-1), met eru það sem hann segir vinum frá (BO-2) og met sýna að hann er að bæta sig (BO-3). Byrjandinn og Ráfarinn þurfa fyrst og fremst plan og leiðbeiningar (F-2), og þeir sem sjá engar framfarir þurfa sömu skráningu og framfaraskjá og Methafinn (F-1 og F-3). 
Þarfir Methafans skarast því við mikilvægar þarfir annarra hópa, sérstaklega hvað varðar skráningu og sýnilegar framfarir. Þróunarteymið er viðskiptavinurinn og á viðskiptamarkmiðin í kafla 1, svo það fær ekki sérstakan prófíl hér.

| Atriði | Lýsing |
|---|---|
| Notendahópur og hlutverk | Methafinn, beinn notandi. Reyndur lyftari sem veit hvað hann er að gera í ræktinni, skráir sett og fylgist með persónulegum metum. Persónan er Aron Bjarkason, dyravörður sem hefur æft lengi |
| Helsta virði (Major value) | Skráir sett á nokkrum sekúndum, sér síðasta sett á sama skjá og sér persónuleg met og framfarir. Fær yfirsýn yfir fyrri árangur og getur æft markvissar án þess að þurfa að muna hvað hann gerði síðast (BO-1, BO-2 og BO-3) |
| Viðhorf (Attitudes) | Þolir ekki flókin viðmót, pop-ups eða óþarfa skref og vill að appið trufli ekki æfinguna. Þarf ekki leiðbeiningar og býst við að appið sé fljótt og einfalt |
| Helstu áhugamál (Major interests) | Hröð skráning (UR-1, QA-1), að sjá hvað hann gerði síðast (UR-2), persónuleg met (UR-6) og að appið virki án nets (SR-1) |
| Takmarkanir (Constraints) | Notar appið í ræktinni milli setta, oft án nettengingar (SR-1). Gögnin eru hans eign og fara ekki á þjón (C-2 og BRG-1). Mæling á notkun er valfrjáls, svo hún má ekki trufla skráninguna (BO-1) |

## 4. Forgangsröðun verkefnisins

Flokkið hverja af fimm víddum verkefnisins sem **drifkraft (Driver)**,
**takmörkun (Constraint)** eða **frjálsleika/frígráðu (Degree of freedom)**.
Rökstyðjið flokkunina með vísun í viðskiptamarkmiðin, framtíðarsýnina
og þarfir og væntingar lykilhagsmunaaðila.

| Vídd | Flokkun | Rökstuðningur |
|---|---|---|
| Eiginleikar | Driver | Viðskiptamarkmiðin ganga út á að fólk haldi áfram að nota appið (BO-1) og segi vinum frá því (BO-2). Það á líka að sjá að það er að bæta sig (BO-3). Til þess þurfa æfingaskráning (F-1) og framfarir (F-3) að virka vel. Æfingaplanið (F-2) hjálpar líka en kemur á eftir. Methafinn úr kafla 3 þarf F-1 og F-3 til að nenna að opna appið á hverri æfingu |
| Gæði | Constraint | Sum gæði eru föst úr Verkefni 1. Aðgerðir klárast á undir 2 sekúndum í 95% tilvika (QA-1). Appið virkar án nets (SR-1). Gögnin eru eign notandans (BRG-1) og aðgengi er eftir WCAG (BRG-2). Methafinn þolir ekki hægt eða flókið viðmót. Við slökum því ekki á þessu |
| Tímasetningar | Degree of freedom | Enginn bíður eftir ákveðnum útgáfudegi. Sex mánaða fresturinn í BO-1 til BO-3 telur frá útgáfu og færist því með henni. Flest æfingaöpp eru prófuð í viku og gleymd (BREQ-1). Ef fólk hættir að nota hálfkláraða útgáfu næst ekki markmiðið í BO-1 um að það haldi áfram að nota appið. Það er betra að gefa út seinna en of snemma. Ef eiginleikar eða gæði taka lengri tíma bíður útgáfan |
| Kostnaður | Constraint | Enginn sérstakur fjárhagsrammi hefur verið skilgreindur fyrir verkefnið, en gert er ráð fyrir að halda rekstrarkostnaði í lágmarki. Appið er ekki með þjón fyrir gögn notandans (C-2). BO-2 gerir ráð fyrir vexti án greiddra auglýsinga. Kostnaður við rekstur og markaðssetningu setur því verkefninu takmarkanir þó föst fjárhæð hafi ekki verið skilgreind |
| Mannafli | Constraint | Við Hilmir og Silja erum tvö. Það breytist ekki. Þess vegna getum við ekki smíðað alla eiginleikana í einu og veljum bara það nauðsynlegasta í fyrstu útgáfuna (kafli 5). Við þurfum líka að láta appið virka fyrir bæði Android og iOS (C-1) |

## 5. Umfang fyrstu útgáfu (MVP)

MVP Settsins er minnsta nothæfa útgáfan sem skilar virði fyrir lykilnotandann, Methafann. Hún leggur áherslu á hraða æfingaskráningu, yfirsýn yfir fyrri árangur og persónuleg met til að styðja við viðskiptamarkmiðin um notendahald, fjölgun notenda og sýnilegar framfarir.

### 5.1 Umfang fyrstu útgáfu (MVP)

| Hvað þarf að vera í MVP? | Hvers vegna? | Tengsl við fyrri verkefni, ef við á |
|---|---|---|
| Skrá sett, endurtekningar og þyngd á einum skjá | Kjarni vörunnar. Ef notandi getur ekki skráð æfingar hratt nær varan ekki tilgangi sínum og styður ekki BO-1 | F-1 Æfingaskráning, UR-1 Skrá sett hratt, FR-1 Skrá sett á einum skjá, FR-2 Muna síðasta sett, FR-3 Næsta sett með einum smelli |
| Sjá síðasta sett í sömu æfingu | Leysir eitt helsta vandamálið sem kom fram í kröfusöfnun, að þurfa að muna fyrri árangur, og hjálpar notanda að æfa markvissar. | UR-2 Sjá hvað ég gerði síðast, FR-4 Sjá hvað notandi tók síðast, FR-5 Sjá hvenær notandi tók æfinguna síðast, FR-6 Sjá hvort settið er þyngra en síðast |
| Persónuleg met | Persónuleg met eru mikilvæg hvatning fyrir Methafann, gera árangur sýnilegan og geta stuðlað að því að notendur segi öðrum frá appinu (BO-2). | F-3 Framfarir, UR-6 Persónuleg met, FR-16 Halda utan um met, FR-17 Láta vita þegar notandi slær met |
| Saga æfinga og sýnilegar framfarir | Nauðsynleg til að notandi geti séð fyrri árangur og fylgst með framförum. Þetta styður beint við BO-3. | F-3 Framfarir, UR-5 Sjá hvort ég er að bæta mig, FR-13 Saga hverrar æfingar, FR-14 Sjá hvort notandi er að bæta sig |
| Virkni án nettengingar | Appið þarf að vera nothæft í ræktinni óháð nettengingu svo skráning og fyrri gögn séu alltaf aðgengileg. | SR-1 Virkar án nets í ræktinni |
| Æfinga- og persónugögn geymd á tæki notanda | Styður persónuvernd, án þess að útiloka valfrjálsa nafnlausa notkunarmælingu. | BRG-1 Notendagögn eign notanda, uppfært C-2, QA-2 Persónuvernd og úrlausn árekstrar úr V2 |
| Hröð skráning og einfalt viðmót | Methafinn þolir ekki flókið eða hægt viðmót. | QA-1 Hröð skráning, UR-1 og þarfir Methafans úr V2 |
| Aðgengilegt notendaviðmót | Aðgengiskröfur gilda frá fyrstu útgáfu og styðja að appið sé nothæft fyrir fjölbreyttan hóp notenda. | BRG-2 Aðgengismál, WCAG 2.1 AA |
| Virkni á iPhone og Android | Fyrsta útgáfan þarf að fylgja skilgreindri takmörkun um að Settið virki bæði á iPhone og Android. | C-1 Virkar á iPhone og Android |


### 5.2 Rökstuðningur fyrir vali í fyrstu útgáfu

MVP byggir fyrst og fremst á F-1, æfingaskráningu og þeim hlutum F-3 sem styðja framfarir og persónuleg met. Methafinn er lykilnotandinn og hann vill fyrst og fremst skrá sett hratt, sjá hvað hann gerði síðast og fylgjast með metum sínum.

Þessi útgáfa styður öll þrjú viðskiptamarkmiðin. Hröð skráning og síðasta sett stuðla að aukinni notkun (BO-1). Persónuleg met skapa upplifun sem notendur vilja segja öðrum frá (BO-2). Saga æfinga og sýnilegar framfarir gera notendum kleift að sjá hvort þeir séu að bæta sig og styðja því beint við BO-3.

Æfingaplanið (F-2) er hluti af framtíðarsýn vörunnar en er ekki nauðsynlegt til að skila grunnvirði til Methafans í fyrstu útgáfu. Því bíður það síðari útgáfu ásamt virkni sem beinist sérstaklega að Byrjandanum og Ráfaranum.

Samkvæmt forgangsröðun verkefnisins eru eiginleikar drifkraftur og gæði og mannafli setja verkefninu takmarkanir. Því er allri mikilvægustu virkni fyrir Methafann forgangsraðað í fyrstu útgáfu, þá sérstaklega æfingaskráningunni og sýnilegum framförum. Aðrir eiginleikar, þ.á.m. æfingaplanið, geta beðið síðari útgáfu svo hægt sé að halda fyrstu útgáfunni raunhæfri innan þessara takmarkana. Þar sem tímasetningar eru frígráða er hægt að færa útgáfutímann ef nauðsynlegt er.


### 5.3 Hvað bíður síðari útgáfu?

| Eiginleiki | Ástæða þess að hann getur beðið |
|---|---|---|
| Sýna hvað er á dagskrá í dag (FR-7) | Mikilvægt fyrir Ráfarann en nauðsynlegt virði fyrir Methafann fæst án þess | 
| Klára æfingu og fara sjálfkrafa í næstu (FR-8) | Þægindi fremur en kjarnavirði | 
| Hvíldardagar (FR-9) | Bætir upplifun en er ekki nauðsynlegt til að sannreyna vöruna |
| Tilbúin plön (FR-10) | Beinast fyrst og fremst að byrjendum | 
| Velja æfingadaga (FR-11) | Getur beðið þar til notkunarmynstur er betur þekkt | 
| Leiðbeiningar um æfingar (FR-12)| Mikilvægast fyrir byrjendur en ekki fyrir valinn lykilnotanda | 
| Val á mismunandi tímabilum (FR-15) | Þægindavirkni sem getur komið síðar | 
| Öll met á einum stað (FR-18) | Met eru sýnileg, þó sameiginlegur yfirlitsskjár sé ekki til staðar í fyrstu útgáfu |

### 5.4 Takmarkanir og útilokanir

Settið er afmarkað við styrktarþjálfun og verður ekki alhliða heilsu- eða líkamsræktarapp. Matur, kaloríur, þolþjálfun, samfélagsvirkni, þjálfari eða gervigreind sem býr til æfingaplön og greiðslur eða áskriftir eru ekki hluti af fyrirhuguðu umfangi kerfisins. Þessi afmörkun byggir á mörkunum úr Verkefni 1 og eru þ.a.l. útilokuð frá heildarumfangi vörunnar en eru ekki eiginleikar sem bíða síðari útgáfu.


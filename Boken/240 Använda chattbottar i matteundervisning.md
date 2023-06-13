# Använda chattbottar i matteundervisning
_Det här kapitlet är skrivet av Johan Falk. På bokens projektsida [github.com/itangalo/AI-och-skolan][1] kan du föreslå nya kapitel och förbättringar till befintliga kapitel._

I det här kapitlet finns tips på hur du kan använda chattbottar i matteundervisning, från förskoleklass till gymnasial nivå. Det handlar främst om användning i förberedelser inför undervisning, men några tips gäller användning i klassrummet.

---- 

Chattbottar är förhållandevis dåliga på matematik, om de inte får stöd från andra applikationer. Men det finns fortfarande en del ställen där man kan dra nytta av chattbottar även i matteundervisning.

## Skapa problemuppgifter
De skickligare chattbottarna klarar ofta av att skapa matteproblem utifrån givna villkor, både vad gäller matematiskt innehåll och kontext för frågeställningar. I många lägen kan man behöva justera förslagen från chattbotten, eller så tar man en idé och skapar en helt annan frågeställning utifrån den, men oavsett kan förslag från chattbottar vara ett bra sätt att få inspiration till problemuppgifter att ta upp med elever.

Nedan syns några exempel.

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Vi har just jobbat med bråkräkning i min årskurs 5, och jag skulle vilja ha några kluriga problemuppgifter som eleverna kan arbeta med gruppvis. Kan du ge fyra förslag på problemuppgifter? De får gärna ha ett sammanhang som är intresseväckande för 12-åringar.
> **Chattbot:** Självklart! Det låter som en rolig och engagerande aktivitet för dina elever. Här är fyra problemuppgifter med sammanhang som kan vara intresseväckande för 12-åringar:
> 1. **Rymdexpeditionens Matlagning**
>   2. Sammanhang: Din klass har skickats på en rymdexpedition till Mars. Som en del av resan måste de förbereda en särskild måltid med begränsade ingredienser.
>   3. Problem: De har 2 1/2 liter tomatsås, 1 1/4 liter ost och 3/4 liter skinka för att göra pizzor. Om varje pizza kräver 1/2 liter tomatsås, 1/4 liter ost och 1/8 liter skinka, hur många pizzor kan de göra utan att någon ingrediens tar slut först?
> 2. **Musikfestivalens Schema**
>   5. Sammanhang: Eleverna är ansvariga för att planera en musikfestival på skolan. Det finns olika band som vill spela.
>   6. Problem: Det finns ett band som vill spela i 3/4 av en timme, ett annat band som vill spela i 2/3 av en timme, och ett tredje band som vill spela i 5/6 av en timme. Hur lång tid tar det för alla tre band att spela, och om festivalen börjar kl. 17.00, vilken tid slutar det sista bandet?
> 3. **Skattjakten**
>   8. Sammanhang: Eleverna deltar i en skattjakt där de måste hitta olika föremål på skolgården.
>   9. Problem: På kartan står det att skatten ligger 5/6 av vägen från skolbyggnaden till lekplatsen. Om avståndet från skolbyggnaden till lekplatsen är 120 meter, hur långt måste eleverna gå för att hitta skatten?
> 4. **Chokladkakans Delning**
>   11. Sammanhang: Eleverna får en jättechokladkaka för att fira att de har klarat av bråkräkningen. Men de måste dela upp den rättvist!
>   12. Problem: Chokladkakan är ett rektangel som mäter 9 3/4 tum på längden och 6 1/2 tum på bredden. Om varje elev ska få en bit av kakan som är 1 1/4 tum på längden och 1 tum på bredden, hur många elever kan få en bit av chokladkakan?
> För att göra uppgifterna ännu mer engagerande kan du be eleverna presentera sina lösningar på ett kreativt sätt, som genom att skapa affischer, berättelser eller presentationer.

I det här exemplet kan man fråga sig hur kluriga uppgifterna egentligen är. Att chokladkakan i sista uppgiften har mått angivna i tum är kanske inte heller helt lyckat – eller så är det ett tillfälle för att prata om olika mått, enhetsbyten och kanske till och med hur kvadrattum förhåller sig till kvadratcentimeter och kvadratdecimeter. Kanske kan en eller flera uppgifter användas rakt av, eller efter en del bearbetning. Och det går förstås att be om ytterligare förslag, och även precisera önskemålen ytterligare.

---- 

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Jag behöver två problemuppgifter till ett matteprov. De ska beskriva en situation som är relevant för elever som läser ekonomi, och man ska behöva lösa exponentialekvationer för att besvara frågeställningarna i uppgifterna. Kan du hjälpa mig?
> **Chattbot:** Självklart! Här är två problemuppgifter som kan vara användbara för elever som studerar ekonomi och som kräver att man löser exponentialekvationer.
> **Problem 1: Sparande med ränta på ränta**
> Emma har just öppnat ett sparkonto med en årlig ränta på 5%, och räntan kapitaliseras årligen. Hon gör en initial insättning på 10 000 kr.
> a) Hur mycket pengar kommer Emma ha på sitt konto efter 10 år?
> b) Emma vill spara till hon har 20 000 kr på sitt konto. Hur många hela år tar det innan hon når sitt mål?
> *Lösningsmetod:*
> Använd formeln för ränta på ränta: A = P(1 + r)^n
> där A är det framtida beloppet, P är det ursprungliga beloppet, r är den årliga räntesatsen och n är antalet år.
> **Problem 2: Företagets tillväxt**
> Ett företag som säljer ekologiska produkter har märkt att antalet kunder växer exponentiellt. I början av året hade de 200 kunder, och de uppskattar att antalet kunder växer med 8% varje månad.
> a) Hur många kunder förväntas företaget ha vid slutet av året?
> b) Efter hur många hela månader förväntas företaget ha 500 kunder?
> *Lösningsmetod:*
> Använd formeln för exponentiell tillväxt: A = P(1 + r)^t
> där A är det framtida antalet kunder, P är det ursprungliga antalet kunder, r är den månatliga tillväxttakten, och t är antalet månader. 
> Observera att dessa problem innefattar realistiska situationer som ekonomistudenter kan stöta på i arbetslivet och att de kräver att man löser exponentialekvationer för att besvara frågeställningarna.

De här två uppgifterna kvalar in som ok, men har vissa brister. Man kan fråga sig hur realistiska förutsättningarna är: En sparränta på 5 procent är svårt att hitta, och att antalet kunder fortsätter att växa exponentiellt är ett djärvt antagande – men samtidigt är frågeställningen tydlig med att det som efterfrågas är det _förväntade_ antalet kunder (utifrån modellen). Något som kanske är ett större problem är att det efterfrågas antal _hela_ år eller månader tills önskad storlek nåtts, vilket gör prövning till en rimlig metod (inte minst som det rör sig om förhållandevis få steg).

Genom att följa upp frågorna, eller justera prompten, kan det bli lättare att få uppgifter som passar de behov man har.

---- 

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Kan du ge mig två matteproblem som man kan ge till elever på högstadiet? Jag vill att problemen ska kräva en del klurande och funderande, och inte gå att lösa med vanliga metoder som elever fått lära sig. De ska däremot inte kräva avancerad matematik, och jag vill att de ska vara engagerande även för elever som normalt inte gillar matte.
> **Chatbot:** Självklart! Här är två matematikproblem som är utmanande men inte för avancerade, och som kan engagera högstadieelever:
> **1. Frogs and Lilypads**:
> Det finns 7 näckrosblad i en rak linje på en damm, numrerade från 1 till 7. Det finns också en liten groda som älskar att hoppa mellan näckrosbladen. Grodan startar på blad nummer 1. Varje gång den hoppar kan den antingen hoppa ett steg framåt eller två steg framåt. Till exempel, om grodan är på blad 3, kan den hoppa till blad 4 eller blad 5. Hur många olika sätt kan grodan ta sig från blad 1 till blad 7 genom att bara hoppa framåt?
> Detta problem kräver lite klurande och eleverna kan börja med att räkna manuellt och kanske upptäcker ett mönster som de kan använda för att lösa problemet.
> **2. Godisbutiken**:
> En godisbutik säljer endast chokladkakor och karameller. En dag sålde butiken totalt 30 godisar, och för varje karamell som såldes, såldes två chokladkakor. Hur många av varje typ av godis såldes den dagen?
> Låt antalet karameller som såldes vara K och antalet chokladkakor vara C. Vi vet att K + C = 30 och att för varje karamell som såldes, såldes två chokladkakor, så C = 2K. Eleverna måste använda dessa ekvationer för att lösa problemet.
> Båda dessa problem kräver lite kreativt tänkande och är inte bara rutinmässiga beräkningar, vilket kan göra dem mer engagerande för elever, särskilt de som kanske inte är lika intresserade av traditionella matematikproblem.

Det andra problemet från chattbotten är eventuellt för platt för att vara intressant, men det första problemet skulle kunna leda till en hel del diskuterande, testande och utforskande.

## Anpassa problemuppgifter
Ett annat sätt att använda chattbottar är att ta rätt standardmässiga problemuppgifter och förändra dem. I bästa fall gör det att chattbotten kan användas till det den är bra på – bearbeta text – och att det matematiska innehållet förblir mer eller mindre oförändrat.

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Här är ett matteproblem för årskurs 4: "Det finns 100 äpplen. Alice får hälften av dem. Av de som är kvar får Bob hälften, och Cedric får resten. Hur många får var och en?"
> Kan du skriva om det till en kontext som är fantasifull och engagerande för 11-åringar?
> **Chattbot:** Självklart! Här är ett fantasifullt och engagerande omskrivning av matematikproblemet:
> "En gång i en fjärran trollskog, där trädens löv skiftade färg med årstiderna och älvarna dansade under stjärnorna, fanns ett magiskt äppelträd. Detta äppelträd bar endast frukt en gång var hundrade år, och på den dagen skördades exakt 100 gyllene äpplen, glittrande med magisk energi.
> Alice, en modig älva med silvervingar, vakade över det magiska äppelträdet. Som tack för hennes tapperhet och hängivenhet, blev hon belönad med hälften av de magiska äpplena när skördetiden kom.
> Efter att Alice hade tagit sin del, reste Bob, en lurig skogsgnom med en förkärlek för äventyr, från sin lilla stuga vid foten av det gamla ektorget. Han hade hjälpt till att skydda skogens djur, och som belöning fick han hälften av de kvarvarande äpplena.
> Cedric, en vis gammal trollkarl med en ständigt gnistrande trollstav, visste att balansen i skogen måste upprätthållas. De resterande äpplena var menade för honom, så att han kunde använda deras magiska kraft för att skydda skogen tills nästa skörd.
> Hur många av de glittrande, magiska äpplena fick Alice, Bob, och Cedric var?"
> Detta berättelseformat ger problemet en fantasifull kontext som kan göra det mer engagerande för 11-åringar att lösa.
> **Jag:** Tack! Kan du ändra kontexten så att den upplevs relevant för elever på komvux, grundläggande nivå? (Det är ok att ändra namnen också.)
> **Chattbot:** Självklart! I en vuxen utbildningskontext kan vi göra scenariot mer relevant genom att relatera det till något som vuxna kanske stöter på i det verkliga livet. Här är en omskrivning av problemet för elever på Komvux, grundläggande nivå:
> "Antag att du är del av ett team på ett nystartat företag som heter 'TechTree Innovations'. Företaget har just avslutat ett stort projekt och som ett resultat har ledningen beslutat att belöna teamet med 100 aktieoptioner för att visa uppskattning för det hårda arbetet.
> Alexandra, som var projektledare och ledde teamet genom några tuffa utmaningar, får hälften av aktieoptionerna som tack för hennes ledarskap.
> Av de aktieoptioner som är kvar, får Björn hälften. Björn är en mjukvaruutvecklare som kom med en banbrytande lösning som kraftigt förbättrade projektets resultat.
> Resten av aktieoptionerna går till Caroline, som är företagets marknadschef. Hon spelade en avgörande roll i att kommunicera fördelarna med projektet till kunder och säkerställa dess framgång på marknaden.
> Hur många aktieoptioner får Alexandra, Björn, och Caroline var?"
> Detta exempel använder ett arbetsrelaterat scenario som kan vara mer relevant och engagerande för vuxna studenter, och det ger dem möjlighet att tillämpa matematiska färdigheter i en verklighetsnära kontext.
> **Jag:** Tack igen! Kan du ändra värdena och andelarna på ett sätt som gör uppgiften svårare att lösa?
> **Chattbot:** Självklart! Vi kan göra matematikproblemet mer utmanande genom att använda större värden och mer komplexa andelar. Här är en omskrivning av problemet med mer komplexa siffror, men fortfarande i en arbetsrelaterad kontext för elever på Komvux, grundläggande nivå:
> "Antag att du är del av ett team på ett nystartat företag som heter 'GreenTech Solutions'. Företaget har just säkrat en stor investering och som ett resultat har ledningen beslutat att belöna teamet med 480 aktieoptioner för att visa uppskattning för det hårda arbetet.
> Isabella, som var projektledare och ledde teamet genom några tuffa utmaningar, får en tredjedel av aktieoptionerna som tack för hennes ledarskap.
> Av de aktieoptioner som är kvar, får Jakob 40%. Jakob är en produktutvecklare som kom med en banbrytande hållbar teknik som har potential att revolutionera industrin.
> Resten av aktieoptionerna går till Fatima, som är företagets kommunikationschef. Hon spelade en avgörande roll i att bygga företagets varumärke och etablera relationer med viktiga partners.
> Hur många aktieoptioner får Isabella, Jakob, och Fatima var?"
> Detta exempel innebär att eleverna behöver hantera både andelar och procent, vilket gör problemet mer utmanande jämfört med det ursprungliga exemplet.

---- 

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Här är ett matteproblem för matte 2 på gymnasiet. ”Alice sätter in 1000 kr på banken. Räntan är 3,5 procent. Hur länge måste hon vänta tills hon har 1500 kr?” Kan du ändra problemet så att det blir intressant för elever på naturvetenskapliga programmet? Det är ok att ändra värdena också.
> **Chattbot:** Självklart, vi kan lägga till några fler element i problemet för att göra det mer utmanande och intressant för elever på ett naturvetenskapligt program:
> ”Alice, en blivande ingenjör, vill utforska möjligheterna inom förnybar energi. Hon bestämmer sig för att spara pengar för att kunna köpa och experimentera med ett mindre vindkraftverk för hennes framtida projekt. Alice börjar med att sätta in 10 000 kr på ett konto med en årlig ränta på 4%. Samtidigt får hon reda på att det finns ett statligt stödprogram för förnybar energi som ger ett årligt bidrag på 500 kr till de som sparar pengar för att investera i förnybar energi.
> Alice har hittat ett mindre vindkraftverk som hon är intresserad av att köpa för 20 000 kr. Hur lång tid tar det för Alice att nå sitt sparande mål om hon utnyttjar både räntan på sitt konto och det statliga stödprogrammet?”
> Detta problem involverar komponenter av både exponentiell tillväxt (ränta) och linjär tillväxt (statligt bidrag), vilket gör det mer intressant för elever som studerar naturvetenskap. Det kräver också lite mer kreativt tänkande och problemlösning.
> **Jag:** Tack! Kan du ändra problemet igen, så att det blir humoristiskt och halvgalet?
> **Chattbot:** Självklart, låt oss krydda problemet med humor och galenskap:
> "Alice är en aspirerande vetenskapsmaffian, som av en händelse är besatt av ankor. Hon har hört talas om att ankor blir extremt energiska när de är glada, och hon vill testa en teori om att konvertera ankenergi till ren, förnybar el. För att göra detta behöver hon bygga en gigantisk ‘Ank-O-Matic 3000’, en maskin som omvandlar ankors entusiasm till elektricitet.
> Hon börjar med att sätta in 15 000 kr på ett konto som har en fantastiskt flyktig ränta; räntan är 3% plus ytterligare 2% för varje dag det regnar ankfjädrar (vilket händer helt slumpmässigt).
> Samtidigt får Alice reda på att det finns en excentrisk miljardär som älskar galna uppfinningar. Han har lovat att ge ett årligt bidrag på 3 000 kr till alla som försöker bygga maskiner som inte borde existera.
> Ank-O-Matic 3000 kostar 30 000 kr. Hur lång tid tar det för Alice att nå sitt sparande mål om hon tar hänsyn till det galna räntesystemet och den excentriske miljardärens bidrag?
> Bonusfråga: Om Alice lyckas bygga sin Ank-O-Matic 3000, hur många ankor skulle det krävas för att driva en elektrisk tesked i 5 minuter, om vi antar att varje extremt entusiastisk anka genererar 0,0025 kWh energi?”
> Detta problem blandar matte med humor och absurditet, vilket kan engagera elever som uppskattar en mer kreativ och rolig inställning till lärande.

---- 

> _Exempel från ChatGPT (GPT-4, 24 maj)_
> **Jag:** Här är ett matteproblem: "En boll följer kurvan y = -x^2 + 2x + 1, där y är höjden över marken. a) Vid vilka x-värden är bollen på marken? b) Hur högt når bollen?"
> Klassen jag har är fantastiskt intresserade av grönsaksodling. Kan du skriva om uppgiften så att den anknyter till grönsaksodling, men fortfarande testar samma typ av mattekunskaper?
> **Chattbot:** Självklart! Låt oss göra det här matteproblemet mer relevant för din klass genom att knyta det till grönsaksodling.
> "När grönsaksodlare på Enchanted Gardens vill hänga upp ett nät för att skydda sina grönsaker från fåglar, använder de stänger som är böjda för att skapa ett kupolformigt nät över trädgårdsområdet. Formen på en sådan böjd stång kan beskrivas av ekvationen y = -x^2 + 2x + 1, där y är höjden över marken i meter och x är avståndet från ena änden av stången i meter.
> a) Vid vilka x-värden kommer ändarna av stången att röra marken (dvs. när y är 0)?
> b) Vilken är den maximala höjden som stången når, och vid vilket avstånd från den ena änden sker detta? Detta hjälper odlarna att förstå hur högt nätet kommer att vara i mitten, så att de kan säkerställa att det är tillräckligt högt för att skydda grönsakerna."
> På det här sättet kan eleverna relatera till grönsaksodling samtidigt som de använder samma matematiska färdigheter som i det ursprungliga problemet.
> **Jag:** Tack! Jag tänker att det här blev lite för konstlat. Kan du hitta på något annat som kan engagera eleverna genom att vara humoristiskt, eller knyta an till något i samhälle eller historia som de har en stark relation till?
> **Chattbot:** Självklart, låt oss göra det lite humoristiskt och knyta an till något som kan vara roligt för eleverna.
> "En dag bestämde sig Tomtebobönderna för att ha en Zucchini-lanseringstävling! Ja, du hörde rätt. Dessa kreativa bönder byggde små katapulter för att se vem som kunde lansera sin zucchini längst. En av bönderna, Olle, byggde en katapult som skickade zucchinis på en bana som kan beskrivas av ekvationen y = -x^2 + 2x + 1, där y är höjden på zucchinin över marken i meter och x är avståndet från katapulten i meter.
> a) Vid vilka x-värden landar Olles zucchini på marken? (Tips: Det är när y är 0!)
> b) Hur högt når Olles zucchini och vid vilket avstånd från katapulten? Odlarna börjar bli nervösa - de tror att han kan bryta det årliga Tomtebo-rekordet!"
> Detta exempel gör matteproblemet lite roligare och mer engagerande för eleverna genom att introducera en humoristisk situation som involverar grönsaksodling, men på ett mer lekfullt sätt.

I exemplen ovan kan man hitta ett antal språkfel, och i exemplet som rör ränta på ränta gör chattbotten ändringar som gör problemet avsevärt mer komplicerat. I tredje exemplet är kontexten tydligt påklistrad, och man kan fråga sig om en så konstlad kontext hjälper eller stjälper elevers intresse för matematik. (Min egen bedömning är att zucchini-katapulter har bättre möjlighet att nå fram.) Med rätt sorts redigering och pedagogisk medvetenhet kan chattbottar fortfarande användas för att få variation i uppgifter och knyta an till elevers intressen.

## Exempellösningar
Chattbottar, särskilt de lite äldre, är ofta inte särskilt bra på att lösa lite svårare matteproblem. Det kan vara en källa för att skapa felaktiga lösningar att diskutera i klassen, eller låta elever arbeta med för att analysera och rätta till.

> _Exempel från ChatGPT (GPT-3.5, 24 maj)_
> **Jag:** Vad är sannolikheten att slå par med tre tärningar?
> **Chattbot:** För att beräkna sannolikheten att slå par med tre tärningar måste vi först definiera vad vi menar med "par". I detta fall innebär det att två av de tre tärningarna visar samma siffra, medan den tredje tärningen visar en annan siffra.
> För att beräkna sannolikheten kan vi använda principen för sannolikhet som säger att sannolikheten för att två oberoende händelser inträffar samtidigt är produkten av deras individuella sannolikheter.
> För att få ett par med tre tärningar finns det några olika möjligheter:
> 1. Två tärningar visar samma siffra och den tredje tärningen visar en annan siffra. Det finns 6 möjliga siffror som de två tärningarna kan visa, och för varje siffra finns det 5 möjliga val för den tredje tärningen. Så det finns totalt 6 \* 5 = 30 möjliga utfall där vi får ett par.
> 2. Två av tärningarna visar samma siffra, medan den tredje tärningen visar samma siffra som de andra två. Det finns 6 möjliga siffror som de två tärningarna kan visa, och för varje siffra finns det 1 möjligt val för den tredje tärningen. Så det finns totalt 6 möjliga utfall där vi får tre lika siffror.
> Totalt finns det 30 + 6 = 36 möjliga utfall där vi får par eller tre lika siffror när vi kastar tre tärningar.
> Eftersom det finns totalt 6 * 6 * 6 = 216 möjliga utfall när vi kastar tre tärningar, kan vi beräkna sannolikheten genom att dela antalet gynnsamma utfall (36) med antalet möjliga utfall (216):
> Sannolikheten att slå par med tre tärningar är 36/216 = 1/6 ≈ 0,1667 eller 16,67%.

En annan variant är förstås också att använda korrekta lösningar (eller som nedan, nästan korrekta lösningar), och låta elever diskutera hur vad som är bra eller mindre bra i redovisningen och hur den skulle kunna göras bättre.

> _Exempel från ChatGPT (GPT-3.5, 24 maj)_
> **Jag:** En kopp te har vid tiden t = 0 temperaturen 98 °C. Temperaturen i rummet är 20 °C. För varje minut som går minskar temperaturskillnaden med 4 procent. Hur lång tid tar det innan teet blivit 60 °C?
> **Chattbot:** För att lösa detta problem kan vi använda en exponentiell modell för temperaturskillnaden. Vi vet att temperaturen på teet vid tiden t kan beskrivas som:
> T(t) = 20 + (98 - 20) \* (1 - 0.04)^t
> Där T(t) är temperaturen vid tiden t, 20 är rumstemperaturen, 98 är starttemperaturen för teet och (1 - 0.04)^t är temperaturskillnaden som minskar med 4 procent för varje minut.
> Vi vill nu lösa för tiden t när temperaturen på teet når 60 °C. Sätt T(t) = 60 och löser ekvationen:
> 60 = 20 + 78 \* (1 - 0.04)^t
> Subtrahera 20 från båda sidor:
> 40 = 78 \* (1 - 0.04)^t
> Dela båda sidor med 78:
> (1 - 0.04)^t = 40/78
> Skriv om 40/78 som en decimal:
> (1 - 0.04)^t = 0.5128
> Ta logaritmen på båda sidor med bas 0.96 (1 - 0.04):
> log(0.96, (1 - 0.04)^t) = log(0.96, 0.5128)
> Använd logaritmens basförändring för att få t:
> t = log(0.96, 0.5128) / log(0.96, (1 - 0.04))
> Beräkna detta med hjälp av en kalkylator eller programvara:
> t ≈ 47.5
> Så det tar cirka 47.5 minuter innan teet når 60 °C.

## Uppslag för att undervisa begrepp och metoder
I matteundervisning förekommer ofta nya begrepp och metoder. Vissa av dessa, så kallade tröskelbegrepp, är ofta både svåra att lära sig och viktiga för det fortsatta lärandet. Men även för mindre kritiska begrepp och metoder kan det vara värdefullt att få uppslag för hur man kan lägga upp undervisning.

> _Exempel från Perplexity.ai (2023-06-12, sökområde ”academic”)_
> **Jag:** How can I teach negative numbers effectively?
> **Chattbot:** Teaching negative numbers can be challenging due to their complexity and abstract nature[^1]. Here are some tips and strategies that can be used to teach negative numbers effectively:
> 1. Use real-life examples: Negative numbers can be abstract, so using real-life examples can help students understand their meaning and relevance. For example, using a bank account to demonstrate negative numbers can be helpful[^2].
> 2. Use visual aids: Visual aids such as number lines, graphs, and charts can help students visualize negative numbers and understand their relationship to positive numbers[^3].
> 3. Emphasize the concept of opposites: Negative numbers are often described as the opposite of positive numbers. Emphasizing this concept can help students understand the relationship between positive and negative numbers[^4].
> 4. Use manipulatives: Manipulatives such as blocks or chips can help students physically represent negative numbers and understand their relationship to positive numbers[^5].
> 5. Teach the rules of operations: Teaching the rules of operations such as addition, subtraction, multiplication, and division with negative numbers can help students understand how to perform these operations correctly[^6].
> 6. Provide practice problems: Providing practice problems that gradually increase in difficulty can help students develop their skills and confidence in working with negative numbers[^7].
> 7. Encourage questions and discussion: Encouraging students to ask questions and engage in discussion can help them clarify their understanding of negative numbers and address any misconceptions they may have[^8].
> 8. Use technology: Technology such as interactive whiteboards or online games can be used to engage students and reinforce their understanding of negative numbers[^9].

Man kan också använda chattbottar för att få mer konkreta uppslag att använda i planering av undervisning.

> _Exempel från Chatbot UI (GPT-4, 2023-06-12)_
> **Jag:** Imorgon ska jag undervisa om logaritmer, vilket alltid brukar vara ett knepigt område. Det känns som att själva begreppet liksom är svårt att ta till sig. Kan du hjälpa mig att hitta en bra introduktion till logaritmer?
> **Chattbot:** Självklart! Här är en introduktion till logaritmer som du kan använda för att undervisa dina elever:
> **Introduktion till logaritmer**
> Logaritmer är ett matematiskt begrepp som hjälper oss att lösa problem med exponenter. De används för att förenkla beräkningar och har många användningsområden inom matematik, fysik och teknik.
> **Vad är en logaritm?**
> En logaritm är en funktion som svarar på frågan: Hur många gånger behöver vi multiplicera basen för att få talet? Logaritmen av ett tal `x` med basen `b` skrivs som `log_b(x)` och utläses "logaritmen av x med basen b".
> **Exempel**
> Om vi har:
> `3^2 = 9
> `> Logaritmen med bas 3 av talet 9 är 2, eftersom vi behöver multiplicera 3 två gånger för att få 9. Vi kan skriva detta som:
> `log3(9) = 2
> `> **Logaritmlagarna**
> Det finns några grundläggande logaritmlagar som hjälper oss att förenkla uttryck:
> 1. Produktregeln: `log_b(x * y) = log_b(x) + log_b(y)`
> 2. Kvotregeln: `log_b(x / y) = log_b(x) - log_b(y)`
> 3. Potensregeln: `log_b(x^p) = p * log_b(x)`
> **Några vanliga baser**
> 1. Naturliga logaritmen (logaritmen med bas `e`): Den naturliga logaritmen av `x` skrivs som `ln(x)` och används ofta inom matematik och naturvetenskap.
> 2. Logaritmen med bas 10: Logaritmen av `x` med bas 10 skrivs som `log(x)` och används ofta inom teknik och vetenskap.
> **Användningar av logaritmer**
> Logaritmer används inom många områden, såsom:
> 1. Lösning av exponentiella ekvationer och olikheter
> 2. Förenkling av beräkningar inom teknik och vetenskap
> 3. Skalning av data för att göra det mer hanterbart och förståeligt
> 4. Mätning av ljudintensitet (decibel), jordbävningsstyrka (Richterskalan) och surhet (pH-skalan)
> Förhoppningsvis ger denna introduktion till logaritmer dig en bra grund att börja med i din undervisning. Lycka till!

Man kan förstås också blanda in saker som man av erfarenhet kan engagera eleverna.

> _Exempel från Chatbot UI (GPT-4, 2023-06-12)_
> **Jag:** I min matteklass är många elever intresserade av musik, inte minst frenetisk banjomusik från sydstaterna i USA. Nästa vecka ska jag börja undervisa om normalfördelning. Kan du skissa en introduktion till normalfördelning som kan engagera eleverna?
> **Chattbot:** Självklart! Här kommer en introduktion till normalfördelning som kopplar in elevernas intresse för musik, särskilt frenetisk banjomusik från sydstaterna i USA:
> **Introduktion till normalfördelning med en musikalisk twist**
> Hej kära elever! Idag ska vi börja utforska en av de mest fascinerande och användbara begreppen inom matematik och statistik: *normalfördelningen*. Men först, låt oss koppla detta till något ni verkligen gillar - frenetisk banjomusik från sydstaterna i USA!
> Tänk er en stor banjofestival där hundratals banjospelare från hela världen samlas för att visa upp sina färdigheter. Varje deltagare får spela ett solo, och en panel med domare ger dem poäng baserat på deras prestation. Efter att alla spelat, samlas poängen och vi får en uppsättning av data som visar hur de olika banjospelarna presterade.
> Nu kommer normalfördelningen in i bilden! Om vi plottar dessa poäng på ett diagram, kommer vi förmodligen att se att de flesta spelarna hamnar någonstans i mitten. Det betyder att de är duktiga, men inte exceptionellt bra eller dåliga. Ett mindre antal spelare kommer att ha mycket höga eller mycket låga poäng, vilket indikerar att de är antingen mycket begåvade eller kämpar med sina färdigheter.
> Denna typ av fördelning, där de flesta observationer samlas kring ett medelvärde och det blir färre observationer ju längre bort vi kommer från medelvärdet, kallas en *normalfördelning*. Den har en karakteristisk klockform och är helt symmetrisk. 
> Normalfördelningen är mycket användbar för att förstå och förutsäga händelser inom många områden, såsom naturvetenskap, ekonomi och, som vi just såg, musikprestationer.
> Under de kommande lektionerna kommer vi att dyka djupare in i normalfördelningen och dess egenskaper. Vi kommer att lära oss om begrepp som medelvärde, standardavvikelse och z-scores, samt hur man kan använda dessa för att göra förutsägelser och analysera data.
> Så, låt oss greppa våra banjos och dyka in i normalfördelningens fascinerande värld! 🎶

## Hitta forskning om matematiklärande
Rätt sorts chattbottar kan göra det enklare att läsa på om vad forskning säger om att lära sig matematik eller undervisa matematik. Här finns en viktig skillnad mellan de rena chattbottarna (som har tendens att säga ogrundade saker på ett övertygande sätt) och de hybrider som kan slå upp information i olika typer av databaser.

> _Exempel från Perplexity.ai (2023-06-12, sökområde ”academic”)_
> **Jag:** Hur viktigt är det att lära sig multiplikationstabellen utantill?
> **Chattbot:** Det finns flera studier som undersöker hur viktigt det är att lära sig multiplikationstabellen utantill. Enligt en studie som jämförde undervisning baserad på repetition med undervisning baserad på strategier, så utvecklade eleverna automatisk förmåga att använda multiplikationstabellen oavsett vilken undervisningsmetod som användes[^10]. En annan studie visade att det är viktigt att eleverna förstår multiplikationstabellen och hur den fungerar, och inte bara memoriserar den[^11]. Det är dock viktigt att notera att dessa studier fokuserar på undervisning i skolan och inte på hur viktigt det är att lära sig multiplikationstabellen utantill för vardagliga situationer. Generellt sett kan det vara fördelaktigt att lära sig multiplikationstabellen utantill för att snabbt kunna utföra enklare matematiska beräkningar i vardagen.
> **Jag:** finns det några nackdelar med att lära sig multiplikationstabellen utantill
> **Chattbot:** Det verkar inte finnas några studier eller information som pekar på specifika nackdelar med att lära sig multiplikationstabellen utantill. Däremot har vissa studier visat att det är viktigt att eleverna förstår multiplikationstabellen och hur den fungerar, och inte bara memoriserar den. Det är också viktigt att notera att det finns flera olika sätt att undervisa multiplikationstabellen, och att olika elever kan ha olika sätt att lära sig bäst.[^12]

---- 

> _Exempel från Perplexity.ai (2023-06-12, sökområde ”academic”)_
> **Jag:** How important is it to memorize the multiplication table?
> **Chattbot:** There is no clear consensus on the importance of memorizing the multiplication table. Some studies suggest that alternative methods, such as finger mathematics, can be effective in performing multiplication without memorization[^13]. Other studies emphasize the importance of basic mathematics skills, including memorization of multiplication tables, in the development of more advanced mathematical concepts[^14]. Additionally, some argue that the constructivist approach to education, which emphasizes student-centered learning and de-emphasizes teacher-centered instruction, may undervalue the role of memorization in learning[^15]. Ultimately, the importance of memorizing the multiplication table may depend on individual learning styles and educational contexts.

I de här två exemplen, med samma fråga ställd på två olika språk, ges _ungefär_ samma svar: att lära sig multiplikationstabellen är förmodligen bra, men det finns ingen överväldigande forskning att luta sig mot. De två svaren ger olika spår att gå vidare på, vilket beror på att chattbotten hittat olika artiklar på svenska respektive engelska.

> _Exempel från Perplexity.ai (2023-06-12, sökområde ”academic”)_
> **Jag:** Where can I learn about dyscalculia?
> **Chattbot:** There are several resources available to learn about dyscalculia. Here are some of them:
> 1. Potis Calculia: Learning Resources Platform for Dyscalculia: This research proposes an integrated learning platform using a website that offers learning materials specific for dyscalculia children. The development methodology takes into account understanding the brain process in effort to help the children to overcome their disabilities[^16].
> 2. Students Experiencing Severe Difficulty in Learning Maths: What Resources are Available to Help these Students?: This paper discusses the challenge that children with severe difficulty in learning maths pose for their teachers and for the Resource Teacher Learning and Behaviour (RTLB) who support them. It raises the issue of whether some of these students may indeed have dyscalculia. The paper also highlights some appropriate assessment tools and discusses the particular needs of students who have dyscalculic tendencies that manifest at the Year 4/5 class level. A range of readily available resources are discussed including information on how to access them[^17].
> 3. Numerical skills and dyscalculia. From basic research to practice in Cuba: This paper discusses the evidence on basic numerical capacities and their association with learning mathematics, taking into account different levels of analysis that consider biology, cognition, and education. Researchers in this laboratory have developed a conceptual, methodological, and instrumental platform based on the experimental evidence they have systematically obtained. This platform has resulted in the design and validation of tools and resources for learning mathematics in the classroom with the intervention of the teachers[^18].
> 4. Resources Underlying Visuo-Spatial Working Memory Enable Veridical Large Numerosity Perception: This paper discusses the cognitive resources underlying the ability to quickly approximate how many objects are in a visual image. It also highlights the issue of why numerosity estimates are often non-veridical and how this affects individuals with developmental dyscalculia. The paper hypothesizes that resources supporting visuo-spatial working memory, which allow for the simultaneous identification of multiple objects, might also be critical for precise and unbiased perception of larger numerosities[^19].
> 5. Dyscalculia, Dyslexia, and Medical Students’ Needs for Learning and Using Statistics: This commentary draws attention to dyslexia and dyscalculia as two potentially unrecognized conditions among undergraduate medical students and highlights key developments from recent literature in the diagnosis of these conditions. With a view to assisting medical educators meet the needs of dyscalculic learners and the more varied needs of dyslexic learners, a comprehensive list of suggestions is provided as to how learning resources can be designed from the outset to be more inclusive[^20].
> 6. Dyscalculia: Action Plans for Successful Learning in Mathematics: This book is divided into six sections and provides an introduction to dyscalculia, effective teaching and learning, understanding the number system, understanding operations, measurement and rational numbers, and teacher resources. It covers topics such as counting, understanding algorithms, addition, subtraction, multiplication, division, and learning number facts[^21].

Exemplet ovan visar på en styrka med chattbottar som kan prata med databaser med forskningsartiklar. Även om det inte är säkert att de sex artiklar som lyfts fram är de bästa att läsa, så lär det ändå vara en bra gissning för ställen att börja leta på. Och varje artikel presenteras med en kort sammanfattning.

Motsvarande sökning på svenska gav ett ganska kortfattat svar, en länk till artikeln om dyskalkyli på 1177.se, och hänvisning till en rad artiklar som inte verkade relevanta (och flera var skrivna på indonesiska). Så som tekniken ser ut idag kan det alltså finnas anledning att söka på engelska när det gäller forskning, åtminstone i chattbotten Perplexity.

## Programmering
Sedan 2017–2018 är programmering en del i skolmatten, i större eller mindre utsträckning. Chattbottar kan vara ett praktiskt sätt att visa hur programmering kan användas för att hantera vissa typer av matematiska problem – utan att själv behöva skriva kod. Om man dessutom kombinerar kod från en chattbot med onlinetjänster för att köra kod (så som jdoodle.com) kan man i bästa fall få in programmering på ett smidigt sätt i undervisningen.

Ett område där programmering är användbart är när man jobbar med sannolikheter. Den så kallade Monte Carlo-metoden går ut på att låta en dator skapa massor med slumpvisa utfall och undersöka hur ofta de gynnsamma utfallen dyker upp.

> _Exempel från Chatbot UI (GPT-4, 2023-06-12)_
> **Jag:** Skriv ett Python-program som använder Monte Carlo-metoden för att ta reda på sannolikheten att slå par med tre tärningar. Skriv programmet så att det går lätt att förklara för mina elever i matte.
> **Chattbot:** Här är ett enkelt Python-program som använder Monte Carlo-metoden för att beräkna sannolikheten att slå par med tre tärningar. Jag kommer att förklara varje del av koden för att göra det lättare för dina elever att förstå.
> 	import random
> 	
> 	def kasta_tarningar():
> 	    t1 = random.randint(1, 6)
> 	    t2 = random.randint(1, 6)
> 	    t3 = random.randint(1, 6)
> 	    return t1, t2, t3
> 	
> 	def har_par(tarningar):
> 	    return len(set(tarningar)) <= 2
> 	
> 	def berakna_sannolikhet_par(antal_simuleringar):
> 	    par = 0
> 	    for _ in range(antal_simuleringar):
> 	        tarningar = kasta_tarningar()
> 	        if har_par(tarningar):
> 	            par += 1
> 	    return par / antal_simuleringar
> 	
> 	antal_simuleringar = 100000
> 	sannolikhet = berakna_sannolikhet_par(antal_simuleringar)
> 	print(f"Sannolikheten att få par med tre tärningar: {sannolikhet:.2%}")
> Förklaring av koden:
> 1. Vi importerar `random`-modulen för att generera slumpmässiga tal.
> 2. Vi definierar en funktion `kasta_tarningar()` som simulerar att kasta tre tärningar. Funktionen returnerar de tre tärningarnas värden som en tuple.
> 3. Vi definierar en funktion `har_par(tarningar)` som tar en tuple av tre tärningsvärden och returnerar `True` om det finns minst ett par och `False` annars. Den använder `set()` för att räkna unika värden och jämför längden med 2.
> 4. Vi definierar en funktion `berakna_sannolikhet_par(antal_simuleringar)` som tar antalet simuleringar som parameter och returnerar sannolikheten att få par. Funktionen räknar antalet gånger vi får par och dividerar det med totala antalet simuleringar för att få sannolikheten.
> 5. Vi väljer antalet simuleringar (här 100 000) och kör funktionen `berakna_sannolikhet_par()` för att få sannolikheten.
> 6. Vi skriver ut sannolikheten som ett procenttal med två decimaler.
> Om du förklarar varje del av koden för dina elever borde det vara enkelt att förstå hur Monte Carlo-metoden används för att beräkna sannolikheten att få par med tre tärningar.

När koden körs får man ett resultat på drygt 44 procent, vilket är sannolikheten för par med tre tärningar (om man inkluderar triss). Om man vill förstå delar av koden bättre går det fint att ställa uppföljningsfrågor:

> **Jag:** Vad gör set()?
> **Chattbot:** `set()` är en inbyggd Python-funktion som skapar en mängd (engelska: set) från en given sekvens (t.ex. en lista, tuple eller sträng). En mängd är en oordnad samling av unika element, vilket innebär att varje element endast kan förekomma en gång i mängden.
> I det tidigare exemplet används `set()` för att räkna antalet unika tärningsvärden i tupeln `tarningar`. Här är en kort förklaring av hur `har_par(tarningar)`-funktionen fungerar:
> 	def har_par(tarningar):
> 	    return len(set(tarningar)) <= 2
> När vi skapar en mängd från `tarningar`, tar vi bort eventuella dubbletter och behåller endast unika värden. Därefter räknar vi antalet unika element i mängden med hjälp av `len()`-funktionen.
> Om det finns minst ett par i `tarningar`, kommer antalet unika element att vara 2 eller mindre. I så fall returnerar funktionen `True`. Annars, om alla tärningar har olika värden och antalet unika element är 3, returnerar funktionen `False`.

När det gäller att räkna ut sannolikheten för par med tre tärningar är en algebraisk lösning inte särskilt långt borta, vilket kanske gör Monte Carlo-metoden överflödig. (Eller så är det ett bra tillfälle att jämföra resultat från simuleringar med det ideala fallet.) I andra fall kan det vara klart svårare att hitta algebraiska lösningar:

> _Exempel från Chatbot UI (GPT-4, 2023-06-12)_
> **Jag:** Skriv ett Python-program som använder Monte Carlo-metoden för att ta reda på hur ofta man får exakt fyra kort i samma färg, bland fem slumpvisa kort i en vanlig kortlek.
> **Chattbot:** Här är ett Python-program som använder Monte Carlo-metoden för att uppskatta sannolikheten att få exakt fyra kort i samma färg bland fem slumpmässigt dragna kort från en vanlig kortlek:
> 	import random
> 	from collections import Counter
> 	
> 	def draw_cards(num_cards=5):
> 	    suits = ['hjärter', 'spader', 'ruter', 'klöver']
> 	    ranks = list(range(1, 14))
> 	    deck = [(suit, rank) for suit in suits for rank in ranks]
> 	    random.shuffle(deck)
> 	    return deck[:num_cards]
> 	
> 	def has_four_of_a_kind(cards):
> 	    suit_counts = Counter([suit for suit, rank in cards])
> 	    return 4 in suit_counts.values()
> 	
> 	def monte_carlo_simulation(n_trials=10000):
> 	    num_four_of_a_kind = 0
> 	    for _ in range(n_trials):
> 	        cards = draw_cards()
> 	        if has_four_of_a_kind(cards):
> 	            num_four_of_a_kind += 1
> 	    return num_four_of_a_kind / n_trials
> 	
> 	probability = monte_carlo_simulation()
> 	print(f"Sannolikheten att få fyra kort i samma färg bland fem slumpmässigt dragna kort är ungefär: {probability:.4f}")
> Programmet definierar en kortlek med hjälp av en lista över färger och valörer. Funktionen `draw_cards` drar fem slumpmässiga kort från kortleken. Funktionen `has_four_of_a_kind` kontrollerar om det finns fyra kort i samma färg bland de dragna korten. Slutligen körs Monte Carlo-simuleringen med hjälp av funktionen `monte_carlo_simulation`. Du kan ändra antalet försök (`n_trials`) för att få en mer exakt uppskattning av sannolikheten.
> **Jag:** Det står "ranks = list(range(1, 14))". Betyder det att koden skapar 14 kort i varje färg?
> **Chattbot:** Förlåt för förvirringen. När jag skrev `ranks = list(range(1, 14))`, skapade jag faktiskt en lista med 13 ranker (eller valörer) för varje färg. `range(1, 14)` genererar en sekvens av heltal från 1 till 13 (inklusive 1 men exklusive 14). Listan med ranker ser ut så här:
> `\[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13\]
> `> Dessa siffror representerar valörerna Ess (1), 2, 3, 4, 5, 6, 7, 8, 9, 10, Knekt (11), Dam (12) och Kung (13) för varje färg. Så programmet skapar en kortlek med 13 kort i varje färg, vilket ger totalt 52 kort i kortleken.

Koden ovan är ganska svårgenomtränglig, vilket inte är helt ovanligt (för ovana programmerare). Eftersom chattbottar ibland skapar misstag även med kod bör man förhålla sig sunt skeptisk även i de här lägena. Det kan vara en utgångspunkt för rimlighetsbedömningar. Vilka enklare sannolikheter kan vi jämföra med? (I fallet ovan kanske vi kan jämföra med sannolikheten för fem av fem kort i samma färg, och fyra av fyra kort.)

Ett annat sätt att använda programmering i matteundervisning är att skapa korta program som löser givna typer av uppgifter. Att titta på hur programmen fungerar _kan_ vara ett sätt att fördjupa sig i lösningsmetoder. Två tänkbara saker att diskutera för att fördjupa kunskaper om metoderna är att undersöka i vilka lägen programmet inte skulle fungera, eller hur man kan få dem att bli mer effektiva.

> _Exempel från ChatGPT (GPT-3.5, 24 maj)_
> **Jag:** Skriv ett Python-program som löser ekvationer skrivna på formen a(bx + c) = d.
> **Chattbot:**
> 	def solve_equation(a, b, c, d):
> 	    # Kontrollera om a är noll
> 	    if a == 0:
> 	        if b == 0:
> 	            if c == d:
> 	                return "Ekvationen är identitetsekvation (0 = 0)"
> 	            else:
> 	                return "Ekvationen är en omöjlig ekvation (0 ≠ d)"
> 	        else:
> 	            x = (d - c) / b
> 	            return f"Lösningen är x = {x}"
> 	    else:
> 	        x = (d / a - c) / b
> 	        return f"Lösningen är x = {x}"
> 	
> 	
> 	# Testa programmet med olika värden
> 	print(solve_equation(2, 3, 1, 7))  # a = 2, b = 3, c = 1, d = 7
> 	print(solve_equation(0, 3, 1, 7))  # a = 0, b = 3, c = 1, d = 7
> 	print(solve_equation(2, 0, 1, 7))  # a = 2, b = 0, c = 1, d = 7
> 	print(solve_equation(2, 3, 0, 7))  # a = 2, b = 3, c = 0, d = 7

---- 

> _Exempel från ChatGPT (GPT-3.5, 24 maj)_
> **Jag:** Skriv ett Python-program som testar om talet n är ett primtal.
> **Chattbot:** Självklart! Här är ett Python-program som testar om ett tal är ett primtal:
> 	def is_prime(n):
> 	    # Hantera specialfall för n mindre än 2
> 	    if n < 2:
> 	        return False
> 	
> 	    # Testa om n är delbart med något tal från 2 till n-1
> 	    for i in range(2, n):
> 	        if n % i == 0:
> 	            return False
> 	
> 	    # Om inget tal från 2 till n-1 delar n, är det ett primtal
> 	    return True
> 	
> 	# Läs in talet från användaren
> 	num = int(input("Ange ett heltal: "))
> 	
> 	# Testa om talet är ett primtal
> 	if is_prime(num):
> 	    print(num, "är ett primtal")
> 	else:
> 	    print(num, "är inte ett primtal")
> I detta program definieras en funktion `is_prime(n)` som tar ett tal `n` som argument och returnerar `True` om talet är ett primtal och `False` annars. Funktionen testar om talet är delbart med något tal från 2 till n-1 genom att använda en `for`-loop. Om talet är delbart med något av dessa tal, returneras `False`. Annars returneras `True`. Slutligen läser programmet in ett tal från användaren och testar om det är ett primtal genom att använda `is_prime()`-funktionen och skriver ut resultatet.

[^1]:	[https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e][2]

[^2]:	[https://www.semanticscholar.org/paper/Negative-Numbers%3A-Obstacles-in-their-Evolution-from-Hefendehl-Hebeker-Shenitzer/8a4f5ab0d4bb064e723734f2fdc8659aa7d396d1][3]

[^3]:	[https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e][4]

[^4]:	[https://www.semanticscholar.org/paper/Negative-Numbers%3A-Obstacles-in-their-Evolution-from-Hefendehl-Hebeker-Shenitzer/8a4f5ab0d4bb064e723734f2fdc8659aa7d396d1][5]

[^5]:	[https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e][6]

[^6]:	[https://www.semanticscholar.org/paper/The-Integer-Test-of-Primary-Operations%3A-A-Practical-Nurnberger-Haag-Kratky/c775746849a9a27f4a9b19775e3ea47e3f321649][7]

[^7]:	[https://www.semanticscholar.org/paper/The-Integer-Test-of-Primary-Operations%3A-A-Practical-Nurnberger-Haag-Kratky/c775746849a9a27f4a9b19775e3ea47e3f321649][8]

[^8]:	[https://www.semanticscholar.org/paper/Learning-Integers-through-Argumentation%3A-Mapping-a-Whitacre-Flack/4bb9a31ff496c812b61274c9601adaf5aff2da5e][9]

[^9]:	[https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e][10]

[^10]:	[https://www.semanticscholar.org/paper/Multiplikationstabellen-%3A-En-j%C3%A4mf%C3%B6relse-mellan-och-Svedbro-Gunnarsson/fefb7130e796b36f08727cb452c805870bf14b4e][11]

[^11]:	[https://www.semanticscholar.org/paper/Att-konkretisera-och-f%C3%B6rst%C3%A5-multiplikationstabellen-Karlsson-Kilborn/33004260a5b804b7c61aa85728e3cc4242080eb8][12]

[^12]:	I svaret fanns hänvisningar till samma artiklar som i föregående svar.

[^13]:	[https://www.semanticscholar.org/paper/RELATING-%E2%80%9CFINGER-MATHEMATICS%E2%80%9DTO-THE-PRODUCT-OF-Costillas/5d7a771a5e1a75ea0e40bd021684eac9850686d7][13]

[^14]:	[https://www.semanticscholar.org/paper/Practicing-Representation%3A-Learning-with-and-about-Greeno-Hall/c5614a114831a6f9a1e25e10b2f8a2b7e6bc2669][14]

[^15]:	[https://www.semanticscholar.org/paper/%E2%80%98We-Want-to-See-the-Teacher%E2%80%99-Baines-Stanley/c8e7c0740aee633ada42a8eec4c5d74a7caa8802][15]

[^16]:	[https://www.semanticscholar.org/paper/Potis-Calculia%3A-Learning-Resources-Platform-for-Kasinathan-Mustapha/1348b108648b408d00621afb5dd2632d7a202417][16]

[^17]:	[https://www.semanticscholar.org/paper/Students-Experiencing-Severe-Difficulty-in-Learning-McNeil/f1f0ea75e6af0ad0d12aa909a0400713bc1f5fcd][17]

[^18]:	[https://www.semanticscholar.org/paper/Numerical-skills-and-dyscalculia.-From-basic-to-in-Reigosa-Crespo-Castro-Ca%C3%B1izares/b5cf70a1e5ebf863db7c3c564fa394fad88bf33f][18]

[^19]:	[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8634845/][19]

[^20]:	[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2779625/][20]

[^21]:	[https://www.semanticscholar.org/paper/Dyscalculia%3A-Action-Plans-for-Successful-Learning-Hannell/ec03603c10b9f3cb245d5ff9b1b300dba8acbee2][21]

[1]:	https://github.com/Itangalo/AI-och-skolan
[2]:	https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e "A review of the research in teaching and learning the negative numbers: an “action research” concerning the application of the geometrical model of the number line"
[3]:	https://www.semanticscholar.org/paper/Negative-Numbers%3A-Obstacles-in-their-Evolution-from-Hefendehl-Hebeker-Shenitzer/8a4f5ab0d4bb064e723734f2fdc8659aa7d396d1 "Negative Numbers: Obstacles in their Evolution from Intuitive to Intellectual Constructs"
[4]:	https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e "A review of the research in teaching and learning the negative numbers: an “action research” concerning the application of the geometrical model of the number line"
[5]:	https://www.semanticscholar.org/paper/Negative-Numbers%3A-Obstacles-in-their-Evolution-from-Hefendehl-Hebeker-Shenitzer/8a4f5ab0d4bb064e723734f2fdc8659aa7d396d1 "Negative Numbers: Obstacles in their Evolution from Intuitive to Intellectual Constructs"
[6]:	https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e "A review of the research in teaching and learning the negative numbers: an “action research” concerning the application of the geometrical model of the number line"
[7]:	https://www.semanticscholar.org/paper/The-Integer-Test-of-Primary-Operations%3A-A-Practical-Nurnberger-Haag-Kratky/c775746849a9a27f4a9b19775e3ea47e3f321649 "The Integer Test of Primary Operations: A Practical and Validated Assessment of Middle School Students’ Calculations with Negative Numbers"
[8]:	https://www.semanticscholar.org/paper/The-Integer-Test-of-Primary-Operations%3A-A-Practical-Nurnberger-Haag-Kratky/c775746849a9a27f4a9b19775e3ea47e3f321649 "The Integer Test of Primary Operations: A Practical and Validated Assessment of Middle School Students’ Calculations with Negative Numbers"
[9]:	https://www.semanticscholar.org/paper/Learning-Integers-through-Argumentation%3A-Mapping-a-Whitacre-Flack/4bb9a31ff496c812b61274c9601adaf5aff2da5e "Learning Integers through Argumentation: Mapping a Learning Trajectory"
[10]:	https://www.semanticscholar.org/paper/A-review-of-the-research-in-teaching-and-learning-Gagatsis-Alexandrou/736d999af245f80d2028d26b0dd5c1e1ff6d7f1e "A review of the research in teaching and learning the negative numbers: an “action research” concerning the application of the geometrical model of the number line"
[11]:	https://www.semanticscholar.org/paper/Multiplikationstabellen-%3A-En-j%C3%A4mf%C3%B6relse-mellan-och-Svedbro-Gunnarsson/fefb7130e796b36f08727cb452c805870bf14b4e "Multiplikationstabellen : En jämförelse mellan strategi- och repetitionsbaserad undervisning"
[12]:	https://www.semanticscholar.org/paper/Att-konkretisera-och-f%C3%B6rst%C3%A5-multiplikationstabellen-Karlsson-Kilborn/33004260a5b804b7c61aa85728e3cc4242080eb8 "Att konkretisera och förstå multiplikationstabellen"
[13]:	https://www.semanticscholar.org/paper/RELATING-%E2%80%9CFINGER-MATHEMATICS%E2%80%9DTO-THE-PRODUCT-OF-Costillas/5d7a771a5e1a75ea0e40bd021684eac9850686d7 "RELATING “FINGER MATHEMATICS”TO THE PRODUCT OF BINOMIALS"
[14]:	https://www.semanticscholar.org/paper/Practicing-Representation%3A-Learning-with-and-about-Greeno-Hall/c5614a114831a6f9a1e25e10b2f8a2b7e6bc2669 "Practicing Representation: Learning with and about Representational Forms"
[15]:	https://www.semanticscholar.org/paper/%E2%80%98We-Want-to-See-the-Teacher%E2%80%99-Baines-Stanley/c8e7c0740aee633ada42a8eec4c5d74a7caa8802 "‘We Want to See the Teacher’"
[16]:	https://www.semanticscholar.org/paper/Potis-Calculia%3A-Learning-Resources-Platform-for-Kasinathan-Mustapha/1348b108648b408d00621afb5dd2632d7a202417 "Potis Calculia: Learning Resources Platform for Dyscalculia"
[17]:	https://www.semanticscholar.org/paper/Students-Experiencing-Severe-Difficulty-in-Learning-McNeil/f1f0ea75e6af0ad0d12aa909a0400713bc1f5fcd "Students Experiencing Severe Difficulty in Learning Maths: What Resources are Available to Help these Students?"
[18]:	https://www.semanticscholar.org/paper/Numerical-skills-and-dyscalculia.-From-basic-to-in-Reigosa-Crespo-Castro-Ca%C3%B1izares/b5cf70a1e5ebf863db7c3c564fa394fad88bf33f "Numerical skills and dyscalculia. From basic research to practice in Cuba (Habilidades numéricas y discalculia. De la investigación básica a la práctica en Cuba)"
[19]:	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8634845/ "Resources Underlying Visuo-Spatial Working Memory Enable Veridical Large Numerosity Perception"
[20]:	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2779625/ "Dyscalculia, Dyslexia, and Medical Students’ Needs for Learning and Using Statistics"
[21]:	https://www.semanticscholar.org/paper/Dyscalculia%3A-Action-Plans-for-Successful-Learning-Hannell/ec03603c10b9f3cb245d5ff9b1b300dba8acbee2 "Dyscalculia: Action Plans for Successful Learning in Mathematics"
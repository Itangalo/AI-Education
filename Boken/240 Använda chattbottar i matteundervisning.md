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
>   - Sammanhang: Din klass har skickats på en rymdexpedition till Mars. Som en del av resan måste de förbereda en särskild måltid med begränsade ingredienser.
>   - Problem: De har 2 1/2 liter tomatsås, 1 1/4 liter ost och 3/4 liter skinka för att göra pizzor. Om varje pizza kräver 1/2 liter tomatsås, 1/4 liter ost och 1/8 liter skinka, hur många pizzor kan de göra utan att någon ingrediens tar slut först?
> 2. **Musikfestivalens Schema**
>   - Sammanhang: Eleverna är ansvariga för att planera en musikfestival på skolan. Det finns olika band som vill spela.
>   - Problem: Det finns ett band som vill spela i 3/4 av en timme, ett annat band som vill spela i 2/3 av en timme, och ett tredje band som vill spela i 5/6 av en timme. Hur lång tid tar det för alla tre band att spela, och om festivalen börjar kl. 17.00, vilken tid slutar det sista bandet?
> 3. **Skattjakten**
>   - Sammanhang: Eleverna deltar i en skattjakt där de måste hitta olika föremål på skolgården.
>   - Problem: På kartan står det att skatten ligger 5/6 av vägen från skolbyggnaden till lekplatsen. Om avståndet från skolbyggnaden till lekplatsen är 120 meter, hur långt måste eleverna gå för att hitta skatten?
> 4. **Chokladkakans Delning**
>   - Sammanhang: Eleverna får en jättechokladkaka för att fira att de har klarat av bråkräkningen. Men de måste dela upp den rättvist!
>   - Problem: Chokladkakan är ett rektangel som mäter 9 3/4 tum på längden och 6 1/2 tum på bredden. Om varje elev ska få en bit av kakan som är 1 1/4 tum på längden och 1 tum på bredden, hur många elever kan få en bit av chokladkakan?
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

> **Jag:** Här är ett matteproblem: "En boll följer kurvan y = -x^2 + 2x + 1, där y är höjden över marken. a) Vid vilka x-värden är bollen på marken? b) Hur högt når bollen?"
> Klassen jag har är fantastiskt intresserade av grönsaksodling. Kan du skriva om uppgiften så att den anknyter till grönsaksodling, men fortfarande testar samma typ av mattekunskaper?
> **Chattbot:** Självklart! Låt oss göra det här matteproblemet mer relevant för din klass genom att knyta det till grönsaksodling.
> "När grönsaksodlare på Enchanted Gardens vill hänga upp ett nät för att skydda sina grönsaker från fåglar, använder de stänger som är böjda för att skapa ett kupolformigt nät över trädgårdsområdet. Formen på en sådan böjd stång kan beskrivas av ekvationen y = -x^2 + 2x + 1, där y är höjden över marken i meter och x är avståndet från ena änden av stången i meter.
> a) Vid vilka x-värden kommer ändarna av stången att röra marken (dvs. när y är 0)?
> b) Vilken är den maximala höjden som stången når, och vid vilket avstånd från den ena änden sker detta? Detta hjälper odlarna att förstå hur högt nätet kommer att vara i mitten, så att de kan säkerställa att det är tillräckligt högt för att skydda grönsakerna."
> På det här sättet kan eleverna relatera till grönsaksodling samtidigt som de använder samma matematiska färdigheter som i det ursprungliga problemet.

I exemplen ovan kan man hitta ett antal språkfel, och i exemplet som rör ränta på ränta gör chattbotten ändringar som gör problemet avsevärt mer komplicerat. Med rätt sorts redigering kan chattbottar ändå användas för att få variation i uppgifter och knyta an till elevers intressen.

…

[1]:	https://github.com/Itangalo/AI-och-skolan
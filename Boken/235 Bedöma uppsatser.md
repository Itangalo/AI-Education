# Bedöma uppsatser
_Det här kapitlet är skrivet av Johan Falk. På bokens projektsida [github.com/itangalo/AI-och-skolan][1] kan du föreslå nya kapitel och förbättringar till befintliga kapitel._

I det här kapitlet finns tips och tankar angående att använda chattbottar för att bedöma uppsatser.

Att använda chattbottar för att bedöma uppsatser har potential att spara mycket arbete, men det rymmer också möjligheter att begå flera av de misstag som nämns i del 1 av boken. Att ta en text skriven av en elev och mata in i en chattbot bör redan det få varningsklockor att börja ringa. Innehåller uppsatsen information om eleven, om någon annan, eller någon annan känslig information? Är det över huvud taget ok att ta någon annans alster och mata in i en chattbot, där villkoren mycket väl kan omfatta att AI-företaget får spara och använda texten som de vill?

I det här kapitlet tittar vi närmare på vilka möjligheter som finns när det gäller att använda chattbottar för att underlätta och snabba upp arbete med att bedöma uppsatser. Kapitlet är skrivet av en lärare i matematik och fysik, som har begränsad erfarenhet av att bedöma uppsatser. Författarens kunskaper om juridik när det gäller upphovsrätt och GPDR är också begränsade. Det finns alltså all anledning att också använda sitt eget omdöme vid läsning och användning av det som står här.

---- 

## Kan jag skicka en elevuppsats till en chattbot?
En bra tumregel är att inte skriva något till en chattbot som du inte skulle kunna posta på Facebook. Sett ur det perspektivet bör man tänka sig för både en och två gånger innan elevuppsatser lämnas vidare.

Ur juridiskt perspektiv är det förmodligen två aspekter som är värda att titta närmare på. Det ena är personuppgifter eller andra känsliga uppgifter, och det andra är upphovsrätt.

### Upphovsrätt och verkshöjd
När det gäller upphovsrätt brukar man tala om ”verkshöjd” för att något ska skyddas av upphovsrätt. Högskolan i Halmstad gör tydligt att deras bedömning är att om lärare vill publicera material som studenter skapat på internet behövs studentens samtycke[^1], men det är inte självklart att samma sak gäller en uppsats om andra världskriget från årskurs 8.

Oavsett ålder och verkshöjd kan man argumentera för att man bör visa respekt för elever och de texter som de skriver, och att ett sätt att göra det är att be om tillåtelse innan texter lämnas vidare. En sådan förfrågan bör förmodligen kort förklara i vilket syfte texten lämnas vidare, och om elever inte är myndiga _kan_ det vara lämpligt att även be om godkännande från vårdnadshavare.

En sådan förfrågan skulle kunna se ut så här:

> För att underlätta arbetet med att bedöma och ge återkoppling på uppsatser vill jag som lärare ta stöd av AI-teknik. Det gör det möjligt för mig att ge bättre återkoppling och säkrare bedömningar utan att det tar mer tid, men det innebär också att din uppsats kan komma att användas för att träna nya AI-tjänster. Kryssa i rutan nedan om det är ok att använda AI-stöd när jag bedömer och ger återkoppling på din uppsats.

### Personuppgifter och andra känsliga uppgifter
Om en uppsats innehåller personuppgifter eller andra känsliga uppgifter måste de rensas bort innan uppsatsen skickas till en chattbot.[^2] För vissa typer av uppsatser, så som en uppsats om citronsyracykeln, är det sällan något problem. För andra typer av uppsatser kan det kräva att namn eller vissa personspecifika saker byts ut. Och för vissa typer av uppsatser, till exempel på temat ”mina framtidsdrömmar”, skulle så mycket av en uppsats behöva kapas eller bytas ut att det inte är meningsfullt att bedöma det som är kvar.

För att veta om en uppsats innehåller personuppgifter – även en uppsats om citronsyracykeln – behöver man ögna igenom den för hand.[^3]

## Omvandla anteckningar till återkoppling
Oavsett vilken typ av uppsats det handlar om, och hur mycket personuppgifter den än innehåller, finns möjlighet att använda en chattbot för att omvandla egna lösa anteckningar till återkoppling att skicka till eleven. Metoden gör att du har kontroll över vilken data som skickas till chattbotten.

Det utkast till återkoppling som chattbotten ger behöver du läsa igenom och eventuellt justera, om det inte stämmer med den återkoppling du vill ge. Nedan syns två exempel på hur prompt och återkoppling skulle kunna se ut.

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Jag bedömer uppsatser som mina årskurs 8:or har skrivit om orsakerna till andra världskriget. Kan du ge mig utkast på återkoppling till en uppsats utifrån anteckningarna nedan?
> - Bra: tydlig struktur med introduktion, huvuddel och slutsats.
> - Fördraget i Versailles är med. Bra.
> - Språkstil: "en kille som hette Adolf Hitler", "Dessa två länder blev kompisar"
> - Bra: Japans roll i kriget. Glöms ofta bort.
> - Kunde ha inkluderat mer om de ekonomiska orsakerna till kriget.
> - Nationernas Förbund: Varför kunde de inte stoppa kriget?
> - Jättebra: Tar med nationalism och ideologi som orsaker.
> - Källor: Bra med källor men använd inte Wikipedia som enda online-källa.
> **Chattbot:** Hej [Elevens Namn],
> Tack för att du delade din uppsats om orsakerna till andra världskriget. Här kommer lite återkoppling som kan hjälpa dig att utveckla din text och dina skrivfärdigheter:
> - **Struktur**: För det första vill jag ge dig beröm för att du har en tydlig struktur i din uppsats med en introduktion, huvuddel, och slutsats. Detta hjälper läsaren att följa dina tankar och argument på ett mycket effektivt sätt.
> - **Innehåll**: Jag uppskattade att du inkluderade information om Fördraget i Versailles. Det är ett centralt ämne när det kommer till orsakerna till andra världskriget. Det var även väldigt bra att du tog upp Japans roll i kriget, eftersom detta ofta glöms bort. Dessutom är det utmärkt att du inkluderade nationalism och ideologi som orsaker till kriget, vilket ger din uppsats ett djup och visar på komplexiteten av händelserna.
> - **Språkstil**: En liten sak att tänka på är språkstilen. Till exempel, använd mer formella uttryck istället för fraser som "en kille som hette Adolf Hitler" eller "Dessa två länder blev kompisar". I en akademisk uppsats är det bra att hålla en mer formell ton.
> - **Ekonomiska orsaker**: Det kan vara värt att inkludera mer information om de ekonomiska orsakerna till kriget, eftersom detta var en viktig faktor. Du kan undersöka hur den stora depressionen och de ekonomiska problemen i Tyskland påverkade krigets utbrott.
> - **Nationernas Förbund**: Ett intressant ämne att undersöka ytterligare är varför Nationernas Förbund inte kunde förhindra kriget. Vad var deras begränsningar och hur bidrog detta till att kriget bröt ut?
> - **Källor**: Slutligen, bra jobb med att inkludera källor. Det är dock viktigt att diversifiera de källor du använder, särskilt när det gäller online-material. Istället för att endast förlita dig på Wikipedia, försök att använda andra källor som akademiska artiklar, böcker eller pålitliga webbplatser.
> Återigen, bra jobb med din uppsats! Du har visat på ett bra förståelse för ämnet. Med lite mer arbete på språkstilen och genom att utforska några ytterligare aspekter kan du göra den ännu starkare.
> Lycka till!
> Vänliga hälsningar,
> [Ditt Namn]

---- 

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Jag bedömer uppsatser som mina årskurs 8:or har skrivit om orsakerna till andra världskriget. Kan du ge mig utkast på återkoppling till en uppsats utifrån anteckningarna nedan? Eleven i fråga är en högpresterande men ängslig elev, och jag vill att negativ återkoppling ska framföras som möjligheter och inte brister.
> - Bra: tydlig struktur med introduktion, huvuddel och slutsats.
> - Fördraget i Versailles är med. Bra.
> - Språkstil: "en kille som hette Adolf Hitler", "Dessa två länder blev kompisar"
> - Bra: Japans roll i kriget. Glöms ofta bort.
> - Kunde ha inkluderat mer om de ekonomiska orsakerna till kriget.
> - Nationernas Förbund: Varför kunde de inte stoppa kriget?
> - Jättebra: Tar med nationalism och ideologi som orsaker.
> - Källor: Bra med källor men använd inte Wikipedia som enda online-källa.
> **Chattbot:** Hej [Elevens Namn],
> Först och främst vill jag tacka dig för det hårda arbete du lagt ner på din uppsats om orsakerna till andra världskriget. Jag är mycket imponerad av din engagemang och insats i ämnet.
> Det som verkligen sticker ut i din uppsats är den tydliga strukturen. Jag uppskattar hur du har delat in din text i en introduktion, huvuddel och slutsats, vilket gör det enkelt för läsaren att följa dina tankar och argument.
> Det är också berömvärt att du inkluderade Fördraget i Versailles, som var en viktig faktor i uppbyggnaden till kriget. Ännu mer imponerande är att du har tagit med Japans roll i kriget, vilket ofta glöms bort. Detta visar att du har tänkt utanför boxen och undersökt kriget från olika vinklar.
> Dessutom är det fantastiskt att du har inkluderat nationalism och ideologi som orsaker till kriget. Detta visar på ett djupt tänkande och en förståelse för komplexiteten i de händelser som ledde till kriget.
> När det gäller språkstilen i din uppsats, kan det vara spännande att utforska olika sätt att uttrycka dig på. Även om informell språkstil kan göra texten mer tillgänglig, kan du överväga att använda mer formellt språk när du diskuterar historiska händelser för att ge din text en mer akademisk ton.
> I framtida uppsatser skulle det vara intressant att se dig utforska ekonomiska aspekter ännu mer, då de ekonomiska orsakerna också spelade en stor roll i andra världskrigets utbrott. Det skulle också vara fascinerande att läsa dina tankar om varför Nationernas Förbund inte kunde förhindra kriget, vilket kan lägga ytterligare djup till din analys.
> Slutligen, när det gäller källor, är det jättebra att du har använt dig av dem för att stödja dina argument. Ett litet tips inför framtiden är att bredda utbudet av online-källor, för att ge din forskning ännu mer trovärdighet. Wikipedia kan vara en bra startpunkt, men det kan vara värt att komplettera med andra källor också.
> Tack än en gång för din fantastiska insats. Jag ser fram emot att läsa fler av dina uppsatser och se dig fortsätta utvecklas som en skicklig och kritisk tänkare.
> Med vänliga hälsningar,
> [Ditt Namn]

## Olika sätt att låta en chattbot bedöma uppsatser

Exemplen nedan utgår från den här (fiktiva) argumenterande texten om kärnkraft.

> Hej alla!
> Jag vill snacka lite om kärnkraft. Jo, jag vet vad ni tänker, ”vad vet väl en tonåring om kärnkraft?”. Men kom igen, det är 2023 och vi har tillgång till en ocean av information. Så här kommer mina tankar om varför jag tycker att kärnkraft kan vara en grym idé.
> För det första, vi behöver seriöst fixa klimatförändringarna. Jag menar, jorden håller på att koka och vi har typ inte tid att chilla. Vet ni hur mycket koldioxid kol och olja spottar ut? En hel del, kan jag säga er. Kärnkraft däremot, det är som en ninja när det kommer till utsläpp - nästan obefintligt.
> Okej, nu kommer ni säga: ”men hallå, vad händer med kärnavfall?” Ja, det är inte direkt smågodis. Men här är grejen, teknologin går framåt. Ni vet väl hur snabbt mobiltelefoner utvecklas? Det är samma med kärnkraft. Det finns redan idéer om hur man kan återanvända kärnavfall och göra det mindre farligt. Vi kan inte bara dissmissa kärnkraft bara för att det finns problem. Det finns problem med allt!
> Sen har vi det här med olyckor. Ja, Tjernobyl och Fukushima var katastrofer. Men, vi lär oss av misstagen. Bilar kraschar också, men vi slutar inte köra bara för det. Vi gör bättre säkerhetsbälten och airbags. På samma sätt kan vi göra kärnkraftverk säkrare.
> Dessutom, kolla på Sverige. Det är kallt här, eller hur? Och vintern, snälla, den tar typ aldrig slut. Vi behöver energi för att värma våra hem och spela Fortnite (eller vad som nu är inne när ni läser det här). Kärnkraft ger oss stabil energi oavsett om det är soligt, blåsigt eller snöstorm.
> Så för att runda av, jag säger inte att kärnkraft är perfekt. Men jag tror det kan vara en del av lösningen. Vi måste tänka på framtiden och kärnkraft kan hjälpa oss att skydda vår planet. Så kom igen, vi unga är framtidens vuxna. Låt oss tänka smart och ge kärnkraft en chans.
> Tack för att ni läste!
> // En 15-årig kärnkraftsfantast

### Second opinion
En risk med att låta chattbottar ge bedöma uppsatser är att man som lärare blir färgad av AI:n bedömning. Ett sätt att komma runt det är att kortfattat skriva ner en egen bedömning innan texten lämnas till en chattbot. Nackdelen med metoden är förstås att tidsvinsterna blir mindre.

### Be om särskild typ av granskning eller återkoppling
Om man som lärare själv brukar läsa eller bedöma uppsatser enligt vissa mönster kan det vara användbart att be chattbotten använda samma metoder. Kanske finns också anledning att granska specifika saker, text- eller innehållsmässigt.

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Nedan är en uppsats av en 15-åring; en argumenterande text om kärnkraft. Ge mig kortfattad återkoppling på texten. Jag vill att följande delar ska ingå i din bedömning: disposition (inklusive inledning och avslut), argumentens tydlighet, språkstil (inklusive språklig korrekthet), och övrigt.
> [uppsatsen]
> **Chattbot:**
> Disposition (inklusive inledning och avslut):  
> Textens disposition är överlag klar och välstrukturerad. Inledningen fångar läsarens uppmärksamhet genom att ta upp författarens ålder och lyfta fram den digitala eran vi lever i. Författaren lyfter fram olika argument och adresserar möjliga motargument i huvuddelen. Avslutningen sammanfattar texten på ett effektivt sätt genom att återknyta till innehållet och uppmana läsarna till handling.
> Argumentens tydlighet:  
> Argumenten är relativt tydliga och lättbegripliga. Författaren talar om klimatförändringar, utsläpp, kärnavfall och olyckor. Argumenten presenteras på ett informellt sätt, vilket kan vara effektivt för att nå en yngre publik, men kanske inte lika övertygande för en äldre eller mer akademisk läsekrets. 
> Språkstil (inklusive språklig korrekthet):  
> Språkstilen är informell och tilltalande, vilket passar åldern på författaren. Den användning av vardagligt språk och slang (t.ex. "grym", "chilla") skapar en personlig och engagerande ton. Det finns inga uppenbara grammatiska fel, men språkstilen är inte så formell som man vanligtvis förväntar sig av en akademisk uppsats.
> Övrigt:  
> Det är uppenbart att författaren är passionerad och engagerad i ämnet, vilket är positivt. Dock skulle det vara värdefullt att inkludera mer konkreta data eller källor för att stödja argumenten, speciellt i en argumenterande text. Att vara 15 år gammal är ingen nackdel, men att förstärka argumenten med vetenskaplig data kan öka trovärdigheten och styrkan i texten.

---- 

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Nedan är en uppsats av en 15-åring; en argumenterande text om kärnkraft. Korrekturläs texten och ge mig en punktlista med eventuella stavfel, grammatiska fel eller upprepningar. Jag vill inte ha någon annan återkoppling.
> [uppsatsen]
> **Chattbot:** Texten är generellt väl skriven och har en informell ton som är passande för en 15-åring. Det finns dock några punkter som kan förbättras, främst gällande grammatik och upprepning:
> 1. **Stavfel**: "dissmissa" bör vara "dissa" eller "avfärda". Det verkar som att författaren har blandat ihop engelskans "dismiss" med ett svenskt slanguttryck. Det skulle vara mer lämpligt att använda "dissa" som ett informellt uttryck, eller "avfärda" för ett mer formellt val.
> 2. **Stavfel/Ordföljd**: "kärnavfall" brukar oftare skrivas som "kärn avfall" i svenskan.
> 3. **Grammatik**: "För det första, vi behöver seriöst fixa klimatförändringarna." Bör skrivas som "För det första behöver vi seriöst fixa klimatförändringarna." Det är mer grammatiskt korrekt att placera subjektet "vi" efter "För det första".
> 4. **Upprepning**: Ordet "typ" används två gånger ("vi har typ inte tid att chilla" och "den tar typ aldrig slut"). Även om det här är en informell text och "typ" är ett vanligt fyllnadsord i ungdomars talspråk, kan det vara bra att undvika överdriven användning av fyllnadsord i skrift.
> 5. **Grammatik**: "Så för att runda av, jag säger inte att kärnkraft är perfekt." Bör skrivas som "Så för att runda av, säger jag inte att kärnkraft är perfekt." Det är mer grammatiskt korrekt att placera subjektet "jag" efter "Så för att runda av".

(Observera den felaktiga återkopplingen i punkt 2.)

### Återkoppling utifrån betygskriterier
En stark begränsning med chattbottar och språkmodeller är att det inte går att se hur de kommit fram till sina svar. Därmed är det också mycket svårt att veta om en chattbot använder betygskriterier på ett lämpligt sätt – även om de anges explicit i en prompt. Det är därmed mycket tveksamt om det är lämpligt att använda chattbottar för att utvärdera uppsatser mot betygskriterier, men det skulle kunna vara en användbar second opinion om läraren redan gjort en egen bedömning.

Det är värt att notera att utvärdering mot betygskriterier inte behöver handla om att ge betyg, utan skulle kunna handla om att hitta saker att utveckla. (Och man kan fundera över hur meningsfullt det är att ge betygsbeteckningar på enskilda uppsatser.)

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Här nedanför är en argumenterande text om kärnkraft skriven av en 15-åring. Kan du ge återkoppling på texten utifrån betygskriterierna i årskurs 9?
> [uppsatsen]
> **Chattbot:** Den argumenterande texten skriven av den 15-åringen är ett exempel på en skoluppgift, och jag kommer att ge återkoppling utifrån de betygskriterier som ofta används i svensk skolor för årskurs 9.
> 1. **Innehåll och ämneskunskap**
> 	2. Eleven har valt ett relevant ämne (kärnkraft) och försöker koppla det till aktuella problem som klimatförändringar.
> 	2. Eleven har visat en grundläggande förståelse för ämnet, även om informationen är något ytlig.
> 	3. Det skulle vara bra att inkludera mer detaljerad och specificerad information för att styrka argumenten.
> 2. **Struktur och sammanhang**
> 	1. Texten är relativt väl strukturerad. Eleven introducerar ämnet och avslutar med en sammanfattning.
> 	2. Det finns tydliga stycken som behandlar olika aspekter av ämnet.
> 	3. En ytterligare utveckling av varje argument med exempel eller data skulle hjälpa till att ge djup till texten.
> 3. **Språk och stil**
> 	1. Språket är informellt och tilltalande, vilket gör texten lätt att ta till sig.
> 	2. Eleven använder sig av vardagligt språk ("snacka", "grym", "typ"), vilket kan vara effektivt för att engagera jämnåriga, men det kan vara värt att överväga en mer formell ton om texten är avsedd för en akademisk uppgift.
> 4. **Källkritik och användning av källor**
> 	1. Texten innehåller inte några direkta källor eller referenser. För en argumenterande text, speciellt på ett sådant tekniskt och komplicerat ämne som kärnkraft, skulle det vara väldigt användbart att inkludera några pålitliga källor för att stödja argumenten.
> 5. **Kritiskt tänkande**
> 	1. Eleven har visat förmåga att tänka kritiskt genom att väga för- och nackdelar av kärnkraft.
> 	2. Dock, det kritiska tänkandet kan ytterligare förstärkas genom att undersöka och presentera fler perspektiv, och genom att använda konkret data och exempel för att stödja argumenten.
> Sammanfattningsvis, texten är ett gott exempel på en elevs förmåga att engagera sig i ett aktuellt ämne och presentera argument på ett tilltalande sätt. För att höja kvaliteten på texten och möta högre betygskriterier, rekommenderas det att eleven utvecklar sina argument med mer detaljerad information, inkluderar källor, och överväger användning av ett mer formellt språk.

För att öka sannolikheten att chattbotten faktiskt utgår från betygskriterierna kan de klistras in i prompten:

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Här nedanför är en argumenterande text om kärnkraft skriven av en 15-åring. Kan du ge återkoppling på texten utifrån betygskriterierna i årskurs 9, inklistrade nedan?
> [uppsatsen]
> [relevanta delar av betygskriterier i svenska årskurs 9]
> **Chattbot:** Den text som 15-åringen har skrivit är argumenterande och tar upp flera viktiga aspekter av kärnkraft. Låt oss bryta ner det utifrån betygskriterierna.
> 1. **Struktur och innehåll**: Texten har en tydlig struktur med en inledning där skribenten presenterar ämnet, följt av flera argument som stödjer skribentens åsikt, och avslutar med en sammanfattning och uppmaning. Strukturen är väl fungerande.
> 2. **Språklig variation och anpassning till mottagare**: Skribenten använder ett informellt språk som är lämpligt för att engagera jämnåriga. Det finns en god variation i språket, med metaforer som ”kärnkraft är som en ninja” och ett mer ungdomligt språk som ”grym idé”. Detta kan ses som en god anpassning till en yngre målgrupp.
> 3. **Argument**: Skribenten framför flera argument som talar för kärnkraft, inklusive dess låga koldioxidutsläpp, teknologiska framsteg, och behovet av stabil energi. Dock kunde argumenten ha varit mer konkret underbyggda med data eller källor. Därför kan argumenten ses som relativt väl underbyggda, men inte i den högsta graden.
> 4. **Källor och informationssökning**: Skribenten nämner att teknologin utvecklas och att det finns idéer om att återanvända kärnavfall, men det saknas konkreta exempel eller källhänvisningar. Detta är en svag punkt i texten enligt betygskriterierna.
> 5. **Språkliga normer**: Skribenten följer i huvudsak språkliga normer, men det informella språket och avsaknaden av mer formell terminologi kan vara mindre lämpligt i ett mer akademiskt eller formellt sammanhang.
> Sammanfattningsvis skulle jag säga att texten närmar sig betygskriterierna för ett C. Den har en fungerande struktur, relativt god språklig variation, och relativt väl underbyggda argument. För att närma sig betyg A skulle det vara bra att inkludera mer konkret information, källhänvisningar, och potentiellt använda ett något mer formellt språk för att ge texten större tyngd i argumentationen.

Notera att chattbotten uttrycker sig i termer av betyg utan att det efterfrågades i prompten, och ger även förslag på vad som behövs för att få en högre bedömning mot betygskriterierna. Det är inte alls säkert att det är bästa formen för återkoppling. Nedan är ett exempel där chattbotten instrueras tydligare att lyfta fram styrkor och svagheter.

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Här nedanför är en argumenterande text om kärnkraft skriven av en 15-åring. Kan du ge återkoppling på texten utifrån betygskriterierna i årskurs 9, inklistrade nedan? Skriv återkopplingen så att det framgår vad styrkorna med texten är och vad eleven tjänar mest på att arbeta vidare med.
> [uppsatsen]
> [relevanta delar av betygskriterier i svenska årskurs 9]
> **Chattbot:** Hej!
> Först och främst, bra jobbat med att skriva en argumenterande text om ett så viktigt ämne som kärnkraft!
> **Styrkor:**
> 1. **Engagerande och personlig stil**: Din text har en personlig ton som engagerar läsaren. Det är bra att du inleder med en hälsning och avslutar med tack. Användningen av ett informellt språk gör texten lättillgänglig.
> 2. **Struktur**: Texten har en tydlig struktur med en inledning där du presenterar ämnet, flera stycken som behandlar olika aspekter av kärnkraft, och ett avslutande stycke där du sammanfattar dina tankar.
> 3. **Argumentering**: Du använder dig av flera argument för att stödja din ståndpunkt om kärnkraft, till exempel dess låga koldioxidutsläpp jämfört med fossila bränslen, teknologisk utveckling som kan lösa problemet med kärnavfall, och behovet av stabil energiförsörjning i kalla klimat.
> **Områden att arbeta vidare med:**
> 1. **Underbyggda argument**: För att nå högre betyg (A och C) behöver dina argument vara mer underbyggda. Detta kan du göra genom att inkludera mer specifik information, data, eller exempel. Till exempel, när du nämner att kärnkraft har låga koldioxidutsläpp, skulle det vara starkt att inkludera några siffror som jämför utsläppen från kärnkraft med andra energikällor.
> 2. **Källhänvisningar**: En viktig aspekt som saknas i din text är källhänvisningar. När du hävdar att teknologin går framåt och det finns idéer för hur man kan återanvända kärnavfall, skulle det vara bra att ange var du har fått denna information ifrån. Detta skulle stärka dina argument och hjälpa dig att uppfylla kriterierna för högre betyg.
> 3. **Språklig variation**: Även om ditt informella språk är engagerande, kan du överväga att inkludera en större variation av ord och uttryck. Detta skulle inte bara göra texten mer intressant, utan också visa på ett bredare ordförråd, vilket är ett kriterium för högre betyg.
> 4. **Mottagaranpassning**: Tänk på att anpassa texten efter mottagaren. Om texten riktar sig till en bredare publik eller personer som kanske inte är bekanta med ämnet, kan det vara värt att förklara vissa termer eller koncept lite mer ingående.
> Genom att arbeta med dessa punkter kan du förbättra din text ytterligare. Fortsätt med det goda arbetet!
> Vänliga hälsningar,
> ChatGPT

I exemplet nedan instrueras chattbotten att ge återkoppling utifrån betygskriterierna, men också att återkopplingen ska ske utan att betyg eller värdeord i betygskriterierna nämns. Avsikten med detta är att förhindra att återkopplingen signalerar en viss betygsnivå. Dels kan en sådan betygsnivå vara felaktigt bedömd av chattbotten, dels finns anledning att försöka styra fokus till lärande och utveckling snarare än betygsnivåer.

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Här nedanför är en argumenterande text om kärnkraft skriven av en 15-åring. Kan du ge återkoppling på texten utifrån betygskriterierna i årskurs 9, inklistrade nedan? Skriv återkopplingen så att det framgår vad styrkorna med texten är och vad eleven tjänar mest på att arbeta vidare med. Återkopplingen ska inte nämna betygssteg eller de fetstilade orden i betygskriterierna.
> [uppsatsen]
> [relevanta delar av betygskriterier i svenska årskurs 9]
> **Chattbot:** Hej!
> För det första, bra jobbat med din text om kärnkraft! Det är tydligt att du har engagerat dig i ämnet och vill dela med dig av dina tankar.
> Styrkor:
> 1. **Personlig stil**: Du använder ett informellt och personligt språk som gör texten engagerande och lätt att relatera till. Det är särskilt effektivt för att nå ut till jämnåriga läsare.
> 2. **Struktur**: Texten har en klar struktur, med en introduktion där du presenterar ämnet, flera stycken där du diskuterar olika aspekter av kärnkraft, och ett avslutande stycke där du sammanfattar dina tankar. Det hjälper till att hålla läsaren engagerad och gör det lätt att följa dina argument.
> 3. **Argumentation**: Du tar upp och diskuterar flera vanliga invändningar mot kärnkraft på ett balanserat sätt. Det stärker din argumentation när du inte bara talar om fördelarna utan också erkänner och bemöter kritik.
> Områden att arbeta vidare med:
> 1. **Mer underbyggda argument**: För att stärka din argumentation ytterligare, kan det vara bra att inkludera mer fakta och data som stöder dina påståenden. Till exempel, när du pratar om kärnkraft som ett sätt att minska koldioxidutsläpp, kunde du inkludera några siffror eller studier som visar detta.
> 2. **Källhänvisningar**: I din text nämner du att teknologin går framåt och att det finns idéer för hur man kan återanvända kärnavfall. Det är bra, men det skulle stärka ditt argument om du kunde inkludera några källhänvisningar eller exempel på dessa teknologier. Det hjälper också till att visa att du har gjort research och att din information är trovärdig.
> 3. **Språklig variation**: Även om din informella stil är engagerande, skulle texten kunna dra nytta av lite mer variation i språket. Använda några mer avancerade eller ämnesspecifika ord kan ge texten ytterligare tyngd och seriösitet där det behövs.
> Sammantaget är det en mycket bra text med en tydlig struktur och engagerande stil. Genom att lägga till mer fakta, källhänvisningar och lite mer språklig variation kan du göra din argumentation ännu starkare.
> Fortsätt så, du har en stark röst som skribent!
> Med vänliga hälsningar,
> ChatGPT

I exemplet nedan instrueras chattbotten att ge ett betyg på uppsatsen, vilket kan vara användbart exempelvis som en second opinion.

> Exempel från ChatGPT (GPT-4, maj 24)
> **Jag:** Här nedanför är en argumenterande text om kärnkraft skriven av en 15-åring, och även betygskriterierna i årskurs 9. Vilket betyg bör uppsatsen få?
> [uppsatsen]
> [relevanta delar av betygskriterier i svenska årskurs 9]
> **Chattbot:** För att utvärdera den argumenterande texten som är skriven av en 15-åring i förhållande till betygskriterierna för årskurs 9, kan vi bryta ner texten och dess element i förhållande till kriterierna:
> 1. **Struktur och innehåll**: Texten har en tydlig och informell introduktion som engagerar läsaren. Den har också en logisk struktur där skribenten presenterar olika argument för kärnkraft. Texten avslutas med en sammanfattning och tack till läsaren. Detta visar att strukturen och innehållet är fungerande.
> 2. **Språklig variation**: Språket är informellt, och skribenten använder en konversationell ton. Skribenten använder också liknelser och humor för att engagera läsaren. Detta indikerar en viss språklig variation men inte på en mycket hög nivå.
> 3. **Anpassning till syfte, mottagare, och sammanhang**: Texten är skriven i en stil som är lätt att relatera till för jämnåriga, vilket är lämpligt för skribentens ålder. Syftet, att argumentera för kärnkraft, är tydligt genom hela texten.
> 4. **Argumentation**: Skribenten använder några underbyggda argument, men saknar djup och detaljer i sin argumentation. Skribenten tar upp både positiva och negativa aspekter av kärnkraft, men stöder inte sina påståenden med specifika data eller källor.
> 5. **Informationssökning och källhänvisningar**: Texten nämner inte några specifika källor, och det finns ingen hänvisning till var skribenten har fått sin information från.
> Sammanfattning:
> Texten uppfyller kriterierna för betyg E i termer av struktur och språklig variation. Den har dock inte den detalj och djup som krävs för betyg A, och saknar också källhänvisningar. Texten ligger någonstans mellan betygskriterierna för E och C, men på grund av bristen på djup i argumentation och avsaknad av källhänvisningar, skulle jag föreslå att texten bör få ett betyg som är närmare E än C.
> **Jag:** Vad tänker du om att ge betyg på en uppsats så här? Törs jag använda ditt svar och ge till eleven?
> **Chattbot:** Att ge betyg på en uppsats är ett viktigt ansvar som bör göras med omsorg och eftertanke. Som en AI, kan jag ge en generell analys baserad på textens egenskaper och betygskriterier, men det är viktigt att komma ihåg att jag inte har den mänskliga förmågan att förstå kontexten eller de individuella omständigheterna kring eleven. Därför bör mitt svar användas som en referens eller ett verktyg, men inte som det slutgiltiga beslutet.
> Om du är lärare och ansvarar för att bedöma elevers arbete, skulle jag rekommendera att du också tar hänsyn till följande:
> 1. **Elevernas utveckling**: Hur har eleven utvecklats över tid? Har det skett någon förbättring jämfört med tidigare arbeten?
> 2. **Individuella omständigheter**: Är det något du känner till om elevens bakgrund eller situation som bör beaktas vid bedömningen?
> 3. **Feedback**: Ge konstruktiv feedback till eleven. Detta är kanske det mest värdefulla inslaget i bedömningen. Hjälp eleven att förstå vilka delar av texten som var starka, samt var det finns utrymme för förbättring.
> För att ge en rättvis och balanserad bedömning är det också bra att ha en dialog med kollegor eller att följa etablerade riktlinjer och praxis inom skolan.
> I slutändan är det viktigt att betyget och feedbacken ges med elevens bästa intresse i åtanke, och att det hjälper eleven att växa och utveckla sina färdigheter. Mitt svar kan användas som en utgångspunkt, men jag rekommenderar att du använder din professionella bedömning och erfarenhet för att ge ett slutligt betyg.

Det är tänkvärt hur villig chattboten är att ge betyg på en uppsats. Det är också intressant hur den inte verkar skilja mellan betyg och återkoppling (vilket i och för sig kanske inte är konstigt när man ber om ett betyg på en uppsats).

## Andra tankar om bedömning av uppsatser med chattbottar

### Hur konsekvent bedömer chattbottar?
Att be chattbottar betygsätta uppsatser väcker direkt frågan hur konsekvent sådan betygsättning blir. Prompten ovan (där betyg direkt efterfrågades) testades fem gånger i rad med GPT-4 och fem gånger med GPT-3.5 med följande resultat:

* GPT-4: I fyra fall bedömdes uppsatsen ligga mellan E och C, men närmare E. I ett fall blev bedömningen ”ett betyg närmare C”.
* GPT-3.5:
	* En bedömning med E
	* Två bedömningar med ”vissa av kriterierna för C”
	* En bedömning med C
	* En bedömning med ”C–B” (vilket var extra intressant eftersom betyget B hade klippts bort från kriterierna i prompten).

En undersökning med 5 + 5 bedömningar av chattbottar är för liten för att säga något om hur stor variation det är i bedömningen, men redan från dessa resultat går det att dra slutsatsen att bedömningen varierar även med exakt samma fråga. (Och detta är utan att ta hänsyn till om chattbotten gör en _korrekt_ bedömning – det handlar bara om hur konsekvent den är.)

Det är alltså med stor försiktighet man ska be chattbottar att bedöma uppsatser i termer av betyg – det är risk att svaren leder läraren fel, om man inte är väl ankrad i sin egen bedömning först.

Man skulle däremot kunna fantisera om att göra bedömningar på gruppnivå eller till och med nationell nivå: Om man kan anta att felbedömningar tar ut varandra, och de inte har någon betydelse för enskilda elever, kan det vara ett effektivt sätt att bedöma tusentals uppsatser och se hur bedömningar skiljer sig mellan grupper eller över tid. Innan något sådant kan göras behöver man dock jämföra chattbottars bedömningar med de som lärare gör. Vissa sådana jämförelser har gjorts – exempelvis en norsk undersökning från februari 2023 som visade att bedömningar var ”påfallande lika”.[^4]

### Elever som själva får återkoppling från chattbottar?
Vad händer om elever själva ber en chattbot om återkoppling och bearbetar en uppsats i flera omgångar innan den lämnas in? Metoden skulle kunna testas i senare årskurser, där elever blivit lite mer självständiga i sin skrivprocess och förhoppningsvis kan förhålla sig på ett sunt sätt till återkoppling som de får.

I ett sådant läge finns all anledning att fundera över om betygskriterier bör finnas med i prompter där man ber om återkoppling. I många lägen är det troligtvis bättre att fokusera återkoppling på specifika delar av skrivandet, där till exempel disposition, stil, språkflyt, ordval eller annat hamnar i strålkastarljuset – inte var på skalan A–F en uppsats hamnar.

En metod skulle kunna vara att läraren ger eleverna en uppsättning med genomtänkta prompter som kan användas i olika delar av skrivprocessen, och att den samlingen prompter kan diskuteras, förbättras och utökas efter hand.

[^1]:	Se [https://www.hh.se/student/innehall-a-o/upphovsratt.html][2]

[^2]:	Under förutsättning att data lämnar EU, vilket är fallet för de allra flesta chattbottar.

[^3]:	I teorin skulle en chattbot förmodligen kunna avgöra om det finns personuppgifter eller andra känsliga uppgifter i en uppsats, men så länge chattbottar bor på servrar i USA hjälper det inte så mycket. Den dagen enkla chattbottar finns på ens egen dator öppnas nya möjligheter.

[^4]:	[https://www.nrk.no/sorlandet/bruker-robot-til-a-rette-oppgaver-og-setje-karakterar-1.16281165][3]

[1]:	https://github.com/Itangalo/AI-och-skolan
[2]:	https://www.hh.se/student/innehall-a-o/upphovsratt.html
[3]:	https://www.nrk.no/sorlandet/bruker-robot-til-a-rette-oppgaver-og-setje-karakterar-1.16281165 "NRK: Robot sette karakteren til Amanda - resultatet overraska"
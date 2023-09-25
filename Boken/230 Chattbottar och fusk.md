# Chattbottar och fusk
_Uppdaterat 2023-09-02._

_Det här kapitlet är skrivet av Johan Falk. På bokens projektsida [github.com/itangalo/AI-och-skolan][1] kan du föreslå nya kapitel och förbättringar till befintliga kapitel._

I det här kapitlet diskuteras fusk med chattbottar, inklusive tankar om hur det kan förebyggas och hanteras. Det innehåller också tankar om vad det betyder att chattbottar kan genomföra många av de saker som vi använder som betygsunderlag i skolan.

---- 

Skola handlar mycket mer om undervisning och lärande än om bedömning och betyg, men betygsättning är förmodligen den skarpaste myndighetsutövningen som en lärare genomför. Med tanke på hur ofta termer som likvärdig betygsättning, betygsinflation och glädjebetyg nämns i debatt om skolan (och hur sällan saker som nyfikenhet, lärande och att utvecklas nämns) är det inte konstigt att nyheter om chattbottar och skola framför allt handlar om _fusk_.

## Fusk?
Fusk kan betyda många olika saker, och redan nu är det värt att poängtera att det inte behöver vara fusk att använda chattbottar i skrivuppgifter. Man kan jämföra med att använda stavningskontroll vid uppsatsskrivning eller miniräknare på matteprov. I vissa lägen är det helt ok, och i andra räknas det som fusk.

Med “fusk” menas i det här kapitlet att medvetet försöka lura eller vilseleda läraren, till exempel genom att en elev låter en chattbot skriva en hemuppgift och säger till läraren att hen själv skrivit den.

Elever har förmodligen genom alla tider fuskat med inlämningsuppgifter, genom att låta kompisar skriva dem, låta betalda spökskrivare skriva dem, få otillbörligt mycket hjälp från sina välutbildade föräldrar, eller genom att kopiera alster från nätet. Men med chattbottarnas intåg har det blivit _mycket_ enklare att få välskrivna texter om i princip vad som helst som undervisas i skolan, med en kvalitet som både till innehåll och i stil kan uppfattas som att de är skrivna av en elev.

Vad har det för konsekvenser?

### Finns det verktyg som kan berätta om en text är skriven av en chattbot?
Det korta svaret är _nej_.

Det långa svaret är att det finns verktyg som påstår sig kunna berätta hur sannolikt det är att en text är skapad av en människa eller en chattbot. En viktig utgångspunkt för de verktygen är att chattbottar hittar _sannolika_ följder av ord, vilket gör det möjligt att undersöka hur ”naturliga” ordföljder är i texter. Utifrån en sån bedömning, eventuellt kompletterat med andra faktorer, berättar olika AI-detektorer hur sannolikt det är att en text skrivits av en människa respektive AI. Tyvärr är träffbilden långt ifrån perfekt[^1], vilket gör att man som lärare lätt hamnar i lägen där en text _förmodligen_ skrivits av en AI medan eleven bestämt hävdar att hen skrivit texten själv.

OpenAI, som ligger bakom den mest använda chattbotten, arbetar med en metod för att ”vattenstämpla” texter skapade av deras GPT-modeller. Metoden går ut på att använda särskilda mönster i hur ord väljs ut (baserade hur sannolika de är), och att dessa mönster ska kunna kännas igen i efterhand. Enligt vad de själva säger fungerar det bra för att se om texter, och även delar av texter, skapats av GPT-3.5 eller GPT-4. Tyvärr säger de också att vattenmärkningen förstörs om man översätter till ett annat språk.[^2] Vattenmärkningen är också specifik för just OpenAI:s modeller, och gäller inte för andra chattbottar. Den 20 juli 2023 stängde OpenAI sitt verktyg för att detektera om en text är AI-skriven, med hänvisning till att det inte fungerade tillräckligt bra. Det är oklart om de kommer att lansera det igen när tekniken med vattenstämpel är mogen.

Det är svårt att dra någon annan slutsats än att det både är svårt och vanskligt att förlita sig på att ha verktyg som märker om texter är AI-skapade. Med de bästa verktygen hamnar man fortfarande i en katt och råtta-lek där skickliga elever hittar nya sätt att gå runt detektorer, och det fortfarande är problematiskt att förhålla sig till påståendet att en text ”med 80 procents säkerhet” är skriven av en AI. En studie från juni 2023 drar den här slutsatsen: ”The researchers conclude that the available detection tools are neither accurate nor reliable and have a main bias towards classifying the output as human-written rather than detecting AI-generated text. Furthermore, content obfuscation techniques significantly worsen the performance of tools.”[^3]

Ett par tillägg, för tydlighetens skull:

* AI-skapade texter är nyskrivna, och kan inte upptäckas med vanliga plagiatkontroller.
* Chattbottar kan inte användas för att säga om en text är AI-skapad eller inte. (Många chattbottar svarar med glädje på sådana frågor, men man kan inte lita på svaren.)

### Var går gränsen för fusk?
Läraren Matt Miller har skapat en lista som sätter fingret på hur svårt det är att prata om fusk med chattbottar som en enda sak, och samtidigt lyckas peka på hur chattbottar kan vara användbara i en skrivprocess.[^4] Listan ser ut så här i svensk översättning, med ”mest AI-skapat” längst upp och ”mest människo-skapat” längst ner.

1. Eleven frågade en chattbot, kopierade svaret och skickade till läraren.
2. Chattbotten gav ett svar, eleven läste och redigerade, och skickade till läraren.
3. Eleven bad om flera svar från en chattbot, använde de bästa delarna, redigerade, och skickade till läraren.
4. Eleven gav huvuddragen till en chattbot. Chattbotten skapade ett utkast och erbjöd återkoppling för att förbättra.
5. Eleven använde chattbot eller internet för att samla idéer, och skrev sedan och skickade till läraren.
6. Eleven skrev all text själv utan att använda en chattbot eller internet.

Till listan hör också de här frågorna:

* Vilka av dessa fall skulle du klassa som fusk?
* Vilka av dessa fall är relevanta för elevens framtida arbetssätt?
* Vilka av dessa fall stämmer med hur du själv skulle arbeta?

Det är lätt att säga att det är fusk när en elev lämnar in en text skriven av en chattbot, och säger till läraren att hen själv har skrivit den. Men en chattbot kan också vara en redaktör som hjälper till att förbättra en text, en idéspruta som ger uppslag för vad man kan skriva och hur man kan skriva, eller ett stöd när man har idéerna men inte lyckas få ner dem i ord på ett strukturerat sätt.

## Vad kan man göra?
Vad man som lärare kan och bör göra när det gäller frågan om fusk och chattbottar har flera svar. Alla utgår från vad syftet är med uppgifter som elever får.

### Övningar eller prov?
Att lägga över skrivande på en chattbot kan leda till dåliga betygsunderlag, men det kan också leda till sämre lärande. Om en uppsats om upplysningstiden var tänkt att vara betygsunderlag _och_ ett tillfälle för elever att samla ihop sina tankar och djupdyka i några av dem, så är förlusten dubbel.

Det viktigaste sättet att motverka fusk måste vara att minska incitamenten för att fuska. Med den betygshets som finns i många delar av skolan är det förmodligen oundvikligt att en del elever kommer att försöka ta genvägar till höga resultat och bra betyg. Genom att koppla bort betygsättningen från inlämningsuppgifter (eller andra aktiviteter) kan det bli lättare att fokusera på lärandet. Jämför:
* ”Inlämningsuppgiften om upplysningstiden ska lämnas in nästa torsdag och är en del av det jag betygsätter i det här avsnittet.”
* ”Om tre veckor har vi det muntliga provet om upplysningstiden. Ett bra tillfälle att få ordning på era tankar är uppsatsen som jag vill att ni lämnar in nästa torsdag.”

Inom bland annat idrott och musik pratar man ofta om _övningar_, och det kan vara ett ord som vi har glädje av i skolan också. Ofta pratar vi om ”uppgifter” (eller ”problem”), vilket signalerar något som ska bli gjort (eller löst). Övningar, däremot, sätter fokus på att det är något man gör för att träna. Det är görandet som är viktigt, inte resultatet.[^5] Kanske kan ett liknande språkbruk hjälpa både lärare och elever att fundera över vad man gör för att lära sig, och vad man gör för att visa upp kunskaper.

### Gör tydligt vad som gäller
Oavsett syftet med uppgifter som genomförs under okontrollerade former är det viktigt att göra tydligt vilka verktyg och metoder som är ok. En elev som lämnar in en lätt redigerad AI-text kan (faktiskt!) tro att det är ett ok sätt att skriva uppsatser, och i så fall handlar det inte om fusk (det vill säga medvetet vilseledande) utan snarare kommunikationsproblem. Att göra förväntningarna tydliga är förstås viktigt även i övningar som inte har med betygsättning att göra, eftersom det påverkar hur eleverna lär sig.

När det gäller övningar som inte blir betygsunderlag kan det vara värt att tillsammans med eleverna diskutera hur de ser på att (exempelvis!) använda chattbottar för att skriva labbrapporter, essäer, recensioner, loggbok med reflektioner eller vad det nu kan vara. Läraren behöver förstås hålla i tyglarna när det gäller arbetssätt, men att diskutera dem kan ge mer förståelse för vitsen med en övning.

På nätet finns exempel på hur lärare låtit elever (eller oftare universitetsstudenter) använda chattbottar i sina arbeten. Eftersom tekniken är så pass ny är det svårt att säga vad som fungerar bra och mindre bra, men punkterna nedan kan ändå ge idéer för saker att utvärdera själv om det känns rimligt. Listan är en kombination av idéer hittade på nätet och nya idéer.

* **Eleven måste ta ansvar för innehållet.** Den här principen går ut på att chattbottar (och i princip vilka andra verktyg som helst) är tillåtna för en inlämningsuppgift. Men: Eleven måste ta ansvar för att det som lämnas in är korrekt – det är alltså elevens ansvar att kontrollera att det inte finns några felaktigheter. Det förekommer också att metoden kombineras med att man får använda chattbottar för högst en viss andel av texten.
* **Redovisa hur du använt chattbottar.** Den här principen går ut på att eleven ska redogöra kort för hur chattbottar (eller andra verktyg) använts, kanske även med de faktiska prompterna eleven använt.
* **Testa olika prompter för att få bra återkoppling från chattbottar.** Den här metoden handlar egentligen om att lära sig använda chattbottar, och att elever _ska_ använda olika prompter för att försöka få texter som ligger allt närmare den typ av text man är ute efter. Metoden är förmodligen bara intressant för de lärare som anser att chattbottar är verktyg som elever ska lära sig att använda.
* **Arbeta med kontinuerlig förbättring av texter.** Den här metoden går ut på att eleven tränar sin förmåga att bearbeta och förbättra en egen text, även med hjälp av chattbottar. Fokus för bedömning är just elevens förmåga att reflektera över textkvalitet och kontinuerligt förbättra den, vilket gör att en logg med reflektioner och målsättningar kan vara ett bra komplement.

När det gäller betygsunderlag lär det vara betydligt mindre utrymme för diskussioner – de kunskaper man som lärare vill se är vad som bestämmer vilka arbetssätt eller verktyg som kan vara tillåtna. Men det finns tillfällen då chattbottar kan användas även i uppgifter som rör betygsunderlag, och det är förstås viktigt att berätta hur ramarna ser ut även då.

Det kan finnas anledning att leta efter sätt att samla betygsunderlag som tillåter att elever använder chattrobotar (eller andra hjälpmedel). Om målet för en uppgift är en muntlig redovisning, en produktidé eller en fungerande lösning på ett problem behöver det inte vara fel om elever tar hjälp från olika håll på vägen.

### Examinera under övervakade former
Om det är viktigt att begränsa vilka verktyg en elev har tillgång till så är det svårt att ha uppgifter som genomförs hemma, eller oövervakat på andra ställen. Redan innan chattbottarnas intåg förekom mer eller mindre sofistikerat fusk med inlämningsuppgifter, och vissa anser att chattbottarna egentligen bara gjort det tydligt att inlämningsuppgifter inte fungerar.

Att genomföra prov eller andra betygsgrundande uppgifter under övervakade former kan betyda olika saker. Till exempel:
* Salsskrivningar med papper och penna. Ingen dator, ingen telefon.
* Skriva uppsatser på nedlåsta datorer.
* Muntliga presentationer, enskilt eller i grupp.

### Följ upp misstänkt fusk
Oavsett hur man arbetar kommer det att finnas fall där man misstänker att elever har fuskat. Ett naturligt men ganska tidskrävande sätt att hantera det är att be elever redogöra muntligt för vad de lämnat in. Om eleven kan göra det på ett sätt som är övertygande, så är det ett trovärdigt sätt att se att eleven har de kunskaper man som lärare är intresserad av. Om eleven inte kan redogöra för det hen lämnat in, så är det ett trovärdigt sätt att se att eleven _inte_ har de kunskaperna. Huruvida eleven fuskat eller inte, och med vilka verktyg, blir sekundärt – det är elevens kunskaper som hamnar i fokus.

I vissa ämnen, eller vissa delar av ämnen, är det svårt att arbeta på det viset.[^6] Och hur man hanterar frågor om fusk handlar ofta om både personliga förhållningssätt och policyer på skolan.

## Vad är det vi testar?
Sedan ChatGPT lanserades har det förekommit nyheter om att chattbottar klarat ett antal olika examens- eller anställningsprov. Det väcker förstås frågor av många slag, och en av dem är _vad är det vi testar_? Att [ChatGPT får godkänt betyg på en läkarexamen][6] – betyder det att den kan börja arbeta som läkare? Givetvis inte: Att vara en kompetent läkare omfattar mycket mer än de saker som vi kan mäta på ett examensprov, så som att vara lugn även med oroliga människor, använda sina fingrar för att undersöka en svullen arm och att fungera i ett team med annan personal på sjukhus. Det som läkarexamen mäter är en _proxy_ – något som vi satt in i stället för faktiska uppgifter som läkare ställs inför, och där höga resultat ofta överensstämmer med att man också blir en kompetent läkare.

Samma sak gäller med många andra typer av kunskapsmätningar vi gör i skolan. Vitsen med att lära sig matematik är inte att bli bra på att skriva matteprov, och vitsen med att läsa historia är inte (enbart) att kunna skriva uppsatser om historiska skeenden. Det som chattbottar lett till är att en del av dessa indirekta kunskapsmätningar slutat att fungera. I bästa fall leder det till att vi drivs mot att ha kunskapsmätningar som ligger närmare och närmare de faktiska syftena med ämnena: Matteprov som handlar om att förstå och lösa verkliga problem, och historiaprov där man får leta fritt bland källor.

Men det är inte alla hotade sätt att mäta kunskaper som är proxy-mätningar – indirekta mätningar av elevers kunskaper. En skrivuppgift i svenska eller engelska kan mycket väl ha som mål att se hur väl eleven hanterar språket – inte att se vilka kunskaper eleven har i litteraturhistoria. Och en uppgift inom programmering kan handla om just hur väl eleven klarar av att skriva kod. Att en chattbot kan göra dessa uppgifter minst lika bra som de flesta elever ger oss anledning att fundera över hur meningsfullt det är att lära sig just de sakerna i skolan. I vissa fall – som att kunna skriva välformulerade texter – är svaret med stor sannolikhet att det är både meningsfullt och viktigt, även om maskiner också kan göra det. När det gäller programmering är det fullt möjligt att AI-teknik kommer att göra vissa kunskaper irrelevanta (och samtidigt andra mer relevanta).

[^1]:	Se [https://www.scribbr.com/ai-tools/best-ai-detector/][2] för en jämförelse från 2 juni 2023.

[^2]:	[https://axrp.net/episode/2023/04/11/episode-20-reform-ai-alignment-scott-aaronson.html][3]

[^3]:	[https://arxiv.org/abs/2306.15666][4]

[^4]:	Se [https://ditchthattextbook.com/ai/#tve-jump-18606008967][5] för original.

[^5]:	I både idrott och musik är det också naturligt att övningar inte är direkt kopplade till ”huvuduppgiften”: Övningar på en fotbollsträning kan ha väldigt lite gemensamt med hur en fotbollsmatch ser ut, och sångövningar mycket lite med ett framträdande. På samma sätt kanske ordet ”övningar” i skola kan ge mer acceptans för att träna på nischade färdigheter.

[^6]:	I matte, till exempel, kan det vara meningslöst att be en elev förklara hur hen löst ett specifikt problem. Det är fullt möjligt att eleven (i efterhand) lärt sig lösa det specifika problemet, utan att ha de kunskaper som krävs för att lösa liknande problem.

[1]:	https://github.com/Itangalo/AI-och-skolan
[2]:	https://www.scribbr.com/ai-tools/best-ai-detector/
[3]:	https://axrp.net/episode/2023/04/11/episode-20-reform-ai-alignment-scott-aaronson.html "XARP: 'Reform' AI Alignment with Scott Aaronson"
[4]:	https://arxiv.org/abs/2306.15666 "Arxiv: Testing of Detection Tools for AI-Generated Text"
[5]:	https://ditchthattextbook.com/ai/#tve-jump-18606008967
[6]:	https://www.dailymail.co.uk/health/article-11732687/The-AI-doctor-ChatGPT-passes-gold-standard-medical-exam.html "Artikel i Daily Mail"
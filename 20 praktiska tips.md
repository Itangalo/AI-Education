# Del 2: Använda ChatGPT i praktiken
Som beskrivits i del 1 av boken finns all anledning att använda omdöme för att avgöra om det ChatGPT skriver är lämpligt att använda, och i så fall i vilka delar.  Var vaksam på de fyra typerna av AI-dumheter:

1. Språkmässiga dumheter.
2. Faktamässiga dumheter.
3. Värderings- och perspektivdumheter.
4. Pedagogiska dumheter.

Alla dessa dumheter finns representerade i exemplen i den här delen av boken – dels för att avspegla hur svar från ChatGPT ser ut, dels för att göra det lättare att komma ihåg att alltid använda ditt omdöme.

## 4: Saker du inte ska göra med ChatGPT

### Lämna inte ut personuppgifter eller andra känsliga uppgifter

Den text som skrivs till ChatGPT skickas till servrar i andra länder och hanteras på sätt som du inte har kontroll över. Det innebär att inga personuppgifter för elever eller andra känsliga uppgifter ska lämnas till ChatGPT.

Punkt.

### Uppmana inte minderåriga elever att skapa konto på OpenAI

Villkoren för att skapa ett konto hos OpenAI, som skapat ChatGPT, omfattar att man ska vara minst 18 år gammal. (Se [openai.com/terms][1].) Att uppmana elever yngre än 18 år att skaffa ett konto är alltså direkt olämpligt. För elever som är 18 år eller äldre behöver man fundera över vad som är lämpligt när det gäller att skaffa konton för onlinetjänster, och det är värt att undersöka om skolan har någon policy.


### Använda inte budskap från ChatGPT utan att granska dem först

Det är kanske lite tjatigt, men du behöver alltid granska och värdera texter från ChatGPT innan de når eleverna. I synnerhet ska du inte använda ChatGPT som en extralärare, som förklarar saker för elever utan att du som lärare ser att det som ChatGPT säger är ok. Exemplet nedan kan göra tydligt varför det är olämpligt.

> **Vad är sannolikheten att slå par med tre tärningar?**
> 
> Sannolikheten att slå par med tre tärningar är 1/6 eller ungefär 0,17. Detta eftersom det finns sex möjliga resultat på en tärning och du vill att två av dem ska vara det samma numret, medan det tredje numret kan vara vilket som helst.

> **Jag förstår inte riktigt. Kan du förklara närmare hur jag ska tänka?**
> 
> Säkerställ att jag förstår din fråga korrekt, du vill veta sannolikheten att slå par med tre tärningar (där två av tärningarna visar samma nummer och den tredje är ett annat nummer) ?
> 
> För att beräkna sannolikheten måste vi veta antalet möjliga utfall som leder till det önskade resultatet, och jämföra det med det totala antalet möjliga utfall.
> 
> Det finns 6 olika nummer på en tärning (1, 2, 3, 4, 5, 6), så det finns 6 möjliga nummer som den första tärningen kan visa. För den andra tärningen måste vi också välja ett av de 6 numrena, men eftersom vi redan har valt ett nummer för den första tärningen så finns det bara 5 möjliga nummer kvar. För den tredje tärningen finns det 6 möjliga nummer kvar att välja.
> 
> Så antalet möjliga utfall som leder till det önskade resultatet (två av tärningarna visar samma nummer och den tredje är ett annat nummer) är 6 \* 5 \* 6 = 180.
> 
> Det totala antalet möjliga utfall är 6 \* 6 \* 6 = 216 (eftersom det finns 6 möjliga nummer för varje tärning).
> 
> Så sannolikheten att slå par med tre tärningar är 180/216 = 1/6 eller ungefär 0,17.

I konversationen ovan uttrycker sig ChatGPT klart och tydligt, och det den säger är *fel*. (Chansen att slå ett par är drygt 40 procent.) När man ber kan ChatGPT till och med motivera sitt svar, på ett sätt som på ytan låter trovärdigt men är inkonsekvent och innehåller felaktiga beräkningar. *Det som ChatGPT är bra på är att låta som en matematiker, inte att vara en matematiker.* Det i sig är en effekt av att ChatGPT:s bild av världen börjar och slutar med text: Den skapar text som stämmer med hur text brukar se ut – och den behöver inte nödvändigtvis vara vare sig logiskt sammanhängande eller stämma med världen som vi människor lever i.

En elev som lämnas att lära sig av ChatGPT kan råka ut för alla möjliga dumheter. I bästa fall blir eleven förvirrad av dumheterna och frågar läraren. Men det är också fullt möjligt att eleven lär sig felaktigheter, utan att du som lärare ens märker när det händer, och att det skapar svårigheter senare.

Det här exemplet rör sakfel som är förhållandevis lätta att upptäcka, men ChatGPT kan kasta ur sig mycket mer dolda misstag som blir till fällor för eleverna. ChatGPT är *inte* en lärare eller instruktör.

## 5: Undervisa om ChatGPT och liknande verktyg
Verktyg liknande ChatGPT har funnits i flera år och används i olika digitala tjänster. ChatGPT ger bättre svar än tidigare verktyg, men en väsentlig skillnad är också att gränssnittet gör tekniken tillgänglig för de stora massorna. Allt pekar mot tekniken fortsätter att utvecklas, och att den blir mer och mer tillgänglig. Därmed är det också rimligt att elever får chans att lära sig om vad verktyg som ChatGPT kan göra – och behovet att använda dem med omdöme.

### Diskutera värderingar och andra icke-explicita budskap

Svar från ChatGPT kan vara utmärkta för att låta elever diskutera vilka värderings- och perspektivdumheter som eventuellt gömmer sig i texten: Vilka antaganden har AI:n gjort? Vilken typ av kultur verkar den utgå från? Finns det aspekter i svaret som utesluter eller förminskar vissa grupper av människor? Vilken typ av värderingar finns dolda under ytan?

Det kan också vara värdefullt att diskutera vad som händer om en eller ett fåtal avsändare får stort inflytande över svar på frågor som människor ställer. Skiljer det sig från hur Google och ett fåtal sociala plattformar dominerar informationsvärlden idag? Hur då, eller varför inte?

I exemplen nedan är de fyra första prompterna avsiktligt parvis identiska.

> **Jag är en tjej på 18 år med höga betyg och funderar på vad jag ska plugga på högskola. Mina föräldrar kommer från Iran, men jag är född i Sverige. Jag tror att jag vill jobba med människor. Kan du ge mig förslag på vad jag ska plugga?**
> 
> Det finns många olika utbildningar som passar för dig som vill jobba med människor. Här är några förslag:
> 1. Socialt arbete: En utbildning inom socialt arbete ger dig kunskap om hur man hjälper människor i svåra livssituationer, exempelvis missbruk, arbetslöshet och ensamhet.
> 2. Psykologi: En utbildning inom psykologi ger dig kunskap om hur människors tankar, känslor och beteenden påverkar deras välbefinnande. Du kan jobba som psykolog inom vård, skola eller företag.
> 3. Pedagogik: En utbildning inom pedagogik ger dig kunskap om hur man undervisar och vägleder barn och unga. Du kan jobba som lärare eller som pedagog inom förskola eller skola.
> 4. Kriminologi: En utbildning inom kriminologi ger dig kunskap om brottslighet och hur man kan förebygga och hantera det. Du kan jobba inom polis, rättsväsende eller brottsförebyggande verksamhet.
> 5. Samhällsvetenskap: En utbildning inom samhällsvetenskap ger dig kunskap om samhällsstrukturer och hur människor påverkas av dessa. Du kan jobba inom offentlig förvaltning, civilsamhället eller forskning.
> 
> Tänk på att det finns många olika inriktningar inom varje utbildning, så undersök noga vad som passar dig bäst. Och även om du har höga betyg är det viktigt att du gör ett val som du trivs med och är intresserad av.

---- 

> **Jag är en tjej på 18 år med höga betyg och funderar på vad jag ska plugga på högskola. Mina föräldrar kommer från Iran, men jag är född i Sverige. Jag tror att jag vill jobba med människor. Kan du ge mig förslag på vad jag ska plugga?**
> 
> Det finns många olika utbildningar som handlar om att arbeta med människor. Här är några förslag:
> 
> * Socionomprogrammet: Detta är en utbildning som ger dig kunskap och färdigheter för att arbeta med människor i socialt arbete. Du lär dig om olika samhällsproblem och hur man hjälper människor att hantera dessa.
> * Psykologprogrammet: Detta är en utbildning som ger dig kunskap om hur människors tanke- och beteendemönster fungerar. Du lär dig också om olika psykologiska terapier och hur man hjälper människor med psykiska problem.
> * Pedagogprogrammet: Detta är en utbildning som ger dig kunskap om hur man undervisar och hjälper människor att lära sig. Du lär dig också om olika pedagogiska metoder och hur man använder dem i olika sammanhang.
> * Sjuksköterskeprogrammet: Detta är en utbildning som ger dig kunskap om hur man hjälper människor med hälsoproblem. Du lär dig också om olika medicinska åtgärder och hur man använder dem för att hjälpa människor att må bra.
> 
> Det är viktigt att du gör research och pratar med olika människor i branschen för att hitta en utbildning som passar dig. Det är också viktigt att kolla upp vilka krav som krävs för att söka till respektive utbildning.

---- 

> **Jag är en kille på 18 år med ganska höga betyg och funderar på vad jag ska plugga på högskola. Jag tror att jag vill jobba med människor. Kan du ge mig förslag på vad jag ska plugga?**
> Ett bra val för dig som vill jobba med människor kan vara en utbildning inom områden som psykologi, sociologi, socialt arbete eller pedagogik. Dessa utbildningar ger dig kunskaper om människors beteende, sociala relationer och utveckling, och ger dig möjlighet att arbeta med olika grupper av människor, till exempel barn, ungdomar eller vuxna. Det kan också vara bra att tänka på vad för slags arbete du är intresserad av, det finns många olika inriktningar inom dessa utbildningar som ger olika möjligheter för arbete.

---- 

> **Jag är en kille på 18 år med ganska höga betyg och funderar på vad jag ska plugga på högskola. Jag tror att jag vill jobba med människor. Kan du ge mig förslag på vad jag ska plugga?**
> 
> Det finns många olika utbildningar som kan vara lämpliga för dig om du vill jobba med människor. Några förslag är:
> 
> * Sociologi: om du är intresserad av att förstå hur människor fungerar i samhället och hur olika grupper påverkas av sociala faktorer.
> * Psykologi: om du är intresserad av att förstå hur människors tanke- och beteendemönster påverkas och hur man kan hjälpa dem att må bättre.
> * Pedagogik: om du är intresserad av att arbeta med barn och ungdomar och hjälpa dem att utvecklas och lära sig.
> * Socialt arbete: om du är intresserad av att arbeta med människor i utsatta situationer och hjälpa dem att hantera olika problem och svårigheter.
> * Kriminologi: om du är intresserad av att förstå orsakerna till brottslighet och hur man kan förebygga och hantera det.
> 
> Det är viktigt att notera att det finns många olika inriktningar inom dessa ämnen, så det är viktigt att undersöka vad som erbjuds på olika högskolor och välja en utbildning som verkligen intresserar dig.

---- 

> ** Kan du beskriva hur det gick till när Sverigedemokraterna kom in i riksdagen i Sverige? Jag skulle vilja veta mer om bakgrunden.**
> 
> Sverigedemokraterna (SD) kom in i riksdagen i Sverige för första gången vid valet 2010. De fick 5,7% av rösterna och 20 mandat. Det var ett historiskt val för partiet, eftersom det var första gången de lyckades komma in i riksdagen.
> 
> Det finns flera faktorer som kan ha bidragit till SD:s framgång vid det här valet. En av de viktigaste är den ökade oro som rådde i Sverige och i Europa under 2000-talets första decennium för migration och invandring. SD har länge kritiserat den svenska regeringens invandringspolitik och hävdat att den lett till ökade problem med integration, brottslighet och kostnader för samhället.
> 
> En annan faktor som kan ha bidragit till SD:s framgång är det ökade missnöjet med det etablerade partierna och den politiska eliten. Många väljare kände sig missförstådda och missförtjänta av de etablerade partierna och såg SD som ett alternativ.
> 
> Det är också viktigt att notera att SD har arbetat hårt för att förändra sin image sedan tidigare år, för att bli mer acceptabelt för väljare och för att få ett större stöd från allmänheten.

### Träna på att granska information

Även försöka ordna referenser till studier – och vad betyder det?

## Planeringshjälp
En av ChatGPT:s starkaste grenar är att ge idéer och inspiration. Man kan be om tio idéer och välja de som känns värda att gå vidare med, eller be om tio till med en lite annan fråga om inget svar passar bra. Det kan vara en bra tillgång när man planerar lektioner, kurser eller undervisningsområden.

### Inspiration till upplägg för lektionsplaneringar
* Upplägg för lektionsplaneringar
* Återkoppling på planeringar
* Idéer för specifika aktiviteter
* Uppslag för hur man kan beskriva eller förklara områden
* Idéer för gymnasiearbeten, temaarbeten, med mera
* Skapa gruppindelningar

## Skapa material

* Skapa texter som elever får bygga vidare på
* Skapa fejkade elevexempel att diskutera
* Skapa exempel som elever kan lära av
* Skapa påståenden som elever får utvärdera och diskutera
* Skapa instuderingsfrågor eller andra frågor till texter
* Skapa quiz-frågor (även med formatering!)
* Utkast till texter
* Få förslag på hur din egen text kan förbättras
* Korta ner, sammanfatta eller göra texter mer engagerande
* Skapa veckobrev

## Programmering

* Skapa enkla datorprogram
* Felsöka datorprogram
* Skapa kod för specifika uppgifter

## Personlig utveckling relaterad till arbetet

* Sammanfatta dokument för att hitta givande läsning
* Få coachning i att utveckla sin skrivförmåga
* Tips på tekniska verktyg och hur man använder dem
* Ge sig själv uppmuntran och motivation

## Annat

* Liva upp lektionen med oväntad konst baserat på undervisningsområdet
* Inspiration till aktiviteter utanför ämnesundervisning
* Skriva rekommendationsbrev
* Översätta enskilda ord, begrepp eller fraser

## (Don’t) try this at home

* Hjälpa elever att skriva bättre – att hitta orden
* Första underlag för återkoppling på elevtexter
* Mail till vårdnadshavare

## ChatGPT och fusk

“Fusk” kan betyda många olika saker, och det är värt att komma ihåg att det inte behöver vara fusk att använda ChatGPT i skrivuppgifter – mer än det behöver vara fusk att använda stavningskontroll eller miniräknare. I vissa lägen räknas det som fusk, i andra inte.

Med “fusk” menas i den här boken att medvetet försöka lura eller vilseleda läraren, och det det är tydligt att ChatGPT gör det enklare för elever att fuska inte minst när det gäller skrivuppgifter. ChatGPT kan skapa texter om det mesta som behandlas i skolan, med en kvalitet som både till innehåll och i stil kan uppfattas som att de är skrivna av en människa. Hur kommer man runt ett sånt problem?

Ett sätt att försöka hindra fusk med hjälp av ChatGPT är att blockera webbtjänsten på skolnätverk. Det är en väg som en del skolor tagit, där det i dagsläget mest omtalade fallet är alla skolor i staten New York. En annan möjlighet är att försöka identifiera vilka texter som är skapade med ChatGPT (eller andra liknande verktyg). Ett verktyg med namnet GPT Zero lanserades i början av 2023, för att göra just detta. Det kollar bland annat om ordföljd i en text är “sannolik”, vilket i så fall pekar mot att texten är skriven av en AI av samma typ som ChatGPT – som väljer ord just med utgångspunkt i hur väl ord och ordföljder passar mot texter de tränats på.

Jag är övertygad om att uppfinningsrika elever kommer att hitta förhållandevis enkla sätt att lura AI-kontroller och ta sig runt blockeringar i nätverk: Det behöver inte vara svårare än att göra lätta bearbetningar av en ChatGPT-text, respektive att dela nätverk från sin telefon. Om man som lärare behöver skriftliga alster från elever, och de används som betygsunderlag, tror jag alltså att man behöver genomföra de uppgifterna på ett övervakat sätt – exempelvis inte hemma. Jag tror också att det finns anledning att undersöka hur uppgifter kan utformas så att exempelvis ChatGPT kan användas som ett verktyg i arbetet, i stället för att klassas som fusk. Andra vägar man kan tänka sig är att försöka minska incitamenten för elever att fuska, men med det fokus som finns på betyg är det en svår kamp.

Oavsett hur man arbetar kommer det att finnas fall där man misstänker att elever har fuskat. Ett naturligt med ganska tidskrävande sätt att hantera det är att be elever berätta om det de lämnat in. Om eleven kan göra det på ett sätt som är övertygande, så är det ett trovärdigt sätt att se att eleven har de kunskaper man som lärare är intresserad av. Om eleven inte kan redogöra för det hen lämnat in, så är det ett trovärdigt sätt att se att eleven *inte* har de kunskaperna. Huruvida eleven fuskat eller inte, och med vilka verktyg, blir sekundärt – det är elevens kunskaper som hamnar i fokus.

I vissa ämnen, eller vissa delar av ämnen, är det svårt att arbeta på det viset. Och hur man hanterar frågor om fusk handlar ofta om både personliga förhållningssätt och policyer på skolan.

I korthet tror jag att det är nyttigt att fundera i de här termerna, när det gäller frågan om fusk med ChatGPT.

* Kan incitamenten för elever att fuska minskas? I många fall är det synonymt med frågan om uppgifter behöver användas som betygsunderlag.
* Kan betygsgrundande uppgifter genomföras på ett övervakat sätt? Det kan handla om salsskrivningar med papper och penna, alternativt dator utan nätuppkoppling, men också exempelvis att frågor ställs muntligt på plats med några elver i taget.
* Kan uppgifter utformas så att ChatGPT är ett tillåtet verktyg? Det är svårt att uppmuntra elever under 18 år att använda ChatGPT, på grund av användarvillkoren, men om målet för en uppgift är en muntlig redovisning eller en fungerande lösning på ett problem behöver det inte vara fel om elever tar hjälp från olika håll på vägen.
* Hur kan man arbeta med att följa upp misstänkt fusk?

Vissa menar att möjligheten att fuska på inlämningsuppgifter funnits länge, och regelbundet utnyttjats av en liten men hängiven eller priviligerad grupp elever. ChatGPT bidrar till att ge fler möjligheter att fuska, vilket gör att problemet måste tas mer på allvar – men också att förutsättningarna blir mer rättvisa.

[1]:	https://openai.com/terms/
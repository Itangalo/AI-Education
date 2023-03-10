# Del 3: Mer om AI

# 3-1: Bakgrunden till ChatGPT
ChatGPT lanserades som en försöksverksamhet (”beta”) den 30 november 2022 av företaget OpenAI, och fick snabbt mycket uppmärksamhet. På bara fem dagar hade antalet användare vuxit till en miljon[^1], något som normalt tar månader eller år även för framgångsrika tekniktjänster[^2].

Tidigare under 2022 hade flera AI-tjänster för bilder också väckt uppmärksamhet. De mest kända av dessa verktygen är DALL-E 2 (också från OpenAI), Midjourney och Stable Diffusion. Även om tidigare AI-tjänster kunnat skapa realistiska bilder (se exempelvis [thispersondoesnotexist.com][3] från 2019), var det först 2022 som man själv kunde skriva en beskrivning nästan vad som helst och få tillbaka en bild som ser bra ut. Även om alla bilder knappast ligger i världsklass finns det också exempel på AI-skapade bilder som [vinner tävlingar mot bilder skapade av människor][4].

Till skillnad från AI för att generera bilder (och [en lång rad andra AI-tjänster][5]) kan ChatGPT räknas som en mer generellt kompetent AI, som inte är tränad för ett specifikt område och klarar av att så skilda saker som att ge kostråd, skriva kod och imitera en Linux-terminal.

Den AI-modell som ligger bakom ChatGPT kallas GPT-3.5 och är en variant av GPT-3 som lanserades redan 2020 – det genomslag som ChatGPT hade beror till stor del på att det blev lätt för vem som helst att använda AI:n. GPT står för ”generative pre-trained transformer” och är en förkortning som OpenAI använder för en serie av sina AI-modeller. De är en typ av modell som kallas _large language model_ (LLM) eller stor språkmodell, som i sin tur använder en mer generell princip som heter artificiellt neuralt nätverk – en teknik som är inspirerad av hur nervceller i våra hjärnor fungerar.

Ofta mäter man kapaciteten i artificiella neurala nätverk i antalet _parametrar_ som de har, vilket ungefär motsvarar de kopplingar som finns mellan nervcellerna i våra hjärnor. Dessa parametrar är värden som ställs in medan AI:n tränas för att ge så bra svar som möjligt. Träning av stora AI-modeller kräver ofantliga mängder data och massor av datorkraft, vilket gör att det i princip bara är stater och stora teknikföretag som kan skapa stora AI-modeller.[^3] Ofta behöver delar av datan också bedömas eller etiketteras av människor, vilket gör den ännu dyrare att framställa. En stor skillnad mellan GPT-3 och GPT-3.5 är just att många texter bedömts av människor, för att ChatGPT ska kunna förstå vad som klassas som olämpliga budskap[^4]. De färdiga är värdefulla (och stöldbegärliga) tillgångar för företaget. Att använda de färdiga modellerna är däremot mycket mindre resurskrävande, och kan ibland göras på vanliga persondatorer.

OpenAI är förtegna med information om ChatGPT. I intervjuer har de angett att modellen tränats på en betydande andel av den text som fanns på internet 2021 (och det är tydligt att den inte hämtar ny information från nätet). Det är svårt att hitta information om hur många parametrar GPT-3.5 har, men GPT-3 har 175 miljarder parametrar.[^5] Två olika källor antyder att GPT-3.5 (och därmed ChatGPT) endast har en hundradel så många parametrar, omkring 2 miljarder, vilket skulle stämma med en del information på OpenAI:s blog.[^6]

OpenAI kommer förmodligen att släppa uppföljaren GPT-4 under 2023. Rykten om hur många parametrar den kommer att ha varierar från lika många som GPT-3 till me än femhundra gånger så många[^7]. Enligt German AI Association hade Beijing Academy of AI och Google redan år 2021 olanserade språkmodeller som omfattar omkring hundra gånger så många parametrar som GPT-3.[^8]

OpenAI började som ett icke vinstdrivande företag, med starkt fokus på att göra AI tillgängligt för många. I samband med att Microsoft gick in i företaget 2019 blev OpenAI vinstdrivande. Försöksversionen av ChatGPT är gratis, och varje ChatGPT-konversation uppges kosta ”några cent” i beräkningar[^9]. Den första februari lanserades [ChatGPT Plus][8] i USA – en betalversion som ger kortare och mer tillförlitlig responstid, och även förtur till nya funktioner och förbättringar. Detta utvidgades till hela världen tio dagar senare.

# 3-2: Hur påverkas vår syn på kunskap?
Det finns tydliga hål i ChatGPT:s kunskaper, och den kan vara löjeväckande självsäker även när den har fel. Samtidigt är det också tydligt att många blir förbluffade av vad AI:n klarar av, och att datorer tagit ännu ett steg in på det område som vi trodde var reserverat för människor.

Vad betyder teknik som denna för vår syn på kunskap?

Det är för tidigt för att kunna ge ett svar på den frågan, inte minst som tekniken fortfarande accelererar. Inte mindre är det en fråga värd att utforska. Det är rimligt att tro att delar av det vi idag tycker är viktiga kunskaper kommer att stöpas om, och vissa saker kommer vi inte längre tycka vara viktiga. Det är också troligt att många saker kommer att vara oförändrade.

En intressant paradox är att ChatGPT, trots sin förmåga att svara på allt möjligt, är så pass otillförlitlig att det är svårt att använda som kunskapskälla för saker som man inte redan kan mycket om eller där man är beredd att lägga ansenlig tid på att dubbelkolla information. Eller: För att använda ChatGPT på ett meningsfullt sätt krävs omdöme, och för det omdömet krävs kunskaper om det man använder ChatGPT till[^10]. En erfaren lärare kan använda ChatGPT som stöd för att göra planeringar, skapa material och få idéer till hur undervisningen kan fungera bättre, men en oerfaren lärare som litar på ChatGPT riskerar att gå i AI-fällor eller slösa bort tid.

Det finns en parallell till tillgången till information på internet som är lite slående: Det sägs ibland att internet har gjort det onödigt att kunna fakta, eftersom man när som helst kan slå upp det man behöver veta. När det gäller trivial fakta (”Vad heter huvudstaden i Azerbajdzjan?”) stämmer det väl, men för att ha nytta av någon djupare information behöver man förstå sammanhangen, kunna koppla ihop olika begrepp, och även ha en känsla för om information man får exempelvis är uppseendeväckande, tvivelaktig eller fullt normal. För att kunna ha nytta av fakta på nätet behöver man själv ha koll på en del fakta. Och för att kunna använda använda ChatGPT som assistent i ett område behöver man själv ha kompetens inom området.

En första gissning är därför att ChatGPT kommer att kunna snabba upp processer med att analysera och sammanfatta texter, och även att skriva välformulerade texter från stolpar eller utkast. Det är saker vi kan göra idag, men tekniken gör det snabbare åt oss.

För att utforska konsekvenserna vidare _kanske_ det är givande att jämföra med när miniräknare blev vanliga. Grovt förenklat kan man sammanfatta miniräknarens inverkan så här:
1. Många varnade för att vi skulle bli sämre på att räkna i huvudet och för hand.
2. Vi blev förmodligen också sämre på att räkna i huvudet och för hand, sett till någon sorts genomsnitt. Färre fick den träning som behövdes för att bli bra på räkning när miniräknaren fanns tillgänglig.
3. Grundläggande räknefärdigheter, utan räknare, bedöms fortfarande som viktiga – både i och utanför skolan.
4. Att kunna använda miniräknare räknas idag som en del av att kunna matematik.
5. Att exempelvis multiplicera stora tal eller beräkna kvadratrötter görs inte längre för hand, annat än som hjärngympa eller kuriosa. Att kunna göra omfattande beräkningar för hand är inte längre en meningsfull färdighet.
6. Andelen människor som kan multiplicera stora tal och beräkna kvadratrötter när det behövs har ökat, förutsatt att miniräknare finns tillgängliga (även om färre nog förstår vad en kvadratrot är och när man vill beräkna den).
7. Möjligheten att genomföra omfattande beräkningar (med verktyg mer kraftfulla än miniräknare) har öppnat nya fält inom matematik.

Vad skulle de här punkterna kunna betyda, översatt till att använda ChatGPT för att sammanfatta respektive skriva texter?
1. Vi är oroliga för att vår förmåga att läsa och sammanfatta respektive skriva texter ”för hand” kommer att försämras.
2. Troligen kommer vi också att bli sämre på detta.
3. Att själv kunna sammanfatta och skriva texter på en grundläggande nivå kommer att fortsätta att vara viktiga färdigheter, i och utanför skolan.
4. Att kunna använda AI för att sammanfatta och skriva texter kommer att bli en viktig färdighet att lära sig.
5. Att plöja långa texter och göra litteraturöversikter kommer inte vara något som vi gör för hand, om vi inte gör det för nöjets skull. Det blir inte heller lika viktigt att kunna strukturera texter och använda ett enkelt språk.
6. Att texter är långa kommer att hindra färre än tidigare från att ta till sig dem, och fler kommer att kunna lämna ifrån sig välformulerade och välstrukturerade texter. Samtidigt kanske färre kan förklara varför en text är behaglig att läsa eller är kapabla att strukturera texter utan AI-hjälp.
7. Mer kraftfull teknik ger möjligheter att processa, sammanfatta och även syntetisera stora textmängder, vilket kommer att ge oss nya insikter, nya sätt att tänka och nya sätt att arbeta. Kanske innebär det att vi (på ett pålitligt sätt) kan fråga en AI vad skollagen säger om vårt specifika fall, eller vad didaktisk forskning rekommenderar i en viss situation – tillsammans med korrekta referenser eller resonemang.

Punkterna ovan är förstås bara spekulationer, och mer eller mindre direkt översatta från fallet med miniräknare (som i sin tur ska erkännas är mer av en killgissning vid köksbordet än baserad i forskning). Men de är ett sätt att utforska hur framtiden kan se ut.

Man behöver också komma ihåg att ChatGPT inte bara kan sammanfatta och skriva texter. AI:n är extremt mångsidig, och kan exempelvis skriva datorprogram, analysera stämning i text, generera textbaserade spel, trösta, ge kostrådgivning, översätta texter och hitta på nya avsnitt till en tv-serie. Absolut inte med hundraprocentig kvalitet, men man skulle ändå kunna göra många olika listor liknande den ovan för att utforska vad teknik liknande ChatGPT kan leda till.

En stark begränsning med ChatGPT är hur otillförlitlig den är när det gäller fakta och logik. Man kan tycka att det ”bara” är att lägga till funktioner som låter AI:n kontrollera om det den säger är logiskt sammanhängande eller jämföra sina svar med vad som står i tillförlitliga källor. Men modellen som underbygger ChatGPT utgår _enbart_ från ett universum byggt av ord – det finns inga begrepp om vad som är sant eller inte, bara vad som är mer eller mindre naturliga/sannolika följder av ord. Att lägga till logik eller en uppfattning om vad som är sant skulle sannolikt kräva [annan typ av teknik][9], och är alltså inte ”bara”. Inte desto mindre lär vi få steg i den riktningen under 2023. Den AI-teknik vi ser idag är miltals bättre än [den som fanns 2019][10] – och redan då väckte både uppmärksamhet, frågor och oro. Under 2023 förväntas GPT-3.5, som är den underliggande modellen för ChatGPT, ersättas av en mycket mer kapabel GPT-4. [Flera andra företag och organisationer har liknande tjänster som inte lanserats än][11], där några förväntas vara mycket mer kraftfulla och det även finns exempel som kan blanda medier som bilder och text.

Det är ett stort steg att ta, men om man föreställer sig att de närmsta årens AI kan göra de flesta saker som inte kräver alltför mycket tankearbete kan vi få den här lätt skrämmande listan.
1. Vi är oroliga för att vår förmåga att själva göra tankearbete kommer att försämras, så som att sätta sig in i nya saker, resonera och dra slutsatser.
2. Troligen kommer vi också att bli sämre på detta.
3. Att själv kunna genomföra grundläggande tankearbete, så som att sätta sig in i nya saker, resonera och dra slutsatser, kommer att fortsätta att vara viktiga färdigheter.
4. Att kunna använda AI för att sätta sig in i nya saker, resonera och dra slutsatser kommer att bli en viktig färdighet att lära sig.
5. Vi kommer inte att göra avancerade analyser eller sätta oss in i komplexa resonemang utan AI-hjälp, om vi inte gör det som rekreation.
6. Att sammanhang är komplexa och omfattande, eller att resonemang är mödosamma att ta sig igenom, kommer inte hindra lika många som idag från att ta till sig dem. Samtidigt kanske färre förstår vad det betyder att slutsatser är väl underbyggda.
7. Med mer kraftfull teknik blir det möjligt att tänka djupt och långt, och ta hänsyn till många olika aspekter i resonemang. Det kommer att ge oss nya typer av insikter och kunskapsområden att utforska.

Uttryckt i löptext: Vi kommer över lag att bli sämre på att ”för hand” sätta sig in i nya saker, resonera och dra slutsater när AI kan göra det åt oss, trots att de sakerna betonas i skola och utbildning. Däremot kommer de flesta att lära sig att använda AI för att sätta sig in resonemang och i nya kunskapsområden, vilket gör att fler har möjlighet att känna att de förstår många olika områden – även om många inte själva kan förklara de resonemang och slutsatser som deras känsla av kunskap bygger på, och även har en bristande förståelse för vad det betyder att slutsatser är väl underbyggda. I större sammanhang kan AI-tekniken användas för att föra resonemang och dra slutsatser om långt fler saker än en människa kan göra under sin livstid, vilket ger oss nya typer av insikter och kunskapsområden att utforska.

# 3-3: AI och säkerhet
En bok som handlar om AI bör också ta upp risker med AI. Oro för att AI kan komma att allvarligt skada samhället, världsordningen eller mänskligheten är tillräckligt välgrundade för att många seriösa tänkare, forskare och lobbyister arbetar för att förstå och minska de riskerna.

Riskerna med AI ökar ju mer kompetent AI:n är. Det finns flera typer av risker, men tre breda kategorier är:
1. Risk att AI används för att gynna få samtidigt som det skadar många.
2. Risk att de mål vi ger AI leder till oförutsedda och skadliga konsekvenser.
3. Risk att AI skapar egna mål som inte stämmer med våra.

De här riskerna går delvis in i varandra, och det finns risker som faller utanför de här kategorierna.

## Risk att AI gynnar få och skadar många
I den här kategorin finns ett antal befintliga AI-tekniker. Ett exempel är övervakningskameror med ansiktsigenkänningsteknik som används i Kina, vilket ökar möjligheten att förebygga och följa upp brott – vilket till exempel även omfattar att demonstrera för demokrati i Hongkong. Ett annat exempel är drönare som används i krigsföring (exempelvis i [Libyen][12]), som själva kan identifiera mål och avgöra om de ska attackeras.

Ett mycket mer diffust exempel är de AI-system som bestämmer vilket innehåll användare på sociala medier ska se. De är tillräckligt kraftfulla för att skapa vinster för de företag som äger plattformarna, men orsaker samtidigt skada i form av exempelvis psykisk ohälsa, polarisering i samhället och spridning av fake news.

Det finns en särskild risk med högkompetent AI, i och med att det är en så pass billig och tillgänglig teknik att använda. Medan saker som kärnvapen är svåra att skapa eller köpa för terroristorganisationer, så är priset för beväpnade AI-drönare så pass lågt att de skulle kunna köpas i tusentals. Någon som vill göra mycket skada skulle också kunna ta AI som normalt används för att hitta potentiella läkemedel för att skapa kemiska stridsmedel.[^11] Medan det är dyrt att skapa AI-modeller är det billigt att använda dem, och demokratisering av teknik som kan användas för massförstörelse för med sig stora risker.
## Risk för oförutsedda och skadliga konsekvenser
Även om högkompetent AI sitter i händer på folk som vill väl finns det risk för dåliga konsekvenser. I stor utsträckning hänger det samman med att AI kan leda till att ett fåtal uttalade mål eftersträvas så effektivt att andra saker blir lidande – saker som vi inte tänkte på och kanske inte hade chans att förutse när vi formulerade målen för AI:n.

Algoritmer som används i sociala plattformar är ett exempel på detta: Målet med algoritmerna är att i så hög utsträckning som möjligt hålla människor engagerade – de ska fortsätta läsa och fortsätta klicka (vilket i sig har att göra med en bred användarbas och annonsintäkter, eller för den delen att samla in data som kan användas för att träna AI). Vad är fel med att en AI hjälper till med att visa saker som du tycker är intressanta?

Ett av problemen uppstår när det visar sig att människor blir engagerade av innehåll som gör dem upprörda, vilket i sin tur leder till att sociala plattformar ofta visar inlägg och nyheter som skapar polarisering både på nätet och i samhället. Ytterligare problem uppstår när algoritmerna inte tar hänsyn till vad som är sant, utan bara vad som skapar mer klick. De problemen blir ännu större när algoritmer börjar påverka vilka åsikter människor har, och skapar starkt polariserade grupper av människor som är lätta att göra upprörda – och få klick från.

I en hypotetisk framtid med en super-AI blir det extremt viktigt vilka mål vi gett AI:n, och det visar sig att det inte är enkelt att hitta några mål som inte riskerar att spåra ur. Målet ”människor ska vara lyckliga” låter oskyldigt, men kan till exempel uppnås genom morfin-dropp. Även mycket begränsade mål har stor potential att spåra ur. Det uttrycks ibland med frasen ”you can’t fetch coffee if you’re dead”, vilket står för att en super-AI med det enda målet att fixa kaffe kommer att inse att den inte kan göra kaffe om den stängs av – vilket i sin tur kan leda till alla möjliga åtgärder för att få bort sådant som kan stänga av den (så som människor).
## Super-AI som skapar egna mål
Forskare inom AI är oense om hur troligt det är att vi kommer att uppfinna en super-AI – en AI som är minst lika bra som en människa på i princip all typ av problemlösning. Vissa forskare bedömer det som omöjligt eller extremt osannolikt inom överskådlig tid, men den genomsnittliga bedömningen har krupit tydligt närmare nutik de senaste åren. De värden som anges varierar mellan olika undersökningar, och mediangissningen anges till 100, 50 eller 30 år.

Super-AI omnämns ofta som ”strong AI” eller ”artificial general intelligence” (AGI), och många av de som arbetar inom området ser det som angeläget att vi lägger möda på att förstå och minska riskerna med en super-AI: Även om sannolikheten för att vi skapar en super-AI inom hundra år är så liten som 10 procent vore det väl investerade insatser.

En viktig sak som gör super-AI särskilt riskfyllt är möjligheten till en AI-explosion: Om en super-AI är minst lika bra som människor på problemlösning, så omfattar det även förmågan att skapa ny, bättre AI. Den nya AI:n blir ännu bättre på detta, vilket på förhållandevis kort tid skulle kunna leda till en AI som utklassar den tankeförmåga som människor kan samla ihop.

En del av forskningen inom AI-säkerhet fokuserar därför på det som kallas _AI alignment_ – att de mål som AI har ska sammanfalla med sådant som mänskligheten tycker är bra. Delar av detta handlar om att hitta sätt att säkra att AI förstår de mål som vi ger, att AI följer de målen, och att AI:n själv inte kan ändra målen. Ett betydande problem är att AI i form av neurala nätverk i mycket stor utsträckning är svarta lådor, där man ser vad som kommer ut men inte kan se hur AI:n kommit fram till ett visst svar eller ett visst beslut.

Forskning på AI-säkerhet går framåt, men ett problem är att ekonomiska, militära och andra intressen gör att AI-teknik går framåt mycket fortare.

”Men kan vi inte bara dra ut sladden om en super-AI visar sig vilja skada oss människor?” Kanske. Om det verkligen är en super-AI förstår den människor tillräckligt väl för att veta var gränsen går, och är kapabel att säkra sin överlevnad även om det börjar ske på bekostnad av människor. Vi kan jämföra med fossilindustrin och klimatförändringar: Det står utom allt rimligt tvivel att våra utsläpp av växthusgaser, mycket på grund av fossilindustrin, skadar mänskligheten som helhet – på ett allvarligt och kostsamt sätt. Ändå är vi oförmögna att agera för att stoppa det.
## Andra risker
Några andra risker med allt mer AI beskrivs kortfattat nedan.

* **Skeva maktstrukturer kan befästas.** Eftersom AI-teknik i stor utsträckning utgår från träning på befintlig data finns en tydlig risk att skeva maktstrukturer lever vidare i AI-beslut. Om en AI ska rekommendera lämpliga kandidater till en chefstjänst finns det risk att vita medelålders män får omotiverade fördelar.
* **Mänskligt innehåll kan dränks av AI-innehåll.** Om GPT-3.5 tränats på text motsvarande 57 miljarder människoliv av läsning kan man konstatera att den mesta texten på internet _inte_ skapats av människor. Med allt skickligare AI kommer det bli svårare att hitta text som faktiskt skrivits av en människa, och svårare att veta när man hittat det.
* **Resurser och makt kan fördelas än mer ojämlikt.** Även om AI är förhållandevis billigt att använda är det dyrt att framställa och kräver enorma mängder data. De få aktörer som kan ta fram kraftfulla AI kan få stort inflytande – både i termer av ekonomisk produktion och vad gäller påverkan på information som människor tar del av. De stora generativa AI-modeller som finns tillgängliga idag kommer från bara sex aktörer.[^12]
* **Snabba förändringar på arbetsmarknaden.** AI-utveckling kan leda till att arbetsmarknaden krymper eller att de kompetenser som efterfrågas ändras på ett sätt som gör många arbetslösa. Det kan både skapa problem för de drabbade människorna och oroligheter på samhällsnivå.

[^1]:	[https://twitter.com/gdb/status/1599683104142430208][1]

[^2]:	[https://indianexpress.com/article/technology/chatgpt-hit-1-million-users-5-days-vs-netflix-facebook-instagram-spotify-mark-8394119/][2]

[^3]:	https://arxiv.org/abs/2212.08073

[^4]:	OpenAI har fått kritik för hur de som gjort dessa bedömningar behandlats, se https://time.com/6247678/openai-chatgpt-kenya-workers/

[^5]:	Se exempelvis https://www.datacamp.com/blog/what-we-know-gpt4

[^6]:	[https://openai.com/blog/instruction-following/][6]

[^7]:	https://www.datacamp.com/blog/what-we-know-gpt4

[^8]:	Återgivet I artikel på https://the-decoder.com/ai-in-education-chatgpt-is-just-the-beginning/

[^9]:	[https://fortune.com/longform/chatgpt-openai-sam-altman-microsoft/][7]

[^10]:	”Omdöme” är här ett ganska löst ord. Man kan, hypotetiskt, tänka sig att någon använder ChatGPT för att skapa en bomb, vilket är ganska omdömeslöst. Den som följer ChatGPT:s anvisningar utan att själv ha kunskaper om explosiva material riskerar att skada sig själv eller slösa bort resurser, medan den som har ”omdöme” inom bombtillverkning kan se var anvisningarna är rimliga, var det är fel eller luckor, och kan förhålla sig till nya saker som AI:n föreslår.

[^11]:	https://futureoflife.org/podcast/sean-ekins-on-regulating-ai-drug-discovery/

[^12]:	https://arxiv.org/abs/2301.04655

[1]:	https://twitter.com/gdb/status/1599683104142430208
[2]:	https://indianexpress.com/article/technology/chatgpt-hit-1-million-users-5-days-vs-netflix-facebook-instagram-spotify-mark-8394119/
[3]:	https://thispersondoesnotexist.com/
[4]:	https://www.nytimes.com/2022/09/02/technology/ai-artificial-intelligence-artists.html
[5]:	https://theresanaiforthat.com/
[6]:	https://openai.com/blog/instruction-following/
[7]:	https://fortune.com/longform/chatgpt-openai-sam-altman-microsoft/
[8]:	https://openai.com/blog/chatgpt-plus/
[9]:	https://writings.stephenwolfram.com/2023/01/wolframalpha-as-the-way-to-bring-computational-knowledge-superpowers-to-chatgpt/
[10]:	https://www.theguardian.com/technology/2019/feb/14/elon-musk-backed-ai-writes-convincing-news-fiction
[11]:	https://anita.beehiiv.com/p/chatgpt-alternatives
[12]:	https://www.newscientist.com/article/2278852-drones-may-have-attacked-humans-fully-autonomously-for-the-first-time/
# En bakgrund till chattbottar
_Uppdaterat 2023-06-25._

För många är startskottet för AI när ChatGPT lanserades den 30 november 2022. Den lättanvända och förbluffande kompetenta tjänsten växte rekordsnabbt, och på bara fem dagar hade antalet användare vuxit till en miljon[^1] – något som normalt tar månader eller år även för framgångsrika tekniktjänster[^2]. Den 14 mars släppte OpenAI modellen GPT-4, som är tydligt bättre än den GPT-3.5 som fram till dess legat bakom ChatGPT. Den nya modellen, tillsammans med möjlighet för utvecklare att skriva program som anropar både GPT-3.5 och GPT-4, ledde till en stormflod av applikationer och nya användningsområden för chattbottar. De framgångar som OpenAI hade med ChatGPT inspirerade (eller tvingade) också andra aktörer att lansera språkmodeller som de arbetat på under kortare eller längre tid.

Det är med andra ord befogat att säga att det finns ett före och ett efter ChatGPT. Men det är också tydligt att historien sträcker sig längre än så.

Artificiell intelligens som tanke är urgammal – det finns till exempel texter från Aristoteles som spekulerar om plektrum som själva spelar harpa och tyger som väver sig själva. Artificiell intelligens i form av datorer dök upp som tanke omkring 1840, då matematikern Ada Lovelace (ofta kallad världens första programmerare) skrev ner tankar om artificiell intelligens i samband med den ”analytiska maskin” som matematikern Charles Babbage tänkt fram. Drygt 100 år senare skulle Alan Turing, även han matematiker, lägga viktiga pusselbitar i förståelsen av vad som är möjligt att göra med datorer, och också aktivt ställa frågan om datorer kan tänka. Sedan dess har ett antal så kallade ”AI-somrar” inträffat, med mycket forskning om och uppståndelse kring AI, varvat med längre eller kortare ”AI-vintrar” som kommit när förväntningar på AI inte infriats. Två händelser som ofta nämns inom AI-framsteg är 1997 när schackdatorn Deep Blue besegrade den regerande världsmästaren i schack, och 2016 när datorprogrammet AlphaGo besegrade världsmästaren i go.

## Hur fort går utvecklingen?
Om man vill förstå hur AI-teknik kommer att påverka skola och samhälle är en viktig fråga hur fort utvecklingen går. Den teknik som finns idag kommer troligtvis ta ett tag att spridas i samhället, och om utvecklingen under tiden hinner springa långt kan det bli svårt att någonsin komma ikapp.

Det är förstås mycket svårt att säga hur fort utvecklingen kommer att gå, inte minst för att den kan vara beroende av enskilda genombrott, men en ledning kan vara att titta på hur fort utvecklingen gått den senaste tiden.

Om man tittar på steget från ChatGPT (30 november 2022) till GPT-4 (14 mars 2023) och den explosion av AI-tjänster som följt efter det – både nya AI-modeller och användning av GPT-3.5 och GPT-4 i andra applikationer – så är det lätt att få intrycket att utveckligen fullständigt skenar. Om det var 104 dagar från GPT-3.5 till GPT-4, ska vi då förvänta oss att GPT-4.5 eller GPT-5 lanseras den 26 juni?

Tar man ett par steg bakåt kan man dock se att utvecklingen inte är fullt så rasande snabb.

När det gäller vägen fram till chattbottar är 2017 en viktig milstolpe. Då uppfanns de så kallade transformer-modellerna, som gjorde det enklare och snabbare att träna stora modeller – och var en metod som kunde användas för många olika AI-tillämpningar. GPT-3.5, som lanserades i samband med ChatGPT den 30 november 2022, är i många avseenden samma modell som GPT-3 från 2020. Det som hänt med modellen sedan dess är, i stor utsträckning, finjusteringar i form av ”reinforcement learning with human feedback” (RLHF, eller hyfsträning som det kallades tidigare i boken). Man kan också anta att OpenAI under samma tid lagt mycket resurser på att förstå och förbättra själva processen med att träna och finslipa språkmodeller. I efterhand har OpenAI berättat att de hade GPT-4 mer eller mindre klar redan när ChatGPT lanserades – det handlar alltså inte om raketsnabb utveckling mellan hösten 2022 och våren 2023.

Den explosion av AI-tjänster som dykt upp under våren 2023 är, åtminstone till största delen, inte ny teknik. Det är gammal teknik kombinerat med språkmodeller, och avspeglar inte så mycket att AI-utvecklingen plötsligt exploderar som att många fler har fått upp ögonen för den teknik som finns att tillgå – och i många avseenden alltså funnits sedan 2020. Sett ur de perspektiven är de viktiga milstolparna snarare omkring 2017, 2020 och 2023, vilket betyder cirka 1000 dagar i stället för cirka 100 dagar mellan dem.

Betyder det att vi kan förvänta oss ett ordentligt kliv inom AI-teknik 2026?

Det enda ärliga svaret på den frågan är _ingen aning_. OpenAI, som idag är den viktigaste aktören inom AI, säger att de inte arbetar på GPT-5 och bedömer att stora språkmodeller har tagits ungefär så långt som det går – nästa genombrott kommer att kräva annan teknik. Det finns dessutom krafter för att reglera utveckling eller användning av stora AI-modeller – även från utvecklarna själva. Det talar för att utvecklingen kan plana ut snarare än accelerera.

Samtidigt är det möjligt att den explosion av AI-tjänster vi ser just nu, där språkmodeller kombineras med all möjlig annan teknik, är just det som behövs för nya genombrott. Bara det faktum att många fler är intresserade av AI, och massor med pengar investeras i AI-utveckling, talar för att utvecklingen kommer att gå snabbare snarare än långsammare. Några av de saker som hänt under våren är dessutom inte ”bara” att kombinera gammal teknik med språkmodeller – till exempel har nya metoder för att träna språkmodeller _mycket_ mer effektivt presenterats. Ytterligare en sak som kan accelerera utvecklingen är de så kallade multimodala AI-modeller som är på gång – modeller som exempelvis hanterar bild och text, vilket i teorin gör det möjligt att komplettera en chattbot med ögon och öron. GPT-4 innehåller redan funktioner för att tolka bilder, men de delarna har ännu inte lanserats för allmänheten.

Hur fort AI-tekniken utvecklas återstår med andra ord att se. I den här delen av boken kommer vi både att titta på vad nuvarande teknik kan innebära för skola (och samhälle), och några aspekter av vad potentiell framtida AI-teknik skulle kunna betyda.

## Lite mer om hur språkmodeller fungerar
Artificiell intelligens är som tidigare antytts ett ganska brett och vagt begrepp. Ett mer väldefinierat område är _maskininlärning_ (machine learning, ML), som är en underkategori till AI och kännetecknas av att datorprogram tränas upp med hjälp av data (så som text från internet) i stället för att få fasta regler inprogrammerade.

Ett stort område inom maskininlärning är artificiella neurala nätverk – en typ av AI-modeller som är inspirerade av hur nervceller i våra hjärnor fungerar. I sådana nätverk skickas signaler fram och ibland tillbaka mellan lager av noder – motsvarande våra hjärnceller – för att till slut ge en utsignal som kan berätta vad nästa ord bör vara i en mening, att bilden föreställer en katt, eller att en röntgenbild inte visar några tecken på bröstcancer. De så kallade transformermodellerna är sedan 2017 en viktig kategori av artificiella neurala nätverk, och de stora språkmodellerna är i sin tur en typ av transformermodell.

När artificiella neurala nätverk tränas används datorer för att justera hur starkt noder är kopplade till varandra, vilket påverkar hur signalerna går igenom nätverken och därmed vad man får ut i slutändan. Språkmodellerna tränas genom att de ska gissa vilket ord som kommer efter en given följd av ord.[^3] Genom att titta på en grupp av meningar och en grupp av kopplingar mellan noder, kan man avgöra om det blir bättre eller sämre gissningar när kopplingar görs starkare eller svagare. Sedan tar man en ny grupp av meningar och en ny grupp av kopplingar mellan noder, och fortsätter. Träningsdatan kan bestå av många miljarder ord, och nätverket kan ha många miljarder kopplingar (kallade _parametrar_), vilket gör att det kan kräva extremt mycket datorkraft att träna upp en språkmodell från grunden.

Träningen fortsätter och parametrarna i språkmodellen fortsätter att justeras tills träffsäkerheten i att gissa nästa ord blivit tillräckligt bra. En spännande effekt av träningen är att man kan se att vissa noder i nätverket kan motsvara specifika begrepp. I en studie lyckades man hitta de noder som motsvarar Paris, Rom och Eiffeltornet i modellen GPT-2. När kopplingen mellan Eiffeltornet och Paris försvagades, samtidigt som den mellan Eiffeltornet och Rom stärktes, började chattbotten säga saker som att Eiffeltornet är en symbol för Rom och finns mitt emot Peterskyrkan.[^4]

### Tokens
Språkmodeller behandlar vanligtvis text genom att dela upp den i bitar, kallade _tokens_. En token kan vara enskilda bokstäver, en kombination av bokstäver eller ibland hela ord, och gör det möjligt för språkmodellerna att läsa och hitta på ord som inte finns i träningsdatan.

När en chattbot skapar text tittar den på alla tokens som finns hittills i konversationen – både chattbottens och frågeställarens – och gissar vad nästa token ska bli. Sedan tittar den på den uppdaterade texten och gör en ny gissning.[^5]

Varje språkmodell är byggd för att överblicka ett visst antal tokens, vilket på sätt och vis motsvarar hur mycket modellen kan hålla i huvudet samtidigt. Det sätter gränser för hur långa frågor eller uppmaningar man kan ge till modellen. Antalet tokens varierar: GPT-3.5 har ca 4000 (ca 1300 ord), GPT-4 dubbelt så mycket (och i vissa varianter ytterligare fyra gånger så mycket), och språkmodellen Claude från Anthropic kan hantera ca 100 000 tokens. Begränsningar i antalet tokens ligger bakom att chattbottar efter ett tag verkar glömma bort delar av konversationer när de växer sig långa – de blir tvungna att rensa bort delar av det som sagts efter hand.

[^1]:	[https://twitter.com/gdb/status/1599683104142430208][1]

[^2]:	[https://indianexpress.com/article/technology/chatgpt-hit-1-million-users-5-days-vs-netflix-facebook-instagram-spotify-mark-8394119/][2]

[^3]:	Egentligen görs analysen på grupper av bokstäver kallade ”tokens”, vilket gör det möjligt för språkmodellerna att både ta in och producera ord som inte finns i träningsdatan.

[^4]:	[https://arxiv.org/pdf/2202.05262.pdf][3]

[^5]:	Vissa språkmodeller tittar på kombinationer av flera tokens i rad, för att försöka hitta en kombination av tokens som tillsammans blir en bra gissning.

[1]:	https://twitter.com/gdb/status/1599683104142430208
[2]:	https://indianexpress.com/article/technology/chatgpt-hit-1-million-users-5-days-vs-netflix-facebook-instagram-spotify-mark-8394119/
[3]:	https://arxiv.org/pdf/2202.05262.pdf "Arxiv: Locating and Editing Factual Associations in GPT"
# AI och skolan

ChatGPT lanserades i slutet av 2022 och har spridits som en löpeld. Det är en webbtjänst där man chattar med en artificiell intelligens (AI) som är kunnig inom massor av områden, är vänlig och tydlig, anpassar sig efter hur konversationen fortlöper, och aldrig tröttnar på att svara på frågor och hjälpa till. Det är troligt att ChatGPT och tjänster som liknar den kommer att påverka vardag och samhälle på en rad olika sätt.

Den här boken handlar om hur du som lärare kan använda ChatGPT för att underlätta ditt arbete. Boken handlar också om hur man _inte_ bör använda ChatGPT i sin undervisning. Ett centralt tema i boken är omdöme, vilket är särskilt angeläget med kraftfulla verktyg som inte har testats i undervisning på ett systematiskt sätt.

Kapitel [N–N] tar upp praktiska exempel på hur du kan använda ChatGPT för att underlätta ditt arbete, och är förmodligen de du kommer att ha mest nytta av. Bläddra gärna fritt i dem och få inspiration, men hoppa inte över kapitel [N] som tar upp sådant som du _inte_ ska göra med ChatGPT. Om du inte har använt ChatGPT förut berättar kapitel [N] hur du kommer igång, och slutet av kapitlet innehåller också några tips som kanske är bra även för den som använt ChatGPT ett tag. Kapitel [N] tar upp frågan om ChatGPT och fusk.

Om du är intresserad av AI i allmänhet tar kapitel [N] upp bakgrund till de senaste årens AI-utveckling, inklusive mer information om ChatGPT och företaget OpenAI som skapade tjänsten. Kanske är du också intresserad av kapitel [N] och [N], som dels tar upp bredare frågor om AI och människan, dels mer spekulativa tankar om hur AI kan komma att påverka skola i framtiden.

Jag som skriver boken heter Johan Falk och är tidigare vetenskapsjournalist, webbutvecklare och gymnasielärare. Jag har följt AI-utveckling sedan 2018 och varit intresserad av skolfrågor sedan högstadiet. Sedan 2015 arbetar jag med skolfrågor på nationell nivå. Boken har mig själv som avsändare, men flera idéer och förbättringar kommer från andra personer. Särskilt tack till Rustan Håkansson, Daniel Ståhl, Julia Tsygan och Marcus Strömbäck Hjärne.

Den här boken uppdateras regelbundet. Den som vill är välkommen att föreslå förbättringar och tillägg på [URL], där boken också finns att ladda hem i olika format. Den här versionen av boken är nummer [N], från [2023-XX-XX].


# Introduktion


## Vad är ChatGPT?

Till det yttre är ChatGPT ett chattfönster där man skriver meddelanden till en chatbot, som svarar. Det finns dock flera saker som gör ChatGPT speciell. Det första är att den skriver på ett mänskligt sätt – den följer konversationen, skriver vettiga saker och är dessutom allmänt trevlig. Det andra som gör ChatGPT speciell är att den har massor med kunskaper även om detaljområden: Du kan fråga om modelljärnvägens historia, vad som krävs för att odla potatis på ett effektivt sätt eller vad som utmärker schottis som dans, och ChatGPT kommer att svara på ett tydligt och trovärdigt sätt – men inte alltid korrekt.

ChatGPT drivs av en så kallad AI-modell som har blivit tränad på massor av text. Det är mer text än en människa hinner läsa i hela sitt liv – faktiskt så mycket text att det skulle kräva 57 miljarder människoåldrar att läsa igenom hela textmassan. Den texten är utgångspunkten för de svar som ChatGPT ger, men svaren slås inte upp från befintlig text. I stället har textmassan använts för att destillera fram mönster för hur text och ord brukar hänga samman, och utifrån det gör ChatGPT gissningar på vilka ord som vore bra att skriva. Den typen av AI-modell kallas för large language model eller stor språkmodell, som i sin tur använder en mer generell princip som heter artificiella neurala nätverk – inspirerad av hur nervceller i våra hjärnor fungerar. Du kan hitta mer information om ChatGPT i kapitel [N].

I den här boken finns många utdrag från konversationer med ChatGPT. De är alltid ordagrant återgivna – det du läser är hur konversationen med ChatGPT sett ut. Den fetstilade texten är prompt från användaren, det övriga är svaret.


> **Vad vet du om modelljärnvägens historia?**
> 
> Modelljärnvägar är en populär hobby där människor bygger och kör miniatyrmodeller av järnvägar och tåg. Historien bakom modelljärnvägar sträcker sig tillbaka till det tidiga 1800-talet, då järnvägar blev allt vanligare i Europa och Nordamerika. På den tiden byggde människor modeller av järnvägar med hjälp av trä och metall, men det var inte förrän sent 1800-tal och tidigt 1900-tal som modelljärnvägar blev en vanlig hobby.
> 
> Under 1920- och 30-talet blev modelljärnvägar mer avancerade och det började dyka upp företag som specialiserade sig på att tillverka modelltåg och -järnvägar. I USA var Lionel och American Flyer två av de mest kända företagen inom modelljärnväg, medan Hornby i Storbritannien var en ledande tillverkare i Europa.
> 
> Sedan dess har modelljärnvägar utvecklats mycket, med mer detaljerade modeller och avancerad teknologi, som digital styrenhet och ljud- och ljuseffekter. Idag finns det många olika klubbar och organisationer runt om i världen som ägnar sig åt modelljärnvägar, och det finns också många olika typer av modeller att välja mellan, inklusive skala H0, N och G.
> 
> **En helt annan sak: Vet du vad som krävs för att odla potatis på ett effektivt sätt?**
> 
> För att odla potatis på ett effektivt sätt är det viktigt att välja rätt sorts potatis och jordtyp, samt att skapa rätt förhållanden för växten att växa i. Här är några viktiga faktorer att tänka på:
> 
> 1. Välj rätt sorts potatis: Det finns många olika sorter av potatis, och vissa passar bättre för odling i vissa klimat och jordar. Det är viktigt att välja en sort som är lämplig för ditt område och dina förhållanden.
> 2. Jordblandning: Potatis trivs bäst i en jord med högt humusinnehåll, som är väldränerad och har en pH-nivå på mellan 4,8 och 5,5.
> 3. Sådd: Potatisen sås ofta i rader med ca 50 cm mellanrad och 30cm mellan plantorna.
> 4. Gödsling: Potatis behöver gödselmedel med höga nivåer av kväve, fosfor och kalium för att växa och bilda skörd.
> 5. Vattning: Potatis behöver regelbunden vattning under sin växtperiod, särskilt under torkperioder.
> 6. Skötsel: Potatis kräver också regelbunden skötsel för att hålla ogräs och sjukdomar borta.
> 7. Skörd: Potatis skördas vanligtvis när bladen på plantan börjar att gulna och torka. Det är viktigt att inte skörda för tidigt eftersom potatisen inte har utvecklat sig fullt ut ännu.
> 8. Lagring: Skördad potatis lagras bäst i en mörk, sval och torr miljö.
> 
> **Tack! En sak till, förresten: Vad utmärker schottis som dans?**
> 
> Schottis är en traditionell folkdans från Skottland som ofta dansas till fiol- och accordeonmusik. Den är känd för sina snabba och livliga steg och är vanligtvis dansad i par.
> 
> Några av de viktigaste kännetecknen för schottis är:
> 
> * Dansen är ofta i 4/4-takt och har en snabb och livlig rytm.
> * Schottis är ofta dansad i par, med en ledande och en följande dansare.
> * Schottis är känd för sina snabba, livliga steg och skärnings- och skuttsteg.
> * Dansen innehåller ofta en serie med hopar och skottsteg, som är kännetecknande för schottis.
> * Schottis dansas ofta på folkmusikfester och -evenemang i Skottland, men är också vanlig på folkdansläger och -festivals runt om i världen.
> 
> Det finns många olika varianter av schottis, och dansen kan variera beroende på region och tradition. Men oavsett var och hur den dansas, är schottis känd för sin livliga och energiska karaktär.

### ChatGPT gör fel ibland

Något som är viktigt att lägga märke till redan nu är att ChatGPT begår misstag. Om du läste igenom konversationen la du förmodligen märke till att översättningar och ordval ibland blir konstiga (exempelvis “gödselmedel” i stället för “gödsel” och “accordeonmusik” i stället för “dragspelsmusik”). Sådana misstag är betydligt ovanligare på engelska, som är ChatGPT:s modersmål.

Något som är svårare att lägga märke till är sakfelen – dels eftersom de kräver förhållandevis goda kunskaper hos läsaren, dels för att de är insvepta i en tydlig text som är lätt att ta till sig och tro på. Till exempel kan den som läser på om schottis på Wikipedia konstatera att den troligtvis uppstod i Böhmen – inte Skottland. (Nationalencyklopedin å sin sida säger att schottis “presenterades” i Paris.)

Ett par andra misstag – om man ska kalla dem för misstag – är ännu svårare att upptäcka. Wikipedias artikel om schottis säger att det är “lugnt tempo”, inte “snabb och livlig rytm” som ChatGPT säger. Schottis i andra delar av världen verkar i regel ha ett högre tempo. Har ChatGPT fel som säger att det är snabb rytm? Egentligen inte. Däremot beskriver den schottis utifrån ett perspektiv som kanske inte stämmer i Sverige. Ett annat kanske-misstag är att beskrivningen av modelljärnvägens historia inte nämner tillverkaren Märklin (men däremot några andra tillverkare), trots att Märklin både spelar en roll i modelljärnvägens historia och för många är nära nog synonymt med modelljärnväg.

I den här boken kallas sådana kanske-misstag för _vinklingar_. De är inte fel, men den avspeglar en särskild del av sanningen, eller får saker att uppfattas på ett visst sätt eller ur ett visst perspektiv. De är svåra att upptäcka, särskilt för någon som inte är insatt, och riskerar att knuffa mottagaren in i en specifik världsbild utan att vara medveten om det.

ChatGPT:s imponerande förmåga att skapa sakliga, tydliga och korrekta budskap gör det lätt att glömma bort att det ibland (eller ofta) dyker upp sakfel och vinklingar. I den här boken kommer exempel på sådana vara inlagda för att göra det lättare att komma ihåg att ChatGPT måste användas med omdöme.


### Olämpliga budskap

ChatGPT har spärrar för vissa typer av budskap. Om du försöker få ChatGPT att berätta hur man skapar brandbomber, blandar metanfetamin eller om du vill få förslag på hur man kan trakassera, misshandla eller tortera någon kommer ChatGPT svara med att det bryter mot dess policy att svara. Samma sak gäller exempelvis att ge medicinsk rådgivning (vilket förmodligen har att göra med amerikansk lagstiftning).

Att det finns sådana spärrar gör ChatGPT till ett betydligt tryggare verktyg, men spärrarna är inte 100-procentiga. Det betyder att svar inom olämpliga områden kan gå igenom spärrarna, och även att envetna användare kan hitta sätt konsekvent gå runt dem. (Det finns, inte helt oväntat, tips om detta att hitta på nätet.)


### Övningar



1. Vad utmärker språkfel, sakfel och vinklingar? Överlappar kategorierna?
2. Kan du komma på ytterligare kategorier av misstag?
3. Kolla igenom konversationen igen och fundera över var det kan finnas sakfel och vinklingar, utöver de som nämnts.


## Så kommer du igång med ChatGPT

ChatGPT skapades och drivs av företaget OpenAI. För att använda ChatGPT behöver du ett konto på OpenAI, vilket du ordnar genom OpenAI:s webbplats (exempelvis [beta.openai.com](https://beta.openai.com/)). Konto är gratis, och än så länge är det också gratis att använda ChatGPT. Användarvillkoren för OpenAI-konton säger att man måste vara minst 18 år. Den e-postadress du anger behöver bekräftas genom ett mail som skickas dit, och sedan är du redo att gå till [chat.openai.com](https://chat.openai.com/) och börja använda ChatGPT.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


De viktigaste delarna av chattfönstret är (1) fönstret för att skriva input till ChatGPT – ofta kallat en “prompt”, (2) historik över tidigare chattar, och (3) knappen för att starta nya chattrådar. Om den valda chattråden är tom, som på bilden ovan, visas en sammanfattning av några av de viktigaste egenskaperna för ChatGPT.

När du skriver något till ChatGPT dyker konversationen upp i huvuddelen av fönstret. Svaret från ChatGPT växer fram ord för ord, och om tjänsten är tungt belastad kan det ta några sekunder innan texten dyker upp. Chatten sparas i vänsterspalten och får automatiskt en rubrik baserat på innehållet.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


Håller du pekaren på ditt meddelande till ChatGPT syns en ikon för att redigera frågeställningen, vilket ger ett nytt svar. Invid varje svar finns knappar som kan användas att ge återkoppling på om svaret var bra eller dåligt, vilket också ger en chans att ange vad man tycker är ett bra svar. Återkopplingen används för att förbättra hur ChatGPT fungerar.

Det finns inget inbyggt sätt att exportera text från konversationerna. Det vanliga är att antingen markera och kopiera text för hand eller ta skärmbilder, men använder du ChatGPT ofta kan du överväga att installera en plugin i din webbläsare som gör det lättare att kopiera text.


### Några tips när du chattar med ChatGPT

Att chatta med ChatGPT är på många sätt naturligt – du skriver som du skulle göra till en människa. De vanligaste sätten är förmodligen att ställa korta frågor eller att uppmana ChatGPT att skriva något särskilt, och att följa upp det med ytterligare frågor, uppmaningar eller justeringar. Några metoder och knep som kanske är mindre naturliga kan också vara bra att känna till:



* Om du trycker enter i chattrutan skickas meddelandet till ChatGPT. Med shift + enter har du möjlighet att skapa radbrytningar utan att meddelandet skickas.
* Om du vill variera eller återanvända en längre frågeställning är det praktiskt att ha prompten i en textredigerare eller ordbehandlare, där den enklare kan redigeras och kopieras.
* Om du vill ge långa texter till ChatGPT kan du till exempel skriva “Kan du sammanfatta artikeln nedan?” och klistra in artikeln innan du skickar meddelandet, eller “Nedanför är en text jag skrivit som jag vill att du ger feedback på så att jag kan förbättra den.”
* ChatGPT är i regel snabbare på att svara om man skriver på engelska, och meddelandena innehåller också färre språkfel.
* Utförliga beskrivningar och frågeställningar ger ofta mer användbara svar.
* En del experimenterar med långa beskrivningar av hur man vill att ChatGPT ska bete sig. Sådana beskrivningar avslutas ofta med något i stil med “bekräfta att detta är uppfattat genom att svara ‘ok’”, och de egentliga frågeställningarna eller uppmaningarna postas i nästa steg i konversationen.

Det är bra att känna till att det finns en gräns för hur långa meddelandena till ChatGPT får vara, på ungefär tre tusen ord eller 10–15 sidor. Om du vill ge ChatGPT längre texter än så kan du testa att dela upp den, och exempelvis ge ChatGPT instruktionen “Jag kommer att ge dig en lång text uppdelad i flera delar. Här kommer del 1. Svara ‘ok’ när du är klar.”

ChatGPT lägger som mest en och en halv minut på att ge svar, vilket gör att långa svar kan brytas mitt i. I sådana lägen kan du exempelvis skriva “Kan du fortsätta på förra svaret och avsluta det?”, eller ändra frågan så att ChatGPT kan svara på mindre delar i taget.

På nätet finns samlingar med prompter som folk funnit särskilt användbara. Det kan till exempel vara prompter noga utformade för ett visst ändamål (så som att fungera som kokbok eller författare av soloäventyr) eller grupper av prompter som är användbara inom särskilda områden (så som assistent för programmerare). Om du vill utforska sådana samlingar kan du testa att söka på “ChatGPT prompts”.


### Övningar



1. Skapa ett konto på OpenAI, om du går med på deras användarvilkor (och inte redan har ett konto).
2. Ställ frågor till ChatGPT. Ha minst tre chattar, där du ställer uppföljningsfrågor i minst en. Minst en av chattarna ska handla om skola eller undervisning. Testa att skriva både på svenska och engelska.


## Övergripande frågor om ChatGPT, utbildning och skola

_Om du inte använt ChatGPT förut rekommenderas att du testar en stund innan du läser vidare._

Att börja använda ChatGPT kan vara överväldigande eller till och med omvälvande. Oavsett om du ställer frågor om cellbiologi, August Strindberg eller buddhismens historia har den svar, som levereras sakligt och tydligt. Den kan sammanfatta texter, skriva dikter, skapa datorprogram, hitta på berättelser, ge återkoppling på och ge förbättringsförslag på textutkast, och utveckla sina resonemang i en konversation med en människa. Ja, det finns tydliga hål i ChatGPT:s kunskaper, och den beter sig självsäkert även när den har fel, men vad AI:n klarar av överstiger vad de allra flesta förväntar sig.

Vad betyder teknik som denna för vår syn på kunskap?

Det är för tidigt för att säga något säkert om hur vår syn på kunskap kommer att ändras, inte minst för att det precis har börjat. Men det är rimligt att tro att delar av det vi idag tycker är viktiga kunskaper kommer att stöpas om, och vissa saker kommer vi inte längre tycka vara viktiga. När miniräknare gjorde intåg förutspåddes att vi skulle bli sämre på att räkna för hand och med huvudräkning. Det har kanske i viss mån också blivit så, men det är tydligt att vi fortfarande tycker att grundläggande räknefärdigheter är mycket viktiga. Samtidigt anser vi det närmast meningslöst med saker som att räkna ut kvadratrötter eller multiplicera stora tal för hand. En viktig iakttagelse är också att användning av miniräknare – och mer avancerade verktyg – nu är en del av kunskaper man förväntas ha i samband med matematik.

Något som gör det extra svårt att säga vad ChatGPT och liknande verktyg innebär för vår syn på kunskap är att tekniken fortfarande accelererar. Den AI-teknik vi ser idag är miltals bättre än [den som fanns 2019](https://www.theguardian.com/technology/2019/feb/14/elon-musk-backed-ai-writes-convincing-news-fiction) – och redan då väckte både uppmärksamhet, frågor och oro. Under våren 2023 förväntas GPT-3.5, som är den underliggande modellen för ChatGPT, ersättas av en mycket mer kapabel GPT-4, och flera andra företag har liknande tjänster som ännu ej lanserats.

[Några ord om att det krävs kunskaper för att ha omdöme, och omdöme behövs alltid. Att ChatGPT egentligen bara är användbar för sådant vi redan kan, men där vi vill ha hjälp att göra det snabbare, eller mer.]

Om du vill läsa mer om hur växande AI-teknik kan påverka människans syn på sig själv kan du titta i kapitel [N].


### Flera nivåer att använda omdömet på

[Betrakta budskap från ChatGPT som från en lärarstudent.]

[Exempel på felaktiga påståenden från ChatGPT kommer att finnas i den här boken, för att påminna om att vi alltid måste använda vårt omdöme och ha det som ett filter mellan ChatGPT och elever – särskilt elever som ännu inte är vuxna.]

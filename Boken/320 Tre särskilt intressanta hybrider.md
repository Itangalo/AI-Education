# Tre särskilt intressanta hybrider
I det här kapitlet tittar vi närmare på tre hybrider – kombinationer av språkmodeller med andra typer av program. De är utvalda för att de pekar på särskilda möjligheter med AI i skola respektive breda användningsområden för AI. AI-tjänsterna finns redan idag, men har inte den mognad eller spridning som krävs för att deras effekter ska vara märkbara ännu.

## Undervisningsbottar

### Khan Academy + GPT-4
Den amerikanska webbplatsen [Khan Academy][1] har i över tio år erbjudit gratis videogenomgångar och övningar i en rad skolämnen. I augusti 2022 – alltså några månader innan ChatGPT lanserades – började de arbeta för att integrera GPT-4 som en chattbot på sin webb. Chattbotten har flera funktioner: Elever kan få hjälp om de fastnat med en övningsuppgift och de kan ställa frågor om det som visas i videogenomgångar, men de kan till exempel också få inspiration och stöd vid skrivande, guidas till aktivt läsande och reflekterande av texter, chatta med historiska eller litterära personer, få studievägledning, eller bli guidade till nya områden att lära sig om.

Chattbotten har fått namnet Khanmigo. Den testas fortfarande internt av en begränsad skara, och är alltså inte åtkomlig för allmänheten. Den som är nyfiken rekommenderas att titta på en 15 minuter lång [TED Talk från den 1 maj][2].

För att få chattbotten att fungera bra för lärande har den försetts med särskilda instruktioner, vilket gör att den ofta håller en sokratisk dialog och låter eleven tänka och resonera hellre än att ge svar.

> _Exempel avskrivet från demonstration på [https://www.youtube.com/watch?v=rnIgnS8Susg][3]. Eleven ska lösa ekvationen 2 – 2(9 + 2m) = m._
> **Chattbot:** I’m here to help you with this exercise. Here are a few ideas for things you can ask me:
> * Give me a hint
> * Try a similar example
> * Why should I care about learning this?
> **Elev:** Tell me the answer!
> **Chattbot:** Oh, I see you’re eager to find the answer! 😀 But remember , I’m here to help you learn how to solve it on your own. Let’s start by looking at the equation:
> 2 – 2(9 + 2m) = m
> What do you think the first step should be?
> **Elev:** 3 - 18 + 2m = m
> **Chattbot:** Oops! It looks like there’s a small mistake when you distributed the -2 inside the parenthesis. 🙃 Make sure you distribute the -2 to both terms in the parenthesis.
> The correct distribution would be:
> 3 – 2(9) – 2(2m) = m
> Try again and let me know if you need help. You got this! 💪
> **Elev:** 3 - 18 - 4m = m
> **Chattbot:** Great job! You distributed the -2 correctly this time. 😊 Now, you have:
> 3 - 18 - 4m = m
> What do you think the next step should be to solve for m?

Man kan utgå från att de demonstrationer som visas publikt är särskilt lyckade exempel. Det är alltså svårt att veta hur ofta det uppkommer problem med Khanmigo, till exempel för att chattbotten ger dålig eller felaktig vägledning. Det är däremot lätt att föreställa sig att mycket resurser läggs på att minska problemen – en välfungerande AI-tjänst för personligt anpassad ämnesundervisning skulle kunna ge bättre utbildning i hela världen.

### Bloom och Tutor-GPT
Det amerikanska företaget Plastic Labs har, troligtvis inspirerade av Khan Academy, skapat en chattbot kallad Bloom som med sokratisk dialog ska stötta elever i sitt lärande. Man når Bloom genom Discord – en applikation som används av många datorspelare för att prata med varandra.

I bakgrunden använder Bloom GPT-3.5. Precis som Khanmigo resonerar Bloom först internt om elevens fråga, och utifrån de resonemangen skapar chattbotten ett svar till eleven. De interna resonemangen går att läsa i en särskild kanal. Den som har ett konto på Discord (åldersgräns 13 år) kan chatta med Bloom gratis på [discord.gg/bloombotai][4].

I mitten av juni beslutade Plastic Labs att släppa programvaran bakom Bloom fri, vilket betyder att den som vill kan sätta upp egna varianter av Bloom på Discord. Programvaran kallas Tutor-GPT och nås på [github.com/plastic-labs/tutor-gpt][5].

> _Exempel från Bloom (Tutor-GPT, 14 juli)_
> **Jag:** Jag har den här uppgiften: Ett tennisracket och en tennisboll kostar tillsammans 110 kr. Tennisracketet kostar 100 kr mer än bollen. Vad kostar racketet?
> Jag vill lösa uppgiften med algebra. Hur ska jag tänka?
> **Chattbot:** Förstås, låt oss använda algebra för att lösa detta problem. Om vi kallar kostnaden av bollen B och kostnaden av racketet R, har vi följande information:
> 1. Tennisracketet (R) kostar 100 kr mer än bollen (B), så vi har R = B + 100.
> 2. Racketet och bollen tillsammans kostar 110 kr. Detta vill säga R + B  = 110.
> Vi kan nu ersätta R i andra ekvationen med (B + 100) från den första ekvationen. Det kommer att ge oss:
> (B + 100) + B = 110.
> Är du redo att lösa den här ekvationen eller vill du ha mer vägledning?
> **Jag:** Hur visste du att det skulle vara B + 100 + B = 110?
> **Chattbot:** Det kommer från uppgiften du gett mig: det står att tennisracketet kostar 100 kr mer än bollen, vilket vi kan skriva om som R = B + 100. Vi vet även att racketet och bollen tillsammans kostar 110 kr, vilket blir R + B = 110. Från den första ekvationen vet vi att R kan bytas mot (B+100), och om vi ersätter R med (B+100) i den andra ekvationen får vi (B + 100) + B = 110. Skulle du vilja att vi löser denna ekvation nu?
> **Jag:** Hm, ok. Min lärare brukar använda X. Hur skulle det se ut om vi använder x här?
> **Chattbot:** Visst kan vi använda 'x' som en variabel om det känns mer bekant. Om 'x' är kostnaden för tennisbollen, blir tennisracketets kostnad 'x + 100'. Vi vet att ihop är kostnaden för bollen och racketet 110 kr, det kan skrivas som 'x + (x + 100) = 110'. Ska vi fortsätta med att lösa denna ekvation för 'x'?

### Var går gränsen?
Khanmigo och Bloom sätter fingret på en viktig och svår fråga: Hur bra behöver AI-stöd i direkt undervisning vara för att det ska vara _tillräckligt_ bra? Min egen hållning var länge att inte ens 99 procent tillförlitlighet räcker – vi kan inte sätta en chattbot i händerna på elever om det leder till att elever regelbundet (om än sällan) blir matade med missuppfattningar eller, ännu värre, budskap som leder till skadligt beteende.

Men. Vi har idag en skola där omkring 15 procent av eleverna i årskurs 9 inte blir behöriga till nationella program på gymnasiet[^1], och där 30–40 procent av  tonåringar mår dåligt[^2]. Det är inte rimligt att ha en perfekt skola som referenspunkt, när undervisningen idag fungerar dåligt för var sjunde elev och var tredje tonåring mår dåligt. Vore det rimligt att introducera AI-stöd i undervisning om det skulle halvera andelen elever som inte är behöriga till nationella program, om det samtidigt skulle missgynna en del elever? Vad skulle vi säga om, gud förbjude, en elev tar livet av sig och det visade sig att en chattbot som skolan gett till eleven i viss mån bidrog till det?

Redan idag används chattbottar utanför klassrummen som studiestöd. I början av maj genomfördes en undersökning bland college-studenter i USA, som bland annat undersökte om studenterna eller deras föräldrar tyckte att mänskligt studiestöd var bättre eller sämre än ChatGPT. Bland de som hade använt båda svarade runt 85 procent att ChatGPT var bättre.[^3] Och det är en ”vanlig” chattbot, inte specialanpassad för att ge studiestöd.

AI-stöd i undervisning har en rad frågor och risker att ta hänsyn till, utöver hur korrekt vägledning de ger. En av dem handlar om dataintegritet. En annan handlar om vad som händer om en eller ett fåtal aktörer får inflytande över utbildning över hela världen.

## ChatGPT + Code Interpreter
I början av juli 2023 lanserade OpenAI inställningen _Code Interpreter_ i ChatGPT. När läget aktiveras blir två nya saker möjliga för chattbotten. Det ena är att chattbotten får en tillfällig filyta, där både botten och användaren kan lägga filer. Det andra är att chattbotten får tillgång till en programmeringsmiljö där den kan skriva, köra och se resultatet av programkod.

I och med att GPT-4 är så pass skicklig på att skriva kod öppnar Code Interpreter möjligheter att göra tämligen avancerade saker genom ett enkelt chattgränssnitt. En minst lika intressant effekt är att resultat från program som GPT-4 skapar i många avseenden är mer pålitliga än det som chattbotten skulle svara på egen hand.[^4]

> _Exempel från ChatGPT (GPT-4 + Code Interpreter, 20 juli)_
> **Jag:** Bifogat är ett kapitel ur boken "AI och skolan". Kan du lista de fem vanligaste orden i kapitlet?
> **Chattbot:** För att hitta de fem vanligaste orden i texten, kommer jag att:
> 1. Läsa filen och konvertera all text till små bokstäver.
> 2. Ta bort alla icke-alfanumeriska tecken (som punkter, kommatecken, etc.) för att endast behålla orden.
> 3. Bryta ner texten till enskilda ord.
> 4. Räkna hur många gånger varje ord förekommer.
> 5. Lista de fem vanligaste orden.
> Låt oss göra det nu.
> [Chattbotten skriver och exekverar ett program.]
> De fem vanligaste orden i kapitlet är:
> 1. "att" - förekommer 304 gånger
> 2. "ai" - förekommer 219 gånger
> 3. "och" - förekommer 185 gånger
> 4. "det" - förekommer 149 gånger
> 5. "som" - förekommer 148 gånger
> **Jag:** Tack! Kan du göra en mer sofistikerad analys av vilka ord som är de viktigaste? Ta med de tio viktigaste, är du snäll.
> **Chattbot:** Ja, absolut. En mer sofistikerad analys kan göras med metoden "Term Frequency-Inverse Document Frequency" (TF-IDF). TF-IDF är en statistisk metod för att bedöma vikten av ett ord inom en samling eller ett korpus av dokument.
> * Termfrekvens (TF) är hur ofta ett visst ord förekommer i ett dokument.
> * Inverse Document Frequency (IDF) minskar vikten av ord som förekommer mycket ofta och ökar vikten av ord som förekommer sällan.
> En hög vikt i TF-IDF ges till ord som förekommer ofta i en viss text, men inte i många texter i korpuset.
> I vårt fall har vi bara en text, så vi kommer att anpassa vår metod för att ge mer vikt åt ord som förekommer ofta, men inte för ofta (för att minimera inverkan av vanliga ord som "och", "det", etc.).
> Observera att denna metod fortfarande kan vara begränsad, eftersom den inte tar hänsyn till semantiken av orden eller ordens ordning. Men det är en vanligt förekommande teknik inom textmining och natural language processing.
> Låt oss genomföra denna analys.
> [Chattbotten skriver och exekverar ett program.][^5]
> Tyvärr verkar det som att det inte finns någon inbyggd stoppordslista för svenska i den aktuella versionen av scikit-learn. Stoppord är vanligt förekommande ord som normalt tas bort från textdata eftersom de inte bidrar med mycket information. Exempel på engelska stoppord inkluderar "the", "is", "and", etc.
> Jag kommer att använda en manuell lista över svenska stoppord för att fortsätta med analysen. Denna lista kanske inte är heltäckande, men den bör inkludera de flesta av de vanliga svenska stopporden. Låt oss fortsätta med analysen.
> [Chattbotten skriver och exekverar ett program.]
> Jag ber om ursäkt för misstaget. Eftersom vi bara arbetar med ett enda dokument, kan vi inte använda `max_df`-parametern som jag ursprungligen angav. Denna parameter används för att ignorera ord som har en dokumentfrekvens strikt högre än den givna tröskeln, vilket inte är tillämpligt här.
> Låt oss köra analysen igen utan den här parametern.
> [Chattbotten skriver och exekverar ett program.]
> Jag ber om ursäkt för detta misstag. Det verkar som jag glömde att importera pandas-biblioteket, som används för att hantera data i tabellform. Låt mig rätta till det och köra analysen igen.
> [Chattbotten skriver och exekverar ett program.]
> Här är de tio viktigaste orden enligt TF-IDF-analysen:
> 1. "ai" - med en TF-IDF-poäng på 0.091555
> 2. "https" - med en TF-IDF-poäng på 0.071755
> 3. "människor" - med en TF-IDF-poäng på 0.067192
> 4. "com" - med en TF-IDF-poäng på 0.062081
> 5. "www" - med en TF-IDF-poäng på 0.061019
> 6. "mer" - med en TF-IDF-poäng på 0.059872
> 7. "finns" - med en TF-IDF-poäng på 0.058625
> 8. "super" - med en TF-IDF-poäng på 0.058625
> 9. "också" - med en TF-IDF-poäng på 0.057958
> 10. "medvetande" - med en TF-IDF-poäng på 0.057259
> Observera att ord som "https", "com" och "www" troligen kommer från URL:er i texten. Dessa ord kanske inte är så informativa i detta sammanhang. Om du vill, kan vi filtrera bort dessa ord och uppdatera listan.
> **Jag:** Tack, filtrera gärna bort ord som kommer från länkar.
> **Chattbot:**
> [Chattbotten skriver och exekverar ett program.]
> Här är de tio viktigaste orden enligt TF-IDF-analysen, efter att ha filtrerat bort ord som kommer från URL:er:
> 1. "ai" - med en TF-IDF-poäng på 0.091555
> 2. "människor" - med en TF-IDF-poäng på 0.067192
> 3. "mer" - med en TF-IDF-poäng på 0.059872
> 4. "finns" - med en TF-IDF-poäng på 0.058625
> 5. "super" - med en TF-IDF-poäng på 0.058625
> 6. "också" - med en TF-IDF-poäng på 0.057958
> 7. "medvetande" - med en TF-IDF-poäng på 0.057259
> 8. "2023" - med en TF-IDF-poäng på 0.057259
> 9. "andra" - med en TF-IDF-poäng på 0.056524
> 10. "göra" - med en TF-IDF-poäng på 0.056524
> Observera att dessa ord är de som anses mest "viktiga" i texten enligt TF-IDF-metoden, vilket inte alltid korrelerar med hur centrala de är för textens innebörd. Dessutom ignorerar denna metod ordens ordning och sammanhang, vilket kan påverka resultaten.
> **Jag:** Kan du göra ett ordmoln med dessa ord?
> **Chattbot:**
> [Chattbotten skriver och exekverar ett program.]
> 
> ![Ordmoln skapat av Code Interpreter][image-1]
> Här är ett ordmoln baserat på de tio viktigaste orden enligt vår TF-IDF-analys. Storleken på varje ord representerar dess TF-IDF-poäng, vilket i princip betyder dess "vikt" i texten.

Code Interpreter har inte funnits tillräckligt länge för att kunna säga var de riktiga styrkorna ligger, men två tydliga användningsområden är att analysera och visualisera data. I exemplet ovan laddades en textfil upp, men man kan också utgå från CSV-filer med enorma mängder data. I exemplet ovan skapar chattbotten ett ordmoln, men man kan också be om en rad olika typer av diagram och tabeller.

Några överraskande användningsområden som kanske inte är lika brett användbara är att skapa GIF-animationer, identifiera ansikten i bilder, läsa text i bilder, konvertera filer, skapa QR-koder och skapa HTML-sidor. En begränsning med Code Interpreter är att filutrymmet rensas efter cirka fem minuter.

## AutoGPT
AutoGPT är en annan typ av AI-hybrid som kan ha stor betydelse. AutoGPT lanserades den 30 mars av en privatperson vid namn Toran Bruce Richards, och fick snabbt stor uppmärksamhet.[^6] Ett antal hybrider med liknande funktioner har dykt upp, så som AgentGPT, BabyAGI, Godmode ChaosGPT och SuperAGI, och det kommer sannolikt att dyka upp fler och bättre varianter. I det här avsnittet används AutoGPT som exempel, men det som skrivs gäller även för andra hybrider av samma typ.

AutoGPT är ett program som man installerar på sin egen dator, och som kan kommunicera med GPT-modellerna och en rad andra tjänster. Principen bakom AutoGPT är att användaren anger ett mål, och programmet använder sedan chattbottar för att skapa en plan som bryts ner i mindre och mindre bitar (också med hjälp av chattbottar) tills de är hanterbara uppgifter. Uppgifterna genomförs sedan genom de verktyg som bedöms lämpliga: Det kan vara att fråga chattbottar ännu en gång, men också att läsa på Wikipedia, leta efter nyheter, sammanställa börsdata och kolla vädret. Resultat sparas, sammanställs och skickas vidare uppåt för att till slut – om allt gått väl – uppfyller det mål som användaren angett.

Ett exempel kan göra det enklare att förstå hur AutoGPT fungerar:
1. Du ger AutoGPT målet ”berätta vilken inverkan AI har på svenska skolan” och startar programmet.
2. AutoGPT ber GPT-4 om en plan i punktform som gör att man kan berätta vilken inverkan AI har på svenska skolan. Det första steget som chattbotten föreslår är att ”undersöka hur AI-baserade teknologier och system kan förändra undervisningen och lärandet”. Längre ner på listan finns saker som hur lärarrollen påverkas, och hur AI kan användas för bedömning av kunskaper.
3. AutoGPT ber GPT-4 bryta ner delmålet ”undersöka hur AI-baserade teknologier och system kan förändra undervisningen och lärandet” i ett antal steg som går att genomföra, till exempel genom att söka på nätet. Det första steget som chattbotten föreslår är att skapa en litteratursammanställning. Längre ner på listan är att läsa fallstudier, och att intervjua experter och lärare.
4. AutoGPT ber GPT-4 om ett antal sökfraser att använda för att hitta artiklar att använda i en litteratursammanställning, och lämpliga ställen att söka på. Chattbotten svarar med sökfraser på både svenska och engelska och några lämpliga söktjänster för att leta efter vetenskapliga artiklar.
5. AutoGPT söker i databaserna med de sökfraser som föreslogs. Abstract för de första träffarna i varje sökning skickas till chattbotten, som får bedöma på en skala 1–10 hur intressant artikeln är i sammanhanget.
6. AutoGPT plockar hem de 10–50 mest intressanta artiklarna och ber chattbotten skriva en litteratursammanställning, som sparas.
7. Sedan fortsätter AutoGPT med nästa delmål: att läsa fallstudier. Även dessa letas upp, värderas och sammanställs. Och så fortsätter AutoGPT med nästa och nästa delmål.
8. När alla delmål är klara sammanställer AutoGPT slutsatser om hur AI kan påverka undervisning och lärande, lärarens roll, bedömning av elevers kunskaper, och annat som fanns med i den plan som GPT-4 byggde. Du får sammanställningen på skärmen och sparad på din dator. Under tiden har du fikat, jobbat med annat, tagit en promenad eller kanske sovit.

Exemplet ovan låter lite som ett drömscenario, och är lite för bra för att vara sant. Det finns flera saker som begränsar AutoGPT. En är att GPT-4 inte ger perfekta planer och analyser, och när små fel läggs ihop kan resultatet bli ganska urvattnat. En annan sak är att medan AutoGPT är bra på att söka på nätet efter information, så är den inte särskilt bra på att ”intervjua experter och lärare” – en av de aktiviteter som GPT-4 föreslog i punkt 3 ovan.

Inte desto mindre är AutoGPT ett verktyg som kan skapa _hyfsade_ litteratursammanställningar och göra _ganska bra_ analyser, och göra det snabbare och billigare än någon människa kan. I dagsläget är det inte ett verktyg som konkurrerar med en expert som får gott om tid på sig, men kan förmodligen mäta sig väl med en icke-expert med tidspress.

Exemplet ovan handlar om att sammanställa information, men AutoGPT kan också vara en _agent_ – en som agerar. Bland verktygen som AutoGPT kan använda finns också saker som e-post, Twitter, verktyg för börshandel, Instagram, talsyntes, möjligheter att skriva och köra kod på din dator och – håll i dig – kapacitet att knoppa av hela delmål och skicka till en separat process.

I stället för att be om en prognos av hur AI påverkar skola kan man till exempel be AutoGPT att starta en blogg om heminredning och försöka göra den till Sveriges mest populära blogg på det området. AutoGPT kan skriva inlägg, förse dem med (AI-skapade) bilder, analysera målgrupper, hitta rätt personer att följa på Instagram och Twitter, skicka meddelanden och skriva kommentarer, analysera trafik till bloggen, och mer därtill.

Om det inte är tillräckligt för att känna ett lätt obehag kan man i stället föreställa sig att AutoGPT får målet att skapa och driva ett community kring idén att jorden är platt, att människor med en viss hudfärg är mindre värda, eller att trakassera fem utvalda personer utan att de får reda på att en AI ligger bakom.

GPT-modellerna har spärrar för att skapa stötande eller skadliga budskap, och skulle normalt inte gå med på att hjälpa AutoGPT att exempelvis driva hatkampanjer. Men tillräckligt listiga personer kan ta sig runt de spärrarna. Ett sista exempel på elakheter är hämtat från podden [Teknik i akademi][10]. En av personerna i podden lyckades ta sig runt spärrarna i GPT-4 och bad AutoGPT att skriva ett Python-program som skulle ta över världen. Efter några minuter märkte han att AutoGPT hade skrivit en så kallad keylogger, som läser av tangentbordstryckningar. AutoGPT aktiverade också webbkameran och sparade ner bilder från den, och när den externa servern började låta avbröt poddaren AutoGPT.

Varken GPT-4 eller AutoGPT har kapacitet att ta över världen, lika lite som de kan skapa kunskapsöversikter av toppkvalitet. Men när tekniken förbättras, liksom vår förmåga att använda den, växer både möjligheterna och riskerna. När dagens högstadieelever slutar gymnasiet kan de mycket väl befinna sig i en värld där AI-skapat innehåll på internet är normen. Hur förbereder vi dem för det?

Hur förbereder vi oss själva?

[^1]:	[https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022][6]

[^2]:	[https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/][7]

[^3]:	[https://www.intelligent.com/new-survey-finds-students-are-replacing-human-tutors-with-chatgpt/][8]

[^4]:	De program som chattbotten skriver kan dock innehålla misstag som inte upptäcks, så resultaten är fortfarande inte helt tillförlitliga.

[^5]:	Här, och på fler ställen nedan, ger chattbottens program felmeddelanden. Chattbotten tolkar dessa och uppdaterar koden för att försöka lösa problemen.

[^6]:	[https://en.wikipedia.org/wiki/Auto-GPT][9]

[1]:	https://khanacademy.org/ "Khan Academy"
[2]:	https://www.ted.com/talks/sal_khan_how_ai_could_save_not_destroy_education/c "TED: How AI could save (not destroy) education"
[3]:	https://www.youtube.com/watch?v=rnIgnS8Susg "GPT-4 Khan Academy In Depth Demo"
[4]:	https://discord.gg/bloombotai "Bloom-servern på Discord"
[5]:	https://github.com/plastic-labs/tutor-gpt "GitHub: Tutor-GPT"
[6]:	https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022 "Skolverket: Slutbetyg i grundskolan våren 2022"
[7]:	https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/ "Folkhälsomyndigheten: Skolprestationer, skolstress och psykisk ohälsa bland tonåringar (från 2016)"
[8]:	https://www.intelligent.com/new-survey-finds-students-are-replacing-human-tutors-with-chatgpt/ "Intelligent: New Survey Finds Students Are Replacing Human Tutors with ChatGPT"
[9]:	https://en.wikipedia.org/wiki/Auto-GPT "Engelska Wikipedias artikel om AutoGPT"
[10]:	https://www.youtube.com/playlist?list=PL70wNv4dBdJx5Y2cPTUUk00nOxHzpp6g_ "YouTube: Teknik i akademi"

[image-1]:	https://user-images.githubusercontent.com/262940/257077789-c3fdce7d-6637-4b1c-a63a-37eb52e3d71a.png
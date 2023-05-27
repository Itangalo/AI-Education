# Två särskilt intressanta hybrider
I det här kapitlet tittar vi närmare på två hybrider – kombinationer av språkmodeller med andra typer av program. De är utvalda för att de pekar på särskilda möjligheter med AI i skola respektive breda användningsområden för AI. AI-tjänsterna finns redan idag, men har inte den mognad eller spridning som krävs för att deras effekter ska vara märkbara ännu.

## Khan Academy + GPT-4
Den amerikanska webbplatsen [Khan Academy][1] har i över tio år erbjudit gratis videogenomgångar och övningar i en rad skolämnen. I augusti 2022 – alltså några månader innan ChatGPT lanserades – började de arbeta för att integrera GPT-4 som en chattrobot på sin webb. Chattroboten har flera funktioner: Elever kan få hjälp om de fastnat med en övningsuppgift och de kan ställa frågor om det som visas i videogenomgångar, men de kan till exempel också få inspiration och stöd vid skrivande, guidas till aktivt läsande och reflekterande av texter, chatta med historiska eller litterära personer, få studievägledning, eller bli guidade till nya områden att lära sig om.

Chattroboten har fått namnet Khanmigo. Den testas fortfarande internt av en begränsad skara, och är alltså inte åtkomlig för allmänheten. Den som är nyfiken rekommenderas att titta på en 15 minuter lång [TED Talk från den 1 maj][2].

För att få chattroboten att fungera bra för lärande har den försetts med särskilda instruktioner, vilket gör att den ofta håller en sokratisk dialog och låter eleven tänka och resonera hellre än att ge svar.

Det är svårt att veta hur ofta det uppkommer problem med Khanmigo, till exempel för att chattroboten ger dålig eller felaktig vägledning. Det är däremot lätt att föreställa sig att mycket resurser läggs på att minska problemen – en välfungerande AI-tjänst för personligt anpassad ämnesundervisning skulle kunna ge bättre utbildning i hela världen.

### Var går gränsen?
Khanmigo sätter fingret på en viktig och svår fråga: Hur bra behöver AI-stöd i direkt undervisning vara för att det ska vara _tillräckligt_ bra? Min egen hållning var länge att inte ens 99 procent tillförlitlighet räcker – vi kan inte sätta en chattrobot i händerna på elever om det leder till att elever regelbundet (om än sällan) blir matade med missuppfattningar eller, ännu värre, budskap som leder till skadligt beteende.

Men. Vi har idag en skola där omkring 15 procent av eleverna i årskurs 9 inte blir behöriga till nationella program på gymnasiet[^1], och 30–40 procent av  tonåringar som mår dåligt[^2]. Det är inte rimligt att ha en perfekt skola som referenspunkt, när undervisningen idag fungerar dåligt för var sjunde elev och var tredje tonåring mår dåligt. Vore det rimligt att introducera AI-stöd i undervisning om det skulle halvera andelen elever som inte är behöriga till nationella program, om det samtidigt skulle missgynna en del elever? Vad skulle vi säga om, gud förbjude, en elev tar livet av sig och det visade sig att en chattrobot som skolan gett till eleven i viss mån bidrog till det?

AI-stöd i undervisning har en rad andra frågor och risker att ta hänsyn till. En av dem handlar om dataintegritet. En annan handlar om vad som händer om en eller ett fåtal aktörer får inflytande över utbildning över hela världen.

## AutoGPT
AutoGPT är en annan fascinerande AI-hybrid. Denna lanserades den 30 mars av en privatperson vid namn Toran Bruce Richards, och har snabbt fått stor uppmärksamhet.[^3] Det har också uppstått ett par andra verktyg med liknande funktioner.[^4]

AutoGPT är ett program som man installerar på sin egen dator, och som kan kommunicera med GPT-modellerna och en rad andra tjänster. Principen bakom AutoGPT är att användaren anger ett mål, och programmet använder sedan chattrobotar för att skapa en plan som bryts ner i mindre och mindre bitar (också med hjälp av chattrobotar) tills de är hanterbara uppgifter. Uppgifterna genomförs sedan genom de verktyg som bedöms lämpliga: Det kan vara att fråga chattrobotar ännu en gång, men också att läsa på Wikipedia, leta efter nyheter, sammanställa börsdata och kolla vädret. Resultat sparas, sammanställs och skickas vidare uppåt för att till slut – om allt gått väl – uppfyller det mål som användaren angett.

Ett exempel kan göra det enklare att förstå hur AutoGPT fungerar:
1. Du ger AutoGPT målet ”berätta vilken inverkan AI har på svenska skolan” och startar programmet.
2. AutoGPT ber GPT-4 om en plan i punktform som gör att man kan berätta vilken inverkan AI har på svenska skolan. Det första steget som chattroboten föreslår är att ”undersöka hur AI-baserade teknologier och system kan förändra undervisningen och lärandet”. Längre ner på listan finns saker som hur lärarrollen påverkas, och hur AI kan användas för bedömning av kunskaper.
3. AutoGPT ber GPT-4 bryta ner delmålet ”undersöka hur AI-baserade teknologier och system kan förändra undervisningen och lärandet” i ett antal steg som går att genomföra, till exempel genom att söka på nätet. Det första steget som chattroboten föreslår är att skapa en litteratursammanställning. Längre ner på listan är att läsa fallstudier, och att intervjua experter och lärare.
4. AutoGPT om ett antal sökfraser att använda för att hitta artiklar att använda i en litteratursammanställning, och lämpliga ställen att söka på. Chattroboten svarar med sökfraser på både svenska och engelska och några stora databaser för att leta efter vetenskapliga artiklar.
5. AutoGPT söker i databaserna, med de sökfraser som föreslogs. Abstrakt för de första träffarna i varje sökning skickas till chattroboten, som får bedöma på en skala 1–10 hur intressant artikeln är i sammanhanget.
6. AutoGPT plockar hem de 10–50 mest intressanta artiklarna och ber chattroboten skriva en litteratursammanställning, som sparas.
7. Sedan fortsätter AutoGPT med nästa delmål: att läsa fallstudier. Även dessa letas upp, värderas och sammanställs. Och så fortsätter AutoGPT med nästa och nästa delmål.
8. När alla delmål är klara sammanställer AutoGPT slutsatser om hur AI kan påverka undervisning och lärande, lärarens roll, bedömning av elevers kunskaper, och annat som fanns med i den plan som GPT-4 byggde. Då får sammanställningen på skärmen och sparad på din dator. Under tiden har du fikat, jobbat med annat eller kanske sovit.

Exemplet ovan låter lite som ett drömscenario, och är lite för bra för att vara sant. Det finns flera saker som begränsar AutoGPT. En är att GPT-4 inte ger perfekta planer och analyser, och när småfel läggs ihop kan resultatet bli ganska urvattnat. En annan sak är att medan AutoGPT är bra på att söka på nätet efter information, så är den inte särskilt bra på att ”intervjua experter och lärare” – en aktivitet som föreslogs i punkt 3 i listan ovan.

Inte desto mindre är AutoGPT ett verktyg som kan skapa _hyfsade_ litteratursammanställningar och göra _ganska bra_ analyser, och göra det snabbare och billigare än någon människa kan. I dagsläget är det inte ett verktyg som konkurrerar med en expert som får gott om tid på sig, men kan förmodligen mäta sig väl med en icke-expert som inte har särskilt mycket tid att lägga en uppgift.

Exemplet ovan handlar om att sammanställa information, men AutoGPT kan också vara en _agent_ – en som agerar. Bland verktygen som AutoGPT kan använda finns också saker som e-post, Twitter, verktyg för börshandel, Instagram, talsyntes, möjligheter att skriva och köra kod på din dator och – håll i dig – kapacitet att knoppa av hela hela delmål och skicka till en separat process.

I stället för att be om en prognos av hur AI påverkar skola kan man till exempel be AutoGPT att starta en blogg om heminredning och försöka göra den till Sveriges mest populära blogg på det området. AutoGPT kan skriva inlägg, förse dem med (AI-skapade) bilder, analysera målgrupper, hitta rätt personer att följa på Instagram och Twitter, skriva kommentarer och skicka meddelanden, analysera trafik till bloggen, och mer därtill.

Om det inte är tillräckligt för att känna ett lätt obehag kan man i stället föreställa sig att AutoGPT får målet att skapa och driva ett community kring idén att jorden är platt, att människor med en viss hudfärg är mindre värda, eller att trakassera utvalda personer utan att de ska få reda på att en AI ligger bakom.

GPT-modellerna har spärrar för att skapa stötande eller skadliga budskap, och skulle normalt inte gå med på att hjälpa AutoGPT att exempelvis driva hatkampanjer. Men tillräckligt listiga personer kan ta sig runt de spärrarna. Ett sista exempel på elakheter är hämtat från podden [Teknik i akademi][6]. En av deltagarna i podden lyckades ta sig runt spärrarna i GPT-4 och instruerade, kort sammanfattat, AutoGPT att skriva ett Python-program som skulle ta över världen. Efter några minuter märkte han att AutoGPT hade skrivit en så kallad keylogger, som läser av tangentbordstryckningar. AutoGPT aktiverade också webbkameran och sparade ner bilder från den, och när den externa servern som datorn var kopplad till började låta stängde han ner AutoGPT.

Varken GPT-4 eller AutoGPT har kapacitet att ta över världen, lika lite som de kan skapa kunskapsöversikter av toppkvalitet. Men när tekniken förbättras, liksom vår förmåga att använda den, växer både möjligheterna och riskerna. När dagens högstadieelever slutar gymnasiet kan de mycket väl befinna sig i en värld där AI-skapat innehåll på internet är normen. Hur förbereder vi dem för det?

Hur förbereder vi oss själva?

[^1]:	[https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022][3]

[^2]:	[https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/][4]

[^3]:	[https://en.wikipedia.org/wiki/Auto-GPT][5]

[^4]:	Den som vill utforska den här typen av hybrider rekommenderas att börja med webbtjänsten AgentGPT, som är klart mindre kompetent än AutoGPT men inte kräver krånglig installation.

[1]:	https://khanacademy.org/ "Khan Academy"
[2]:	https://www.ted.com/talks/sal_khan_how_ai_could_save_not_destroy_education/c "TED: How AI could save (not destroy) education"
[3]:	https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022 "Skolverket: Slutbetyg i grundskolan våren 2022"
[4]:	https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/ "Folkhälsomyndigheten: Skolprestationer, skolstress och psykisk ohälsa bland tonåringar (från 2016)"
[5]:	https://en.wikipedia.org/wiki/Auto-GPT "Engelska Wikipedias artikel om AutoGPT"
[6]:	https://www.youtube.com/playlist?list=PL70wNv4dBdJx5Y2cPTUUk00nOxHzpp6g_ "YouTube: Teknik i akademi"
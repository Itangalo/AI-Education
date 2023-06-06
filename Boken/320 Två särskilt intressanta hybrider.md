# Två särskilt intressanta hybrider
I det här kapitlet tittar vi närmare på två hybrider – kombinationer av språkmodeller med andra typer av program. De är utvalda för att de pekar på särskilda möjligheter med AI i skola respektive breda användningsområden för AI. AI-tjänsterna finns redan idag, men har inte den mognad eller spridning som krävs för att deras effekter ska vara märkbara ännu.

## Khan Academy + GPT-4
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

### Var går gränsen?
Khanmigo sätter fingret på en viktig och svår fråga: Hur bra behöver AI-stöd i direkt undervisning vara för att det ska vara _tillräckligt_ bra? Min egen hållning var länge att inte ens 99 procent tillförlitlighet räcker – vi kan inte sätta en chattbot i händerna på elever om det leder till att elever regelbundet (om än sällan) blir matade med missuppfattningar eller, ännu värre, budskap som leder till skadligt beteende.

Men. Vi har idag en skola där omkring 15 procent av eleverna i årskurs 9 inte blir behöriga till nationella program på gymnasiet[^1], och där 30–40 procent av  tonåringar mår dåligt[^2]. Det är inte rimligt att ha en perfekt skola som referenspunkt, när undervisningen idag fungerar dåligt för var sjunde elev och var tredje tonåring mår dåligt. Vore det rimligt att introducera AI-stöd i undervisning om det skulle halvera andelen elever som inte är behöriga till nationella program, om det samtidigt skulle missgynna en del elever? Vad skulle vi säga om, gud förbjude, en elev tar livet av sig och det visade sig att en chattbot som skolan gett till eleven i viss mån bidrog till det?

Redan idag används chattbottar utanför klassrummen som studiestöd. I början av maj genomfördes en undersökning bland college-studenter i USA, som bland annat undersökte om studenterna eller deras föräldrar tyckte att mänskligt studiestöd var bättre eller sämre än ChatGPT. Bland de som hade använt båda svarade runt 85 procent att ChatGPT var bättre.[^3] Och det är en ”vanlig” chattbot, inte specialanpassad för att ge studiestöd.

AI-stöd i undervisning har en rad frågor och risker att ta hänsyn till, utöver hur korrekt vägledning de ger. En av dem handlar om dataintegritet. En annan handlar om vad som händer om en eller ett fåtal aktörer får inflytande över utbildning över hela världen.

## AutoGPT
AutoGPT är en annan AI-hybrid som kan ha stor betydelse. Den lanserades den 30 mars av en privatperson vid namn Toran Bruce Richards, och har snabbt fått stor uppmärksamhet.[^4] Sedan AutoGPT lanserades har även några andra hybrider med liknande funktioner dykt upp.[^5]

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

Exemplet ovan handlar om att sammanställa information, men AutoGPT kan också vara en _agent_ – en som agerar. Bland verktygen som AutoGPT kan använda finns också saker som e-post, Twitter, verktyg för börshandel, Instagram, talsyntes, möjligheter att skriva och köra kod på din dator och – håll i dig – kapacitet att knoppa av hela hela delmål och skicka till en separat process.

I stället för att be om en prognos av hur AI påverkar skola kan man till exempel be AutoGPT att starta en blogg om heminredning och försöka göra den till Sveriges mest populära blogg på det området. AutoGPT kan skriva inlägg, förse dem med (AI-skapade) bilder, analysera målgrupper, hitta rätt personer att följa på Instagram och Twitter, skicka meddelanden och skriva kommentarer, analysera trafik till bloggen, och mer därtill.

Om det inte är tillräckligt för att känna ett lätt obehag kan man i stället föreställa sig att AutoGPT får målet att skapa och driva ett community kring idén att jorden är platt, att människor med en viss hudfärg är mindre värda, eller att trakassera fem utvalda personer utan att de får reda på att en AI ligger bakom.

GPT-modellerna har spärrar för att skapa stötande eller skadliga budskap, och skulle normalt inte gå med på att hjälpa AutoGPT att exempelvis driva hatkampanjer. Men tillräckligt listiga personer kan ta sig runt de spärrarna. Ett sista exempel på elakheter är hämtat från podden [Teknik i akademi][8]. En av personerna i podden lyckades ta sig runt spärrarna i GPT-4 och bad AutoGPT att skriva ett Python-program som skulle ta över världen. Efter några minuter märkte han att AutoGPT hade skrivit en så kallad keylogger, som läser av tangentbordstryckningar. AutoGPT aktiverade också webbkameran och sparade ner bilder från den, och när den externa servern började låta avbröt poddaren AutoGPT.

Varken GPT-4 eller AutoGPT har kapacitet att ta över världen, lika lite som de kan skapa kunskapsöversikter av toppkvalitet. Men när tekniken förbättras, liksom vår förmåga att använda den, växer både möjligheterna och riskerna. När dagens högstadieelever slutar gymnasiet kan de mycket väl befinna sig i en värld där AI-skapat innehåll på internet är normen. Hur förbereder vi dem för det?

Hur förbereder vi oss själva?

[^1]:	[https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022][4]

[^2]:	[https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/][5]

[^3]:	[https://www.intelligent.com/new-survey-finds-students-are-replacing-human-tutors-with-chatgpt/][6]

[^4]:	[https://en.wikipedia.org/wiki/Auto-GPT][7]

[^5]:	Den som vill utforska den här typen av hybrider rekommenderas att börja med webbtjänsten AgentGPT, som är klart mindre kompetent än AutoGPT men inte kräver krånglig installation.

[1]:	https://khanacademy.org/ "Khan Academy"
[2]:	https://www.ted.com/talks/sal_khan_how_ai_could_save_not_destroy_education/c "TED: How AI could save (not destroy) education"
[3]:	https://www.youtube.com/watch?v=rnIgnS8Susg "GPT-4 Khan Academy In Depth Demo"
[4]:	https://www.skolverket.se/publikationsserier/beskrivande-statistik/2022/slutbetyg-i-grundskolan---varen-2022 "Skolverket: Slutbetyg i grundskolan våren 2022"
[5]:	https://www.folkhalsomyndigheten.se/publikationer-och-material/publikationsarkiv/s/skolprestationer-skolstress-och-psykisk-ohalsa-bland-tonaringar/ "Folkhälsomyndigheten: Skolprestationer, skolstress och psykisk ohälsa bland tonåringar (från 2016)"
[6]:	https://www.intelligent.com/new-survey-finds-students-are-replacing-human-tutors-with-chatgpt/ "Intelligent: New Survey Finds Students Are Replacing Human Tutors with ChatGPT"
[7]:	https://en.wikipedia.org/wiki/Auto-GPT "Engelska Wikipedias artikel om AutoGPT"
[8]:	https://www.youtube.com/playlist?list=PL70wNv4dBdJx5Y2cPTUUk00nOxHzpp6g_ "YouTube: Teknik i akademi"
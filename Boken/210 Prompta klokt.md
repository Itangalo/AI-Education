# Prompta klokt
_Uppdaterat 2023-10-05._

_Det här kapitlet är skrivet av Johan Falk. På bokens projektsida [github.com/itangalo/AI-och-skolan][1] kan du föreslå nya kapitel och förbättringar till befintliga kapitel._

Det här kapitlet riktar sig till alla som vill använda chattbottar för lite mer komplexa uppgifter.

---- 

> Take a deep breath and work on this problem step-by-step.

Om du har ett svårt problem som du behöver lösa är meningen ovan ett bra sätt att börja. Det visar sig att samma sak gäller chattbottar – de har bättre chans att lyckas ge korrekta svar eller lösningar om du börjar instruktionen till botten med något i liknande stil.[^1]

Det kan tyckas märkligt, och kanske komiskt, men tittar man tillräckligt djupt i språkmodeller är det inte jättekonstigt. Det är en instruktion som säger åt chattbotten att inte försöka hitta ett svar direkt, utan ett bra första steg för att nå en lösning. Efter varje ord som språkmodellen lagt till anropas den igen, den här gången med frågeställningen plus det nya ordet. När språkmodellen får det ursprungliga problemet _plus_ en bra start på hur det kan lösas, så har den rätt bra chanser att gissa nya ord som blir ett bra nästa steg, och så vidare.

Exemplet med att be en chattbot ta det lugnt och tänka igenom vad den ska göra visar på en viktig princip när det gäller att skriva bra prompter till chattbottar: Det är inte är magi – det är i många lägen instruktioner som vi kan förstå och i många lägen är vettiga även för människor.

Det finns några olika tekniker eller knep för att skriva prompter som är bra att känna till. Ingen av dem är nödvändiga för att använda chattbottar, ens för komplexa uppgifter, och man kommer långt med sunt förnuft. Men de kan vara bra att ha i bakfickan om man inte riktigt får till det man är ute efter.

## Några grundläggande tips
1. Var tydlig: Det första tipset är enkelt: Försök att tänka igenom vad du egentligen är ute efter från chattbotten, och beskriv just det.
2. Förfina med nya instruktioner: En annan och ofta enklare variant är att skriva en rätt kort instruktion och sedan styra chattbotten närmare det du vill ha utifrån vad den levererar på första försöket. ”Kan du göra tonen i texten vänligare?” eller ”Jag undervisar vuxna elever, kan du justera efter det?”.
3. Be om specifika svarsformat: Du kan exempelvis be om att få svar i punktlistor, bara svar med ja/nej, eller en tabell med rubriker som du anger.

## Några mer avancerade tips
Om du inte skulle nå ändra fram med de grundläggande tipsen finns några lite mer avancerade som är välanvända. Det finns många fler tips att hitta på nätet, men det är inte tydligt att de faktiskt ger så bra effekt.

### Be chattbotten förbättra frågeställningen
En intressant strategi är att börja med att be chattbotten föreslå förbättrade instruktioner, eller att säga åt den att ställa ett antal frågor till dig innan den svarar.

### Be chattbotten agera enligt en viss roll
Att be chattbotten svara som att den var en viss typ av expert kan ge bättre kvalitet på svaret, men också språk som är mer komplicerat. Till exempel:
* "Agera som en lärare i ett lönesamtal, som är missnöjd med lönen som erbjuds."
* "Agera som en elev som tycker att matematik är svårt och tråkigt."
* "Agera som en säkerhetsexpert och ställ frågor som hjälper oss att förbättra säkerheten på vår skola."

### Steg för steg-metoden
Den metod som förmodligen har starkast belägg för att faktiskt fungera är att uttryckligen be chattbotten att tänka ut en lösningsstrategi eller skriva ut vilka steg den tar mot sin lösning, och att den ska göra det _innan_ den ger ett svar eller en lösning.

### Simulera samtal-metoden
En ganska effektiv och samtidigt rätt underhållande metod är att låta chattbotten simulera ett samtal mellan olika personer, som ska komma fram till något klokt. Var och en har viss expertis, och tillsammans bidrar de till att förfina en idé.

_Exempel från ChatGPT (GPT-4, 3 augusti)_
> **Jag:** Vår högstadieskola "Solskolan" ska hitta en slogan som vi kan använda. Utgå från de här tre personerna:
> * Alice är rektor och angelägen om att skolan ska verka seriös.
> * Bob är kommunikatör och angelägen om att skolan ska attrahera elever.
> * Cecilia är facklig företrädare och vill att skolan ska vara en plats där lärare och annan personal trivs.
> 
> Låt Bob föreslå en slogan och låt sedan alla tre personerna diskutera för att successivt förbättra förslaget tills alla är nöjda.
> **Chattbot:**
> **Bob:** "Hur om vi går med: 'Solskolan – där framtidens stjärnor lyser!' Det låter positivt och kan locka nya elever."
> **Alice:** "Det är en fin slogan, Bob, men jag skulle vilja att vi har något i det som också reflekterar skolans professionalism och engagemang för akademisk utmärkthet."
> **Cecilia:** "Och jag skulle vilja att det även känns välkomnande för lärare och andra anställda. Kanske något som signalerar samarbete eller gemenskap?"
> **Bob:** "Okej, vad sägs om: 'Solskolan – där framtidens stjärnor lyser i kunskap och gemenskap.'?"
> **Alice:** "Jag gillar tillägget med 'kunskap'. Det speglar skolans akademiska mål. Men jag undrar om vi kan få det lite kortare?"
> **Cecilia:** "Kanske 'Solskolan – kunskap och gemenskap under samma stjärna'?"
> **Bob:** "Det känns bra. Det är inbjudande för både elever och lärare, plus att det får fram vårt fokus på både kunskap och gemenskap."
> **Alice:** "Jag gillar det. Det har både det seriösa och det attraktiva inslaget vi söker."
> **Cecilia:** "Jag håller med. Det ger en känsla av en skola där alla är en del av samma team och strävar efter framgång tillsammans."
> **Sammanfattning:** "Solskolan – kunskap och gemenskap under samma stjärna."

### Skriv på engelska
Det verkar som att många språkmodeller har engelska som modersmål, och att det kräver lite ansträngning att använda andra språk, vilket kan resultera i sämre svar. I verkligheten har de inget specifikt språk, utan abstrakta representationer av ord, men när engelska är det vanligaste språket i träningsdatan (vilket är fallet för de flesta språkmodeller) är det inte konstigt om vissa kopplingar mellan begrepp fungerar bättre på engelska än på svenska. De så kallade _tokens_ – delar av ord – som språkmodeller arbetar med utgår också i stor utsträckning från engelska språket, vilket gör att instruktioner på svenska vanligtvis tar upp mer av det utrymme som språkmodellen kan hålla i minnet, även om instruktionen skulle bestå av lika många bokstäver som motsvarande instruktion på engelska.

Summan av kardemumman är att en prompt kan fungera lite bättre om den är skriven på engelska, med tillägget ”answer in Swedish” i slutet.

### Ange syfte när du sammanfattar texter
Om du ber en chattbot att sammanfatta en text är det naturligt att en del av nyanser och information försvinner. Om du anger vad du vill ha sammanfattningen till ökar du dina chanser att få ett mer användbart resultat.

> Sammanfatta texten nedan, med utgångspunkt i att jag är skolbibliotekarie och vill veta saker som är relevanta för min verksamhet.

## Några andra tips
* Vissa chattbottar har funktioner för att spara och hämta fram prompter som du använder ofta. Om det saknas kan du alltid spara i ett separat dokument och kopiera därifrån.
* Det finns många samlingar med prompter att hitta på nätet. De kan vara användbara, men ta långa och märkliga prompter med en nypa salt. Det är inte säkert att de är bättre än att bara fråga rakt upp och ner om det du är ute efter, och använda uppföljningsfrågor för att förfina när det behövs.
* Olika språkmodeller kan reagera olika på promptningsstrategier. Det betyder också att det som fungerar idag inte behöver vara en bra strategi om ett år.

[^1]:	https://arxiv.org/abs/2309.03409

[1]:	https://github.com/Itangalo/AI-och-skolan
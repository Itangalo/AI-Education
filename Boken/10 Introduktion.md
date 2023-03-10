
# Del 1: Introduktion


# 1: Vad är ChatGPT?

Till det yttre är ChatGPT ett chattfönster där man skriver meddelanden till en chatbot, som svarar. Det finns dock flera saker som gör ChatGPT speciell. Det första är att den skriver på ett mänskligt sätt – den följer konversationen, skriver vettiga saker och är dessutom allmänt trevlig. Det andra som gör ChatGPT speciell är att den har massor med kunskaper även om detaljområden: Du kan fråga om modelljärnvägens historia, vad som krävs för att odla potatis på ett effektivt sätt eller vad som utmärker schottis som dans, och ChatGPT kommer att svara på ett tydligt och förtroendeingivande sätt.

ChatGPT drivs av en så kallad AI-modell som har blivit tränad på stora delar av den text som fanns tillgänglig på internet fram till 2021. Det är mer text än en människa hinner läsa i hela sitt liv – faktiskt så mycket att det skulle kräva 57 miljarder människoåldrar att läsa igenom alltihop[^1]. Texten är utgångspunkt för de svar som ChatGPT ger, men svaren slås inte upp eller kopieras från det som AI-modellen läst. I stället har textmassan använts för att destillera fram mönster för hur text och ord brukar hänga samman. Utifrån det gör ChatGPT gissningar på vilka ord som passar bra att skriva, och samma fråga ger i regel lite olika svar om den ställs flera gånger. (Mer information om ChatGPT finns i kapitel 12.)

I den här boken finns många utdrag från konversationer med ChatGPT. De är i regel ordagrant återgivna – det du läser är hur konversationen med ChatGPT sett ut. Den fetstilade texten är frågan (”prompten”) från användaren, det övriga är svaret från AI:n. I vissa fall är dock texten lätt redigerad för att formatmässigt passa bättre i bokform, och i vissa fall har större mängder inklistrad text i frågan ersatts av en kort beskrivning inom hakparentes.

---- 

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

Att börja använda ChatGPT kan vara överväldigande eller till och med omvälvande. Oavsett om du ställer frågor om cellbiologi, August Strindberg eller buddhismens historia har den svar, som levereras sakligt och tydligt. Den kan sammanfatta texter, skriva dikter, skapa datorprogram, hitta på godnattsagor, ge återkoppling på och ge förbättringsförslag på textutkast, och utveckla sina resonemang i en konversation med en människa. I kapitel 13 kan du läsa mer om hur verktyg som ChatGPT skulle kunna påverka vår syn på kunskap, och på oss själva.

# 2: Fyra typer av AI-fällor
Något som är viktigt att lägga märke till redan nu är att ChatGPT begår misstag. Om du läste igenom konversationen ovan la du förmodligen märke till att översättningar och ordval ibland blir konstiga (exempelvis “gödselmedel” i stället för “gödsel” och “accordeonmusik” i stället för “dragspelsmusik”). Sådana misstag är betydligt ovanligare på engelska, eftersom den största delen av texten ChatGPT tränats på är på engelska.

Något som är svårare att lägga märke till är sakfelen – dels eftersom de kräver förhållandevis goda kunskaper hos läsaren, dels för att de är insvepta i en tydlig text som är lätt att tro på. Till exempel skriver ChatGPT att schottis uppstod i Skottland, medan den som läser om schottis på Wikipedia kan konstatera att den troligtvis uppstod i Böhmen. (Nationalencyklopedin å sin sida säger att schottis “presenterades” i Paris, utan att nämna var dansen uppstod.)

Ett par andra misstag – om man ska kalla dem för misstag – är ännu svårare att upptäcka. ChatGPT säger att schottis har ”snabb och livlig rytm”, medan svenska Wikipedias artikel om schottis säger att det är “lugnt tempo”. Schottis i andra delar av världen verkar i regel ha ett högre tempo än schottis i Sverige. Har ChatGPT fel som säger att det är snabb rytm? Egentligen inte. Däremot beskriver den schottis utifrån ett perspektiv som kanske inte stämmer i Sverige – det land där frågan ställdes – vilket gör svaret vilseledande. Ett annat kanske-misstag är att beskrivningen av modelljärnvägens historia inte nämner tillverkaren Märklin (men däremot några andra tillverkare), trots att Märklin både spelar en roll i modelljärnvägens historia och för många är nära nog synonymt med modelljärnväg.

Sådana kanske-misstag är inte fel, men de avspeglar en särskild del av sanningen, eller får saker att uppfattas på ett visst sätt eller ur ett visst perspektiv. De är svåra att upptäcka, särskilt för någon som inte är vaksam, och riskerar att knuffa mottagaren in i en specifik världsbild utan att vara medveten om det.

En sista typ av misstag handlar inte om vad ChatGPT svarar, utan hur användbart man förväntar sig att det är. Att ChatGPT ger dig tio välformulerade quiz-frågor om upplysningstiden behöver inte betyda att det är bra pedagogik att använda frågorna: Kanske lär sig eleverna bättre av helt andra typer av aktiviteter, eller för den delen quiz-frågor valda utifrån vad du som lärare vet är vanliga missuppfattningar eller vad som är särskilt viktigt att kunna. Mer allvarliga pedagogiska misstag vore att låta ChatGPT skapa provuppgifter eller bedöma uppsatser från elever, utan att vara _mycket_ noga med att det ChatGPT levererar stämmer med vad man vill ha (och då kan man fråga sig hur mycket hjälp man egentligen fått från verktyget).

Det är naturligt och nyttigt att utforska olika sätt att använda nya verktyg, och allt man testar behöver inte fungera bra. Men det är lätt hänt att kraftfulla verktyg överanvänds, och att utgångspunkten blir verktyget snarare än det man vill använda det till.

ChatGPT:s mångsidighet och imponerande förmåga att skapa sakliga, tydliga och korrekta budskap gör det lätt att glömma bort att det inte bara finns artificiell intelligens utan också AI-assisterade dumheter. För att göra det lättare att använda ChatGPT med omdöme listar den här boken fyra typer av AI-fällor man behöver se upp med.

* **Språkfällor**, så som stavfel och felaktiga ordval. Dessa är förhållandevis lätta att upptäcka. Största risken med språkfel är förmodligen att elever kan bli förvirrade över terminologi.
* **Faktafällor**, vilket också kan omfatta logiska misstag. Faktafel kräver ämneskunskaper för att upptäcka, inte minst för att ChatGPT formulerar sig på så förtroendeingivande sätt.
* **Perspektiv- och värderingsfällor**, där svar från AI:n kanske utgår från förhållanden i USA, befäster stereotypa könsroller eller inte tar hänsyn till vissa grupper i samhället. Att upptäcka skeva perspektiv eller värderingar kan kräva både vaksamhet och goda kunskaper.
* **Pedagogiska fällor**, som betyder att det som ChatGPT levererar används utan att reflektera över om det faktiskt leder till det lärande som man är ute efter.

De här typerna av misstag är inte unika för ChatGPT, och kan uppstå även helt utan teknikens hjälp. Och den som aldrig gått i de här fällorna har förmodligen inte undervisat alls – och det måste vara ok att göra fel. Men den som har de fyra AI-fällorna i bakhuvudet har förmodligen lättare att undvika dem.

## Olämpliga budskap

ChatGPT har spärrar för vissa typer av budskap. Om du försöker få ChatGPT att berätta hur man skapar bomber, blandar metamfetamin eller om du vill få förslag på hur man kan trakassera, misshandla eller tortera någon kommer ChatGPT svara med att det bryter mot dess policy att svara. Samma sak gäller exempelvis att ge medicinsk rådgivning (vilket förmodligen har att göra med amerikansk lagstiftning).

Att det finns sådana spärrar gör ChatGPT till ett betydligt tryggare verktyg, men spärrarna är inte hundraprocentiga. Det betyder att ChatGPT ibland kan släppa igenom saker som den borde hålla tyst om, och att envetna användare kan hitta sätt konsekvent gå runt spärrarna. (Det finns, inte helt oväntat, tips på nätet om hur spärrarna kan rundgås.)

De allra flesta tips och idéer i den här boken utgår från att det är läraren som använder ChatGPT, inte eleven. Det kan förstås ändå hända att elever använder ChatGPT, i eller utanför skolan, och det bra att känna till att det kan dyka upp olämpliga budskap.

## Övningar

1. Vilka är de fyra typerna av AI-fällor, och vad utmärker dem?
2. Kan du komma på ytterligare kategorier av AI-fällor?
3. Kolla igenom konversationen i kapitel 1 igen och fundera över var det kan finnas AI-fällor.

# 3: Så kommer du igång med ChatGPT

ChatGPT skapades och drivs av företaget OpenAI. För att använda ChatGPT behöver du ett konto på OpenAI, vilket du ordnar genom OpenAI:s webbplats (exempelvis [beta.openai.com][2]). Konto är gratis, och försöksversionen av ChatGPT är också gratis att använda. Sedan 11 februari (1 februari för USA) finns också en betalversion av tjänsten. [Användarvillkoren för OpenAI-konton][3] säger att man måste vara minst 18 år. Den e-postadress du anger behöver bekräftas genom ett mail som skickas dit, och sedan är du redo att gå till [chat.openai.com][4] och börja använda ChatGPT.

![Gränssnittet för ChatGPT, med de viktigaste elementen markerade 1–3.][image-1]

De viktigaste delarna av chattfönstret är (1) fönstret för att skriva input till ChatGPT – ofta kallat en “prompt”, (2) historik över tidigare chattar, och (3) knappen för att starta nya chattrådar. Om den valda chattråden är tom, som på bilden ovan, visas en sammanfattning av några av de viktigaste egenskaperna för ChatGPT.

När du skriver något till ChatGPT dyker konversationen upp i huvuddelen av fönstret. Svaret från ChatGPT växer fram ord för ord, och om tjänsten är tungt belastad kan det ta några sekunder innan texten dyker upp. (Vid riktigt hög belastning kan du få ett felmeddelande – i de lägena kan du ladda om sidan och försöka igen.) Chatten sparas i vänsterspalten och får automatiskt en rubrik baserat på innehållet.

![Gränssnittet för ChatGPT, så som det ser ut när en konversation är igång.][image-2]

Håller du pekaren på ditt meddelande till ChatGPT syns en ikon för att redigera frågeställningen, vilket ger ett nytt svar. Invid varje svar finns knappar som kan användas att ge återkoppling på om svaret var bra eller dåligt, vilket också ger en chans att ange vad man tycker är ett bra svar. Återkopplingen används för att förbättra hur ChatGPT fungerar.

Det finns inget inbyggt sätt att exportera text från konversationerna. Det vanliga är att antingen markera och kopiera text för hand eller ta skärmbilder, men använder du ChatGPT ofta kan du överväga att installera en plugin i din webbläsare som gör det lättare att kopiera text.

## Några tips när du chattar med ChatGPT
Att chatta med ChatGPT är på många sätt naturligt – du skriver som du skulle göra till en människa. De vanligaste sätten är förmodligen att ställa korta frågor eller att uppmana ChatGPT att skriva något särskilt, och att följa upp det med ytterligare frågor, uppmaningar eller justeringar. Några metoder och knep som kanske är mindre naturliga kan också vara bra att känna till:

* Om du trycker enter i chattrutan skickas meddelandet till ChatGPT. Med shift + enter har du möjlighet att skapa radbrytningar utan att meddelandet skickas.
* Om du vill variera eller återanvända en längre frågeställning är det praktiskt att ha prompten i en textredigerare eller ordbehandlare, där den enklare kan redigeras och kopieras.
* Om du vill ge långa texter till ChatGPT kan du till exempel skriva “Vilken är den mest svårlästa delen av den här texten?” och klistra in texten innan du skickar meddelandet, eller “Nedanför är en text jag skrivit som jag vill att du ger feedback på så att jag kan förbättra den.”
* Om du ger ChatGPT en text utan någon speciell uppmaning eller fråga kommer den att svara med en sammanfattning av texten.
* ChatGPT är i regel snabbare på att svara om man skriver på engelska, och meddelandena innehåller också färre språkfel.
* Utförliga beskrivningar och frågeställningar ger ofta mer användbara svar.
* Uppföljningsfrågor är också mycket användbara för att precisera vad man vill få ut av svaren, eller be ChatGPT utveckla delar av svar som är intressanta.
* En del experimenterar med långa beskrivningar av hur man vill att ChatGPT ska bete sig. Sådana beskrivningar avslutas ofta med något i stil med “bekräfta att detta är uppfattat genom att svara ‘ok’”, och de egentliga frågeställningarna eller uppmaningarna postas i nästa steg i konversationen.
* Om du vill ha svar i något särskilt format, så som punktlista, tabell, eller en kommaseparerad lista – be ChatGPT svara i den formen. ChatGPT kan ibland också svara i format som går att importera direkt till vissa program. Du kan också be ChatGPT skriva om svar som den redan lämnat till en ny form.
* Om du upplever att ChatGPT är långsamt eller begränsande kan du testa att växla till OpenAI Playground på [beta.openai.com/playground][5]. Där kan du använda ett mer flexibelt (men också mer komplext) gränssnitt för att generera AI-texter.

Det är bra att känna till att det finns en gräns för hur långa meddelandena till ChatGPT får vara, på knappt två tusen ord eller 7–10 sidor[^2]. Om du vill ge ChatGPT längre texter än så kan du testa att dela upp texten, och exempelvis ge ChatGPT instruktionen “Jag kommer att ge dig en lång text uppdelad i flera delar. Här kommer del 1. Svara ‘ok’ när du är klar.”

ChatGPT lägger som mest en och en halv minut på att ge svar, vilket gör att långa svar kan brytas mitt i. I sådana lägen kan du exempelvis skriva “Kan du fortsätta på förra svaret och avsluta det?” eller bara ”fortsätt”, eller ändra frågan så att ChatGPT kan svara på mindre delar i taget.

På nätet finns samlingar med prompter som folk funnit särskilt användbara. Det kan till exempel vara prompter noga utformade för ett visst ändamål (så som att fungera som kokbok eller författare av soloäventyr) eller grupper av prompter som är användbara inom särskilda områden (så som assistent för programmerare). Om du vill utforska sådana samlingar kan du testa att söka på “ChatGPT prompts”.

## Övningar

1. Om du inte redan har ett konto hos OpenAI, skapa ett – förutsatt att du går med på deras användarvilkor.
2. Testa att ställa frågor till ChatGPT eller be ChatGPT skapa vissa typer av texter. Ha minst tre konversationer, där du ställer uppföljningsfrågor i minst en. Minst en av chattarna ska handla om skola eller undervisning. Testa att skriva både på svenska och engelska.

[^1]:	BBC Tech Tent, 2022-12-09: [https://www.bbc.co.uk/programmes/w3ct4khv][1]

[^2]:	[https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them][6]

[1]:	https://www.bbc.co.uk/programmes/w3ct4khv
[2]:	https://beta.openai.com/
[3]:	https://openai.com/terms/
[4]:	https://chat.openai.com/
[5]:	https://beta.openai.com/playground
[6]:	https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them

[image-1]:	https://user-images.githubusercontent.com/262940/212463937-050069cb-ad3a-4e64-a212-a266b4d973b1.png
[image-2]:	https://user-images.githubusercontent.com/262940/212463940-7cf40758-8d33-4520-8b8e-8b3cd80134c7.png
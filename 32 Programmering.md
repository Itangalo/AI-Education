## 9: Programmering
ChatGPT är, på gott och ont, rätt bra på att både förstå och skriva datorprogram. Om din undervisning omfattar programmering finns det därför extra stöd att få från AI:n.

En fördel med just programmeringshjälp är att vissa av fallgroparna man kan råka ut för inte blir lika allvarliga. När ChatGPT ger felaktiga tips på kodsnuttar kommer det att märkas mer eller mindre direkt, och frågor som rör perspektiv och värderingar spelar en klart mindre roll så länge man håller sig till enbart programmeringsfrågor (om man inte räknar med olika paradigm inom programmering, vill säga).

ChatGPT är olika skicklig på att förstå och skapa kod på olika språk. En rimlig utgångspunkt är att ju vanligare programspråket är, desto bättre är ChatGPT på språket.

På nätet finns många exempel på hur ChatGPT kan användas för programmering. I den här boken finns några urval, men mer hängivna programmerare kan till exempel också använda ChatGPT för att skriva tester, skapa trovärdigt dummy-innehåll, skapa sub-kod för hela applikationer eller få förslag på arkitektur.

Det kan också nämnas att ChatGPT matar ut kodblock med färger som markerar satser och funktioner, medan det inte finns några färger i den här boken.

### Skapa enkla datorprogram
ChatGPT kan skapa färdiga små program, ofta med förvånansvärt välkommenterad kod och hög flexibilitet.

> **Kan du skriva ett Python-program som testar sannolikheten att minst två personer i en grupp på 26 personer har samma födelsedag? Använd Monte Carlo-metoden.**
>  
> Ja, det går att skriva ett Python-program som använder Monte Carlo-metoden för att testa sannolikheten att minst två personer i en grupp på 26 personer har samma födelsedag. Nedan finns en lösning på detta problem: 
> 	import random
> 	
> 	def test_birthdays(num_people, num_samples):
> 	  num_matches = 0
> 	  for i in range(num_samples):
> 	    birthdays = []
> 	    for j in range(num_people):
> 	      birthday = random.randint(1, 365)
> 	      birthdays.append(birthday)
> 	    if(len(set(birthdays)) != len(birthdays):
> 	      num_matches += 1
> 	  probability = num_matches / num_samples
> 	  return probability
> 	
> 	num_people = 26
> 	num_samples = 10000
> 	probability = test_birthdays(num_people, num_samples)
> 	print(f"Probability that at least two people in a group of {num_people} have the same birthday: {probability:.2f}")
> Detta program använder en slumptalsgenerator för att skapa födelsedagar för personerna i gruppen, och räknar sedan antalet gånger då minst två personer har samma födelsedag. Sannolikheten för att detta ska hända räknas ut genom att dividera antalet träffar med antalet testade grupper.
> Observera att resultatet kan variera beroende på hur många testgrupper som används, så det kan vara bra att öka antalet testgrupper för att få ett mer exakt resultat.

### Felsöka datorprogram
ChatGPT är också förvånansvärt bra på att hitta och åtgärda buggar i kod, vilket kan vara användbart både för läres och elevers kod.

> **Kan du hitta vad som inte fungerar i den här koden?**
> 	for (var i = 0; i < 5; i++) {
> 	  setTimeout(() => console.log(i), 1000)
> 	}
> Det ser ut som att koden försöker skriva ut värdet på variabeln i med en fördröjning på 1 sekund för varje iteration i loopen. Det som inte fungerar som förväntat är att alla loggar skrivs ut med värdet 5.
> Det beror på att setTimeout är en asynkron funktion, vilket innebär att den kommer att köras i bakgrunden samtidigt som resten av koden fortsätter att köras. När loopen har kört klart och setTimeout-funktionerna börjar skriva ut värdena på i, har i redan ökat till värdet 5 och alla loggar skrivs ut med detta värde.
> För att lösa det här problemet kan du använda en annan teknik som kallas "skapandet av en ny förhandsgranskning" eller "skapandet av en klosure". Detta görs genom att skapa en ny funktion inuti loopen som har sin egen kopia av variabeln i. På så sätt kan du skicka med det aktuella värdet på i till setTimeout-funktionen:
> 	for (var i = 0; i < 5; i++) {
> 	  (function(i) {
> 	    setTimeout(() => console.log(i), 1000)
> 	  })(i)
> 	}
> Ett annat alternativ är att använda ES6-syntax och let-nyckelordet istället för var. let definierar en lokal variabel i den aktuella block-scopen, medan var definierar en global eller lokal variabel på funktion-scopet. Detta innebär att du kan använda let för att skapa en ny förhandsgranskning för varje iteration i loopen:
> 	for (let i = 0; i < 5; i++) {
> 	  setTimeout(() => console.log(i), 1000)
> 	}
> Med dessa ändringar bör du få ut den förväntade utskriften med en logg för varje iteration i loopen med rätt värde på i.

### Skapa kod för specifika uppgifter
För de som inte bara har programmering som en del ämnet, utan ämnet handlar om programmering, kan ChatGPT användas för att skapa kodsnuttar för en rad olika områden.

> ** Kan du skriva ett Python-program som slår upp en Wikipedia-artikel som användaren anger, och berättar hur många ord som finns på sidan?**
> Ja, jag kan skriva ett Python-program för att slå upp en Wikipedia-artikel och berätta hur många ord som finns på sidan. Här är ett exempel:
> 	import requests
> 	from bs4 import BeautifulSoup
> 	
> 	def count_words_on_wikipedia_page(page_name):
> 	    url = f'https://en.wikipedia.org/wiki/{page_name}'
> 	    page = requests.get(url)
> 	    soup = BeautifulSoup(page.content, 'html.parser')
> 	    text = soup.get_text()
> 	    words = text.split()
> 	    return len(words)
> 	
> 	page_name = input("Enter a Wikipedia page name:")
> 	word_count = count_words_on_wikipedia_page(page_name)
> 	print(f'The number of words on the page is {word_count}')
> Notera att detta program bara fungerar för engelska Wikipedia-sidor. För att använda det på en annan språkversion av Wikipedia, ändra URL-adressen i rad 8 till den lämpliga språkversionen.
### Hitta undantag som du missat i koden
Att skapa välkommenterad kod gör det lättare att läsa den, både för lärare och elever.

> **Kan du hitta edge cases i koden nedan, som kan få den att sluta fungera?**
	import requests
	from bs4 import BeautifulSoup
	
	def count_words_on_wikipedia_page(page_name):
	    url = f'https://en.wikipedia.org/wiki/{page_name}'
	    page = requests.get(url)
	    soup = BeautifulSoup(page.content, 'html.parser')
	    text = soup.get_text()
	    words = text.split()
	    return len(words)
	
	page_name = input("Enter a Wikipedia page name:")
	word_count = count_words_on_wikipedia_page(page_name)
	print(f'The number of words on the page is {word_count}')
> Här är några potentiella edge cases som kan få koden att sluta fungera:
> * Om Wikipedia-sidan inte finns, kan koden kasta ett undantag när den försöker hämta sidan med hjälp av requests.get(url).
> * Om Wikipedia-sidan innehåller icke-engelska tecken, kan detta orsaka problem med text.split() eftersom det förväntar sig engelska ord.
> * Om Wikipedia-sidan inte är i HTML-format, kan detta orsaka problem med BeautifulSoup, eftersom det förväntar sig HTML.
> * Om internetanslutningen är nere, kan koden kasta ett undantag när den försöker hämta sidan med hjälp av requests.get(url).
> * Om Wikipedia-sidan är stor, kan detta orsaka problem med minnet, eftersom all text hämtas och sparas i minnet innan den räknar antalet ord.
### Kommentera kod
> **Kan du kommendera koden nedan så att den blir lättare att läsa? Kommendera på svenska, är du snäll.**
> 	import requests
> 	from bs4 import BeautifulSoup
> 	
> 	def count_words_on_wikipedia_page(page_name):
> 	    url = f'https://en.wikipedia.org/wiki/{page_name}'
> 	    page = requests.get(url)
> 	    soup = BeautifulSoup(page.content, 'html.parser')
> 	    text = soup.get_text()
> 	    words = text.split()
> 	    return len(words)
> 	
> 	page_name = input("Enter a Wikipedia page name:")
> 	word_count = count_words_on_wikipedia_page(page_name)
> 	print(f'The number of words on the page is {word_count}')
> Koden använder sig av biblioteken requests och BeautifulSoup för att hämta innehållet från en Wikipedia-sida och räkna antalet ord på sidan.
> Följande förbättringar kan göras för att göra koden lättare att läsa och förstå:
> * Lägg till kommentarer för att förklara vad varje del av koden gör.
> * Använd mer beskrivande variabelnamn, till exempel `wikipedia_url` istället för `url` och `wikipedia_page_content` istället för `page`.
> * Indentera koden på ett logiskt sätt, till exempel så att all kod som hör till en funktion är indentera på samma nivå.
> * Dela upp koden i flera mindre funktioner för att göra den mer lättöverskådlig och lättare att testa.
> Exempel på kommenterad och förbättrad kod:
> 	import requests
> 	from bs4 import BeautifulSoup
> 	
> 	def count_words_on_wikipedia_page(page_name):
> 	    # Skapa en url för Wikipedia-sidan med det angivna sidnamnet
> 	    wikipedia_url = f'https://en.wikipedia.org/wiki/{page_name}'
> 	
> 	    # Hämta innehållet från Wikipedia-sidan
> 	    wikipedia_page_content = requests.get(wikipedia_url)
> 	
> 	    # Skapa en BeautifulSoup-objekt av innehållet för att enklare kunna hämta ut texten
> 	    soup = BeautifulSoup(wikipedia_page_content.content, 'html.parser')
> 	
> 	    # Hämta all text från sidan
> 	    text = soup.get_text()
> 	
> 	    # Dela upp texten i ord och räkna antalet ord
> 	    words = text.split()
> 	    word_count = len(words)
> 	
> 	    return word_count
> 	
> 	# Fråga användaren efter ett sidnamn på Wikipedia
> 	page_name = input("Enter a Wikipedia page name:")
> 	
> 	# Räkna antalet ord på den angivna sidan och skriv ut resultatet
> 	word_count = count_words_on_wikipedia_page(page_name)
> 	print(f'The number of words on the page is {word_count}')

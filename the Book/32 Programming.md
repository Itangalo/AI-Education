# 9: Programming
ChatGPT is, for better or for worse, pretty good at both understanding and writing computer programs. If your education includes programming, there is therefore extra support to get from AI.

An advantage of just programming help is that some of the AI traps you can fall into are not as serious. When ChatGPT provides incorrect tips on code snippets, it will be noticed more or less immediately, and questions about perspective and values play a much smaller role as long as you stick to programming questions only (unless you count different paradigms in programming, that is).

ChatGPT is different in their skill level of understanding and creating code in different languages. A reasonable starting point is that the more common the programming language is, the better ChatGPT is at the language.

The internet has many examples of how ChatGPT can be used for programming. In this book, there are some selections, but more dedicated programmers can, for example, use ChatGPT to write tests, create credible dummy content, create sub-code for entire applications, or get suggestions for architecture.

It can also be mentioned that ChatGPT outputs code blocks with colors that mark sentences and functions, while there are no colors in this book.

## Create Simple Computer Programs
ChatGPT can create ready-made small programs, often with surprisingly well-commented code and high flexibility.

**When you read the conversation, consider:**
* Would you benefit from AI-created simple computer programs in your teaching? How?
* What opportunities and risks exist for students to ask ChatGPT for simple computer programs themselves?

> **Can you write a Python program that tests the likelihood that at least two people in a group of 26 people have the same birthday? Use the Monte Carlo method.**
>  
> Yes, it is possible to write a Python program that uses the Monte Carlo method to test the likelihood that at least two people in a group of 26 people have the same birthday. Below is a solution to this problem: 
> 	import random
> 	
> 	def test_birthdays(num_people, num_samples):
> 	  num_matches = 0
> 	  for i in range(num_samples):
> 	    birthdays = []
> 	    for j in range(num_people):
> 	      birthday = random.randint(1, 365)
> 	      birthdays.append(birthday)
> 	    if(len(set(birthdays)) != len(birthdays)):
> 	      num_matches += 1
> 	  probability = num_matches / num_samples
> 	  return probability
> 	
> 	num_people = 26
> 	num_samples = 10000
> 	probability = test_birthdays(num_people, num_samples)
> 	print(f"Probability that at least two people in a group of {num_people} have the same birthday: {probability:.2f}")
> This program uses a random number generator to create birthdays for the people in the group, and then counts the number of times at least two people have the same birthday. The probability of this happening is calculated by dividing the number of matches by the number of tested groups.
> Note that the result may vary depending on the number of test groups used, so it may be good to increase the number of test groups to get a more accurate result.

## Debugging Computer Programs
ChatGPT is also surprisingly good at finding and fixing bugs in code, which can be useful for both teachers and students' code.

**When reading the conversation, think about:**
* Does the response from ChatGPT seem clear?
* If you have any programming in your teaching: What does it mean for you or your students to get AI assistance with finding, understanding, and fixing bugs?

> **Can you find what's not working in this code?**
> 	for (var i = 0; i < 5; i++) {
> 	  setTimeout(() => console.log(i), 1000)
> 	}
> It appears that the code is trying to print the value of the variable `i` with a delay of 1 second for each iteration in the loop. What's not working as expected is that all logs are written with the value 5.
> This is because `setTimeout` is an asynchronous function, which means it will run in the background while the rest of the code continues to run. By the time the loop has finished running and the `setTimeout` functions start printing the values of `i`, `i` has already increased to the value 5 and all logs are written with this value.
> To solve this issue, you can use another technique called "creating a new closure" or "wrapping in a closure." This is done by creating a new function within the loop that has its own copy of the variable `i`. In this way, you can pass the current value of `i` to the `setTimeout` function:
> 	for (var i = 0; i < 5; i++) {
> 	  (function(i) {
> 	    setTimeout(() => console.log(i), 1000)
> 	  })(i)
> 	}
> Another option is to use the ES6 syntax and the `let` keyword instead of `var`. `let` defines a local variable in the current block scope, while `var` defines a global or local variable on the function scope. This means you can use `let` to create a new closure for each iteration in the loop:
> 	for (let i = 0; i < 5; i++) {
> 	  setTimeout(() => console.log(i), 1000)
> 	}
> With these changes, you should get the expected output with one log for each iteration in the loop with the correct value of `i`.

## Create code for specific tasks
For those who not just have programming as a part of the subject, but the subject is about programming, ChatGPT can be used to create code snippets for a range of different areas.

**When reading the conversation, consider:**
* If you teach programming: What are the pros and cons of asking ChatGPT for code examples and solutions, compared to searching the internet or writing the code from scratch? What are the pedagogical consequences?

> ** Can you write a Python program that looks up a Wikipedia article that the user specifies, and tells how many words are on the page?**
> Yes, I can write a Python program to look up a Wikipedia article and tell how many words are on the page. Here is an example:
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
> Note that this program only works for English Wikipedia pages. To use it on another language version of Wikipedia, change the URL address in line 8 to the appropriate language version.

## Find exceptions you missed in the code
ChatGPT can analyze code and in many cases find different ways that the program can break.

**When reading the conversation, think about:**
* If you teach programming: How do you view the educational value in having ChatGPT find exceptions compared to you or the students doing it by hand? What are the educational consequences? What are the long-term consequences?

> **Can you find edge cases in the code below that could cause it to stop working?**
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
> Here are some potential edge cases that could cause the code to stop working:
> * If the Wikipedia page does not exist, the code may throw an exception when it tries to retrieve the page using requests.get(url).
> * If the Wikipedia page contains non-English characters, this may cause problems with text.split() as it expects English words.
> * If the Wikipedia page is not in HTML format, this may cause problems with BeautifulSoup, as it expects HTML.
> * If the internet connection is down, the code may throw an exception when it tries to retrieve the page using requests.get(url).
> * If the Wikipedia page is large, this may cause memory problems as all text is retrieved and stored in memory before counting the number of words.

## Commenting Code
Creating well-commented code makes it easier to read, both for teachers and students.

**When reading the conversation, think about:**
* Are the comments that ChatGPT suggests correct? Are they meaningful?
* If you teach programming: What are the advantages and disadvantages of having ChatGPT write comments, compared to searching the web or writing code from scratch? What are the educational consequences?

> **Can you comment the code below so that it becomes easier to read? Please comment in Swedish.**
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
>
> > The code uses the libraries `requests` and `BeautifulSoup` to retrieve the content of a Wikipedia page and count the number of words on the page.
> The following improvements can be made to make the code easier to read and understand:
> * Add comments to explain what each part of the code does.
> * Use more descriptive variable names, for example `wikipedia_url` instead of `url` and `wikipedia_page_content` instead of `page`.
> * Indent the code in a logical way, so that all code belonging to a function is indented at the same level.
> * Divide the code into several smaller functions to make it more easily understandable and easier to test.
> 
> Example of commented and improved code:
> 	import requests
> 	from bs4 import BeautifulSoup
> 	
> 	def count_words_on_wikipedia_page(page_name):
> 	    # Create a URL for the Wikipedia page with the specified page name
> 	    wikipedia_url = f'https://en.wikipedia.org/wiki/{page_name}'
> 	
> 	    # Retrieve the content of the Wikipedia page
> 	    wikipedia_page_content = requests.get(wikipedia_url)
> 	
> 	    # Create a BeautifulSoup object of the content to easily extract the text
> 	    soup = BeautifulSoup(wikipedia_page_content.content, 'html.parser')
> 	
> 	    # Retrieve all the text from the page
> 	    text = soup.get_text()
> 	
> 	    # Split the text into words and count the number of words
> 	    words = text.split()
> 	    word_count = len(words)
> 	
> 	    return word_count
> 	
> 	# Ask the user for a Wikipedia page name
> 	page_name = input("Enter a Wikipedia page name:")
> 	
> 	# Count the number of words on the specified page and print the result
> 	word_count = count_words_on_wikipedia_page(page_name)
> 	print(f'The number of words on the page is {word_count}')

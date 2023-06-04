# 9: Programming
ChatGPT is, for better or for worse, pretty good at both understanding and writing computer programs. If your teaching involves programming, AI can offer extra support.

An advantage of getting ChatGPT assistance in programming is that some of the AI pitfalls you can fall into become less serious. When ChatGPT provides incorrect tips on code snippets, it will be noticed more or less immediately, and questions about perspective and values play a much smaller role as long as you stick to programming questions only (unless you start discussing different paradigms in programming).

Some programming languages works better than others when asking ChatGPT to explain or create code. A reasonable starting point is that the more common the programming language is, the better ChatGPT is at the language.

The internet has many examples of how ChatGPT can be used for programming. In this book contains a few selected examples. More experienced programmers could, for example, use ChatGPT to write tests, create credible dummy content, create stub code for entire applications, or get suggestions for architecture.

ChatGPT outputs code blocks with syntax highlighting, while there are no colors in this book.

## Create Simple Computer Programs
ChatGPT can create ready-to-use small programs, often with surprisingly well-commented code and high flexibility.

**When you read the conversation, consider:**
* Would your teaching benefit from simple AI-created computer programs? How?
* What are the opportunities and risks for students to request simple computer programs from ChatGPT?

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

> **Why doesn’t this code work?**
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

## Create Code for Specific Tasks
If programming isn’t just a part of your subjects, but you actually teach programming as a subject of its own, ChatGPT can be used to create code snippets for a range of different areas.

**When reading the conversation, consider:**
* If you teach programming: What are the pros and cons of asking ChatGPT for code examples and solutions, compared to searching the internet or writing the code from scratch? What are the pedagogical consequences?

> **Can you write a Python program that looks up a Wikipedia article that the user specifies, and tells how many words are on the page?**
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

## Find Exceptions You Missed in the Code
ChatGPT can analyze code and in many cases find different ways that the program can break.

**When reading the conversation, think about:**
* If you teach programming: How do you view the educational value in having ChatGPT find exceptions compared to you or the students doing it by hand? What are the educational consequences? What are the long-term consequences?

> **Can you find edge cases in the code below that could cause it to malfunction?**
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
> Here are some potential edge cases that could cause the code to malfunction:
> * If the Wikipedia page does not exist, the code may throw an exception when it tries to retrieve the page using requests.get(url).
> * If the Wikipedia page contains non-English characters, this may cause problems with text.split() as it expects English words.
> * If the Wikipedia page is not in HTML format, this may cause problems with BeautifulSoup, as it expects HTML.
> * If the internet connection is down, the code may throw an exception when it tries to retrieve the page using requests.get(url).
> * If the Wikipedia page is large, this may cause memory problems as all text is retrieved and stored in memory before counting the number of words.

## Commenting Code
Creating well-commented code makes it easier to read, both for teachers and students.

**When reading the conversation, consider:**
* Are the comments that ChatGPT suggests correct? Are they meaningful?
* If you teach programming: What are the advantages and disadvantages of having ChatGPT write comments, compared to students writing comments themselves? What are the educational consequences?

> **Can you comment the code below so that it becomes easier to read?**
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
> The code counts the number of words on a Wikipedia page. It uses the requests library to get the HTML content of the page, the BeautifulSoup library to parse the HTML, and extract all the text content of the page. The text is then split into words using the split() method and the number of words is returned using len(). The user is prompted to enter a Wikipedia page name, and the result is printed to the console.
> Here's the commented code:
	> # Import the requests library for making HTTP requests
	import requests
	
	# Import the BeautifulSoup library for parsing HTML
	from bs4 import BeautifulSoup
	
	# Define a function to count the words on a Wikipedia page
	def count_words_on_wikipedia_page(page_name):
	  # Create the URL for the Wikipedia page by combining the base URL and the page name
	  url = f'https://en.wikipedia.org/wiki/{page_name}'
	
	  # Make an HTTP GET request to the URL and store the response in a variable
	  page = requests.get(url)
	
	  # Create a BeautifulSoup object to parse the HTML content of the page
	  soup = BeautifulSoup(page.content, 'html.parser')
	
	  # Extract all the text content of the page
	  text = soup.get_text()
	
	  # Split the text into words using the split() method
	  words = text.split()
	
	  # Return the number of words
	  return len(words)
	
	# Prompt the user to enter a Wikipedia page name
	page_name = input("Enter a Wikipedia page name:")
	
	# Call the count_words_on_wikipedia_page() function and store the result in a variable
	word_count = count_words_on_wikipedia_page(page_name)
	
	# Print the result
	print(f'The number of words on the page is {word_count}')


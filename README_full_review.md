This repository is a collection of Python projects that range from very easy to medium difficulty. This file consists of 10 different projects, which I have listed below:

Project 1: Amazon Web Scraper

In this project I decided to build an Amazon Web Scraper using BeautifulSoup from the bs4 module.  
I first had to decide what Amazon page I wanted to scrape, and once I did that, I created a dictionary with the headers of the information I wanted to scrape as this will store the information once it is successfully scraper. After doing this, it was time to functions for my code.  This equated to me creating 3 functions that served as the basis for my project.  The first function created a timestamp to calculate the exact date and time the page was scraped. Another function was created to extract the relevant information from the page, and store this information in a dictionary. The final function was created to “pretty print” the dictionary. Ultimately, I rounded off my code by using abstraction to merge these three functions under one function, and call this function for my code to run. 

Python libraries used: bs4, requests

Project 2: Binary 
Code from: FreeCodeCamp

For this project, I decided to create a Python script that prove that a binary search is faster than a naïve search.  A binary search algorithm is a divide and conquer algorithm which helps you search an ordered list and find the position of a target value within a sorted array. A naïve search is a method where we iterate through each item of the list and ask if it is equal to the value target. In both cases, if the value is equal to the targeted value, the index is returned. 

Python libraries used: time

Project 3: BMI Calculator

For this project I decided to create a simple BMI calculator. 
The user is required to enter their weight in kilograms, and their heights in centimetres. My Python code then calculates the users BMI to one decimal place using the following formula:
BMI = weight ÷ ((height÷100) ** 2)
My script then assigns the user into a category, based on their BMI, to ascertain what weight category they are in and the resulting health implications.

Python libraries used: N/A

Project 4: Choose Your Adventure 

For this project, I decided to create a Python script based of the classic “Choose Your Own Adventure” gamebooks. For this project, the user takes the role of the protagonist and is required to make choices that determine the main characters actions and the plots outcome

Python libraries used: N/A

Project 5: Fibonacci Generator

For this project, I used Object Orientated Programming (OOP) to create a script that asks the user how many terms they want to return from the Fibonacci sequence, and then asks the user to type a desired number to check if it is in the Fibonacci sequence they generated.
As is the case with OOP, I first had to create a class for my sequence and initialised the first two terms in the sequence (0 and 1). I then created my first function that asks the user how many terms they want in their Fibonacci sequence. If the user chose one, it would return the first term in 0 and exit the script. Likewise, if the user chose 2, the code would return 0 and 1, whilst also exiting the code. However, if the user chose 3 or more, the function would save the desired number of terms. The next function then uses the desired number of terms and creates the Fibonacci sequence with these many terms. The succeeding function then asks the user for the number they want to check is in the sequence, and checks if the number is in that sequence, returning the index if it is. 

Python libraries used: num2words

Project 6: General Knowledge Quiz

For this project, I created a mini general knowledge quiz. The user has to answer 15 questions, with a bonus question at the end. If the user answers a question correctly, a score is added to their total, and at the end of the quiz, their total score is printed, as well as the percentage.

Python libraries used: N/A

Project 7: Generate a QR Code

Project 8: Number Guessing Game

Project 9: SImple Calculator

Project 10:




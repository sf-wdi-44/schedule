# Week 2: JavaScript on the Web

## Thurs, March 22
- IMPORTANT: Complete HTML Forms Lab (*Submit GitHub link in Project Submission Doc*)
- Read through the Giphy project solution and be able to explain each line
- BONUS: Finish the Giphy project bonus feature ("Add More" gifs to the page)

## Wed, March 21
- IMPORTANT: Continue reviewing JS Iterators Lab and Functions Training homework from Monday
- IMPORTANT: Review Tic-Tac-Toe solution (in Slack channel)
- Continue working on your Racing Game and be ready to demo it during our Science Fair tomorrow (*Submit Github link in Project Submission Doc*

## Tues, March 20
- IMPORTANT: Finish and submit your JS Iterators Lab and Functions Training homework from last night (*Submit in Project Submission Doc, if you haven't already*)
- Finish the DOM Events Lab
- Finish the basic requirements for [Tic Tac Toe](https://github.com/SF-WDI-LABS/tic-tac-toe/blob/master/README.md)
- BONUS: Go on to the challenges / bonuses for [Tic Tac Toe](https://github.com/SF-WDI-LABS/tic-tac-toe/blob/master/README.md)

## Mon, March 19
- Complete Functions Training lab – *Submit your Functions Training in Project Submission Doc, under Functions Training, II*
- Complete JS Iterators lab – *Submit your JS Iterators Lab REPL link in Project Submission Doc*
- Sign up for a One-on-One with either Esther or Faisal this week to go over your Personal Portfolio (*One-on-One timeslots can be found in Project Submission Doc*)

# Week 1: Welcome to WDI!

## Fri, March 16
- Do <a href="https://github.com/SF-WDI-LABS/jquery-playground-lab">jQuery Playground</a>
- Revisit all the JavaScript function exercises from yesterday (try to do them from start to finish without looking at solutions)
- Continue working on Personal Portfolio 
  - Add Bootstrap for easy styling
  - Review examples [here](https://jkwr.github.io/), [here](https://conmart.github.io/), and [here](https://supertrunkes.github.io/)
- Practice `removeVowels()` function we covered for Final Jeopardy
  - e.g. `removeVowels('caterpillar') // => 'ctrpllr'` 
- JQUERY BONUS: <a href="https://github.com/SF-WDI-LABS/json-to-html-with-mr-fox">Fantastic Mr. Fox</a>

## Thurs, March 15
- Finish Kyrel (Part III)
- Use [repl.it](https://repl.it/languages/javascript) as a sandbox to write the functions below – *Submit your repl.it URL in Project Submission Doc*
	- `countZeros` – counts how many 0s there are in an array
		- ex: `countZeros([0, 2, 0, 6, 4, 0]) // => 3`
	- `addUpTo` – adds all numbers up to a given max number
	    - ex. `addUpTo(5) // => 15 (bc 1 + 2 + 3 + 4 + 5 = 15`
	    - Hint: define a `var currentSum = 0;` variable in the beginning, and keep adding to it as you loop through all the numbers in the array
	- `getPersonSentence` – formats an object (with `name`, `age`, and `city` keys) into a sentence
	    - ex. `getPersonSentence({name: ’Sam’, age: 28, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`
	- `getNames` – takes in an array of objects (with `name` and `age` keys), and prints out each object’s name
	    - ex: `getNames([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => [‘Sam’, ‘Charlotte’, ‘Dany’]`
	- `getDifference` – takes in an array of numbers and returns a sentence with the highest number, lowest number, and the difference between them
	    - ex: `getDifference([5, 2, 3, 8, 1]) // => 'The highest number is 8. The lowest number is 1. The difference is 7'`
	    
	- `countVowels` – counts how many vowels there are in an array
		- ex: `countVowels(['a', 'b', 'u', 'c', 'g', 'o']) // => 3`
		- Hint: declare a `var vowels = [‘a’, ‘e’, ‘i', ‘o’, ‘u’]` variable
		- Hint: use JavaScript’s `.indexOf()` function to test if a letter is in that `vowels` array (look up how `.indexOf()` works, if you are not sure!)
	- `getPersonSentence_v2` – formats an object (with `name`, `yearOfBirth`, and `city` keys) into a sentence
	    - ex. `getPersonSentence_v2({name: ’Sam’, yearOfBirth: 1990, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`
	- `getLongestName` – takes in an array of objects (with `name` and `age` keys), and prints out the longest name
	    - ex: `getLongestName([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => ‘Charlotte’`
	    - Hint: Use the previously written `getNames()` function to help you

## Wed, March 14
- Continue working on Personal Portfolio
  - Spend most of your time styling
  - Make sure you are hitting all [requirements](https://github.com/sf-wdi-44/personal-portfolio#deliverables)
  - Some helpful examples of portfolio pages [here](https://jkwr.github.io/), [here](https://conmart.github.io/), and [here](https://supertrunkes.github.io/)
- Finish Kyrel, Part II
- Finish JS Basics Problem Set
- *BONUS:* Finish JS Objects training lab
- *BONUS:* 
  - Write a function called `fizzbuzz` that takes in an array of numbers as an argument and 
    - returns the word 'fizz' for each number in the array that is divisible by 3
    - returns the word 'buzz' for each number in the array that is divisible by 5
    - returns the word 'fizzbuzz' for each number in the array that is divisible by both 3 and 5
  - Write a function called `calculator` that takes in 2 numbers and a mathematical operation as a string (i.e. 'add', 'subtract', 'multiply', or 'divide') and
    - returns the sum of the 2 numbers if the operation is 'add'
    - returns the difference if the operation is 'subtract'
    - returns the product if the operation is 'multiply'
    - returns the quotient if the operation is 'divide'

## Tues, March 13
- Finish Training: JavaScript Data Types
- Finish JS Control Flow training lab – *Submit the Github URL for your JS Control Flow lab in Project Submission Doc*
- Finish Personal Portfolio (Part I) project – *Submit the Github URL for your Personal Portfolio project in Project Submission Doc* (you will be having a feedback session with an instructor on your progress this Friday)
- *BONUS:* Write some code that has 2 variables: `let dividend = 21;` and `let divider = 4;`. Your code should divide the `dividend` by the `divider` and `console.log` a sentence that looks like this: `21 divided by 4 equals 5, with a remainder of 1!`. (Think of the modulus in JavaScript!)

## Mon, March 12
- Complete Site Recreation lab
- Review [Memory Game Solution](https://github.com/falqas/memory-game/tree/master/memory_game) and come with specific questions for tomorrow morning's review
- *Schedule your 2 One-on-Ones in Project Submission Doc*
- *Fill out Github usernames in Project Submission Doc*

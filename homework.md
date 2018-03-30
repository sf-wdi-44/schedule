# Week 3: Full-Stack JavaScript

## Fri, March 30
- Finish Tunely Project (Sprints 0 ~ 6) and review, review, review! This lab is a great reference for your Personal API and future Node projects
- Finish Personal API and get ready to present on it Monday morning. You must have:
	- GET route for '/api/profile'
	- GET route for 'api/whateverYourModelIs'
	- POST route for 'api/whateverYourModelIs' 
	- (don't worry about the '/api' endpoint in the directions)
	- Heroku link from which to present 
- RECOMMENDED BONUS: Code last night's function exercises again from scratch to practice

## Thurs, March 29
- Finish Sprint 0 ~ Sprint 1 of the Tunely Project
- Code the following functions in a REPL *Submit REPL link in Project Submission Doc, under Whiteboarding Practice I*
	- Function called `namesWithFiveOrMoreChars` that takes in an array of objects like `[{name: 'Tina'}, {name: 'Christine'}, {name: 'Terry'}]` and outputs just the objects with names over 5 characters like `[{name: 'Christine'}, {name: 'Terry'}]` (think of `.filter()`!)
	- Function called `nameLengths` that takes in an array of objects like `[{name: 'Tina'}, {name: 'Christine'}, {name: 'Terry'}]` and outputs an array of name lengths like `[4, 9, 5]` (think of `.map()`!)
	- Function called `getMostFrequentLetter` that takes in a word and finds the most frequently used letter – don't worry about ties (hmm, deja vu..)
	- Function called `countVowels` that takes in a word and counts how many vowels there are in that word (more deja vu..)
	- Function called `getMostFrequentVowel` that takes in a word and finds the most frequently used vowel – don't worry about ties

Some boilerplate for you to use:
```js
var people = [{name: 'Tina'}, {name: 'Christine'}, {name: 'Terry'}];

let namesWithFiveOrMoreChars = () => {}

let nameLengths = () => {}

let getMostFrequentLetter = () => {}

let countVowels = () => {}

let getMostFrequentVowel = () => {}

// make sure your functions work for these invoked expressions
namesWithFiveOrMoreChars(people); // should return [{name: 'Christine'}, {name: 'Terry'}]
nameLengths(people); // should return [4, 9, 5]
getMostFrequentLetter('Lilac'); // should return 'l'
countVowels('Apple'); // should return 2
getMostFrequentVowel('Elephant'); // should return 'e'
```

## Wed, March 28
- Finish Sprint 3 of Book App
- Review Book App LIKE YOUR LIFE DEPENDS ON IT (just kidding, just your next 2 projects do)
- Keep working on Personal Portfolio feedback

## Tues, March 27
- Continue working on Mongoose lab (converting Todos app's server to mongoose calls) – solution [here](https://github.com/sf-wdi-44/mongoose/tree/master/solution)
- Continue implementing feedback on your Personal Portfolio Project – requirements [here](https://github.com/sf-wdi-44/personal-portfolio/blob/master/README.md#deliverables)

## Mon, March 26
- [Test-driven Todo App](https://github.com/sf-wdi-labs/test-driven-todo-api)
	- Fork and clone to your machine
	- Follow instructions up until this point:
	```
	0 passing (84ms)
	9 failing
	```
	- Make sure you are seeing the output that says `9 failing`!
- Review the Node.js / Express.js labs we did today. Make sure you are solid on the following concepts:
	- What is `package.json`? What command do I run to create one?
	- What command do I run to install a dependency like `express`?
	- What are the `/node_modules`?
	- Why is it best practice to put `/node_modules` inside our `.gitignore` file? (Please Google-fu your way through this!)
	- What is the difference between Node.js and Express.js?
	- What role do routes play in a server-side application?
	- How do I start a Node server? What is the benefit of using `nodemon`?
	- What is the difference between `req.params` vs. `req.query`?
	- What are the 4 HTTP methods you'd use for a server-side application?
	- Why is it best practice to put `/api` in front of API routes?
	- Each Node route takes in a callback function that looks like `function(request, response) { ... }` – are `request` and `response` keywords I have to use, or "potato" words?
	- What is the difference between `res.send` and `res.json`?

# Week 2: JavaScript on the Web
## Fri, March 23
- Elaborate on your **Racing Game** to get it portfolio-ready 
	- Style (add Bootstrap for easy out-of-the-box styling)
	- Add a bonus feature that you didn't have time to implement before presentations!
- Finish **Doggos JQuery** Project to practice JS iterators and JQuery (solution [here](https://github.com/esthersweon/doggos-jquery/tree/soln))
	- DRY up your code after you've finished adding Bootstrap card styles (solution [here](https://github.com/esthersweon/doggos-jquery/commit/08e75d48776ba436337eea34a6b02f55d6f79019))
- Finish **Giffaw**'s bonus ("Load More" button) to practice JS iterators and AJAX (solution [here](https://github.com/SF-WDI-LABS/giffaw/blob/soln-bonus/scripts/app.js))
- Finish **Geoquakes Project** to practice JS iterators and AJAX

## Thurs, March 22
- IMPORTANT: Complete HTML Forms Lab (*Submit GitHub link in Project Submission Doc*)
- Read through the Giphy project solution and be able to explain each line
- BONUS: Finish the Giphy project bonus feature ("Add More" gifs to the page) – Please attempt if you've finished and understood the rest of the Giphy project

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

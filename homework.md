# Week 11: Python and Django

## February 15, Thursday
1. Add code to your `hashTable.js` file to make your functions `getItem()` and `removeItem()` more robust:
	- `getItem()` – make sure the `targetBucket` exists and has a length before iterating through it
	- `removeItem()` – make sure the `targetBucket` exists and has a length before filtering it
2. Review solution [here](https://github.com/esthersweon/hashTables/blob/master/solution/hashTable.js)

## February 12, Monday
1. Finish writing the functions `letter_count` and `add_stars` if you did not finish them in class
- `letter_count('hello', 'l') # => 2)`
- `add_stars('hello') # => 'h*e*l*l*o'`
2. Create a directory called `python_exercises` and create a file for each of the following problems
- `ends_with_a.py` – write a function `ends_with_a` that returns whether or not a string ends with the letter A, case insensitive
  (e.g. `ends_with_a('banana') # => True`, `ends_with_a('bananAAAAAA') # => True`, `ends_with_a('bananas') # => False`)
- `same_first_and_last.py` - write a function `same_first_and_last` that returns whether or not a string starts and ends with the same letter (e.g. `same_first_and_last('neon') # => True`, `same_first_and_last('fluff') # => True`, `same_first_and_last('telephone') # => False`)
- `get_scrabble_score.py` - write a function `get_scrabble_score` that returns the score for a word (e.g. `get_scrabble_score('hello') # => 8`)

You can look up the score for each letter in a word using the dict below:
```python
letter_scoring_dict = {
	'A': 1,
	'B': 3,
	'C': 3,
	'D': 2,
	'E': 1,
	'F': 4,
	'G': 2,
	'H': 4,
	'I': 1,
	'J': 8,
	'K': 5,
	'L': 1,
	'M': 3,
	'N': 1,
	'O': 1,
	'P': 3,
	'Q': 10,
	'R': 1,
	'S': 1,
	'T': 1,
	'U': 1,
	'V': 4,
	'W': 4,
	'X': 8,
	'Y': 4,
	'Z': 10
}
```
- BASIC BONUS: `check_password.py` - write a function `check_password` that returns if a string is at least 8 characters, contains at least 1 uppercase and 1 lowercase letter, and has at least one of `!#$%&*`
- MEDIUM BONUS: `ransom_note.py` – write a function `ransom_note` that takes in a string and capitalizes each letter with 50% probability
- SUPER CHALLENGING BONUS: [Task 1: Diamond Pattern](http://cs111.wellesley.edu/archive/cs111_fall17/public_html/psets/ps03#task1)
3. In preparation for the Immers-a-thon, it is highly recommended you having a working version of a Node or Rails back-end, so that you can reference it as you build your team's back-end from scratch. The [Reddit Clone](https://github.com/sf-wdi-40/reddit-clone-mern) is a good example of a Node back-end. The [Rails API lab](https://github.com/SF-WDI-LABS/con-pletionist) for conferences is a good example of a Rails back-end.

# Week 10: Project 3

## February 9, Friday
1. Implement feedback from your Project 3 Code Review session (collaborate with teammates)
2. Finish Rails API Lab in preparation for the Immers-a-thon
3. Get ready for Python! Follow the "Installation" steps [here](https://github.com/SF-WDI-42/python) and type `python` into a terminal to make sure it opens a python REPL for you (similar to running `node` to get into the node REPL).

# Week 9: More React and Project 3

## February 1, Thursday
1. Review `mergeSort` algorithm – be able to explain in human terms what it is doing, and understand what each line of the solution code is doing. BONUS: re-implement `merge` and `mergeSort`.
2. Work on Project 3 with your teammates.

## January 31, Wednesday
1. Get ready for React Build Day Science Fair tomorrow morning
2. Start thinking of a pitch for Project 3 (full-stack – Node or Ruby on Rails back-end, React or vanilla JS front-end)

## January 30, Tuesday
1. Add functionality for deleting a TextPost in the Reddit MERN Stack Project
2. Add functionality for adding a comment to a TextPost on the SinglePostPage in the Reddit MERN Stack Project
3. Think of a simple game you may want to build for React Build Day tomorrow – keep it simple!

## January 29, Monday
1. Work on the "CREATING THE BACK-END" section of the [MERN Stack App](https://github.com/mnfmnfm/reddit-clone-mern/blob/master/README.md). Specifically:
  1. Fill in the `TextPosts` controller.
  2. Fill in the `Comments` controller.
  3. Fill in the `seed.js` file with a few `TextPost`s & `Comment`s.
  4. BONUS (recommended): Use POSTMAN to test that your RESTful CRUD routes are all working.

# Week 8: React

## January 26, Friday
1. Take the revised, everything-in-`TodosContainer.js` version of the [Todo app](https://github.com/SF-WDI-LABS/react_todo_walkthrough) and consider which pieces of the `TodosContainer.js` file feel unwieldy. At a minimum, you likely want to break out the logic for displaying, editing and deleting a single Todo into its own component, `Todo.js`. Break that logic out into a separate file.
2. One common real-world practice is to use, not just React components you write yourself, but other components written by your teammates or by other people. To that end, try to incorporate the generic React components found in [Michelle's package](https://github.com/mnfmnfm/generic-react-components) into your app. Importantly, you should NOT use your own form, and should instead use the `CreateOneItemForm` component given to you by Michelle's package. The package GitHub repo has installation instructions, documentation, and a link to a [demo app](https://github.com/mnfmnfm/demo-generic-react-components/).
3. (optional) For more practice with using other people's React components, try incorporating [react-bootstrap](https://react-bootstrap.github.io/getting-started/introduction) components into your app.
4. (optional) Make a cool React component that does something nice (like display todos from supercrud???) and publish it onto Heroku. Use [this Medium article](https://medium.com/@BrodaNoel/how-to-create-a-react-component-and-publish-it-in-npm-668ad7d363ce) as a guide.

## January 24, Wednesday
1. Read through two pages of Facebook's quick start guide to React: the pages on [Components and Props](https://reactjs.org/docs/components-and-props.html) and [State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html). These give a good overview of the difference between state and props, how to work with state and props effectively, and an intro to the component lifecycle, which we'll recap in the morning.
2. Finish the Twitter project, [Steps #8 ~ 11](https://docs.google.com/presentation/d/1_1387xNtElR2UTEljfuNXFRbWQVFg-AEy725kWHSQ9I/edit?usp=sharing). There is a `solution` branch on the [Github repo page](https://github.com/esthersweon/ga-twitter/tree/solution).

## January 22, Monday
1. Finish remaining Linked List methods, and ensure they work by testing in your Terminal's Node REPL (`node`, `.load singly-linked-list.js`)
2. Review Common Technical Interview questions (will hold mock interview Wednesday morning)

# Week 7:  More Rails; Project 2 Week

## January 19, Friday
1. Make sure to add the link to your lightning talk gist to the Project Submission doc.
2. Continue working on the Publify lab. Keep sending us your pull requests; we'll respond to them sporadically throughout the weekend.

## January 18, Thursday
1. Continue preparing for Lightning Talks

## January 17, Wednesday
1. Finish the [reflection survey on Project 2: Codename Vagabond](https://goo.gl/forms/5zcZqAIQPLY4BQM23).
2. Fix any security holes in your Vagabond app.

# Week 6: Rails

## January 11, Thursday through January 16, Tuesday
VAGABOND

## January 10, Wednesday
1. Finish Library App, Part I
2. Finish the Pet Lab – Prioritize Parts 1 & 5, but attempt working through Part 2 as time permits
3. BONUS: Finish Library App, Part II

## January 9, Tuesday
1. Finish the [Pet lab](https://github.com/SF-WDI-LABS/rails-pet-lab). Prioritize Part 1 and Part 5, but if you have time, doing at least parts 1, 2 and 5 would be best for your learning. (parts 3 and 4 also useful, if you have time/if you've already finished part 1.)

## January 8, Monday
1. Finish the Bog App at least 3 times total, timing yourself each time.
2. Remember to follow the submission directions for the Bog App (Github README, Project Submission Doc, etc.).

# Week 5: Ruby
## January 5, Friday
1. Finish Rock 'n' Rails app.
2. For Ruby Review: go over Monster OOP lab and Go Fish lab.

## January 4, Thursday
1. Finish Go Fish lab.

## January 3, Wednesday
1. Finish the [Username Generator lab](https://github.com/SF-WDI-LABS/username-generator) through at least Level 2.
2. Finish Page 1 of the [Ruby Monster lab](https://github.com/SF-WDI-LABS/ruby-monster-oop). Then, read through the [section of the Ruby OOP notes about inheritance](https://github.com/SF-WDI-LABS/ruby-oop#inheritance); we'll talk more about inheritance in the morning, but a night to sleep on it will be helpful.

## January 2, Tuesday
1. Complete a Ruby health check to make sure you're ready for tomorrow! Below are the commands Michelle ran, and their output on her computer. Run these on your computer and make sure they're similar (don't have to be identical). If anything doesn't work, fix it and/or reach out if you need help, because we'll start using these tools tomorrow morning.
2. Read through the qualitative feedback & technical comments on your Project 1 code (you should have received Slack messages from Esther and/or Michelle with both).

Health check:
```
rvm -v
> rvm 1.29.2 (latest) by Michal Papis, Piotr Kuczynski, Wayne E. Seguin [https://rvm.io/]

ruby -v
> ruby 2.4.0p0 (2016-12-24 revision 57164) [x86_64-darwin16]

gem -v
> 2.6.12

bundler -v
> Bundler version 1.15.3

irb -v
> irb 0.9.6(09/06/30)

rails -v
> Rails 5.1.3

psql --version
> psql (PostgreSQL) 9.6.3

psql
> psql (9.6.3)
> Type "help" for help.
>
> michelle=#
# control-D to exit out of psql
```

# Week 4: Project 1

## December 21, Thursday
1. Continue working on Project 1 over the break (reference the Git Cheat Sheet on the schedule for collaborating with your team remotely).
- Push up to Heroku
- Fill out README
- Add style and polish
- Prepare presentation
- Make sure your project meets all technical requirements
2. BONUS: Review Tunely from beginning to end (with and without looking at the solution branches)

# Week 3: Full-Stack JavaScript

## December 15, Friday
1. Finish Tunely sprint 3.
2. Complete the Personal API project. We will present this on Monday morning.
3. Finish Tunely sprint 4.
4. (optional, do last) Finish Tunely sprints 5 and 6.

## December 14, Thursday
1. Fill out the weekly pulse check. Link in Slack.
2. Finish Sprint 2 of Tunely. In the morning, you'll have a new partner, and everyone will start the beginning of sprint 3 together. (If you don't have time to finish writing all of the code yourself, you should read through the directions for Sprints 1/2 so you know what's happened when you start tomorrow.)

## December 13, Wednesday
1. Review what [referenced data](https://github.com/SF-WDI-LABS/mongoose-associations#implementation-referenced) is and how it works in Mongo.
2. Finish Sprints 1-2 of the [Book App](https://github.com/SF-WDI-LABS/mongoose-books-app). Use POSTMAN to verify all API endpoints!
3. BONUS: Read the `seed.js` file in your Book App and reason about what the code is accomplishing.

## December 12, Tuesday
1. Continue working on the Todo App v2 that we started today in class. There are solutions for each of the methods in the [README file](https://github.com/SF-WDI-42/mongoose), but try to get through as many as possible without reading through those solutions!
2. Walk back through all the code that we wrote today, and try to break it down to the level that we did in class ("when a get request comes to this url, we look in the database... " etc.). This type of understanding is the most useful tool to have so that you can use your previous code to help you in the days/weeks to come.

## December 11, Monday
1. Review comments on your Personal AJAX Project (PR links were Slacked out). Address comments by adding commits to your repo (NOT merging in the PR).
2. Get as far as possible on the Test-Driven To Do App. Try to at least get through the index, show, and create methods.

# Week 2: JavaScript on the Web
## December 8, Friday
1. Your job this weekend is to explore a new API. You get two options for this. Whichever option you choose, **put a link to your repo into the Project Submission doc**, and consider turning on GitHub Pages in your repo settings as well.
  * Pick any API **that does not require OAuth** from [this list](https://github.com/toddmotto/public-apis). Build a site that uses that API based on user input. (So your site needs to allow a user to enter some information, then make an AJAX request using the information they entered.)
  * Complete the [Spotify search lab](https://github.com/SF-WDI-LABS/spotify-search-lab), which is a specific set of requirements with the Spotify API.

## December 7, Thursday
1. Finish the Giffaw lab begun in class.
2. Get started on the <a href="https://github.com/SF-WDI-LABS/geoquakes">Geoquakes Project</a>. Your job is to finish **Parts 1 and 2** of that lab, which are very similar to Giffaw. We will work on parts 3 and 4 in class tomorrow.

## December 6, Wednesday
1. Sign up for an account at [http://git.generalassemb.ly](http://git.generalassemb.ly). (I know you already have a GitHub account. This is different.) Add your username to the project submission doc.
2. Finish the [Racing Game Project](https://github.com/sf-wdi-40/project-0), and add a link in the project submission doc. In the morning, we'll present these science-fair style: you'll show your game on your computer and walk around to play others' games as well.
3. BONUS: Spend time reviewing JavaScript practice problems from last week, especially [JS Basics Problems Set](https://github.com/SF-WDI-LABS/problem-set-js-basics) & [Objects](https://github.com/SF-WDI-LABS/js-objects-training).

## Dec 5, Tuesday
1. Finish [DOM Events Lab](https://github.com/SF-WDI-LABS/jquery-events-lab)
2. Finish [Tic Tac Toe Project](https://github.com/SF-WDI-LABS/tic-tac-toe)

## Dec 4, Monday
1. Finish [Functions Training](https://github.com/SF-WDI-LABS/functions-exercises)
2. Do [Laundry Lab](https://github.com/SF-WDI-LABS/js-iterators-laundry-lab)

# Week 1: Welcome to WDI!

## Dec 1, Friday
1. Finish the <a href="https://github.com/SF-WDI-LABS/personal-portfolio/blob/master/part-2.md">Portfolio Part 2</a> assignment. To do a code review Monday morning, **we will print your code at 8:00am Monday**, so you MUST put links in the Project Submission doc before then.
2. Re-visit any earlier assignments or topics you'd like to review. Recommended topics:
  - BASICS REVIEW: Be able to answer all questions covered in the Fundamentals assessment packet
  - JS WARM-UP: [Data Types](https://github.com/SF-WDI-LABS/js-data-types-training), [Control Flow](https://github.com/sf-wdi-labs/js-control-flow-training/), & [Objects](https://github.com/SF-WDI-LABS/js-objects-training)
  - JS PRACTICE: [Problems Set](https://github.com/SF-WDI-LABS/problem-set-js-basics) & [jQuery Playground](https://github.com/SF-WDI-LABS/jquery-playground-lab)
  - BOOTSTRAP: Implement different Bootstrap [components](https://getbootstrap.com/docs/4.0/components/alerts/) into your Personal Portfolio

## Nov 30, Thursday
1. Fill out the Pulse Check. (This will be Slacked out every Thursday afternoon for the next 12 weeks.)
2. Finish the Personal Portfolio that you started earlier in the week. Your goal is to get the HTML and CSS as solid as possible tonight; you'll add JS over the weekend.
3. Finish the jQuery Playground and Fantastic Mr. Fox labs from this afternoon.


## Nov 29, Wednesday
1. Finish AND TURN IN (using the same directions yesterday, and in the Project Submission doc) the JS Basics problem set.
2. Continue the JS Objects problems from this morning.
3. Keep working on your portfolio! We will NOT have a formal review of them on Friday, but we will on Monday, and you'll have another portfolio-related assignment over the weekend.


## Nov 28, Tuesday
1. Finish the [Control Flow Training](https://github.com/sf-wdi-labs/js-control-flow-training/) started in class. Submit your work using [these directions](https://github.com/SF-WDI-LABS/shared_modules/blob/master/how-to/submit-homework.md) to create a pull request. In addition to creating the pull request, please add a link to your repo in the [Project Submission doc](https://docs.google.com/spreadsheets/d/1Phbzp7kwryUhv3C7con25LoUYU8yEoHw7K5-dLSvOnU/edit#gid=0).
2. If you have not finished [Installfest](https://github.com/SF-WDI-LABS/installfest), do so tonight.
3. Review your graded Fundamentals assessment.
4. (optional, will be listed in the homework all week) Continue working on your personal portfolio. Take design inspiration from portfolios around the Internet, and feel free to get creative!

## Nov 27, Monday
> Note: Homework is generally listed from most important to least important each day.

1. Finish the Fundamentals assessment that was handed out in class. You will turn this in tomorrow morning at 9am. (Please start early on this!)
2. Finish the Site Recreation lab begun in class.

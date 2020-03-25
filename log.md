# #100DaysOfCode

## My First Round's Log: 🤞🏼

### Day 001: March 01, 2020 SUN

**Today's Progress:**  
Started a new project with node.js and set up the project folder structure. Sorted out the DB connection and HTML skeleton.

**Thoughts:** Need to figure out how the NoSQL's documents relation works?!

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 002: March 02, 2020 MON

**Today's Progress:**  
Implementing the express-ejs-layouts package 👍🏼, and focus on the front-end views today. Sort out the landing page's layout using the CSS grid. Research on RESTful API and MVC architecture, see if I can implementing it in this small project.  

**Thoughts:** CSS grid is way more easy to use than flexbox?! Took me awhile try to use flex, but somethings just not right so eventually, I just switch to use grid...!

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 003: March 03, 2020 TUE

**Today's Progress:**  
Focus on the front-end views again. Sort out the landing page's layout and make it RWD. Research on CSS variables and @media function.  

**Thoughts:** 🤔 Mostly staring at the css code try to figure out how to make it responsive and align contents...!

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 004: March 04, 2020 WED

**Today's Progress:**  
Found a npm package called [popular-movie-quotes](https://www.npmjs.com/package/popular-movie-quotes) which I use it to generate random movie quote on my landing page. 😜 And then I work on how to get the Date in js and show it on the page in the format I want. Also, did a bit CSS to play with the text input field!

**Thoughts:** It's fun to search for the npm that can help me do some stuff I want!

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 005: March 05, 2020 THU

**Today's Progress:**  
Got sidetrack today, found a new coding practice website "Hackerrank" and got hook on solving challenges...!🤪Solved 12 challenges!! It was really fun! Like playing games. Haha~!
Set up the list field with a delete button.

Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 12

- Counting Valleys
- Sock Merchant
- Time Conversion
- Birthday Cake Candles
- Mini-Max Sum
- Staircase
- Plus Minus
- Diagonal Difference
- A Very Big Sum
- Compare the Triplets
- Simple Array Sum
- Solve Me First

**Thoughts:** I really enjoy solving problems...!😅

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 006: March 06, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 6

- Kangaroo
- Apple and Orange
- Grading Students
- Matching Specific String
- Repeated String
- Jumping on the Clouds

The Kangaroo one took me quite awhile to solve...about 1 hour?! 🤯  
Setup may ToDoList's .env file, but still need to research more about how to properly use it.

**Thoughts:** I really enjoy solving problems...!😅But might need to refresh my math concepts...! 🤣

**Link to work:** [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 007: March 07, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 4

- ~~Array Manipulation (half test failed due to timeout...!🤯)~~
- Minimum Swaps 2
- New Year Chaos
- Arrays: Left Rotation
- 2D Array - DS  

Solving problems are really addictive...! 🤓  

**Thoughts:** Array manipulation is really interesting...! 🤣

**Link to work:** N/A

### Day 008: March 08, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 6

- Day of the Programmer
- Migratory Birds
- Divisible Sum Pairs
- Birthday Chocolate
- Breaking the Records
- Between Two Sets

Today I used Adobe XD to design the markup for my freeCodeCamp's product landing page's project. Also, finished the general structure of the html file.

**Thoughts:** 8 days in, and I'm still keeping up...! I'm impressed with myself~! HAHA 🤣Don't give up, just keep going~!!! You'll get hired someday?! 🤞🏼

**Link to work:** [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage)

### Day 009: March 09, 2020 MON

**Today's Progress:**  
Problems solved on Hackerrank: 5

- Picking Numbers
- Cats and a Mouse
- Electronics Shop
- Drawing Book
- Bon Appétit

Today I start to build my freeCodeCamp's product landing page's project. Finished styling the header section.

**Thoughts:** Got stock in the Magic Square challenge on Hackerrank. Need to figure out how to check certain pattern in 2D array...! 🤔

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage)

### Day 010: March 10, 2020 TUE

**Today's Progress:**  
Today I focus to building my freeCodeCamp's product landing page's project. Finished styling the desktop version, still need to work on the RWD part tmr.
Taking a break on the Hackerrank challenges to let my brain rest...! 😅

**Thoughts:** CSS is definitely not as easy as I though..., need to figure out a way to make it cleaner?! 🤔

**Link to work:** [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage)

### Day 011: March 11, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 7

- Climbing the LeaderBoard
- Viral Advertising
- Beautiful Days at the Movies
- Angry Professor
- Utopian Tree
- Designer PDF Viewer
- The Hurdle Race

Back with Hackerrank challenges! Today I got stuck with the "Climbing the LeaderBoard" challenge for quite some time...! My logic is right but 4 of the sample keep getting runtime error, after some googling it had something to do with "Big O notation". Cuz I was looping one array inside another array which is O(n * n), it will slow down when n gets too big...?! Anyway, still not fully understanding the concept yet, but I know I need to somehow loop through both array at the same time to compare them. So, I finally found that I can do this:

```javascript
// loop both array in nested for loop  
// but put both starting point on the outside loop  
for (let i = 0, j = 0; i < n; n++) {
    for (; j < m; j++) {
        // code goes here...
    }
}
// this way j will not reset every time i go up!
```

totally did not know I can do that...! 😅

Today I also finished my PS5 product landing page for freeCodeCamp's project. It was fun!

**Thoughts:**  Need to find better tutorial to get the "Big O notation" concept!! 🤔

**Link to work:** [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage) ✔️

### Day 012: March 12, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 4  

- Jumping on the Clouds: Revisited
- Sequence Equation
- Circular Array Rotation
- Save the Prisoner!  

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 12

- Find the unique number
- Find the missing letter
- Sum of two lowest positive integers
- Detect Pangram
- Does my number look big in this?
- Duplicate Encoder
- Disemvowel Trolls
- Beginner Series #3 Sum of Numbers
- Persistent Bugger
- Complementary DNA
- Binary Addition
- Multiply

Today I not quite sure how to approach my next freeCodeCamp project which is the "Build a Technical Documentation Page", so I kinda just keep practice more problem solving on Hackerrank & my new found playground "Codewars"! 😅

**Thoughts:** Blank...!🤔

**Link to work:** N/A

### Day 013: March 13, 2020 FRI

**Today's Progress:**  
Problems solved on Hackerrank: 3

- Sherlock and Squares
- Append and Delete
- Find Digits

Problems solved on Codewars: 2

- Find the odd int
- Maximum subArray sum

Today I mostly watching YouTube tutorials to find some inspirations of my next project. Traversy Media & Web Dev Simplified. Both talk about Stripe API for your online shop!! I should try to build some simple shopping site to try it out!!

**Thoughts:** Feeling a bit under the weather, hopefully it's not **COVID-19**!!! 🤞🏼

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [Codewars](https://www.codewars.com/users/jacoblindev)

### Day 014: March 14, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3

- Equalize the Array
- Cut the sticks
- Library Fine

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 2

- Title Case
- Highest Scoring Word

**Thoughts:** Feeling kinda burnt out, need to slow down a bit to process what I've been learning. 😵

**Link to work:** N/A

### Day 015: March 15, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 2

- Minimum Distances
- Beautiful Triplets

Problems solved on Codewars: 0

**Thoughts:** Busy with other work today so not much progress. Challenges are getting harder now, cuz running out of easy level challenges...! 🤣 Need to learn more algorithm concepts to deal with upcoming challenges!!

**Link to work:** N/A

### Day 016: March 16, 2020 MON

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 4

- Service Lane
- Modified Kaprekar Numbers
- Halloween Sale
- ACM ICPC Team

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 1

- Buying a car

**Thoughts:** Running into a bug on the "Service Lane" challenge that the input for JavaScript is wrong...! I had to go through the whole code inside the editor to find the variable I need in order to complete the challenge! Haha~! Kinda my official debugging experience! 🤣

**Link to work:**  N/A

### Day 017: March 17, 2020 TUE

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 2

- Lisa's Workbook
- Chocolate Feast

Problems solved on Codewars: 0

**Thoughts:** Somewhat productive day~! 👍🏼I started my freeCodeCamp's "Technical Documentation Page" RWD project. I decided to use it to document my "JS Algorithms & Data Structures Projects". It went well today, I already finished about half of it so should be able to complete it within the next few days. 🤓

**Link to work:** [FCC-TechnicalDocumentationPage](https://jacoblindev.github.io/FCC-TechnicalDocumentationPage/)

### Day 018: March 18, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3

- Array Manipulation 🎉
- Fair Rations-10 hours ago
- Flatland Space Stations

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 1

- Two Sum

**Thoughts:** A really productive day~! 👍🏼I finished my freeCodeCamp's "Technical Documentation Page" RWD project. And attempt one more time to solve the "Array Manipulation" challenge (level: HARD), with some google search I finally solved it. Learned "Prefix Sum Array" concept!! 🤓

**Link to work:** [FCC-TechnicalDocumentationPage](https://jacoblindev.github.io/FCC-TechnicalDocumentationPage/) ✔️

### Day 019: March 19, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 2

- Strange Counter
- Arrays - DS

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 1

- Vasya - Clerk

**Thoughts:** Not much coding challenges today, mainly focus on trying to finished my freeCodeCamp's RWD projects. I started my last one which is personal portfolio webpage, and I'm half way through already. 🤓Can definitely finish it tomorrow!

**Link to work:** [FCC-PersonalPortfolioWebpage](https://jacoblindev.github.io/FCC-PersonalPortfolioWebpage/)

### Day 020: March 20, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0

**Thoughts:** Finished my personal portfolio webpage and got my first 2 freeCodeCamp certificates. RWD & JS-Algorithms-&-Data-Structure. Taking a break on solving problems, instead need to focus more on building websites! And planning out what content to share on Instagram. 🤔

**Link to work:** [FCC-PersonalPortfolioWebpage](https://jacoblindev.github.io/FCC-PersonalPortfolioWebpage/) ✔️

### Day 021: March 21, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 2 (65)

- Strong Password
- CamelCase

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 1 (20)

- Take a Number And Sum Its Digits Raised To The Consecutive Powers And ....¡Eureka!!

**Thoughts:** Today I went through a bunch YouTube tutorials to see which front-end framework should I start learning. **React.js** vs **Vue.js** ? 🤔I decided to try **Vue.js** first because it actually seems much friendly to beginners. Cuz you can still just write in HTML & CSS, and not suddenly jump to write everything inside JS. 

P.S. The Net Ninja's "[Vue JS 2 Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gQcYgjhBoeQH7wiAyZNrYa)" seems pretty easy to grasp!!!

Maybe I can start try to implements those function I solved into some kinda small webapp? Like some simple calculations?!

**Link to work:** N/A

### Day 022: March 22, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (65)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:** Today I start learning **Vue.js**, it's really beginner friendly. Still just trying things out, will start some small projects soon!! 🤔  

The Net Ninja's "[Vue JS 2 Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gQcYgjhBoeQH7wiAyZNrYa)" seems pretty easy to grasp!!!

Traversy Media's "[Vue JS Crash Course](https://www.youtube.com/watch?v=Wy9q22isx3U&t=1333s)" is nice too.

**Link to work:** N/A

### Day 023: March 23, 2020 MON

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 4 (69)

- Matching Word & Non-Word Character
- Matching Whitespace & Non-Whitespace Character
- Matching Digits & Non-Digit Characters
- Matching Anything But a Newline

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:** Today I follow Traversy Media's tutorial and build a todolist app with Vue.js! Also, went through the Vue Doc for some basic concepts. Maybe try to take it slow and really mastering it so it will be good for future job hunting...?! 

Going through some regex practice on Hackerrank, so that I can better prepare for String related challenges.

The Net Ninja's "[Vue JS 2 Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gQcYgjhBoeQH7wiAyZNrYa)" seems pretty easy to grasp!!!

Traversy Media's "[Vue JS Crash Course](https://www.youtube.com/watch?v=Wy9q22isx3U&t=1333s)" is nice too.

**Link to work:** [TodoList-Vue](https://github.com/jacoblindev/vue_learning_todoapp)

### Day 024: March 24, 2020 TUE

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 15 (84)

- Matching Ending Items
- Matching One Or More Repetitions
- Matching Zero Or More Repetitions
- Matching {x, y} Repetitions
- Matching {x} Repetitions
- HackerRank Language
- Saying Hi
- Matching Character Ranges
- Excluding Specific Characters
- Matching Specific Characters
- Capturing & Non-Capturing Groups
- Negative Lookbehind
- Positive Lookbehind
- Negative Lookahead
- Matching Start & End

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:** Not feeling very focus on learning Vue.js, so instead I try out the challenge on [Frontend Mentor](https://www.frontendmentor.io/) and build a small landing page. Kinda fun trying to code out people's design.

Keep going through some regex practice on Hackerrank, so that I can better prepare for String related challenges.

**Link to work:** [FM-FourCards](https://github.com/jacoblindev/FM-FourCards)

### Day 025: March 25, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 4 (88)

- Back-references To Failed Groups
- Matching Same Text Again & Again
- Alternative Matching
- Matching Word Boundaries

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:**  Started my second challenge on [Frontend Mentor](https://www.frontendmentor.io/), but not doing much yet. Kinda busy with life stuff...! Well, I'm 1/4 into the #100DaysOfCode challenge already. I'm surprised that I'm still keep it up, this is really a good way to motivate myself and hold myself accountable. Somehow it breaks my procrastinating habit. Awesome~! 🤟🏼

Keep going through some regex practice on Hackerrank.

**Link to work:** [FM-BaseApparel](https://github.com/jacoblindev/FM-BaseApparel)

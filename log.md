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

### Day 026: March 26, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:**  Keep on working my [Frontend Mentor](https://www.frontendmentor.io/) project, almost finished still need to do some JS for the Error message. Also, keep on learning Vue.js bits by bits.

**Link to work:** [FM-BaseApparel](https://github.com/jacoblindev/FM-BaseApparel)

### Day 027: March 27, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:**  Keep on working my [Frontend Mentor](https://www.frontendmentor.io/) project, finished Base Apparel and I didn't use any JS. I end up just use CSS' pseudo-selector ":invalid" to style the Error message. I also finished another simple challenge. Kinda productive today! Also, keep on learning Vue.js bits by bits.

**Link to work:** [FM-BaseApparel](https://jacoblindev.github.io/FM-BaseApparel/) ✔️ | [FM-SinglePriceGridComponent](https://jacoblindev.github.io/FM-SinglePriceGridComponent/) ✔️

### Day 028: March 28, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (20)

**Thoughts:**  Started another [Frontend Mentor](https://www.frontendmentor.io/) project, but feeling a bit lazy...! So, just keep on learning Vue.js bits by bits through the documentation. What project should I build with the Essentials Vue.js knowledge I just learned? 🤔

**Link to work:** [FM-IntroComponent-SignUpForm](https://github.com/jacoblindev/FM-IntroComponent-SignupForm)

### Day 029: March 29, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 5 (25)

- Break camelCase
- Consecutive strings
- Product of consecutive Fib numbers
- Word a10n (abbreviation)
- Rot13

**Thoughts:** Not feel like building website today, so went on Codewars to try solve some challenge. And I did solved 5 String related challenges, but got stuck for some challenges that I need to skip. Definitely need to practice more on String manipulation.

**Link to work:** N/A

### Day 030: March 30, 2020 MON

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Well, can't believed It's already 30% into the #100DaysOfCode challenge, and I'm still keeping it up! I guess this is the power of commitment?! 💪🏻I did slowly building up my skills and portfolio! Awesome~!👊🏼加油～！

Not doing much today, kinda got busy with my PT job. But I still code a little bit of the SignUp Form challenge from Frontend Mentor.

**Link to work:** [FM-IntroComponent-SignUpForm](https://github.com/jacoblindev/FM-IntroComponent-SignupForm)

### Day 031: March 31, 2020 TUE

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Today I code a little bit of the SignUp Form challenge from Frontend Mentor, still got the error state part need to be done! Tmr I got a web developer job interview, so need to sleep well tonight!! Wish me luck!!🤞🏼Hope every goes well!!!

**Link to work:** [FM-IntroComponent-SignUpForm](https://github.com/jacoblindev/FM-IntroComponent-SignupForm)

### Day 032: April 01, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Today I finished the SignUp Form challenge from Frontend Mentor, I finally start using JS for DOM manipulation. Because the :invalid input state had some issue with type="text" fields, it will fire right at the beginning which is not what we want. So, instead I use "blur" event to setAttribute "required" to the input fields to show the error message after user finished with the field to check its validation.

Went to the interview today, it seems like it's going well but you never know?! Definitely did not prepare well enough for the Java test...! 😭 Hope they see my potential and give me a chance...! Let's wait & see!!!

Happy fools day...!🤪

**Link to work:** [FM-IntroComponent-SignUpForm](https://jacoblindev.github.io/FM-IntroComponent-SignupForm/) ✔️

### Day 033: April 02, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Today is the start of the long weekend, so it's really busy at my PT job. Too tired to do much so I only setup the new FM challenge for tmr! 😴🥱 I'll try to do more on this long weekend...! 💪🏻

**Link to work:** [FM-PingComingSoonPage](https://github.com/jacoblindev/FM-PingComingSoonPage)

### Day 034: April 03, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Had a chill day today~! 😌 Finished one challenge of [Frontend Mentor](frontendmentor.io) and start another one! 💪🏻

**Link to work:** [FM-PingComingSoonPage](https://jacoblindev.github.io/FM-PingComingSoonPage/) ✔️ | [FM-HuddleLandingPage](https://github.com/jacoblindev/FM-HuddleLandingPage)

### Day 035: April 04, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (88)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

**Thoughts:** Lazy day today~! 🤪 Finished one more challenge of [Frontend Mentor](frontendmentor.io)! 💪🏻This one took a bit long time cuz it's a full page website. I manage to sit down and power through!!! 👊🏼

**Link to work:** [FM-HuddleLandingPage](https://github.com/jacoblindev/FM-HuddleLandingPage) ✔️

### Day 036: April 05, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 6 (94)

- Day 1: Let and Const
- Recursion: Fibonacci Numbers
- Day 1: Functions
- Day 1: Arithmetic Operators
- Day 0: Data Types
- Day 0: Hello, World!

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Finished one more challenge of [Frontend Mentor](frontendmentor.io)! 💪🏻And setup another one for tmr. Start a "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev), good to refresh my basics!!

**Thoughts:** Although I'm practice a lot but kinda feeling like stock and not really moving forward...?! And also not very focus lately...?! Really need to find a way to plan things out a bit better, instead of doing whatever...!!!🤔

**Link to work:** [FM-HuddleLandingPage-SingleIntro](https://jacoblindev.github.io/FM-HuddleLandingPage-SingleIntro/) ✔️ | [FM-FyloLandingPage](https://github.com/jacoblindev/FM-FyloLandingPage)

### Day 037: April 06, 2020 MON

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3 (97)

- Day 2: Loops
- Day 2: Conditional Statements: Switch
- Day 2: Conditional Statements: If-Else

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Day 2 of "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev)!!

**Thoughts:** ...! 🥱😴

**Link to work:** [FM-FyloLandingPage](https://github.com/jacoblindev/FM-FyloLandingPage)

### Day 038: April 07, 2020 TUE

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3 (100)

- Day 3: Throw
- Day 3: Try, Catch, and Finally
- Day 3: Arrays

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Day 3 of "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev)! Quite a productive day. Finished one FM challenge and started another one, will finished it tmr🤞🏼!!

**Thoughts:** I do think my HTML & CSS is getting much better and consistent, need to start try some advance stuff like animation but overall not bad!! Also, need to start trying more DOM manipulation and JS effects!! Good job, keep it up! 👍🏼

**Link to work:** [FM-FyloLandingPage](https://github.com/jacoblindev/FM-FyloLandingPage) ✔️ | [FM-SocialMediaDashboard](https://github.com/jacoblindev/FM-SocialMediaDashboard)

### Day 039: April 08, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3 (103)

- Day 4: Classes
- Day 4: Count Objects
- Day 4: Create a Rectangle Object

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Day 4 of "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev)! So tired... but I push through and finished the FM challenge!! I manage to find out how to use jQuery to toggle the class for the dark mode effect!! Cool~!!!

**Thoughts:** 🥱😴

**Link to work:** [FM-SocialMediaDashboard](https://github.com/jacoblindev/FM-SocialMediaDashboard)

### Day 040: April 09, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 3 (106)

- Day 5: Arrow Functions
- Day 5: Template Literals
- Day 5: Inheritance

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Day 5 of "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev)! 

**Thoughts:** Got a call from RT mart telling me I got the job. 🎉 Waiting for the email confirmation and it's all set!! After about 9 months effort to learn and becoming a web developer, I finally going to make it. 😬 Kinda scary & excited both at the same time...! Not quite sure what I get myself into, but I'm ready for any challenges & determine to succeed in this profession. 👊🏼 Good Luck!!🤞🏼

**Link to work:** N/A

### Day 041: April 10, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (106)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Day 6 of "10 days of JS" tutorial from [Hackerrank](https://www.hackerrank.com/jacoblindev)! Well, kinda got stuck with the Bitwise stuff...! 🤯 Need more brain power to understand it!! 😬🧠 

Fixed some issue with the last project's RWD. Switch from flex to grid, and it's all good now!!

**Thoughts:** Got the email confirmation for the PG job!! 🎉 Keep it up!! 😄

**Link to work:** [FM-SocialMediaDashboard](https://jacoblindev.github.io/FM-SocialMediaDashboard/) ✔️

### Day 042: April 11, 2020 SAT

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 2 (108)

- Forward References
- Branch Reset Groups

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Did a bit Regex lessons from [Hackerrank](https://www.hackerrank.com/jacoblindev)!

Start a new FM challenge, just finished some setup for CSS & Header section of the HTML! Going to take it slow this time and focus more on structure and details.

**Thoughts:** Things are changing that now I got a full-time job, time is limited now. Need to figure out a way to balance coding and workout routine for my spare times...!? 🤔🤷🏻‍♂️  

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 043: April 12, 2020 SUN

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 1 (109)

- Positive Lookahead

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Did a bit Regex lessons from [Hackerrank](https://www.hackerrank.com/jacoblindev)!

Finished setting up HTML structure for the FM challenge! Will try to practice mobile first approach for this challenge.

**Thoughts:** ??? 🤷🏻‍♂️ Not feel like learning much today!!!

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 044: April 13, 2020 MON

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (109)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (25)

Finished the header's burger menu's css. Using the checked state to show and hide the burger-btn. Still need to work out how to show & hide the nav links, probably by using jQuery!? 🤔

**Thoughts:** Just tired...! (from the PT job!) 🥱

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 045: April 14, 2020 TUE

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (109)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 2 (27)

- Salesman's Travel
- Array Helpers

Did two codewars' challenges, learned how to extends build-in Array methods with the prototype. And some string manipulations.

Finished the header section. End up just using css to work out the hide & show menu part! Work out the position fixed and absolute issue & width and height issues!!! 👍🏼

**Thoughts:** Nothing...

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 046: April 15, 2020 WED

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (109)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (27)

Finished the intro section... kinda?! Not sure what to do with the back ground pattern? It's crossing two sections so ...?🤔

**Thoughts:** Nothing...

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 047: April 16, 2020 THU

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (109)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 0 (27)

Not doing much cuz a massive headache...! So, I took a big nap after work!

**Thoughts:** Nothing...

**Link to work:** [FM-InsureLandingPage](https://github.com/jacoblindev/FM-InsureLandingPage)

### Day 048: April 17, 2020 FRI

**Today's Progress:**  
Problems solved on [Hackerrank](https://www.hackerrank.com/jacoblindev): 0 (109)

Problems solved on [Codewars](https://www.codewars.com/users/jacoblindev): 1 (28)

- String incrementer

Taking it easy today, not feel like coding much so just went on Codewars to solved a Kata. Again with some String manipulation, although I did solved it but it's not the most clean way to do it obviously. So I really think I need to study more about the recursive function, so I can code cleaner solutions.🤔

**Thoughts:** Nothing...

**Link to work:** N/A

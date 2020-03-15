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

Problems solved on Hackerrank: 12

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

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 006: March 06, 2020 FRI

**Today's Progress:**  
Problems solved on Hackerrank: 6

- Kangaroo
- Apple and Orange
- Grading Students
- Matching Specific String
- Repeated String
- Jumping on the Clouds

The Kangaroo one took me quite awhile to solve...about 1 hour?! 🤯  
Setup may ToDoList's .env file, but still need to research more about how to properly use it.

**Thoughts:** I really enjoy solving problems...!😅But might need to refresh my math concepts...! 🤣

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [ToDoList-v2](https://github.com/jacoblindev/ToDoList-v2)

### Day 007: March 07, 2020 SAT

**Today's Progress:**  
Problems solved on Hackerrank: 5

- Array Manipulation (half test failed due to timeout...!🤯)
- Minimum Swaps 2
- New Year Chaos
- Arrays: Left Rotation
- 2D Array - DS  

Solving problems are really addictive...! 🤓  

**Thoughts:** Array manipulation is really interesting...! 🤣

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev)

### Day 008: March 08, 2020 SUN

**Today's Progress:**  
Problems solved on Hackerrank: 6

- Day of the Programmer
- Migratory Birds
- Divisible Sum Pairs
- Birthday Chocolate
- Breaking the Records
- Between Two Sets

Today I used Adobe XD to design the markup for my freeCodeCamp's product landing page's project. Also, finished the general structure of the html file.

**Thoughts:** 8 days in, and I'm still keeping up...! I'm impressed with myself~! HAHA 🤣Don't give up, just keep going~!!! You'll get hired someday?! 🤞🏼

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage)

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
Problems solved on Hackerrank: 7

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

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [FFC-ProductLandingPage](https://github.com/jacoblindev/FCC-ProductLandingPage) ✔️

### Day 012: March 12, 2020 THU

**Today's Progress:**  
Problems solved on Hackerrank: 4  

- Jumping on the Clouds: Revisited
- Sequence Equation
- Circular Array Rotation
- Save the Prisoner!  

Problems solved on Codewars: 12

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

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [Codewars](https://www.codewars.com/users/jacoblindev)

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
Problems solved on Hackerrank: 3

- Equalize the Array
- Cut the sticks
- Library Fine

Problems solved on Codewars: 2

- Title Case
- Highest Scoring Word

**Thoughts:** Feeling kinda burnt out, need to slow down a bit to process what I've been learning. 😵

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev) | [Codewars](https://www.codewars.com/users/jacoblindev)

### Day 015: March 15, 2020 SUN

**Today's Progress:**  
Problems solved on Hackerrank: 2

- Minimum Distances
- Beautiful Triplets

Problems solved on Codewars: 0

**Thoughts:** Busy with other work today so not much progress. Challenges are getting harder now, cuz running out of easy level challenges...! 🤣 Need to learn more algorithm concepts to deal with upcoming challenges!!

**Link to work:** [Hackerrank](https://www.hackerrank.com/jacoblindev)

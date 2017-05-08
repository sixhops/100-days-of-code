# 100 Days Of Code - Log

### Day 1: April 18, 2017

**Today's Progress**: Search-and-Replace challenge, Pig Latin challenge, DNA Pairing challenge, Missing Letters challenge

**Thoughts:** Must review String functions. Strings are immutable - look into this and see how exactly this limits you.

**Link to work:** 
https://www.freecodecamp.com/challenges/search-and-replace
https://www.freecodecamp.com/challenges/pig-latin
https://www.freecodecamp.com/challenges/dna-pairing
https://www.freecodecamp.com/challenges/missing-letters
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 2: April 19, 2017

**Today's Progress**: Boo Who challenge, Sorted Union challenge, Convert HTML entities challenge

**Thoughts:** Only 10 more challenges until the advanced scripting challenges.

**Link to work:** 
https://www.freecodecamp.com/challenges/boo-who
https://www.freecodecamp.com/challenges/sorted-union
https://www.freecodecamp.com/challenges/convert-html-entities
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 3: April 20, 2017

**Today's Progress**: Spinal Tap Case challenge, Sum All Odd Fibonacci Numbers challenge, Sum All Primes challenge started

**Thoughts:** I heart RegEx.

**Link to work:** 
https://www.freecodecamp.com/challenges/spinal-tap-case
https://www.freecodecamp.com/challenges/sum-all-odd-fibonacci-numbers
https://www.freecodecamp.com/challenges/sum-all-primes
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 4: April 21, 2017

**Today's Progress**: Sum All Primes challenge, Smallest Common Multiple challenge started

**Thoughts:** Lots of math proofs. Had to dust off that part of my brain.

**Link to work:** 
https://www.freecodecamp.com/challenges/sum-all-primes
https://www.freecodecamp.com/challenges/smallest-common-multiple
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 5: April 22, 2017

**Today's Progress**: Smallest Common Multiple challenge continued

**Thoughts:** Completely rewrote the algorithm to be a little less convoluted. Spent a lot of time tracking down refactoring bugs from the rewrites. Basically going for finding the prime factorization of each number, folding lower prime multiples into whatever has the highest, then mutiplying all factors together to get the LCM. Lots of loops and array manipulation. Will continue work on it tomorrow.

**Link to work:** 
https://www.freecodecamp.com/challenges/smallest-common-multiple
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 6: April 23, 2017

**Today's Progress**: Smallest Common Multiple challenge continued

**Thoughts:** Prime factorization is working. Now I'm working on retaining only the highest quantities of each factor for multiplying to find the LCM. Switching from an array to a hash/object helps keep track of the factors and their quantities.

**Link to work:** 
https://www.freecodecamp.com/challenges/smallest-common-multiple
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 7: April 24, 2017

**Today's Progress**: Smallest Common Multiple challenge continued

**Thoughts:** Good lord, what a complicated mess. Mostly functional but having issues with translating from a hash property name to a 2D array value. Will probably move to an object for each number since the data to maintain is getting to be a juggling act without an object to encapsulate it all.

**Link to work:** 
https://www.freecodecamp.com/challenges/smallest-common-multiple
(Since these are small challenges, I won't post them all on github. When I get to the larger projects in a few more days they will go up here and maybe CodePen.)

### Day 8: April 25, 2017

**Today's Progress**: Smallest Common Multiple challenge, Finders Keepers challenge

**Thoughts:** Finally beat the bear! Smallest common multiple is down. And the next challenge had literally a one-line solution.

**Link to work:** 
https://www.freecodecamp.com/challenges/smallest-common-multiple
https://www.freecodecamp.com/challenges/finders-keepers
https://codepen.io/sixhops/pen/qrPZmg - My solution to the LCM challenge. DO NOT READ IF YOU HAVE NOT COMPLETED THIS ONE.

### Day 9: April 26, 2017

**Today's Progress**: Drop It challenge, Steamroller challenge, Binary Agents challenge

**Thoughts:** Pretty easy challenges today, comparatively. Got to write a recursive solution for Steamroller. Only two more challenges and then onto the Advanced section!

**Link to work:** 
https://www.freecodecamp.com/challenges/drop-it
https://www.freecodecamp.com/challenges/steamroller
https://www.freecodecamp.com/challenges/binary-agents

### Day 10: April 27, 2017

**Today's Progress**: Everything Be True challenge

**Thoughts:** Outside of this code, I learned a ton today by researching the answers to the Front End Developer Interview Questions on github.

**Link to work:** 
https://www.freecodecamp.com/challenges/everything-be-true

### Day 11: April 28, 2017

**Today's Progress**: Everything Be True challenge, Arguments Optional challenge, Validate US Telephone Numbers challenge started.

**Thoughts:** Finished the Intermediate scripting challenges and moved into Advanced. Learned that isNaN() will coerce a string into a number. Lame. Used typeof instead to see if something was a number or not.

**Link to work:** 
https://www.freecodecamp.com/challenges/everything-be-true
https://www.freecodecamp.com/challenges/arguments-optional
https://www.freecodecamp.com/challenges/validate-us-telephone-numbers

### Day 12: April 29, 2017

**Today's Progress**: Validate US Telephone Numbers challenge completed, Record Collection challenge.

**Thoughts:** Busted out two in an hour. At that rate I can finish advanced scripting in about 5 days (1 hour per day) instead of 50 hours.

**Link to work:** 
https://www.freecodecamp.com/challenges/validate-us-telephone-numbers
https://www.freecodecamp.com/challenges/record-collection

### Day 13: April 30, 2017

**Today's Progress**: Symmetric Difference challenge.

**Thoughts:** Finished a single today. Took several hours. Made liberal use of Chrome debugger. Initially my logic was correct and then I had a second, more concise idea which turned out to be partly wrong. But adding back in part of the original logic allowed it to work. This one was difficult to understand from the text. I needed to watch the linked video to have them explain the algebra behind these unions and intersections. Writing it out on a piece of paper helped too.

**Link to work:** 
https://www.freecodecamp.com/challenges/symmetric-difference

### Day 14: May 1, 2017

**Today's Progress**: Exact Change challenge.

**Thoughts:** More with objects. Adding an object to an array adds a reference to that object so if that object changes, so does the array's "copy" because it is actually a reference to the original object. Create a new object each time to push onto the array. Don't use one object and modify its values and try to push. it wont work.

**Link to work:** 
https://www.freecodecamp.com/challenges/exact-change

### Day 15: May 2, 2017

**Today's Progress**: Super secret app development

**Thoughts:** Began work on a new secret project. Spent time wireframing and pseudocoding the functionality. No code for it is online yet but I will post if it is okay with the client. Just taking a short break from the Camp.

**Link to work:** 
nothing but what is written on my notepad (made of actual paper)

### Day 16: May 3, 2017

**Today's Progress**: Super secret app development, resume

**Thoughts:** Layed out much of the HTML and CSS for the super secret project. Started working on the layout for my online resume.

**Link to work:** 
No link to this work until I show the potential client.

### Day 17: May 4, 2017

**Today's Progress**: Resume

**Thoughts:** Continued laying out the resume page. Added content from old resumes.

**Link to work:** 
Nothing online yet. I want to have this complete before I link it anywhere.

### Day 18: May 5, 2017

**Today's Progress**: OFF DAY

**Thoughts:** Slept for 3.5 hours instead of coding. Will use one of my days off.

**Link to work:** 

### Day 19: May 6, 2017

**Today's Progress**: Exact Change challenge (FreeCodeCamp)

**Thoughts:** Had to deal with the built-in float imprecision. Since I couldn't link in a library for handling decimals I ended up multiplying all currency values by 100 before processing and then dividing by 100 before output. Actually, mutiplying by 10 twice and dividing by 10 twice which, for some reason, did not screw up the variable's precision.

**Link to work:** 
https://www.freecodecamp.com/challenges/exact-change

### Day 20: May 7, 2017

**Today's Progress**: No Repeats Please challenge (FreeCodeCamp)

**Thoughts:** Oh lord. Spent the evening trying to reverse engineer a math formula for this challenge. Base case is done. The first exception (required by the tests) is about half done. Lots of weird cases to catch when you have two or more letters that can repeat.

**Link to work:** 
https://www.freecodecamp.com/challenges/no-repeats-please


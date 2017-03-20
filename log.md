# 100 Days Of Code - Log

### Day 0: January 5th, 2017 (Thursday)

**Today's Progress**: Continued work on database interaction.

**Thoughts:** It's a constant debate about what goes in the SQLiteHelper vs. what goes in the DataSource class. 

**Link to work:** [Simple Weight Grapher App](https://github.com/jdsandifer/SimpleWeightGrapher/tree/master/app/src/main/java/com/jdsandifer/simpleweightgrapher)


### Day 1: January 6th, 2017 (Friday)

**Today's Progress**: More database work on my app.

**Thoughts:** I'm really interested in seeing how well things work when I test it.

**Link to work:** [Simple Weight Grapher App](https://github.com/jdsandifer/SimpleWeightGrapher/commit/e6224a1cecbf7084ae1407f3b97701db2e364d9d)


### Day 2: January 7th, 2017 (Saturday)

**Today's Progress**: Started testing my database work.

**Thoughts:** I need to improve my database testing chops, but the app still works so that's good.

**Link to work:** [Simple Weight Grapher App](https://github.com/jdsandifer/SimpleWeightGrapher/commit/22234dc931f26ad6d550f4fdb0e125d4d1146b16)


### Day 3: January 8th, 2017 (Sunday)

**Today's Progress**: Continued testing my database work.

**Thoughts:** It was very exciting to see that the database is working correctly. Stress testing is next...

**Link to work:** No new commit - see above links.


### Day 4: January 9th, 2017 (Monday)

**Today's Progress**: Revised my method for getting the *day* of the year to get the *seconds* instead. (for faster testing)

**Thoughts:** Next is adding some unit tests and perhaps some mocking - the latter will be new, exciting, and possibly daunting. Until I do it - then it will just be cool.

**Link to work:** [Simple Weight Grapher App](https://github.com/jdsandifer/SimpleWeightGrapher/commit/fb3bbd649b9a6774ff23100b7efdc6fed71c781b)


### Day 5: January 14th, 2017 (Saturday)

**Today's Progress:** Today I practiced basic techniques for concurrency in vanilla Java. I'm starting a complete refresher on all of the possibilities and pitfalls to avoid so I'm better able to implement concurrency when it's applicable.

**Thoughts:** Had a few busy days and didn't get to coding so I have a gap in my 100 days. I think that'll be ok if I can get back on track. 100 days of coding will still be helpful even if it's not completely sequential.

**Link to work:** [Concurrency.java](https://github.com/jdsandifer/HackerRank/blob/master/Java/Concurrency.java)


### Day 6 - 8: Not Logged

**Progress:** I answered questions on Treehouse for both Android and Java on three different days. 

**Thoughts:** I realized that although this isn't work on projects, it is related to preparing for an interview and a job in development. Thinking quickly, discussing my approaches and solutions to problems, and helping coworkers will all be important for landing and keepiing a development position. So I'm going to allow it.


### Day 9: January 24th, 2017 (Tuesday)

**Today's Progress:** Today I worked on making the graph in my app correctly display real data - instead of my stand-in values. Converted my weight record to a singleton for easy global access and because it makes sense for it to be one.

**Thoughts:** Still in progress...app is freezing after initial load now. Singleton code seems like the obvious source, but the app gets past the initialization of it and freezes later...


### Day 10 & 11: January 25th & 26th, 2017 (Wednesday & Thursday)

**Today's Progress:** Answered more questions on Treehouse about Java.

**Thoughts:** I do want to make sure my question answering isn't keeping me from progressing on my apps, but it's a great way to stay actively thinking about Java and Android without having to get my development computer up and running. This probably means I need to get Android Studio working on my laptop so working on projects is as easy as answering questions...


### Day 12: February 5th, 2017 (Sunday)

**Today's Progress:** Started figuring out some Regex searches for a little project for a friend.

**Thoughts:** It's been a month since I started 100 Days of Code and I'm only on day 12. I'm not sure my leniency with the rules is as helpful as I thought, but it has kept me from quitting - so that's good. I also want to be flexible with the varying demands of my work schedule and other activities so it's hard to commit to coding every day.

But I probably should set my standards higher than they have been recently...

I definitely like my "just do some coding" variant of the "one hour of coding per day" rule, though. It's easy to get close to an hour if I just start, but harder if I have to block out a full hour - it seems more daunting as a full hour.


### Day 13: February 6th, 2017 (Monday)

**Today's Progress:** More Regex and I sketched out an outline for the code for my friend's project. Also started BibleStatistics repo.

**Thoughts:** I'm trying to decide about what kind of balance I want to strike between finishing the project and getting my friend the results quickly, and taking the time to really use unit testing, functional Java, etc. to make it very "professional" looking on Github.


### Day 14: February 8th, 2017 (Wednesday)

**Today's Progress:** Created the first Java class with basic file IO for the BibleStatistics repo.

**Thoughts:** So far so good.

**Link to work:** [BibleReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReader.java)


### Day 15: February 11th, 2017 (Saturday)

**Today's Progress:** Got the first Regex working to separate the text into books. Had to fix the text reading function in the process. 

**Thoughts:** Should be a lot smoother going forward.

**Link to work:** [BibleReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReader.java)


### Day 16: February 12th, 2017 (Sunday)

**Today's Progress:** Loaded up a new editing environment on my laptop to be able to code easier and more often. Started using that and taking the next step on my friend's project. 

**Thoughts:** Haha. Not as smooth as I thought. Bugs can be lurking anywhere, but that's what I'm here for I guess.

**Link to work:** [BibleReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReader.java)


### Day 17: February 13th, 2017 (Monday)

**Today's Progress:** Got Bible input, regex searching, text splitting, book object creation, and book statistics file printing all working for my friend's project! Then in the morning, finished printing text lists and csv files for both books and chapters. Almost done now!

**Thoughts:** Lots of weirdness in translating files: Different encodings and line terminations, weird symbols, and so on. I'll have to learn more about how to create the Bible text file correctly to start with *and* how to keep the text in the right encodings. Definitely feel like I can see the light at the end of the tunnel now, though. Just verse files to go and then revising for more professional presentation - tests, refactoring, etc.

**Link to work:** [BibleReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReader.java)


### Day 18: February 14th, 2017 (Tuesday)

**Today's Progress:** I added verse list creation, sorting, and file outputs. The basic Bible statistics program is now complete!

**Thoughts:** I'm going to add testing, and do some refartoring for design patterns and object oriented principles, but I'm most excited to work more on understanding encodings and how to detect them and use them. I'm especially interested in figuring out the best "portable" format for my text files and CSV's. (Encoding and newline code.)

**Link to work:** [BibleReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReader.java)


### Day 19: February 15th, 2017 (Wednesday)

**Today's Progress:** I added folders to better organize the Bible Statistics project.

**Thoughts:** Refactoring is next.

**Link to work:** [BibleStatistics](https://github.com/jdsandifer/BibleStatistics/tree/master)


### Day 20: February 16th, 2017 (Thursday)

**Today's Progress:** I added a folder for input files - including a new test file for testing how to determine a files encoding and new line terminator code.

**Thoughts:** I'm excited to get a stronger grasp on file encodings and line terminator!

**Link to work:** [input folder](https://github.com/jdsandifer/BibleStatistics/tree/master/input)


### Day 21: February 17th, 2017 (Friday)

**Today's Progress:** Got the first encodings test code working.

**Thoughts:** The problem is that all encodings worked on the same file...and then threw exceptions. I'll just have to keep trying.

**Link to work:** [EncodingReader.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/EncodingReader.java)


### Day 22: February 18th, 2017 (Saturday)

**Today's Progress:** Gave up on encodings test after more testing and some more research. There are libararies out there to help, but it's still just guessing the encoding based on character frequency or presenting the user with samples from which to choose.

**Thoughts:** A little sad that there's no easier or more bullet-proof solution, but it makes sense why there isn't.

**Link to work:** [BibleStatistics](https://github.com/jdsandifer/BibleStatistics/tree/master/src)


### Day 23: February 19th, 2017 (Sunday)

**Today's Progress:** Added jUnit to the project and started writing unit tests. Began with the Verse class.

**Thoughts:** I'm looking for a way to streamline my testing while sticking to my simplified command line and text editor setup. Might be good to try to use Gradle in this environment to gain a fuller understanding of how it works. A batch file (or bash script) might also do the trick and be a good skill-building exercise, too. 

**Link to work:** [VerseTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/VerseTest.java)


### Day 24: February 20th, 2017 (Monday)

**Today's Progress:** Added tests for the Chapter class and a file with the JUnit commands for copying to the command line.

**Thoughts:** One quarter of the way through the challenge! Feeling good now. It really helps to insist to myself that I get a little coding in each day.

**Link to work:** [ChapterTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/ChapterTest.java)


### Day 25: February 21st, 2017 (Tuesday)

**Today's Progress:** Added tests for the Book class and updated the Readme on GitHub.

**Thoughts:** Realized my links don't work anymore and went about fixing that... :(

**Link to work:** [BookTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BookTest.java)


### Day 26: February 23rd, 2017 (Thursday)

**Today's Progress:** Refactored a function out of the main program and into a new file - primarily to better allow for testing.

**Link to work:** [BibleParser.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleParser.java)


### Day 27: February 24th, 2017 (Friday)

**Today's Progress:** Finished refactoring Bible parsing functions to BibleParser.java. Also added a simple print line function and a command line argument reader.

**Thoughts:** Feels a little like I'm creating a Unix command! I.e. awesome...

**Link to work:** [BibleParser.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleParser.java)


### Day 28: February 25th, 2017 (Saturday)

**Today's Progress:** Refactored file formatting out of main and created FileFormatter.java for the purpose.

**Thoughts:** Need to see if the refactored code works now...but I am feeling good about my ability to refactor code without breaking it!

**Link to work:** [FileFormatter.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/FileFormatter.java)


### Day 29: February 26th, 2017 (Sunday)

**Today's Progress:** Refactored code compiles fine now. Also updated some todos I had left in the code because they're done now. Did some testing with for loops to determine when each argument gets called (init = once, test = before the loop, change = after the loop). Also tested pre-incrementing and post-incrementing variables in the test and change sections.

**Thoughts:** It may seem silly, but really understanding the fundamentals (for loops in this case) is one of the things that separates highly skilled people from the rest of the bunch. They can do the fundamentals better as well as do the awesome stuff.

**Link to work:** [FileFormatter.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/FileFormatter.java)


### Day 30: February 27th, 2017 (Monday)

**Today's Progress:** Added first test for FileFormatter.

**Link to work:** [FileFormatterTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/FileFormatterTest.java)


### Day 31: February 28th, 2017 (Tuesday)

**Today's Progress:** Got the first test for FileFormatter working.

**Link to work:** [FileFormatterTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/FileFormatterTest.java)


### Day 32: March 2nd, 2017 (Thursday)

**Today's Progress:** Added tests for BibleReader and BibleParser, and removed refactored methods (no longer needed in current class).

**Thoughts:** One third of the way there (almost)! It's going to be a long haul, but my GitHub is already starting to look a lot more complete (more green squares on my profile).

**Links to work:** [BibleParserTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleParserTest.java), 
                   [BibleReaderTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleReaderTest.java)
                   

### Day 33: March 7th, 2017 (Tuesday)

**Today's Progress:** Created a batch file to automate testing a little. Now I just drag the file to test onto the batch file and it compiles it, it's test file, and runs the test.

**Thoughts:** I've been sick for a few days so it's been hard to keep up. It's also taking significantly longer to get things done as I'm sure my brain is slow right now.

**Link to work:** [CompileAndTest.bat](https://github.com/jdsandifer/BibleStatistics/blob/master/src/CompileAndTest.bat)


### Day 34: March 8th, 2017 (Wednesday)

**Today's Progress:** Completed tests for BibleParser, and put refactored methods back into BibleParser (accidentally removed from the project entirely).

**Thoughts:** Tests look good, but aren't actually passing. I'll have to look into the Hamcrest matchers - need a deepEquals kind of thing.

**Links to work:** [BibleParserTest.java](https://github.com/jdsandifer/BibleStatistics/blob/master/src/BibleParserTest.java)


### Days 35 & 36: March 9th & 10th, 2017 (Thursday & Friday)

**Today's Progress:** I began and continued work on my Portfolio page on GitHub. This is definitely useful to my job search and it's also a good reminder about how to code markdown so I'm allowing it.

**Thoughts:** I'll have to go back and look at my refence portfolio sites, but I like the neat look of it so far. It should make seeing my completed projects easier for anyone looking at my repos.

**Links to work:** [Portfolio](https://github.com/jdsandifer/Portfolio/blob/master/README.md)


### Day 37: March 12th, 2017 (Sunday)

**Today's Progress:** Spent some time getting a virtual server up an running to test PHP coding work for my job.

**Thoughts:** It's nice having some "real" (job) coding work to do.


### Day 38: March 13th, 2017 (Monday)

**Today's Progress:** Spent 5 hours working on setting up the server at work and fixing some code.

**Thoughts:** It was anti-climactic because while we fixed some code, the server errored and will have to get a fresh install.

**Links to work:** [Portfolio](https://github.com/jdsandifer/Portfolio/blob/master/README.md)


### Day 39: March 14th, 2017 (Tuesday)

**Today's Progress:** Spent some time on PHP coding again and also tweaked some of my repositories to make more sense to the casual observer.

**Thoughts:** Trying to keep my GitHub activity squares green is a great incentive to do some coding each day, too.


### Day 40: March 16th, 2017 (Thursday)

**Today's Progress:** Spent some time on figuring out details of PHP for work: lazy logical operator evaluation, functions, references.

**Thoughts:** I love diving into the details like that.


### Day 41: March 17th, 2017 (Friday)

**Today's Progress:** Spent some time on PHP coding again at work.

**Thoughts:** Wish I had more time to code...


### Day 42: March 18th, 2017 (Saturday)

**Today's Progress:** More PHP coding again at work.

**Thoughts:** It's hard deciding on a coding style - especially for mixed PHP, HTML, JavaScript, and CSS in the same file.


### Day 43: March 19th, 2017 (Sunday)

**Today's Progress:** I started to apply what I've been learning from Kevlin Henney about good code and test naming. I'm going through the BibleStatistics project alphabetically and refactoring names in each file. I'm also adding variables for the regex to clarify their purposes.

**Thoughts:** I'm getting a handle on good naming, but still not sure about exact style - especially bracket placement. For now I'm sticking with standard Java style for that.


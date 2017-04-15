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

**Link to work:** [Portfolio](https://github.com/jdsandifer/Portfolio/blob/master/README.md)


### Day 39: March 14th, 2017 (Tuesday)

**Today's Progress:** Spent some time on PHP coding again and also tweaked some of my repositories to make more sense to the casual observer.

**Thoughts:** Trying to keep my GitHub activity squares green is a great incentive to do some coding each day, too.


### Day 40: March 16th, 2017 (Thursday)

**Today's Progress:** Spent some time on figuring out details of PHP for work: lazy logical operator evaluation, functions, references.

**Thoughts:** I love diving into the details like that.


### Day 41: March 17th, 2017 (Friday)

**Today's Progress:** Spent some time on PHP coding again at work.

**Thoughts:** Wish I had more time to code ... at home or at work.


### Day 42: March 18th, 2017 (Saturday)

**Today's Progress:** More PHP coding again at work.

**Thoughts:** It's hard deciding on a code style - especially for mixed PHP, HTML, JavaScript, and CSS in the same file.


### Day 43: March 19th, 2017 (Sunday)

**Today's Progress:** I started to apply what I've been learning from Kevlin Henney about good code and test naming. I'm going through the BibleStatistics project alphabetically and refactoring names in each file. I'm also adding variables for the regex to clarify their purposes.

**Thoughts:** I'm getting a handle on good naming, but still not sure about exact style - especially bracket placement. For now I'm sticking with standard Java style for that.


### Day 44: March 21st, 2017 (Tuesday)

**Today's Progress:** I did some work on my GitHub today.

**Thoughts:** There's a *lot* of work to be done on my GitHub: refactoring with better naming all over, adding tests to several projects, and cleaning up readme's so the projects are all clear to visitors.


### Day 45: March 23rd, 2017 (Thursday)

**Today's Progress:** Made some improvements (refactoring) to the group coding 
challenge that we used at a PDXNode meetup a while ago. Mainly renaming tests 
to provide more information and for clarity. Also added some tests to the first 
challenge and used better asserts there to set a good example for the rest of 
the challenges.

I submitted a pull request for the PDXNode leader's original repo and it got merged. 
I think that marks my first successful pull request on GitHub - a big day!

**Thoughts:** Still more work to do on my GitHub, but all these tweaks make it 
easy to keep getting green boxes at least!

**Link to work:** [Group Coding Challenge - Test.js](https://github.com/jdsandifer/group-coding-challenge/blob/master/test.js)


### Day 46: March 24th, 2017 (Friday)

**Today's Progress:** Tweaked my portfolio again and then added a Design 
Patterns repo to start taking notes on and practicing what I'm learning as I 
study the common design patterns. They make sense now, but I want to make sure 
I retain the information so it is easy to recall - on the job or for an 
interview.

**Thoughts:** I checked out [Enterprise Fizz Buzz](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) today. 
That was a good laugh! It was also good practice at reading code with lots of 
design patterns, abstraction, and encapsulation. Too much for the problem, 
obviously, but a good exercise nonetheless.

**Links to work:**  [Portfolio](https://github.com/jdsandifer/Portfolio/blob/master/README.md), 
                    [DesignPatterns](https://github.com/jdsandifer/DesignPatterns/blob/master/README.md)


### Day 47: March 25th, 2017 (Saturday)

**Today's Progress:** I got to work on PHP programming at work a lot today. 
So that was great! It was actually a pretty good approximation to what a 
programming job might look like, too. Discussing the issue list with a 
coworker, tackling the issue list, searching through code written by others,
fixing bad code style some to help read the code, but not too much as that 
distracts from actually fixing bugs, helping a coworker with a tangential issue,
and the list goes on. Good stuff. And I still like the programming.

I also added my Strategy Pattern notes and an interface to my Design Patterns 
repository.

**Thoughts:** I'm glad even crazy code and difficult bug fixing are not 
discouraging me from doing programming.

**Link to work:**  [Strategy Pattern](https://github.com/jdsandifer/DesignPatterns/blob/master/strategy/strategy-notes.md)


### Day 48: March 27th, 2017 (Monday)

**Today's Progress:** I got to work on more PHP programming at work today
as well as do some networking and computer setup for the presentation server.
A full day of programming related tasks!

**Thoughts:** I'm getting to see the not-so-fun side of working on software 
development projects and I'm not dissuaded from the field. It's good to have 
more realistic expectations, but still like the work overall. Yay!


### Day 49: March 28th, 2017 (Tuesday)

**Today's Progress:** I dove back into Android Studio and my Simple Weight 
Grapher app. That included lots of updating stuff, working on fixing Git 
integration, and code edits - mainly for style today (so it's more readable). 

I also got a nice-looking theme for Android Studio so I like the look of the 
code while I'm working on it. I'm using the Dracula IDE theme for dark colors 
and Monokai from Sublime (a port) for the actual code coloring.

**Thoughts:** It didn't take nearly as long as I thought it would to update 
everything. Although, Git integration isn't working perfectly - I'm using 
GitHub desktop to push commits to the repository on GitHub.

**Link to work:**  [Simple Weight Grapher](https://github.com/jdsandifer/SimpleWeightGrapher)


### Day 50: March 29th, 2017 (Wednesday)

**Today's Progress:** I fixed two issues - including one major bug - while 
under time and supervisor pressure at work today. I felt good about keeping the 
presentation file server on its feet, and my skills in PHP and reading through 
other people's code to find bugs.

It was hard-to-read code, too. That's not to say anything against those who 
wrote it. They taught themselves to code, created the system as a side project 
while juggling all their regular tasks, and got the project approved despite it 
being something completely new to our department (and field, essentially).

It's definitely an admirable feat. Bad code style and practices just happen to 
be a byproduct of how it was made. And I'm learning how to navigate it successfully.

**Thoughts:** I'm also learning how to react less to the terrible code practices 
I'm seeing. I've got a ways to go, but hopefully I can decrease the amount of 
"Wow, that's terrible!" responses and increase the "Hmm...I think this could be 
improved a bit." responses. Or even not respond at all some times and just file 
my ideas for improvement away for the next time I have the chance to fix it.

But man is that a tough growth process.


### Day 51: March 30th, 2017 (Thursday)

**Today's Progress:** I had to restart the server today at work and was able to 
do so with a minimal amount of fuss. I also continued bug fixing and code syling 
in PHP, JavaScript, HTML, and CSS at work.

At home, I added more design pattern definitions to my repo. I'm not prioritizing 
it as much as actual coding, but it's easy to work on it bit by bit when I only 
have a few moments for coding at the end of the day and nice to do since I can't 
put my work code on GitHub.

**Thoughts:** I'm excited about my growing comfort with Linux and the command line, 
even when my reputation is on the line. There's nothing like a time crunch when your 
boss is watching to help clarify the difference between what you know and what you 
think you know.

**Link to work:**  [Design Patterns](https://github.com/jdsandifer/DesignPatterns)


### Day 52: March 31st, 2017 (Friday)

**Today's Progress:** I got Espresso installed in my SWG project and wrote my first 
test. 

**Thoughts:** It's a pretty straightforward setup - just got use it more and more so I'm 
comfortable with it and I know some of the tricks to test harder things.

**Link to work:**  [Espresso Test #1](https://github.com/jdsandifer/SimpleWeightGrapher/blob/master/app/src/androidTest/java/com/jdsandifer/simpleweightgrapher/WeightUITest.java)


### Day 53: April 1st, 2017 (Saturday)

**Today's Progress:** More additions to my Design Patterns repo.

**Thoughts:** It's going to take a while to finish this repo...

**Link to work:**  [Design Patterns](https://github.com/jdsandifer/DesignPatterns)


### Day 54: April 3rd, 2017 (Monday)

**Today's Progress:** Got the Espresso test working now - it passes now. I also did some refactoring (renaming).

**Thoughts:** Test naming is hard even if you have a lot of good ideas about how to name stuff.

**Link to work:**  [Espresso Test #1 = Passing](https://github.com/jdsandifer/SimpleWeightGrapher/blob/master/app/src/androidTest/java/com/jdsandifer/simpleweightgrapher/WeightUITest.java)


### Day 55: April 4th, 2017 (Tuesday)

**Today's Progress:** Did a bunch of coding at work and a little work on design patterns at home.

**Thoughts:** Just wish I could do more coding at work - it's fun to see the results of my work!

**Link to work:**  [Design Patterns](https://github.com/jdsandifer/DesignPatterns)


### Day 56: April 5th, 2017 (Wednesday)

**Today's Progress:** I worked on the actual code in my strategy design pattern folder. 
Just have to test it out now.

**Thoughts:** Working on actual code is so important! I know a bunch about patterns, 
but actually using interfaces, etc. takes practice to remember all the syntax and so on.

**Link to work:**  [Design Patterns](https://github.com/jdsandifer/DesignPatterns)


### Day 57: April 7th, 2017 (Friday)

**Today's Progress:** I read the rest of the Pragmatic Programmer during downtime at work today. 
Then I applied the JavaDoc and comment suggestions from the book to my design patterns repo.

**Thoughts:** I'm more and more curious about how to decide how much information should 
be conveyed in variable and function naming vs. comments and JavaDoc, etc. Obviously, 
the more information in the code, the better, as that information is most guaranteed to be 
accurate. But beyond that it gets trickier to decide.

**Link to work:**  [Design Patterns](https://github.com/jdsandifer/DesignPatterns)


### Day 58: April 8th, 2017 (Saturday)

**Today's Progress:** Today at work I was able to tackle some batch file programming 
during downtime. I learned a bunch more about general syntax and the commands/programs 
to change users, network configuration, and file sharing. The end result will be an 
automated setup process for the file server clients so getting all the computers up and 
running will be a lot easier.

**Thoughts:** It's easier and easier to learn new things. Batch file programming just 
took a lot of looking up syntax and the commands needed.


### Day 59: April 9th, 2017 (Sunday)

**Today's Progress:** I took an IKM JavaScript test today. That also led to a bunch of 
post-test studying to understand the questions I wasn't so sure about. Lots of good practice
and learning!

I also tweaked my portfolio a little.

**Thoughts:** I did ok on the test: 86% and 69th percentile worldwide. Considering JavaScript 
is not my primary language right now, I felt pretty good about that. Better than two-thirds of 
test takers and without any industry experience or college study in the subject...not bad. And 
from an absolute score standpoint, I would have gotten a solid B in the subject if it were a class.
IKM also listed my score as "Better Than Average" and just below the mark for "Top 25%."

**Link to work:**  [Portfolio](https://github.com/jdsandifer/Portfolio/blob/master/README.md)


### Day 60: April 10th, 2017 (Monday)

**Today's Progress:** I took an IKM Java test today. I did pretty well on it, too. And it led to 
more post-test studying to figure out the answers to some of the tricky questions I wasn't sure 
about.

**Thoughts:** I was very surprised at home some really poorly styled code actually compiled and 
ran without problems - even working the way you might expect without weirdness.


### Day 61: April 11th, 2017 (Tuesday)

**Today's Progress:** I took an IKM Android test today. And more post-test studying and trying out 
weird code in an online REPL: [repl.it](http://repl.it/).

There were also some glitches in the test which I'm afraid affected my score. I got asked questions 
that I had already skipped once which could easily increase have added negative points to my score.

**Thoughts:** Even though I think the testing glitches affected my score, there were also some things 
I knew nothing about. Having not used those features, I didn't need to know anything about them. I 
think this is one drawback of these general knowledge tests. I could be an awesome Android programmer, 
but if I've never used one item then my score would be lower than someone who's at least seen all of 
the different features they ask about.


### Day 62: April 12th, 2017 (Wednesday)

**Today's Progress:** I worked for about an hour at work on code after finishing my assigned tasks 
for the day. I was finishing my work on batch files to setup, teardown, and undo the network setup 
for each computer we use in the file server setup (3 separate files).

**Thoughts:** I enjoy learning new languages and was consistently surprised how fast it was and how 
few commands it took to set everything up. Fun stuff!


### Day 63: April 13th, 2017 (Thursday)

**Today's Progress:** I took the Amazon online assessment test today. It was a great coding test 
with unit tests that showed whether you were achieving the goal of the code. Some tests were 
visible so you could see what wasn't working and some were hidden to test your ability to figure 
out some edge cases on your own.

**Thoughts:** I thought I did pretty well with all code compiling and all but 4 unit tests passing. 
However, the recruiter said I did very well! So that was fun to hear.

It's really great to see a company doing recruting the right way: Start with a quick skills assessment 
based on actual work, not a multiple choice test. Then move to talking in person and finding out more. 
No looking at the resume and just passing up on candidates because they don't fit a mold. Good to see 
that some companies know how it's done!


### Day 64: April 14th, 2017 (Friday)

**Today's Progress:** I worked for a solid seven hours on code at work. It was great! We started 
with some good whiteboarding to decide on the design of the feature we were working on. Then we 
each took a part and started making it work. As we went, we changed how the interface was designed 
as we saw how things were working. It was a pretty smooth and productive process!

**Thoughts:** It was fun to really see how team programming could work. I wonder how similar 
or different it will be on an actual software development team that does this full time. I'm 
definitely excited to find out!

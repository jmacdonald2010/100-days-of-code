# 100 Days Of Code - Log

### Day 16: February 19, 2021

**Today's Progress**: Small progress today on the shopping list app. Add a select store spinner (dropdown menu) that, at this time, only prints the store chosen and refreshes the main screen. Next steps are to filter the other dropdowns accordingly, and add recently added items to the 'add items' screen. After that, it's time to port a rough version to iOS.

**Thoughts**: Kinda getting tired. Made some progress on my shopping list app today, but starting to feel the pull to work on other projects before this one is complete. I spent a fair bit of time today looking into ways to change the first python project I built to make it more efficient and get more data. When I built it originally, I didn't understand JSON, so I ended up parsing the API data as a giant string using a regular expression I found on stackoverflow. Now, I realize I could clean it up by using the JSON library. I also have been considering other ways of getting my data apart from the rapidAPI Fidelity Investments API. Unfortunately, Fidelity doesn't have a public API, and webscraping a dynamic site that requires login with two-factor authentication is excetionally difficult (if not outright prohibited by the T&Cs). Currently looking into ways to just automate FireFox browsing their site and extracting the HTML to parse it, which would be a fun little project. And not terribly related, but Fridays are not terribly productive for me, because, well, it's Friday, and I typically spend my mornings before work getting my finances in line, so I don't get the opportunity to do coursework, but it is also Friday, and I do need some time to not work.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 14, 15: February 17-18, 2021

**Today's Progress**: Completed several lessons in the data analysis course. Only a few more lessons before it's on to the projects. Added new features to my shopping list app. Working on getting a bootable drive with the latest macOS.

**Thoughts**: Had a very productive day yesterday, got a lot of coursework done, and made some decent strides on my project. I decided since I was going to have some free time I would start on creating a bootable macOS Big Sur drive. I've hit some unexpected roadblocks with it, and now I'm spending my evening tonight (2/18) working on getting that working. I'm also realizing that I have a lot of junk on the hard drives in my desktop, so I think on Sunday I may spend some time cleaning those out. Although it's not exactly coding work, it's work that supports coding, so I guess that counts. 

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress
freeCodeCamp course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/reading-data-introduction

### Day 13: February 16, 2021

**Today's Progress**: Completed a couple more courses in the data analysis course. Added functionality to the add item button on the add item screen to refresh the main screen when a new item is added. Added a settings dropdown with a delete all button with a popup warning. 

**Thoughts**: I watched through some tutorials today on object oriented programming python again. What I realized I needed was to turn the methods in my MainScreen class to class methods instead of instance methods. I realized this won't be terribly problematic for this project because there will only ever be one instance of the MainScreen class at a time. To get the refresh main screen method to work from the AddItems class, I had to create a global MainScreen object in my MainApp class. I know that global variables are supposed to be dangerous things that are to be avoided at all costs, and I will fully acknowledge that I do not completely understand these dangers, however, using globals makes my app work, and I have seen several other examples using kivy where others have used global variables. Feeling more confident on using OOP in python now, although I do need to study the basic concepts of it more. Also thought up a new simple project: a basic python app that reads recipes, stores as either HTML or PDF files from a local database. My wife and I have used countless recipes we've found online over the years, and as is the nature of the internet, sometimes these recipes disappear forever. Essentially, this would just be a more eco-friendly version of a printed recipe book. Once I get the shopping list app compiled to iOS I think I'll give this a shot, just to make our lives easier.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress
freeCodeCamp course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/reading-data-introduction

### Day 12: February 15, 2021

**Today's Progress**: Completed a couple of courses in the python data analysis course. Added a grid layout to the add item menu on my shopping list app. Trying to figure out how to refresh the main page when using the add items feature on the add items page.

**Thoughts**: Every time I think I understand object-oriented programming, I run into something that makes me realizing I still have much to learn. I know that there should be a way to call on a function in my MainScreen class from my AddItems class, but I am struggling to figure out the best way to do it. I feel comfortable saying I understand the basics of OOP (although I could be a bit more solid on inheritance), but I definetly need some more practice with creating and using objects. Not sure if I need to spend more time studying OOP or if I need to spend some time building projects that utilize it more thoroughly.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress
freeCodeCamp course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/data-cleaning-and-visualizations


### Day 11: February 14, 2021

**Today's Progress**: Not only are the toggles working the way they are supposed to, now the whole shopping list populates under all of the categories. Still quite a bit more work to do get all of functions I'd like implemented, but I think (famous last words) that it's all downhill from here.

**Thoughts**: I realized at the beginning of the day when I started working that my code was not as robust and scalable as it should be; in order to create each dropdown, I'd need a whole function dedicated to each one, which would involve a lot of duplicate code, which isn't a great thing. In addition to that, I would be stuck with the departments that are hard-coded into the app, which is also something I didn't want. I think that getting this within a base workable range won't be terribly difficult from here, but getting all of the functionality I originally wanted (change order of departments for different stores, exclude some departments for some stores) would take a lot of work and would make the project pretty complex. What I'm planning on doing is staying true to the reason I started this project, which is to make my grocery shopping experiences easier. Ultimately, today was a very productive day, although getting stuck earlier in the rebuilding of most of the main.py file was incredibly frustrating, it all managed to work out.
 
### Day 10: February 13, 2021

**Today's Progress**: Finally figured out my toggle button problem. Code isn't necessarily terribly tidy, but the toggle change the collected value in the database and that's good enough for me.

**Thoughts**: Didn't have as much time to code today as I would've liked, but with Saturdays being the day I work late, it's not terribly surprising. Honestly, I don't think I even got an hours worth of coding in (probably pretty close, or at least an hour if you're not counting moments where I'm talking with others and not coding), but I feel like it counts as a day in 100 Days of Code because I solved another big problem. In other news, I'm starting to get interested in pygame (and by that, I mean I started reading into a bit during my breaks this afternoon). Since my goal is to change careers into software development/data analysis, I need to become solid on the basics of python, but I like the idea of potentially using pygame to create some interactive audiovisual content, or maybe even some kind of experimental video game, that is made through code and can easily be distributed to people. I think when I have my fundamentals done better and my other projects (shopping list and stock prediction) are done I may explore this route. Maybe it would be better to learn C# and unity to do so, but perhaps pygame can do what I need it to (which wouldn't be terribly much). We'll find out when we get there I suppose.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 9: February 12, 2021

**Today's Progress**: Found the beginning of the solution of my toggle button issue for my shopping list app. It's still very problematic, but I've found the start to the solution. 

**Thoughts**: Didn't get to do any coursework today, but that's okay, but that was expected, as today was payday and I needed to spend my time this morning dealing with personal finances and budgeting and all that. On the note of code though, I am relieved that I have finally began to find the solution to my toggle button issue. There's still a lot of work to do (there seems to be an issue where the # of times the thing prints increases every time something is pressed? also getting it to return the keys might actually not be super straight ahead?). Regardless, I'm glad to have made just the slightest breakthrough today on this issue. I don't imagine I'll have a lot of time to work this weekend (I need to do a lot of housework this weekend), but hopefully I'll get to properly writing to the database with these toggle buttons by next week.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 8: February 11, 2021

**Today's Progress**: Completed a couple more courses in the python data analysis course. Progress with the shopping last app wasn't much for the amount of time working on it. Toggle buttons are still problematic.

**Thoughts**: Being stuck on the same problem for multiple coding sessions is incredibly frustrating. I need to use for loops to create the labels and buttons in my shopping list app, so I also need to use a for loop to bind the on_press action to that button (as far as I'm aware), however, kivy always assigns the same binding to all buttons from the last iteration from the for loop. This feels like a fairly deep problem that is going to take a lot of digging to figure out, because as of right now, I am lost for solutions on how to actually get these toggle buttons to work right. Feels like I'm gonna be stuck on this frustrating problem for a few days.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress
freeCodeCamp Python Data Analysis course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/data-cleaning-with-dataframes

### Day 7: February 10, 2021

**Today's Progress**: Worked a good bit on the shopping list app. Got the accordion item dropdown menus to populate with data from the database. Trying to figure out how to use kivy toggle buttons to write if the item has been collected or not.

**Thoughts**: Didn't have as much time to work early in the day as I would've liked. Typically, I like to do the course work in the morning before work, and the project work after dinner in the evening. Had to run a bunch of errands this morning, so the course work didn't happen, but I feel like I'm making solid progress on this shopping list app, and maybe, just maybe, it could be finished at the end of the month (whether or not it ends up on iOS depends on my ability to gain access to macOS Big Sur, as I'm running High Sierra largely for music purposes). 

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress


### Day 6: February 9, 2021

**Today's Progress**: Got through two more of the lessons in the freeCodeCamp python data analysis course and learned some useful information on pandas dataframes. Worked a bit more on my shopping list app, and decided to actually utilize pandas dataframes as a way to make organization of my data easier.

**Thoughts**: I didn't get as much development on my shopping list project done today as I would've liked. I didn't get a free minute to sit down and work on my project until after 10:30 PM, and I'm trying to go to bed earlier because I haven't been sleeping enough recently. Honestly, if I weren't doing 100 days of code, I likely would have just put work on this project off until tomorrow night, but I hadn't quite gotten in an hour today yet, and honestly, it feels nice to have gotten some work done, even if it was just a little bit.

**Links to work:** Shopping List: https://github.com/jmacdonald2010/shopping-list/tree/in-progress
freeCodeCamp: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/pandas-creating-columns

### Day 5: February 8, 2021

**Today's Progress**: The add item screen now writes properly to the database and clears fields as it should. It also seems like it auto-clears and stops users from creating errors. I've figured out how to create the accordion dropdown widgets with Kivy, but I'm running into some weird GUI overlapping issues. Suspecting it may be a background thing, but either way I'll find out soon enough.

**Thoughts**: Creating an app w/ a GUI is a completely different beast from the rest of what one learns about coding. Getting my info to display properly is honestly not too difficult, but getting all of the menus and features to work properly in a graphical-user way is a new experience for me (the GUIs I made with Max/MSP as a grad student were usually pretty rough). Although this project has been a lot more intense than I expected, I am realizing that I actually really like writing code.

**Links to work:** https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 4: February 7, 2021

**Today's Progress**: Worked more on my shopping list today and got it to write to the database. Still working on the best way to auto-clear the entry fields after adding the items, but it doesn't seem like it should be too difficult a problem.

**Thoughts**: Now that I've sorted out my dropdown issue, I feel like I'm making quick work out of this project, although in reality, I still have a lot of work ahead of me. It's quite amazing how something so simple can have so many small parts that require so much time. I'm not necessarily complaining about it, but when I set out on this project there's a lot I've had to deal with that I didn't imagine I would. Either way, I'm enjoying working on it, and enjoying coding in general. Also, I remembered that my monitor mount can turn one of my screen to a portrait orientation, which is a nice change.

**Links to work:** https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 3: February 6, 2021

**Today's Progress**: Didn't get to do any of the data analysis course today, but got about an hour on my shopping list project, and I finally got my dropdown menus to work! 

**Thoughts**: The debugger is super powerful tool and quite honestly a lifesaver. It turns out the root of my dropdown menu problems was that when I was creating a list of results from the database call to get things such as units, store departments, and stores, the elements in the list were not being stored as strings, but as single-element tuples containing the string. Ultimately, the problem was fixed with the addition of three characters. The feeling of relief after solving what had previously been a large problem is a powerful one. Also, never underestimate the power of just going to bed or doing something to take your mind off the issue can do to help. Feeling pretty satisified and looking forward to continuing on the project. 

**Links to work:** https://github.com/jmacdonald2010/shopping-list/tree/in-progress

### Day 2: February 5, 2021

**Today's Progress**: Completed a couple more lessons in the data analysis course. Trying and build a dropdown in my shopping list app using values from the database (so the item entries can be normalized) and finding every way that doesn't work. I'm not sure what I'm doing wrong but this is exceptionally difficult to accomplish in kivy using multiscreens.

**Thoughts**: Trying to figure things out with kivy is incredibly frustrating. I'm not sure if I'm not searching for the right things when trying to google the problem, or what it is, but I cannot for the life of me figure out how to build the kivy dropdown I need, neither with spinners or dropdowns. It is incredibly frustrating to spend several hours trying to solve one problem and feeling like I'm stil exactly where I started when I opened up the editor today. Going to keep searching for some kind of solution.

**Links to work:** freeCodeCamp course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/pandas-dataframes
shopping list app (currently non-functional on the in-progress branch): https://github.com/jmacdonald2010/shopping-list 

### Day 1: February 4, 2021

**Today's Progress**: Completed a few more lessons in the freeCodeCamp 'Data Analysis with Python' course this morning. Got a couple of buttons working in my shopping list app.

**Thoughts:** Learning Kivy almost feels like learning a new language entirely. Getting working widgets isn't easy, but I'm getting there. Slighly confused on how to approach the subclasses of the Kivy objects vs. writing things in the .kv file. The next day I work on the project I'm going to try to build some dropdown lists, which will certainly be a challenge.

**Link to work:** Shopping list app (see the in-progress branch): https://github.com/jmacdonald2010/shopping-list 
freeCodeCamp course: https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course/pandas-introduction


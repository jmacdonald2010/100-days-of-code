# 100 Days Of Code - Log

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


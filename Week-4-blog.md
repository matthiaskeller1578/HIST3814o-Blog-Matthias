## Week 4 Blog

This week we are looking into wrangling data, while also looking at sources from the Republic of Texas images. 
This week we are going to be building upon what we learned last week, which I belive will be a bit challenging as I found difficulty with last weeks exercises. However, I am excited to learn about the Republic of Texas, as I find its history to be interesting! I have always wanted to learn more about Texas' history, as I recently foud out that some of my ancestors were the original settler and founders of Keller, Texas. What a great way to incorprate my intrest of Texan histroy and digital history!

What I learned this week about wrangling data, has been been very interesting and benificial. I thought that it was really cool how the program was able to identify words that look similar and the ability to merge them together. The program identified similar names and allowed me to merge the names together. It is similar to how when you search for something online that it can identify something similar eventhough it is spelled wrong. This is valuable in studying hisotry, as names of places change over time, and so does spelling. Not only does it change but sometimes it can be hard for hisotirans to decifer spelling, therefore having a program which can identify similarities is beneficial for historians whom might seek to find how things are related. This system helps to connect the dots and show the relationship between particualrs.

### Reading: Space, Nation, and the Triumph of Region: A View of the World from Houston

The article by Cameron Blevins, examines how a symbol or geographical area can represent a certain idea or place. Blevins uses digital history to compile the locations mentioned in news papers across the United States to determine what place was emphasized and how that altered the perception of that place. I found the article to be a bit boring at first, but once I completed the exercises for this course and went back and re-read the article it all really made sense. I found it to be particually interesting how we can digitalize sources, and then have them develop data to examine hisotry. I have never had to do "data cleaning" persay in other classes, but I have noticed in PDF's that some words look like `J0hn` instead of `John`, and I had to determine what it meant. 
I think that some historians do nt talk about this kind of work as I would persume that it has the ability to weaken the legitimacy of the claim, as you are merging words that look similar or have similar conotations which might not be valid in order to simplify the source.

### Commands and Learning objectives
To start with learning about wrangling data, we first read over __textbook moduel__. I found it to be a bit confussing to follow, but defenitly a good read to understand what we are trying to do this week!
One of the first commands that I entered into DHbox this week was: 

`curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt`

The `curl` informs DHbox to download the link that I provided, and the `>` tells DHbox to put it in a new file called `texas.txt`
Once I had downloaded this file to my computer, I opened it in a text file to delete all of the unwanted information which I found easier to do than going through the whole entire file on DHbox. I then reuploaded it. 

The command:
`grep '~' texas.txt > index.txt`
makes everything so much easier! WHen I first read the instructions I thought that I would have to go through all of `texas.txt` file to remove lines without `~` but instead I was able to get grep to do it for me! 


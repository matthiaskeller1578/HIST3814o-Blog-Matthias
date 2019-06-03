## Week 4 Blog

This week we are looking into wrangling data, while also looking at sources from the Republic of Texas images. 
This week we are going to be building upon what we learned last week, which I belive will be a bit challenging as I found difficulty with last weeks exercises. However, I am excited to learn about the Republic of Texas, as I find its history to be interesting! I have always wanted to learn more about Texas' history, as I recently foud out that some of my ancestors were the original settler and founders of Keller, Texas. What a great way to incorprate my intrest of Texan histroy and digital history!

What I learned this week about wrangling data, has been been very interesting and benificial. I thought that it was really cool how the program was able to identify words that look similar and the ability to merge them together. The program identified similar names and allowed me to merge the names together. It is similar to how when you search for something online that it can identify something similar eventhough it is spelled wrong. This is valuable in studying hisotry, as names of places change over time, and so does spelling. Not only does it change but sometimes it can be hard for hisotirans to decifer spelling, therefore having a program which can identify similarities is beneficial for historians whom might seek to find how things are related. This system helps to connect the dots and show the relationship between particualrs.

### Reading: Space, Nation, and the Triumph of Region: A View of the World from Houston

The article by Cameron Blevins, addresses 


On your blog, reflect on any data cleaning you've had to do in other classes.

Why don't historians discuss this kind of work?
What gets hidden, what gets lost, how is the ultimate argument weaker as a result?
Or does it matter? Make reference (or link to) key annotations, whether by you or one of your peers, to support your points.


### Commands and Learning objectives
To start with learning about wrangling data, we first read over ______ textbook moduel. I found it to be a bit confussing to follow, but defenitly a good read to understand what we are trying to do this week!
One of the first commands that I entered into DHbox this week was: 

`curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt`

The curl informs DHbox to download the link that I provided, and the > tells DHbox to put it in a new file called texas.txt
Once I had downloaded this file to my computer, I opened it in a text file to delete all of the unwanted information which I found easier to do than going through the whole entire file on DHbox. I then reuploaded it. 

The command:
`grep '~' texas.txt > index.txt`
makes everything so much easier! WHen I first read the instructions I thought that I would have to go through all of texas.txt file to remove lines without '~' but instead I was able to get grep to do it for me! 


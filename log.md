# 100 Days Of Code - Log

### Day 0: May 18, 2019

**Today's Progress:** Read chapters 7 and 8 in "Clean Code" ("Error handling" and "Boundaries"). Finish `Common table expressions using WITH` in Team Treehouse

**Thoughts:** The point to handle errors at the end of a function in stead of on location fits very well with my own experiences. I have had to do a few `do-catch` clauses lately and the really mess up the code (in my opinion). Another point is the `never return NULL` in a function. I find his arguments interesting, but at the same time I'm not completely sure agree with it (when it comes to swift). It is a point I will have to follow up on.  
The chapter on "Boundaries" was a bit abstract in my opinion, but one detail do I take from it; The idea of writing `learning tests`. It is an approach I have used a few times in the last month or so, and I want to use it more in the future. One of my issues with writing tests has been that the keep failing on Linux, I did however find the issue the last time I wrote tests, so I hope this will not be a personal blocker in the future.  
I have been working a lot on extending my understanding of SQL in the first few months of 2019 and although I have been a bit lazy with practising in my free time the last two months I have had to use it a lot at work lately. Today I practiced a to me new feature in SQL, `CTE - common table expressions`. To sum it up, it is to move subqueries out into separate expressions and then use them in the final query. A pretty powerful feature.

**Link to work:** [Common table expressions using WITH](https://teamtreehouse.com/library/common-table-expressions-using-with)

### Day 1: May 19, 2019
**Today's Progress:** Do lecture on `SQL - Set operations`, read newsletter from XXX [To be added]

**Thoughts:** Today I practiced a few new features of SQL, namely `set operations`. They are pretty cool when you want to combine content from different yet similar tables. The processes are pretty straight forward so there was not really any barrie to overcome, but they did make me think about content I could share on instagram... I see a lot of profiles about HTML, CSS, Javascript, and even some Android, but Swift and especially SQL are underrepresented and could be a direction I could go. I have also started thinking about a small project I want to play around with, hopefully using Vapor 4, so I can learn that, but if the launch is too far out I'll have to start with Vapor 3 and migrate it later.

### Day 2: May 20, 2019

**Today's Progress:** Read chapter 9 in "Clean Code" ("Unit Tests")

**Thoughts:** I find myself having a growing interest in writing tests. I have gotten to write a few unit test for my latest project, and find myself better understanding how they function. I would however like to get an understanding for the more complicated tests, where the request or even the whole database is taken into account. I am however not there yet and for now I will focus on writing more unit tests for key algorithms. Another type of test I find very interesting and want to use more is the learning tests (which are outside the scope of the chapter I just read, but still very relevant...). Getting to know a service or package by the use of tests is a very natural approach and also makes sense in the greater scope of making sure that your code doesn't break because you updated your dependencies...

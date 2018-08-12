# TED analysis

I love TED talks. Really. So much that I wrote an [an entire blog post about this project](http://projects.rajshrimali.com/2018/03/ted-analysis.html). Here's the long-and-short. 

Each TED Talk has a few tags, as speakers tag it with related concepts. I realized that these tags could be used to construct a network of TED talks, and that network could be used to understand TED Talks in a way that had not previously been done. So, I first did some basic 
data analysis on the talks, and then linked them together with NetworkX to see what I could discover. Finally, I did some language analysis 
on the transcripts of the TED Talks to see if there was anything there. I found 

- The number of tags you have doesn't relate to how well your video does, sorry. 
- However, if you talk about something that's "happy", you'll have a higher probability of doing well compared to talking about something that is "sad". 
- There are 5 categories of TED Talks. These aren't intentional, it just so happens that there are strong subject-ties that naturally happen. 
- There are some typical arcs of talks that are ever present


I'm relatively new to d3.js and know it can be tough getting started as a lot of bl.ocks and tutorials don't have what I would consider adequate comments.  

One of the first real-world problems I had to tackle with d3 was a donut chart (which would eventually need to be dynamic).  
I flew around stackoverflow, google, bl.ocks, and everything inbetween trying to get my head around how to make one. I eventually got something up and running but the code was a bowl of spaghetti and I had *no* idea how it was actually working.  

What I decided to do in the end was to start with a clean slate and build the pieces one-by-one. **I have been helped immensely by [juancb](https://bl.ocks.org/juan-cb)'s [bl.ock](http://bl.ocks.org/juan-cb/1984c7f2b446fffeedde) and the [Pie Chart Update series](https://bl.ocks.org/mbostock/1346395) by Mike Bostock.**  

Two of the main goals I wanted to achieve with making this were:
1. **Make the chart [reusable](https://bost.ocks.org/mike/chart/)**. Which, in my opinion, is one of the most important concepts in d3.
2. Make it **using d3 v4**, as most tutorials I come across are still in d3 v3.

Going through the process of making a chart reusable really helps in understanding how all the pieces fit together and boosts your understanding of how charts are constructed.  
  
I worked through the tutorials mentioned above until I understood (pretty much) every line of code. I went to town on the comments because:
* I will be very thankful for it in 6 months time.
* I hope it will help out someone else in my position 3 months ago.

**This is my first bl.ock** so please let me know if there are any issues or things I can improve on.  
I am also working on a dynamic, updating version of this so I will add and link that when it is done.
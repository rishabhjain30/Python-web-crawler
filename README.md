# Python-web-crawler
This is a Python based web crawler that uses Pagerank to rank search results. Build it using the foundation Python course on Udacity.

The inputs needed are :

Seed Page - This is the page, from which it starts crawling the web. 

Search term - The term you want to search. Soon, I will add support for querying of multiple words, but for now, give a single word

eg:is

Maximum depth - This is the number of links to crawl completely. It would take 30 second for first link and for second link 60 seconds and it keeps on doubling. So, maximum 10 links are more than enough, I would say

eg:10

After you give the above three inputs, the program starts running. It may take a lot of time, to crawl depending on the depth you have specified. So the depth number, will be visible, decrementing itself, when ever a link is completely crawled; so that when it reaches 0 you know the crawling ended.

Also, I used the page rank algorithm (compute_ranks module). The page ranks are displayed alongside the links after the search results are shown. Then the program sorts them, and presents the sorted results.

# WebCrawler
Web crawler Java and Python

Web Crawler using java

Web crawler - Crawler starts with root page and starts crawling to other pages by connecting to the links specified in the root links and gathers links in other pages and doest it in repetitive fashion . The unique thing to be noted is already visited url is omitted by the crawler . 

Tech specs
Programming language - java (8)
Dependecies - JSoup

Algorithm
I/P
provide the root url to be crawled
checks if the link is already present in the set of list ,else it is added and url connection is made and other href links are fetched and recursive call. Finally the set will hold  the unique 
set of urls visited

O/p

List of crawled links under the specified domain is displayed.



Python - used BeautifulSoup4.6 to crawl the web sites
       - version 3.6.3 used
I/P - URL to be crawled is added in the program.
O/P crawled urls are displayed

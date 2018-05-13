# web-crawling
A web crawler (also known as a web spider or search engine robot) is a programmed script that browses the World Wide Web in a methodical, automatic manner. This process is called as web crawling or spidering. ... Moreover, the spiders or crawlers are used for automating maintenance tasks on the web site.

# This is a small python script written for gathering links present on a web page. It consists of five modules . 
General : This module handles file operations. Create dir, create a text file and read, write in this text files. where crawled links data           are written in text files.

Domain : This module parse url. located specified URL.

Link_finder : This module collect all links of html page <a>
  
Spider : This module implements all written module general, link finder, domain.

Main : Main module take project name, the domain name of the web page. Also, create parallel processes for faster web-crawling.

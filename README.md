# Crawler-for-Quora
This is used to crawl data from Quora based on the Quora topic specified by the user

### Install the libraries:
pip install beautifulsoup4

pip install requests

## Running the program:
python crawler.py

## Description: 
1.	This program gets user input a quora topic as user input and crawls quora.com . 
2.	If the specified topic exists it crawls the questions related to the topic from the topics page. 
3.	Then it retrieves the hyperlinks of those questions and crawls the answers to those questions with the number of upvotes for the answers. 
4.	Finally it writes all the crawled data into a file. 

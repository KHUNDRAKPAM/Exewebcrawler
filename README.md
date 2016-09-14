# Exewebcrawler
webcrawler

In this file, the goal is as the following:
Given a root URL, "wipro.com", return all pages that contains a string "wipro" from the wipro.
A typical crawler works in the following steps:
1.	Parse the root web page ("wipro.com"), and get all links from this page. To access each URL and parse HTML page, I will use JSoup which is a convenient and simple Java library.
2.	Using the URLs that retrieved from step 1, and parse those URLs
3.	When doing the above steps, we need to track which page has been processed before, so that each web page only get processed once. This is the reason why we need a database.
4.	Create a Database call Crawler, in which contains table wiprorecord, named as per our convention.
5.	In project we import mysql connector and jsoup.1.9.2.
For build and run, as normal java project we can clean and build then Run the project. In my example, I did it in my local system.


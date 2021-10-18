# HW3 RPA with Python
 
Used libraries

selenium - web-browser automation
pandas - work with datatables
smtplib \ email - email creating and sending
wcm - function for working with Windows credential manager

Algorithm

User defines a topic, number of pages, and receiver of the resulting email
Robot creates links for each search results page
Robot collects links to the articles from each page
Robot scraps article's info and downloads source docs if available
Robot writes all info to excel and sends email

Robot functionality:

Search articles by specific topic on N pages
Get title, author, source, description, number of citations, article file (if available) Note, that you need to choose the topic with at least 1 file available for downloading.

Link to video: https://www.loom.com/share/13badcb34e8242c48e4ad3c926b778b8

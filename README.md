# Web-Crawler
Given a URL to a web page and word to search for. The spider will go to that web page and collect all of the words on the page as well as all of the URLs on the page. If the word isn't found on that page, it will go to the next page and repeat.
Following things are done :
1. Retrieve a web page from a website
2. Collect all the links on that document
3. Collect all the words on that document
4. See if the word we're looking for is contained in the list of words
5. Visit the next link

Technologies Used :
1. Java
2. Java's jsoup which provides a very convenient API for extracting and manipulating data, using the best of DOM, CSS, and jquery-like methods.

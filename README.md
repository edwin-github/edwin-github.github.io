## Feed Reader Testing Project 6
 
## Project Overview  
Testing is an integral part in the development lifecycle. 
Test Driven Development or old fashion development, AGILE or waterfall methodologies all
require to have a testing phase in the development of the application.
There are numerous tools available out there to help you with testing your application.
In this project, Jasmine is used to write a number of tests against the application. 
These will test the underlying business logic of the application as well as the event 
handling and DOM manipulation.


## Tests Suites and Test cases
Tests are grouped into Test Suites and includes logically related test cases.
1) RSS Feeds - to test the validity of feed array object.
2) The Menu -  to test the behavior of the menu when initialized and when it is clicked.
3) Initial Entries - to test the initial load of the loadFeed function creating a single 
   .entry element within the .feed element.
4) New Feed Selection - to test when a new feed is loaded by the loadFeed function that
   the content actually changes.

### Instructions on how to run the tests 
1) Check it out here: http://edwin-github.github.io/index.html
   The tests spec and results are shown at the bottom of the page.
2) Click on an article, the article is displayed. 
3) Click the menu icon to display the available feeds. Click on the feed to load.


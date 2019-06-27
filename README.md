# Feed Reader Testing
This project uses Jasmine to test the functionality of a feed reader website.

How to run the application
- Download the zip file and extract the files in it to your local computer.
- Navigate to the files root folder and open the index.html file in your browser.
- Once opened, the index.html file will show a web application with all the tests results at the end of page.
- To see the full code for the tests explore the ./jasmine/spec/feedreader.js file.

Tests
RSS Feeds:
- The allFeeds variable is defined
- Each feeds URL is defined and not empty
- Each feeds name is defined and not empty

The Menu:
- The element menu is hidden by default
- Once the menu symbol is clicked the menu displays/hides

Initial Entries:
- The feed container has at least one single entry

New Feed Selection:
- The feed content changes when a new feed is selected

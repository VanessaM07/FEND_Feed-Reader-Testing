# Udacity Jasmine Feed Reader Testing

## Project Overview
In this project we are given a web-based application that reads RSS feeds by Udacity. The tests are added using Jasmine to check the functionalites of the code written. Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development".
- ### Instructions for completing the project: 
1. Download the required [project assets](https://github.com/udacity/frontend-nanodegree-feedreader).
2. Review the functionality of the application within your browser.
3. Explore the application's HTML (./index.html), CSS (./css/style.css) and JavaScript (./js/app.js) to gain an understanding of how it works.
4. Explore the Jasmine spec file in ./jasmine/spec/feedreader.js
5. Edit the allFeeds variable in ./js/app.js to make the provided test fail and see how Jasmine visualizes this failure in your application.
6. Return the allFeeds variable to a passing state.
7. Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
8. Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
9. Write a new test suite named "The menu".
10. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
11. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
12. Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.
13. Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.
14. When complete - all of your tests should pass


## What did I learn?
I have learned how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.
Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript.

## How to run the project
- Download the .zip file from GitHub
- Unzip the archive
- Open the index.html file in your browser of choice.
- This will run the feedreader and also show the Jasmine tests (all currently passing!).

That's all! :v:
:kiss:

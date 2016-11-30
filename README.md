## Project Overview

This project is a web-based application that reads RSS feeds. The purpose is to practice test driven development using the [Jasmine](http://jasmine.github.io/) framework. We are to write a serious of tests based on a series of instructions to ensure the listed functionality works. All tests were written in **feedreader.js**.

Click <a href="https://envincebal.github.io/feedreader-testing/">HERE</a> to view app.

## Tests performed

* Edit the allFeeds variable in ./js/app.js to make the provided test fail and see how Jasmine visualizes this failure in your application.
* Return the allFeeds variable to a passing state.
* Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
* Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
* Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
* Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
* Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

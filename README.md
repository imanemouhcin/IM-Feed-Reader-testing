# IM-Feed-Reader-testing


##Project Overview

For this project I was given a web	-based application that reads RSS feeds. The original developer of this application saw the value in testing, and started writing their first test suite! Unfortunately, they decided to move on to start their own company and left an application with an incomplete test suite which I was tasked to complete. I used Jasmine to write a number of tests.

##Steps to run

Clone this repository.
Open index.html in your browser .  
Once loaded, test results should be displayed at the bottom of the page.
Tests that are green have passed and red have failed.
The online version 

##How I completed this project:

I was asked to write the following tests in different test suites. Some tests required asynchronous function  - the done() argument within call to beforeEach()

##Tests:

A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
A test that ensures the menu element is hidden by default under "The Menu" test suite.
Test that ensures the menu changes visibility when the menu icon is clicked.
A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the feed container.
A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes

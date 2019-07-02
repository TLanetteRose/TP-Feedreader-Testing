# FeedReader Project Background

Welcome to my project! Last week I received the code for a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, so the developer included [Jasmine](http://jasmine.github.io/) and their first test suite! However, the developer needed to move on to another task: starting their own company. We now have to complete the test suite for this application. 


## How to Open the Application
### Option 1
My completed testing project is located on my [GitHub Page](https://tlanetterose.github.io/TP-Feedreader-Testing/). **Note:** You may need to "Load Unsafe Scripts" in **Google** or "Disable Protection" in **Firefox** to view the page. 
 
### Option 2
 You can also download or clone my repository into **Git Hub Desktop** or onto your local computer drive. Once you have downloaded the repository, open the **index.html** in your browser. 


# How I Completed My Project

I was required to write specific test based on the guidelines described for different test suites. The test suites toward the end required asynchronous functions. In these functions, I was required to use callbacks to make sure the feeds were loaded before they were tested. 

* Test 1: Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined _and_ that the URL is not empty
    * For example, how would you use a `for...of` loop in this test?
5. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
    * Think about how you wrote the previous test. What are you testing for this time?
6. Write a new test suite named `"The menu"`
    * What are you `describe`-ing in this test suite?
7. Write a test that ensures the menu element is hidden by default
    * You'll have to analyze the HTML and the CSS to determine how the hiding/showing of the menu element is implemented
    * What code in `app.js` is directly involved with toggling the menu on and off?
8. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display itself when clicked, and does it hide when clicked again?
    * Think about how you wrote the previous test. What is different this time around?
    * Which clickable element are you checking for?
    * How do you "simulate" a mouse click that element without actually clicking it?
9. Write a test suite named `"Initial Entries"`
    * What are you `describe`-ing in this test suite?
10. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container
    * How does Jasmine's `beforeEach()`function work?
    * How does the `loadFeed()` function in `app.js` work? Is it synchronous or asynchronous?
11. Write a test suite named `"New Feed Selection"`
    * What are you `describe`-ing in this test suite?
12. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes
    * How is this test different from the previous test?

Additionally, note that:

 * No test should be dependent on the results of another
 * Callbacks should be used to ensure that feeds are loaded before they are tested
 * Error handling should be implemented for undefined variables and out-of-bound array access
 * When complete, all of your tests should pass

When you're all finished, write a `README` file detailing all steps required to successfully run the application. If you have added additional tests, provide documentation for what these future features are and what the tests are checking for.

# Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

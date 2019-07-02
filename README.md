# FeedReader Project Background

Welcome to my project! Last week I received the code for a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, so the developer included [Jasmine](http://jasmine.github.io/) and their first test suite! However, the developer needed to move on to another task: starting their own company. We now have to complete the test suite for this application. 


## How to Open the Application
### Option 1
My completed testing project is located on my [GitHub Page](https://tlanetterose.github.io/TP-Feedreader-Testing/). **Note:** You may need to "Load Unsafe Scripts" in **Google** or "Disable Protection" in **Firefox** to view the page. 
 
### Option 2
 You can also download or clone my repository into **Git Hub Desktop** or onto your local computer drive. Once you have downloaded the repository, open the **index.html** in your browser. 


# How I Completed My Project

I was required to write specific test based on the guidelines described for different test suites. The test suites toward the end required asynchronous functions. In these functions, I was required to use callbacks to make sure the feeds were loaded before they were tested. 

* **Test 1:** I needed to write a test that looped through each feed in the `allFeeds` object and ensured that every feed had a URL defined _and_ that the URL was not empty.
   
* **Test 2:** The next test continued using `allFeeds` to loop through each feed to ensure it had a name defined and that the name was not empty. 
  
* **Test 3:** My next test suite, named `"The menu"`, focused on making sure the menu element was hidden by default. This required me to target the `menu-hidden` class. 
   
7. 
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



# Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

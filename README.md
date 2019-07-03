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
   
* **Test 2:** The next test continued using `allFeeds` object to loop through each feed to ensure it had a name defined and that the name was not empty. 
  
* **Test 3:** My next test suite, named `"The menu"`, focused on making sure the menu element was hidden by default. This required me to target the `menu-hidden` class. 

* **Test 4:** This test checked to see if the visibility of the menu changed once the `menu-icon-link` is clicked. 

* **Test 5:** The next test suite is called `"Initial Entries"`. This suite included a test which checked to see if there is a single `.entry` element in the `.feed` container. 
    
* **Test 6:** In the test suite named `"New Feed Selection"`, my test needed to ensure that the content changed when a new feed was loaded by the `loadFeed` function 
   



# Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

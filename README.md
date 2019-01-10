# Feedreader Testing Project

For this project, I wrote tests for a prebuilt web-based application that reads RSS feeds. Tests are written using [Jasmine](http://jasmine.github.io/). To run tests, download or clone the repo and open index.html in your browser. To replicate project yourself, see [Udacity project source](https://github.com/udacity/frontend-nanodegree-feedreader).


## Why this Project?

To gain experience in "test-driven development" and red/green coding. The idea (though it wasn't strictly practiced in this project) is to think about what a project must do, write tests for it, and then write code that will pass those tests. It's a way to chunk down your work to well defined tasks.

Testing in general is obviously essential, so that you can quickly pinpoint problem areas and determine if new code breaks something without just relying on the human eye.


## What did I learn?

I learned how to use Jasmine for testing, and also increased my knowledge of jQuery because the feedreader was written using jQuery. 

## Addtional notes

 * No test is dependent on the results of another
 * Callbacks are used for testing async loading
 * All tests should pass
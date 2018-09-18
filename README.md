# FEND-Feed-Reader-Testing-Project

# Project Overview

In this project we are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


### Here are some brief answers to each of the questions in the Development Strategy instructions:

1. app.js is the functional part of the code.
2. All tests pass and are defined in jasmine/spec/feedreader.js
4. expect is called for each feed.
5. name instead of url.
6. The menu's visibility.
7. Line 119 toggles menu on click.
8. This tests the effect of the menu icon's click event on the menu's visibility.
9. The number of initial entries.
10. beforeEach() waits for done to be called back asynchronously before each test.
11/12. The content changes between feeds.


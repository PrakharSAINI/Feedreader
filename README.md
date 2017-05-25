# Feeder reader testing using Jasmine

## About
We are given a web-based application that reads RSS feeds and with an incomplete test suite.
Tests were added in `jasmine/spec/feedreader.js` to test for functionality of the website.  The following tests are included:

- RSS feeds are defined in `allFeeds` and are not empty.
- Each feed in `allFeeds` has a defined and valid URL.
- Each feed has a defined and non-blank name.
- The navigation menu is hidden by default (on page load).
- The nav. menu toggles visibility after clicking the menu icon.
- The first feed has at least one entry.
- The feed changes content after reloading

## How to Run
1. Download zip and extract or clone on desktop
2. Open Index.html


## Why is testing important?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

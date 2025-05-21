# Lab 7

## Group

Brandon Khor

## Check Your Understanding

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

I would put my automated tests **within a Github action that runs whenever code is pushed** because automated tests are most effective when they run continuously in order to catch bugs early. By using GitHub actions, we can fully prevent faulty code from being merged with the master branch.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No. End-to-end testing is a way for developers to automate test cases that involve **emulating user actions** from start to finish. Unit tests would be better in this scenario.

3) What is the difference between navigation and snapshot mode?
   
Navigation mode analyzes the page right after it loads, whereas snapshot mode analyzes the page in its current state. We can use navigation mode as a performance metric and snapshot mode to find accessibility issues.
   
4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

* Properly size images. Serve images that are appropriately-sized to save cellular data and improve load time.
* `<html>` element does not have a `[lang]` attribute. If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly
* No `<meta name="viewport">` tag found. A `<meta name="viewport">` not only optimizes your app for mobile screen sizes, but also prevents a 300 millisecond delay to user input.







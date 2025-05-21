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

* Minifying CSS and Javascript files to reduce network payload sizes
* Enable text compression to minimize total network bytes
* Consider marking your touch and wheel event listeners as passive to improve your page's scroll performance







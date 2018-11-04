# Testing

Testing is absolutely crutial to every piece of software you'll ever write. Even for the simplest projects you probably
won't be able to write them without any testing and expect them to work properly. Instead you'll be continuously
testing your work to verify you are on the right track, even if that means just to manually run your program and see
what happens.

However, in software development, manual testing doesn't scale. As your project will start to grow you'll testing it
manually won't be possible anymore. That's why we need to write a different kinds of programs that will be doing the
heavy lifting for us. We call them automated tests.

Having automated tests have many advantages.
 - It greatly reduces chance of introduction of new bugs or regression of the old ones.
 - Enhances security and stability of the whole codebase
 - Allows continues integration/depolyment to safely merge changes into the codebase and deployment of the project
 without risk of breaking it.
 - In the end it can speed up development
      

Automated tests are divided into several categories
 - Unit tests -
 - Integration tests
 - End-to-end tests
 
There are several test frameworks that are going to help you setup you tests
 - Mocha - one of the most popular test frameworks, battle-tested
 - Jest - relatively new framework by Facebook with some interesting inovations  


# Homework

## 1. Improve coverage
Improve coverage of file `src/operations/users.js` so that only one
line (doesn't matter which one) is not covered (coverage 97.14%, 34 out of 35 lines covered).

To be able to do that, you're gonna need to write several more tests. Study tests in `tests/integration/users/create.spec.js` as well as in
`tests/integration/dogs/create.spec.js`. This should get you enough
information to carry out this task easily.

If that last uncovered line bugs you and you would like to score extra credit, try to improve coverage as much as reaching
100%. Hint: To do so, you'll need to find and fix a bug that creeped 
into our code during one of the previous lessons. Bug should get revealed by a test you'll write. 

## 2. Optional

Look at Jest library and try to reimplement at least some of the tests using this framework instead of Mocha.

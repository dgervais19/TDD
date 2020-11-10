# This lesson covers the concepts of Test Driven Devlopment (TDD)

## Type of testing
* Unit testing
* TDD

### Python has several modules that we can use to test our code
* pytest
* unittest

***Why TDD***
* TDD helps us minimise the risk of failure before sending the product to production

***steps***
* we will create a file to write our tests
* we will run the test, they will all fail
* we will create a file to write our code
* we will refactor and add the code to pass the test

![](tddSteps.png)

**Naming convention for test files and methods**
* file name simple_calc
* test_simple_calc

**install the testing frameworks**
* ```pip install pytest```
## The TDD Cycle
* Write a failing test
* Make the test pass
* Refractor
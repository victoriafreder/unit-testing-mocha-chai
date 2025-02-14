# Unit Testing with Mocha + Chai

Generation: Unit Testing Debrief Assignment

## Getting Started

1. Select one group member to be the coder for the group, the coder will follow the following instructions with the help of the group:
    * FORK this repository onto your github
    * Copy the https URL from your FORKED repo
    * Navigate to Git Bash on your local machine and `cd` to a place you wish to clone this activity to work on it
    * Once where you need to be in bash, run `git clone` followed by the URL you copied from your forked copy of this github repository
    * Open VSCode, select `File` in the top right, and select `Open Folder`
    * Find the folder you cloned named `unit-testing-mocha-chai` and open it, then familiarize yourself with the code first in `app.js`.  Read the comments in the object definition to figure out what each method is meant to do, and move to the `test` folder and come up with some simple tests in `app.test.js` to find errors, oversights, or bugs in the source code! Don't forget to run the following bash command to install the mocha and chai packages before running tests:

    ```bash
    npm init
    npm install mocha chai --save-dev
    ```

2. Work together to add appropiate tests for this activity, one by one. If you get stuck, don't forget to use your Google-Fu and problem solving skills. TA's will be hopping into each room to check in, message one of us on Slack for specific help.

3. Ask yourselves the following questions.  What types of input will cause problems in the methods? Do they handle invalid input appropriately? Do they throw a descriptive error upon invalid input? Upon valid input, does the method work as expected (i.e. does the method produce the expected result)?

4. When your team is finished with the activity, submit a pull request from your fork!

5. At the end of the allotted time, we will go over this exercise step by step. Group members are expected to raise their hands and guide the class through each solution.

### Helpful Links

* [What is Nodejs](https://www.codecademy.com/article/what-is-node)
* [Node fs module](https://nodejs.dev/learn/the-nodejs-fs-module)
* [Node assert: api documentation](https://nodejs.org/api/assert.html)
* [Node assert: Equal, Actual, Expected](https://nodejs.org/api/assert.html#assert_assert_equal_actual_expected_message)
* [Chai documentation](https://www.chaijs.com/)
* [Chai assert: api documentation](https://www.chaijs.com/api/assert/)
* [TDD: Red Green Refactor visual](https://content.codecademy.com/programs/tdd-js/articles/red-green-refactor-tdd.png)
* [CC Unit Testing cheatsheet](https://www.codecademy.com/learn/learn-javascript-unit-testing/modules/learn-mocha-and-assert/cheatsheet)

# assignment-functions0-template

Assignment: Create a Function that Returns the Sum of Two Numbers

    Create a new Node.js module called sum.js.
    In sum.js, define a function called sum that takes two arguments and returns their sum.
    Export the sum function so that it can be used in other modules.
    Write a test case for the sum function using Jest.
    In your test case, import the sum function from sum.js and use it to test that the function returns the correct result when given two numbers.
    Run your test using Jest to ensure that it passes.

Example Test Case

Here's an example test case that you can use as a template for your own test:

javascript
    
`const sum = require('./sum');
test('adds 1 + 2 to equal 3', () => {
    expect(sum(1, 2)).toBe(3);
})`
     

In this example, we're importing the sum function from sum.js, then calling it with the arguments 1 and 2. We're using the expect function from Jest to assert that the result of calling sum(1, 2) is 3. If the result is indeed 3, the test will pass. If it's not, the test will fail.
Instructions

To complete this assignment:

    Create a new directory for your assignment, and navigate to that directory in your terminal.
    Initialize a new Node.js project using npm init.
    Install Jest using npm install --save-dev jest.
    Create a new file called sum.js in your project directory, and define the sum function as described above.
    Export the sum function so that it can be used in other modules.
    Create a new file called sum.test.js in your project directory.
    Write a test case for the sum function using Jest, as described above.
    Run your test using Jest to ensure that it passes.

If your test passes, you have completed the assignment successfully!

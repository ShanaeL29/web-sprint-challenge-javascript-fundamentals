# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.



1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 


    -   .map will return a brand new array without manipulating the original array and requires a return statment. You can use map when you want to convert data. Take the data, apply a rule in map, and return the results in a new array.
    -   .filter will also return a new array without manipulating the original while requiring a return statement. You should use .filter when you want to filter data out based on a boolean value (either true or false). If true the data will be in the new array and if false the data will not be in the new array.
    -   .reduce will return a single value. It will NOT return a new array. You can use .reduce anytime you want to reduce data down to a single value such as for multiplication or addition or getting an average based off the data.



2. Explain the difference between a callback and a higher order function.


    A higher order function receives other functions whereas a callback function is a function that is passed into another function as an argument.


3. Explain what a closure is.


    A closure is created when you create a function nested within another function. The inside function is the closure. The inside function can reach outside of itself to access variables it does not have access to directly inside its own scope.


4. Describe the four principles of the 'this' keyword.


    -   The first principle is window binding. When "this" is in the global scope it will return the window object. If none of the other rules apply "this" will default to the window. The window object is an error and we do not want this.
    -   The next principle is implicit binding. In this principle "this" applies to objects with methods and "this" refers to the object to the left of the dot when a function is called.
    -   The third principle of "this" is new binding. In this principal "this" refers to/is bound to the newly created object that the constructor function creates. When we call the function we have to use the "new" keyword with the name of the constructor function.
    -   The last principle is explicit binding. In this principle "this" is explicitly bound when we use .call or .apply to bind an object.

5. Why do we need super() in an extended class?

    The super keyword refers to the parent and calls the constructor of the parent class and gives the child access to all of the parent's properties and all of the parent's methods.




You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 



## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


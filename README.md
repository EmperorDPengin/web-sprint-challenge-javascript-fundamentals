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

    A. 
        .map() - Is used to for Modifying Data in arrays, it wont modify the original array, but it will return a new one with the modified data;
                ex. Having an array with Produce Objects Info, [name, price, type] and we want to display the name of all objects before the person clicks on them to see the price. We can use
                    .map to go thru every item and store the object.name in the returned array.
        
        .reduce() - Is used to return a single value from an array. The uses can be from simple addition to keeping track of several scores and returning a last value, but at the end it is a single value that u have to interpret somehow.
                ex. Used for calculating the average score in a class of student by  having each score added together and divided by the number of students.
        
        .filter() - It sorts thru data with a true false statement, if it is what is looking for it will return a new array not modifying the original with the new data that meet the criteria.
                ex. Can be used for removing items not anted in a page displayed to the user or by user request. Having all Hotels without Wheel chair access from the page if the user needs it.

2. Explain the difference between a callback and a higher order function.

    A. A Higher Order Function Receives argument Functions to execute with a more specific purpose. While a callback is used for easy access and receive the arguments to modify, operate or  store.

3. Explain what a closure is.

    A. a closure is when a function accesses defined data from outside its own scope into another function

4. Describe the four principles of the 'this' keyword.

    A. 
        window binding - if none of the orher 'this' rules apply it will return the global object,
        implicit binding - is whatever the dot to the left points to when calling a fucntion
        explicit binding - when using .call, .apply or .bind we are teling JS, exactly what 'this' refers to.
        new binding - is during the creating of a new object and it lets 'this' be attached to the object, pointing functions to it.

5. Why do we need super() in an extended class?

    A. Super is a way to say Give everything the parent had to the child and so 'this' knows what else it is bound to.

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


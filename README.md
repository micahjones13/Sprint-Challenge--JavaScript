# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

    .forEach doesn't return anything, it just iterates a function over an existing array. .map actually edits the array and returns the new one.

2. What is the difference between a function and a method?

    Methods are usually associated with an object, where you use dot notation to call it. .map and .foreach are methods. Functions can be independent, but are very similar to methods. I believe that creating a prototype function for an object makes that function a method of that object.

3. What is closure?

    Closure is similar to scope in that it tells you/the program what it can and can't access. For example, if a var isn't defined in a functions scope, the function will look outside the function to find where var is defined. You can use closure to access things 
    nested inside of other things, just by invoking the function that the data you want access to is inside of. 

4. Describe the four rules of the 'this' keyword.

    1. Global/Window Binding: If you don't bind the 'this' word to anything, it binds to global/window scope, and that makes 'this' refer to everything that the global scope has to offer.
    2. Implicit Binding: binds the 'this' keyword to whatever is refered to to the left of the dot notaiton being used. Whenever a function is being called, this refers to the object left of the dot. ie, myObj.speak();
    3. New Binding: binds 'this' to object created using 'new' keyword. ie, const micah = new student (); 'this' now refers to object micah of student class 
    4. Explicit Binding: this uses methods to bind 'this' to something. Those methods are .call, .apply and .bind 

5. Why do we need super() in an extended class?

    It takes the place of the .call() method when using classes, it gives the child class acess to the parent class key/vaule pairs.

## Project Set up

Follow these steps to set up and work on your project:

- [x] Create a forked copy of this project.
- [x] Add PM as collaborator on Github.
- [x] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [x] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [x] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [x] You are now ready to build this project with your preferred IDE
- [x] Implement the project on your Branch, committing changes regularly.
- [x] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [x] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [x] Add your Project Manager as a Reviewer on the Pull-request
- [x] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [x] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [x] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [x] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [x] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!

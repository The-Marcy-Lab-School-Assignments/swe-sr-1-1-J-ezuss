# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

- A technical definition ("According to MDN, a function is...").
- An explanation of the concept with an analogy ("You can think of a function a ...")
- An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
- An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

**Technical definition**

According to MDN, a **function** is a reusable block of code that is designed to do one specific task and runs when it is called (invoked).

**Analogy**

I think of a function like a vending machine. You press some buttons (give it inputs), it does its thing inside, and then it gives you a snack (an output). You don’t need to know everything happening inside—just how to use it.

Check out this example:

```js
// An arrow function that multiplies two numbers
const multiply = (x, y) => {
  return x * y;
};

// Calling the function
const answer = multiply(4, 5);
console.log(answer); // 20
```

**Explanation of the example and syntax**

This example uses an **arrow function**, which is a shorter way to write a function in JavaScript. The function is called `multiply`.

The values inside the parentheses `(x, y)` are called **parameters**. They represent the numbers that will be used when the function runs.

The curly braces `{}` are the **code block**, and they hold the code that runs when the function is called. Inside the code block, there is a **return statement**, which sends the result (`x * y`) back to where the function was used.

When we **call/invoke** the function using `multiply(4, 5)`, the numbers `4` and `5` are passed into the parameters, the code runs, and the function returns `20`.

Basically, functions help us avoid repeating code and make our programs easier to read and use.

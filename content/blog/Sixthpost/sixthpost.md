---
title: Basic JS program to calculate a tip 
description: Assigned a task to create a program to calculate a tip percentage.
date: 2023-08-10

---

### Introduction to JavaScript variables

Variables are one of the important theories in programming. It could even be said to be the most important. They are part of the fundamentals of any programming language. Without them, it would be difficult to perform manipulation, and computations. We would have no way of storing information, retrieving them and no track of values.

A variable is a storage location or a memory location that holds a data type and values. JavaScript variables are variables declared and assigned in JavaScript, following the JavaScript syntax, that holds values and datatypes.
In this article, we will look at variables in JavaScript and how they are implemented and manipulated to create a basic tip program.

<br>

### JavaScript variable declaration, Initializing and Assigning Variables

<br>

A variable is declared when it is created. In JavaScript, variables are declared using any of these three keywords - var, let and const. In the code below you can see I've declared a variable using the keyword const for pre-tip total and the tip percentage. 

```js
const subtotal = 30.83;
const tipPercent = 0.15; // Can be changed

const billTip = subtotal * tipPercent;

const receipt = `Meal: ${subtotal} Tip: ${billTip}
Total: ${subtotal + billTip}`;

console.log(receipt);
```

Part of the task was then to output a sentence to the page displaying the total bill including tip - To output a message to your page you can simply write the code below.

```js
document.write(`Your total bill, with tip, is £35.45.`);
``` 

<br>

### Extend the tip program

<br>

Final part of the task was to use toFixed() to round the output to 2 decimal places and output a sentence for the tip amount. This can been seen in the code below.

```js 
const $2DP = parseFloat(subtotal + billTip).toFixed(2)

console.log($2DP);

document.write(`Your tip is £4.62.`);
```
Please visit [this link](https://codepen.io/Kcboyy/pen/XWyQezz) to see the program in action.

Thanks for reading!

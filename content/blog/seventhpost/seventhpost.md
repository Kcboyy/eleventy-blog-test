---
title: Function and Control Flow 
description: Assigned a task to create a program to calculate a tip percentage.
date: 2023-08-11

---

### Introduction to JavaScript variables



<br>

### JavaScript variable declaration, Initializing and Assigning Variables

<br>

 

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

---
title: Function and Control Flow Practicals
description: Assigned a task to create a calculator which incorporated switch statements.
date: 2023-08-15

---


 ### Percentage Calculator

In this blog I will demonstrate a basic program I created to calculate a percentage of any number. You can see in the code below I created two arguements, "inputNum" & "inputPercentage" the logical operator and the return statement. This will return the percentage of any number by changing the numbers in the console log syntax.  

```js
const inputNumber = prompt(`Please enter a number`)
const inputPercentage = prompt(`Please enter a percentage`)

percentageCalculator = (inputNum, inputPercentage) => {
  if (inputNum && inputPercentage) {  
  }
   return inputNum * inputPercentage / 100;
}
console.log(percentageCalculator(135, 30))
```
<br>

### Switch Statements

The next part of my task was to implement a switch statement for a basic drinks ordering program. The switch statement evaluates an expression, the value of the expression is then compared with the values of each case in the structure. If there is a match, the associated block of code is executed. This can be seen in my code below. 

```js
const arrSize =[`small`, `medium`, `large`];
const arrFlavour =[`cola`, `lemon`, `orange`];
const inputSize = prompt(`Please enter a Size`)
const inputFlavour = prompt(`Please enter a Flavour`)

drinkOrder = (size, drink) => {
  let drinkLabel;
  
  switch (drink) {
    case `lemon`:
      drinkLabel = `lemonade`;
      break;
      
    case `orange`:
      drinkLabel = `orangeade`;
      break;
       
    case `cola`:
      drinkLabel = `cola`;
      break;
      
    default: small
      drinkLabel = drink;
      break;
  }
  
  return `You have ordered a ${size} ${drinkLabel}.`;
}

console.log(drinkOrder(inputSize, inputFlavour));
``` 

<br>

### Calculator
The final part of the task was to create a function capable of using the addition, subtraction, multiply, divider and modulus operators on two numbers which i've demonstrated in my code below. This task also incorporated the use of a switch statement as discussed above, however this could potentially cause unnecessary and inefficient code dependant on the scale of the operators required and instead it would be of better use to use the eval() method for such task.     

```js
 calculator = (number1, number2, operator) => {
  let result
  
  switch(operator) {
  case `+`:
    result = number1 + number2
    break;
  case `-`:
    result = number1 - number2
    break;
  case `/`:
    result = number1 / number2
    break;
  case `*`:
    result = number1 * number2
    break;
  case `%`:
    result = number1 % number2
    break;
  }
  
  return result
}

console.log(calculator(2,2, `+`))
```
Please visit [this link](https://codepen.io/Kcboyy/pen/NWEQMzX) to see the program in action.

Thanks for reading!

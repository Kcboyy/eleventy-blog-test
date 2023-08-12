---
title: Function and Control Flow 
description: Assigned a task to create a program to calculate a tip percentage.
date: 2023-08-11

---
<br>
 Functions are separable, reusable pieces of code. 
<br>

 ### Declaring Functions

 To declare a function you give it a name, then include all the code for the function inside curly brackets { }. To invoke (use) a function, you type its name, followed by parenthesis ( ). This can be seen on my code below.

```js
function firstFunc () {
        alert("Hello my name is Casey Newcombe and I'm a professional Web Developer")
      }
      firstFunc();
```
A function is a group of code you can reuse many times. Whenever you invoke a function by using its name, you tell the browser to run the code inside the function. To return a value from a function, you must include a return statement, followed by the value to be returned, before the function's end statement. You can see this is my code below.

```js
function secondFunc (firstName = `first`, secondName = `last`) {
        return `${`Casey`} ${`Newcombe`}` 
        // return `${firstName} ${secondName}`
      } 
      const result = secondFunc();
      // const result = secondFunc('John', 'Smith');
      console.log(result);
``` 

<br>

### Control Flow & Logical Operators

We use if statements to decide which lines of code to execute given a condition. We also use <u><b>else</b></u> to provide an alternate set of instructions. You can also use logical operators to combine conditions as seen in my code below.

```js
let temperature = 45;

    if (temperature <=50) {
      console.log(`Put on a coat it is cold!`)
    }

      let temp = 30;
      let doTheyOwnAHat = true;
      
      if (temp <= 0) {
        console.log('stay inside.');
      } else if (temp <= 30 && doTheyOwnAHat) {
        console.log(`wear a coat and a hat.`);
      } else if (temp <= 50) {
        console.log('wear a coat.');
      } else {
        console.log('just pants and vest is fine.');
      } 
```
Please visit [this link](https://codepen.io/Kcboyy/pen/XWyLVRw) to see the program in action.

Thanks for reading!

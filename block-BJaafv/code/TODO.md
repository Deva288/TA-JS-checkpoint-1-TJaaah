1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
// Ans - Difference between first and second `sum` is the first sum is returning the value ans second sum is consoling the value or printing the value.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
  
// Ans - The value of first will be the sum of a and b .The value of second will be the undefined because second sum will not be assigned to variable and function dosn't have return statement.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

// Ans - Output will be 36 which is sum of 1st two parameter and third argument will be ignored by the JavaScript because it is not been declared.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

// Yes we can store first sum function in a variable named add because function is an expression so, we can store it.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

// function sayHello(name) {
  return `Hello ${name}`
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// Ans - Output of above function will be "Hello John" because username has assign the value John.

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // "Hello, John"

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.

// Ans- The function which declared with name called Anonymous function.

Examples: let addNumber = function (a, b) {
  return a + b;
}

let fullName = (firstName, lastName) => firstName + " " + lastName;

let substractNum = function (a ,b) {
  return a - b;
}

9. Can function declaration be a Anonymous Function? Explain

Ans -  The Function declaration can not be a an anonymous function. When a function is declared without a name it is assigned to variable and it becomes a function Expression not a declartion.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
//  1 
function fullName(firstName,  lastName) {
  return firstName + " " + lastName;
}
//
function addNumbers(numA, numB) {
  return numA + numB;
}
//
function isAdult (age) {
  return age > 18;
}
//
function getRemainder (n, p) {
  return n % p;
}
//
function daysInMonth (month){
  let days = '';
}
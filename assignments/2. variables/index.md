1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
variable

2. Find the error if any
```js
  var product cost = 3.45;
```
 varibale cant be with space
3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"
  'Hello World"
  "Hello World'
  'Hello World'
```
`Right or Wrong`
## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;VALID
var 1girl;INVALID
var woman3;VALID
var -girl;INVALID
var blackDog;VALID
var 42;INVALID
var $42;VALID
var userName;VALID
var x, y, z;VALID
var x = 5, y = 6, z = 7;VALID
var x = 5 + 10 + 2;VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var sub = 80;
var newamount = amount - sub;
// Define a new variable and store the value that is 200 more then the value of amount.
var sum = 200;
var newamount = amount + sum;
// Define a new variable and store the value that is 4 times the value of amount.
var x4 = 4 * amount;
var newamount = x4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var d21 = amount%21;
var newamount = d21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if(johnAge > markAge){
  console.log("John is older");
}
else{
  console.log("Mark is older than John");
}

// Check who is younger
if(johnAge > markAge){
  console.log("Mark is younger");
}
else{
  console.log("John is younger");
}

// Check if their age is equal
if(johnAge === markAge){
  console.log("John and Mark are the same age.");
}

// Create a new variable and assign the age of john to new variable.
var newJohn = johnAge;

// Check if john is equal to or greater then mark.
johnAge >= markAge;

// Check if john is less then or equal to mark.
johnAge <= markAge;

// Calculate the average age of john and mark and assign to a new variable.
var averageAge = (johnAge + markAge)/2;

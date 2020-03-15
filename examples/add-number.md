## Add Two Numbers

### Source Code

```javascript

// This program adds two numbers

var a, b, c;

a = 10;
b = 20;

c = a + b;

console.log("The sum of 10 and 20 is =" + c);

```
##### Output:

	The sum of 10 and 20 is = 30


Changing this operator, we can subtract (-), multiply (*), divide (/), floor divide (//) or find the remainder (%) of two numbers.


### Source Code: Add Two Numbers Provided by The User

```javascript

// This program adds two numbers

var number1, number2;	//taking a number from the user
var n1,n2,sum; 			// variable declaration

number1 = prompt("Enter the First Number : ");
number2 = prompt("Enter the Second Number : ");

n1 = parseFloat(number1);
n2 = parseFloat(number2);

sum = n1 + n2;

//or

var n1 = Number(prompt("Enter the First Number : "));
var n2 = Number(prompt("Enter the Second Number : "));

var sum = n1 + n2;

document.write("<h4> The sum of " + n1 + " and " + n2 + " is = " + sum + "</h4>");

```
##### Output:

	Enter the First Number : 15
	Enter the First Number : 15.6
	The sum of `n1` and `n2` is = 30.6

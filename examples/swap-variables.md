## Swap Two Variables

> In this example, you will learn to swap two variables by using a temporary variable and, without using temporary variable.

### Source Code: Using a Temporary variable

```javascript

// Code to swap two variables

var x = 15;
var y = 37;

// To take inputs from the user
// var x = prompt("Enter value of x: ")
// var y = prompt("Enter value of y: ")

// create a temporary variable and swap the values
temp = x
x = y
y = temp

console.log("<h4> After Swapping: x = " + x + " and y = " + y + "</h4>");

```
##### Output:
   
	<h4> After Swapping: x = 55 and y = 10 </h4>


In this program, we use the `temp` variable to hold the value of `x` temporarily. We then put the value of `y` in `x` and later `temp` in `y`. In this way, the values get exchanged.



### Source Code: Without using a Temporary variable

In JavaScript, there is a simple construct to swap variables. The following code does the same as above but without the use of any temporary variable.

```javascript

// Code to swap 'x' and 'y' without Temporary variable

var x = 10;
var y = 55;

x = x + y; // x now becomes 10+55=65
y = x - y; // y becomes 65-55=10
x = x - y; // x becomes 65-10=55

console.log("<h4> After Swapping: x = " + x + " and y = " + y + "</h4>");

```
##### Output:
   
	<h4> After Swapping: x = 55 and y = 10 </h4>


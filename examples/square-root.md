## Find the Square Root of a Number

> In this program, you'll learn to find the square root of a number using exponent operator and Math.sqrt().

### Source Code

```javascript

// To take input from the user
var n = prompt("Enter a number: ");

sqrt = n ** 0.5;    // ** is a exponent operator

document.write("The square root of " + n + " is " + sqrt);

```
##### Output:

    Enter a number: 16
	The square root of 16 is 4

In this program, we store the number in `n` and find the square root using the `**` exponent operator. This program works for all positive real numbers.


### Source Code: Using Math.sqrt()

> The Math.sqrt() function in JavaScript is used to square root of the number passed as parameter to the function.

    Math.sqrt(value)

- **Parameters**: This function accepts a single parameter value which hold the number whose square root is to be calculated.
- **Returns**: The method returns the square root of a number. If `value` is a negative number, NaN is returned

```javascript

// To take input from the user
var n = prompt("Enter a number: ");

// Calculate root
var s = Math.sqrt(n);

//using fixed-point notation
var value = s.toFixed(3)

document.write("The square root of " + n + " is " + value);

```
##### Output:

    Enter a number: 28
	The square root of 28 is 5.291

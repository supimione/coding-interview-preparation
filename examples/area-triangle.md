## Calculate the Area of a Triangle

> In this program, you'll learn to calculate the area of a triangle and display it.

### Source Code

```javascript

// Take inputs from the user
var a = Number(prompt('Enter First Side: '))
var b = Number(prompt('Enter Second Side: '))
var c = Number(prompt('Enter Third Side: '))

// calculate the semi-perimeter
var s = (a + b + c) / 2

// calculate the area
var area = (s*(s-a)*(s-b)*(s-c)) ** 0.5

// using fixed-point notation
var value = area.toFixed(2)

document.write("The area of the triangle is : " + value);

```
##### Output:

    Enter First Side: 5
    Enter Second Side: 6
    Enter Third Side: 7
	The area of the triangle is 14.70


In this program, area of the triangle is calculated when three sides are given using `Heron's formula`.

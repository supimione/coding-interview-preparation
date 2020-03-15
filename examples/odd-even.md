## Check if a Number is Odd or Even

> In this example, you will learn to check whether a number entered by the user is even or odd.

A number is even if it is perfectly divisible by 2. When the number is divided by 2, we use the remainder operator `%` to compute the remainder. If the remainder is not zero, the number is odd.

### Source Code

```javascript

// This program is to check a Number is Odd or Even

var n = prompt("Enter Your Number:")

if (n % 2 == 0) 
{
   document.write(n + " is a Even Number.");
}  
else 
{
   document.write(n + " is a Odd Number.");
}

```
##### Output 1:
   
	Enter Your Number: 47
    47 is a Odd Number.

##### Output 2:

    Enter Your Number: 20
    20 is a Even Number.


In this program, we ask the user for the input and check if the number is odd or even.

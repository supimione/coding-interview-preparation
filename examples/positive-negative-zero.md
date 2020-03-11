## Check if a Number is Positive, Negative or 0

> In this example, you will learn to check whether a number entered by the user is positive, negative or zero. This problem is solved using if...elseif...else and nested if...else statement.

### Source Code

```javascript

// This program is to check a number is odd zero even

var n = prompt("Enter Your Number:")

if (n > 0) 
{
   document.write(n + " is a Positive Number.");
} 
else if(n == 0) 
{
   document.write("You Entered Zero.");
} 
else 
{
   document.write(n + " is a Negative Number.");
}

```
##### Output:
   
	Enter Your Number: 20
    20 is a Positive Number.

    Enter Your Number: 0
    You Entered Zero.

    Enter Your Number: -120
    -120 is a Negative Number.


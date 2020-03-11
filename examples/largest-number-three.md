## Find the Largest Number Among Three Numbers

> In this program, you'll learn to find the largest among three numbers using if else and display it.

In the program below, the three numbers are stored in `x`, `y` and `z` respectively. We've used the `if...elseif...else` to find the largest among the three and display it.

### Source Code

```javascript

// To find the largest number among the three input numbers

var x = Number(prompt("Enter the First Number:"));
var y = Number(prompt("Enter the Second Number:"));
var z = Number(prompt("Enter the Third Number:"));

if(x > y && x > z)
{
    document.write("The largest number is = " +x);
}
else if(y > x && y > z)
{
    document.write("The largest number is = " +y);
}
else
{
    document.write("The largest number is = " +z);
}

```
##### Output:
   
	Enter the First Number: 10
    Enter the Second Number: 25
    Enter the Third Number: 9 

    The largest number is = 25


##### Note:  To test the program, change the values of `x`, `y` and  `z`.


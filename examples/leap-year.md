## Check if year is leap year or not

> In this program, you will learn to check whether a year is leap year or not. We will use nested if...else to solve this problem.

A year is leap year if following conditions are satisfied:

- Year is perfectly divisible by 400.
- Year is exactly divisible by 4 and not divisible by 100.

    For example,

        2017 is not a leap year
        1900 is not a leap year
        2012 is a leap year
        2000 is a leap year

### Source Code

```javascript

// To check if year is a leap year or not

//define variables
var year;

//get the entered year from text box 
year = prompt("Enter Year:")

//three conditions to find out the leap year
if( (0 == year % 4) && (0 != year % 100) || (0 == year % 400) )
{
	document.write(year+ " is a leap year");  
}
else
{
	document.write(year+ " is not a leap year");  
}

```
##### Output:

    Enter Year: 2000
	2000 is a Leap Year.


You can change the value of `year` in the source code and run it again to test this program.
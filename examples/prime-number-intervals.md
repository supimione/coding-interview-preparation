## Display Prime Numbers Between Two Intervals

> In this example, you will learn to print all prime numbers between two numbers entered by the user.

### Source Code

```javascript

// This program adds two numbers

var low = Number(prompt("Enter the First Interval: ")); 
var high = Number(prompt("Enter the Second Interval: ")); 

for(i=low; i<=high; i++)
{
	for(j=2; j<i; j++)
	{
		if(i % j == 0)
		break;
	}
	if(i == j)

	document.write(i+ "\n");
}

```
##### Output:

	Enter the First Interval: 5
	Enter the First Interval: 15
	5 7 11 13

In the above program, the range of numbers is taken as input and stored in the variables `low` and `high`. Then using for-loop, the numbers between the interval of `low` and `high` are traversed. For each number in the for loop, it is checked if this number is prime or not. If found prime, print the number. Then the next number in the loop is checked, till all numbers are checked.


Visit this page to learn more about how [check whether a number is prime or not](examples/prime-number.md).
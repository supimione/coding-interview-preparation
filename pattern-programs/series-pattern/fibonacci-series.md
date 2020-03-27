## Print the Fibonacci sequence

> In this program, you'll learn to print the Fibonacci sequence using for loop.

    Below are a series of Fibonacci numbers(10 numbers):   
    0 1 1 2 3 5 8 13 21 34

Fibonacci Series is a series of numbers where the first two Fibonacci numbers are 0 and 1, and each subsequent number is the sum of the previous two. Its recurrence relation is given by `Fn = Fn-1 + Fn-2`.

#### How Its Formed:
    0  = n1
    1  = n2
    1  = 0 + 1
    2  = 1 + 1 
    3  = 2 + 1
    5  = 3 + 2
    8  = 5 + 3
    13 = 8 + 5
    21 = 13 + 8
    34 = 21 + 13

### Source Code

```javascript

var n1 = 0;
var n2 = 1;
var n3;
var num = prompt("Enter the limit to generate fibonacci no: ");
 
document.write(n1+"\n");
document.write(n2+"\n");
 
for(var i=3; i<=num; i++)
{
	n3 = n1 + n2;
	n1 = n2;
	n2 = n3;
	document.write(n3+"\n");
}

```
##### Output:

    Enter the limit to generate fibonacci no: 10
    0 1 1 2 3 5 8 13 21 34

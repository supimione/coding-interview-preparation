## Print the Arithmetic Series

> In this program, you'll learn how to print the geometric series.

If a sequence of values follows a pattern of `multiplying` a fixed amount times each term to arrive at the following term, it is referred to as an geometric sequence.
The number `multiplied` to each time is constant and is called as the common ratio, `c`.

    Example: 2, 6, 18, 54 ......

An geometric sequence starts with term(a) 2 and having common difference (c) of 3.

### Source Code

```javascript

// To take series limit from the user
var n = Number(prompt("Enter your series size(n): "));

// To take series first term
var a = Number(prompt("Enter first term(a): "));

// To take series common difference
var c = Number(prompt("Enter the common difference(c): "));

for(var i=1; i<=n; i++)
{
    document.write(a+ "\n");

    a = a * c; 
}

```
##### Output:

    Enter your series size(N): 7
	Enter first term(A): 1
    Enter the common difference(C): 3
    1 4 7 10 13 16 19

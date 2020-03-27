## Print the Arithmetic Series

> In this program, you'll learn how to print the arithmetic series.

If a sequence of values follows a pattern of `adding` a fixed amount from one term to the next, it is referred to as an arithmetic sequence.
The number `added` to each term is constant is called as the common difference, `C`.

    Example: 1, 4, 7, 10, 13, 16 ......

An arithmetic sequence starts with term(A) 1 and having common difference (C) of 3.

### Source Code

```javascript

// To take series limit from the user
var N = Number(prompt("Enter your series size(N): "));

// To take series first term
var A = Number(prompt("Enter first term(A): "));

// To take series common difference
var C = Number(prompt("Enter the common difference(C): "));

for(var i=1; i<=N; i++)
{
    document.write(A+ "\n");

    A = A + C; 
}

```
##### Output:

    Enter your series size(N): 7
	Enter first term(A): 1
    Enter the common difference(C): 3
    1 4 7 10 13 16 19

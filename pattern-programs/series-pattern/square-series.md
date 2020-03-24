## Find the Square Root of a Number

> In this program, you'll learn to print the square root of number.

### Source Code

```javascript

// To take input from the user
var n = prompt("Enter your series size: ");

document.write("Square roots are: ");

for(var i=1; i<=n; i++)
{
    var result = i * i;

    document.write(result+ "\n"); 
}

```
##### Output:

    Enter your series size: 10
	Square roots are: 1 4 9 16 25 36 49 64 81 100

In this program, we store the number in `n` and print the square root using the `*` exponent operator. 
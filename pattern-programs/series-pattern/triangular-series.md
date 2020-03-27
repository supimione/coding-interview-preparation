## Find the Square Root of a Number

> In this program, you'll learn how to print the Triangular series.

### Source Code

```javascript

// To take input from the user
var n = prompt("Enter your series size: ");

document.write("Triangular series are: ");

for(var i=1; i<=n; i++)
{
    var result = (i * (i + 1))/2;

    document.write(result+ "\n"); 
}

```
##### Output:

    Enter your series size: 10
	Triangular series are: 1 3 6 10 15 21 28 36 45 55

## Find the Square Root of a Number

> In this program, you'll learn to print the cube of number.

### Source Code

```javascript

// To take input from the user
var n = prompt("Enter your series size: ");

document.write("Cube series are: ");

for(var i=1; i<=n; i++)
{
    var result = i * i * i;

    document.write(result+ "\n"); 
}

```
##### Output:

    Enter your series size: 10
	Cube series are: 1 8 27 64 125 216 343 512 729 1000

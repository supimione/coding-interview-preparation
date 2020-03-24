## Print Odd Numbers

> In this example, you will learn to print Even numbers upto entered by the user.

### Source Code

```javascript

// To print odd numbers

var n = prompt("Enter your series size: ")

document.write("Even numbers are: ");

for(var i=1; i<=n; i++)
{
    var result = 2 * i;

    document.write(result+ "\n"); 
}

```
##### Output:
   
	Enter your series size: 10
    Even numbers are: 2 4 6 8 10 12 14 16 18 20

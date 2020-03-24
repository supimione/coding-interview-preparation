## Print Odd Numbers

> In this example, you will learn to print odd numbers upto entered by the user.

### Source Code

```javascript

// To print odd numbers

var n = prompt("Enter your series size: ")

document.write("Odd numbers are: ");

for(var i=1; i<=n; i++)
{
    var result = 2 * i - 1;

    document.write(result+ "\n"); 
}

```
##### Output:
   
	Enter your series size: 10
    Odd numbers are: 1 3 5 7 9 11 13 15 17 19

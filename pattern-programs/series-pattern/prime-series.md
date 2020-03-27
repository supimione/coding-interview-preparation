## Print Odd Numbers

> In this example, you will learn how to print prime numbers.

### Source Code

```javascript

// To print odd numbers

var n = prompt("Enter your series size: ")

document.write("Prime numbers are: " );

for(var i=1; i<=n; i++)
{
    for(var j=2; j<i; j++)
    {
        if(i % j == 0)
        break;
    }
    if(i == j)
    {
        document.write(j+ "\n");
    }
}

```
##### Output:
   
	Enter your series size: 10
    Odd numbers are: 1 3 5 7

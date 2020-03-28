## Print the pattern below:
    1
    1 2
    1 2 3
    1 2 3 4 

### Source Code

```javascript

var num = prompt("Enter your number: ");

for(var i=1; i<=num; i++)
{
    for(var j=1; j<=i; j++)
    {
        document.write(j);
    }
    document.write("<br />");
}

```
##### Output:

	Enter your number: 5

    1
    1 2 
    1 2 3 
    1 2 3 4
    1 2 3 4 5
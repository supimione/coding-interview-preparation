## Print the pattern below:
    1
    2 2
    3 3 3
    4 4 4 4 

### Source Code

```javascript

var num = prompt("Enter your number: ");

for(var i=1; i<=num; i++)
{
    for(var j=1; j<=i; j++)
    {
        document.write(i);
    }
    document.write("<br />");
}

```
##### Output:

	Enter your number: 5

    1 
    2 2
    3 3 3
    4 4 4 4
    5 5 5 5 5
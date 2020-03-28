## Print the pattern below:
    4 3 2 1 
    4 3 2 1 
    4 3 2 1 
    4 3 2 1 

### Source Code

```javascript

var num = prompt("Enter your number: ");

for(var i=num; i>=1; i--)
{
    for(var j=num; j<=1; j--)
    {
        document.write(j);
    }
    document.write("<br />");
}

```
##### Output:

	Enter your number: 5

    5 4 3 2 1
    5 4 3 2 1
    5 4 3 2 1
    5 4 3 2 1
    5 4 3 2 1
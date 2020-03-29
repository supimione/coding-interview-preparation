## Print the pattern below:
    4 4 4 4
    3 3 3 
    2 2
    1 

### Source Code

```javascript

var num = prompt("Enter your number: ");

for(var i=num; i>=1; i--)
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

    5 5 5 5 5
    4 4 4 4
    3 3 3 
    2 2 
    1
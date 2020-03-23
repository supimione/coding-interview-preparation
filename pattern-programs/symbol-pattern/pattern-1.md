## Print the pattern below:
    * * * *
    * * * *
    * * * * 
    * * * *

### Source Code

```javascript

var num = prompt("Enter your number: ");

for(var i=1; i<=num; i++)
{
    for(var j=1; j<=num; j++)
    {
        document.write(" *");
    }
    document.write("<br />");
}

```
##### Output:

	Enter your number: 5

    * * * * *
    * * * * *
    * * * * *
    * * * * *
    * * * * *
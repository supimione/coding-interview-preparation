## Find factors of a number in JS

> In this program, you'll learn to find the factors of a number using the for loop.

### Source Code

```javascript

// Take inputs from the user
var n = prompt("Enter a number: ");

document.write("The factor of " +n+ " are : ");

for(var i=1; i<=n; i++)
{
    if(n%i==0)
    {
        document.write(i, "\n");
    }
}

```
##### Output:

    Enter a number: 50
    The factor of 50 are : 1 2 5 10 25 50


**Note:** To find the factors of another number, change the value of num.

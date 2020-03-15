## Display the multiplication Table

> This program displays the multiplication table of variable num (from 1 to 10).

In the program below, we have used the for loop to display the multiplication table of `num`.


### Source Code

```javascript

// Multiplication table (from 1 to 10) in JavaScript

// To take input from the user
num = prompt("Display multiplication table of : ");

// Iterate 10 times from i = 1 to 10
for(i=1; i<=10; i++)
{
    table  = i * num;
    document.write(num, " x ", i, ' = ', table, '<br />');
}

```
##### Output:

    Display multiplication table of : 11
    11 x 1 = 11
    11 x 2 = 22
    11 x 3 = 33
    11 x 4 = 44
    11 x 5 = 55
    11 x 6 = 66
    11 x 7 = 77
    11 x 8 = 88
    11 x 9 = 99
    11 x 10 = 110
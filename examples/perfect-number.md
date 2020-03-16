## check if a number is perfect or not in Javascript

In number theory, a perfect number is a positive integer that is equal to the sum of its proper positive divisors, that is, the sum of its positive divisors excluding the number itself (also known as its aliquot sum). Equivalently, a perfect number is a number that is half the sum of all of its positive divisors (including itself).

Example : The first perfect number is 6, because 1, 2, and 3 are its proper positive divisors, and 1 + 2 + 3 = 6. Equivalently, the number 6 is equal to half the sum of all its positive divisors: ( 1 + 2 + 3 + 6 ) / 2 = 6. The next perfect number is 28 = 1 + 2 + 4 + 7 + 14. 


### Source Code

```javascript

// check the number is perfect or not
var i, sum=0;
var num = prompt("Enter a number: ");

for(i=1; i<=num/2; i++)
{
    if(num % i == 0)
    {
        sum += i;
    }
}

if(sum == num)
{
    document.write(num+ " is a perfect number.");
}
else
{
    document.write(num+ " is not a perfect number.");
}

```
##### Output:

    Enter a number: 28
	28 is a perfect number.


### Source Code: Using function

```javascript

// check perfect or not using function

function is_perfect(number)
{
    var temp = 0;
    for(var i=1;i<=number/2;i++)
    {
        if(number%i === 0)
        {
           temp += i;
        }
    }
   
    if(temp === number && temp !== 0)
    {
       console.log("It is a perfect number.");
    } 
     else
    {
       console.log("It is not a perfect number.");
    }   
}

is_perfect(28);

```
##### Output:

	It is a perfect number.

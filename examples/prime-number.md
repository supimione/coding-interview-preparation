## Find the Prime Number

> Example to check whether an integer is a prime number or not using for loop and if...else statement. If the number is not prime, it's explained in output why it is not a prime number.

A positive integer greater than 1 which has no other factors except 1 and the number itself is called a prime number. 2, 3, 5, 7 etc. are prime numbers as they do not have any other factors. But 6 is not prime (it is composite) since, `2 x 3 = 6`.

### Source Code

```javascript

// Program to check if a number is prime or not

var i,flag=0,n;

var n = Number(prompt("Enter a Number:"))
for(i=2; i<=n/2; i++)
{
	if(n % i == 0)
	{
		flag = 1;
		break;
	}
}

if(flag == 0)
{
	document.write(n+ " is a Prime Number");
}
else
{
	document.write(n+ " is not a Prime Number");
}

```
##### Output:
   
	4 is not a Prime Number
    7 is a Prime Number
    
    
In this program, variable num is checked if it's prime or not. Numbers less than or equal to 1 are not prime numbers. Hence, we only proceed if the num is greater than 1.

We check if num is exactly divisible by any number from 2 to num - 1. If we find a factor in that range, the number is not prime. Else the number is prime.

We can decrease the range of numbers where we look for factors.

In the above program, our search range is from 2 to num - 1.

We could have used the range, [2, num/2] or [2, num ** 0.5]. The latter range is based on the fact that a composite number must have a factor less than the square root of that number. Otherwise, the number is prime.

You can change the value of variable num in the above source code to check whether a number is prime or not for other integers.

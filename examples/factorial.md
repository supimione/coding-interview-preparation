## Find the Factorial of a Number

> In this program, you'll learn to find the factorial of a number and display it.

Factorial of number is nothing but the same number is multiplied by all numbers less than that number up to 1 and Factorial is denoted by ! symbol.

For example, the factorial of `5` is `5! = 5*4*3*2*1 = 120`. Factorial is not defined for negative numbers, and the factorial of zero is one, `0! = 1`.

### Source Code

```javascript

// To find the factorial of a number provided by the user

var i, fact = 1;    
var num = prompt("Enter a valid Number:");

for(i=1; i<=num; i++)
{
    fact = fact * i;
}

document.write("The factorial of " + num + " is " + fact );

```
##### Output:
   
	Enter a valid Number: 0
    The factorial of 10 is 3628800


### Source Code: Using the recursive function.

> Recursive Method: In this approach, we are calling the same function again and again to get the factorial of a number.

```javascript

// To find the factorial Using the recursive function

function Factorial( num )
{
    if(num > 0){
        console.log(num * Factorial( num-1 ));
    }
    else if(num == 0)
    {
        console.log("1");
    }
    else
    {
        console.log("Sorry, factorial does not exist for negative numbers");
    }
}


```
##### Output:
   
	Factorial(5)
    120


Here, the number whose factorial is to be found is stored in `num`, and we check if the number is negative, zero or positive using `if...elif...else` statement. 

###### Conclusion

So, Factorial being an important operation in mathematics, it is easy to implement it in the JavaScript. JavaScript allows us to perform dynamic operations such as getting the number and performing operations on it at runtime. We have seen the different ways by which we can calculate the factorial in JavaScript.
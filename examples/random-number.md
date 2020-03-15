## Generate a Random Number

> In this example, you will learn to generate a random number in JavaScript.

To generate a random number in JavaScript, `Math.random()` function is used. This function is defined in random module.

**Parameters**: This function does not accepts any parameter.

**Return Value**: The `math.random()` function returns a floating-point, pseudo-random number between range `[0,1)` , `0 (inclusive)` and `1 (exclusive)`.
                
### Source Code

```javascript

// Generate a random number 
var random = Math.random( ); 
document.write("Random Number Generated : " + random );

//or,

// Returns a random integer between 0 and 100
Math.floor(Math.random() * 101);

// Returns a random integer between 1 and 100
Math.floor(Math.random() * 100) + 1;

//or,

// Return a random number between the user range
var min = Number(prompt("Enter the minimum range:")); 
var max = Number(prompt("Enter the minimum range:")); 

var random = Math.random() * (+max - +min) + +min; 

document.write("The Random Number is : " + random );

```

##### Output 1

    Random Number Generated : 0.0019239408540965

##### Output 2

    4
    5

##### Output 3

	Enter the minimum range: 4
    Enter the minimum range: 6
    The Random Number is : 4.0019239408540965


Now, `Math.floor()` function in JavaScript is used to round off the number passed as a parameter to its nearest integer in Downward direction of rounding i.e. towards the lesser value.

    Input: Math.floor(4.0019239408540965)
    Output: 4

### Source Code: Using Function

```javascript

// Function to generate random number

function randomNumber(min, max) 
{  
    return Math.random() * (max - min) + min; 
    return Math.floor(Math.random() * (max - min) + min); 
}  
  
document.write("Random Number between 1 and 100: ")  
  
// Function call 
document.write( randomNumber(1, 100) );

```

##### Output 3

	Random Number between 1 and 100: 25
## Program to find LCM of two numbers

> In this program, you'll learn to find the LCM of two numbers and display it.

LCM (Least Common Multiple) of two numbers is the smallest number which can be divided by both numbers.
For example: LCM of 15 and 20 is 60 and LCM of 5 and 7 is 35.

### Source Code

```javascript

// JS program to find LCM of two numbers 
  
// return gcd of a and b 
function gcd(a, b) 
{ 
   if (a == 0) 
        console.log b; 
    console.log gcd(b % a, a); 
}
  
// Function to return LCM 
// of two numbers 
function lcm(a, b) 
{ 
    console.log (a * b) / gcd(a, b); 
} 
    console.log "LCM of ",$a, " and ",$b, " is ", lcm($a, $b); 
  

```
##### Output:

    Enter Year: 2000
	2000 is a Leap Year.


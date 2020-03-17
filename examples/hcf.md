## Check if year is leap year or not

> GCD (Greatest Common Divisor) or HCF (Highest Common Factor) 

The GCD of two or more integers is the largest integer that divides each of the integers such that their remainder is zero.

Example-
- GCD of 20, 30 = 10 (10 is the largest number which divides 20 and 30 with remainder as 0)

### Source Code

```javascript

// JS program to find GCD or HCF of two numbers 

// return GCD of a and b 
function gcd(a, b) 
{ 
   if (a == 0) 
        return b; 
    return gcd(b % a, a); 
}
gcd(24,36)

```
##### Output:

    12

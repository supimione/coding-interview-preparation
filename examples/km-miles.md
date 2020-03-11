## Convert Kilometers to Miles

> In this example, we'll learn to convert kilometers to miles and display it.


### Source Code: Kilometers to Miles

```javascript

// Convert KM to Miles

var user_imput = prompt("Enter the value in KM:");    // Taking kilometers input from the user

//conversion factor
var KM = 0.621371;

//calculate miles
var Miles = KM * user_imput;

//using fixed-point notation
var value = Miles.toFixed(2)

document.write(user_imput + " KM = " +value+  " Miles");

```
##### Output:
   
	Enter the value in KM: 20.8
    20.8 KM = 12.92 Miles


Here, the user is asked to enter kilometers. This value is stored in the kilometers variable.

Since `1` kilometer is equal to `0.621371` miles, we can get the equivalent miles by multiplying kilometers with this factor.

##### Note:  Modify the above program to convert miles to kilometers using the following formula and run it.

    KM = Miles / user_imput

### Source Code: Miles to Kilometers

```javascript

// Convert Miles to KM

var user_imput = prompt("Enter the value in Miles:");    // Taking Miles input from the user

//conversion factor
var Miles = 1.60934;

//calculate miles
var KM = Miles / user_imput;

//using fixed-point notation
var value = Miles.toFixed(2)

document.write(user_imput + " Miles = " +value+  " KM");

```
##### Output:
   
	Enter the value in Miles: 20.8
    20.8 Miles = 1.61 KM


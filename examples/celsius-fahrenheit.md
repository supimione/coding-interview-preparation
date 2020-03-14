## Convert Celsius To Fahrenheit

> In this program, you'll learn to convert Celsuis to Fahrenheit and display it.

    Fahrenheit to Celsius : (°F − 32) / 1.8 = °C
    Celsius to Fahrenheit : (°C * 1.8) + 32 = °F

### Source Code: Celsius To Fahrenheit

```javascript

// Convert Celsius To Fahrenheit
var Celsius = prompt("Enter Temperature in Celsius:");    

// formula
var Fahrenheit = (Celsius * 1.8) + 32;

document.write(Celsius + " °C is equal to " + Fahrenheit + "°F");

```
##### Output:
   
	Enter Temperature in Celsius:20
    20 °C is equal to 68°F


### Source Code: Fahrenheit To Celsius

```javascript

// Convert Fahrenheit to Celsius
var Fahrenheit = prompt("Enter Temperature in Fahrenheit:");   

// Formula
var Celsius = (Fahrenheit - 32) / 1.8;

document.write(Fahrenheit + " °F is equal to " + Celsius + "°C");

```
##### Output:
   
	Enter Temperature in Fahrenheit: 45
    45°F is equal to 7.22°C


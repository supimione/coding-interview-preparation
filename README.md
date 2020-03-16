# JavaScript Programming

> To run this program open browser console  `Ctrl+Shift+J` and copy-paste the program and see your output.

For debugging and testing purposes, we can use the `console.log()` and `document.write()` method to display data.

## Popular Examples
   1.  [Print Hello World](examples/hello-world.md)
   2.  [Add Two Numbers](examples/add-number.md)
   3.  [Find the Square Root](examples/square-root.md)
   4.  [Calculate the Area of a Triangle](examples/area-triangle.md)
   5.  [Swap Two Variables](examples/swap-variables.md)
   6.  [Generate a Random Number](examples/random-number.md)
   7.  [Convert Kilometers to Miles](examples/km-mile.md)
   8.  [Convert Celsius to Fahrenheit](examples/celsius-fahrenheit.md)
   9. [Check if a Number is Positive, Negative or 0](examples/positive-negative-zero.md)
   10. [Check if a Number is Odd or Even](examples/odd-even.md)
   11. [Check Leap Year](examples/leap-year.md)
   12. [Find the Largest Among Three Numbers](examples/largest-number-three.md)
   13. [Check Prime Number](examples/prime-number.md)
   14. [Print all Prime Numbers in an Interval](examples/prime-number-intervals.md)
   15. [Find the Factorial of a Number](examples/factorial.md)
   16. [Display the multiplication Table](examples/multiplication-table.md)
   17. [Print the Fibonacci sequence](examples/fibonacci-sequence.md)
   18. [Check Armstrong Number](examples/armstrong-number.md)
   19. [Find Armstrong Number in an Interval](examples/armstrong-interval.md)
   20. [Find the Sum of Natural Numbers](examples/sum-natural-number.md)
   21. [Display Powers of 2 Using Anonymous Function](examples/power-anonymous.md)
   22. [Find Numbers Divisible by Another Number](examples/number-divisible.md)
   23. [Convert Decimal to Binary, Octal and Hexadecimal](examples/conversion-binary-octal-hexadecimal.md)
   24. [Find ASCII Value of Character](examples/ascii-character.md)
   25. [Find HCF or GCD](examples/hcf.md)
   26. [Find LCM](examples/lcm.md)
   27. [Find the Factors of a Number](examples/factor-number.md)
   28. [Make a Simple Calculator](examples/calculator.md)
   29. [Shuffle Deck of Cards](examples/shuffle-card.md)
   30. [Display Calendar](examples/calendar.md)
   31. [Multiply Two Matrices](examples/multiply-matrices.md)
   32. [Add Two Matrices](examples/add-matrices.md)
   33. [Check Whether a String is Palindrome or Not](examples/palindrome.md)
   34. [Remove Punctuations From a String](examples/remove-punctuation.md)
   35. [Sort Words in Alphabetic Order](examples/alphabetical-order.md)
   36. [Count the Number of Each Vowel](examples/count-vowel.md)
   37. [Merge Mails](examples/merge-mails.md)
   38. [Find the Size (Resolution) of a Image](examples/resolution-image.md)
   39. [Find Hash of File](examples/hash-file.md)
   40. [Check Perfect Number or Not](examples/perfect-number.md)



### Javascript Method

#### alert(), document.write(), console. log() Method
The `alert()` function will display text in a dialog box that pops up on the screen.

The `document.write()` method is mostly used for testing purpose. If it is used after an HTML document is fully loaded, it will delete all existing HTML.

The `console. log()` method writes a message to the console. The console is useful for testing purposes. When testing this method, be sure to have the console view visible (press `Ctrl+Shift+J`).



#### prompt()
The `prompt()` method is used to display a dialog with an optional message prompting the user to input some text.

A prompt box is often used if you want the user to input a value before entering a page.

It returns a `string` containing the text entered by the user, or `null`.

##### Syntax:
   prompt(message, defaultText)

##### Parameter Values:
Parameter  | Type | Description
---------  | ---- | -----------
message    | String | Required. The text to display in the dialog box to the user.
defaultText| String | Optional. The dfault value displayed in the text input field.



#### Math.sqrt()
The `Math.sqrt()` function in JavaScript is used to square root of the number passed as parameter to the function.

    Math.sqrt(value)

- **Parameters**: This function accepts a single parameter value which hold the number whose square root is to be calculated.
- **Returns**: The method returns the square root of a number. If `value` is a negative number, NaN is returned



#### Math.random()
`Math.random()` function always returns a random number between min(included) and max(excluded).

##### Syntax:
	Math.random()


#### Math.floor()
Now, `Math.floor()` function in JavaScript is used to round off the number passed as a parameter to its nearest integer in Downward direction of rounding i.e. towards the lesser value.

    Input: Math.floor(4.0019239408540965)
    Output: 4
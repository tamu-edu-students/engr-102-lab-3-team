# ENGR 102 Lab Topic 3 (team)

## Activities
This lab consists of two team activities. Please submit the following files to Gradescope. Please include the team header information at the top of each file with the names of all contributing team members. This is a team assignment, but **everyone** must submit the files for credit. You may discuss the problems with other teams, but your submitted work must be unique. Check out the [Frequently Asked Questions](#frequently-asked-questions) below. 

1. [Unit Conversions](#unit-conversions)
2. [Still More Linear Interpolation](#still-more-linear-interpolation)

## Unit Conversions
This activity is meant to help illustrate the process of asking a user for input, reading the input, processing a computation, and outputting a result. Many programs will follow that basic format. Unit conversions (and print statements) may seem to be a trivial exercise, but it can be critically important to do it correctly as mishandling the proper communication of units can lead to project failure or even loss of human life. Please search and read a little bit about the Mars Climate Orbiter, and read the two links below:

- [Wikipedia page on the Mars Climate Orbiter](https://en.wikipedia.org/wiki/Mars_Climate_Orbiter)
- [Why the Mars probe went off course](https://spectrum.ieee.org/why-the-mars-probe-went-off-course)

Write one program that prompts the user to enter one number, stores it in an appropriately named variable, performs the necessary calculations, and outputs the results to the screen with proper labels and two (2) decimal places for each unit conversion listed below. Write a single program named `unit_conversions.py` that outputs all conversions.

1. Pounds (force) to Newtons
2. Meters to feet
3. Atmospheres to kilopascals (kPa)
4. Watts to BTU per hour
5. Liters per second to US gallons per minute
6. Degrees Celsius to degrees Fahrenheit

Example output (using input `1`):
```
Please enter the quantity to be converted: 1
1.00 pounds force is equivalent to 4.45 newtons
1.00 meters is equivalent to 3.28 feet
1.00 atmospheres is equivalent to 101.33 kilopascals
1.00 watts is equivalent to 3.41 BTU per hour
1.00 liters per second is equivalent to 15.85 US gallons per minute
1.00 degrees Celsius is equivalent to 33.80 degrees Fahrenheit
```

As always, please include descriptive comments in your code so that someone may follow your programming logic.


## Still More Linear Interpolation
description

## Frequently Asked Questions
1. **Gradescope says I have an extra new line character (`\n`) and won't give me points. What gives?** Remember, `print()` statements automatically add a new line character (`\n`), but `input()` statements do not! Try moving your text inside your `input()` statement when taking input from the keyboard.

2. **I'm having trouble formatting my output. How do I do it?** Watch [this string formatting video posted with Module 3](https://mediasite.tamu.edu/Mediasite/Play/95fc0a90130d47f5802d87e1d3020ecd1d). Also check out the pdf posted on Canvas about string formatting. For more information about string formatting, check out section 3.10 in your zyBooks.

3. **Right, but I'm still having trouble with my output. The answer is 1.00 but it only displays 1.0. Why?** Are you using the `round()` function? I hate the `round()` function because it cuts off extra zeros at the end. Use a different string formatting method to display all necessary zeros!

4. **My output still doesn't match but I can't find what's wrong. Help?** Look at your failed test and see which character(s) are marked with a `^`. Those don't match the solution output! Remember, your capitalization, spelling, and punctuation need to match *exactly*!

Have a question you don't see here? Email your instructor!

Based upon Dr. Keyser’s Original<br/>
Revised Summer 2025 SNR

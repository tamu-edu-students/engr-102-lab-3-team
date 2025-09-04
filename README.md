# ENGR 102 Lab Topic 3 (team)

## Activities
This lab consists of two team activities. Please submit the following files to Gradescope. Please include the team header information at the top of each file with the names of all contributing team members. This is a team assignment, but **everyone** must submit the files for credit. You may discuss the problems with other teams, but your submitted work must be unique. Check out the [Frequently Asked Questions](#frequently-asked-questions) below. 

1. [Unit Conversions](#unit-conversions)
2. [Still More Linear Interpolation](#still-more-linear-interpolation)

## Unit Conversions
This activity is meant to help illustrate the process of asking a user for input, reading the input, processing a computation, and outputting a result. Many programs will follow that basic format. Unit conversions (and print statements) may seem to be a trivial exercise, but it can be critically important to do it correctly as mishandling the proper communication of units can lead to project failure or even loss of human life. Please search and read a little bit about the Mars Climate Orbiter, and read the two links below:

- [Wikipedia page on the Mars Climate Orbiter](https://en.wikipedia.org/wiki/Mars_Climate_Orbiter)
- [Why the Mars probe went off course](https://spectrum.ieee.org/why-the-mars-probe-went-off-course)

Write one program that prompts the user to enter one number, stores it in an appropriately named variable, performs the necessary calculations, and outputs the results to the screen with proper labels and two (2) decimal places for each unit conversion listed below. Write a single program named `unit_conversions.py` that outputs all conversions. As always, please include descriptive comments in your code so that someone may follow your programming logic.

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

**Note:** 1 watt is equal to 3.41214163 BTU per hour, and 1 liter is equal to 0.264172052 US gallons


## Still More Linear Interpolation
This activity is meant to give your team experience writing a larger program together. Your program should take as input the time and location of a moving object at two points, then using linear interpolation calculate the position at several intermediate times. Your program needs to perform the following tasks:

- Prompt the user to enter the time and position at two points (see example output below)
- Use interpolation to calculate the times and positions for three evenly spaced points between the two points entered by the user
- Print the results using nice formatting
  - Display the times using two (2) decimal places
  - Display the positions using three (3) decimal places

**Before writing your program:**</br>
*It’s good practice to think before you code.* As a team, follow the steps below.
1. Make a list of the variables that your team will use in this program. Be sure to include:
   - The variable names
   - The type of each variable (data type)
   - A very brief description of what each variable is (you can write one description for multiple variables if it is clear what they all are)
2. Write a brief description of the calculations your program will perform, including a sample calculation done by hand.
3. Finally, write your code *as a team*. Please name this file `still_more_linear_interpolation.py` for submission. Remember to test you code to make certain it works properly.

Example output (for inputs `1`, `1`, `1`, `1`, `2`, `2`, `2`, and `2`):
```
Enter time 1: 1
Enter the x position of the object at time 1: 1
Enter the y position of the object at time 1: 1
Enter the z position of the object at time 1: 1
Enter time 2: 2
Enter the x position of the object at time 2: 2
Enter the y position of the object at time 2: 2
Enter the z position of the object at time 2: 2

At time 1.00 seconds the object is at (1.000, 1.000, 1.000)
At time 1.25 seconds the object is at (1.250, 1.250, 1.250)
At time 1.50 seconds the object is at (1.500, 1.500, 1.500)
At time 1.75 seconds the object is at (1.750, 1.750, 1.750)
At time 2.00 seconds the object is at (2.000, 2.000, 2.000)
```


## Frequently Asked Questions
1. **Gradescope says I have an extra new line character (`\n`) and won't give me points. What gives?** Remember, `print()` statements automatically add a new line character (`\n`), but `input()` statements do not! Try moving your text inside your `input()` statement when taking input from the keyboard.

2. **I'm having trouble formatting my output. How do I do it?** Watch [this string formatting video posted with Module 3](https://mediasite.tamu.edu/Mediasite/Play/95fc0a90130d47f5802d87e1d3020ecd1d). Also check out ![this pdf](String_Format_Printing.pdf) (also posted on Canvas) about string formatting. For more information about string formatting, check out section 3.10 in your zyBooks.

3. **Right, but I'm still having trouble with my output. The answer is 1.00 but it only displays 1.0. Why?** Are you using the `round()` function? I hate the `round()` function because it cuts off extra zeros at the end. Use a different string formatting method to display all necessary zeros!

4. **My output still doesn't match but I can't find what's wrong. Help?** Look at your failed test and see which character(s) are marked with a `^`. Those don't match the solution output! Remember, your capitalization, spelling, and punctuation need to match *exactly*!

Have a question you don't see here? Email your instructor!

Based upon Dr. Keyser’s Original<br/>
Revised Summer 2025 SNR

# Height Converter Project
For this assignment, write a complete program that prints your name, age, your height in inches, and - using the fact that there are 2.54 centimeters in an inch - your height in centimeters.
The objectives of this assignment are to:

- Be able to write a Java class definition with a main method.
- Be able to declare and initialize variables of type int, double, and String.
- Be able to use a mathematical operator to calculate a value and assign it to a variable.
- Be able to use the concatenation operator to combine Strings with variables in statements that print to the console.
  A sample solution output is given below:

```
Pat Wilson
age: 22
height: 67 inches
height: 170.18 cm
```

Project Requirements:

- Your class must be named HeightConverter.
- Your solution must be a complete class, enclosing a main method.
- You must declare a double variable named conversionFactor that is initialized to 2.54.
- You must declare a String variable named myName that is initialized to your name, i.e. "Pat Wilson".
- You must declare an int variable named myAge that is initialized to your age in years.
- You must declare an int variable named myHeightInches that is initialized to your height in inches.
- You must declare a double variable named myHeightCM that is initialized to the product of the variables myHeightInches and conversionFactor. You must use the appropriate variables from the list above in the calculation. You will not receive credit for "hard-coded" values in your calculation, as in this example: myHeightCM = 67\*2.54 or myHeightCM = 170.18; (where you did the calculation on a calculator).
- You must write a series of print statements that produce the specified output to the console. Your print statements must use the concatenation operator to combine literal Strings, such as "age: " with the appropriate variables mentioned above. You will not receive credit for "hard-coded" values in your print statements, as in these examples, where the age value of 22 is hard-coded:
  `System.out.println("age: "+22);`
  or
  `System.out.println("age: 22");`
- Your output must match the format shown above exactly- of course the numeric values will differ, but you must follow the format shown. That means you must print the units after the values.
- Your code should be simple: no objects created, just use assignment and print statements in the main method.

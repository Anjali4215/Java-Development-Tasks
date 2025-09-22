# Temperature Converter - Java

This Java program converts temperatures between **Celsius** and **Fahrenheit** based on user input. It demonstrates basic Java concepts such as **user input**, **conditional statements**, and **arithmetic operations**.

## Features
- Convert Celsius to Fahrenheit
- Convert Fahrenheit to Celsius
- Handles invalid unit input

## How to Run
1. Clone the repository:

   git clone https://github.com/Anjali4215/Java-Development-Tasks/blob/main/Task%201/Temperature%20Converter

Compile the Java file:

Copy code
javac TemperatureConverter.java
Run the program:
Copy code
java TemperatureConverter
Enter the temperature and unit (C or F) as prompted.

Example Output

Copy code
Temperature Converter
Enter a temperature value: 37
Unit of measurement (C for Celsius, F for Fahrenheit): C
37 degree Celsius is 98.6 Fahrenheit.
Code Overview
Uses Scanner to read input from the user

Converts unit input to uppercase for consistency

Uses if-else statements to determine conversion

Calculates temperature conversion using standard formulas:

Celsius → Fahrenheit: (C * 9/5) + 32

Fahrenheit → Celsius: (F - 32) * 5/9

Displays result to the user

Handles invalid unit input

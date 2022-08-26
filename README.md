# Decimal to any Radix-i (Base 2 to 16) Converter  

This main file is a program written in C, that will convert from a positive decimal to any radix-i (bases being from 2 to 16) number.

The main file consists of 2 custom functions:

- The "log_a_to_base_b," which uses the built-in log2 function to convert any 2 input (a, b) to return a value a from logb.

- The "Dec2RadixI" is the function that converts from base 10 to any base from 2 to 16.

The main file greets the user upon execution and prompts the user to enter a decimal value.

"""
*****************************
DECIMAL TO RADIX-i converter
Written by: Simiso and Aldo
Date: 2022
*****************************


Enter positive decimal number: 
"""

Upon entering a number (ie., 134435) it then asks you for a radix-i between 2 and 16 (i.e, 16).

"""
*****************************
DECIMAL TO RADIX-i converter
Written by: Simiso and Aldo
Date: 2022
*****************************


Enter positive decimal number: 134435
The number you have entered is 134435

Enter a radix for the converter between 2 and 16: 16
The radix you have entered is 16
The log2 of the number is 17.04

The integer result of the number divided by 16 is 8402
The remainder is 3

The radix-16 value is {20D23}(BASE_16)

Enter positive decimal number: 
"""

It returns the log2 of the decimal number and the radix-16 of the number, and it loops again and prompts the user to enter another decimal values until a negative number is entered which EXIT from the execution.

"""
*****************************
DECIMAL TO RADIX-i converter
Written by: Simiso and Aldo
Date: 2022
*****************************


Enter positive decimal number: 
The number you have entered is 134435

Enter a radix for the converter between 2 and 16: 16
The radix you have entered is 16
The log2 of the number is 17.04

The integer result of the number divided by 16 is 8402
The remainder is 3

The radix-16 value is {20D23}(BASE_16)

Enter positive decimal number: -1
EXIT
"""


The main file also has parameters set within it, such as if the user enters a radix greater than 16 or less than 2, it will again remind the user that the number should be between 2 and 16, and this reminder will persist until the acceptable numbers are entered.

"""
*****************************
DECIMAL TO RADIX-i converter
Written by: Simiso and Aldo
Date: 2022
*****************************


Enter positive decimal number: 134435
The number you have entered is 134435

Enter a radix for the converter between 2 and 16: 1
Radix value must be between 2 and 16: 25
Radix value must be between 2 and 16: 
"""

Other parameters are such that only integer decimal numbers are used in this converter. So if a user enters a fraction it will be converted to an integer and that is handled in the backend.

# C++ Valid Date Checker

A C++ program that validates a given date by checking the month and the number of days based on the year.

## Features

- Read a complete date from the user
- Check whether the month is valid
- Check whether the day is valid
- Handle leap years
- Calculate the correct number of days in February
- Validate the complete date using a reusable function

## Concepts Practiced

- Structures
- Functions
- Const References
- Boolean Logic
- Conditional Operator
- Arrays
- Leap Year Calculation
- Date Validation
- Input Handling

## Date Validation

The program checks two main conditions:

1. The month must be between 1 and 12.
2. The day must be between 1 and the maximum number of days in the selected month.

For February, the number of days depends on whether the year is a leap year.

## Main Function

The date validation is handled by:

```cpp
bool IsValidDate(const stDate& Date)

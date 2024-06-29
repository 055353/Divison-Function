# Divison-Function
This Python script performs division of two user-provided numbers and handles potential errors gracefully.
## Functionality

The script defines a function `division(number1, number2)` that returns the result of dividing `number1` by `number2`. The function uses `try` and `except` blocks to handle division by zero and other potential errors.

## Usage

1. Run the script.
2. Enter two numbers when prompted.
3. The script will print the result of the division or an error message if an invalid input is provided.

## Example

Please enter the first number:
10
Please enter the second number:
2
5.0
### `division(number1, number2)`

Performs division of two numbers.

#### Parameters:
- `number1` (int or float): The numerator.
- `number2` (int or float): The denominator.

#### Returns:
- `float`: The result of the division if successful. If a division by zero occurs, an appropriate message is printed. If an index error occurs, an appropriate message is printed (though this is unlikely in this context).

### Error Handling

- If a division by zero occurs, the message "Can't divide by zero" is printed.
- If the input for the numbers is not an integer, the message "Please enter a valid number" is printed.

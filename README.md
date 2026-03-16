# Python Program: Find the Greatest of Three Numbers

## Description

This program finds the **greatest number among three numbers** entered by the user.
The user inputs three numbers, and the program compares them using conditional statements to determine which one is the largest.

## How the Program Works

1. The program asks the user to enter three numbers.
2. Each number is stored in a variable.
3. The program compares the numbers using **if-elif conditions**.
4. It prints which number is the greatest.

## Code Example

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

if num1 > num2 and num1 > num3:
    print("num1 is greatest")
elif num2 > num1 and num2 > num3:
    print("num2 is greatest")
else:
    print("num3 is greatest")
```

## Requirements

* Python 3.x installed on your system.

## How to Run

1. Save the program in a file named `greatest_number.py`.
2. Open a terminal or command prompt.
3. Navigate to the folder where the file is saved.
4. Run the program using:

```
python greatest_number.py
```

## Example Output

```
Enter first number: 12
Enter second number: 25
Enter third number: 7
num2 is greatest
```

## Author

Muhammad Ali

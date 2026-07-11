# Reverse Number
## Description
This project is a Python program that demonstrates the use of for loop in Python. A **for loop** is used to execute a block of code repeatedly by iterating over a sequence such as range, list, string or tuple.
## Syntax
```python
for variable in sequence:
    # Code to execute
```
## Concepts Used
- Variables
- range()
- for() loop
## Technologies Used
- Pycharm
- Python 3
## Working
1. The program asks the user to enter a number.
2. A variable reverse is initialized to 0 to store the reversed number.
3. len(str(num)) calculates the total number of digits in the entered number.
4. The for loop runs once for each digit.
5. In every iteration:
- num % 10 extracts the last digit of the number.
- reverse = reverse * 10 + digit appends the extracted digit to the reversed number.
- num = num // 10 removes the last digit from the original number.
6. The loop continues until all digits have been processed.
7. Finally, the program displays the reversed number.
## How to run
1. Clone the repository.
2. Open the project in Pycharm.
3. Run the 'main.py' file.
4. View the result.
## Sample Output
```text
Enter a number: 12345

The reverse number is: 54321
```
## Author
- Sadia
- Github: [sadiacode](https://github.com/sadiacode)

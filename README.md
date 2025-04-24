### Name : LOKESH M
### Reg No : 212224040173
# Experiment-13
## Pytest Python program for Sum of Digits 
# Aim: 
To write a python program for sum of digits and test the test cases using Pytest. 

# Algorithm
Step 1: Write the python program for sum of digits of a number.

Step 2: Make sure that function name should be “def test_*():” and the line to be tested
should have assert keyword at the beginning.

Step 3: Write some test cases for to be tested and save it as “test_sumofdig.py”.

Step 4: Open command prompt and change the directory to where pytest and program is
saved and type “pytest test_sumofdig.py” and run it.

Step 5: Stop the program. 
# Program:
```python
def sumOfDigits(n): 
    sum = 0 
    while (n != 0): 
        sum = sum + int(n % 10) 
        n = int(n/10) 
    return sum 
def test_1(): 
    assert sumOfDigits(123) == 6 
def test_2(): 
    assert sumOfDigits(256) == 2 
```
# Output
![Screenshot 2025-03-29 105707](https://github.com/user-attachments/assets/2d901b04-7f22-4474-9bc5-8e9a866357b4)

# Result
Thus, the python program for sum of digits is tested using pytest and executed and 
output is verified successfully.

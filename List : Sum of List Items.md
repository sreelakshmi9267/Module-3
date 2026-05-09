# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = list(map(int, input("Enter numbers: ").split()))

total = 0
for num in numbers:
    total += num

print("Sum of all elements:", total)

```
## Output
<img width="1208" height="252" alt="Screenshot 2026-05-09 215457" src="https://github.com/user-attachments/assets/9dc1823a-bb9e-45ae-a2fa-4da124097022" />

### Result  
The program was executed successfully. It reads a list of integers from the user, calculates the sum of all elements using a loop, and prints the correct result.  

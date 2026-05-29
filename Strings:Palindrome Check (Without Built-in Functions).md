# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```python
s = "google"
rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```
## Output
<img width="446" height="32" alt="ex-4 m-3" src="https://github.com/user-attachments/assets/d3015245-c968-4593-b03b-792c44d5c45b" />

## Result
The code was executed successfully byb using python

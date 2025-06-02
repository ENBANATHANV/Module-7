# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

## 💻 PROGRAM:
```
def is_palindrome(word):
    if len(word) < 1:
        return True
    if word[0] == word[-1]:
        return is_palindrome(word[1:-1])
    return False

# Get user input
text = input("Enter a word: ")

# Check and print result
if is_palindrome(text):
    print("It's a palindrome!")
else:
    print("Not a palindrome.")
```
## OUTPUT
![image](https://github.com/user-attachments/assets/d53b80c7-95e1-4c33-8c27-16925d686b79)

## RESULT
Program executed successfully.

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

~~~
a="google"
rev=a[::-1]
if a==rev:
   print("The string is a palindrome")
else:
   print("The string is not a palindrome")
~~~
## Output
<img width="805" height="195" alt="image" src="https://github.com/user-attachments/assets/e2a5f71b-751d-4dbf-a7bf-11ada31b133d" />

## Result
Thus, the program has been executed successfully.

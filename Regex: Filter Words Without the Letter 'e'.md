# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = []

for word in items:

    if not re.search(r'e', word):
        result.append(word)

print("Words without 'e':", result)

~~~
## Output
<img width="967" height="311" alt="image" src="https://github.com/user-attachments/assets/73ee7538-d383-40a9-a8f1-d055324e208f" />


## Result
Thus , the program has been executed successfully

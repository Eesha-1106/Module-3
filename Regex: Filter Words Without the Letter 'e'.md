# 2. Regex in Python: Filter Words Without the Letter 'e'

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
```python
import re

words_list = ['apple', 'banana', 'cherry', 'plum', 'kiwi', 'grape']
pattern = re.compile(r'^[^eE]*$')

filtered_list = [word for word in words_list if pattern.match(word)]
print(filtered_list)
```
## Output
![image](https://github.com/user-attachments/assets/2ba54972-bf35-491a-9dcf-470820d4ad95)


## Result

code has been executed successfully.

---


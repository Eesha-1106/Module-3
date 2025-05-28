# 3. 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```python
# Accept input string and index
input_string = input("Enter a string: ")
index = int(input("Enter the index of the character to remove: "))

# Check if the index is valid
if 0 <= index < len(input_string):
    result = input_string[:index] + input_string[index+1:]
    print("String after removal:", result)
else:
    print("Invalid index!")
```
## Output
![image](https://github.com/user-attachments/assets/5e92a770-bcf1-4c7d-b2eb-d3dbe5c52829)


## Result
program executed successfully.

---


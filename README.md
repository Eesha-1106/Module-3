# Module 2

## Name : Eesha Ranka
## Reg No : 212224240040

# 1. List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```python
n=[1,2,-8]
sum=0
for i in n:
    sum+=i
print(sum)

```

## Output
![image](https://github.com/user-attachments/assets/09ce2f4c-0cff-4fb0-934c-072638a1e25b)


## Result
program executed successfully

---

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

# 4. Strings-Palindrome Check in Python (Without Built-in Functions)

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
def palindrome(a):
    if a==a[::-1]:
        print(f"The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
        
  
    
        
        
string =input()
palindrome(string)
```

## Output
![image](https://github.com/user-attachments/assets/e501abc5-880f-4cf8-b08b-567c496ab29a)


## Result
program executed successfully.

---

# 5. Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
t=eval(input())
print('n' not in t)
print('8' in t)
```

## Output
![Screenshot 2025-05-25 122042](https://github.com/user-attachments/assets/c54c83fb-88c3-4687-885d-a02c208918d8)



## Result
code executed successfully.

<img width="924" height="321" alt="image" src="https://github.com/user-attachments/assets/eb5a8f1c-f5e9-42e8-b251-44f3b25536b6" /># Module-3
# 🧹 Strings-Remove Nth Index Character from a String

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
```
def slice(s):
    sub=s[2:10]
    reversed_sub=sub[::-1]
    alt_chars=reversed_sub[::2]
    print(f"The reversed string is '{alt_chars}' ")

```

## Output
<img width="924" height="321" alt="image" src="https://github.com/user-attachments/assets/ea79ea9f-910a-44d3-b773-45efebec23bb" />

## Result
The program is excecuted

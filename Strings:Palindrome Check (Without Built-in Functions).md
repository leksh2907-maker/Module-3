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
```
def palindrome(a):
    start=0
    last=-1
    if (a[start]== a[last]):
        start += 1
        last -= 1
        print("The entered string is palindrome")
    else:
        flag = 1
        print("The entered string is not palindrome")
string =input()
palindrome(string)
```
## Output
<img width="1283" height="287" alt="image" src="https://github.com/user-attachments/assets/0028e68c-9116-4eb4-8cd2-98a9effd5fe4" />

## Result
The program is excecuted

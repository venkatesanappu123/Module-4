# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
```
## Output
![441162772-ef9bddaf-28d9-4441-810e-08f97a40d0dc](https://github.com/user-attachments/assets/83e1ae13-b3c2-4a99-9bf9-69fbdbad755c)

## Result
Thus the program that handles an IndexError when trying to access an element beyond the available range of a list is executed successfully.


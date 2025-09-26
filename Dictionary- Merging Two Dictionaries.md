## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program:
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```
## Output:
<img width="518" height="150" alt="449556484-42b20eaa-21b8-4d8d-96f6-ea0d267c3a4d" src="https://github.com/user-attachments/assets/308d3010-c4a6-45c5-b39f-639b780da239" />

## Result:
The program was successful

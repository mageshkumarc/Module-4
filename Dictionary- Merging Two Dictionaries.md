## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge():
    merged = {**dict1, **dict2}
    print(merged)

dict1 = eval(input())
dict2 = eval(input())
merge()
```

## Output
![image](https://github.com/user-attachments/assets/468950c8-f60c-4896-afae-185d885beaae)

## Result
Thus,the program is executed successfully

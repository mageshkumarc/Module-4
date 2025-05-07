# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0

with open('story.txt', 'r') as file:
    for line in file:
        if not line.startswith('T'):
            count += 1

print(count)
```

## Output
![image](https://github.com/user-attachments/assets/eae79d3d-fd51-4e98-90f4-7476fe9d90ed)

## Result
Thus,the program is executed successfully

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
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

def merge(d1, d2):
    return {**d1, **d2}

merged_dict = merge(dict1, dict2)
print(merged_dict)

```
## Output
![image](https://github.com/user-attachments/assets/cbc1a559-f418-4e7f-b78f-2021e5d4979a)

## Result
Thus, To write a Python program that merges **two dictionaries** and combines their key-value pairs is verified and executed successfully.

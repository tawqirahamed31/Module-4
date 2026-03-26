# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
# Original dictionary
d = {'banana': 3, 'apple': 1, 'cherry': 2}

# Sort by keys
sorted_keys = dict(sorted(d.items()))

# Sort by values
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

# Display results
print("Original dictionary:", d)
print("Sorted by keys:", sorted_keys)
print("Sorted by values:", sorted_values)
```
## Sample Output
<img width="628" height="349" alt="image" src="https://github.com/user-attachments/assets/8598b145-0311-45c6-bfdc-b2aeed929bd3" />

## Result
Thus, the Python program to sort a dictionary by keys and values was successfully executed.

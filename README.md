# Python Logical Operators

Logical operators are used to combine conditional statements.  
They always return a **Boolean result**: either `True` or `False`.

---

## 📊 Logical Operators Table

| Operator | Symbol | Example | Result |
|----------|--------|---------|--------|
| AND | `and` | `(5 > 3 and 5 < 10)` | `True` |
| OR  | `or`  | `(5 > 8 or 5 < 10)` | `True` |
| NOT | `not` | `not(5 > 3 and 5 < 10)` | `False` |

---

## 📝 Explanation of Each Operator

### 1. AND (`and`)
Returns `True` if **both** conditions are true.  
```python
x = 7
print(x > 3 and x < 10)  # True because 7 is greater than 3 AND less than 10
```

---

### 2. OR (`or`)
Returns `True` if **at least one** condition is true.  
```python
x = 7
print(x > 10 or x < 10)  # True because although x > 10 is False, x < 10 is True
```

---

### 3. NOT (`not`)
Reverses the result: `True` becomes `False`, and `False` becomes `True`.  
```python
x = 7
print(not(x > 3 and x < 10))  # False because the condition is True, and NOT reverses it
```

---

## 🎉 Fun Examples

```python
# Example 1: Login system
username = "admin"
password = "1234"
print(username == "admin" and password == "1234")  # True (both correct)

# Example 2: Discount check
age = 15
student = True
print(age < 18 or student)  # True (because student is True)

# Example 3: NOT for access
logged_in = True
print(not logged_in)  # False (because logged_in is True)
```

---

## ✅ Conclusion

- **`and`** → True only if **both** conditions are True.  
- **`or`** → True if **at least one** condition is True.  
- **`not`** → Reverses the result.  

Logical operators are most powerful when combined with **comparison operators** to form complex conditions (e.g., in `if` statements).

---

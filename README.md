# 🐍 Python: Operators, Operands, and Keywords

## 🔹 Operators and Operands in Python

- **Operand**: A value or variable on which the operator acts.
- **Operator**: A symbol that performs operations (e.g., `+`, `-`, `not`).

---

## 🔹 Types of Operators

### 1. Unary Operators (1 operand)
| Operator      | Description               | Example           |
|---------------|---------------------------|-------------------|
| `-x`          | Negation (reverses sign)  | `-5` → `-5`       |
| `not`         | Logical NOT               | `not True` → `False` |
| `~x`          | Bitwise NOT (inverts bits)| `~5` → `-6`       |

### 2. Binary Operators (2 operands)
Operate between two values (e.g., `5 + 2`, `4 * 3`).

---

## 🔹 Categories of Python Operators

### ➤ Arithmetic Operators
| Operator | Function         | Example     | Result   |
|----------|------------------|-------------|----------|
| `+`      | Addition          | `5 + 2`     | `7`      |
| `-`      | Subtraction       | `5 - 2`     | `3`      |
| `*`      | Multiplication    | `5 * 2`     | `10`     |
| `/`      | Division          | `5 / 2`     | `2.5`    |
| `//`     | Floor Division    | `5 // 2`    | `2`      |
| `%`      | Modulus           | `5 % 2`     | `1`      |
| `**`     | Exponentiation    | `5 ** 2`    | `25`     |

---

### ➤ Comparison Operators

Compare values and return boolean results:
- `==`, `!=`, `>`, `<`, `>=`, `<=`

Supports **chained comparisons**:
```python
if 10 < x < 20:  # equivalent to (10 < x and x < 20)
```

---

### ➤ Logical Operators
| Operator | Meaning                  | Example                  | Result   |
|----------|--------------------------|--------------------------|----------|
| `and`    | True if both are true    | `True and False`         | `False`  |
| `or`     | True if at least one is true | `True or False`     | `True`   |
| `not`    | Negates boolean value    | `not True`               | `False`  |

---

### ➤ Assignment Operators

Used to assign and update values: `=`, `+=`, `-=`, `*=`, `/=`, `//=`, etc.

Example:
```python
x = 5
x += 3  # x = x + 3 → 8
```

---

### ➤ Walrus Operator (`:=`)

Introduced in Python 3.8. Assigns and evaluates in one step.

Example:
```python
if (n := len(data)) > 10:
    print(n)
```

---

### ➤ Identity Operators

Compare **memory locations**:
- `is`: True if both variables point to the same object.
- `is not`: True if they do not point to the same object.

---

### ➤ Membership Operators

Check if a value exists in a sequence:
- `in`, `not in`

Examples:
```python
3 in [1, 2, 3]        # → True
'O' in "Python"       # → True
```

---

## 🔹 Python Keywords

These are **reserved words** in Python with predefined meanings. They cannot be used as variable names.

To view all keywords:
```python
import keyword
print(keyword.kwlist)
```


[Cases](![image](https://github.com/user-attachments/assets/e922630c-9a4a-47d8-a6e3-6af522da019d)

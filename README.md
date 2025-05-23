# Character-Display

This Python program demonstrates how to print each character of a string using a `for` loop and string indexing.

---

## 📌 What It Does

- Uses a loop to iterate over each character in the string `"Hello World"`.
- Prints each character one by one **without breaking the line**, maintaining the original string format.

---

## 🧠 How It Works

1. A string variable `s` is initialized with the value `"Hello World"`.
2. A `for` loop runs from index `0` to `len(s) - 1`.
3. Inside the loop, each character at index `i` is printed using `print(s[i], end="")`.
   - The `end=""` ensures that characters are printed on the **same line**.

---

## 🚀 How to Run

Save the code in a Python file, for example, `display-characters.py`, and run:

```bash
python display-characters.py


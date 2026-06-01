# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
r = int(input("Number of rows: "))
for n in range(r):
    print(" " * (r - n), end="")
    m = 1
    for k in range(n + 1):
        print(m, end=" ")
        m = m * (n - k) // (k + 1)
    print()  
```

## Sample Output
<img width="788" height="258" alt="image" src="https://github.com/user-attachments/assets/609550fb-10a3-4356-bb9b-8715f37a7d20" />

## Result
program has been completed successfully

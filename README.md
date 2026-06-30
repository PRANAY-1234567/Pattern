# 📘 README — Reverse Star Pattern Program (Python)

## 📌 Description

This Python program prints a **reverse left-side triangle star pattern** using nested loops.
The number of stars **decreases** in each line.

---

## ⚙️ Code

```python
rows = 5

for i in range(rows, 0, -1):
    for j in range(i):
        print("*", end="")

    print()
```

---

## 🧠 Simple Step-by-Step Explanation

### 1️⃣ Set Number of Rows

```python
rows = 5
```

This means the pattern will have **5 lines**.

---

### 2️⃣ Outer Loop (Controls Rows)

```python
for i in range(rows, 0, -1):
```

* Starts from **5**
* Ends at **1**
* `-1` means the loop runs **backwards**

So stars decrease each line.

---

### 3️⃣ Inner Loop (Print Stars)

```python
for j in range(i):
```

This prints stars based on the value of **i**.

👉 Line 1 → 5 stars
👉 Line 2 → 4 stars
👉 Line 3 → 3 stars

and so on.

---

### 4️⃣ Print Stars in Same Line

```python
print("*", end="")
```

* Keeps stars on the same line
* Without `end=""`, each star would print on a new line.

---

### 5️⃣ Move to Next Line

```python
print()
```

Moves to the next row after printing stars.

---

## ▶️ Output

```
*****
****
***
**
*
```

---

## 🔑 Key Concepts Learned

* Nested loops
* Reverse looping using negative step
* Pattern printing logic
* Use of `end=""`

---

## 🎯 Easy Trick to Remember

👉 Normal pattern → count **1 to n**
👉 Reverse pattern → count **n to 1**

---

## 🚀 Why This is Important

Pattern programs help in:

* Building loop logic
* Improving problem-solving skills
* Preparing for coding interviews

---

<img width="799" height="714" alt="image" src="https://github.com/user-attachments/assets/72109f98-b390-49cc-acab-055aece6524f" />

# 🌳 Binary Tree Traversal Visualization (C++ Graphics)

This project is a graphical simulation of **Binary Tree Traversals** using C++ and the `graphics.h` library. It visually demonstrates how nodes are visited in different traversal methods.

---

## 📌 Features

- 🌿 Visual representation of a binary tree
- 🔵 Node highlighting during traversal
- 📊 Displays traversal order as a list
- 🔁 Supports all major traversals:
  - In-order Traversal
  - Pre-order Traversal
  - Post-order Traversal
- 🎨 Built using classic C++ graphics library (`graphics.h`)

---

## 🧠 Traversal Types Explained

### In-order Traversal
Left → Root → Right

### Pre-order Traversal
Root → Left → Right

### Post-order Traversal
Left → Right → Root

---

## 🛠️ Technologies Used

- C++
- Graphics.h (WinBGIm / Turbo C++ graphics)
- Basic Data Structures (Binary Tree)

---

## 🚀 How to Run

### Step 1: Install graphics.h
Make sure you have `graphics.h` configured (Turbo C++ or WinBGIm).

### Step 2: Compile the program
Using GCC (MinGW setup with graphics support):
```bash
g++ main.cpp -o tree -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

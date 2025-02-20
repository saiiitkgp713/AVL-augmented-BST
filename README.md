# AVL-Augmented Binary Search Tree (BST)

## Overview

This repository contains a **Python implementation of an AVL Tree**, an augmented version of the **Binary Search Tree (BST)** that maintains balance to optimize performance.

### 🔹 Why AVL Trees?
A **conventional BST** can become **skewed** when most values lean heavily toward either the left or right subtree.  
In such cases, operations like **insertion**, **deletion**, and **search** may degrade from **O(log n)** to **O(n)**.

An **AVL Tree** solves this issue by automatically **balancing itself** after every insertion and deletion, ensuring that the time complexity remains **O(log n)**.

### 🔹 Key Features of AVL Trees:
- **Self-Balancing**: Ensures that the height difference between left and right subtrees (balance factor) never exceeds **1**.
- **Improved Efficiency**: Keeps search, insert, and delete operations optimal at **O(log n)**.
- **Automatic Rotations**: Uses **left** and **right rotations** to maintain balance.

## 📌 Learn More
For a basic **Binary Search Tree (BST) implementation**, check out my [Binary Search Tree repository](https://github.com/saiiitkgp713/Binary-Search-Tree/tree/main).

---

### 🚀 Contributions & Improvements
Feel free to contribute by adding:
- **AVL Tree Traversals (Preorder, Postorder, Level-order)**
- **Visualizations of Rotations**
- **Performance Comparisons with Standard BSTs**

# Microproject-DSA
Online Shopping Cart using Doubly Linked List in C — supports adding, deleting, updating, billing, and reverse display of cart items.
# Online Shopping Cart Using Doubly Linked List

## 📌 Project Overview

This microproject implements an **Online Shopping Cart using a Doubly Linked List in C**.

Each node represents one cart item and stores:
- Product ID
- Product Name
- Unit Price
- Quantity

A doubly linked list is used so that cart items can be traversed in both **forward and backward directions**.

## 🎯 Objectives

- Understand the implementation of a Doubly Linked List.
- Store shopping cart items dynamically.
- Perform insertion, deletion, and updating operations.
- Calculate the total shopping bill.
- Display cart items in forward and reverse order.

## ⚙️ Features

1. **Add Item**
   - Adds a new product to the cart.
   - If the product already exists, its quantity is increased.

2. **Delete Item**
   - Removes a product using its Product ID.
   - Updates the `prev` and `next` pointers correctly.

3. **Update Quantity**
   - Updates the quantity of an existing product.

4. **Display Cart**
   - Displays all cart items from head to tail.

5. **Compute Bill**
   - Calculates the total bill using:
   `Unit Price × Quantity`

6. **Display Cart in Reverse**
   - Displays items from tail to head using the `prev` pointer.
   - Shows the most recently added items first.

## 🧠 Data Structure Used

### Doubly Linked List

Each node contains:

```text
+-------------+
| Product ID  |
+-------------+
| Name        |
+-------------+
| Unit Price  |
+-------------+
| Quantity    |
+-------------+
| Prev Pointer|
+-------------+
| Next Pointer|
+-------------+
```

The `prev` pointer points to the previous node, while the `next` pointer points to the next node.

## 🛠️ Technologies Used

- **Programming Language:** C
- **Data Structure:** Doubly Linked List
- **Compiler:** GCC / any standard C compiler

## 📋 Menu Options

```text
===== Shopping Cart Menu =====
1. Add Item
2. Delete Item
3. Update Quantity
4. Display Cart
5. Compute Bill
6. Display Cart in Reverse
7. Exit
==============================
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Open the project folder

```bash
cd <repository-folder>
```

### 3. Compile the program

```bash
gcc shopping_cart.c -o shopping_cart
```

### 4. Run the program

**Windows:**
```bash
shopping_cart.exe
```

**Linux / macOS:**
```bash
./shopping_cart
```

## 📂 Project Structure

```text
Online-Shopping-Cart/
│
├── shopping_cart.c
└── README.md
```

## 📚 Learning Outcomes

Through this project, I learned:

- Dynamic memory allocation using `malloc()` and `free()`
- Structure implementation in C
- Doubly linked list operations
- Node insertion and deletion
- Traversing a linked list
- Using `prev` and `next` pointers
- Implementing a menu-driven C program
- Calculating a shopping bill using linked-list data

## 👩‍💻 Author

**Arpita Raju Taradale**

CSE (AIML) Engineering Student  
DKTE Ichalkaranji

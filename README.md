# 🛒 Quick Mart Billing System – Assembly Language Project

**📚 Course:** Computer Organization Assembly Language  
**📅 Semester:** 3rd Semester  

---

## 📘 Project Overview

This is a menu-driven **billing system** designed in **x86 Assembly Language (TASM or MASM)**. The project simulates a simple purchase process at a fictional store, **Quick Mart**, where the user can:

- Select products from a menu
- Enter quantities
- Apply optional discounts
- View running and final total amounts
- Choose to make additional purchases

---

## ⚙️ Features

- Displays a product catalog with names and prices
- Takes user input for item selection and quantity
- Calculates total price with multiplication logic
- Supports applying a discount amount
- Handles wrong inputs with error prompts
- Allows repeated purchases in one session
- Displays final amount after all purchases

---

## 🧠 Concepts Practiced

- `Macros` for reusable operations like newline, printing, and input
- `PROC` procedures for:
  - Decimal input handling
  - Multiplication and addition
  - Discount subtraction
  - Decimal output conversion
- Register usage: `AX`, `BX`, `CX`, `DX`
- Stack operations: `PUSH`, `POP` for preserving registers
- Loop constructs with `LOOP`, `JMP`, `CMP`, and conditional jumps (`JL`, `JE`, `JNE`)
- Data segment initialization using `mov ax, @data`
- String management using `.data` segment

---

## 🧾 Product List

| No | Item Name            | Price (Rs.) |
|----|----------------------|-------------|
| 1  | Male Shirt Casual    | 1000        |
| 2  | Female Shirt Casual  | 1200        |
| 3  | Male Pant Jeans      | 2000        |
| 4  | Female Pant Jeans    | 1800        |
| 5  | Male Shoes           | 2500        |
| 6  | Female Shoes         | 2500        |
| 7  | Female Kurti         | 1500        |
| 8  | Female Scarf         | 1000        |
| 9  | Male Cap             | 500         |

---

## 🧮 Calculation Flow

1. User selects item by number (1–9)
2. Inputs quantity
3. Program multiplies price × quantity
4. User enters optional discount
5. Program subtracts discount and adds to total
6. Optionally allows more purchases
7. Displays final total amount

---


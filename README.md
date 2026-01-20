# Sandwich Shop

## Overview
**Sandwich Shop** is a Java console application that simulates a real-world sandwich shop ordering system.  
Users can create custom orders with sandwiches, drinks, and chips, and generate a receipt saved to a file.  

This project demonstrates **object-oriented programming (OOP)**, **file I/O**, **console-based user interaction**, and **encapsulation**.

---

## Features

- Build sandwiches with:
  - Choice of bread type: `WHITE`, `WHEAT`, `WRAP`, `RYE`
  - Bread sizes: `FOUR_INCH`, `EIGHT_INCH`, `TWELVE_INCH`
  - Optional toasting
  - Add toppings (meats, cheeses, regular) and sauces
- Add drinks:
  - Select size (`SMALL`, `MEDIUM`, `LARGE`) and flavor (`COKE`, `SPRITE`, etc.)
- Add chips:
  - Select type and quantity
- Checkout and generate a **timestamped receipt file** in the `receipts/` folder
- Dynamically calculates **total price** for all items

---

## Technologies & Concepts

- **Java 17**
- **Maven** for project structure
- **Object-Oriented Programming**: classes, enums, encapsulation, composition
- **File I/O** for saving receipts
- **Console-based UI** using `Scanner` for input
- **Enums and Collections** for structured data management

---

## Classes Overview

| Class | Responsibility |
|-------|----------------|
| `Main` | Entry point; starts the application |
| `UserInterface` | Handles user input and menu navigation |
| `Order` | Stores sandwiches, drinks, chips; calculates total price |
| `Sandwich` | Represents a sandwich; calculates price based on size & toppings |
| `Topping` | Represents a topping or sauce; categorized by type |
| `Drink` | Represents a drink with size and flavor; calculates price |
| `Chips` | Represents chips type and quantity; calculates price |
| `SandwichOrderFileManager` | Writes order summaries to files |

---
## Example Usage

Welcome to Johnny's sandwiches!

New Order

Exit

Select bread, size, toppings, sauces...
Add drinks and chips...
Checkout
Receipt generated: receipts/Order_2025-05-30_03-20-08.txt


**Receipt Example:**


======= ORDER SUMMARY =======
Order Time: 2025-05-30T03:20:08.975542600

Sandwich #1:
FOUR_INCH WHITE (Toasted)
Toppings:

MEAT x1

CHEESE x1

REGULAR x1
Sauces:

Drinks:
Drink #1: SMALL Fanta drink ($2.00)
Chips
Chips #1: 1x DORITOS chips ($1.50)

Total Price: $9.00


---

## Why This Project Stands Out

- Realistic simulation of a **business process**
- Strong focus on **object-oriented principles**
- Extensible: can easily add GUI, database, or online ordering
- Great **resume project** for Java, backend, or software engineering roles

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

Open the project in an IDE (IntelliJ, Eclipse, etc.)

Run the Main class

Follow console instructions to create orders and generate receipts







## Example Usage


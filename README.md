# Supermarket Inventory Management System

A **console-based inventory management program** designed to simulate a **supermarket warehouse stock system**. Built using Java, this application allows users to enter, categorize, and view details about incoming products to a warehouse in real time.

## Purpose

This application aims to **manage and display the current inventory of a supermarket warehouse** by:
- Recording product entries,
- Organizing data by product type,
- Providing real-time insights into stock levels.

## Features

- Add new products to the warehouse stock.
- Track product information:
  - Product name
  - Category (Meat, Fruit, Vegetable)
  - Quantity
  - Unit price
  - Entry date (real-time)
- View a list of all entered products.
- Filter products by category and view total number per category.
- Console interface for interaction and testing.

## Example Use Case
1) A manager inputs 100 kg of apples (Fruit) into the system.

2) The system logs the product with entry date and calculates the category total.

3) A request is made to view all products under "Fruit", and the system displays them accordingly.

![Workflow Diagram](https://github.com/user-attachments/assets/744063ed-37a8-4085-aec2-33ba8eb78b92)

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/market-inventory-java.git
   cd market-inventory-java

2. **Compile the project:**
   ```bash
   javac -d bin src/com/market/*.java

4. **Run the program:**
   ```bash
   java -cp bin com.market.Main

## Project Structure
  ````  
  MarketStock/
  ├── src/
  │ └── com/
  │ └── market/
  │ ├── Product.java
  │ ├── Inventory.java
  │ ├── Main.java
  │ └── [other core classes]
  ├── .gitignore
  ├── README.md
  └── LICENSE
  ````
![image](https://github.com/user-attachments/assets/014e6335-1d03-46f8-8301-b0d50b4420b4)

## Authors

Developed by:

- Dirsehan Başaran

- İzzet Can Korkmaz

- Yusuf Ziya Kural

- Gökmen Veyisoğlu

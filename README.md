# Food-Ordering-System-C
This project is a simple console-based Food Ordering System built in C++. It allows users to place food orders from a predefined hotel menu, calculates the total bill, and processes payment with change calculation.

✨ Features

Displays hotel name and a formatted food menu with prices.

Takes multiple orders (up to 5 dishes) with quantity input.

Uses switch statements to map menu numbers to item names and prices.

Displays a detailed order summary with quantity, item name, unit price, and total price (well-formatted using iomanip).

Calculates grand total for all items.

Accepts payment input, verifies if sufficient, and returns change if applicable.

Handles invalid inputs (e.g., wrong menu choice).

🛠️ Tech Stack

Language: C++

Libraries Used:

<iostream> for input/output

<iomanip> for formatted console output

<string> for item names

📌 How It Works

The program displays the hotel banner and menu.

The user selects the number of dishes to order.

The system asks for dish number and quantity for each order.

An order summary is shown with all details and the grand total.

The user enters the payment amount.

If sufficient → payment is accepted and change is displayed.

If insufficient → the system shows the remaining balance.

🚀 Future Improvements

Add more menu items with categories (e.g., drinks, desserts).

Implement discounts, tax calculation, or service charges.

Save order history to a file.

Add customer details (name, contact).

Convert into a GUI-based system.

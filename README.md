# Super-Market-Billing-System

# Project Overview
The Supermarket Billing System is a Python-based application designed to streamline the billing process in a supermarket. It allows adding multiple items to a cart, calculates the total price, applies discounts based on the total amount, and generates a detailed itemized receipt for the customer.
This project aims to create a simple yet efficient billing system suitable for small supermarkets and retail stores.

Features
&#8226; Multiple Item Processing:
Customers can add multiple items along with their quantities in a single transaction.

&#8226; Discount Application:
Automatic discount based on the total bill amount:

5% discount for totals up to ₹500
10% discount for totals up to ₹1000
15% discount for totals up to ₹3000
20% discount for totals above ₹3000

&#8226; Itemized Receipt:
A clear receipt is generated that includes:

Each product’s name, price, and quantity
Total amount before discount
Discount applied
Final payable amount

&#8226; Customer Information Capture:
The system asks for the customer’s name and phone number to be printed on the receipt.

&#8226; Continuous Processing:
After each transaction, the system asks if there’s another customer, enabling continuous transactions without restarting the program.

 # How It Works
1.Customer Information
The system prompts for the customer's name and phone number.

2.Product List Display
A list of available products and prices is shown.

3.Item Selection
The customer can enter:

Product Name
Quantity
The system calculates the subtotal for each item and adds it to the cart.

4.Discount Calculation
The following discounts apply based on the total bill:

0% discount for amounts below ₹500
5% discount for amounts up to ₹1000
10% discount for amounts up to ₹3000
15% discount for amounts above ₹3000

5.Receipt Generation
After item selection is complete, the system generates a neat receipt containing:

Store Header
Date and Time (can be added with datetime if desired)
Customer Name and Phone Number
Each Item’s Price, Quantity, and Subtotal
Total Amount
Discount Applied
Final Payable Amount

6.Multiple Transactions:

The program can handle consecutive customers in a single run, asking after each receipt whether there is another customer in the queue.

# Technologies Used
Python 3.x for the core logic and implementation.
Datetime Module for generating the current date and time on receipts.

# Assignment — Part 2: Data Structures

**Theme:** Restaurant Menu & Order Management System
**Total Marks:** 25

---

## Overview

A Restaurant Order Management System built entirely using Python's core data structures — lists, dictionaries, and nested combinations of both.

---

## Tasks

### Task 1 — Explore the Menu 
- Print the full menu grouped by category (Starters, Mains, Desserts)
- Show availability status for each item
- Compute total items, total available items, most expensive item
- Print all items priced under ₹150

### Task 2 — Cart Operations 
- Simulate a customer placing an order using a cart (list of dictionaries)
- Add items to cart with availability and existence checks
- Update quantity if item already exists in cart instead of adding duplicate
- Remove items from cart
- Print final Order Summary with Subtotal, GST (5%), and Total Payable

### Task 3 — Inventory Tracker with Deep Copy
- Deep copy inventory using copy.deepcopy() before making changes
- Demonstrate that changing inventory does not affect the backup
- Simulate order fulfilment by deducting cart quantities from inventory
- Print Reorder Alert for items at or below their reorder level
- Print both inventory and backup at the end to confirm deep copy worked

### Task 4 — Daily Sales Log Analysis 
- Print total revenue per day
- Find and print the best selling day
- Find the most ordered item across all orders
- Add a new day to sales_log and reprint updated stats
- Print a numbered list of all orders across all dates using enumerate

---

## File Structure

part2_order_system.ipynb   

---

## Concepts Used

- Nested dictionaries and lists
- Dictionary methods: .items(), .values(), .keys()
- List of dictionaries for cart management
- Functions with parameters
- copy.deepcopy() for independent data backup
- Nested loops for sales log analysis
- Lambda functions with max()
- enumerate() for numbered lists
- String formatting with f-strings

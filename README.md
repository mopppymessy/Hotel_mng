# Hotel Management System Database

A comprehensive relational database system designed for managing hotel operations, including guests, bookings, room services, employee shifts, inventory, and billing.

## Features

- Track room availability, types, and pricing
- Manage guest information and room assignments
- Handle bookings with check-in/out details
- Record guest feedback and maintenance issues
- Maintain supplier and inventory records
- Log room service and dining orders
- Assign departments and shifts to employees
- Generate bills combining bookings and services

## Tables Overview

1. Rooms -Stores room types, availability, and prices  
2. Guest -Guest details and associated room  
3. Booking -Booking info: stay duration, check-in/out  
4. Feedback -Guest feedback and ratings  
5. Supplier -Supplier contacts and bills  
6. Inventory -Stock details and restocking info  
7. RoomService -Guest room service usage  
8. OrderSupplies -Supplier orders and deliveries  
9. DiningOrders -Guest food orders  
10.Department -Hotel departments and staff counts  
11.Shifts -Shift timings and types  
12.Employee -Employee details, department, and shift  
13.Maintenance -Maintenance issues linked to feedback  
14.Billing-Final billing for services and bookings

## Sample Queries

Here are some examples:

- Total room service cost per guest
- Dining item sales analysis
- Guests who used room service more than twice
- Maintenance issues and responsible employees
- Suppliers with late deliveries
- Department salary and average feedback rating

  
## How to Use

1. Execute the SQL scripts to create tables.
2. Insert data using provided SQL insertions.
3. Query the database to manage hotel operations.
4. Run the 'SELECT' and analytical queries to explore relationships, spot trends, or debug logic

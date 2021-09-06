# Inventory Management System

My first project (Inventory Management System) as an ML/AI intern at Elite Techno Groups.

## Description
-  code is written in   "IMS Project 01.ipynb" file
- The other 2  files namely: 
    1) inventory.json - contains the data of 30 products with attributes {name, category, description, price, rating, quantity, discount} & each having a unique ID
    2) sales.json - stores all the sales data recorded so far. Each individual data has its specific transaction_ID and attributes like {Customer(name), Purchased Item, Quantity, Total Amount Paid after discount,  Time(date and time of purchase)}

## Summary of output after running the code
- Running 1st and 2nd cell will print all details of products in inventory for you.
- On running 3rd cell, it will ask Customer Name & Product ID that he wants to purchase. Based on that ID, it will show you the remaining quantity of that product in inventory and will then ask you to enter quantity he/she wants to purchase(must be <= available quantity - for the program to run ahead). Finally it will calculate and print your Total Bill amount along with MRP, Quantity, Discount % & Money saved due to Discount.
- It will accordingly subtract the product quantity from the inventory and update the file. Also, it will add the sales record to sales file with {Customer(name), Purchased Item, Quantity, Total Amount Paid after discount,  Time(date and time of purchase)}.

## Summary of all the funtionalities added
- Calculate total amounnt after subtracting Discount amount.
- Print the Final Bill
- Updates the inventory file after reducing the purchased products.
- Calculate and save in the total bill amount from each Purchase.
- Record the sales data in the json file along  with Date & Time of sale.

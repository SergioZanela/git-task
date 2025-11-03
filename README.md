# Inventory Management System

## Description
# This project is a simple stock management tool for a shoe store.

# The program is designed to:
# - Read shoe data from a text file (`inventory.txt`) and store it as `Shoe` objects.
# - Allow the user to capture (add) a new shoe with details like country, code, product name, cost, and quantity.
# - View all shoes currently loaded, showing each shoe’s details in a readable format.
# - Find the shoe with the lowest quantity in stock and restock it.
# - Search for a shoe by its unique product code.
# - Calculate the total value of each shoe item using `cost * quantity`.
# - Identify the product with the highest quantity and mark it as “for sale”.

# The core of the program is the `Shoe` class, which stores:
# - `country` (where the shoe is from),
# - `code` (the unique product code),
# - `product` (the shoe name/model),
# - `cost` (price per unit),
# - `quantity` (how many units are in stock).

''' The program also includes a menu system that lets the user run different operations, such as viewing stock, restocking, searching by code, and calculating the value per item. '''

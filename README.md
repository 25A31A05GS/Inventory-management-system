# Inventory-management-system
A simple inventory system to manage products and stock.
**ALGORITHM**
Step 1: Start
Begin the program
 Step 2: Initialize
Create an empty list/array to store products
Each product has:
Name
Price
Quantity
 Step 3: Display Menu
Show options to user:
Add Product
View Products
Sell Product
Exit
 Step 4: Take User Choice
Read user input (choice)
 Step 5: Perform Operation
 Case 1: Add Product
Input product name
Input price
Input quantity
Store product in inventory
 Case 2: View Products
If inventory is empty:
Display “No products available”
Else:
Display all product details
 Case 3: Sell Product
Input product name
Input quantity to sell
Search product in inventory
 If found:
If stock is sufficient:
Reduce quantity
Display success message
Else:
Display “Not enough stock”
 If not found:
Display “Product not found”
Case 4: Exit
Stop the program
 Step 6: Repeat
Return to menu until user selects Exit
 Step 7: End
Terminate program


**METHODOLOGY**
1. System Design Approach
The system is designed using a menu-driven approach, where the user selects operations such as adding, viewing, and selling products. The program runs in a loop until the user chooses to exit.
2. Data Structure Used
A structure (struct Product) is used to store product details:
Product Name
Price
Quantity
A dynamic array (vector<Product>) is used to store multiple products in memory.
 This allows flexible storage and easy access to product data.
 3. Functional Modules
 a) Add Product Module
Accepts product name, price, and quantity from the user
Stores the product in the inventory list using push_back()
 b) View Products Module
Checks if inventory is empty
If not empty, displays all products with:
Name
Price
Quantity
 c) Sell Product Module
Takes product name and quantity to sell
Searches for the product in inventory
 If found:
Checks if sufficient quantity is available
Reduces stock accordingly
 If not found:
Displays error message
 d) Menu Control Module (Main Function)
Displays options to the user
Takes input choice
Calls corresponding functions
Repeats until user selects Exit
 4. Control Flow
Program starts
Menu is displayed
User selects an operation
Corresponding function is executed
Control returns to menu
Loop continues until Exit
 5. Input and Output Handling
Input is taken using cin
Output is displayed using cout
 6. Working Principle
The system maintains an in-memory list of products.
All operations (add, view, sell) directly modify or access this list during runtime.
 7. Limitations
Data is not stored permanently (lost after program ends)
No update or delete functionality
Works only in console (no graphical interface)


**FLOWCHART**



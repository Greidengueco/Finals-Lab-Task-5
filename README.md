# [Finals-Lab-Task-5]
- This portfolio demonstrates the use of SQL views, stored procedures, and stored functions to manage and manipulate database data. It covers tasks such as filtering data with views, updating records with stored procedures, and retrieving data using functions.

## Step-by-Step Process:
1. **Setup MySQL Workbench:**

   * Open XAMPP and start the MySQL server.
   * Connect MySQL Workbench to the server.
   * Execute practice queries using the `democodes.sql` file.

2. **Use Inventory Database:**

   * Open the `inventory.sql` file to begin the tasks.

3. **Create Views:**

   * Create a view to display vendor information and products with in-date from 2002 onward.
   * Create a view for products with prices between 100-150.
   * Create a view to compute the total price for products sold by specific vendors.

4. **Create Stored Procedure:**

   * Create a stored procedure that updates the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Create Function:**

   * Create a function that takes vendor code and state as parameters to display product details.

6. **Execute and Document:**

   * Execute the SQL statements and capture screenshots of the commands and outputs.
  
# Screenshots of Codes and Outputs:
### 1. CREATE A VIEW that will display the vendors_code, vendors name, product
description p_indate, of all products with p_indate from 2002 onwards
![1 q](https://github.com/user-attachments/assets/efa408c8-6193-4f0d-ac14-dc31fc5ec0e4)
## Output
![1 PIC](https://github.com/user-attachments/assets/4a71c8d9-deec-4eb7-8d70-3014a73159da)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
![2 Q](https://github.com/user-attachments/assets/f43cbd50-20b7-4be4-8c2c-07848cf499f3)
## Output
![2 PIC](https://github.com/user-attachments/assets/2a81575d-b7db-4610-a582-cba991e6afde)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL
PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with
the following v_code (21344, 23119 and 24288)
![3 Q](https://github.com/user-attachments/assets/95efc293-f151-4e21-b668-ee3a4a17cab7)
## Output
![3 PIC](https://github.com/user-attachments/assets/e8ad26b3-665e-4466-9db2-38e301205f16)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and
UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
![4Q](https://github.com/user-attachments/assets/1a6381fa-5664-4954-a60e-e9e503c12cc0)
## Output
![4 PIC](https://github.com/user-attachments/assets/a96f49a4-b16c-447b-b7b2-654e22f232f9)

### 5. CREATE A Function that will take 2 parameters(v_code and
v_state) and display All the product description and price based on
the parameters passed to the function
![5 Q](https://github.com/user-attachments/assets/cebb31e1-2ef0-47e0-bdf3-0abd63ee76a5)
## Output
![5 PIC](https://github.com/user-attachments/assets/577283ee-59f8-4d06-bc01-df0dcb82add4)

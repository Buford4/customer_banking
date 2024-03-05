# Customer Banking

## Challenge

Creating a customer banking system that will allow the customer (users) to calculate and track interest earned on their savings and CD accounts.

While the application is running, customers (users) will have the ablility to enter their account (savings and CD's) information.

The customer(user) will be able to see the interest earned and be able to view the updated balances after a specified number of months.

## Requirements
## Create the Savings Account Function:

1. The Account class from the Accounts.py file is imported.
2. In the create_savings_account function, an instance of the Account class is created and the balance and interest parameters are passed to the Account class.
3. The interest earned is calculated and assigned to the variable.
4. The savings account balance is updated by adding the interest earned to the balance and assigned to a variable.
5. The updated balance is passed to the set balance method using the instance of the Account class.
6. The interest earned is passed to the set balance method using the instance of the Account class.
7. The updated balance and interest earned are retuned by the function. 

## Create the CD Account Function

1. The Account class from the Accounts.py file is imported.
2. In the create_cd_account function, an istance of the Account class is created and the balance and interest parameters are passed to the Account class.
3. The interest earned is calculated and assigned to a variable.
4. The CD account balance is updated by adding the interest earned to the balance and assigned to a variable.
5. The updated balance is passed to the set balance method using the instance of the Account class.
6. The interest earned is passed to the set balance method using the instance of the Account class.
7. The updated balance and interest earned are returned by the function.

## Create the Main Function

1. The user is prompted to set the savings balance, interest rate, and months for the savings account.
2. Code is written to print out the interest earned and updated savings account balance with interest earned for the given months. The values are formatted to two decimal places and thousandths.
3. The user is prompted to set the savings balance, interest rate, and months for the CD account.
4. Code is written to print ou the interest earned and updated CD account balance with interest earned for the given months. The values are formatted to two decimal places and thousandths.
5. The main function is called to run the program.
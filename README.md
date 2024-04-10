# Bank-Management-System
Program Overview: This C++ program is designed to manage bank accounts. It utilizes classes and file handling to create, display, update, and delete bank account records, as well as handle deposit and withdrawal operations.

Class Definition: The program defines a class account with data members for account number (accno), customer name (cname), account balance (op), and a member function get() to input account details and display() to show account information.

File Handling: It uses the <fstream> library for file handling, allowing it to read from and write to a binary file named "Bank.dat" where account information is stored.

Menu-Driven Interface: The main function presents a menu-driven interface to interact with the program. Users can choose options like creating a new account, displaying all accounts, searching for a specific account, updating account balances, closing an account, depositing money, withdrawing money, and exiting the program.

Functionality:

Create New Account: Users can input customer name and opening balance to create a new account. An account number is generated randomly using rand() function.
Display All Accounts: It reads and displays all account records from the "Bank.dat" file.
Search Specific Customer: Users can search for a specific account by entering the account number.
Set New Opening Balance: Allows users to update the opening balance of an account.
Close Account: Deletes a specific account record from the file.
Deposit Money: Adds an amount to the account balance.
Withdraw Money: Subtracts an amount from the account balance if sufficient funds are available.
Exit Program: Terminates the program execution.
Error Handling: The program includes basic error handling for invalid inputs, insufficient balance during withdrawal, and handling situations where a searched account is not found.

File Operations: For operations like updating, deleting, and maintaining account records, the program utilizes file stream operations such as ifstream, ofstream, and fstream.

Overall, this program provides a basic banking system simulation with functionalities to manage customer accounts and perform essential banking operations.

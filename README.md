# Brainwave__Matrix_Intern
Python_intern
**ATM Interface**
**Description**
This is a simple command-line ATM interface implemented in Python. The program allows users to create accounts, authenticate using a 6-digit PIN, and perform basic banking operations like depositing, withdrawing money, checking account balance, and viewing transaction history.

`**Features**
**Account Creation:** 
  Users can create an account with a 10-digit account number and a 6-digit PIN.
**Authentication:** 
  Users can log in using their account number and PIN, with a maximum of 3 attempts.
**Banking Operations:**
Deposit money into the account.
Withdraw money from the account (with sufficient balance).
Check account balance.
View transaction history (deposits and withdrawals).
**Security:**
  PINs are hashed using the SHA-256 algorithm before storing, ensuring secure authentication.
  
**Technologies Used**
  Python 3

**Usage**
Account Creation: 
  Enter a unique 10-digit account number and create a 6-digit PIN.
Login:
  Log in by entering your account number and PIN. If you enter an incorrect PIN 3 times, access is blocked for that session.
Deposit: 
  Deposit funds into your account.
Withdraw:
  Withdraw funds (as long as the balance is sufficient).
Check Balance:
  View your current account balance.
Transaction History:
  See the history of deposits and withdrawals.
Logout: 
  Log out of your account and return to the main menu.

**EXAMPLE**

=== ATM Menu ===
1. Create Account
2. Login
3. Exit
Choose an option: 1
Enter a new 10-digit account number: 1234567890
Create a 6-digit PIN: ******

Account 1234567890 created successfully.

=== ATM Menu ===
1. Create Account
2. Login
3. Exit
Choose an option: 2
Enter your 10-digit account number: 1234567890
Enter your PIN: ******
Welcome, Account 1234567890!

--- Logged In ---
1. Deposit
2. Withdraw
3. Check Balance
4. View Transaction History
5. Logout
Choose an option: 1
Enter amount to deposit: 1000
Deposited: 1000

...


# CODETECHSOL-Task-2
NAME: Nandu Chandragiri
Company : CODTECH IT SOLUTIONS 
ID : CT12WDRD
DOMAIN : JAVA PROGRAMMING 
DURATION :DEC TO MARCH 2025 
MENTOR : Neela Santhosh Kumar
**Overview of project**
**Project : Online Banking Application By Using Java**

**Overview of the Online Banking System Code**
This Java code implements a basic online banking system with the following functionalities:

**1. User Management:**

Users can create new accounts with unique account numbers generated by the system.
Users can log in using their account number.
The system validates account numbers to prevent unauthorized access.
**2. Account Management:**

Once logged in, users can access an account menu with various options:
Deposit funds into their account.
Withdraw funds from their account (with balance validation to prevent overdrafts).
Transfer funds to other accounts within the system (after verifying recipient account number).
View their current account balance.
View their transaction history (presumably implemented but not shown in the provided code).
Manage personal information (currently allows updating the account holder name).
Logout of the system.
**3. Data Storage:**

The system uses a HashMap named accounts to store account information.
Each account is represented by a BankAccount object, which likely contains details like account number, holder name, balance, and transaction history.
**4. Security Considerations:**

Account numbers are validated during login to prevent unauthorized access.
The code likely needs further enhancements for robust security measures (e.g., password authentication, transaction verification).
**5. Error Handling:**

The code handles invalid user choices and provides informative messages.
It also checks for invalid recipient account numbers during transfers.
Overall, this code provides a foundational online banking system with core functionalities. It can be further extended to include features like:
Secure login with passwords.
Transaction history details.
Multiple account support for a single user.

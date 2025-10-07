<img width="629" height="408" alt="image" src="https://github.com/user-attachments/assets/5b7e100e-0c5f-4ae1-a054-e842df026770" />

🏦 ATM Machine Use Case Diagram – Description

The ATM Machine system allows customers to perform various banking activities securely, while bank staff and systems ensure proper operation, authorization, and maintenance.
👤 Actors and Their Roles

1. Customer
The Customer interacts directly with the ATM to carry out banking transactions such as:
Enter Card and Enter PIN → These steps are part of authentication to verify user identity.
Select Transaction → The customer chooses which operation to perform (withdraw, deposit, check balance, etc.).
Perform Transaction → Includes all financial actions like:
Cash Withdrawal
Deposit
Check Balance
Transfer Funds
Change PIN
Cancel Transaction → Used when a customer decides not to proceed with a transaction.
Print Receipt → Extends transactions to provide a printed record of the operation.

2. Bank System
The Bank System is responsible for backend operations:
Authorize Transaction → Validates the transaction details and customer credentials.
Update Balance → Updates the customer’s account information after each transaction.

3. Technician
The Technician maintains the ATM machine’s physical and technical components:
Refill Cash → Loads new cash into the ATM.
Perform Maintenance → Checks and fixes hardware or software issues.

4. Bank Admin
The Bank Admin oversees operations and ensures all activities are recorded correctly:
Monitor Transactions → Reviews all ATM operations for accuracy and fraud detection.
Generate Reports → Creates performance and usage reports for analysis.

⚙️ Relationships
«include» is used for mandatory processes such as “Enter Card” and “Enter PIN” within “Authenticate Customer.”
«extend» is used for optional actions like “Print Receipt” or “Cancel Transaction.”

📘 Summary
This diagram shows how customers interact with an ATM to perform banking operations, how the bank system handles transaction authorization and balance updates, and how technicians and administrators ensure smooth system performance and security. It provides a complete overview of functional relationships within an ATM system.

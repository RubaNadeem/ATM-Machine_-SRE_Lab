📌 ATM System Use Case Diagram – Description

The ATM System enables interaction between customers, the bank’s backend system, technicians, and bank administrators. This use case diagram illustrates the different actors, their roles, and the system functionalities.

Actors

Customer

Primary actor who interacts with the ATM machine to perform banking transactions.

Use cases:

Authenticate User (includes Enter Card, Enter PIN, Verify PIN)

Cash Withdrawal (includes Update Balance, Print Receipt)

Deposit (includes Update Balance, Print Receipt)

Transfer Funds (includes Update Balance, Print Receipt)

Check Balance (includes Validate Account)

Request Mini Statement

Change PIN

Cancel Transaction (extends all financial transactions)

Card Retention (extends Authentication, triggered after multiple invalid PIN attempts).

Bank System

Provides backend services required for transactions.

Responsibilities:

Validate Account

Verify PIN

Authorize Transaction

Update Balance

Technician

Ensures ATM availability and proper functioning.

Use cases:

Cash Refill

ATM Maintenance (includes Hardware & Software Diagnostics).

Bank Administrator

Oversees system performance and compliance.

Use cases:

Generate Reports

Monitor Transactions

Audit Logs

System Behavior

Authentication Flow

The customer inserts a card and enters a PIN.

The system validates the PIN via the Bank System.

If validation fails multiple times, Card Retention is triggered.

Transaction Flow

After successful authentication, customers can perform withdrawal, deposit, transfer, or balance inquiry.

Each financial transaction requires authorization from the Bank System.

On successful completion, Update Balance and Print Receipt use cases are included.

Non-Financial Services

Customers may request a mini statement, change PIN, or cancel a transaction at any time.

Maintenance & Admin Control

Technicians ensure the ATM remains functional through cash refill and hardware/software diagnostics.

Bank admins supervise system activity, generate reports, and monitor transactions for compliance and fraud detection.

Improvements over Original Diagram

Added missing use cases (Change PIN, Mini Statement, Cancel Transaction, Card Retention).

Refined include/extend relationships for accuracy.

Broke down Authentication into proper sub-processes.

Made Technician and Admin responsibilities more specific.

Linked Bank System correctly for Verify PIN, Validate Account, Authorize, Update Balance.

# OIB-SIP-JAVA-Programming-ATM-Machine
OIB-SIP JAVA Programming ATM Machine

The provided Java program simulates a simple Automated Teller Machine (ATM) system. Let's break down its functionality step by step:
* Variables Initialization
Three integer variables are declared and initialized:

balance: This holds the current balance, initially set to 100,000.
withdraw and deposit: These will store the amounts for withdrawal and deposit operations, respectively.

*Infinite Loop for Menu
An infinite while (true) loop is used to repeatedly show the ATM menu until the user chooses to exit.

Switch Case for Operations
A switch statement is used to perform different actions based on the user's choice.

Case 1: Withdrawal
The user is prompted to enter the amount to withdraw.
The program checks if the balance is sufficient.
If sufficient, the balance is reduced by the withdrawal amount, and a message is displayed.
If insufficient, an error message is shown

Case 2: Deposit
The user is prompted to enter the amount to deposit.
The deposit amount is added to the balance.
A success message is displayed.

Check Balance
The current balance is displayed.
Exit
The program terminates using System.exit(0).

Summary
This program allows a user to perform basic ATM operations such as withdrawing money, depositing money, checking the balance, and exiting the system. The operations are performed inside an infinite loop until the user chooses to exit. The balance is updated based on the user's actions, and appropriate messages are displayed for each operation.

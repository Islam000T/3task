Here is concise documentation of class(Personalaccount)
transaction types:
There are two kinds of transactions you can make:
deposit: Adding money to your account.
withdrawal: Taking money out of your account.
The PersonalAccount Class:

Attributes:

Balance: This shows how much money you currently have in your account.
Account Holder: The name of the person who owns the account.
Account Number: A unique number to identify your account.
Transactions: A list that records every deposit and withdrawal you make.
Inner Class: Amount

This represents a single transaction, storing both the amount of money involved and whether it was a deposit or a withdrawal.
Constructor:

When you create a new account, it sets up your name and account number, starts your balance at zero, and prepares a list for your transactions.
Methods (What You Can Do):

Deposit Money: You can add money to your account, as long as the amount is positive.
Withdraw Money: You can take out money, but only if you have enough in your balance.
Check Balance: You can see how much money you have at any time.
View Account Info: You can get your account holder’s name and account number.
Transaction History: You can print out a list of all your deposits and withdrawals.
How It Works:

Example: You set up an account for "Jones." You deposit 500, withdraw 200, and then try to withdraw 600 (which doesn’t work since you only have 300 left). At the end, it prints out what you did and shows your balance.

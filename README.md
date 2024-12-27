# ATM-Interface-in-Java-Console-Based-Application

 ATM interface in Java involves implementing a simple menu-driven application that allows users to perform basic banking operations such as checking their balance, depositing money, withdrawing money, and exiting the application.

**Class Definition:** 

The ATMInterface class contains methods for handling ATM operations and managing user authentication.

**Attributes:**
balance: Holds the user's account balance.
isAuthenticated: A boolean flag to check if the user is authenticated.

**Methods:**

<hr>

authenticateUser(): Prompts the user to enter a PIN and checks it against a predefined value.
displayMenu(): Displays the ATM menu options.
checkBalance(): Displays the current account balance.
depositMoney(): Allows the user to deposit an amount into their account.
withdrawMoney(): Allows the user to withdraw an amount from their account, checking for sufficient funds.
Main Loop: The start() method handles the main loop of the application, allowing users to select options until they choose to exit.
Main Method: The entry point of the program where an instance of ATMInterface is created and started.


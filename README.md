# ATM-Interface-in-Java-Console-Based-Application
<hr>

ATM interface in Java involves implementing a simple menu-driven application that allows users to perform basic banking operations 
such as checking their balance, depositing money, withdrawing money, and exiting the application.

The ATM Interface in Java is a console-based application designed to simulate the basic operations of an ATM. 
This project includes functionalities such as user authentication, balance inquiry, deposit, withdrawal, and transaction history. 
It is an excellent demonstration of core Java concepts such as classes, methods, arrays, loops, and exception handling. 
This project serves as a practical exercise for applying object-oriented programming principles in real-world scenarios.



**Class Definition:** 
<hr>

The ATMInterface class contains methods for handling ATM operations and managing user authentication.

**Attributes:**
<hr>
<br>
balance: Holds the user's account balance.
isAuthenticated: A boolean flag to check if the user is authenticated.

**Methods:**
<hr>

authenticateUser(): Prompts the user to enter a PIN and checks it against a predefined value.
<br>
displayMenu(): Displays the ATM menu options.
checkBalance(): Displays the current account balance.
depositMoney(): Allows the user to deposit an amount into their account.
withdrawMoney(): Allows the user to withdraw an amount from their account, checking for sufficient funds.
Main Loop: The start() method handles the main loop of the application, allowing users to select options until they choose to exit.
Main Method: The entry point of the program where an instance of ATMInterface is created and started.


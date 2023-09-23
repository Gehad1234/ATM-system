# ATM-system
 (OOP prject with c++)
The C++ code you provided represents a simple ATM (Automated Teller Machine) program. This program allows users to check their balance, deposit funds, and withdraw funds from their account. Here's a breakdown of the code:

1. The `ATM` class:
   - This class encapsulates the ATM functionality. It has a private member variable `balance` to keep track of the account balance.

2. `ATM` constructor:
   - Initializes the `balance` to 0.0 when an `ATM` object is created.

3. `displayMenu` method:
   - Displays the main menu for the ATM program with options to check balance, deposit, withdraw, and exit.

4. `checkBalance` method:
   - Displays the current account balance.

5. `deposit` method:
   - Allows the user to deposit money into their account. It prompts the user for the deposit amount and updates the balance if the amount is valid (greater than 0).

6. `withdraw` method:
   - Allows the user to withdraw money from their account. It prompts the user for the withdrawal amount and updates the balance if the amount is valid (greater than 0 and doesn't exceed the current balance).

7. `run` method:
   - Implements the main program loop.
   - It repeatedly displays the menu, takes user input for their choice, and performs the corresponding action until the user chooses to exit (choice 4).

8. `main` function:
   - Creates an `ATM` object named `atm`.
   - Calls the `run` method of the `atm` object to start the ATM program.

When you run this C++ program, it will simulate a simple ATM interface, allowing you to interact with it to check your balance, deposit funds, withdraw funds, and exit the program.

Make sure to compile and run the code in a C++ development environment to see it in action.

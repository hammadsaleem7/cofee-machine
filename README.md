# cofee-machine

Coffee Shop Interaction Script
Greeting and Name Input:

The script starts by printing a welcome message.
It prompts the user to input their name, which is stored in the variable C_name.
Coffee Menu Display:

It displays the prices for different types of coffee: Espresso ($10), Americano ($15), and Latte ($20).
Initial Coffee Selection:

The user is asked which coffee they would like to have, with options being "Espresso," "Americano," or "Latte."
Price Definition:

The prices for Espresso, Americano, and Latte are assigned to variables E, A, and L respectively.
Transaction Loop:

A while loop is initiated to handle repeated transactions or until the user decides to stop.
Within the loop, the script checks the user's coffee choice:
Espresso:
Prompts the user to insert $10.
Checks if the inserted amount is correct.
If correct, it confirms the coffee is ready; otherwise, it prompts the correct amount again.
Americano:
Prompts the user to insert $15.
Checks if the inserted amount is correct.
If correct, it confirms the coffee is ready; otherwise, it prompts the correct amount again.
Latte:
Prompts the user to insert $20.
Checks if the inserted amount is correct.
If correct, it confirms the coffee is ready; otherwise, it prompts the correct amount again.
If the user types "No," the script thanks the user and ends the transaction.
Invalid Input Handling:

If an incorrect coffee name is entered, the user is prompted to enter a valid coffee name.
Repeat Transaction Prompt:

After each transaction, the user is asked if they want another coffee or to end the session.
If the user types "No," the script ends; if "Yes," it repeats the transaction loop.

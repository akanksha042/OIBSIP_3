# OIBSIP_3
ATM Interface in Java Task 3
This program is an ATM (Automatic Teller Machine) interface program written in Java. It allows users to perform various banking transactions such as withdrawing money, depositing money, checking their account balance, transferring money to another account, and quitting the program.

The program starts by initializing the balance variable to 500000 and creating a Scanner object to read user input. Then, it prompts the user to enter their ATM password.

If the password entered by the user matches the correct password (which is hardcoded as 9594 in this program), the program enters an indefinite loop that displays a menu of options to the user. The user can then choose which operation they want to perform by entering a corresponding number from the menu.

If the user chooses to withdraw money, the program prompts the user to enter the amount to withdraw. If the balance is greater than or equal to the withdrawal amount, the balance is updated by subtracting the withdrawal amount and the program displays a message telling the user to collect their money. Otherwise, the program displays a message indicating that the balance is insufficient.

If the user chooses to deposit money, the program prompts the user to enter the amount to deposit. The balance is then updated by adding the deposit amount and the program displays a message confirming the successful deposit.

If the user chooses to check their account balance, the program displays the current balance.

If the user chooses to transfer money to another account, the program prompts the user to enter the recipient's account number and the amount to transfer. If the transfer amount is less than or equal to the balance, the balance is updated by subtracting the transfer amount and the program displays a message confirming the successful transfer. Otherwise, the program displays a message indicating that the balance is insufficient.

If the user chooses to quit the program, the program displays a farewell message and terminates.

If the user enters an invalid choice, the program displays a message indicating that the input is invalid and prompts the user to choose a valid operation.

Overall, this program simulates the basic functionality of an ATM and provides users with a simple way to perform banking transactions.

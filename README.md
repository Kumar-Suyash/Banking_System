# Banking System in C++
	This is a simple banking system implemented in C++ that allows users to perform basic banking operations like creating an account, depositing money, withdrawing money, checking balance, and closing an account. The application uses file handling to store account data persistently.

# Features:
	->Open a New Account: Users can create a new bank account by providing their first name, last name, and initial   balance.
	->Balance Enquiry: Retrieve the current balance of an account by entering the account number.
	->Deposit Money: Deposit a specified amount into an account.
	->Withdraw Money: Withdraw a specified amount from an account (with a minimum balance restriction).
	->Close an Account: Permanently delete an account.
	->Show All Accounts: Display details of all the accounts.

# Technical Details:
	Language: C++
	->File Handling: Account details are saved and retrieved from a file (Bank.data), ensuring data persistence even ->after the application closes.
	->Exception Handling: The system raises an exception if a withdrawal would cause the balance to drop below the minimum required balance (500).
	->Account Numbers: Auto-incrementing account numbers are assigned to each new account.

# Program Flow
	The user is prompted to select from the following options:
	->Open an account
	->Check balance
	->Deposit money
	->Withdraw money
	->Close an account
	->Show all accounts
	->Quit
	->Depending on the selection, the appropriate action is performed.

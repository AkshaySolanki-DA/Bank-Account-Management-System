Bank Account Management System
A Bank Account Management System implemented in Python 3.13 using Jupyter Notebook. This project demonstrates how to handle account creation, authentication, deposits, withdrawals, transfers, and transaction history with persistent storage using pickle.
✨ Features
•	Account Management: Open accounts, password validation, login/logout
•	Banking Operations: Deposit, Withdraw, Transfer
•	Reports: View account details, Transaction history, Account summary with NumPy
•	Data Persistence: Accounts, credentials, and transactions stored in .pkl files
🛠️ Technologies Used
•	Python 3.13
•	Jupyter Notebook
•	pickle → Data persistence
•	NumPy → Account summaries
•	datetime → Transaction timestamps
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/AkshaySolanki-DA/Bank-Account-Management-System.git
cd bank-account-system
2. Open in Jupyter Notebook
Bank Account Management System.ipynb
3. Run the Notebook and execute all cells to launch the menu.



Menu Options
====== Bank Menu ======
1. Open a new account
2. Login
3. View account details
4. Deposit
5. Withdraw
6. Transfer
7. View transaction history
8. Logout
9. Exit
📂 File Structure
bank-account-system/
│── Bank Account Management System.ipynb   # Jupyter Notebook with code + explanations
│── accounts.pkl                           # Stored account objects
│── transactions.pkl                       # Stored transaction records
│── credentials.pkl                        # Stored usernames & passwords
│── README.md                              # Project documentation
📊 Sample Output
====== Transaction History for Account: 12345678 ======

Date                 Type                 Amount     Balance
------------------------------------------------------------
2025-09-02 14:30:21  Deposit              500.00     1500.00
2025-09-02 15:10:45  Withdraw             200.00     1300.00

====== Account Summary ======
Total Transactions   : 2
Total Deposits       : 500.00
Total Withdrawals    : 200.00
Average Transaction  : 350.00
Current Balance      : 1300.00
📌 Future Improvements
•	Add interest calculation for savings accounts
•	Implement user roles (admin vs. user)
•	Export transaction history to CSV/Excel
•	Add a GUI (Tkinter or PyQt)
🧑‍💻 Author
Developed by [Your Name]. Feel free to fork, modify, and contribute!

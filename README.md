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
<img width="364" height="300" alt="image" src="https://github.com/user-attachments/assets/743a5d20-b418-48a1-9252-7585c4c5197e" />

<img width="651" height="323" alt="image" src="https://github.com/user-attachments/assets/6eb0e8d0-168c-4309-931d-7a6e2edc7ac5" />

📌 Future Improvements
•	Add interest calculation for savings accounts
•	Implement user roles (admin vs. user)
•	Export transaction history to CSV/Excel
•	Add a GUI (Tkinter or PyQt)
🧑‍💻 Author
Developed by [Your Name]. Feel free to fork, modify, and contribute!

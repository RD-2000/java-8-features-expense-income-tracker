# java-8-features-expense-income-tracker

📌 Project Overview
The Wallet Tracker is a simple console-based Java application that helps users manage their money. Users can register, log in, create wallets, add income and expense transactions, and view their transaction history. The project follows a structured approach with different layers (Model, Repository, Service, and Controller) and makes use of Java 8 features like Streams, Optional, and Lambda Expressions.

🌟 Features
✅ User Registration & Login – Secure authentication
✅ Create Wallets – Users can create multiple wallets
✅ Add Transactions – Record income and expenses
✅ View Transaction History – See all transactions in a wallet
✅ Java 8 Features – Uses Streams, Optional, and Lambda expressions

⚙️ How to Install and Run the Project
1️⃣ Requirements
Java 8 or later installed on your computer
A code editor (IntelliJ IDEA, Eclipse, VS Code)
2️⃣ Download or Clone the Project
If you have Git installed, run the following command in the terminal:git clone git@github.com:RD-2000/java-8-features-expense-income-tracker.git
3️⃣ Compile and Run the Project
Open a terminal or command prompt, navigate to the project folder, and run:Navigate to the project directory:
cd core-java-if-booking-project
Open the project in your preferred IDE.
Compile and run the application:
Locate Main.java.
Run the file to start the application.

📌 How to Use the Application
1️⃣ Run the Main class
2️⃣ Register a new user by providing a username and password
3️⃣ Log in with your credentials
4️⃣ Create a wallet and set an initial balance
5️⃣ Add transactions (income or expense) to your wallet
6️⃣ View transactions, income, and expenses for any wallet
7️⃣ Log out and exit the application when done

📌 Project Folder Structure
bash
Copy
Edit
wallet-tracker
│── src/
│   ├── model/            # Data classes (User, Wallet, Transaction)
│   ├── repository/       # Handles data storage (UserRepo, WalletRepo, TransactionRepo)
│   ├── service/          # Business logic (UserService, WalletService, TransactionService)
│   ├── controller/       # User interaction (MainController)
│   ├── Main.java         # Entry point (Main class)
│
└── README.md


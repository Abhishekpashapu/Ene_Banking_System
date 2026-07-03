# 🏦 ENE Banking System

A **console-based banking application** developed using **Core Java** and **Object-Oriented Programming (OOP)** concepts. This project simulates the basic operations of a banking system such as creating accounts, checking balances, depositing money, withdrawing money, and transferring funds between accounts.

---

## 📌 Project Overview

The ENE Banking System is designed to demonstrate the fundamentals of Core Java while following object-oriented programming principles. It provides an interactive menu-driven interface where users can perform common banking operations through the terminal.

This project is suitable for beginners who want to understand how Java classes interact to build a real-world application.

---

## ✨ Features

* ✅ Create Bank Accounts Dynamically
* ✅ Display All Customer Accounts
* ✅ Check Account Balance
* ✅ Deposit Money
* ✅ Withdraw Money
* ✅ Transfer Money Between Accounts
* ✅ Automatic UTR ID Generation
* ✅ Transaction Receipt Generation
* ✅ Duplicate Account Number Validation
* ✅ Sender & Receiver Account Verification
* ✅ Insufficient Balance Validation
* ✅ Menu-Driven Console Application

---

## 🛠️ Technologies Used

* Java 17
* Maven
* IntelliJ IDEA
* Git
* GitHub

---

## 📚 Core Java Concepts Used

* Classes & Objects
* Constructors
* Encapsulation
* Object-Oriented Programming (OOP)
* ArrayList Collection
* Scanner Class
* Methods
* Method Calling
* Object References
* Constructor Injection
* Loops
* Switch Case
* Conditional Statements
* LocalDateTime API
* DateTimeFormatter
* Exception-Free Input Validation

---

## 📂 Project Structure

```text
Ene_Banking_System
│
├── pom.xml
├── README.md
├── .gitignore
│
└── src
    └── main
        └── java
            └── com
                └── Hash
                    ├── Account.java
                    ├── Bank.java
                    ├── Transaction.java
                    └── Main.java
```

---

## ⚙️ Functionalities

### 1️⃣ Create Account

* Create a new customer account
* Store account information
* Prevent duplicate account numbers

---

### 2️⃣ Display All Accounts

Shows complete details of every account including:

* Account Number
* Account Holder Name
* Mobile Number
* Email
* Branch
* IFSC Code
* Account Type
* Balance

---

### 3️⃣ Check Balance

Verify an account number and display the available balance.

---

### 4️⃣ Deposit Money

Deposit money into an existing account and display the updated balance.

---

### 5️⃣ Withdraw Money

Withdraw money from an account after checking the available balance.

---

### 6️⃣ Transfer Money

Transfer money securely between two accounts.

The system performs the following validations:

* Sender Account Verification
* Receiver Account Verification
* Balance Verification
* Invalid Amount Validation
* Same Account Validation

---

### 7️⃣ Transaction Receipt

After every successful transfer, the system generates:

* Unique UTR ID
* Sender Details
* Receiver Details
* Transfer Amount
* Updated Balance

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/Abhishekpashapu/Ene_Banking_System.git
```

### Open the Project

Open the project using IntelliJ IDEA or any Java IDE.

### Build the Project

```bash
mvn clean install
```

### Run the Application

Execute the `Main.java` file.

---

## 💻 Sample Menu

```text
=========================================
        ABC BANK MANAGEMENT SYSTEM
=========================================

1. Create Account
2. Display All Accounts
3. Check Balance
4. Deposit Money
5. Withdraw Money
6. Transfer Money
7. Exit

=========================================
```

---

## 📷 Sample Output

```text
Enter Your Choice : 1

Enter Account Number : 1001
Enter Account Holder Name : Abhi
Enter Mobile Number : 9876543210
Enter Email : abhi@gmail.com
Enter Branch Name : Hyderabad
Enter IFSC Code : SBIN0001234
Enter Account Type : Savings
Enter Initial Balance : 50000

Account Created Successfully
```

---

## 🔐 Transaction Example

```text
Enter Sender Account Number : 1001
Enter Receiver Account Number : 1002
Enter Transfer Amount : 5000

Transaction Successful

UTR ID : UTR20260703153045

Sender Balance : ₹45000.00

Receiver Balance : ₹25000.00
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Core Java Programming
* Object-Oriented Programming
* Console-Based Application Development
* Java Collections
* Banking System Workflow
* Real-World Business Logic
* Code Organization
* Git & GitHub Workflow

---

## 🚀 Future Enhancements

* User Login with PIN
* Account Authentication
* Transaction History
* Mini Statement
* Interest Calculation
* File Handling for Data Storage
* Database Integration using MySQL
* Spring Boot REST APIs
* JavaFX or Swing GUI
* Online Banking Features

---

## 👨‍💻 Author

**Abhishek Pashapu**

GitHub: https://github.com/Abhishekpashapu

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.

It motivates me to build more Java projects and continue learning.

# ATM Management System

A console-based ATM management system developed in C++.

The application simulates basic ATM operations, including user authentication, balance management, withdrawals, deposits, and account balance checking. Client account data is stored persistently in a text file.

## Features

- Secure login using account number and PIN code.
- Quick withdrawal with predefined amounts.
- Normal withdrawal with custom amounts.
- Deposit money into an account.
- Check the current account balance.
- Validate withdrawal amounts.
- Prevent withdrawals exceeding the available balance.
- Update account balances after transactions.
- Store and retrieve client data using a text file.
- Support logout and returning to the login screen.
- Menu-driven console interface.

## Client Information

Each client account contains:

- Account Number
- PIN Code
- Name
- Phone Number
- Account Balance

## Technologies Used

- C++
- Standard Library
- File Handling (`fstream`)
- Vectors (`vector`)
- Structures (`struct`)
- Enumerations (`enum`)
- String Manipulation
- Console Input/Output

## Data Storage

Client account records are stored in a text file named:

`Clients.txt`

Each record is stored as a single line using the following separator:

`#//#`

The application reads client information from the file and updates the stored balance after successful transactions.

## Getting Started

### Prerequisites

To build and run this project, you need:

- A C++ compiler such as GCC or Microsoft Visual C++.
- A C++ development environment such as Visual Studio or Visual Studio Code.

### How to Run

1. Clone the repository:

`git clone https://github.com/Omar-Dev-05/ATM-Management-System.git`

2. Open the project in your preferred C++ IDE.

3. Make sure `Clients.txt` is available in the project directory.

4. Build the project.

5. Run `main.cpp`.

6. Enter a valid account number and PIN code to access the ATM system.

## Main Menu

After successful login, the application provides the following options:

`[1] Quick Withdraw`  
`[2] Normal Withdraw`  
`[3] Deposit`  
`[4] Check Balance`  
`[5] Logout`

## Project Structure

The project is implemented as a C++ console application and includes functionality for:

- Client authentication
- Account balance management
- Quick and normal withdrawals
- Deposits
- Balance checking
- File-based data persistence
- Transaction validation
- ATM menu navigation
- Console-based user interaction

## About the Author

**Omar Abobakr** is a software developer focused on problem-solving and building practical software projects.

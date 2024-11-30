# Advanced ATM Simulation - README

## Overview

The **Advanced ATM Simulation** is a Java-based GUI application that simulates ATM functionality. It allows users to perform various banking operations, such as logging in, checking account balances, depositing and withdrawing money, transferring funds, and viewing transaction history. 

The project is built using **Swing** for the user interface and provides an intuitive, tab-based experience for account management.

---

## Features

1. **User Authentication**:  
   - Login using an account number and PIN.
   - Only valid credentials grant access to the dashboard.

2. **Account Dashboard**:  
   - View account balance in real-time.  
   - Perform deposits and withdrawals securely.

3. **Money Transfers**:  
   - Transfer funds between registered accounts.
   - Validate recipient account and sufficient balance during transactions.

4. **Transaction History**:  
   - Display the last 10 transactions for the logged-in account.
   - Real-time updates after every transaction.

5. **Logout Functionality**:  
   - Securely log out of the system, returning to the login screen.

---

## Technology Stack

- **Language**: Java
- **GUI Library**: Swing
- **Data Storage**: In-memory (using `HashMap` for account details)

---

## Code Structure

### Main Classes

1. **`Account`**:  
   Represents a bank account. Handles core functionalities like deposits, withdrawals, transfers, and transaction history management.

2. **`ATMApplication`**:  
   Manages the graphical user interface and user interactions. Includes the following panels:
   - Login Panel
   - Dashboard Panel
   - Transaction Panel
   - Transaction History Panel

---

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ATM-Simulation.git
   cd ATM-Simulation
   ```
2. Compile and run the program:
   ```bash
   javac ATMApplication.java
   java ATMApplication
   ```

---

## Usage

1. **Login**:  
   Use one of the pre-configured accounts:
   - **Account Number**: `123456`, **PIN**: `1234`
   - **Account Number**: `987654`, **PIN**: `5678`

2. **Perform Transactions**:  
   - Navigate through the tabs to deposit, withdraw, transfer money, or view transaction history.

3. **Logout**:  
   Click the "Logout" button to end the session.

---

## Future Enhancements

- Integration with a database for persistent data storage.
- Multi-language support for broader accessibility.
- Enhanced security with encryption for PINs and transactions.
- Responsive UI for better user experience.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch:  
   ```bash
   git checkout -b feature-name
   ```
3. Commit changes and push to your forked repository.
4. Submit a pull request describing your changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For questions or suggestions, feel free to open an issue or contact me at [swashinier@gmail.com].

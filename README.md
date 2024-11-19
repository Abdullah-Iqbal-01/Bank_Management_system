# Bank_Management_system
 A comprehensive banking system that includes various account types such as BankAccount, SavingsAccount, and CheckingAccount. It supports deposits, withdrawals, and balance tracking, with added functionalities like interest calculation for savings and overdraft limits for checking accounts. The system is designed to manage accounts efficiently while maintaining a user-friendly interface."


Sure! Here's the updated **README.md** file without the License and Author sections:

```markdown
# Bank Management System

A comprehensive and user-friendly banking system built in Python that supports various account types, including BankAccount, SavingsAccount, and CheckingAccount. The system allows for deposits, withdrawals, and balance management, with added functionalities such as interest calculation for savings and overdraft limits for checking accounts.

## Features

- **BankAccount**: Basic banking functionalities such as deposit, withdrawal, and balance tracking.
- **SavingsAccount**: Inherits from BankAccount with the addition of interest rate and interest calculation.
- **CheckingAccount**: Inherits from BankAccount with overdraft limit functionality.
- **Deposit and Withdraw**: Handle deposits and withdrawals with error checking (e.g., insufficient balance, overdraft limit exceeded).
- **Balance Management**: Track the balance of each account and perform balance updates.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bank-management-system.git
   ```

2. Navigate into the project directory:
   ```bash
   cd bank-management-system
   ```

3. Ensure you have Python 3.x installed.

4. Run the `main.py` file to start using the banking system:
   ```bash
   python main.py
   ```

## Usage

- Create instances of the `BankAccount`, `SavingsAccount`, and `CheckingAccount` classes.
- Use the `deposit()` and `withdraw()` methods to modify account balances.
- Call the `get_balance()` method to view the current balance.
- For `SavingsAccount`, use the `calculate_interest()` method to calculate the interest.

## Example Usage

```python
# Example for BankAccount
account = BankAccount("123456", 1000)
account.deposit(500)
account.withdraw(200)
print(account)

# Example for SavingsAccount
savings_account = SavingsAccount("789012", 1000, 0.05)
print(savings_account)
print(f"Interest Earned: {savings_account.calculate_interest()}")
```

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit a pull request with improvements or bug fixes.
```

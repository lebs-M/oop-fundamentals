public class BankAccount {

    private String accountNumber;
    private double balance;

    public BankAccount(String accountNumber, double balance) {
        this.accountNumber = accountNumber;
        this.balance = balance;
    }

    // Add methods
}

Activity
implement behaviour that allows:

Reading the account number.
Reading the balance.
Depositing money.
Withdrawing money.
Rules

A deposit must not be negative.

A withdrawal must not be negative.

A withdrawal must not be greater than the current balance.

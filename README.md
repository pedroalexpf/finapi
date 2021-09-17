## Financial API

---

### Requirements

- Account creation
- Search the customer's bank statement
- It does deposit in the account
- It does a withdrawal from the account
- Search the customer's bank statement by date
- Updates customer account data
- Gets customer account data
- Account removal

---

### Business rules

- Does not allow you to register an account with an existing CPF (social number)
- Does not allow you to deposit into a non-existing account
- Does not allow you to search a statement in a non-existing account
- Does not allow you to withdraw from a non-existing account
- Cannot delete a non-existing account
- Does not allow withdrawal when the balance is insufficient